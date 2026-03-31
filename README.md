# SafeGuard AnyDesk Shield v4.5
### By seendo

---

## 🇪🇸 Español

### Descripción
SafeGuard es una herramienta de privacidad y seguridad de código abierto desarrollada en Python. Está diseñada específicamente para proteger tus archivos locales más sensibles frente a accesos remotos no autorizados o supervisados (como sesiones de AnyDesk o TeamViewer). 

A diferencia de otras aplicaciones de pago, SafeGuard ofrece cifrado de nivel militar y un diseño de interfaz sigiloso estilo *dark loader* de forma completamente gratuita.

### Características Principales
* **Cifrado sin Llaves Físicas (PBKDF2):** No guarda ninguna clave de descifrado en el disco duro. La llave se genera en la memoria RAM usando tu contraseña y se destruye al cerrar el programa.
* **Borrado Seguro Forense:** Antes de ocultar y borrar el archivo original, el sistema lo sobrescribe con datos aleatorios para evitar que pueda ser recuperado con software forense.
* **Registro Cifrado:** La lista de qué archivos tienes ocultos y dónde estaban originalmente está totalmente encriptada.

---

## 🛠️ Modo Sigilo

🇪🇸 **Español:**
Para máxima seguridad, SafeGuard se vuelve invisible (Archivo de Sistema) después de proteger un archivo. Si no lo encuentras en tu carpeta:
1. Abre una terminal (CMD) en la carpeta donde estaba el programa.
2. Ejecuta: `HostNetworkService.exe --show`
3. El archivo volverá a ser visible.

---

🇺🇸 English
Description
SafeGuard is an open-source privacy and security tool developed in Python. It is specifically designed to protect your most sensitive local files from unauthorized or supervised remote access (such as AnyDesk or TeamViewer sessions).

Unlike other paid applications, SafeGuard offers military-grade encryption and a stealthy dark loader style interface design completely free of charge.

Key Features
Keyless Encryption (PBKDF2): It does not store any decryption keys on the hard drive. The key is generated in RAM using your password and is destroyed when the program is closed.
Forensic Secure Wipe: Before hiding and deleting the original file, the system overwrites it with random data to prevent it from being recovered with forensic software.
Encrypted Registry: The list of which files you have hidden and where they were originally located is fully encrypted.

## 🛠️ Stealth Mode
For maximum security, SafeGuard becomes invisible (System File) after protecting a file. If you can't find it in your folder:
1. Open a terminal (CMD) in the folder where the program was located.
2. Run: `HostNetworkService.exe --show`
3. The file will become visible again.