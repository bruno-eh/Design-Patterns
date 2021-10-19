# Design-Patterns

## 1)	O que é um padrão de projeto?
Resumidamente um padrão de projetos ou mais conhecido como Design Patterns são soluções generalistas para problemas recorrentes durante o desenvolvimento de um software. Não se trata de um framework ou um código pronto, mas de uma definição de alto nível de como um problema comum pode ser solucionado.
Porém nem toda solução para um problema em um certo contexto, necessariamente constituirá um padrão, pois é necessário que ela tenha como característica a regularidade, isto é, ela será um padrão caso puder ser utilizada repetidamente.

## 2)	Por que devo aprender padrões?
Devemos aprender e utilizar os padrões de projetos, pois são modelos que já foram utilizados e testados anteriormente, sendo assim podendo representar um bom ganho de produtividade para quem o utiliza. Além do ganho de produtividade, ele também contribui para uma melhor organização e manutenção de projetos, pois esses padrões se baseiam em pouca dependência entre as classes e padronização do código. Além de que com a padronização dos termos, as discussões técnicas são muito mais facilitadas.

## 3)	Quais as características de um bom projeto de software?
Pode-se definir várias características para um bom projeto de software, mas algumas delas são:  

**•	Funcionalidade:** Diz respeito à satisfação das necessidades que deram origem ao projeto. Abrange requisitos implícitos e explícitos e está intimamente ligada à qualidade do código criado.  

**•	Adequação:**  O produto deve estar de acordo com o objetivo que originou sua demanda.  

**•	Interoperabilidade:** Um software de qualidade deve suportar a integração com outras ferramentas, mesmo que não sejam desenvolvidas pela mesma empresa. Tem que ser capaz de interagir com outros sistemas e ser desenvolvido a partir de uma linguagem de programação mais abrangente.  

**•	Segurança:** O software é acessível a qualquer pessoa ou exige uma gestão de identidade e acesso que disponibilize a informação somente para pessoas a quem compete sua visualização? É vulnerável ou constantemente atualizado para ser apto a mitigar ameaças e intrusões? Essas e muitas outras questões devem ser avaliadas antes de classificar o que é um bom software para não colocar em risco a segurança de toda uma organização.  

**•	Conformidade:** Hoje em dia, é necessário que o software esteja de acordo com a legislação que regula a atividade para o qual ele será utilizado. Além disso, precisa ser desenvolvido em conformidade com as leis que regulamentam o setor de TI, em especial a LGPD (Lei Geral de Proteção de Dados).  

**•	Usabilidade:**  O software precisa ser de fácil utilização, principalmente porque a grande maioria dos usuários não entende de linguagem de programação.  

**•	Inteligibilidade:** Compreender o objetivo do uso de um software é o primeiro passo para valorizar os recursos disponíveis e viabilizar os resultados esperados pela implementação da solução.  

**•	Eficiência:** Um nível de desempenho mínimo e máximo para o software devem ser delimitados no início do projeto.  

**•	Manutenibilidade:** A facilidade com que as correções podem ser implementadas também diz muito sobre a qualidade do software.
Fora muitas outras características.  

Além disso, a realização de uma boa documentação abrangente permite manter essa escalabilidade e a continuidade do software, independentemente do desenvolvedor.

## 4)	O que são os princípios S.O.L.I.D.?
O S.O.L.I.D. é um acrônimo criado por Michael Feathers, após observar que cinco princípios da orientação a objetos e design de código criados por Robert C. Martin (a.k.a. Uncle Bob).
### [S] - Princípio da Responsabilidade Única
Esse princípio declara que uma classe deve ser especializada em um único assunto e possuir apenas uma responsabilidade dentro do software, ou seja, a classe deve ter uma única tarefa ou ação para executar.
### [O] - Princípio Aberto-Fechado
Esse princípio declara que os objetos ou entidades devem estar abertos para extensão, mas fechados para modificação, ou seja, quando novos comportamentos e recursos precisam ser adicionados no software, devemos estender e não alterar o código fonte original.
### [L] - Princípio da substituição de Liskov
Uma classe derivada deve ser substituível por sua classe base. Ou seja, se S é um subtipo de T, então os objetos do tipo T, em um programa, podem ser substituídos pelos objetos de tipo S sem que seja necessário alterar as propriedades deste programa.
### [I] - Princípio da Segregação da Interface
Esse princípio basicamente diz que é melhor criar interfaces mais específicas ao invés de termos uma única interface genérica. Uma classe não deve ser forçada a implementar interfaces e métodos que não irão utilizar.
### [D] -Princípio da Inversão de Dependência
Esse princípio pode ser definido da seguinte forma: “Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender da abstração. E abstrações não devem depender de detalhes. Detalhes devem depender de abstrações. ” Resumindo, dependa de abstrações e não de implementações.

## 5)	O que são os padrões de projeto criacionais e seus tipos?
Os padrões criacionais fornecem vários mecanismos de criação de objetos, que aumentam a flexibilidade e reutilização de código já existente. Este padrão se subdivide divide em 5 subtipos:  

**1 - Factory Method:** é um padrão criacional de projeto que fornece uma interface para criar objetos em uma superclasse, mas permite que as subclasses alterem o tipo de objetos que serão criados.  

**2 - Abstract Factory:** é um padrão de projeto criacional que permite que você produza famílias de objetos relacionados sem ter que especificar suas classes concretas.  

**3 – Builder:** é um padrão de projeto criacional que permite a você construir objetos complexos passo a passo. O padrão permite que você produza diferentes tipos e representações de um objeto usando o mesmo código de construção.  

**4 – Prototype:** é um padrão de projeto criacional que permite copiar objetos existentes sem fazer seu código ficar dependente de suas classes.  

**5 – Singleton:** é um padrão de projeto criacional que permite a você garantir que uma classe tenha apenas uma instância, enquanto provê um ponto de acesso global para essa instância.

## 6)	O que são os padrões de projeto estruturais e seus tipos?
Os padrões estruturais explicam como montar objetos e classes em estruturas maiores, mas ainda mantendo essas estruturas flexíveis e eficientes. Este padrão se subdivide divide em 7 subtipos:  

**1 – Adapter:** é um padrão de projeto estrutural que permite objetos com interfaces incompatíveis colaborarem entre si.  

**2 – Bridge:** é um padrão de projeto estrutural que permite que você divida uma classe grande ou um conjunto de classes intimamente ligadas em duas hierarquias separadas—abstração e implementação—que podem ser desenvolvidas independentemente umas das outras.  

**3 – Composite:** é um padrão de projeto estrutural que permite que você componha objetos em estruturas de árvores e então trabalhe com essas estruturas como se elas fossem objetos individuais.  

**4 – Decorator:** é um padrão de projeto estrutural que permite que você acople novos comportamentos para objetos ao colocá-los dentro de invólucros de objetos que contém os comportamentos.  

**5 – Facade:** é um padrão de projeto estrutural que fornece uma interface simplificada para uma biblioteca, um framework, ou qualquer conjunto complexo de classes.  

**6 – Flyweight:** é um padrão de projeto estrutural que permite a você colocar mais objetos na quantidade de RAM disponível ao compartilhar partes comuns de estado entre os múltiplos objetos ao invés de manter todos os dados em cada objeto.  

**7 – Proxy:** é um padrão de projeto estrutural que permite que você forneça um substituto ou um espaço reservado para outro objeto. Um proxy controla o acesso ao objeto original, permitindo que você faça algo ou antes ou depois do pedido chegar ao objeto original.

## 7)	O que são os padrões de projeto comportamentais e seus tipos?
Padrões comportamentais são voltados aos algoritmos e a designação de responsabilidades entre objetos. Este padrão se subdivide divide em 10 subtipos:  

**1 - Chain of Responsibility:** é um padrão de projeto comportamental que permite que você passe pedidos por uma corrente de handlers. Ao receber um pedido, cada handler decide se processa o pedido ou o passa adiante para o próximo handler na corrente.  

**2 – Command:** é um padrão de projeto comportamental que transforma um pedido em um objeto independente que contém toda a informação sobre o pedido. Essa transformação permite que você parametrize métodos com diferentes pedidos, atrase ou coloque a execução do pedido em uma fila, e suporte operações que não podem ser feitas.  

**3 – Iterator:** é um padrão de projeto comportamental que permite a você percorrer elementos de uma coleção sem expor as representações dele (lista, pilha, árvore, etc.).  

**4 – Mediator:** é um padrão de projeto comportamental que permite que você reduza as dependências caóticas entre objetos. O padrão restringe comunicações diretas entre objetos e os força a colaborar apenas através do objeto mediador.  

**5 – Memento:** é um padrão de projeto comportamental que permite que você salve e restaure o estado anterior de um objeto sem revelar os detalhes de sua implementação.  

**6 – Observer:** é um padrão de projeto comportamental que permite que você defina um mecanismo de assinatura para notificar múltiplos objetos sobre quaisquer eventos que aconteçam com o objeto que eles estão observando.  

**7 – State:** é um padrão de projeto comportamental que permite que um objeto altere seu comportamento quando seu estado interno muda. Parece como se o objeto mudasse de classe.  

**8 – Strategy:** é um padrão de projeto comportamental que permite que você defina uma família de algoritmos, coloque-os em classes separadas, e faça os objetos deles intercambiáveis.  

**9 - Template Method:** é um padrão de projeto comportamental que define o esqueleto de um algoritmo na superclasse mas deixa as subclasses sobrescreverem etapas específicas do algoritmo sem modificar sua estrutura.  

**10 – Visitor:** é um padrão de projeto comportamental que permite que você separe algoritmos dos objetos nos quais eles operam.
