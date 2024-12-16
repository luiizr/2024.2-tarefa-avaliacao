# 2024.2 Avaliação do 1o período de Sistemas Operacionais

## Informações gerais
- **Objetivo do repositório**: Avaliação do 1o bimestre da Disciplina de sistemas operacionais do curso de TADS do IFRN-CNAT
- **Público alvo**: alunos da disciplina de SO (Sistemas Operacionais) do curso de TADS (Superior em Tecnologia em Análise e Desenvolvimento de Sistemas) no CNAT-IFRN (Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Norte - Campus Natal-Central).
- disciplina: **SO** Sistemas Operacionais
- professor: [Leonardo A. Minora](https://github.com/leonardo-minora)

## Avaliação
- **Lembre de fazer o fork deste repositório**
- As questões foram construídas com o auxílio do [copilot](https://copilot.microsoft.com/)

# Questão 1. Introdução a sistemas operacionais

Considere as funções e objetivos principais de um sistema operacional conforme discutido no texto. Explique como um sistema operacional gerencia os recursos de hardware e software de um computador para garantir eficiência e segurança. Em sua resposta, aborde os seguintes pontos:

- Gerenciamento de processos
- Gerenciamento de memória
- Gerenciamento de dispositivos de entrada e saída
- Gerenciamento de arquivos

**Dica**: Pense em exemplos práticos de como o sistema operacional realiza essas tarefas no dia a dia de um usuário.

**Copilot informa**: Essa questão incentiva os alunos a explorarem os conceitos fundamentais e a aplicarem o conhecimento teórico em situações práticas. Se precisar de mais alguma coisa, estou aqui para ajudar!

# Questão 2. Estrutura de sistemas operacionais

## Texto informativo
### Estrutura de Sistemas Operacionais: Custo de Desenvolvimento e Segurança da Informação

A estrutura de um sistema operacional (SO) é fundamental para determinar tanto o custo de desenvolvimento e manutenção quanto a segurança da informação. Existem várias arquiteturas de SO, como monolítica, microkernel e em camadas, cada uma com suas próprias implicações em termos de custo e segurança.

#### Custo de Desenvolvimento e Manutenção

1. **Arquitetura Monolítica**:
   - **Desenvolvimento**: Geralmente, mais rápida de desenvolver inicialmente, pois todos os componentes do SO são integrados em um único bloco de código.
   - **Manutenção**: Pode ser mais complexa e cara, pois qualquer alteração em um componente pode afetar todo o sistema, exigindo testes extensivos e cuidadosos.

2. **Arquitetura Microkernel**:
   - **Desenvolvimento**: Pode ser mais demorada e cara inicialmente, pois envolve a criação de um núcleo mínimo e a implementação de serviços adicionais como processos separados.
   - **Manutenção**: Mais fácil e menos custosa, já que os componentes são isolados. Atualizações e correções podem ser feitas em módulos específicos sem impactar o núcleo do sistema.

3. **Arquitetura em Camadas**:
   - **Desenvolvimento**: Moderadamente complexa, pois cada camada deve ser bem definida e interagir corretamente com as outras.
   - **Manutenção**: Relativamente fácil, pois problemas podem ser isolados e corrigidos em camadas específicas sem afetar o restante do sistema.

#### Segurança da Informação

1. **Arquitetura Monolítica**:
   - **Segurança**: Pode ser mais vulnerável, pois uma falha em qualquer parte do sistema pode comprometer todo o SO. A integração de todos os componentes em um único bloco de código pode dificultar a implementação de medidas de segurança robustas.

2. **Arquitetura Microkernel**:
   - **Segurança**: Geralmente mais segura, pois isola os serviços em processos separados. Isso limita o impacto de uma falha ou ataque a um único componente, protegendo o núcleo do sistema e outros serviços.

3. **Arquitetura em Camadas**:
   - **Segurança**: Oferece um bom equilíbrio, pois cada camada pode implementar suas próprias medidas de segurança. No entanto, a comunicação entre camadas deve ser cuidadosamente gerenciada para evitar vulnerabilidades.

### Conclusão

A escolha da arquitetura de um sistema operacional tem um impacto significativo tanto no custo de desenvolvimento e manutenção quanto na segurança da informação. Arquiteturas monolíticas podem ser mais rápidas e baratas de desenvolver inicialmente, mas podem acarretar custos de manutenção mais altos e maiores riscos de segurança. Por outro lado, arquiteturas microkernel e em camadas podem exigir um investimento inicial maior, mas oferecem vantagens em termos de manutenção e segurança.

## Questão
Com base no texto sobre a estrutura de sistemas operacionais, analise como as diferentes arquiteturas (monolítica, microkernel e camadas) impactam o custo com a equipe de desenvolvimento e a segurança do sistema operacional. Em sua resposta, considere os seguintes pontos:
- Complexidade de implementação e manutenção
- Necessidade de especialização da equipe
- Potenciais vulnerabilidades de segurança
- Facilidade de atualização e correção de falhas

**Dica:** Utilize exemplos de sistemas operacionais reais que adotam essas arquiteturas para ilustrar sua análise.

**Copilot informa**: Essa questão incentiva os alunos a considerarem tanto os aspectos econômicos quanto os de segurança ao avaliar diferentes arquiteturas de sistemas operacionais.

# Questão 3. Introdução à Segurança de Sistemas Operacionais

## Texto informativo

A segurança de um sistema operacional é um aspecto crucial que visa proteger os recursos do sistema contra acessos não autorizados, ataques maliciosos e falhas. Um sistema operacional seguro deve garantir a integridade, confidencialidade e disponibilidade dos dados e serviços. Para alcançar esses objetivos, várias técnicas e mecanismos são implementados, incluindo:

1. **Controle de Acesso**: Define quem pode acessar o sistema e quais recursos podem ser utilizados. Isso é feito através de autenticação (verificação de identidade) e autorização (permissão de acesso).

2. **Criptografia**: Utilizada para proteger dados em trânsito e em repouso, garantindo que apenas usuários autorizados possam acessar informações sensíveis.

3. **Auditoria e Monitoramento**: Registra atividades do sistema para detectar e responder a comportamentos suspeitos ou anômalos.

4. **Isolamento de Processos**: Garante que os processos sejam executados em ambientes isolados, evitando que um processo comprometa a segurança de outro.

5. **Atualizações e Patches**: Manter o sistema operacional atualizado é essencial para corrigir vulnerabilidades conhecidas e proteger contra novas ameaças.


## Questão

Considerando os mecanismos de segurança discutidos, analise como a implementação de controles de acesso e criptografia pode impactar a performance e a usabilidade de um sistema operacional. Em sua resposta, aborde os seguintes pontos:
- Benefícios e desafios de cada mecanismo
- Impacto na experiência do usuário
- Exemplos de situações onde esses mecanismos são críticos

**Dica:** Pense em como esses mecanismos são aplicados em sistemas operacionais que você utiliza no dia a dia, como Windows, Linux ou macOS.

**Copilot informa**: Essa questão incentiva os alunos a refletirem sobre o equilíbrio entre segurança, performance e usabilidade, aplicando conceitos teóricos a contextos práticos.


# Questão 4. Custo de Processamento versus Algoritmo Ótimo de Escalonamento

## Texto informativo

O escalonamento de processos é uma função crítica de um sistema operacional, responsável por determinar a ordem em que os processos são executados pelo processador. O objetivo é maximizar a eficiência do sistema, garantindo que os recursos sejam utilizados de maneira justa e eficaz. No entanto, encontrar o algoritmo de escalonamento ótimo envolve um equilíbrio delicado entre o custo de processamento e a eficiência do escalonamento.

### Custo de Processamento

O custo de processamento refere-se ao tempo e aos recursos necessários para executar um algoritmo de escalonamento. Algoritmos mais complexos podem oferecer melhores resultados em termos de tempo de resposta e utilização do processador, mas também podem exigir mais recursos computacionais para tomar decisões de escalonamento. Isso pode incluir tempo de CPU, memória e outras operações de sistema.

### Algoritmo Ótimo de Escalonamento

Um algoritmo ótimo de escalonamento é aquele que maximiza a eficiência do sistema operacional, minimizando o tempo de espera dos processos, o tempo de resposta e o tempo de retorno. Alguns dos algoritmos de escalonamento mais comuns incluem:

- **First-Come, First-Served (FCFS)**: Simples e fácil de implementar, mas pode levar a longos tempos de espera para processos curtos.
- **Shortest Job Next (SJN)**: Minimiza o tempo médio de espera, mas pode ser difícil de implementar devido à necessidade de prever o tempo de execução dos processos.
- **Round Robin (RR)**: Oferece uma abordagem justa, atribuindo fatias de tempo iguais a todos os processos, mas pode resultar em maior sobrecarga de contexto.
- **Priority Scheduling**: Processos com maior prioridade são executados primeiro, mas pode levar à inanição de processos de baixa prioridade.

## Questão

Considerando os conceitos de custo de processamento e algoritmo ótimo de escalonamento, analise como diferentes algoritmos de escalonamento podem impactar a performance de um sistema operacional em termos de tempo de resposta, tempo de espera e utilização do processador. Em sua resposta, aborde os seguintes pontos:
- Vantagens e desvantagens de pelo menos dois algoritmos de escalonamento
- Impacto do custo de processamento na escolha do algoritmo
- Exemplos de situações onde um algoritmo pode ser preferível a outro

**Dica:** Pense em como esses algoritmos são aplicados em diferentes cenários, como sistemas de tempo real, servidores web e sistemas operacionais de uso geral.

**Copilot informa**: Essa questão incentiva os alunos a refletirem sobre a complexidade e os trade-offs envolvidos na escolha de um algoritmo de escalonamento, aplicando conceitos teóricos a contextos práticos.

# Questão 5. Aplicativo em python vs aplicativos em c

## Questão

Explique o caminho que as instruções seguem desde um aplicativo escrito em Python e um aplicativo escrito em linguagem C até serem executadas pelo hardware. Em sua resposta, considere os seguintes pontos:
- O papel do interpretador no caso do Python
- O processo de compilação no caso do C
- A interação entre o kernel do sistema operacional e os drivers de dispositivo
- A tradução final das instruções para o formato binário (0 e 1) executado pelo hardware

**Dica:** Compare e contraste os dois processos, destacando as principais diferenças e semelhanças na forma como as instruções são processadas e executadas.

**Copilot informa**: Essa questão incentiva os alunos a refletirem sobre os diferentes caminhos que as instruções seguem em linguagens interpretadas e compiladas, aplicando conceitos teóricos a contextos práticos.





## RESPOSTAS:


### Questão 1: Introdução a Sistemas Operacionais

Um sistema operacional (SO) é como o "cérebro" do computador, que organiza tudo para que os programas funcionem bem e para que o hardware e o software trabalhem juntos. Ele tem quatro funções principais que garantem que o sistema seja eficiente e seguro:

1. **Gerenciamento de Processos:**
   - O SO é responsável por coordenar os processos, que são basicamente os programas em execução. Ele decide qual processo vai rodar, por quanto tempo e quando trocar para outro. Isso é essencial em sistemas multitarefa, onde o usuário pode assistir a um vídeo, editar um documento e navegar na internet ao mesmo tempo. O SO garante que todos esses processos recebam uma parte do processador sem travar o sistema.

2. **Gerenciamento de Memória:**
   - O SO precisa garantir que a memória RAM seja usada da melhor maneira possível. Ele separa uma parte da memória para cada programa em execução, criando um ambiente onde os programas não interferem uns nos outros. Além disso, ele cria a memória virtual, que utiliza parte do disco rígido como se fosse RAM, permitindo rodar mais programas do que a memória real suportaria.

3. **Gerenciamento de Dispositivos de Entrada e Saída:**
   - Todo dispositivo conectado ao computador é gerenciado pelo SO. Isso inclui teclados, mouses, impressoras, pen drives, entre outros. Ele usa os drivers para traduzir os comandos do sistema para algo que o dispositivo entenda. Por exemplo, quando você clica para imprimir um documento, o SO envia as instruções para a impressora de forma que ela saiba exatamente o que fazer. Esse gerenciamento também permite que vários dispositivos funcionem ao mesmo tempo sem conflitos.

4. **Gerenciamento de Arquivos:**
   - O SO organiza como os arquivos são armazenados e acessados no sistema. Ele cria estruturas de diretórios e oferece comandos para criar, copiar, mover ou apagar arquivos. Além disso, ele cuida da segurança, garantindo que somente usuários autorizados possam acessar determinados arquivos. 

Com essas quatro funções, o SO garante que você possa usar o computador sem se preocupar com os detalhes técnicos do hardware.

---

### Questão 2: Estrutura de Sistemas Operacionais

Os sistemas operacionais podem ser organizados de formas diferentes, dependendo de como seus componentes interagem, podemos citar como exemplo:

1. **Monolítica:**
   - Nesse tipo de arquitetura, todo o código do SO funciona como um bloco único. Isso significa que todas as funções, como gerenciamento de arquivos, memória e dispositivos, estão integradas. A grande vantagem é que o sistema é muito rápido, pois não há separação entre os módulos. Por outro lado, se uma parte do sistema falhar, todo o SO pode travar. Um exemplo clássico é o Linux, que utiliza um núcleo monolítico.

2. **Microkernel:**
   - Aqui, apenas as funções básicas, como comunicação entre processos e acesso ao hardware, ficam no núcleo. Todo o resto é separado em serviços que rodam fora do núcleo. Isso torna o sistema mais seguro e fácil de atualizar, pois uma falha em um serviço não afeta o núcleo. Por outro lado, ele pode ser mais lento devido à comunicação entre os serviços. Exemplos incluem o Minix e o QNX.

3. **Em Camadas:**
   - Nesse modelo, o SO é dividido em "andares", onde cada camada cuida de uma tarefa específica. A camada mais baixa controla o hardware, enquanto as camadas superiores gerenciam dispositivos, memória e processos. Isso facilita a manutenção, mas pode tornar o sistema mais lento devido à necessidade de atravessar várias camadas para realizar uma tarefa. Um exemplo de sistema em camadas é o Windows NT.

Essas arquiteturas mostram como os sistemas operacionais podem ser projetados para balancear desempenho, segurança e facilidade de manutenção.

---

### Questão 3: Segurança de Sistemas Operacionais

Dois dos principais mecanismos usados para proteger os dados e recursos são o controle de acesso e a criptografia.

1. **Controle de Acesso:**
   - Esse mecanismo define quem pode acessar o quê no sistema. Isso é feito através de autenticação (como senhas ou biometria) e permissões (como leitura, escrita e execução de arquivos). Por exemplo, em um computador compartilhado, cada usuário tem sua própria conta e só pode acessar seus próprios arquivos. O desafio do controle de acesso está em balancear segurança e praticidade. Senhas longas e autenticações frequentes podem ser seguras, mas também podem irritar o usuário.

2. **Criptografia:**
   - A criptografia protege os dados "embaralhando" as informações para que apenas pessoas autorizadas possam entendê-las. Isso é muito importante em transações bancárias e comunicações pela internet. Um exemplo comum é o uso de HTTPS em sites, que garante que as informações transmitidas entre você e o site estejam protegidas. O problema é que a criptografia pode consumir mais recursos do sistema, tornando-o um pouco mais lento.

---

### Questão 4: Algoritmos de Escalonamento

Escalonamento é como o sistema operacional decide qual programa vai usar o processador e por quanto tempo.

1. **FCFS (First-Come, First-Served):**
   - Este é o método mais simples: quem chega primeiro é atendido primeiro. Funciona bem para tarefas longas e simples, mas pode causar tempos de espera altos para tarefas curtas, porque uma tarefa longa pode "segurar" o processador por muito tempo.

2. **Round Robin (RR):**
   - Neste método, cada processo recebe um "pedaço" de tempo para rodar. Se não terminar, ele vai para o final da fila e espera a sua vez novamente. Isso é justo e funciona bem em sistemas interativos, mas o SO precisa gastar tempo alternando entre os processos, o que pode gerar alguma lentidão.

Esses algoritmos são escolhidos dependendo do tipo de sistema. Por exemplo, o FCFS é comum em sistemas de lote, enquanto o RR é mais usado em sistemas interativos.

---

### Questão 5: Aplicativo Python vs. C

1. **Python:**
   - Em Python, o código é interpretado. Isso significa que cada linha do programa é lida e traduzida em tempo real pelo interpretador. Isso torna o desenvolvimento mais rápido e simples, mas também faz o programa rodar mais devagar, porque a tradução acontece enquanto ele está sendo executado.

2. **C:**
   - Em C, o código é compilado antes de ser executado. Isso significa que o programa é traduzido de uma vez para linguagem de máquina, criando um arquivo binário que pode rodar direto no hardware. Esse processo torna o programa muito mais rápido, mas também exige mais cuidado no desenvolvimento.

Independente da linguagem, o sistema operacional faz a ponte entre o programa e o hardware, usando o kernel e os drivers para traduzir as instruções do programa em comandos que o processador e outros dispositivos possam entender. Python é ideal para tarefas simples e rápidas, enquanto C é mais adequado para aplicações que precisam de alta performance.
