# GS-Arduino
# INTEGRANTES:

    Gilson Dias Ramos Junior – RM552345 

    Joseh Gabriel Trimboli Agra - RM553094

# Problema

    O Medi+ enfrenta o desafio comum e crítico relacionado à gestão de medicamentos e cuidados de saúde. 
    O serviço aborda problemas como o armazenamento  inadequado de remédios, dificuldades na administração 
    correta das prescrições médicas e a baixa adesão dos pacientes aos tratamentos. 

# Solução

    Busca solucionar esses desafios por meio de uma plataforma integrada que oferece orientações precisas 
    sobre armazenamento, automatização do cronograma de medicamentos, comunicação direta com profissionais de 
    saúde e integração da telemedicina, visando aprimorar a eficácia dos tratamentos e proporcionar uma
    experiência mais segura e personalizada aos usuários.

# Instrucoes

    O circuito será integrado dentro de uma caixa organizadora de remédios, onde cada 
    compartimento será controlado por um servo motor, totalizando sete motores no projeto.
 
    *Funcionamento da liberação do medicamento:*
 
    - O sistema receberá dados sobre os horários e dias dos medicamentos.
    - Quando chegar o momento da medicação, o LED verde, indicando "medicamento disponível", será ativado, 
      juntamente com o LCD informando qual medicamento deve ser tomado.
    - Ao mesmo tempo, o buzzer tocará e o servo motor correspondente abrirá o compartimento.
    - Após a remoção do medicamento pelo usuário, o servo motor fechará a porta e o LED e buzzer serão desligados.
 
    *Funcionalidade dos sensores:*
     
    Os sensores LDR, DHT36 e potenciômetro (simulando o sensor de umidade) captam as condições do ambiente 
    em que os medicamentos estão guardados.
    Se a estrutura condicional do sistema detectar dados fora dos padrões de um ambiente seguro para os medicamentos, 
    como temperatura, umidade ou luminosidade inadequadas:
    - O LCD exibirá "Med Comprometido";
    - O LED vermelho de alerta será ativado;
    - O buzzer emitirá um sinal sonoro contínuo.
    A situação retorna ao normal quando o usuário encontrar um ambiente adequado para armazenar a caixa.

# Circuito montado no ThinkerCad

https://www.tinkercad.com/things/5cB6PFGGSr6-copy-of-teste-gs-arduino/editel?sharecode=tz1rrR7GoGbAKzu0js0Ioe5cdJaE4tkKdcsGnIjTTpE

# Prototipo Caixa de Remedios
https://www.tinkercad.com/things/lUn7u9llIcm-caixa-calendario-de-remedios?sharecode=eph5wkV1YP2R7mW1KN2Vdu2f6i5ZGY1ebvBBBDbgFH0

