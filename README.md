<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>meu primeiro programa...</title>

<style>
body { background-color: rgb(105, 105, 173);
color:white;
font:normal 20pt arial;}

h1 { color: rgb(255,212,22);
}
</style>
</head>

<body>
    <h1>Hello World!!!</h1>
    <p>Ja livrei da maldição!!</p>
<script>
window.alert('Minha primeira mensagem'); // Janela simples de apresentação..    
window.confirm('Está gostando de JavaScript?'); // Janela com botão ok e cancel...
window.prompt('Qual é o seu nome');  //vai perguntar o nome...

</script>
<body>
</html 
  
  
  
code 2 
  
  
  
  
  <html>


<script>
console.log (' Hello World') ; 
console.log ("Gastos em Janeiro")
salJ = 1500
sanJ =  250
kiJ= 65
moJ = 50
claJ = 80
netJ=  120
laJ = 140
siJ = 200
saldoJ = (salJ - sanJ - kiJ - moJ - claJ - netJ - laJ - siJ);
console.log (saldoJ);
estanegativoJ = (saldoJ < 0)
console.log (estanegativoJ)

if (estanegativoJ) {
    console.log("juros de janeiro")    
    jurosJ = (saldoJ * 0.1)
    console.log (jurosJ)
    saldoJ = (saldoJ - jurosJ)
} else { 
    console.log("Rendimentos em janeiro")
    rendimentosJ =(salJ * 0.005)
    saldoJ = (saldoJ + rendimentosJ)
console.log (rendimentosJ)}
console.log(saldoJ)

console.log ("Gastos em Fevereiro")
salF= 1500
sanF =  250
kiF = 70
moF = 60
claF = 90
netF =  220
laF = 140
siF = 1000
saldoF = (salF - sanF - kiF - moF - claF - netF - laF - siF );
console.log (saldoF);
estanegativoF = (saldoF < 0)
console.log(estanegativoF)
acumuladoano = saldoJ + saldoF

if (estanegativoF) {
    console.log("juros de fevereiro")   
    jurosF = (saldoF * 0.1)
    console.log(jurosF)
    saldoF = (saldoF - jurosF)
} else {
    console.log ("rendimentos de fevreiro")
    rendimentosF = (salF * 0.005)
    saldoF = (saldoF + rendimentosF)
console.log (rendimentosF)}
console.log(saldoF)

console.log ("acumulado de dois meses");
console.log (acumuladoano)

</script>
</html>


