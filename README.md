# RESUMO

## ES-Arquitetura e Organização de Computadores.pdf

- Dispositivos de entrada e dispositivos de saída.
  - Mouse
  - Teclado
  - touchscreen...
- Tipos de barramentos.
  - PRINCIPAIS:
    - Barramento de endereço
      - Por ele que o processador pega o endereço da meméria, aonde está contido os dados.
    - Barramento de dados
      - É por esse barramento que os dados processados retornam à memória.
      - **"DE ACORDO COM A FIGURA 2.11, ESSE BARRAMENTO DE DADOS É OU NAO UNIDIRECIONAL?"**
      - > A figura 2.11 do Souza Filho (2014), mostra que o barramento de dados é de uma única via, saindo os dados do processador e indo para a memória. Mas por não fazer sentido (como os dados trafegam da memória até o processador?) pesquisei na internet, e realmente o barramento de dados é de ida e vinda.
    - Barramento de controle
      - Nesse pdf, não temos muitas informações sobre o barramento de controle, sabe-se que ele é interligado a todos os periféricos de entrada/saída, memória e processador.
      - > Mas pesquisando na internet, através de um vídeo explicativo no youtube, sei que: esse barramento faz a sincronização da CPU em geral com os periféricos de entrada e saída (memória, hd, entrada do teclado...) e os controla. Ou seja, como os dados (que trafegam pelo barramento de dados) sabem qual endereço (que trafaga pelo barramento de endereço) é o seu referente? Pelo barramento de controle que os sincronizam.
      - >Referência: https://www.youtube.com/watch?v=fiEF4W_KbLw&ab_channel=Dicion%C3%A1riodeInform%C3%A1tica
      - **PELO QUE ME PARECE, ESSE BARRAMENTO É COMO SE FOSSE A ENERGIZAÇÃO DA PLACA E PERIFÉRICOS. A FORMA DE ENTRADA/CONECTAR**
- Chipset: (ponte) entre os barramentos.

- OUTROS BARRAMENTOS ESSENCIAIS:
  - Barramento local
    - ...
  - Barramento de sistema
    - ...
  - Barramento de expanção
    - ...