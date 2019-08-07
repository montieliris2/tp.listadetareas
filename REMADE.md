<!DOCTYPE html>
<html>
<meta charset="utf-8">
<head>


</head>
<body>

<h1>Lista de tareas</h1>
<ul>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
  <li> <input type="text" size="35" maxlength="50" value="Agregar tarea" name="caja de texto"> <div><span class="ok">Seleccionar</span><span class="ko">Eliminar</span></div></li>
</ul>
<script>
var list = document.querySelector('ul');
 
list.addEventListener('click', function(ev) {
    if(ev.target.className == 'ok')
    {
        ev.target.parentNode.parentNode.classList.remove('ko');
        ev.target.parentNode.parentNode.classList.toggle('ok');
    }else if(ev.target.className == 'ko'){
        ev.target.parentNode.parentNode.classList.remove('ok');
        ev.target.parentNode.parentNode.classList.toggle('ko');
    }
}, false);
 
</script>
</body>
</html>
