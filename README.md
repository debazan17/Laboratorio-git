![Logo Tec](/Imagenes/Tec.png)

# Resumen Laboratorio Github.

**Laboratorio Github.**
Profr. Octavio Navarro.

Grupo: 105.

Alumnos:
- David Elías Bazán C., A01785747
- Jerónimo Ortiz Laresgoiti, A01784793
- Darío Cuahtémoc Peña Mariano, A01785747

Fecha: 
17 de agosto de 2023.

---

## Resumen Laboratorio Github.

**Git:** Es un sistema de control de versiones, que permite a los desarrolladores darle seguimiento a los cambios en su código.

**Github:** Es una plataforma web que permite almacenar de manera remota repositorios.

![Logo Github](/Imagenes/Github.jpg)

### Crear, explorar y operar un repositoriopor Github:

Un repositorio es un espacio centralizado donde se suben, guardan, organizan y descargan archivos informáticos.


**Pasos para utilizar un repositorio:** 
1. Como primer paso, en la terminal de tu dispositivo copiarás e introducirás este texto **"ssh-keygen -t ed25519 -C "youremail@example.c0m"** Es importante mencionar que dentro de estas comillas colocarás la misma dirección de correo electrónico de la cuenta de Github. Este comando sirve para generar llaves de seguridad entre tus actividades y las operaciones de Github.
2. Posterior a eso, te preguntará si deseas configurar una contraseña o no, esta contraseña, en dado caso que desees crearla, te la solicitará cada vez que realices algun procedimiento en tu repositorio.
3. Para poder realizar el punto siguiente, incorpora este comando **"eval "$(ssh-agent -s)"** y ten presente el resultado que arroje este comando para pasos posteriores.
4. Para validar las llaves de SSH deberás ingresar el siguiente comando: **"ssh-add ~/.ssh/id_ed25519"**, pero antes de eso, sustituye **"id_ed25519"** por el resultado que te apareció en el punto 3. De igual forma, copia el resultado que te arrojé el ingresar el comando para utilizarlo en puntos siguientes.
5. Después de estos pasos ve al dashboard de Github (página principal) 

2. Dirígite a la  página web de Github, donde deberás dar clic en el botón "Nuevo" ubicado en el dashboard.
3. Enseguida, te redirigirá a una nueva pantalla donde podrás explorar el repositorio remoto que creaste y predeterminadamente creará dos archivos en tu repositorio, la licencia de tu repositorio y el archivo "Readme", el cual tiene como objetivo ser un medio de presentación/información de tu repositorio para otros usuarios.
3. Para emplear el repositorio remoto deberás crear una carpeta en la biblioteca de tu computadora (de preferencia nombra esta carpeta con una sola palabra, sin signos y sin espacios), después de crearla tendrás que copiar la ruta de acceso de la carpeta y en la terminal de tu dispositvo ingresarás el comando **"cd"** (change directory) junto con la ruta previamente copiada.
4. Posteriormente, en la parte superior derecha de la pantalla de tu repositorio remoto harás clic en "Code" y copiarás la secuencia alfanumérica del apartado SSH.
5. Después, en la terminal de tu dispositivo ingresarás el comando **"git clone"** aunado a la sentencia antes copiada. En dado caso que tras ingresar este comando te aparezca la opción "Are you sure you want to continue connecting (yes/no/[fingerprint])?” escribe "yes".
6. Para subir contenido a tu repositorio remoto deberás agregar los archivos (en formato "Todos los archivos") a la carpeta donde anteriormente copiaste su ruta de acceso, aunado a este proceso deberás ingresar el comando ***"git push"** en tu terminal. 
A continuación te presentaré algunos comandos útiles y su función, ya sea para  agregar, guardar o modificar las actividades y archivos en tus repositorios:
- **Git status:** Como su nombre lo indica, este comando mostrará el estatus actual de lo que estas realizando con Git o en tu terminal.
- **Git add -A:** Exporta los cambios realizados localmente al repositorio remoto.
- **Git commit -m "Mensaje acerca de los cambios que realizaste":** Este comando va después de cada ***"git add -A"*** y se usa muy frecuentemente para indicar los cambios que se han realizado cada que subes algo al repositorio remoto. Generalmente este mensaje es corto y definido.
- **Git push origin main:** Exporta los archivos locales al repositorio remoto.
Los cambios hechos desde la terminal los podrás ver directamente en la pantalla de tu repositorio remoto en Github.