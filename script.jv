function hacerclic(){ 
    var lista=document.querySelectorAll("#cont"); 
    for(var f=0; f<lista.length; f++){ 
    lista[f].onclick=ConfirmDemo; 
    } 
   } 
   function ConfirmDemo() {
    //Ingresamos un mensaje
    var mensaje = confirm("Datos de contacto:\nmail: agfrenedoso@gmail.com \ntel:1155667788 ");
    //Verificamos si el usuario acepto el mensaje
    if (mensaje) {
    alert("¡Gracias por confirmar!");
    }
    //Verificamos si el usuario denegó el mensaje
    else {
    alert("¡Haz denegado el mensaje!");
    }
   } 
window.onload=hacerclic;
