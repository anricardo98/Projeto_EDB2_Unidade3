Projeto de Estrutura de Dados Básico II

Alunos: André Ricardo Cândido Silva e Erildo Gomes de Medeiros Júnior Costa

Professor: Leonardo Cesar Teonacio Bezerra

Descrição do projeto:
Neste projeto, o grupo foi instruído a implementar dois tipos de árvores mostradas em sala de aula, sendo elas:
- A árvore AVL, implementada por André.
- A árvore de Prefixos, implementada por Erildo.
	
Ambos os projetos foram desenvolvidos utilizando a linguagem python.

Árvore AVL:

- Apresenta duas classes, sendo elas no_AVL e a classe Arvore_AVL, além de duas funções externas.
classe no_AVL apresenta como métodos:

- buscar: responsável pela localização de um determinado nó na árvore.
- inserir: Responsável pela inserção de um filho em determinado nó.
- remover: realiza a remoção do nó indicado.
- buscar_maior: Busca o maior membro da árvore a partir de determinado nó.
- antecessor: Busca o elemento antecessor ao nó indicado.

classe Arvore_AVL:
- buscar: fazendo uso da busca anterior, devolve o nó com a chave indicada.
- inserir: responsável pela criação do nó e inserção deste na árvore.
- remover: responsável pela remoção de um nó da árvore.
- rotação_direita: responsável por realizar a rotação direita na árvore
- rotação_esquerda: responsável por realizar a rotação esquerda na árvore
- balanceamento: fazendo uso das duas funções últimas funções citadas, realiza o balanceamento da árvore.

Árvore de Préfixos:

A árvore de Prefixos, ou árvore trie, é uma estrutura de dados do tipo árvore ordenada, que pode ser usada para armazenar um array associativo em que as chaves são, normalmente, cadeias de caracteres.


No seu código, a árvore foi implementado contendo as seguintes funções:
- add_palavra: responsável por adicionar uma única palavra a árvore.
- add_palavras: responsável por adicionar uma lista de palavras a árvore
- busca: realiza a busca de determinada palavra na árvore, importante notar que só será identificada a palavra que estiver por completo na arvore.
	remove_palavra: responsável por remover uma palavra completa da arvore.   