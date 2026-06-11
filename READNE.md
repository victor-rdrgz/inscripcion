# Inscripción

Landing page de inscripción con formulario de registro, página de confirmación y aviso de protección de datos. Desplegada con GitHub Pages sobre dominio propio.

## Demo

🔗 [URL en vivo](https://TU-DOMINIO)

## Características

- Formulario de inscripción con validación en cliente.
- Página de confirmación tras completar el registro.
- Aviso de protección de datos (RGPD).
- Despliegue automático con GitHub Pages y dominio personalizado (CNAME).

## Stack

- HTML
- JavaScript (vanilla)
- GitHub Pages

## Estructura

```
.
├── index.html                 # Página principal con el formulario
├── full.html                  # [describe qué es esta vista]
├── script.js                  # Lógica del formulario / validación
├── inscripcion-completada/    # Página de confirmación
├── proteccion-datos/          # Aviso legal / RGPD
├── abc/                       # [describe qué contiene]
└── CNAME                      # Dominio personalizado
```

## Uso local

Al ser un sitio estático, basta con abrir `index.html` en el navegador, o servirlo localmente:

```bash
python -m http.server 8000
# luego abrir http://localhost:8000
```

## Licencia

MIT
