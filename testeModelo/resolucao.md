# Teste Modelo SIG 2022/23

## 7 (14 valores) - múltiplas perguntas

a. Tabela de requisitos

Requisitos funcionais:
> 1. pesquisa de livros por título, editora, ou autor(es)
> 2. empréstimo de livros
> 3. validação da cedência e da devolução
> 4. avaliação do empréstimo por quem empresta de 1-5, podendo deixar comentários

Requisitos não funcionais:
> 5. aplicação disponível em navegadores web e em smartphones
> 6. idioma em português e inglês

---

b. ver "7-useCaseDiagram.puml"

---

c.

**Pré-condição**: O utilizador é aluno da UL, disposto a emprestar livros ou que pretenda pedir emprestado

**Cenário principal**: 
1. O utilizador seleciona a opção registar
2. O utilizador escolhe a escola a que pertence das opções disponíveis (dropdown)
3. O utilizador preenche o utilizador de email (o sistema já possúi o domínio da escola), nome e número de aluno
4. O utilizador submete o formulário
5. O sistema cria o utilizador com as informações submetidas, mas inactivo
6. O sistema envia, para o email, um link de validação único que tenha alguma referência ao utilizador
7. O utilizador acede ao link de forma a ativar a sua conta
8. O sistema torna a conta do utilizador ativa

---

d. Ver 7-classDiagram.puml