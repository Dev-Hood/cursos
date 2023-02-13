sudo apt-get update
sudo apt-get intall csh
csh

PATH = Lista de diretorios de programas executáveis
Username = Nome do usuario logado
Term = janela de terminal em uso
Home = diretório home do usuário atual
UID = usuário atual
Ramdom - Gera um número alatório
Lang = Idioma

comandos ´env´ e ´printenv´ mostram variaveis de ambientes no terminal

-criar variavel
    teste=valor
-exibir valor
    echo $teste
-deixar variável global
    export $teste
-remover variável
    unset teste

*não pode haver espaço

Criar função:
 palavra() {
> cd /home/tallys/
> echo 'linha acrescentada' >> teste
> }

typeset -f : mostra funçoes

> : insere resultado dentro de um arquivo e posteriormente sobrepõe
>> : insere resultado dentro de um arquivo e mas ao final não sobrepõe, adiciona ao final do arquivo

arq=`date +%d%m%y%H%M`
ls -la /home/tallys > log.$arq

