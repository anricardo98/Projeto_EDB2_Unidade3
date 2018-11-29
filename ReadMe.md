Projeto de Estrutura de Dados B�sico II

Alunos: Andr� Ricardo C�ndido Silva e Erildo Gomes de Medeiros J�nior Costa

Professor: Leonardo Cesar Teonacio Bezerra

Descri��o do projeto:
Neste projeto, o grupo foi instru�do a implementar dois tipos de �rvores mostradas em sala de aula, sendo elas:
- A �rvore AVL, implementada por Andr�.
- A �rvore de Prefixos, implementada por Erildo.
	
Ambos os projetos foram desenvolvidos utilizando a linguagem python.

�rvore AVL:

- Apresenta duas classes, sendo elas no_AVL e a classe Arvore_AVL, al�m de duas fun��es externas.

A classe no_AVL apresenta como m�todos:

- buscar: respons�vel pela localiza��o de um determinado n� na �rvore.
- inserir: Respons�vel pela inser��o de um filho em determinado n�.
- remover: realiza a remo��o do n� indicado.
- buscar_maior: Busca o maior membro da �rvore a partir de determinado n�.
- antecessor: Busca o elemento antecessor ao n� indicado.

A classe Arvore_AVL apresenta como m�todos:
- buscar: fazendo uso da busca anterior, devolve o n� com a chave indicada.
- inserir: respons�vel pela cria��o do n� e inser��o deste na �rvore.
- remover: respons�vel pela remo��o de um n� da �rvore.
- rota��o_direita: respons�vel por realizar a rota��o direita na �rvore
- rota��o_esquerda: respons�vel por realizar a rota��o esquerda na �rvore
- balanceamento: fazendo uso das duas fun��es �ltimas fun��es citadas, realiza o balanceamento da �rvore.

�rvore de Pr�fixos:

A �rvore de Prefixos, ou �rvore trie, � uma estrutura de dados do tipo �rvore ordenada, que pode ser usada para armazenar um array associativo em que as chaves s�o, normalmente, cadeias de caracteres.


No seu c�digo, a �rvore foi implementado contendo as seguintes fun��es:
- add_palavra: respons�vel por adicionar uma �nica palavra a �rvore.
- add_palavras: respons�vel por adicionar uma lista de palavras a �rvore
- busca: realiza a busca de determinada palavra na �rvore, importante notar que s� ser� identificada a palavra que estiver por completo na arvore.
	remove_palavra: respons�vel por remover uma palavra completa da arvore.   