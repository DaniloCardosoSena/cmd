### Comandos Linux

sudo = Permissões especiais.
sudo su = Obter privilégios de super usuário.
cd "nome da pasta"= Navegar pelo sistema de arquivos.

ls = Listagem de arquivos.
ls -al = Listagem de todos os arquivos e diretórios com informações detalhadas como permissões, tamanho, proprietário, etc.
dir = Listagem de arquivos.
mkdir "nome da pasta" = Cria pasta no diretorio atual.
clear = Limpar terminal.
cls = Limpar terminal.

cat "nome do arquivo" = Permite que você exiba arquivos no formato padrão de tela, lista conteúdos do arquivo.
cat > /pasta/origem/arquivo.txt = Permite escrita dentro do arquivo.txt, Ctrl+D para finalizar e salvar.
more "nome do arquivo" = ler arquivos de texto.

cp /pasta/origem/arquivo1 /pasta/destino/ = Copia o arquivo1 e cola na pasta de destino mantendo o mesmo nome.
cp /pasta/origem/arquivo1 /pasta/destino/arquivo2 = Copia renomeando o arquivo1 para arquivo2.
sudo cp -R /pasta/origem/arquivo1 /pasta/destino/

chmod 777 -R "nome do arquivo/pasta" = O comando chmod serve para alterar as permissões sobre determinado diretório ou arquivo(libera acesso para transferencia/cópia externa). Permissão 777 significa acesso total. Se um diretório tem permissão 777, qualquer usuário pode mexer naquele diretório,a todos os diretórios e arquivos a partir do raíz.

ping / telnet = Testar comunicação. Comando baseado em protocolo, tem como princípios uma série de procedimentos e regras que são definidos para padronizar a comunicação.

grep = Procura por trechos de texto (strings) dentro de arquivos ou diretórios [ grep "trecho a procurar" arquivo.txt ].
	telnet | grep 8000
	ls | grep "trecho a procurar"



### Comandos Git
