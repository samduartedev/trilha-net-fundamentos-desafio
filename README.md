# Desafio .NET DIO
Desafio proposto pela DIO resolvido.

## Desafio de projeto
Usar conhecimentos adquiridos no módulo de fundamentos, da trilha .NET da DIO.

## Ferramentas
<div style="display: inline_block"><br>
  <img align="center" alt="C#" height="50" width="40" src="https://github.com/user-attachments/assets/c2146a3d-f568-4ae4-9697-74b443714f07">
  <img align="center" alt="VSCode" height="50" width="40" src="https://img.icons8.com/?size=100&id=0OQR1FYCuA9f&format=png&color=000000">

</div>

## Contexto
Contratado para construir um sistema para um estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Proposta
Construir uma classe chamada "Estacionamento", conforme o diagrama abaixo:

![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

A classe contém três variáveis, sendo:

**precoInicial**: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

**precoPorHora**: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

**veiculos**: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

A classe contém três métodos, sendo:

**AdicionarVeiculo**: Método responsável por receber uma placa digitada pelo usuário e guardar na variável **veiculos**.

**RemoverVeiculo**: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: **precoInicial** * **precoPorHora**, exibindo para o usuário.

**ListarVeiculos**: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

Por último, deverá ser feito um menu interativo com as seguintes ações implementadas:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar



