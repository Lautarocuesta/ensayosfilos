# ensayosfilos
1. Cómo clonar el repositorio
Para empezar a trabajar con el proyecto de la página web de ensayos filosóficos, sigue estos pasos para clonar el repositorio en tu computadora:

1.Abre una terminal o Git Bash.
2.Ejecuta el siguiente comando para clonar el repositorio en tu máquina local:
git clone https://github.com/Lautarocuesta/ensayosfilos.git

Cambia el directorio a la carpeta del repositorio:
cd ensayos-filosoficos

Ahora tienes una copia local del proyecto y puedes comenzar a trabajar en él.

2. Cómo añadir nuevos ensayos o modificar el contenido
Para añadir nuevos ensayos o realizar modificaciones en el contenido existente:

1.Editar ensayos existentes:

-Abre el archivo docs/index.html con un editor de texto o código como VSCode.
-Busca la sección correspondiente al ensayo que deseas modificar.
-Actualiza el texto, enlaces o videos dentro de las etiquetas <section> correspondientes.

3.Añadir un nuevo ensayo:

En el archivo docs/index.html, agrega una nueva sección como esta para el nuevo ensayo:

<section id="ensayo3">
    <h2>Ensayo de Alumno 3</h2>
    <p>Este es el ensayo filosófico del Alumno 3.</p>
    <a href="https://youtube.com/ensayo3">Ver presentación en video</a>
</section>

1.Actualiza el menú de navegación agregando un nuevo enlace para el ensayo:

<li><a href="#ensayo3">Ensayo de Alumno 3</a></li>

4.Guardar y subir cambios:


git add .

git commit -m "Añadido el ensayo del Alumno 3"


git push origin main

3. Cómo hacer deploy de la página en GitHub Pages
Si GitHub Pages ya está configurado, los cambios que hagas en la carpeta docs se publicarán automáticamente. Sin embargo, si necesitas configurar el despliegue, sigue estos pasos:

-Ve a tu repositorio en GitHub.
-Haz clic en Settings.
-Desplázate hasta la sección Pages.
-En Source, selecciona la rama main y la carpeta /docs.
-Haz clic en Save.

Tu sitio se desplegará automáticamente en unos minutos, y podrás acceder a él en una URL como esta:
https://tu-usuario.github.io/ensayos-filosoficos/