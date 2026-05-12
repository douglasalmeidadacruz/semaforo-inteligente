- Nome do projeto: SmartFlow – Semáforo Inteligente
  
- Nome do desenvolvedor: Douglas Almeida da Cruz
  
- Curso: Técnico em Desenvolvimento de Sistemas – SENAI
  
- Objetivo do projeto: Desenvolver um sistema de simulação de um semáforo inteligente utilizando a linguagem C, capaz de controlar o fluxo de veículos em um cruzamento com duas vias (principal e secundária), garantindo organização e segurança no trânsito.
  
- Linguagem utilizada: C
  
- Descrição resumida do funcionamento: O sistema simula o comportamento de dois semáforos:
Via principal (maior fluxo)
Via secundária (menor fluxo)
O programa alterna automaticamente os sinais:
Verde → Amarelo → Vermelho
Regras principais:
Nunca permitir as duas vias com sinal verde ao mesmo tempo
A via principal permanece mais tempo no verde
Existe um tempo de segurança (vermelho para ambas)

- Como executar o programa, quando houver código: 
Pré-requisitos:
GCC instalado
Passos:
gcc main.c -o semaforo
./semaforo

- Estrutura do projeto:
semaforo-inteligente/
├── README.md
├── main.c
├── Docs/
│   └── Documentacao-DouglasAlmeidadaCruz.docx
└── Evidencias/
    └── prints/
    
- Funcionamento do ciclo:
1. Via principal: Verde | Via secundária: Vermelho
2. Via principal: Amarelo | Via secundária: Vermelho
3. Ambas: Vermelho (segurança)
4. Via principal: Vermelho | Via secundária: Verde
5. Via principal: Vermelho | Via secundária: Amarelo
6. Ambas: Vermelho (segurança)
7. Reinicia o ciclo

