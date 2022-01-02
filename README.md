# Boas vindas ao repositório do projeto Docker Todo List!

## Descrição do projeto

Neste projeto, eu fui capaz de:

- Usar comandos dockers no CLI - Interface de linha de comando;
- Criar um contêiner Docker para uma aplicação de front-end;
- Criar um contêiner Docker para uma aplicação de back-end;
- Criar um contêiner Docker para uma aplicação de testes;
- Orquestrar os três contêineres utilizando o Docker compose.

---

## Instalação do projeto localmente

Após cada um dos passos, haverá um exemplo do comando a ser digitado para fazer o que está sendo pedido, caso tenha dificuldades, mande mensagem para o meu e-mail _humberto_bonadiman@hotmail.com_.

1. Abra o terminal e crie um diretório no local de sua preferência com o comando **mkdir**:
```javascript
  mkdir projetos-humberto
```

2. Entre no diretório que acabou de criar e depois clone o projeto:
```javascript
  cd projetos-humberto
  git git@github.com:Humberto-Bonadiman/Project-docker-todo-list.git
```

3. Acesse o diretório do projeto e depois utilize o comando **npm i** (opcional) para instalar todas as dependências necessárias:
```javascript
  cd Project-docker-todo-list
  npm i
```

4. Para visualizar os comandos docker utilizados você deve entrar no diretório docker e após no diretório docker-commands onde você irá encontrar os arquivos command01.dc - command12.dc.

5. Para visualizar os arquivos Dockerfile entre no diretório docker, após isso no diretório todo-app, e dentro de cada um dos diretórios back-end, front-end e tests você encontrará os arquivos.

6. E por último para encontrar o arquivo docker-compose.yml você só precisa abrir o diretório docker.

---

## Requisitos do projeto

## Comandos docker

#### 1. Crie um novo container de modo interativo sem roda-lo nomeando-o como `01container` e utilizando a imagem `alpine` usando a versão `3.12`

  - **Observações técnicas:** 
    - O container **não deve ser inicializado**, somente criado;
    - O container deve estar preparado para acesso interativo;

#### 2. Inicie o container `01container`

#### 3. Liste os containers filtrando pelo nome `01container`

#### 4. Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele

  - **Observações técnicas:**
    - O container deve estar rodando, e você deve ser capaz de **executar um comando** nesse container.
  
  - **Dica:** 
    -  É possível fazer isso sem usar o comando `attach`.

#### 5. Remova o container `01container` que está em andamento.

#### 6. Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container.

#### 7. Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro.

#### 8. Pare o container `02images` que está em andamento.

## Dockerfile

#### 9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`.

#### 10. Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`.

#### 11.Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`.
  
  **Observação**: A aplicação `todotests` só funciona corretamente se estiver dockerizada e dentro de uma rede docker configurada corretamente.

## Bônus

### Docker-compose

#### 12. Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar.

---
