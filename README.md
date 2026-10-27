# HMPI Pro v6 · Acceso con contraseña

`index.html` está **cifrado (AES-256)**: sin la contraseña no se puede leer ni el código ni la app.

Contraseña inicial: `Caldas-HMPI-2026`  → cámbiala con `generador-clave.html` (guárdalo en privado, NO lo subas a GitHub).

## GitHub
```bash
git init && git add . && git commit -m "HMPI Pro v6 protegido"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/hmpi-pro.git
git push -u origin main
```
## Netlify
Arrastra la carpeta a https://app.netlify.com/drop o importa el repo (Publish directory: `.`).
