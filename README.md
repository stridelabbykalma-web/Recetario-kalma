# Recetario Kalma

Herramienta para rellenar las recetas del talonario PDF del Col·legi Oficial de Podòlegs de Catalunya, descargarlas o enviarlas por WhatsApp.

- La página (`index.html`) está cifrada con contraseña (StatiCrypt, AES-256). Sin la contraseña no se puede leer.
- El talonario PDF, el registro de recetas, las plantillas y la firma se guardan solo en el navegador de cada dispositivo. No se suben a este repositorio.
- `lib/` contiene pdf-lib 1.17.1 y pdf.js 3.11.174.
