# Actividad Python Final

1. Abrir la terminal de Git Bash o terminal en Linux. En Windows, debe ser como administrador.

2. Crear una carpeta o directorio:

   mkdir python-final

3. Entrar en la carpeta creada:

   cd python-final

4. Iniciar el repositorio Git:

   git init

5. Crear un archivo:

   touch finales.py

6. Abrir Visual Studio Code en la carpeta actual:

   code .

7. Verificar la versión de Python instalada:

   python -V
   python3 -V

8. Crear el entorno virtual de Python:

   python3 -m venv venv

9. Activar el entorno virtual:

   - En Linux:

     source venv/bin/activate

   - En Windows:

     venv\Scripts\activate

10. Actualizar pip:

    python3 -m pip install --upgrade pip

---

## 11. ¿Qué es pip y por qué lo actualizamos?

_pip es un sistema de gestión de paquetes que permite instalar, desinstalar y actualizar paquetes de software, especialmente aquellos disponibles en el Índice de Paquetes de Python (PyPI). Básicamente, facilita la gestión de bibliotecas y dependencias en proyectos Python._

_se actualiza pip para acceder a nuevas funciones, compatibilidad con versiones más recientes de paquetes, y para solucionar errores y vulnerabilidades de seguridad. Mantener pip actualizado es importante para asegurar que el gestor de paquetes funcione correctamente y que se puedan instalar las últimas versiones de las librerías necesarias para los proyectos._