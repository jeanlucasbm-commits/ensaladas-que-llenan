# Ensaladas que Llenan — landing

Landing estática (HTML + CSS + JS, sin build) para la prueba de humo de la guía "Ensaladas que Llenan" ($19.999 COP, pago por Nequi o llave vía WhatsApp).

## Antes de pautar
- En `index.html`, busca `const WHATSAPP` y pon tu número (ej. `573001234567`).
- Responde la pregunta frecuente "¿Cuándo recibo la guía?" (`[DEFINIR]`).
- Pega el código del Meta Pixel donde dice `Meta Pixel` en el `<head>`. Cada clic en un botón de WhatsApp dispara `InitiateCheckout`.

## Despliegue
Vercel lo publica tal cual: framework "Other", sin comando de build, carpeta raíz `/`.
