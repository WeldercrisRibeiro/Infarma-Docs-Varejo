# Plano de Contas Contábil

## Como criar o plano de contas contábil, vincular aos tipos de operações e ao cadastro de lojas.




## Criando as contas padrões!
1. Acesse em: Controle Fiscal > Arquivo > Plano de Contas Contábil > Cabeçalho: 
Clique em EDITA e verifique se existe algum registro; 
Se existir, basta pular para o próximo passo! 

Se não existir, clique em EDITA e preencha com a descrição: "PLANO DE CONTAS PADRAO" e salve a inclusão devendo ficar desta forma:

![Exemplo Local](./img/plano-de-contas.png)

2. Acesse em Controle Fiscal > Arquivo > Plano de Contas Contábil > Contas: clique em MÁSCARA e preencha a máscara do código com 9.99 e clique no botão PROCESSA

![Exemplo Local](./img/mascara.png)

3. Após a definição do código da máscara, clique em EDITA e clique para incluir as contas contábeis.
Primeiro crie a conta chamada PLC devendo o cadastro da seguinte forma abaixo:

![Exemplo Local](./img/cadastro-plc.png)

Após preencher os dados da primeira conta, clique para salvar e crie uma nova conta chamada PLANO DE CONTAS e defina da seguinte maneira:

![Exemplo Local](./img/cadastro-conta.png)


**⚠️ Não esqueça de marcar na conta PLC, o tipo de conta como Sintético e na conta PLANO DE CONTAS o tipo como analítico⚠️**

## Vinculando ao cadastro de lojas!
Acesse em Controle Fiscal > Arquivo > Lojas > EDITA > Outros dados e vincule o Plano de contas padrão ao cadastro da loja, como mostra a imagem abaixo:

![Exemplo Local](./img/cadastro-loja.png)

## Vinculando as contas aos tipos de operações!

Acesse em Controle Fiscal > Arquivo > Tipo de Operação e clique sob o primeiro tipo de operação uma vez, deixando ele em azul e clique no botão Oper x Conta. ![Exemplo Local](./img/btn-oper.png)

![Exemplo Local](./img/tipooperacao.png)

Clique no botão de inclusão e selecione a conta "PLANO DE CONTAS" do tipo Analítico:

![Exemplo Local](./img/opxconta.png)

Clique para salvar e após a finalização do primeiro Tipo de operação, o mesmo processo deve ser feito para todos os restantes!

> ⚠️ **Observação:** Esse processo pode ser feito tanto no central (para rede de lojas) quando no varejo (para lojas independentes). Irá depender de onde será feito a geração dos arquivos fiscais!

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
npm install
npm start
