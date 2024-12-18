# Problema exemplo:
Uma empresa deseja automatizar o processamento de seus contratos. O processamento de
um contrato consiste em gerar as parcelas a serem pagas para aquele contrato, com base no
número de meses desejado.
###
A empresa utiliza um serviço de pagamento online para realizar o pagamento das parcelas.
Os serviços de pagamento online tipicamente cobram um juro mensal, bem como uma taxa
por pagamento. Por enquanto, o serviço contratado pela empresa é o do Paypal, que aplica
juros simples de 1% a cada parcela, mais uma taxa de pagamento de 2%.
###
Fazer um programa para ler os dados de um contrato (número do contrato, data do contrato,
e valor total do contrato). Em seguida, o programa deve ler o número de meses para
parcelamento do contrato, e daí gerar os registros de parcelas a serem pagas (data e valor),
sendo a primeira parcela a ser paga um mês após a data do contrato, a segunda parcela dois
meses após o contrato e assim por diante. Mostrar os dados das parcelas na tela.

## Exemplo (Saída no console):
![example](https://github.com/user-attachments/assets/b9e18fbd-364d-43f2-b769-cfc84f848917)

## Diagramas:
![Domain layer design (entities)](https://github.com/user-attachments/assets/6956caa7-0ef9-4655-bfa1-7a5f7f55625a)
###
![Service layer design](https://github.com/user-attachments/assets/ae91fd3f-6c8a-44fb-be7b-fd6bd2428fd3)
###
![PaypalService](https://github.com/user-attachments/assets/61e4a701-0a70-426e-b272-07f5f81f116b)
