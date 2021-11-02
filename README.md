# Evently

Evently é uma aplicação web desenvolvida com Vue.js 3 como projeto do bloco de Desenvolvimento Front End.

Evently permite que usuários criem e participem de eventos de qualquer natureza. Crie um evento para o clube de leitura ou um evento esportivo no seu bairro.

---

## Instalação

Após a refatoração o projeto foi dividido para melhor organização do histórico git. O projeto possui dois sub-módulos, cada qual com seu próprio histórico e devem ser atualizados independentemente. Este repositório é apenas uma consolidação do projeto.

**Após clonar o projeto, atualize os sub-módulos**

```sh
git submodule update --remote
```

Rode o comando acima toda vez que quiser atualizar os sub-módulos. É o equivalente ao `git pull`. Note que apenas executar o `pull` no diretório pai não atualizará os sub-módulos. Da mesma forma, o comando `push` não subirá nenhum commit dos sub-módulos. Estes comandos devem ser executados em cada diretório separadamente.

**Para trabalho de desenvolvimento é melhor clonar os sub-módulos separadamente.**

- [evently-api](https://github.com/21E321E4-DFE-GRP-EDC-01C1-T1-P1/evently-api): contém o código da API.
- [evently-vue](https://github.com/21E321E4-DFE-GRP-EDC-01C1-T1-P1/evently-vue): contém o código da aplicação Vue.
