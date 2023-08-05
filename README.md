<?php
echo "Welcome To My GAME\n";
while(true){
echo "====== Game Tebak Angka ======\n";
echo "Tebak Sebuah angka antara 1 dan 9!\n";
$computer = rand(1,9);
echo "Masukan Tebakan Mu :";
$player = trim(fgets(STDIN));
if ($player == $computer){
    echo "Menang. Angka Komputer adalah $computer.\n";
    exit;
}else{
    echo "kalah.  Angka Komputer $computer.\n";
}
}
?>
