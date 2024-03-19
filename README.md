# Irriga-o-Automatizada-do-Jardim
# Grupo: Mateus Araujo, Robson Luan e Alexandre Pacheco
A Irrigação Automatizada do Jardim utiliza sensores de umidade do solo para monitorar e controlar a irrigação, garantindo que as plantas recebam água na quantidade certa. Isso otimiza a saúde das plantas e economiza água, tornando a manutenção do jardim mais eficiente. Seguindo as seguintes condições:

Funcionamento:
1.	Sensores de Umidade do Solo: Sensores de umidade do solo são instalados em locais estratégicos no jardim.
2.	Hub de Controle: Um hub de controle central coleta os dados dos sensores de umidade do solo.
3.	Sistema de Irrigação: Um sistema de irrigação automatizado está conectado ao hub de controle.
4.	Lógica de Controle: Com base nos dados dos sensores de umidade, a lógica de controle decide quando e quanto irrigar o jardim.
5.	Irrigação Automática: O sistema de irrigação é acionado automaticamente para fornecer água às plantas conforme necessário, conforme as informações dos sensores de umidade.
Funcionalidades:
•	Monitoramento de Umidade do Solo: Permite monitorar continuamente os níveis de umidade do solo em diferentes áreas do jardim.
•	Irrigação Automatizada: Mantém as plantas irrigadas de maneira eficiente e automática, evitando tanto o excesso quanto a falta de água.
•	Conservação de Água: Evita desperdícios de água irrigando apenas quando necessário, com base nas condições reais do solo.
Dispositivos IoT:
1.	Sensores de Umidade do Solo: Detectam a umidade do solo e enviam dados para o hub de controle.
2.	Hub de Controle: Recebe os dados dos sensores, processa-os e controla o sistema de irrigação.
3.	Sistema de Irrigação: Responsável por fornecer água às plantas conforme as instruções do hub de controle.
Arquitetura do Sistema:
•	Os sensores de umidade do solo se comunicam sem fio com o hub de controle.
•	O hub de controle pode ser conectado à internet, permitindo acesso remoto aos dados e controle da irrigação.
•	A lógica de controle reside no hub de controle, que toma decisões com base nos dados dos sensores.
Desenvolvimento de Hardware:
•	Desenvolvimento dos sensores de umidade do solo com capacidade de comunicação sem fio.
•	Desenvolvimento do hub de controle para receber dados dos sensores, processá-los e controlar o sistema de irrigação.
•	Integração do sistema de irrigação com o hub de controle.
Plataforma IoT:
•	Uma plataforma IoT pode ser utilizada para armazenar e processar os dados dos sensores, oferecendo análises e insights sobre o estado do jardim.
•	Além disso, a plataforma pode fornecer recursos de controle remoto, permitindo que os usuários monitorem e controlem a irrigação do jardim através de um aplicativo móvel ou interface web.

   +---------------------------+
   |   Sensores de umidade    |
   |    do solo (Comunicação  |
   |          sem fio)        |
   +------------+--------------+
                |
                v
       +--------+--------+
       |  Hub de controle |
       |(Conectado à internet)|
       +--------+--------+
                |
                v
      +---------+----------+
      |  Sistema de irrigação |
      +----------------------+

#Representação/0.1 da Arquitetura do projeto 

