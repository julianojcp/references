# VIM

<pre>
:Se	- file explorer
:e C+d	- explorer bash like

ciw 	- change inner word (substituir palavra)
cat	- change aroung tag (substitui toda a tag)

* 	- busca proxima palavra under cursos
%	- alterna entre a tag abaixo do cursor

gt gT	- alterna tabs
gd	- go to definition
gh	- go to hint/dica
gi	- volta pro ultimo insert

vtx 	- seleciona até o caractere x
vat	- seleciona toda uma area entre tags (usando o "o" alterna entre incio e fim)

"ay	- copia pro register a
"ap	- cola o conteudo do register a
:reg	- exibe tudo o que foi copiado

"+y	- copia pro clipboard do sistema
"+p	- cola do clipboard do sistema

ma	- marca posição na letra a
'a	- pula para a posição da marca a

zz	- cursor line to center of screen

ctrl+f	- page down (page front)
ctrl+b	- page up (page back)

ctrl+v  - entra no Visual Mode Vertical
shift+i - insere no modo vertical

web	- word navigation
ft	- character searching
}])	- object navigation

ctrl+a  - increment number under cursor
ctrl+x	- decrement number under cursor

:set hlsearch			- destaca busca
:hi! link Comment Ignore	- Oculta comentarios iniciando com #

:g/info/d	- deleta todas as linhas que encontra info (sem o /d para exibir as listas selecionadas)
:g/^$/d		- deleta todas as linhas em branco
:g!/^\s*"/d	- deleta as linhas que não possuem o padrão (uso do ! para inverter a pesquisa)
:v/error\|warn\|fail/d	- deleta tudo que não tenha as 3 palavras
  
</pre>

https://gist.github.com/tuxfight3r/0dca25825d9f2608714b
