# Rootpay
Landing page
RootPay · Onboarding (HTML + CSS)

Pantalla de onboarding estática para RootPay: título, subtítulo, logo central y CTA para crear la wallet.
Diseño tipo “móvil” con notch, estilos responsive básicos y fondo con gradientes inspirado en el prototipo de Figma.

1- Cómo ejecutar

Clona o descarga este repositorio.

Abre index.html directamente en tu navegador.

Asegúrate de que la imagen images/logo-rootpay.png esté en la ruta correcta.

2 - Detalles de estilos (styles.css)

Variables de tema en :root (colores, tamaños).

Fondo con gradients  <body> inspirado en el prototipo de Figma:

body {
  background:
    radial-gradient(120% 100% at 0% 0%, #1e0b52 0%, transparent 50%),
    radial-gradient(80% 80% at 100% 0%, #0e103d 0%, transparent 55%),
    var(--bg);
}


Tarjeta flex con altura flexible (.card.phone).

Notch simulado con pseudo-elemento (.card.phone::after).

Tipografías fluidas con clamp().

Imagen central con bordes redondeados y drop-shadow.

CTA (Call To Action) con gradiente y sombra.

Media query @media (max-height:740px) para compactar el layout en pantallas bajas.

3- Vista Previa

<img width="682" height="671" alt="Captura de pantalla 2025-10-01 114409" src="https://github.com/user-attachments/assets/d7b17077-73a5-42f9-be99-d00b962db6f0" />

Licencia

Este proyecto es solo un prototipo de diseño.
Úsalo libremente para demos o pruebas.
