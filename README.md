# Aula_PHP_OK


<?php

$NOTA1 = 1;
$NOTA2 = 5; 
$NOTA3 = 6;
$MEDIA = (($NOTA1 + $NOTA2 + $NOTA3)/3); 

if ($MEDIA >=7){
  ECHO"APROVADO";}

elseif (($MEDIA<7) && ($MEDIA >= 4)) {
  ECHO "PROVA FINAL";
}
else {
    ECHO "REPROVADO";

}

?>
