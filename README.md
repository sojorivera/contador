# Contador Web

Un contador web simple y minimalista construido con HTML, CSS y JavaScript puro. El valor del contador se guarda en un servidor externo, por lo que se mantiene sincronizado incluso si recargas la página o la abres desde otro dispositivo.

## 🔗 Demo en vivo

[Ver el contador funcionando](https://tu-usuario.github.io/contador-web/)

*(Reemplaza el enlace con tu URL real de GitHub Pages)*

## ✨ Características

- Contador persistente: el valor se guarda en un servicio externo (Abacus API), no solo en el navegador.
- Botón para incrementar el conteo con un solo clic.
- Interfaz limpia y responsiva.
- Manejo de errores si falla la conexión con el servidor.

## 🛠️ Tecnologías usadas

- HTML5
- CSS3
- JavaScript (Fetch API)
- [Abacus API](https://abacus.jasoncameron.dev) para almacenamiento del contador

## 🚀 Cómo usarlo localmente

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/contador-web.git
   ```
2. Abre el archivo `index.html` en tu navegador.

No requiere instalación de dependencias ni servidor local.

## 📁 Estructura del proyecto

```
contador-web/
└── index.html
```

## 📌 Notas

El contador utiliza un namespace y una key públicos en la API de Abacus, por lo que el valor es compartido entre todas las personas que visiten la página.

## 📄 Licencia

Este proyecto es de uso libre para fines educativos y personales.
