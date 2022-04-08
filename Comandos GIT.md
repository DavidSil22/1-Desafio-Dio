# Comandos CMD

DIR: – Listando arquivos e pastas
COPY: – Copiar arquivos
Para copiar um arquivo chamado Aula.doc da unidade atual e do diretório
para um diretório existente chamado classe que está localizado na unidade C,
digite: copy Aula.doc c:\classe
MOVE: Mover arquivos ou renomear pastas
Para mover todos os arquivos com a extensão. xls do diretório \data para o
diretório \ Teste \ Anuncio , digite: move \data\*.xls \teste\anuncio\
MD ou MKDIR:– Criar uma Nova pasta
Para criar uma pasta chamada exemplo, digite: mkdir exemplo
CD: Entrar em uma pasta
Para retornar a pasta anterior, digite: cd..
RD: Remover pastas
Para remover a pasta exemplo, digite: RD exemplo
ERASE: Deletar arquivos
DEL: Deletar arquivos
REN: Renomear arquivos (EX: ren exemplo arrozarboreo)
TIME: O comando time permite acertar a hora e o comando date permite
corrigir a data
BOOTCFG: Permite ver as configurações do seu menu de boot
DEFRAG: Desfragmentador de disco.
DISKPART: Gerencia as partições de um disco.
DRIVERQUERY: Mostra a lista de drivers instalados no Windows e as
respectivas propriedades.
FSUTIL: O comando fsutil tem vários complementos que serão listados
digitando-o sem nenhum parâmetro. Digite fsutil fsingo drives e terá a
lista dos drives no seu micro.
GEPRESULT: Este comando mostrará configurações de usuários e de
diretivas de grupos.
RECOVER: Permite a recuperação de arquivos em disco danificado.
REG: Comando para exportar chaves do registro, copiar, restaurar,
comparar, etc.
SCHTASKS: Para agendar, executar, alterar ou deletar tarefas numa
máquina local ou remota com Windows.
SFC: Comando que permite verificar arquivos de sistemas alterados de
forma indevida e recuperar os arquivos originais e oficiais da Microsoft, o
que nem sempre será recomendável. Por exemplo, o arquivo uxtheme.dll
modificado para permitir o uso de temas voltaria a ser substituído pelo
original.
SHUTDOWN: O comando shutdown permite desligar ou reiniciar o
computador de forma imediata ou agendada.

Link de Referencia: https://www.ufsm.br/app/uploads/sites/762/2021/05/Principais-comandos-do-prompt-do-Windows-CMD.pdf

# Comandos Git 

Git add
Este comando adiciona os arquivos solicitados ao ambiente de stage, é uma forma de dizer para o git que você deseja que as modificações daquele arquivo sejam gravadas na próxima remessa. Um exemplo de utilização é: git add . onde o ponto representa todos os arquivos na pasta.

Git commit
Agora fazemos a gravação em si das modificações, desta forma criamos um snapshot do estado atual do nosso projeto. Uma forma muito usada é o git commit -m “descrição das atualizações do projeto” onde o -m é uma flag que aponta para a mensagem de descrição.

Git push
Por fim precisamos subir essas modificações no nosso repositório remoto, para isso basta utilizar o comando git push e, se já estiver tudo devidamente configurado, os arquivos serão salvos no repositório remoto correspondente ao seu repositório local!
