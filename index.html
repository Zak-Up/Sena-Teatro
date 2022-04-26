
<!DOCTYPE html>
<html>
<!-- Presentado por: Jefferson Andres Restrepo Salas
    Instructora: Erly Trinidad Cruz
    Evidencia: 4
    Curso: Sena Desarrollo web con PHP-->
<head>
    <title>Evidencia 4</title>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <link rel="stylesheet" type="text/css" href="./assets/style.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;600;700;800&display=swap">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Krona+One&display=swap">
</head>
<h1>SALA DE CINE</h1>
<?php

//Se requieren las funciones para imprimir el escenario y para enviar las acciones del usuario
require("./assets/escenario.php");
require("./assets/accion.php");
//Se ejecuta el if cuando el usuario envie la informacion del formulario
if(isset($_REQUEST["Enviar"])){
                //Se captura la información enviada del formulario
                $fila = $_POST['fila'];
                $puesto= $_POST['puesto'];
                $accion= $_POST['accion'];
                $StringEscenario=$_POST['lista'];
                //El String generado en el input oculto se convierte en un Array
                $count=0;
                for($i=0;$i<5;$i++){
                    for($j=0;$j<5;$j++){
                        $count=5*$i+$j;
                        //Captura cada elemento del Array extrayendo dicho elemento del String
                        $lista[$i][$j]=substr($StringEscenario,$count,1);
                    }
                    $count=0;
                }
        //Se devuelve el Array con la información modificada por el usuario
        $lista=Accion($fila,$puesto,$accion,$lista);
        //Se ejecuta la funcion para mostrar el Escenario, dado el Array modificado
        Escenario($lista);
}
//Se ejecuta el else if cuando el usario borra la informacion del formulario y cuando se carga la página
else if(isset($_REQUEST["Reset"]) || !isset($_REQUEST["Enviar"])){
    $lista=array(array("L","L","L","L","L"),array("L","L","L","L","L"),array("L","L","L","L","L"),array("L","L","L","L","L"),array("L","L","L","L","L"));
    Escenario($lista);
}
?>
    
<body>
        <div class="form">
        <form method="POST" class="sala_form">
            <!-- Se separa el array $lista en un String y de oculta-->
            <div>
                <table style="margin:auto;">
                <input type="hidden" name="lista" value="<?php foreach ($lista as $fila) {foreach ($fila as $puesto){echo $puesto;}}?>"  />
                </table>
            </div>

            
            <div class="form-details">

                <div class="input-box label">
                <span class="fila details">Fila: </span>
                    <input type="text" name="fila" size="4">
                </div>

                <br>

                <div class="imput-box label">
                <span class="puesto details">Puesto:</span>
				    <input type="text" name="puesto" size="4">
                </div>

                <br>

                <div class="estado">
                <span class="estado">Reservar: </span>
                <td>
                    <input type="radio" name="accion" value="R" />
                </td>
                </tr>
                <tr>
                <span class="estado">Comprar: </span>
                <td>
                    <input type="radio" name="accion" value="V" />
                </td>
                </tr>
                <tr>
                <span class="estado">Liberar: </span>
                <td>
                    <input type="radio" name="accion" value="L" checked="checked" />
                </td>
                </tr>
                
            </div>

                <br>
                
            <!-- botones -->
                <div class="button">
                
                    <input type="submit" value="Enviar" name="Enviar" />
                
                <br><br>

                    <input type="submit" value="Borrar" name="Reset" />
                
                </div>
        
            </div>
        </form>
        </div>
    
</body>
