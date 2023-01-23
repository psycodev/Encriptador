# Encriptador
un encriptador creado para oracle one
un encriptador que tiene 4 funciones en cada boton con el fin de demostrar lo aprendido en el oracle one
actualizacion:
en un principio habiamos utilizado esta funcion para copiar al portapaples
"var texto = document.getElementById("encriptado")
        texto.select(); 
        texto.setSelectionRange(0,9999);
        document.execCommand('copy');
        alert("texto copiado al portapapeles")
        
    }"

pero nos encontramos el problema de que esto ya no era funcional en chrome por cuestiones de seguridad, depues de ua ardua investigacion encontramos otras herramientas para trabajar este componente

trabajamos con los objetos
ClipboardEvent y DataTransfer para poder hacer el respectivo copiado al portapapeles

el try catch es para poder generar una respuestas syncronica y no alla fallos a la espera de la informacion
