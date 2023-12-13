# Comandos de Navegação:

## pwd: Indica o local onde a pasta está localizada (CAMINHO).
## cd: Entra ou sai de uma pasta.
## cd /: Entra no diretório raiz.
## ls: Lista o conteúdo do diretório.
## cd ..: Volta para o diretório anterior.
## cd ../../: Volta dois diretórios anteriores.
# OBS: Ao digitar o início do comando + TAB, autocompleta o comando desejado.

# Comandos de Visualização e Limpeza:

## clear: Limpa a tela do terminal.
## Comandos de Manipulação de Arquivos e Pastas:

## mkdir nome_da_pasta: Cria uma pasta.
## echo mensagem > nome_arquivo.tipo: Escreve uma mensagem em um arquivo.
## cat nome_arquivo.tipo: Mostra o conteúdo de um arquivo.
## more nome_arquivo.tipo: Mostra o conteúdo de um arquivo (página por página).
## gedit nome_arquivo.tipo: Abre o editor com o conteúdo do arquivo.
## cp nome_arquivo pasta/novo_nome_arquivo local/.: Copia um arquivo para um novo local. (`. finaliza o comando)
## mv nome_arquivo novo_nome_arquivo: Renomeia um arquivo.
## mv nome_arquivo pasta/novo_nome_arquivo: Move um arquivo para outra pasta. (OBS: Copia e Cola)
## rm nome_arquivo: Apaga um arquivo.
## rm -rf nome_pasta: Apaga uma pasta e seu conteúdo.

# Comandos de Permissão e Propriedade:

## chmod 777 nome_arquivo.tipo: Concede permissões totais a um arquivo.
## sudo chown root:root nome_arquivo.tipo: Muda o dono do arquivo para root.
## sudo chown usuario_dono:usuario_dono nome_arquivo.tipo: Restaura o dono do arquivo.

# Comandos de Listagem Detalhada:

## ls -l: Lista detalhes do conteúdo da pasta.
## ls -lh: Lista detalhes com unidades de medida.

# Valores de Permissões:

## 4 = Leitura do arquivo.
## 2 = Escrita no arquivo.
## 1 = Executar o arquivo.

### Exemplo de permissão total: 7 (4+2+1) para Dono, Grupo e Usuário.
### Representação: rwx para Dono, Grupo e Usuário.

## Exemplos de Permissões:

## r-x: Não tem permissão de escrita no arquivo.
## r--: Somente leitura.

# Alterar Permissão do Arquivo:

## Comando: chmod 777 nome_arquivo.tipo arquivo (Acesso a permissão total).

# Mudar Dono do Arquivo:

## Lembrando que ROOT é o administrador dos arquivos e diretórios do sistema e deve iniciar com SUDO.
## sudo chown root:root nome_arquivo.tipo arquivo.

# Voltar o Dono do Arquivo:

## sudo chown usuario_dono:usuario_dono nome_arquivo.tipo arquivo.

# Apagar Arquivos e Diretórios:
## rm *: Apaga arquivos.
## rm -rf *: Apaga diretórios/pastas.

