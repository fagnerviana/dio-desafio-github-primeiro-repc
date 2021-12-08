# dio-desafio-github-primeiro-repc
Desafio de projeto sobre Git/GitHub 

# Links Úteis
[Guia básico de Markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)

## O que é o GIT
O Git é o sistema opensource de controle de versão mais popular da internet.

## Porque preciso dos comandos Git
É muito comum que empresas tenham mais de um dev trabalhando paralelamente no mesmo projeto. Então, em primeiro lugar, sistemas como o Git existem para o código não virar uma bagunça.

## Estados

* Modificado (modified);
* Preparado (staged/index)
* Consolidado (comitted);

## Operações principais:

Comandos | Descrição
-------- | --------
CLONE | Copia o repositório remoto para seu computador
PULL | Atualiza seu repositório local em relação ao repositório remoto
COMMIT | Salva uma nova versão (tipicamente no seu repositório local)
PUSH | Envia o repositório local para o repositório remoto

## Como utilizar o Git no meu computador?
* É preciso ter um sistema Git instalado em seu computador
     * Linux: já possui
     * o Mac: já possui / instalação semiautomática
     * o Windows: https://git-scm.com
  * O Git pode ser usado por ou por terminal de comando, ou por um aplicativo gráfico.

## Criar um novo projeto
* ATENÇÃO USUÁRIOS WINDOWS: configurar o sistema para mostrar extensões de arquivos
   Painel de controle -> Opções de pasta -> Modo de exibição
   *Desmarcar "Ocultar as extensões de tipos de arquivos conhecidos"
## Passos: 
1. Crie um novo projeto no seu ambiente de desenvolvimento
2. Crie um novo repositório no Github
  * ATENÇÃO: se seu ambiente de desenvolvimento não gera o arquivo .gitignore
automaticamente, escolha o seu tipo desejado de .gitignore na tela de criação de repositório do
Github
3. Abra um terminal na pasta do seu projeto
4. Certifique-se de estar identificado no Git do seu computador (nome e email)
  git config --list
  git config --global user.name "Fagner Viana"
  git config --global user.email "fagsantiago@gmail.com"
5. Faça os comandos a seguir:

Comandos | Descrição
-------- | --------
git init | Inicia um novo repositório local na pasta do seu projeto
git remote add origin "caminho do seu repositório do Github" | Associa seu repositório local ao repositório remoto, com o apelido de "origin"
git pull origin master | Atualiza seu repositório local em relação ao repositório remoto
git status | Verifica arquivos
git add . | Adiciona todos arquivos ao stage
git commit -m "Projeto criado" | Salva uma nova versão do projeto
git push -u origin master | Envia o repositório local para o repositório remoto
