# Guia Básico de Git

Bem-vindo ao **Guia Básico de Git**! Este repositório contém um conjunto de instruções simples e diretas para iniciantes aprenderem a usar o Git, uma das ferramentas mais importantes no mundo do desenvolvimento de software.

## Descrição

Este guia visa fornecer uma introdução prática aos comandos essenciais do Git, para que você consiga configurar, utilizar e gerenciar seus projetos com controle de versão de forma eficaz.

Se você é iniciante e está começando sua jornada no Git, este repositório é um excelente ponto de partida. Através deste guia, você aprenderá desde a configuração inicial do Git até as operações mais avançadas, como criação de branches e mesclagem de alterações.

## Funcionalidades Principais

Aqui estão os principais tópicos abordados no guia:

- **Configuração de usuário no Git**: Como configurar seu nome e e-mail no Git para associar aos commits.

- **Inicialização e clonagem de repositórios**: Como criar um repositório Git local ou clonar um repositório remoto.

- **Adição e confirmação de alterações**: Como adicionar alterações ao staging area e fazer commits.

- **Observação do estado do repositório**: Como verificar as mudanças no seu repositório.

- **Envio de alterações para repositórios remotos**: Como enviar seus commits para um repositório remoto.

- **Criação, modificação e exclusão de branches**: Como criar novas branches, alternar entre elas e excluí-las.

- **Mesclagem de branches**: Como mesclar mudanças de uma branch para outra.

- **Atualização do repositório local**: Como trazer as últimas alterações do repositório remoto para o seu repositório local.

## Como Utilizar

Para começar a usar o **Guia Básico de Git**, basta seguir as seções e exemplos de comandos listados abaixo. Cada seção é acompanhada de explicações e exemplos para que você possa entender e aplicar cada comando com facilidade.

### Exemplo básico de configuração do Git:

1. **Configure seu nome e e-mail**:
```bash
git config --global user.name "Seu Nome"
git config --global user.email seu.email@email.com
```
2. **Verifique as configurações feitas**:
```bash
git config --list
```
### Como Usar os Comandos:

1.**Criando um repositório local**:
```bash
git init
```
2.**Clonando um repositório remoto**:
```bash
git clone <URL>
```
3.**Adicionando arquivos para o staging**:
```bash
git add .
```
4.**Confirmando alterações (commit)**:
```bash
git commit -m "Sua mensagem de commit"
```
### Estrutura do Repositório

A estrutura deste repositório é organizada da seguinte maneira:

  index.html: Página principal do guia, onde você pode encontrar todos os comandos Git organizados por tópicos.

  style.css: Arquivo de estilo que define o layout e aparência do guia.

  reset.css: Arquivo que faz o reset de estilos para garantir a consistência entre navegadores.

  README.md: Este arquivo, que contém uma descrição detalhada do projeto.

### Contribuição

Contribuições são sempre bem-vindas! Se você encontrar erros, quiser sugerir melhorias ou adicionar mais comandos ao guia, fique à vontade para abrir uma issue ou enviar um pull request.

**Passos para Contribuir**

1. Faça o fork do repositório.

2. **Crie uma branch para a sua feature**:
```bash
  git checkout -b minha-nova-feature
```
3. **Faça as alterações necessárias e commit**:
```bash
  git commit -am 'Adiciona nova feature'
```
4. **Envie para a branch principal do repositório**:
```bash
  git push origin minha-nova-feature
```
5. **Abra um pull request!**

### Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para obter mais informações.