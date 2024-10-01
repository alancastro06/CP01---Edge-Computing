# CP01--Edge-Computing
Integrantes: 
Lucas Cortizo Carvalho
Alan De Castro De Archangelo

Descrição do Projeto:
Vocês foram contratados pela Vinheria Agnello para desenvolver um sistema de monitoramento a
ser instalado no ambiente em que os vinhos são armazenados. O dono a Vinheria informou que a
qualidade do vinho é influenciada diretamente pelas condições de temperatura, umidade e
luminosidade do ambiente. Neste primeiro momento, você propôs ao dono da Vinheria um
projeto em etapas, de modo que seu 1° desafio é:
- Elaborar um sistema usando Arduino que faça a captura das informações de luminosidade do
ambiente. Para isso pesquise sobre o LDR. Verifique como eles funcionam e como poderiam
ser usados no projeto.
- De posse dos dados coletados, implemente um sistema de alarme, utilizando LEDs, para
sinalizar quando o a ambiente estiver OK, ou quando alguma grandeza estiver fora dos limites
estipulados. Use um LED verde para indicar que está OK, um LED amarelo para indica que está
em níveis de alerta e um LED Vermelho para indicar que tem algum problema.
- Quando a luminosidade estiver em nível de alerta, deve soar uma buzina (buzzer) por 3
segundos. A buzina volta a soar caso a luminosidade permaneça em nível de alerta

Nossa visão: O projeto foi algo simples porém no meio teve um único problema que nos fez demorar bastante para resolver, isso é a conversão do valor do ldr que era printado na serial,
sempre era um número diferente do que o LDR estava apresentando, porém depois conseguimos achar uma expressão que igualasse aproximadamente os número de 0 a 100k de lux.
