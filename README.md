# Comandos-de-linux

## Comandos Básicos

📂 Enlistar contenido de un directorio
Comando: ls 
Ejemplo:
```bash
ls
```
👤 Saber en qué usuario estás
Comando: whoami
Ejemplo:
```bash
whoami
```
📍 Saber en qué directorio te encuentras
Comando: pwdEjemplo:
```bash
pwd
```

🧹 Limpiar la pantalla
Comando: clear o Ctrl + L
Ejemplo:
```bash
clear
```

📜 Listar permisos y más información de archivos
Comando: ls -l
Ejemplo:
```bash
ls -l
```

🫥 Listar archivos o directorios ocultos
Comando: ls -la
Ejemplo:
```bash
ls -la
```

🔄 Cambiar entre directorios
Comando: cd
Ejemplo:
```bash
cd 
```
⬅️ Retroceder a un directorio anterior
Comando: cd ..
Ejemplo:
```bash
cd ..
```

Gestión de Archivos y Directorios

📝 Crear un archivo vacío
Comando: touch archivo.txt
Ejemplo:
```bash
touch mi_archivo.txt
```

📖 Mostrar el contenido de un archivo
Comando: cat archivo.txt
Ejemplo:
```bash
cat mi_archivo.txt
```


✏️ Editar o crear un archivo
Comando: nano archivo.txt
Ejemplo:
```bash
nano mi_archivo.txt
```


📁 Crear un directorio
Comando: mkdir nuevo_directorio
Ejemplo:
```bash
mkdir proyectos
```


📋 Copiar un archivo
Comando: cp origen destino
Ejemplo:
```bash
cp archivo.txt copia.txt
```


🔄 Mover o renombrar un archivo
Comando: mv origen destinoEjemplo:
```bash
mv archivo.txt nueva_carpeta/
```

❌ Borrar un archivo
Comando: rm archivo.txtEjemplo:
```bash
rm viejo_archivo.txt
```

⚠️ Precaución: Este comando no puede deshacerse.
🗑️ Borrar directorios vacíos
Comando: rmdir directorioEjemplo:
```bash
rmdir carpeta_vacia
```

🚨 Borrar directorios con archivos
Comando: rm -rf directorioEjemplo:
```bash
rm -rf carpeta_contenido
```
⚠️ Precaución: Usa con cuidado, ya que elimina todo dentro del directorio.


Gestión del Sistema
🧹 Eliminar dependencias sobrantes
Comando: apt autoremove
Ejemplo:
```bash
sudo apt autoremove
```

🌐 Conocer la IP del sistema
Comando: hostname -I
Ejemplo:
```bash
hostname -I
```

Permisos y Propiedades

🔐 Cambiar permisos de un archivo
Comando: chmod
Ejemplo:
```bash
chmod 755 archivo.sh
```
📌 Nota:

r (lectura) = 4

w (escritura) = 2

x (ejecución) = 1

👥 Cambiar propietario de un archivo
Comando: chown
Ejemplo:
```bash
sudo chown usuario archivo.txt
```

Búsqueda de Texto
🔍 Buscar texto dentro de un archivo
Comando: grep "patrón" archivo.txt
Ejemplo:
```bash
grep "error" log.txt
```

🗂️ Buscar un archivo o directorio
Comando: find
Ejemplo:
```bash
find /ruta -name archivo.txt
```
