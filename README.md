
# Aulas de Comandos Básicos no Terminal Linux
## Bem-vindo ao guia de Comandos Básicos no Terminal Linux. Este documento é um recurso rápido para aprender e revisar os fundamentos do uso do terminal no sistema operacional Linux.

# Navegação no Sistema de Arquivos
## pwd: Mostra o caminho do diretório atual.


## pwd

## cd nome_da_pasta
## cd /: Navega até o diretório raiz.

# ls: Lista o conteúdo do diretório.


## ls
## cd .. e cd ../../: Volta para o diretório anterior.

# Autocompletar Comandos: Digite o início do comando e pressione TAB para autocompletar.

# Limpeza e Visualização
## clear: Limpa a tela do terminal.
## clear
## Manipulação de Pastas e Arquivos
## mkdir: Cria uma nova pasta.

## mkdir nome_da_pasta
## echo: Escreve na tela ou redireciona para um arquivo.


## echo mensagem > nome_do_arquivo.tipo
## cat e more: Mostra o conteúdo de um arquivo.

## cat nome_do_arquivo.tipo
## more nome_do_arquivo.tipo
## gedit: Abre o editor de texto.
## gedit nome_do_arquivo.tipo

# Manipulação de Arquivos e Diretórios
## cp: Copia arquivos para outro local.


## cp nome_do_arquivo nova_pasta/
## mv: Renomeia ou move arquivos.


## mv nome_do_arquivo novo_nome_arquivo.tipo
## mv nome_do_arquivo nova_pasta/
## rm e rm -rf: Apaga arquivos ou diretórios recursivamente.
## rm nome_do_arquivo
## rm -rf nome_da_pasta

# Permissões de Arquivos e Diretórios
# chmod e chown: Altera permissões e donos de arquivos.
## chmod 777 nome_do_arquivo.tipo
## sudo chown root:root nome_do_arquivo.tipo
## sudo chown usuario_dono:grupo_dono nome_do_arquivo.tipo
## Listagem Detalhada
## ls -l: Lista com detalhes.


## ls -l
## ls -lh: Lista com detalhes e unidades de medida.
### ls -lh

# Exemplos de Permissões
## r-x: Sem permissão de escrita.
## r--: Somente leitura.

# Alterar Permissão do Arquivo:


## chmod 755 nome_do_arquivo.tipo
## Lembre-se, o ROOT é o administrador do sistema e comandos podem necessitar de sudo para execução.

