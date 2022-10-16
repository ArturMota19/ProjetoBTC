# ProjetoBTC #

## Padrão de commit

> **ATENÇÃO:** mensagens de commit que não estejam de acordo com os critérios abaixo irão impedir a criação do commit.

Os commits devem ser semânticos e seguir o seguinte padrão:

```
feat: add currency verification for credit card transactions
^--^   ^------------^ -> Mensagem no imperativo
 *-> Tipos: chore, docs, feat, fix, merge, perf, refact, style, test, or wip.
```

Os tipos disponíveis são:

- `chore`: se refere à alguma implementação que não impacta diretamente o usuário.
- `docs`: se refere à alterações na documentação.
- `feat`: se refere à implementação de features.
- `fix`: se refere à uma correção.
- `refact`: se refere à refatoração de uma feature previamente implementada.
- `style`: se refere à uma mudança estética no código. Por exemplo: alterar a indentação de espaço para tab.
- `test`: se refere à uma implementação de teste.
##


# 1 INSTRUÇÕES DE INSTALAÇÃO:
- node -v
- git clone https://github.com/ArturMota19/ProjetoBTC
- abra o terminal do seu editor de código no diretório do projeto
- npm i
- npm i react-css-modules

# 2 INICIAR O PROJETO:
- npm run dev

# 3 ORGANIZAÇÃO DE BRANCHS
- Para cada implementação, crie uma branch nova com o padrão dos tipos disponíveis, se será realizada no back ou no frontend e o nome do que será implementado;
  Exemplo: [feat/backend/implement-models], [feat/frontend/login-screen];
- Para criar uma branch, use: git checkout -b x-nome-da-branch;
- Após criar a branch pra sua implementação, faça o que quiser nela, pois ainda não está na branch main, logo, não
  oferece risco à branch de produção;
- Depois de terminar a branch que você estava fazendo, dê git push, solicite o merge da sua branch e marque os outros devs do projeto como revisores do código, uma vez aprovado por TODOS, poderá subir a sua branch pra main;
- *NÃO CODAR NA PASTA MAIN!*

# 4 MANTENDO SUA BRANCH ATUALIZADA
- Sempre que houver uma nova atualização, use "git pull origin main";
- Isso serve para que nossas branchs não tenham conflito, uma vez que pode ocorrer de alguém atualizar o código e
  você ainda não ter essa atualização na sua máquina, e vice-versa.
