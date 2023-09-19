# linux-projeto1-iac
Repositório para os arquivos de script do primeiro projeto do curso de Linux

Nesse projeto foi criado um script que toda a infraestrutura de usuários, grupos de usuários, diretórios e permissões foram criadas automaticamente. ]

Requisitos do projeto: 

diretorios
/publico 
/adm
/ven
/sec

grupos 
GRP_ADM
GRP_VEN
GRP_SEC

usuarios 
adm
carlos
maria
joao

ven
debora
sebastiana
roberto

sec
josefina
amanda
rogerio


REGRAS
todo provisionamento deve ser feito arquivo tipo bash
dono de todos diretorios será o root
todas as permissoes no publico 
o usuario de cada grupo terao permissao total dentro de seu respectivo diretorio 
usuario nao poderao ter permissao de leitura escrita e execução em diretorios que não pertencem 
