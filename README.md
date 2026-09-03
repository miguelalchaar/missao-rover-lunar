# Missão Rover Lunar

![Python](https://img.shields.io/badge/Python-3.6%2B-blue?style=for-the-badge\&logo=python\&logoColor=white)
![Git](https://img.shields.io/badge/Git-Versionamento-orange?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repositório-black?style=for-the-badge\&logo=github\&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

Projeto desenvolvido para a disciplina de **Gestão e Qualidade de Software**, com o objetivo de praticar conceitos fundamentais de **versionamento de código utilizando Git e GitHub**.

A atividade simula o desenvolvimento de um sistema para uma missão espacial, no qual foi criado um programa simples responsável por realizar a **inicialização dos sistemas de um Rover Lunar**.

Além da implementação do algoritmo, a atividade teve como principal objetivo proporcionar a prática de um fluxo básico de desenvolvimento colaborativo, envolvendo **branches, commits, push, Pull Requests, Code Review e merge**.

## ▸ Conceito da atividade

A atividade consiste na criação de um repositório chamado `missao-rover-lunar` e no desenvolvimento de um pequeno algoritmo para inicialização de um Rover.

O projeto foi desenvolvido seguindo um fluxo de branches definido na atividade:

```text
main
  ↑
develop
```

A branch `develop` foi utilizada como ambiente para desenvolvimento e alterações do código. Após a implementação e validação das mudanças, foi criado um **Pull Request** tendo a `main` como branch de destino.

Esse processo simula um fluxo básico utilizado em projetos reais de desenvolvimento de software, no qual as alterações são desenvolvidas separadamente antes de serem incorporadas à versão principal do sistema.

## ▸ O que o código faz?

O programa possui uma função responsável por inicializar os sistemas do Rover Lunar.

Durante a inicialização, são exibidas mensagens informando o estado dos principais sistemas:

* Inicialização dos sistemas do Rover;
* Verificação dos painéis solares;
* Verificação do nível da bateria.

Exemplo de saída:

```text
Sistemas do Rover iniciados!
Painéis solares: OK
Nível de bateria: 100%
```

## ▸ Versionamento de código

Um dos principais objetivos da atividade foi compreender, na prática, como funciona o **versionamento de código**.

O versionamento permite registrar e acompanhar as alterações realizadas em um projeto ao longo do tempo. Dessa forma, é possível saber o que foi alterado, quando a alteração aconteceu e qual versão do código contém determinada modificação.

Durante a atividade, foram praticados conceitos importantes do Git e GitHub:

| Conceito         | Aplicação na atividade                                           |
| ---------------- | ---------------------------------------------------------------- |
| **Repositório**  | Armazenamento do código e dos arquivos do projeto no GitHub      |
| **Branch**       | Criação da branch `develop` para desenvolvimento                 |
| **Commit**       | Registro das alterações realizadas no código                     |
| **Push**         | Envio das alterações para o GitHub                               |
| **Pull Request** | Solicitação para incorporar as alterações da `develop` na `main` |
| **Code Review**  | Simulação da revisão e aprovação das alterações                  |
| **Merge**        | Integração da `develop` com a `main`                             |

## ▸ Aprendizados

A atividade possibilita compreender que o Git não é apenas uma ferramenta para armazenar código, mas também um recurso fundamental para **organizar o processo de desenvolvimento de software**.

Entre os principais aprendizados estão:

* Entendimento do conceito de **versionamento de código**;
* Criação e utilização de diferentes **branches**;
* Importância de manter a `main` organizada e estável;
* Utilização de **commits claros e padronizados**;
* Envio de alterações para um repositório remoto utilizando `push`;
* Utilização de **Pull Requests** para propor alterações;
* Compreensão do processo de **Code Review**;
* Integração das alterações utilizando **merge**;
* Organização do histórico de desenvolvimento;
* Compreensão de um fluxo básico utilizado em equipes de desenvolvimento.

A atividade também demonstrou a importância de separar o desenvolvimento da versão principal do projeto, permitindo que alterações sejam avaliadas antes de serem integradas à `main`.

## ▸ Como executar

**Pré-requisito:** ter o Python instalado na máquina.

1. Clone este repositório:

```bash
git clone https://github.com/SEU-USUARIO/missao-rover-lunar.git
```

2. Entre na pasta do projeto:

```bash
cd missao-rover-lunar
```

3. Execute o programa:

```bash
python Rover.py
```

## ▸ Checklist da atividade

* [x] Criar o repositório `missao-rover-lunar`
* [x] Adicionar o arquivo `README.md`
* [x] Clonar o repositório para a máquina local
* [x] Criar a branch `develop`
* [x] Desenvolver o código de inicialização do Rover
* [x] Atualizar o README com a descrição do projeto
* [x] Adicionar os arquivos ao staging
* [x] Realizar o commit das alterações
* [x] Enviar a branch `develop` para o GitHub
* [x] Criar o Pull Request da `develop` para a `main`
* [x] Realizar a simulação de Code Review
* [x] Aprovar o Pull Request
* [x] Realizar o merge para a `main`
* [x] Confirmar as alterações na branch principal
