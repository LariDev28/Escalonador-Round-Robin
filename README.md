⚙️ Escalonador Round Robin em C++ (Tinkercad)

📌 Descrição

  Este projeto implementa um algoritmo de escalonamento Round Robin utilizando a linguagem C++, simulado na plataforma Tinkercad.
  
  O desenvolvimento foi realizado como parte de uma atividade acadêmica proposta pelo professor Gerson Risso, com o objetivo de aplicar na prática conceitos de sistemas operacionais.
  
  O projeto demonstra como funciona o gerenciamento de processos, utilizando o conceito de fatia de tempo (quantum) para garantir uma execução justa entre os processos.

🎯 Objetivos do Projeto

  Simular o funcionamento do algoritmo Round Robin
  
  Aplicar conceitos de Sistemas Operacionais
  
  Utilizar C++ para controle de execução de processos
  
  Demonstrar o comportamento do escalonador em ambiente simulado

🧠 Conceito: Round Robin

  O Round Robin é um algoritmo de escalonamento que:
  
  Distribui o tempo de CPU de forma igual entre os processos
  
  Utiliza um tempo fixo chamado quantum
  
  Interrompe o processo quando o tempo expira
  
  Coloca o processo no final da fila

  👉 Isso garante maior equidade e responsividade no sistema.
  
🏗️ Arquitetura do Sistema

  Como garantir que vários processos rodem de forma justa em um único processador? Este projeto responde a isso simulando o escalonamento Round Robin. Estruturei o sistema para que o microcontrolador dite o ritmo, alternando entre as tarefas e sinalizando o status com LEDs — vermelho para 'em execução' e verde para 'concluído'. O resultado é um fluxo contínuo e inteligente que reduz a fatia de tempo (quantum) de cada processo progressivamente, mostrando na prática a eficiência por trás do compartilhamento de tempo em sistemas computacionais.
  
⚙️ Funcionalidades

  Simulação de múltiplos processos
  
  Controle de tempo de execução (quantum)
  
  Atualização do estado dos processos
  
  Exibição da ordem de execução

  Indicação luminosa do ciclo de vida do processo (Execução vs. Finalização)

🛠️ Tecnologias Utilizadas

  C++
  
  Tinkercad

🚀 Como Executar

🔹 No Tinkercad

  Acesse a plataforma Tinkercad: https://www.tinkercad.com
  
  Abra o projeto
  
  Inicie a simulação
  
  Observe a execução dos processos no console

📊 Exemplo de Funcionamento

  Entrada:
  
  Processos: P1, P2, P3, P4
  Tempo (burst): 2000, 1300, 50, 234 
  Quantum: 200
  
  Saída esperada:
  
P1 executa 200ms (restam 1800ms) → LED Vermelho pisca

P2 executa 200ms (restam 1100ms) → LED Vermelho pisca

P3 executa 50ms (Finalizado!) → LED Verde sinaliza conclusão

P4 executa 200ms (restam 34ms) → LED Vermelho pisca

P1 retorna para mais 200ms...

📚 Aprendizados

  Funcionamento de algoritmos de escalonamento
  
  Gerenciamento de processos
  
  Uso de estruturas de dados (filas)
  
  Implementação de lógica em C++

💡 Melhorias Futuras

  Interface gráfica da simulação
  
  Suporte a diferentes algoritmos (FIFO, SJF)
  
  Visualização do tempo de espera e turnaround

📌 Conclusão

  Este projeto foi fundamental para visualizar como o compartilhamento de tempo (Time Sharing) impede que um processo 'faminto' monopolize a CPU, um princípio que sustenta desde microcontroladores simples até sistemas complexos como Linux e Windows.
