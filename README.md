## 📊 Visão Geral
Este projeto visa a análise exploratória de um dataset de marketing bancário com foco em identificar os fatores que influenciam a compra de títulos financeiros pelos clientes. A análise considera características socioeconômicas, interações com o banco e a situação financeira de cada cliente.

## 📂 Dataset
O dataset contém informações detalhadas sobre os clientes de um banco e sua interação com os produtos financeiros. As colunas incluem:

- **Cliente_Comprou_o_Título?**: Se o cliente comprou ou não o título.
- **Idade**: A idade do cliente.
- **Profissão**: A profissão atual do cliente.
- **Estado_Civil**: Estado civil (casado, solteiro ou divorciado).
- **Formação**: Nível de educação.
- **Cliente_Devedor?**: Se o cliente tem dívidas com o banco.
- **Saldo_Conta_Corrente**: Saldo atual da conta corrente.
- **Tem_Hipoteca?**: Se o cliente tem uma hipoteca.
- **Tem_Emprestimo?**: Se o cliente tem um empréstimo ativo.
- **Qte_de_Ligações_Feitas**: Quantidade de ligações feitas pelo banco para o cliente.

### 🔍 Acesso ao Dataset
O dataset utilizado para esta análise está disponível na pasta data/.

## 👤 Análise Demográfica dos Clientes
A análise demográfica foi realizada para entender o perfil dos clientes que compraram títulos. Aqui estão os principais insights:

### 1. Faixa Etária:
- **75%** dos clientes têm **até 49 anos**.
- A maior concentração está na faixa de **28 a 42 anos**, representando **52,26%**.
- **Clientes com 60 anos ou mais** apresentam as maiores taxas de compra do ativo.

![image](https://github.com/user-attachments/assets/1fc74c50-97bd-427f-aa61-ac5a93290b3c)
![image](https://github.com/user-attachments/assets/2985b6d0-f26d-462f-ae18-756a3631d13b)


### 2. Nível de Escolaridade:
- **61,8%** dos clientes possuem **Ensino Médio completo**.
- **13,08%** possuem apenas **Ensino Fundamental**.
- **Clientes com ensino superior** apresentaram as maiores taxas de compra do ativo.

![image](https://github.com/user-attachments/assets/431475db-06cd-491a-863b-56076ee29631)


### 3. Profissões Predominantes:
- Mais de **80%** dos clientes atuam nas profissões de **Administrador, Operário, Técnico, Serviços Gerais** e **Aposentado**.
- **Administradores** representam a maior prevalência, com **35,13%**.
- **Estudantes e aposentados** mostraram as maiores taxas de compra do ativo.

![image](https://github.com/user-attachments/assets/4f002601-e35d-43b2-9e99-23a72fa63ba9)


### 4. Estado Civil:
- **56,47%** dos clientes são **casados**.
- **Clientes solteiros** apresentam as maiores taxas de compra do ativo.

![image](https://github.com/user-attachments/assets/0df5858a-6766-4218-8fd3-3557c00906be)


## 💼 Impacto da Situação Financeira
A relação entre a situação financeira do cliente e a compra de títulos foi avaliada. Os resultados mostraram que:

### 5. Saldo em Conta Corrente:
- A grande maioria (**83,87%**) dos clientes possuem saldo de até **R$ 3.000,00**.
- Mais da metade (**58,44%**) têm saldo de até **R$ 1.000,00**, indicando um perfil de clientes com saldo relativamente baixo.
- **Clientes com mais de R$ 3.000,00 de saldo** em conta corrente apresentam maiores taxas de compra.

![image](https://github.com/user-attachments/assets/c5f050f6-e460-4644-8f64-2160480af2df)


### 6. Dívidas e Empréstimos:
- **99,33%** dos clientes **não possuem dívidas ativas**.
- **54,32%** dos clientes **não possuem hipotecas**.
- **88,36%** dos clientes **não possuem empréstimos**.
- **Clientes que não possuem hipoteca nem empréstimo** mostraram as maiores taxas de compra.

![image](https://github.com/user-attachments/assets/2dd312ad-24c6-4123-be31-194fbfe1fcb3)
![image](https://github.com/user-attachments/assets/bd9efbb2-e50d-4a8e-9824-9c9cc75678da)
![image](https://github.com/user-attachments/assets/004d2ee3-b15a-45ce-8f54-71bbf01a4103)


## 📞 Análise das Interações com o Cliente
Analisamos também as interações realizadas pelo banco:

### 7. Relacionamento com o Banco:
- **82,42%** dos clientes receberam até **3 ligações** antes de adquirir um título financeiro.
- **43,45%** dos clientes receberam apenas **uma ligação** antes de efetuar a compra.
- **Clientes que receberam apenas uma ligação** apresentaram as maiores taxas de compra do ativo.

![image](https://github.com/user-attachments/assets/44aa8aff-dcad-428c-a544-c840fdefd05a)


## Análise de Correlações:
- As variáveis que apresentaram maior correlação com a compra do ativo foram **Idade** e **Profissão**, ambas com correlação média.
- **Clientes com hipoteca e/ou empréstimos** apresentaram correlação média com a compra do ativo.
- A **quantidade de ligações** apresentou correlação fraca com a compra do ativo.
- A **análise do saldo em conta corrente** também apresentou correlação fraca com a compra do ativo.
 
## 🚀 Conclusão
Essa análise demonstrou que variáveis como idade, profissão e ausência de dívidas, hipotecas ou empréstimos são determinantes no comportamento de compra de títulos bancários. O foco em otimizar campanhas para esses perfis pode aumentar significativamente as vendas.
A baixa correlação entre a quantidade de ligações e a aquisição do ativo pode ser um indicativo de que campanhas agressivas de ligações não são bem recebidas pelos clientes do banco
