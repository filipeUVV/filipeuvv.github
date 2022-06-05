https://Filipe-Ferreira-trabalho.filipeferreir15.repl.co

Um sorteio em nome para ganhar um brinde

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=6.0">
    <title>sorteio</title>

   <link rel="stylesheet" href="main.css">
    <link rel="stylesheet" href="index.css">
    <link rel="stylesheet" href="indexPC.css">
   

    <link href="https://fonts.googleapis.com/css2?family=Archivo:wght@400;700&amp;family=Poppins:wght@400;600&amp;display=swap" rel="stylesheet">
</head>
<body id="page-landing">
    
    <div id="container">

        <div class="--color-primary-lighter">
            
            <h1>Sorteio</h1>

            <p>Quem ganhar não vai perder, e quem perder não vai ganhar.</p>
        </div>

        <div class=--color-primary-lighter">

            <div class="dados">
       
    <p class="Participantes-nome">NOME DOS PARTIPANTES: <input type="text" id="participantes" class="participantes" > </p>
      
            <div class="alinhar">
     
       <select name="qtdParticipantes" id="qtdParticipantes" >
       
        <option>participantes</option>
        
       
        </select>

       <input type="button"  value="Adicionar" onclick="adicionar()">

         </div>
     </div>
