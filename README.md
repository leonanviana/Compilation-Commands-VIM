# Compilation-Commands-VIM

TEM COMO OBJETIVO MOSTRAR UM COMPILADO COMPLETO DE COMANDOS E MODOS DO VI VIM PARA O DIA-A-DIA!!!


**MODO DE INSERÇÃO:**
o = entra no modo inserção na linha abaixo.\
O = entra no modo inserção na linha acima.\
i = inserir na posição do cursor.\
I = inserir no inicio da linha atual.\
a = entra no modo inserção e um caracter a frente aonde o cursor está posicionado.\
A = entra no modo inserção e independente da posição do cursor ele pula para o final da linha.\


**SALVANDO E SAINDO:**
:w = salvar edição.\
:q = sair do VI VIM.\
:qa = sair de todos os arquivos abertos.\
:q! = sair forçando do VI VIM.\
:wq = salvar e sair do VI VIM.\
:x = salvar e sair do VI VIM, mesma coisa que o :wq.\
ZZ = sair e salvar do Vi VIM, mesma coisa que o :wq e :x.\
ZQ = sair e não salvar do VI VIM.\
ESC = retorna ao modo comando, ou seja, saí da inserção.\


**COPIANDO, COLANDO E RECORTANDO:**
yy = copia a linha inteira.\
p = cola na linha abaixo.\
P = cola na linha acima.\
y8y = copiar 8 linha, o número é de acordo com a quantidade de linha a serem copiadas.\
dd = apaga e ou recorta a linha inteira.\
d8d = apaga e ou recorta 8 linhas inteiras, o número é de acordo com a quantidade de linhas desejadas.\
dw = apaga uma palavra.\
dG = apaga da posição do cursor até final do arquivo.\
dgg = apaga da posição do cursor até o inicio do arquivo.\
cw = recorta uma palavra.\
yw = copia a palaavra.\
x = apaga um caracter (igual ao Delete).\
X = apaga um caracter antes do cursos (igual ao backspace).\
r = faz um replace (substitui o caracter atual pelo novo que quisermos).\


**VISUAL:**
v = modo visual (seleciona um pedaço do texto).\
CTRL+v = visual block (seleciona um bloco na linha reta).\
V = visual line (seleciona linhas do texto).\


**VOLTANDO E REFAZENDO:**
u = voltar (igual ao CTRL+z do windows).\
CTRL+r = refazendo (igual ao CTRL+SHIFT+z do windows).\


**BUSCAS NO ARQUIVO E LOCALICAÇÃO:**
/<Informe a palavra para busca> = irá buscar a palavra no arquivo descendo.\
?<Informe a palavra para busca> = irá buscar a palavra subindo o arquivo.\
n = continua com a busca descendo.\
N = continua com a busca subindo.\
gg = vai para a primeira linha do arquivo.\
G = vai para a última linha do arquivo.\
M = vai para o meio da tela.\
H = vai para o topo da tela.\
L = vai para o final da tela.\

  
**COMANDOS set:**
:set nlsearch = habilita o highlight para as buscas.\
:set number = numera as linhas.\
:set tabstop = tamanho do TAB.\
:set expandtab = converte o TAB em espaços.\
:set bg=dark ou light = muda o esquema de cor.\
:e = abre outro arquivo.\
:r = copia o conteúdo do arquivo X para o arquivo Y.\
:split <Nome Arquivo> = divide a tela na horizontal com outro arquivo desejado.\
:vsplit <Nome Arquivo> = divide a tela na vertical com outro arquivo desejado.\
:! <Nome comando> = executa o comando no shell e retorno para o VI VIM.\
!! <Nome comando> = executa copia/cola a saída do comando p/ dentro do arquivo.\

 
**SUBSTITUINDO:**
:<Numero linha>s/palavra_antiga/palavra_nova = substitui na linha que informamos a palavra antiga pela nova.\
:%s/palavra_antiga/palavra_nova = substitui a palavra antiga pela nova uma por linha apenas.\
:%s/palavra_antiga/palavra_nova/g = substitui a palavra antiga pela nova em todo o arquivo.\
