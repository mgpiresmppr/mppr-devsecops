# Modelagem de ameaças STRIDE
Autor: Moisés de Gois Pires
Funcionalidade escolhida: Login 
<!-- (ex: login, cadastro, listagem) -->

### Spoofing
1. Existe algum risco?\
Sim.
2. Se sim, qual seria?\
Um exemplo seria o uso de credenciais vazadas (ou a exploração de alguma falha no serviço de login) para obter acesso a alguma conta registrada no sistema.
3. Que tipo de atacante se beneficiaria?\
Aquele que busca coletar dados pessoais de clientes ou causar estragos no sistema.

### Tampering
1. Existe algum risco?\
Sim.
2. Se sim, qual seria?\
Tentativa de modificar os dados no processo de autenticação para tentar contorar esse processo e ganhar acesso ao sistema, ou ainda redirecionar o acesso de um cliente para outro destino.
3. Que tipo de atacante se beneficiaria?\
Os que se valem de acesso privilegiado (insiders) ou os que utilizam processos "man in the middle".

### Repudiation
1. Existe algum risco?\
Sim.
2. Se sim, qual seria?\
Negação de uma utilização real, sendo um usuário mal-intencionado ou um atacante. Só "funciona" se os registros (logs) são insuficientes ou passíveis de adulteração.
3. Que tipo de atacante se beneficiaria?\
Aquele que tenta esconder ações nocivas contra o sistema ou o que almeja fraudá-lo.

### Information Disclosure
1. Existe algum risco?\
Sim.
2. Se sim, qual seria?\
Um exemplo é o vazamento de credenciais ou outros dados pessoais de usuários.
3. Que tipo de atacante se beneficiaria?\
O que busca montar base de dados pessoais para venda posterior, ou ainda os que fazem engenharia social.

### Denial of Service
1. Existe algum risco?\
Sim.
2. Se sim, qual seria?\
Sobrecarga do mecanismo de autenticação com grande volume de requisições, utilizando várias técnicas. Isso pode afetar a disponibilidade de um sistema.
3. Que tipo de atacante se beneficiaria?\
Um concorrente que busca prejudicar o dono do sistema atacado, ou ainda ativistas digitais.

### Elevation of Privilege
1. Existe algum risco?\
Sim.
2. Se sim, qual seria?\
Um atacante obtém acesso a uma credencial de privilégio baixo no sistema e depois tenta explorar alguma vulnerabilidade para escalar para uma credencial com acesso privilegiado a dados do sistema ou da empresa.
3. Que tipo de atacante se beneficiaria?\
Algum usuário interno de má-fé ou hackers que conhecem vulnerabilidades inerentes a alguma tecnologia que compõe o ambiente onde o sistema roda.