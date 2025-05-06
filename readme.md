para el POST del usuario
http://localhost:3000/usuario (Aqui se prueba la informacion del usuario) 

{
  "nombre": "Juan villanueva",
  "credito": 185,
  "costoEnvio": 10.5,
  "enviosDisponibles": 50
} //Body en el thunder


para el GET del usuario
http://localhost:3000/usuario/6819270264a8a86fabb3e81c/creditos 



para el POST
http://localhost:3000/envios // para ingresar el envio 

{
  "usuarioId": "6819270264a8a86fabb3e81c",
  "nombre": "Juan villanueva",
  "direccion": "Ciudad pacifica",
  "telefono": "70555497",
  "referencia": "Frente al restaurante pollo campero",
  "observacion": "Frágil",
  "producto": {
    "descripcion": "PC Gamer",
    "peso": 2.5,
    "bultos": 1,
    "fecha_entrega": "2025-05-14"
  }
} //Body en el thunder

para el GET de envios
http://localhost:3000/envios/681928cc64a8a86fabb3e82e //   --- envios/ID, depende de la ID

para el DELETE de envios 
http://localhost:3000/envios/ID //La id depende de la que de en el post
ejemplo : "681928cc64a8a86fabb3e82e" esta me dio a mi, puede probar con esa le deberia de funcionar.

