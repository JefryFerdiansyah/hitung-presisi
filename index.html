<?php
error_reporting(E_ALL);
ini_set('display_errors', 1);

$b = $e = $f = $g = $h = null;
$hasil = [];
$a = [];

if ($_SERVER["REQUEST_METHOD"] == "POST") {

    for ($i = 0; $i < 10; $i++) {
        if (!isset($_POST["a$i"]) || $_POST["a$i"] === "") {
            die("Semua angka harus diisi!");
        }
        $a[$i] = round(floatval($_POST["a$i"]), 3);
    }

    // b = rata-rata
    $sum = array_sum($a);
    $b = round($sum / 10, 3);

    $e = 0;

    for ($i = 0; $i < 10; $i++) {
        $c = $b - $a[$i];
        $d = $c * $c;
        $e += $d;

        $hasil[] = [
            "a" => $a[$i],
            "c" => $c,
            "d" => $d
        ];
    }

    // f = varian
    $f = $e / 10;

    // g = akar varian
    $g = sqrt($f);

    // h = evaluasi
    $h = 2 * $g;
}
?>
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8" name="viewport" content="width=device-width, initial-scale=1.0">
<title>Statistik 10 Data</title>

<style>
* {
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg,#4facfe,#00f2fe);
    margin:0;
    padding:15px;
}

.container{
    background:white;
    padding:20px;
    max-width:600px;
    margin:auto;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,.15);
}

h2{
    text-align:center;
    margin-bottom:15px;
}

#inputs{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:10px;
    margin-bottom:15px;
}

input{
    padding:12px;
    font-size:16px;
    border-radius:8px;
    border:1px solid #ccc;
    width:100%;
}

button{
    width:100%;
    padding:14px;
    font-size:16px;
    background:#4facfe;
    color:white;
    border:none;
    border-radius:10px;
    cursor:pointer;
}

button:hover{
    background:#2f80ed;
}

.result{
    background:#f6f9ff;
    padding:12px;
    border-radius:10px;
    margin-top:10px;
}

table{
    width:100%;
    border-collapse:collapse;
    margin-top:15px;
    font-size:14px;
}

th{
    background:#4facfe;
    color:white;
}

th,td{
    border:1px solid #ddd;
    padding:6px;
    text-align:center;
}

.table-wrapper{
    overflow-x:auto;
}

/* HP kecil */
@media(max-width:480px){
    #inputs{
        grid-template-columns:1fr;
    }
}
</style>

</head>

<body>

<div class="container">
<h2>Perhitungan Presisi Timbangan Mingguan SEMISOLID</h2>

<form method="POST">

<div id="inputs">
<?php
for($i=0;$i<10;$i++){
    $value = isset($_POST["a$i"]) ? $_POST["a$i"] : "";
    echo "<input type='number' step='0.001' name='a$i' placeholder='Hasil Timbang ".($i+1)."' value='$value'>";
}
?>
</div>

<button type="submit">Hitung</button>
</form>

<?php 
error_reporting(E_ALL);
ini_set('display_errors', 1);

if(isset($b)): ?>

<p><b>b (Rata-rata):</b> <?= number_format($b,3) ?></p>

<div class="table-wrapper">
<table>
<thead>
<tr>
<th>a</th>
<th>c = b-a</th>
<th>d = c²</th>
</tr>
</thead>
<tbody>
<?php foreach($hasil as $row): ?>
<tr>
<td><?= $row["a"] ?></td>
<td><?= number_format($row["c"],3) ?></td>
<td><?= number_format($row["d"],6) ?></td>
</tr>
<?php endforeach; ?>
</tbody>
</table>
</div>

<div class="result">
<p><b>e (Σ d):</b> <?= number_format($e,6) ?></p>
<p><b>f (Varian):</b> <?= number_format($f,7) ?></p>
<p><b>g (√f):</b> <?= number_format($g,7) ?></p>
<p><b>h (Evaluasi):</b> <?= number_format($h,7) ?></p>
</div>

<?php endif; ?>

</div>
</body>
</html>
