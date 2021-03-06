# Treinamento LTE com o ns-3

## Bolsistas de IC 2021
- Bolsista 01: RICARDO QUEIROZ DE FARIAS HENRIQUE SILVA
- Bolsista 02: DARIO GUILHERME DE MACEDO
- Bolsista 03: ERIBERTO DE SOUTO SILVA
- Orientador: Vicente Angelo de Sousa Junior
- Co-orientadores: Daniel Rodrigues de Luna e Tarciana Cabral de Brito Guerra 
- Companheiros de grupo: Lucas Ismael Campos Medeiros, Ravan Novaes de Oliveira e Sildolfo Francisco Gomes Neto 

## Metas 2021.2
- Conhecer o LENA LTE
- Conhecer tecnicamente o LTE
- Preparar hands-ons tutoriais sobre o ns-3
- Lecionar um minicurso sobre prototipagem de redes 4G usando o ns-3 (para alunos da UFRN)
- Fazer um estudo inédioto em redes 4G 

## Modus Operandi

As atividades dos bolsistas serão divididas em três frentes:
- **Frente 1:** Redes de Comunicações Móveis 4G-LTE
- **Frente 2:** prototipagem do 4G com ns-3

As Seções a seguir são usadas para a definição e acompanhamento das atividades, utilizando a seguinte legenda:

- **TODO**: são tarefas específicas com escopo, dono e prazo;
- **Hands-on**: são materias já construídos no GppCom que servirão de referência de estudo; os hands-on tem texto, código e desafios de programação. Como de costume, a construção de novos Hands-on serão atribuídos para novos bolsistas a medida que forem avançando no treinamento;
- **P1, P2, P3 e P4**: níveis de prioridade para guiar a sequência de tarefas do bolsista. O nível **P1** é o de maior prioridade e deve ser feito primeiro. Somente tarefas com 
- **TBD (to be defined)**: tarefas ainda não agendadas, com escopo e/ou data a serem definidas;

### Frente 1: Redes de Comunicações Móveis 4G-LTE
   - **TODO 1.1:** Padronização de sistemas 3GPP
      - Descomplicando o 5G (https://5gdescomplicado.com/2020/05/03/descomplicando-o-5g/)
      - De onde vêm os padrões? https://5gdescomplicado.com/2020/05/11/de-onde-vem-os-padroes/
      - Como as Redes de Acesso por Rádio (RANs) evoluíram em direção ao 5G? https://5gdescomplicado.com/2020/05/17/como-as-redes-de-acesso-por-radio-rans-evoluiram-em-direcao-ao-5g/
      - Breve descrição do potencial do 5G para transformar nossas atividades produtivas: https://5gdescomplicado.com/2020/06/08/nem-todos-os-bits-nascem-iguais/
      - Sobre patentes: Nosso dia a dia cercado de patentes: https://5gdescomplicado.com/2020/06/15/nosso-dia-a-dia-cercado-de-patentes/
      - Padronização: O Grande Bazar onde nasce o 5G: https://5gdescomplicado.com/2020/06/27/188/ 
      - Capítulo 2: **LTE for UMTS - Evolution to LTE-Advanced**
      - Capítulo 1: **LTE-ADVANCED 3GPP SOLUTION FOR IMT-ADVANCED**
      - Ricardo: **Prazo:** .  **Feito:** 06/08/2021.
      - Dario: **Prazo:** . **Feito:** 06/08/2021.
      - Eriberto: **Prazo:** . **Feito:** 02/12/2021. 
   - **TODO 1.2:** Overview sobre LTE
      - Capítulo 3: **LTE-ADVANCED 3GPP SOLUTION FOR IMT-ADVANCED**
      - Ricardo: **Prazo:**  27/08/2021.  **Feito:** 27/08/2021.     
      - Dario: **Prazo:** 27/08/2021.  **Feito:** 02/09/2021.
      - Eriberto: **Prazo:** . **Feito:** 03/12/2021. 
   - **TODO 1.3:** Overview LTE-A  (release 9 e 10)
      - Capítulo 1: **LTE-ADVANCED 3GPP SOLUTION FOR IMT-ADVANCED**
      - Carrier aggregation: Seções 4.1, 4.2 e 4.6, 5.1, 5.2 e 5.6
      - MIMO: 6.1, 6.2, 6.5, 7.1, 7.2, 7.5
      - Ricardo: **Prazo:** 03/09/2021.  **Feito:** 02/09/2021.     
      - Dario: **Prazo:** 03/09/2021.  **Feito:** 02/09/2021.
      - Eriberto: **Prazo: 07/12/2021** . **Feito:** 06/12/2021.  
   - **TODO 1.4:** Overview LTE-A PRO (Releases 11, 12, 13)
      - Capítulos 1 ao 3: **LTE Small_Cell Optimization**
      - Ricardo: **Prazo:** TBD .  **Feito:** 14/10/2021.   
      - Dario: **Prazo:** TBD .  **Feito:** 14/10/2021.
      - Eriberto: **Prazo:20/12/2021** . **Feito:** 20/12/2021. 
   - **TODO 1.5:** Arquitetura do LTE
      - Capítulo 3 (somente até a seção 3.2, não ler a 3.3): **LTE for UMTS - Evolution to LTE-Advanced**
      - Ricardo: **Prazo:** TBD .  **Feito:** 14/10/2021.     
      - Dario: **Prazo:** TBD .  **Feito:** 14/10/2021.
      - Eriberto: **Prazo:20/12/2021** . **Feito:** 19/12/2021. 
   - **TODO 1.6:** Interface de radio e camadas de protocolos
      - Seções 6.1 e 6.2: **LTE for UMTS - Evolution to LTE-Advanced**
      - Ricardo: **Prazo:** TBD .  **Feito:** 18/01/2022 .     
      - Dario: **Prazo:** TBD.  **Feito:** 24/01/2022.
      - Eriberto: **Prazo:22/12/2021** . **Feito:** 22/12/2021. 
   - **TODO 1.7:** Camada Fisica
      - Capítulos 4 e 5: **LTE for UMTS - Evolution to LTE-Advanced**
      - Ricardo: **Prazo:** TBD .  **Feito:** .    
      - Dario: **Prazo:** TBD .  **Feito:** .
   - **TODO 1.8:** MAC, RLC, PDCP
      - Seções 6.3, 6.4, 6.5 e 6.6: **LTE for UMTS - Evolution to LTE-Advanced**
      - Ricardo: **Prazo:** TBD .  **Feito:** .     
      - Dario: **Prazo:** TBD .  **Feito:** .
      - Eriberto: **Prazo:30/12/2021** . **Feito:** 27/12/2021. 
   - **TODO 1.9:** RRM
      - Capítulo 8: **LTE for UMTS - Evolution to LTE-Advanced**
      - Ricardo: **Prazo:** TBD .  **Feito:** .  
      - Dario: **Prazo:** TBD .  **Feito:** .
      - Eriberto: **Prazo:04/01/2022** . **Feito:** . 
   - **TODO 1.10:** Desempenho
      - Capítulo 10: **LTE for UMTS - Evolution to LTE-Advanced** 
      - Ricardo: **Prazo:** TBD .  **Feito:** .   
      - Dario: **Prazo:** TBD .  **Feito:** .
      - Eriberto: **Prazo:06/01/2021** . **Feito:** . 
   - **TODO 1.11:** Introdução ao LTE-5G (Releases 15, 16 e 17)
      - Capítulos 1 e 3: **5G Technology - 3GPP New Radio**
      - Leitura somente até o final da Seção 2: **5G New Radio Network Planning, Whitepaper, Ranplan Wireless Network Design Ltd,  February 2019** 
      - Ler artigo todo: **The 5G Evolution: 3GPP Releases 16-17, 5G Americas, Jan, 2020**
      - Ler artigo todo: **5G NEW RADIO – EVOLUTION, Ericsson Technology Review, Mar, 2020** 
      - Ricardo: **Prazo:** TBD .  **Feito:** .     
      - Dario: **Prazo:** TBD .  **Feito:** .
      - Eriberto: **Prazo:14/01/2021** . **Feito:** . 

### Frente 2: prototipagem do 4G com ns-3
   - **TODO 2.0**: instalar e integrar o ns-3 no VS code [Hands-on](https://github.com/vicentesousa/IC_LTE_ns3/blob/main/fase_01/HD_00/f01_hd00.ipynb)
   
   - **TODO 2.1**: Entender e explicar em um jupyter notebook o Basic simulation program (https://www.nsnam.org/docs/models/html/lte-user.html): LTE-only sem EPC. O ipynb deve ter o seguinte conteúdo: [Hands-on](https://nbviewer.org/github/vicentesousa/IC_LTE_ns3/blob/main/fase_01/HD_01/f01_hd01.ipynb)
      - **C1**: explicar cada parte do script **lena-simple.cc**;
      - **C2**: explicar como incluir parâmetros de configuração via linha de comando (ver Seção Configuration of LTE model parameters);
      - **C3**: explicar como usar o ConfigStore para grava e carregar parâmetros de ua simulação;
      - **C4**: Habilitar, gravar e explicar cada arquivo de saída da simulação (ver Seção Simulation Output). Entender e explicar no ipynb cada coluna dos arquivos de saída da simulação. Explicar como manipular a pasta de saída dos resultados. Ver scritp **lena-rlc-traces.cc**.
      - Ricardo: **Prazo:** 20/08/2021.  **Feito:** 03/09/2021.     
      - Dario: **Prazo:** 20/08/2021.  **Feito:** 03/09/2021.
      - Eriberto: **Prazo:** . **Feito:** . 
   -  **TODO 2.2**: Entender, simular e plotar o fading traces [Hands-on](https://nbviewer.org/github/vicentesousa/IC_LTE_ns3/blob/main/fase_01/HD_02/f01_hd02.ipynb)
      - **C1**: Ler e explicar resumidamente os efeitos da Fading (diferenciar desvanecimentos plano e seletivo em frequência. Diferenciar desvanecimentos lento e rápido. Talvez valha a pena assistir as aulas da UNIDADE I de Comunicações Móveis. Prof. Vicente pode disponibilizar os vídeos)
      - **C2**: Explicar como gerar os arquivo de fading via Matlab (**/lte/model/fading-traces/fading-trace-generator.m**). Ver seção Fading Traces Generation.
      - **C3**: Explicar como habilitar o fading em simulações do ns-3. Explicar script **lena-fading.cc**. Ver seção Fading Traces Usage.
      - Ricardo: **Prazo:** TBD .  **Feito:** 24/09/2021.   
      - Dario: **Prazo:** TBD .  **Feito:** 24/09/2021.
      - Eriberto: **Prazo:** . **Feito:** . 
   -  **TODO 2.3**: Entender, simular e plotar o REM (Radio Environment Maps) [Hands-on](https://nbviewer.org/github/vicentesousa/IC_LTE_ns3/blob/main/fase_01/HD_03/f01_hd03.ipynb)
      - **C1**: Explicar o que é o REM e para que ele serve
      - **C2**: Explicar o **script lena-rem.cc** e plotar o REM 
      - **C3**: Explicar o script **lena-rem-sector-antenna.cc** e plotar o REM 
      - Ricardo: **Prazo:** TBD .  **Feito:** 06/10/2021.     
      - Dario: **Prazo:** TBD .  **Feito:** 06/10/2021.
      - Eriberto: **Prazo:** . **Feito:** . 
   -  **TODO 2.4**: Entender, simular e plotar um cenário LTE + EPC [Hands-on](https://nbviewer.org/github/vicentesousa/IC_LTE_ns3/blob/main/fase_01/HD_04/f01_hd04.ipynb)
      - **C1**: Explicar cada parte do script **lena-simple-epc.cc**. Ver Seção Evolved Packet Core (EPC)
      - **c2**: Cenário apenas com 1 eNB e 1 UE. Adicionar o fast fading e shadowing. 
      - **C3**: Fazer campanha de convergência das métricas.
      - **C4**: Fazer curvas de Tput (e outras métricas) com o aumento da carga do sistema (UdpClientHelper)
      - **C5**: CDFs de SINRs, TBler, MCS para uma carga baixa e alta.
      - **C6**: Repetir as curvas para um número maior de UEs.
      - **C7**: Utilizar um cenário hexagonal e multicelular.
      - Ricardo: **Prazo:** TBD .  **Feito:** .     
      - Dario: **Prazo:** TBD .  **Feito:** .
      - Eriberto: **Prazo:** . **Feito:** . 
   - **TODO 2.5**: Entender e simular LTE com EPC
      - **C1**: explicar cada parte do script **lena-simple-epc.cc**. Ver Seção Evolved Packet Core (EPC)
      - **C2**: Pesquisar diferentes modelos de tráfego e rodar 4 serviços diferentes (e.g., voz, streaming, ftp, e-mail) em um único Bearer;
      - **C3**: Ativar um bearer diferente para cada serviço;
      - **C4**: Fazer curvas de Tput (e outras métricas) com o aumento da carga do sistema. Comparar o desempenho dos 4 serviços com um bearer e com 4 bearers.
      - **C5**: Fazer campanha de convergência das métricas.
      - Ricardo: **Prazo:** TBD .  **Feito:** .    
      - Dario: **Prazo:** TBD .  **Feito:** .
      - Eriberto: **Prazo:** . **Feito:** . 
   - **TODO 2.6**: Entender e simular o RLF e o Handover
      - **C1**: explicar o RLF e o script **lena-radio-link-failure.cc**. Ver a Seção Radio link failure example e o https://www.sharetechnote.com/html/Handbook_LTE_RadioLinkFailure.html
      - **C2**: Repetir os dois experimentos e gráficos da Seção Radio link failure example (sem handover);
      - **C3**: Repetir os gráficos ativando o Handover (para entender e configurar o Handover, ver Seção Handover simulation campaign e o script **lena-dual-stripe.cc**)
      - Ricardo: **Prazo:** TBD .  **Feito:** .   
      - Dario: **Prazo:** TBD .  **Feito:** .
      - Eriberto: **Prazo:** . **Feito:** . 
      
     

