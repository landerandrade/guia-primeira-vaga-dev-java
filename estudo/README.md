# Como Estudar Java sem Cair no Tutorial Hell

Tutorial hell é quando você assiste curso atrás de curso, entende enquanto o instrutor está codando, mas trava sozinho na hora de construir qualquer coisa do zero.

Você não está aprendendo. Está consumindo.

---

## Por que o tutorial hell acontece

O tutorial resolve o problema por você. Você vê a solução sendo construída, acha que entendeu — e entendeu. Mas entender diferente de conseguir fazer são coisas completamente diferentes.

É como assistir alguém nadar e achar que aprendeu a nadar.

---

## O ciclo que funciona

```
Aprenda o mínimo → Construa algo → Trave → Pesquise → Resolva → Repita
```

Não:
```
Assista todo o curso → Assista outro curso → Assista mais um → Tente construir algo → Trave → Volte ao curso
```

---

## Quanto estudar por dia

Para quem tem 30–60 minutos por dia:

**30 minutos de estudo ativo** valem mais que **2 horas de vídeo passivo**.

Estudo ativo = você está digitando código, quebrando a cabeça, pesquisando no Google, errando e corrigindo.

Estudo passivo = você está assistindo alguém fazer isso.

---

## Estrutura de aprendizado para Java + Spring Boot

### Fase 1 — Fundamentos Java (4–6 semanas)
Não pule essa fase. Sem fundamentos, Spring Boot vira mágica que você não controla.

- Tipos, operadores, estruturas de controle
- Orientação a objetos: classes, herança, interfaces, polimorfismo
- Collections: List, Map, Set
- Exceptions
- Generics básico

**Meta:** construir um sistema de CRUD em Java puro, sem framework. Arquivo de texto ou banco H2. Funciona no terminal.

### Fase 2 — Spring Boot básico (4–6 semanas)
- Spring Framework: IoC, injeção de dependência, Beans
- Spring Boot: setup, application.yml, auto-configuration
- Spring MVC: controllers, endpoints REST, status HTTP
- Spring Data JPA: entidades, repositórios, queries
- PostgreSQL + Docker

**Meta:** API REST com CRUD completo rodando em localhost com banco real.

### Fase 3 — Mercado real (4–6 semanas)
- Spring Security + JWT
- Validação de dados (`@Valid`, Bean Validation)
- Tratamento de exceções global (`@ControllerAdvice`)
- Testes com JUnit e Mockito
- Git: branches, Pull Requests, merge

**Meta:** API com autenticação, validação, tratamento de erro e pelo menos um teste de integração. Commit e deploy no GitHub.

---

## O projeto é mais importante que o curso

Um projeto completo no GitHub vale mais do que 10 certificados de conclusão.

Escolha um problema que você consegue explicar para qualquer pessoa:
- Sistema de tarefas (clássico, funciona)
- Controle de gastos pessoais
- Agenda de consultas
- Biblioteca pessoal

Simples. Completo. No ar.

---

## Como usar o Google corretamente

Pesquisar no Google não é trapaça. É o que todo dev profissional faz o dia inteiro.

O que muda é *o que* você pesquisa:

❌ `como fazer login com spring boot` → você vai copiar sem entender
✅ `spring security authentication flow how does it work` → você vai entender o mecanismo

Quando travar:
1. Tente resolver por 20–30 minutos sozinho
2. Leia a documentação oficial antes do Stack Overflow
3. Leia o erro completo — a resposta geralmente está nele
4. Pesquise o conceito, não o código pronto

---

## Consistência bate intensidade

Estudar 1 hora por dia durante 6 meses é melhor do que estudar 8 horas por dia durante 2 semanas e sumir.

Seu cérebro consolida memória durante o sono. Intervalos entre sessões de estudo fazem parte do aprendizado.

**Meta realista:** 5 dias por semana, 45–60 minutos. Fim de semana: projeto.

---

## Sinais de que você está progredindo

- Consegue construir features sem olhar tutorial
- Sabe o que pesquisar quando trava (e não o quê copiar)
- Consegue explicar o que seu código faz para outra pessoa
- Os erros do compilador começam a fazer sentido
- Você abre o IDE antes de abrir o YouTube

---

## Sinais de que você está no tutorial hell

- Terminou 3 cursos e ainda não tem nenhum projeto próprio no GitHub
- Consegue seguir o instrutor mas trava sozinho em qualquer variação
- Você "entendeu tudo" mas não consegue escrever um endpoint do zero sem consultar o tutorial
- Sua pasta de projetos tem 12 pastas com nome `teste`, `projeto-spring`, `aula3`

---

## O que fazer agora

1. Pare de assistir curso por 2 semanas
2. Abra o IDE
3. Tente construir uma API de CRUD do zero — sem tutorial aberto
4. Vai travar. Pesquise o conceito específico que está travando
5. Volte ao código

Isso vai doer. É assim que você aprende.

---

*Se quiser fazer esse processo acompanhado, com projeto real, PR desde o primeiro dia e feedback técnico individual: [Forgile — Do Código ao Contrato](https://forgile.com)*
