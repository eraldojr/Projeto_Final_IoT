# Projeto_Final_IoT
## Automação residencial simples

### Projeto final do curso "Introdução aos dispositivos conectados utilizando Python", oferecido pelo IFSP Piracicaba.
A aplicação simula uma automação residencial simples. Tem funções para controlar temperatura ambiente, luzes externas e trancas de portas.


 __Trancas de portas__<br>
As trancas das portas poderão ser abertas/fechadas mediante autenticação do usuário via web, via botão que simula uma trava interna da casa. Um LED simboliza o status da porta:<br>
* Aceso: travada<br>
* Apagado: aberta


 __Luzes externas__<br>
A aplicação liga/desliga as luzes externas de acordo com a luminosidade capatada pelo sensor. As luzes são representadas por LEDs.


 __Temperatura ambiente__<br>
Quando ativado via sistema web, o sistema irá controlar a temperatura ambiente, mantendo-a próxima da temperatura escolhida.
A temperatura será captada pelo sensor e o sistema irá diminuir a temperatura do ar condicionado em  10º quando o sistema ultrapassar 10º do escolhido e manterá nessa temperatura até atingir a temperatura escolhida.
