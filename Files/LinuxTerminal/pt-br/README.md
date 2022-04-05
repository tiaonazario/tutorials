# Comandos Básicos do Terminal Linux

## Dicas e Atalhos

- [ ] Tab ⇾ Completa a digitação;
- [ ] Setas di teclado para navegar no terminal;
- [ ] CTRL + A ⇾ Leva o cursor para o inicio do comando;
- [ ] CTRL + U ⇾ Limpa o comando digitado;
- [ ] CTRL + L ⇾ Limpa o terminal.

## Comandos

- `pwd` ⇾ Exibe o diretório atual;
- `mkdir` ⇾ Criar um novo diretório;
- `touch` ⇾ Cria um ou mais arquivos;

```bash
touch arquivo.txt # um arquivo
touch {arquivo1, arquivo2, arquivo3, ...}.txt # mais de um arquivo
```

- `nano` ⇾ Editor simples de arquivo;
- `cat` ⇾ Exibe o conteúdo do arquivo;
- `ls` ⇾ Lista o conteúdo do diretório;
- `ls -l` ⇾ Mais informações;
- `ls -a` ⇾ Mostra tudo, iclusive arquivos e diretorios ocultos;
- `ls -la` ⇾ Combinação de -a e -l;
- `cd` ⇾ Navega entre diretorios;
- `cp` ⇾ Copia arquivos ou diretorios;

```bash
cp arquivo.txt ./pasta/arquivo.txt # Para copiar um arquivo
cp -r pasta ./outra # Para copiar um diretorio
```

- `mv` ⇾ Move / Renomeia arquivos ou diretorios;

```bash
mv arquivo.txt ./pasta/arquivo.txt # Para mover um arquivo
mv arquivo.txt ./pasta/arquivos.txt # Para mover um arquivo e renomear
```

- `file` ⇾ Informações do arquivo;
- `stat` ⇾ Tamanho, ultimo acesso e modificações (data/hora);
- `rm` ⇾ Excluir arquivos;
- `rm -r` ⇾ Ecluir diretorios;
- `sudo` ⇾ Permissão de administrador;
- `apt install` ⇾ Instala programas que existem no repositório do debian/ubuntu;
- `apt update` ⇾ Baixa as atualizações e informações dos pacotes de todas as fontes (repositórios) configurados;
- `apt upgrade` ⇾ Instala as atualizações disponíveis dos pacotes contidos atualmente no sistema.
