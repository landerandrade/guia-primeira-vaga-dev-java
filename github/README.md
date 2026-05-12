# GitHub para Dev Júnior: seu portfólio real

Recrutador técnico abre o GitHub antes de chamar para entrevista. O que ele vai encontrar no seu?

---

## O que um GitHub forte comunica

- Você realmente sabe codar (não só seguir tutorial)
- Você tem consistência (commits regulares, não surto de uma semana)
- Você sabe trabalhar como profissional (README, branches, commits claros)

Um GitHub fraco — vazio, cheio de forks sem contribuição, projetos sem README — comunica o oposto.

---

## Perfil: o que configurar

**Foto:** foto real, não avatar gerado. Transmite confiança.

**Bio:** 1–2 linhas. Stack + o que você está construindo.
> "Desenvolvedor Java · Spring Boot · Construindo APIs do zero ao deploy"

**Localização:** cidade/estado. Recrutador filtra por região.

**Link:** coloque seu LinkedIn.

**README de perfil:** crie um repo com o mesmo nome do seu usuário (`github.com/seu-usuario/seu-usuario`) e adicione um `README.md`. Aparece na sua página inicial. Exemplo de conteúdo:

```markdown
## Olá, sou [Seu Nome]

Desenvolvedor Java focado em Spring Boot e APIs REST.
Estou construindo [nome do projeto] — [o que faz em uma linha].

Stack: Java · Spring Boot · PostgreSQL · Docker · Git

📌 Projeto em destaque: [link]
📬 LinkedIn: [link]
```

---

## Projetos: o que importa

**Quantidade não é qualidade.** Dois projetos bem feitos valem mais que dez abandonados.

### O que um projeto precisa ter

**README.md obrigatório com:**
- O que é o projeto (1 parágrafo)
- Como rodar localmente (passo a passo)
- Stack usada
- Endpoints principais (se for API)

**Commits com mensagem clara:**
```
feat: adicionar endpoint de criação de tarefa
fix: corrigir validação de data no TaskService
refactor: extrair lógica de autenticação para AuthHelper
```

Não: `update`, `fix bug`, `wip`, `aaa`, `teste`.

**Branches:** pelo menos uma `main` limpa. Idealmente usar `feature/nome` para desenvolvimento.

---

## Que tipo de projeto convence

Em ordem decrescente de impacto:

1. **API REST completa com autenticação** — CRUD + JWT + banco relacional + Docker
2. **Projeto com regra de negócio real** — não só "cadastro de usuário", mas algo que resolve um problema
3. **Projeto com testes** — pelo menos testes de unidade no service layer
4. **Contribuição em open source** — mesmo que correção de documentação

O que não convence: clone de tutorial sem modificação, projeto "Hello World", projeto sem README.

---

## Consistência de commits

Recrutador técnico olha o gráfico de atividade (os quadradinhos verdes).

Não precisa commitar todo dia. Mas commits regulares ao longo de semanas mostram que você é consistente — não que você deu um surto de uma semana e sumiu.

**Meta realista:** 3–4 commits por semana em um projeto ativo.

---

## Pinned repositories

Você pode fixar até 6 repos na sua página. Fixe apenas os melhores.

Para configurar: perfil → "Customize your pins" → selecione os repos.

---

## Checklist do GitHub antes de mandar currículo

- [ ] Foto de perfil real
- [ ] Bio com stack
- [ ] README de perfil criado
- [ ] Pelo menos um projeto com README completo
- [ ] Commits com mensagens descritivas
- [ ] Repos ruins despinados ou arquivados
- [ ] Repos de tutorial marcados como `fork` ou arquivados

---

*Próximo passo: [Configure seu LinkedIn](../linkedin/) para que o recrutador te ache.*
