# VirtualEnv

## Definição

Basicamente, um ambiente virtual empacota todas as dependências que um projeto precisa e armazena em um diretório, fazendo com que nenhum pacote seja instalado diretamente no sistema operacional. Sendo assim, cada projeto pode possuir seu próprio ambiente e, consequentemente, suas bibliotecas em versões específicas.

## Funcionamento

O funcionamento de uma virtualenv é bem simples. Basicamente, uma cópia dos diretórios necessários para que um programa Python seja executado é criada, incluindo:

- PIP (Gerenciador de pacotes);
- A versão do Python utilizada (2.x ou 3.x);
- Dependências instaladas com o pip (armazenadas no diretório site-packages);
- Seu código fonte;
- Bibliotecas comuns do Python.

## Instalação

```powershell
pip install virtualenv
```

## Nova virtualenv

````powershell
virtualenv nome_da_virtualenv
````

## Ativação

### Linux ou macOS

```powershell
source nome_da_virtualenv/bin/activate
```

### Windows

```powershell
nome_da_virtualenv/Scripts/Activate
```

## Desativar

```powershell
deactivate
```

## Instalando pacotes

É feito com a virtualenv ativada e usando o pip.

````powershell
pip install nome_do_pacote
````
