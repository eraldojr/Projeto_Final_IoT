# Projeto_Final_IoT
## Automação residencial simples

### Projeto final do curso "Introdução aos dispositivos conectados utilizando Python", oferecido pelo IFSP Piracicaba.<addr>
A aplicação simula uma automação residencial simples. Tem funções para controlar temperatura ambiente, luzes externas e trancas de portas.<addr>


__Trancas de portas__
As trancas das portas poderão ser abertas/fechadas mediante autenticação do usuário via web, via botão que simula uma trava interna da casa. Um LED simboliza o status da porta:<addr>
Aceso: travada<addr>
Apagado: aberta<addr>


__Luzes externas__<addr>
A aplicação liga/desliga as luzes externas de acordo com a luminosidade capatada pelo sensor. As luzes são representadas por LEDs.


<b>Temperatura ambiente</b><br>
Quando ativado via sistema web, o sistema irá controlar a temperatura ambiente, mantendo-a próxima da temperatura escolhida.<br>
A temperatura será captada pelo sensor e o sistema irá diminuir a temperatura do ar condicionado em  10º quando o sistema ultrapassar 10º do escolhido e manterá nessa temperatura até atingir a temperatura escolhida.
