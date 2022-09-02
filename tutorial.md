# **Como contribuir com o projeto**

## **Passo 1: Crie uma cópia do projeto no seu computador**
Primeiramente é necessário que se crie um fork local do projeto, para isso, aperte no botão "fork" no Github.

Agora faça uma cópia local. Procure por “HTTPS clone URL” ou “SSH clone URL” na coluna direita e copie o endereço para fazer uma cópia local usando o terminal:

```
$ git clone [COLE O LINK COPIADO AQUI]
```
---

Entre no diretório do projeto:

```
$ cd [NOME PROJETO]
```
---

Nesta etapa você precisará configurar um novo remoto que apontará para o projeto original, assim, é possível trazer as mudanças no do mesmo na sua cópia local. Acesse o link do repositório original - está marcado como "forked from" no topo da página do Github. Este link levará à página original do projeto no Github. Busque por "SSH Clone URL", copie e use este link para criar um novo remoto que chamaremos de "cardapio-upstream".

```
$ git remote add cardapio-upstream [LINK COPIADO]
```
Agora você tem dois remotos para esse projeto no disco:

- o origin, que aponta para seu fork do projeto no GitHub. Você tem acesso de leitura e gravação nesse remoto.
- o cardapio-upstream, que aponta para o repositório principal do projeto no GitHub. Você só tem acesso de leitura nesse remoto.
---

#Passo 2
Os Sêniors e Plenos ficarão responsáveis por criarem as issues indicando no label o cargo de quem deve se responsabilizar por aquela issue. Os Sêniors criaram issues que demandem mais conhecimentos, portanto marcadas com o label "plenos". O pleno que ficar responsável por essa issue pode e deve redistribuir a tarefa para júniors e estágiários.

**Ex:**
1. Um sênior cria uma issue com a tarefa de criar um banco de dados com várias tabelas e relacionamentos.
2. O pleno se auto-atribuíra a tarefa de criar o banco
3. O pleno pode demandar de um júnior que crie uma tabela específica e pode demandar do estagiário que crie uma ER para documentação.

---

Para demais instruções do fluxo de trabalho acesse [devmedia](https://dev.to/matheusgomes062/git-workflow-para-times-e-empresas-4dae). A principio o projeto terá a branch master/main e a branch develop.
