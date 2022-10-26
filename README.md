# unity_motores1
Primer proyecto de la asignatura:  Programación y Motores de Videojuegos

Subir archivos de mas de 100MB a github:
Desde consola, bash por ejemplo:
- git lfs install         (para instalar la herramienta)
- git add .gitattributes  (para crear un fichero que registra los archivos que vamos a subir)
- git lfs track "ruta desde .git al archivo"   (por ejemplo en este caso: "Library\PackageCache\com.unity.toolchain.win-x86_64-linux-x86_64@2.0.2\data~\payload.tar.7z")
- git add .               (debemos adjuntar el .gitattributes y el fichero largo)
- git commit -m "mensaje" (ya se hace como una subida normal, creo que lo que hay apuntado en el .gitattribute es lo que hace con el LFS)
- git push origin develop

y listo.
