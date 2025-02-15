<h1>Contador Métrico</h1>

<i>O objetivo desse projeto é desenvolver um sistema automatizado para medir a quantidade de fita, fio ou outros materiais que um motor é capaz de enrolar. Para isso, buscamos criar uma solução que possa detectar o movimento do motor e calcular a quantidade de produto que foi processada de forma precisa e confiável. Com essa ferramenta, espera-se simplificar e otimizar processos que dependem da contagem manual desses materiais, proporcionando uma solução mais eficiente e precisa.</i>

<div>
  Para isso, utilizaremos um Teclado Matricial para que o usuário possa definir a quantidade do material que deseja que o motor enrole, um Display para apresentação dos dados ao usuário, uma Relé para acionamento do motor e, por fim, um Sensor de Contagem - Chave Óptica para Encoder 5mm e um Encoder, que serão utilizados como forma de controle para desligar o motor.

  Cada volta do disco do encoder representa uma determinada quantidade de fita enrolada, representada pela variável "X" em centímetros. A variável "Quantidade_Desejada", também em centímetros, representa a quantidade de fita que o usuário deseja que o motor enrole.

  Com base nesses dados, podemos calcular a quantidade de voltas necessárias para atingir a quantidade desejada de fita, utilizando a fórmula "Voltas = X" e, em seguida, a quantidade total de voltas necessárias para atingir a quantidade desejada de fita, utilizando a fórmula "voltas_totais = Quantidade_Desejada / voltas". Dessa forma, será possível contabilizar de forma precisa e eficiente a quantidade de fita enrolada pelo motor.
</div>

</br><h1>Link do Artigo publicado do projeto:</h1> 
https://www.usinainfo.com.br/blog/projeto-contador-de-fio-eletronico-com-arduino/
