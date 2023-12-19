# Sistema de Estacionamento 🚗
#### DIO - Trilha .NET - Fundamentos
O projeto é um sistema para estacionamento, para gerenciar os veículos estacionados e realizar operações, como adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Classe Estacionamento
O diagrama abaixo mostra como a classe Estacionamento foi organizada.

![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)


A classe contém três métodos, sendo:
|Métodos             |Funcionalidade                                                                                                                          |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------|
|**AdicionarVeiculo**| Método responsável por receber uma placa digitada pelo usuário e guardar na variável **veiculos**.                                     |
|**RemoverVeiculo**  | Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento, e exibir o preço a ser pago.| 
|**ListarVeiculos**  | Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".|

Será exibido um menu suspenso para o usuário escolher o que deseja acionar.
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

