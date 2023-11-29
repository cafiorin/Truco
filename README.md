Descri ̧c ̃ao do Projeto
Neste projeto final, vocˆe deve criar um jogo de Truco em C++ que incorpora e demonstra de forma abrangente
os princ ́ıpios da Programa ̧c ̃ao Orientada a Objetos (OO). O jogo de Truco deve ser totalmente funcional, com
suporte para dois jogadores humanos e implementar todas as regras do jogo de Truco.
Conceitos de OO
1. Classes e Heran ̧ca:
• Organize o projeto em classes que representem os elementos do jogo, como jogadores, cartas, rodadas,
entre outros. Utilize heran ̧ca quando aplic ́avel para modelar rela ̧c ̃oes de especializa ̧c ̃ao entre as classes,
como classes para diferentes tipos de cartas.
2. Polimorfismo:
• Aplique o polimorfismo para permitir o tratamento gen ́erico de objetos, como cartas. Isso pode ser
feito atrav ́es de fun ̧c ̃oes virtuais em classes base, permitindo diferentes implementa ̧c ̃oes em classes
derivadas, se necess ́ario.
3. Encapsulamento:
• Mantenha os detalhes de implementa ̧c ̃ao ocultos e forne ̧ca interfaces bem definidas para interagir com
as classes. Isso inclui o acesso aos membros de classe (utilize modificadores de acesso como public,
private e protected) e o uso de getters e setters quando apropriado.
4. Abstra ̧c ̃ao:
• Abstraia os conceitos do jogo de Truco em classes que representem entidades reais, como jogadores,
cartas e partidas. Isso permite que o c ́odigo seja mais f ́acil de entender e manter.
Concorrˆencia e Multithreading
5. Integra ̧c ̃ao de Threads:
• Integre threads de maneira significativa para realizar opera ̧c ̃oes em paralelo, como a execu ̧c ̃ao das

a ̧c ̃oes dos jogadores e a contagem de pontos, demonstrando a aplica ̧c ̃ao dos conceitos de multithread-
ing. Por exemplo, permita que os jogadores fa ̧cam suas escolhas simultaneamente.

6. T ́ecnicas de Sincroniza ̧c ̃ao:

• Utilize t ́ecnicas de sincroniza ̧c ̃ao e exclus ̃ao m ́utua para garantir a integridade dos dados compartilha-
dos entre threads, evitando problemas como condi ̧c ̃oes de corrida. Analise cuidadosamente seu c ́odigo

em busca de poss ́ıveis condi ̧c ̃oes de corrida, onde duas ou mais threads podem acessar os mesmos
dados simultaneamente. Utilize exclus ̃ao m ́utua para evitar essas condi ̧c ̃oes de corrida, garantindo
que as opera ̧c ̃oes cr ́ıticas sejam feitas de forma segura e ordenada.
Tratamento de Exce ̧c ̃ao
7. Implementa ̧c ̃ao de Tratamento de Exce ̧c ̃oes:
• Implemente tratamento de exce ̧c ̃oes para lidar com erros e situa ̧c ̃oes excepcionais durante a execu ̧c ̃ao
do jogo, como movimentos inv ́alidos dos jogadores ou problemas de aloca ̧c ̃ao de mem ́oria.

1

Interface de Usu ́ario
8. Cria ̧c ̃ao de Interface de Usu ́ario:
• Crie uma interface de usu ́ario amig ́avel que permita aos jogadores interagirem com o jogo de Truco
de forma intuitiva. Utilize a Win32 API (ou MFC) para criar e gerenciar janelas, controles e eventos,
fornecendo uma experiˆencia de usu ́ario agrad ́avel. Isso inclui a representa ̧c ̃ao gr ́afica das cartas,
placar e mensagens informativas.
Utiliza ̧c ̃ao Adequada de Smart Pointers
9. Utiliza ̧c ̃ao de Smart Pointers:
• Utilize smart pointers para gerenciar objetos que requerem aloca ̧c ̃ao dinˆamica de mem ́oria, como
instˆancias de jogadores ou recursos dinˆamicos. Garanta que a utiliza ̧c ̃ao dos smart pointers seja
aplicada de forma apropriada para gerenciar a vida  ́util dos objetos, evitando vazamentos de mem ́oria
e garantindo a libera ̧c ̃ao autom ́atica de recursos quando n ̃ao mais necess ́arios.
Serializa ̧c ̃ao e Persistˆencia
10. Serializa ̧c ̃ao e Persistˆencia:
• Implemente a serializa ̧c ̃ao de dados do jogo para permitir que os jogadores salvem e carreguem
partidas de Truco em qualquer ponto do jogo. Utilize t ́ecnicas de serializa ̧c ̃ao para gravar e ler dados
do jogo em arquivos, garantindo a capacidade de persistˆencia. Utilize std::filesystem para eventuais
manipula ̧c ̃oes de diret ́orios, como salvar e carregar partidas em pastas espec ́ıficas.
Padr ̃ao arquitetural
11. Implementa ̧c ̃ao de padr ̃ao arquitetural:

• Implemente um padr ̃ao arquitetural em sua solu ̧c ̃ao de forma a organizar o c ́odigo visando po-
tencializar propriedades importantes de OO. Espera-se aqui que seja implementado ou o padr ̃ao

arquitetural MVC ou MVVM.
Documenta ̧c ̃ao
12. Gera ̧c ̃ao de documenta ̧c ̃ao:

• Deve ser gerado um documento descrevendo os requisitos do sistema. O documento deve seguir o tem-
plate disponibilizado no arquivo anexo a essa atividade (Exemplo Requisitos ProjetoFinal.docx)

• Al ́em da documenta ̧c ̃ao interna do c ́odigo e o documento de requisitos, vocˆes devem gerar diagramas
e esquem ́aticos do projeto. Pelo menos deve ser entregue o diagrama de classes do projeto. Tamb ́em
 ́e recomendada a entrega de fluxograma e/ou diagramas de sequˆencia de partes espec ́ıficas do projeto.
• Toda a documenta ̧c ̃ao deve estar identificada no README.md do reposit ́orio.
Grupos
• O projeto dever ́a ser realizado em grupo de 4 pessoas.
• Os grupos previamente definidos est ̃ao no arquivo Grupos.pdf tamb ́em junto a essa atividade.
• Os grupos foram definidos pelo SiDi de forma a balancear a experiˆencia da equipe.
• Os l ́ıderes de cada grupo est ̃ao marcados em verde e ser ̃ao respons ́aveis pela cria ̧c ̃ao do reposit ́orio, bem
como o envio do link do projeto no Github que ser ́a usado para a entrega.

2

Crit ́erios de Avalia ̧c ̃ao
Seu projeto ser ́a avaliado com base nos seguintes crit ́erios:
1. Organiza ̧c ̃ao e estrutura do c ́odigo, demonstrando a aplica ̧c ̃ao efetiva dos princ ́ıpios da Programa ̧c ̃ao
Orientada a Objetos.

2. Utiliza ̧c ̃ao apropriada dos conceitos de C++ aprendidos no curso, com ˆenfase em multithreading, trata-
mento de exce ̧c ̃ao, interface de usu ́ario, smart pointers e serializa ̧c ̃ao.

3. Eficiˆencia do c ́odigo para garantir um desempenho significativo, demonstrando a aplica ̧c ̃ao pr ́atica dos
conceitos de threads e smart pointers.
4. Coment ́arios explicativos ao longo do c ́odigo, destacando a aplica ̧c ̃ao dos t ́opicos aprendidos no curso.
Entrega
• Deve ser criado um reposit ́orio para o projeto no Github. A entrega final deve ser identificada por uma
Github tag.
• As informa ̧c ̃oes relevantes sobre o software, bem como o n ́umero do grupo e o nome dos membros que
realizaram a entrega devem estar no arquivo README.md.
• O reposit ́orio deve estar acess ́ıvel para a nossa corre ̧c ̃ao.
• A planilha com o link do projeto no Github dever ́a ser preenchida at ́e a data de entrega apenas pelo
l ́ıder da equipe.
• A data da tag ser ́a checada para avaliar o momento da entrega.

Data de entrega: 26/01/2024 at ́e 23h59.
