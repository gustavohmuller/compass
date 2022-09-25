## Perguntas

#### 1.	Para que serve o método Scrum?

O Scrum é um *framework* ágil e a sua principal característica é trabalhar com *time-boxes*: caixas de tempo de tamanho definido que não muda durante a Sprint atual.

#### 2.	Como funciona o método Scrum?

O Scrum é composto por Sprints, que são os *time-boxes* base do Scrum. A Sprint contém diversas etapas: no início há uma reunião para decidir o que fazer, chamada de *Planning*. A maior parte é ocupada pelo desenvolvimento em si, parando todos os dias para fazer a *Daily Scrum* (reunião diária). E, por fim, ocorre a *Review Meeting* (reunião de revisão) para revisar o que foi feito e a *Retrospective* (retrospectiva), que é a parte dedicada à melhoria contínua.

#### 3.	O que é Git?

O Git é um sistema de controle de versões.

#### 4.	O que é um Scrum *Product Owner*? 

O *Product Owner* é o representante do cliente em um time de Scrum. Ele é quem escutará as diversas opiniões dos clientes e chegará em funcionalidades que façam sentido para os negócios, de maneira a maximizar valor, captando ideias e prioridades do cliente.

#### 5.	Qual o comando para criação de um novo repositório no Git?

Para a criação de um novo repositório no Git utiliza-se o comando `git init`.

#### 6.	Com o Git você pode propor mudanças (adicioná-las ao *Index*) usando um comando. Qual é esse comando?

Para propor mudanças (adicioná-las ao *Index*) no Git utiliza-se o comando `git add`.

#### 7.	O que é a *branch* `master` e para que serve?

A *branch* `master` (agora chamada de `main`) é a *branch* “padrão” quando se cria um repositório. É interessante separar o desenvolvimento de funcionalidades em *branches* diferentes para que as mudanças no código para uma não influenciem no funcionamento de outra.

#### 8.	Quais são os comandos usados para atualizar um repositório local e fazer *merge* de um outro *branch* ao seu *branch* ativo?

Para atualizar um repositório local utiliza-se o comando `git pull` e para fazer *merge* de um outro *branch* ao seu *branch* ativo utiliza-se o comando `git merge`.

#### 9.	Qual a diferença entre Git e GitHub?

O Git é um sistema de controle de versões e o GitHub é um serviço que fornece a possibilidade de se criar repositórios Git.

#### 10. Quais os dois verbos http que podemos utilizar para realizar um *update*? Explique a diferença entre eles.

Os dois verbos http que se pode utilizar para realizar um *update* são: PUT e PATCH. O verbo PUT deve passar todos os dados do recurso preenchidos, independente de quais dados foram de fato editados, e o verbo PATCH é utilizado para editar o recurso sem a necessidade de enviar todos os atributos, encaminha-se apenas aqueles que de fato foram alterados.

#### 11. Qual o *status code* que pode ser usado na criação de um novo usuário?

O *status code* que pode ser usado na criação de um novo usuário é o 201 (*Created*).

#### 12. Quais são os três *status code* que podem ser utilizados para realizar o *delete*?

Os três *status code* que podem ser utilizados para realizar o *delete* são: 200 (*OK*), 202 (*Accepted*) e 204 (*No Content*).

#### 13. Exemplifique para que servem os *status code* http 1XX, 2XX, 3XX, 4XX e 5XX de uma forma macro (geral)!

* 1XX: informativo – a solicitação foi aceita ou o processo continua em andamento;
* 2XX: confirmação – a ação foi concluída ou entendida;
* 3XX: redirecionamento – indica que algo mais precisa ser feito ou precisou ser feito para completar a solicitação;
* 4XX: erro do cliente – indica que a solicitação não pode ser concluída ou contém a sintaxe incorreta;
* 5XX: erro no servidor – o servidor falhou ao concluir a solicitação.

#### 14. O que é a linguagem de programação Dart?

Dart é uma linguagem de programação criada para nos comunicarmos com a máquina. Ela é interoperável, ou seja, consegue se comunicar com outra linguagem, orientada a objetos, conta com uma sintaxe muito simples e uma ótima performance.

#### 15. O que é o Flutter?

Flutter é um *toolkit* que permite construir aplicações e compilar de maneira nativa para ambiente *mobile*, *web* e *desktop*.

#### 16. Como inicio um novo projeto com Flutter?

Para iniciar um novo projeto com Flutter utiliza-se o comando `flutter create` em um prompt ou terminal.

#### 17. Quais ferramentas podemos utilizar para criação de novos *apps* usando Flutter?

Não há uma ferramenta própria do Flutter para o desenvolvimento de aplicativos, mas existem ferramentas que atualmente são muito utilizadas pela maioria dos desenvolvedores, como o Android Studio, IntelliJ ou Visual Studio Code.

#### 18. Qual a diferença entre uma variável `final` e uma variável `var`?

Uma variável `final` não permite que o seu valor seja alterado e uma variável `var` reconhece o tipo da variável conforme o seu valor.

#### 19. Qual a diferença entre um `Statefull` e `Stateless` *widget*?

O `Statefull` é um *widget* completamente dinâmico que dá o poder de torná-lo mutável através da gerência de estados e o `Stateless` é um *widget* estático, ou seja, não há como gerenciar o estado dele.

#### 20. Para que serve o conceito de gerenciamento de estado e como ele pode ser aplicado na prática?

O gerenciamento de estado é responsável por observar um certo objeto e notificar todos os componentes interessados se esse objeto mudou, para que eles se atualizem.

#### 21. Qual a finalidade dos métodos `initState` e `dispose`?

O método `initState` é chamado na criação do *widget*, quando o *widget* é inserido na *widget tree*, e o método `dispose` é chamado quando o *widget* for removido da *widget tree* permanentemente.

#### 22. Conta para a gente como foi sua experiência na Sprint#01 do programa de bolsas @Flutter-set.22 e quais suas expectativas a partir de agora.

Na Sprint#01 do programa de bolsas @Flutter-set.22 pude aprender um pouco sobre metodologias ágeis, com foco no Scrum, Dart, Flutter e Git e GitHub. Minhas expectativas a partir de agora são aprimorar esses conhecimentos e colocá-los em prática nos projetos das próximas Sprints.