este trabajo es realizado para aprobar la materia, trata de un logueo a una pagina la cual contiene un juego de atajar penales simple, y una api sobre frases de kanye west

en la primera parte en index, hago la caja de registro, los campos donde se escriben el nombre y la contraseña junto con el boton que ejecuta la funcion registrar y los mensajes de error o exito al loguearse .

luego paso a la parte de script en la cual hice la funcion registrar, revisa que nada este vacio, toma lo que el usuario escriba y tambien verifica si el usuario ya existe y si no existe lo guarda en localstorage, mismo si el usuario le falto un campo por completar le avisa con un mensaje, en un momento creo la clave donde se guarda el usuario. 
si lo toma todo bien salta el mensaje de redirigiendo la cual le puse un tiempo para que pueda ingresar a juego.html con el selftimeout

el else si no funciona seria que el usuario o la contraseña son incorrectos

en el juego.html puse todo el codigo del juego de patear penales, y mismo la direccion de la api de kanye west