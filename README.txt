# app_gemini_davpar
Pasos para ejecutar el código

1.   Crear un entorno virtual
    en la terminal, usar los comandos python -m venv env     y    .\env\Scripts\activate
2.  Instalar las librerias necesarias
   Estas librerias vienen en el archivo requirements.txt
   Usar el comando       pip install requests
3.  En la raiz de la carpeta, crear el archivo .env
   En este archivo se introduce lo siguiente
    GEMINI_API_KEY=*tullaveaqui*
    Remplazando lo que esta entre ** por el numero de la llave
    importante no dejar espacios entre el igual y la llave
4. ejecutar el programa
   Para esto se usa el codigo    python .\app_gemini.py 