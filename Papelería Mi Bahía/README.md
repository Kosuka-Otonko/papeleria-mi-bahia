Papelería Mi Bahía - Sitio web estático

Contenido
- index.html
- Productos.html
- Contacto.html
- test.html (catálogo de prueba)

Instrucciones rápidas para publicar

1) Publicar en GitHub Pages (desde Windows PowerShell):

   - Inicializar repo local y subir a GitHub (reemplaza <Kosuka-Otonko> y <Tienda_Wep>):

     git init
     git add .
     git commit -m "Sitio inicial"
     git branch -M main
     git remote add origin https://github.com/<Kosuka-Otonko>/<Tienda_Wep>.git
     git push -u origin main

   - En GitHub: ve al repositorio > Settings > Pages > Source: selecciona branch `main` y carpeta `/ (root)` y guarda. En unos minutos tu sitio estará disponible en https://<Kosuka-Otonko>.github.io/<Tienda_Wep>/

2) Publicar en Netlify (sin cambiar código):

   - Crea una cuenta en https://app.netlify.com
   - Conecta tu repositorio de GitHub a Netlify y selecciona el repositorio creado.
   - Netlify desplegará automáticamente el sitio. No necesitas comando de build si es estático.

3) Otras opciones rápidas:
   - Usar servicios como Vercel o Firebase Hosting.

Notas
- El formulario de contacto en `Contacto.html` utiliza `mailto:` para abrir el cliente de correo del usuario. Si necesitas envío desde servidor (SMTP), puedo añadir un backend en Node/PHP o configurar un servicio como Formspree.
- Si quieres que haga el push por ti, puedo guiarte con los comandos a ejecutar en PowerShell.
