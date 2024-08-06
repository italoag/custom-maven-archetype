# Demo Project
This demo project created in the form of a tutorial called [Maven In Depth: Creating A Custom Archetype For Spring Boot Project][tuto-medium],
please check it before start pulling down the project.

### Tech Stack

* [Spring Boot][spring-boot]
* [Apache Maven]

### Definição de Padrão

Um **padrão** é um conjunto de diretrizes, regras ou características especificadas que servem como um modelo ou referência para medir, comparar e garantir a uniformidade e qualidade em diferentes contextos. Padrões são desenvolvidos e estabelecidos por organizações, indústrias, e comitês de normalização para assegurar consistência e eficiência.

### Importância dos Padrões

1. **Consistência e Qualidade**: Padrões garantem que produtos e serviços atendam a critérios de qualidade específicos, proporcionando uma experiência uniforme aos consumidores.

2. **Compatibilidade e Interoperabilidade**: Facilitam a integração de sistemas e componentes de diferentes fabricantes, promovendo a interoperabilidade em tecnologias e serviços.

3. **Segurança**: Estabelecem diretrizes para assegurar a segurança em produtos, serviços e processos, minimizando riscos para os usuários.

4. **Eficiência e Produtividade**: Padronização de processos e metodologias pode aumentar a eficiência operacional e a produtividade ao eliminar variabilidades desnecessárias.

5. **Inovação e Competitividade**: Ao criar uma base comum de entendimento, padrões podem acelerar a inovação, permitindo que empresas foquem em melhorias incrementais e disruptivas em vez de re-inventar soluções básicas.

### Aplicabilidade dos Padrões em Diversos Segmentos

1. **Tecnologia da Informação**:
   - **Protocolos de Internet** (ex.: HTTP, TCP/IP): Asseguram que diferentes dispositivos e sistemas possam se comunicar eficazmente.
   - **Padrões de Codificação** (ex.: Java, Python): Promovem legibilidade, manutenção e colaboração no desenvolvimento de software.
   - **Segurança da Informação** (ex.: ISO/IEC 27001): Estabelecem práticas para proteger dados e informações sensíveis.

2. **Construção Civil**:
   - **Normas de Engenharia** (ex.: Eurocode, ABNT): Garantem segurança estrutural e a durabilidade de edificações.
   - **Padrões de Sustentabilidade** (ex.: LEED): Promovem práticas de construção sustentáveis e ambientalmente responsáveis.

3. **Saúde**:
   - **Normas de Equipamentos Médicos** (ex.: ISO 13485): Asseguram a qualidade e segurança de dispositivos médicos.
   - **Protocolos de Tratamento** (ex.: Guidelines clínicas): Padronizam cuidados e tratamentos médicos para garantir a eficácia e segurança dos pacientes.

4. **Indústria Alimentícia**:
   - **Padrões de Segurança Alimentar** (ex.: HACCP, ISO 22000): Asseguram que os alimentos são seguros para o consumo.
   - **Rotulagem de Alimentos**: Padronizam a forma como informações nutricionais e de ingredientes são apresentadas aos consumidores.

5. **Educação**:
   - **Currículos Padronizados**: Asseguram uma base comum de conhecimento e habilidades que todos os alunos devem adquirir.
   - **Avaliações Padronizadas**: Permitem a medição uniforme do desempenho acadêmico em diferentes regiões ou países.

### Importância dos Padrões na Engenharia de Software e Computação

Os padrões na engenharia de software e computação são fundamentais para garantir a qualidade, a manutenção e a interoperabilidade de sistemas e aplicações. Abaixo estão os principais aspectos que destacam a importância desses padrões:

1. **Qualidade do Software**:
   - **Consistência**: Padrões garantem que o código seja escrito de forma consistente, facilitando a leitura e a compreensão por diferentes desenvolvedores.
   - **Reutilização**: Promovem a criação de componentes reutilizáveis, economizando tempo e recursos no desenvolvimento de novos projetos.
   - **Testabilidade**: Padrões ajudam a garantir que o software seja fácil de testar e depurar, melhorando a qualidade final do produto.

2. **Manutenção e Evolução**:
   - **Facilidade de Manutenção**: Um código padronizado é mais fácil de manter e atualizar, permitindo que novas funcionalidades sejam adicionadas com menos risco de introduzir erros.
   - **Documentação e Treinamento**: Padrões ajudam a criar uma documentação clara e uniforme, facilitando o treinamento de novos membros da equipe e a transferência de conhecimento.

3. **Interoperabilidade e Integração**:
   - **Compatibilidade**: Padrões garantem que diferentes sistemas e componentes possam trabalhar juntos de forma eficaz, promovendo a interoperabilidade entre tecnologias heterogêneas.
   - **APIs e Protocolos**: Padrões de APIs e protocolos de comunicação facilitam a integração de sistemas, tanto internamente quanto com terceiros.

4. **Segurança**:
   - **Práticas de Codificação Segura**: Padrões de segurança ajudam a evitar vulnerabilidades comuns no software, protegendo contra ataques e violações de dados.
   - **Conformidade**: Padrões garantem que o software esteja em conformidade com regulamentos e normas de segurança, reduzindo riscos legais e financeiros.

5. **Eficiência no Desenvolvimento**:
   - **Automação e Ferramentas**: Padrões permitem a criação de ferramentas de automação que aceleram o desenvolvimento e a entrega de software, como linters e formatadores de código.
   - **Metodologias Ágeis**: Padrões são essenciais para implementar metodologias ágeis, facilitando a colaboração e a entrega contínua de valor.

### Exemplos de Padrões na Engenharia de Software e Computação

1. **Padrões de Codificação**:
   - **Java Coding Conventions**: Práticas recomendadas para escrever código Java, promovendo consistência e legibilidade.
   - **PEP 8**: Guia de estilo para Python, assegurando que o código Python seja consistente e fácil de entender.

2. **Padrões de Design**:
   - **Design Patterns (Padrões de Projeto)**: Soluções comprovadas para problemas recorrentes de design, como Singleton, Factory e Observer, que melhoram a robustez e a flexibilidade do software.
   - **Arquitetura de Software**: Padrões arquiteturais como MVC (Model-View-Controller), Microservices e Event-Driven Architecture ajudam a estruturar sistemas complexos de maneira eficaz.

3. **Padrões de Teste**:
   - **Unit Testing**: Práticas e frameworks para testar unidades individuais de código, garantindo que cada componente funcione isoladamente.
   - **Continuous Integration/Continuous Deployment (CI/CD)**: Padrões para integração e entrega contínuas, automatizando o processo de construção, teste e implantação de software.

4. **Padrões de Segurança**:
   - **OWASP Top Ten**: Lista dos dez principais riscos de segurança em aplicativos web, fornecendo diretrizes para evitar vulnerabilidades comuns.
   - **ISO/IEC 27001**: Padrões para sistemas de gestão de segurança da informação, assegurando a proteção de dados sensíveis.

5. **Padrões de Documentação**:
   - **Javadoc**: Ferramenta para gerar documentação de API a partir de comentários no código Java, promovendo uma documentação clara e acessível.
   - **Markdown**: Formato leve para criar documentação legível em diversos contextos, facilitando a criação de documentos técnicos e tutoriais.

### Conclusão

Padrões na engenharia de software e computação são vitais para assegurar que o desenvolvimento de software seja eficiente, seguro e de alta qualidade. Eles facilitam a colaboração, a manutenção e a escalabilidade de sistemas, além de promoverem a interoperabilidade e a inovação. A adoção de padrões é uma prática essencial para qualquer equipe de desenvolvimento que deseja entregar software robusto e confiável.

Padrões são essenciais para a coesão, eficiência e qualidade em praticamente todos os setores da sociedade. Eles facilitam a inovação, garantem a segurança e promovem a confiança dos consumidores, desempenhando um papel fundamental na economia global.

### Padrões de Design na Engenharia de Software

#### Definição de Padrões de Design

Padrões de design (ou padrões de projeto) são soluções comprovadas para problemas recorrentes no design de software. Eles fornecem uma estrutura que ajuda a resolver problemas de maneira eficiente e são baseados em práticas de engenharia que foram testadas e validadas ao longo do tempo.

#### Importância dos Padrões de Design

1. **Reutilização de Soluções**: Padrões de design permitem a reutilização de soluções testadas, economizando tempo e esforço no desenvolvimento de novos sistemas.
2. **Consistência**: Promovem consistência no design e na implementação, facilitando a leitura e manutenção do código.
3. **Comunicação**: Fornecem um vocabulário comum para desenvolvedores, facilitando a comunicação e o entendimento entre membros da equipe.
4. **Manutenibilidade**: Melhoram a manutenibilidade do software ao promover boas práticas de design que facilitam a modificação e extensão do código.
5. **Robustez e Flexibilidade**: Ajudam a criar sistemas mais robustos e flexíveis, preparados para lidar com mudanças e novos requisitos.

#### Exemplos de Padrões de Design

1. **Criacionais**:
   - **Singleton**: Garante que uma classe tenha apenas uma instância e fornece um ponto de acesso global a essa instância.
   - **Factory Method**: Define uma interface para criar um objeto, mas permite que as subclasses alterem o tipo de objeto que será criado.

2. **Estruturais**:
   - **Adapter**: Permite que interfaces incompatíveis trabalhem juntas, convertendo a interface de uma classe em outra que um cliente espera.
   - **Composite**: Compõe objetos em estruturas de árvore para representar hierarquias parte-todo, permitindo que clientes tratem objetos individuais e composições de objetos de maneira uniforme.

3. **Comportamentais**:
   - **Observer**: Define uma dependência um-para-muitos entre objetos, de modo que quando um objeto muda de estado, todos os seus dependentes são notificados e atualizados automaticamente.
   - **Strategy**: Define uma família de algoritmos, encapsula cada um deles e os torna intercambiáveis. O padrão Strategy permite que o algoritmo varie independentemente dos clientes que o utilizam.

### Anti Padrões na Engenharia de Software

#### Definição de Anti Padrões

Anti padrões são soluções que parecem ser eficazes, mas na prática causam mais problemas do que resolvem. Eles são práticas comuns que resultam em código difícil de manter, escalar e entender, levando a sistemas ineficientes e problemáticos.

#### Identificação e Impacto dos Anti Padrões

1. **Código Espaguete**:
   - **Descrição**: Código desorganizado e não estruturado, onde o fluxo de controle é complicado e difícil de seguir.
   - **Impacto**: Dificulta a manutenção e a adição de novas funcionalidades, aumentando o risco de introdução de erros.

2. **Objeto Deus**:
   - **Descrição**: Uma classe que sabe demais ou faz demais, centralizando muita funcionalidade e conhecimento do sistema.
   - **Impacto**: Torna o sistema rígido e difícil de modificar, além de dificultar a reutilização de código.

3. **Carga de Magia**:
   - **Descrição**: Uso excessivo de frameworks ou bibliotecas sem compreensão clara do que está acontecendo por trás.
   - **Impacto**: Resulta em dificuldades de depuração e manutenção, pois o comportamento do sistema pode ser imprevisível.

4. **Copiar e Colar Programação**:
   - **Descrição**: Duplicação de código ao invés de abstrair e reutilizar componentes.
   - **Impacto**: Aumenta a quantidade de código para manter e sincronizar, introduzindo inconsistências e bugs.

5. **Prematuro Otimização**:
   - **Descrição**: Otimização do código antes de identificar claramente onde os gargalos de desempenho estão.
   - **Impacto**: Pode levar a um código mais complexo e menos legível sem benefícios reais de desempenho.

### Contraponto: Quando Padrões se Tornam Anti Padrões

Padrões de design podem se tornar anti padrões quando usados incorretamente ou em contextos inadequados. Exemplos incluem:

1. **Aplicação Indevida**: Usar um padrão de design sem necessidade real pode complicar o sistema sem benefícios claros. Exemplo: usar um Singleton onde a criação de múltiplas instâncias não apresenta problema.

2. **Complexidade Desnecessária**: Implementar padrões de design em sistemas simples pode introduzir complexidade desnecessária. Exemplo: usar padrões de composição complexos em aplicações que não exigem flexibilidade futura.

3. **Overengineering**: Superengenharia ocorre quando padrões são aplicados para prever necessidades futuras que podem nunca ocorrer, resultando em código excessivamente complexo. Exemplo: criar uma arquitetura de microservices para uma aplicação pequena e monolítica.

### Conclusão

Padrões de design são ferramentas poderosas na engenharia de software, proporcionando soluções comprovadas para problemas recorrentes e melhorando a qualidade, manutenibilidade e flexibilidade do software. No entanto, é crucial aplicar esses padrões de maneira apropriada e no contexto correto para evitar que se tornem anti padrões, que podem introduzir problemas e complicar o desenvolvimento e a manutenção do software. A chave está em entender profundamente tanto os padrões quanto os requisitos do sistema, garantindo que as soluções adotadas sejam as mais adequadas para o problema em questão.

### Padrões de Projeto (Design Patterns)

#### Padrões Criacionais

1. **Factory Method**
   - **Propósito**: Definir uma interface para criar um objeto, mas deixar que subclasses decidam qual classe instanciar. O Factory Method permite a uma classe deferir a instanciação para subclasses.
   - **Características**: Desacopla a criação do objeto do seu uso. Oferece uma forma de encapsular a instância de objetos.

2. **Abstract Factory**
   - **Propósito**: Fornecer uma interface para criar famílias de objetos relacionados ou dependentes sem especificar suas classes concretas.
   - **Características**: Permite que um sistema seja configurado com múltiplas famílias de produtos. Facilita a troca de "famílias" de produtos.

3. **Builder**
   - **Propósito**: Separar a construção de um objeto complexo da sua representação, permitindo que o mesmo processo de construção crie diferentes representações.
   - **Características**: Utilizado para criar objetos complexos passo a passo. Promove a reutilização de código ao encapsular a lógica de construção.

4. **Prototype**
   - **Propósito**: Especificar os tipos de objetos a serem criados usando uma instância prototípica e criar novos objetos copiando este protótipo.
   - **Características**: Utiliza a clonagem para criar novos objetos. Reduz a necessidade de subclasses que criam instâncias.

5. **Singleton**
   - **Propósito**: Garantir que uma classe tenha apenas uma instância e fornecer um ponto global de acesso a essa instância.
   - **Características**: Controla a criação de objetos e garante uma única instância. Muito usado para gerenciar recursos compartilhados.

#### Padrões Estruturais

6. **Adapter**
   - **Propósito**: Converter a interface de uma classe em outra interface esperada pelos clientes, permitindo que classes trabalhem juntas que não poderiam de outra forma por incompatibilidade de interfaces.
   - **Características**: Atua como um intermediário entre duas interfaces incompatíveis. Promove a reutilização de código legado.

7. **Bridge**
   - **Propósito**: Desacoplar uma abstração de sua implementação para que os dois possam variar independentemente.
   - **Características**: Promove a flexibilidade ao dividir um grande conjunto de classes em dois conjuntos de hierarquias. Facilita a extensão de ambas as hierarquias.

8. **Composite**
   - **Propósito**: Compor objetos em estruturas de árvore para representar hierarquias parte-todo, permitindo que os clientes tratem objetos individuais e composições de objetos de maneira uniforme.
   - **Características**: Facilita a criação de estruturas de dados complexas. Promove a uniformidade ao tratar objetos individuais e agregados da mesma forma.

9. **Decorator**
   - **Propósito**: Anexar responsabilidades adicionais a um objeto dinamicamente. Decorators fornecem uma alternativa flexível ao uso de subclasses para extensão de funcionalidades.
   - **Características**: Permite a adição de funcionalidades de forma dinâmica. Mantém a interface do objeto original.

10. **Facade**
    - **Propósito**: Fornecer uma interface unificada para um conjunto de interfaces em um subsistema, facilitando seu uso.
    - **Características**: Simplifica a complexidade de um subsistema. Fornece uma interface única e fácil de usar.

11. **Flyweight**
    - **Propósito**: Usar compartilhamento para suportar grandes quantidades de objetos de forma eficiente.
    - **Características**: Reduz o consumo de memória ao compartilhar objetos comuns. Utilizado quando muitos objetos pequenos são necessários.

12. **Proxy**
    - **Propósito**: Fornecer um substituto ou marcador para outro objeto para controlar o acesso a ele.
    - **Características**: Controla o acesso a um objeto, fornecendo um nível de indireção. Pode adicionar funcionalidade adicional ao objeto.

#### Padrões Comportamentais

13. **Chain of Responsibility**
    - **Propósito**: Evitar o acoplamento do remetente de uma solicitação ao seu receptor, permitindo que mais de um objeto trate a solicitação. Encadear os objetos receptores e passar a solicitação ao longo da cadeia até que um objeto a trate.
    - **Características**: Permite que múltiplos objetos possam responder a uma solicitação. Promove a flexibilidade ao dinamicamente mudar o objeto que trata a solicitação.

14. **Command**
    - **Propósito**: Encapsular uma solicitação como um objeto, permitindo parametrizar clientes com diferentes solicitações, filas ou registros de solicitações e suporte para operações que podem ser desfeitas.
    - **Características**: Encapsula uma solicitação em um objeto. Facilita a implementação de operações de desfazer e refazer.

15. **Interpreter**
    - **Propósito**: Dada uma linguagem, definir uma representação para sua gramática junto com um interpretador que usa a representação para interpretar sentenças na linguagem.
    - **Características**: Facilita a adição de novas linguagens e novos comportamentos. Utilizado em sistemas que requerem a interpretação de expressões ou comandos.

16. **Iterator**
    - **Propósito**: Fornecer um meio de acessar sequencialmente os elementos de um agregado sem expor sua representação subjacente.
    - **Características**: Desacopla a iteração sobre uma coleção da coleção em si. Promove a flexibilidade na forma como as coleções são percorridas.

17. **Mediator**
    - **Propósito**: Definir um objeto que encapsula como um conjunto de objetos interage. Promover o acoplamento fraco ao impedir que os objetos se refiram explicitamente uns aos outros.
    - **Características**: Centraliza a comunicação entre objetos. Reduz o acoplamento entre classes.

18. **Memento**
    - **Propósito**: Sem violar o encapsulamento, capturar e externalizar o estado interno de um objeto para que o objeto possa ser restaurado a esse estado mais tarde.
    - **Características**: Permite restaurar um objeto ao seu estado anterior. Útil para implementações de desfazer e refazer.

19. **Observer**
    - **Propósito**: Definir uma dependência um-para-muitos entre objetos de modo que quando um objeto muda de estado, todos os seus dependentes são notificados e atualizados automaticamente.
    - **Características**: Facilita a implementação de notificações automáticas. Promove a desacoplamento entre o sujeito e seus observadores.

20. **State**
    - **Propósito**: Permitir que um objeto altere seu comportamento quando seu estado interno muda. O objeto parecerá ter mudado sua classe.
    - **Características**: Encapsula estados e comportamentos associados. Promove a clareza e a organização do código relacionado a estados.

21. **Strategy**
    - **Propósito**: Definir uma família de algoritmos, encapsular cada um deles e torná-los intercambiáveis. O padrão Strategy permite que o algoritmo varie independentemente dos clientes que o utilizam.
    - **Características**: Encapsula algoritmos em classes separadas. Promove a flexibilidade na escolha do algoritmo a ser usado.

22. **Template Method**
    - **Propósito**: Definir o esqueleto de um algoritmo em uma operação, adiando alguns passos para subclasses. O Template Method permite que subclasses redefinam certos passos de um algoritmo sem alterar sua estrutura.
    - **Características**: Promove a reutilização de código ao definir o esqueleto do algoritmo. Facilita a definição de partes variáveis do algoritmo.

23. **Visitor**
    - **Propósito**: Representar uma operação a ser realizada nos elementos de uma estrutura de objeto. O Visitor permite definir uma nova operação sem mudar as classes dos elementos sobre os quais opera.
    - **Características**: Facilita a adição de novas operações. Promove a separação entre operações e a estrutura de dados.

### Conclusão

Os padrões de design são ferramentas essenciais na engenharia de software, proporcionando soluções bem definidas para problemas comuns de design. Eles promovem a reutilização de código, a manutenibilidade, a flexibilidade e a clareza no desenvolvimento de software. No entanto, é importante usar esses padrões de maneira apropriada, evitando sua aplicação indiscriminada para não introduzir complexidade desnecessária.
