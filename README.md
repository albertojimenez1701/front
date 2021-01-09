# front_alberto_jimenez
 Funciona solamente si en Backend/usuarioController.js linea 37:
res.status(200).send({ 'mensaje':'correcto','data':usuarios})
se sustituye por:
res.status(200).send({ usuarios})
