<!DOCTYPE html>
<html>
<head>
    <title>Diagrama de Flujo - Proceso Comercial</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/10.2.4/mermaid.min.js"></script>
</head>
<body>
    <div class="mermaid">
        graph TD;
            A[Cliente potencial conoce el negocio] -->|Canales Digitales (RRSS, SEO, SEM, Email Marketing)| B[Visita la web / Redes sociales];
            A -->|Canales Tradicionales (Ferias, Networking, Revistas)| B;
            B --> C[Contacto Inicial (Formulario, WhatsApp, Email)];
            C -->|Mensaje Automático Inicial| D[Registro en CRM];
            C -->|Respuesta Personalizada| E[Agendar Reunión / Demo];
            E --> F[Envío de Propuesta Personalizada];
            F --> G[Seguimiento por Email / WhatsApp];
            G -->|Acepta la propuesta| H[Formalización de Compra];
            H -->|Pago Online (Stripe, PayPal, Transferencia)| I[Confirmación de Compra];
            H -->|Firma Digital (DocuSign)| I;
            I --> J[Entrega del Producto / Servicio];
    </div>
    <script>
        mermaid.initialize({ startOnLoad: true });
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script type="module">
        import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
        mermaid.initialize({ startOnLoad: true });
    </script>
</head>
<body>
    <div class="mermaid">
        graph TD;
        A[Inicio] --> B[Proceso];
        B --> C[Fin];
    </div>
</body>
</html>

