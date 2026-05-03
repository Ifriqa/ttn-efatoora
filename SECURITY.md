# Security Policy

## Official distribution channels

TTN e-Fatoora is distributed only through:

- https://ifriqa.com/products/ttn-efatoora
- https://github.com/Ifriqa/ttn-efatoora/releases

Do not install binaries received from unofficial mirrors, messaging apps, or email attachments.

## Updates

TTN e-Fatoora uses Tauri updater artifacts. Update metadata and packages are checked with the embedded updater public key before installation.

The application uses `installMode: quiet` for updates triggered explicitly from inside the application.

## Windows code signing

Public production installers should be signed by **MG Nova Technology** using a trusted Windows code-signing certificate.

Until code signing is active, Windows may show SmartScreen or unknown publisher warnings.

## Reporting security issues

Please report security issues privately to:

contact@ifriqa.com

Do not open a public GitHub issue for vulnerabilities.
