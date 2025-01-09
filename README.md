<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card Example</title>
    <!-- Importar Plus Jakarta Sans -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .card-container {
            width: 100%;
            height: 100%;
            padding-right: 12px;
            display: flex; /* Cambié inline-flex a flex */
            justify-content: flex-start;
            align-items: center;
        }

        .profile-image {
            width: 110px;
            height: 110px;
        }

        .info-container {
            display: flex; /* Cambié inline-flex a flex */
            flex-direction: column; /* Asegura que los elementos se apilen verticalmente */
            justify-content: flex-start;
            align-items: flex-start;
            gap: 10px;
        }

        .name-role-container {
            height: 35px;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: flex-start;
            gap: 4px;
        }

        .name {
            color: #110E99;
            font-size: 16px;
            font-weight: 600;
            line-height: 22px;
            word-wrap: break-word;
        }

        .role {
            color: #1E52C2;
            font-size: 12px;
            font-weight: 400;
            line-height: 16px;
            word-wrap: break-word;
        }

        .divider {
            width: 143px;
            height: 0px;
            opacity: 0.6;
            border: 0.8px solid #1E52C2;
        }

        .contact-info {
            display: flex; /* Cambié inline-flex a flex */
            flex-direction: column; /* Asegura que los elementos se apilen verticalmente */
            justify-content: flex-start;
            align-items: flex-start;
            gap: 8px;
        }

        .contact-item {
            display: flex; /* Cambié inline-flex a flex */
            justify-content: flex-start;
            align-items: center;
            gap: 4px;
        }

        .contact-item img {
            width: 12px;
            height: 12px;
        }

        .contact-text {
            color: #121213;
            font-size: 12px;
            font-weight: 400;
            line-height: 16px;
            word-wrap: break-word;
        }
    </style>
</head>
<body>
    <div class="card-container">
        <!-- Imagen de perfil -->
        <img class="profile-image" src="https://raw.githubusercontent.com/elke-hht/imagenes-html-email-signature/45678d05e4170437811e34f9e331e02828c47efe/Logo.png" alt="Profile Picture" />

        <div class="info-container">
            <!-- Nombre y rol -->
            <div class="name-role-container">
                <div class="name">Jessy Hidalgo Cruz</div>
                <div class="role">UX Lead Designer</div>
            </div>

            <!-- Línea divisora -->
            <div class="divider"></div>

            <!-- Información de contacto -->
            <div class="contact-info">
                <div class="contact-item">
                    <img src="https://raw.githubusercontent.com/elke-hht/imagenes-html-email-signature/45678d05e4170437811e34f9e331e02828c47efe/Phone.png" alt="Phone Icon" />
                    <div class="contact-text">+506 8569-8623</div>
                </div>
                <div class="contact-item">
                    <img src="https://raw.githubusercontent.com/elke-hht/imagenes-html-email-signature/45678d05e4170437811e34f9e331e02828c47efe/Email.png" alt="Email Icon" />
                    <div class="contact-text">jessy.cruz@hammerheadtechnology.com</div>
                </div>
                <div class="contact-item">
                    <img src="https://raw.githubusercontent.com/elke-hht/imagenes-html-email-signature/45678d05e4170437811e34f9e331e02828c47efe/Globe.png" alt="Website Icon" />
                    <div class="contact-text">hammerheadtechnology.com</div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
