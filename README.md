# Sistema de Estacionamento 🚗

#### DIO - Trilha .NET - Fundamentos

O projeto é um sistema de estacionamento, para gerenciar os veículos estacionados e realizar operações, como adicionar um veículo, remover um veículo, exibir o valor cobrado durante o período que ficou no estacionamento e listar os veículos.

## Rodando o projeto

Obs.: Para rodar é necessário ter instalado .NET versão 6.0.

```
git clone link
```

Para acessar o Program.cs:
1º Acesse a pasta Desafio
2º Digite no terminal o comando abaixo

```
dotnet run
```

## Classe Estacionamento

O diagrama abaixo mostra como a classe Estacionamento foi organizada.

![Diagrama de classe estacionamento](./Imagens/diagrama_classe_estacionamento.png)

A classe contém três métodos, sendo:
|Métodos |Funcionalidade |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------|
|**AdicionarVeiculo**| Método responsável por receber uma placa digitada pelo usuário e guardar na variável **veiculos**. |
|**RemoverVeiculo** | Método responsável por verificar se um determinado veículo está estacionado, e caso esteja, irá pedir a quantidade de horas que ele permaneceu no estacionamento, e exibir o preço a ser pago.|
|**ListarVeiculos** | Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".|

## Ferramentas utilizadas ⛏️

<img src="./Imagens/DotNet.svg" width="48"> <img src="./Imagens/CS.svg" width="48">
