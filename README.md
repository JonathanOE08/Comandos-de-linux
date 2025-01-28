# Comandos-de-linux

## Comandos Básicos

📂 Enlistar contenido de un directorio
Comando: ls 
<br>
Ejemplo:
```bash
ls
```
👤 Saber en qué usuario estás
Comando: whoami
<br>
Ejemplo:
```bash
whoami
```
📍 Saber en qué directorio te encuentras
Comando: pwd 
<br>
Ejemplo:
```bash
pwd
```

🧹 Limpiar la pantalla
Comando: clear o Ctrl + L
<br>
Ejemplo:
```bash
clear
```

📜 Listar permisos y más información de archivos
Comando: ls -l
<br>
Ejemplo:
```bash
ls -l
```

🫥 Listar archivos o directorios ocultos
Comando: ls -la
<br>
Ejemplo:
```bash
ls -la
```

🔄 Cambiar entre directorios
Comando: cd
<br>
Ejemplo:
```bash
cd 
```
⬅️ Retroceder a un directorio anterior
Comando: cd ..
<br>
Ejemplo:
```bash
cd ..
```

Gestión de Archivos y Directorios

📝 Crear un archivo vacío
Comando: touch archivo.txt
<br>
Ejemplo:
```bash
touch mi_archivo.txt
```

📖 Mostrar el contenido de un archivo
Comando: cat archivo.txt
<br>
Ejemplo:
```bash
cat mi_archivo.txt
```


✏️ Editar o crear un archivo
Comando: nano archivo.txt
<br>
Ejemplo:
```bash
nano mi_archivo.txt
```


📁 Crear un directorio
Comando: mkdir nuevo_directorio
<br>
Ejemplo:
```bash
mkdir proyectos
```


📋 Copiar un archivo
Comando: cp origen destino
<br>
Ejemplo:
```bash
cp archivo.txt copia.txt
```


🔄 Mover o renombrar un archivo
Comando: mv origen destino
<br>
Ejemplo:
```bash
mv archivo.txt nueva_carpeta/
```

❌ Borrar un archivo
Comando: rm archivo.txt
<br>
Ejemplo:
```bash
rm viejo_archivo.txt
```

⚠️ Precaución: Este comando no puede deshacerse.
🗑️ Borrar directorios vacíos
Comando: rmdir directorio
<br>
Ejemplo:
```bash
rmdir carpeta_vacia
```

🚨 Borrar directorios con archivos
Comando: rm -rf directorio
<br>
Ejemplo:
```bash
rm -rf carpeta_contenido
```
⚠️ Precaución: Usa con cuidado, ya que elimina todo dentro del directorio.


Gestión del Sistema
🧹 Eliminar dependencias sobrantes
Comando: apt autoremove
<br>
Ejemplo:
```bash
sudo apt autoremove
```

🌐 Conocer la IP del sistema
Comando: hostname -I
<br>
Ejemplo:
```bash
hostname -I
```

Permisos y Propiedades

🔐 Cambiar permisos de un archivo
Comando: chmod
<br>
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
<br>
Ejemplo:
```bash
sudo chown usuario archivo.txt
```

Búsqueda de Texto
🔍 Buscar texto dentro de un archivo
Comando: grep "patrón" archivo.txt
<br>
Ejemplo:
```bash
grep "error" log.txt
```

🗂️ Buscar un archivo o directorio
Comando: find
<br>
Ejemplo:
```bash
find /ruta -name archivo.txt
```
