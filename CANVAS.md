# 🎯 Canvas do Projeto Final — App Android

> **Como usar:** este é o primeiro documento do projeto. Preencha em grupo, em uma única aula, **antes de escrever qualquer linha de código**. Cada bloco tem no máximo 5 linhas — se não couber, o projeto está grande demais.
> Depois de preenchido e validado pelo professor, ele vira a base do [`PRD.md`](PRD.md).

| | |
|---|---|
| **Grupo nº** | |
| **Integrantes (3 a 4)** |4 |
| **Turma** | 3º ano — Ensino Médio |
| **Repositório** | `https://github.com/lmm5-web/projeto-final--clientta-` |
| **Data de preenchimento** | _16__/_09__/2026 |
| **Entrega final** | **10/12/2026** |

---

## 🧩 Bloco 1 — Nome e pitch do app

**Nome do app:** _(Clientta)_

**Pitch em uma frase:**
"O Clientta ajuda profissionais de clínicas de estética e outras clínicas a organizar seus atendimentos e agilizar o agendamento e o pré-atendimento dos clientes sem precisar de agendas e formulários de papel e de processos manuais para organizar informações e horários."



---

## 😖 Bloco 2 — Problema

Qual dor real vocês estão resolvendo? Descrevam uma situação concreta que alguém vive hoje.

-O cliente muitas vezes precisa entrar em contato com a clínica para descobrir preços, tratamentos disponíveis e horários, tornando o processo de agendamento mais demorado, pois depende da disponibilidade do profissional para responder. Por exemplo, profissionais como Danielle Macêdo da Uniclin que precisa organizar consultas e horários , além de coletar questionários, termos de responsabilidade e autorizações, muitas vezes utilizando papel. Como resultado, muitas vezes ocorre perda de documentos importantes ou confusão nos agendamentos por excesso de papelada, o que dificulta o cotidiano dos profissionais e afeta o atendimento ao cliente. Além disso, muitas vezes possíveis clientes se sentem constrangidos em entrar em contato para perguntar sobre preços e informações importantres.


**Como esse problema é resolvido hoje (sem o app)?**

-O cliente normalmente entra em contato por WhatsApp ou presencialmente atrás de informações. Após o agendamento, questionários e termos precisam ser preenchidos manualmente ou em papel, enquanto o profissional precisa controlar sua agenda separadamente e guardar toda a papelada.

---

## 👥 Bloco 3 — Público-alvo

Para quem é o app? Sejam específicos (idade, contexto, com que frequência usariam).

- **Perfil principal:** Principalmente para adultos, focando em facilitar o uso para o cliente e a comunicação entre ele e a clinica. 
- **Quando/onde usam:** o link para o app será disponibilizado nas redes sociais da clinica e como mensagem automática no whatsapp. será usado no cotidiano, quando for preciso agendar alguma consulta ou verificar os tratamentos oferecidos na clinica e suas informações.
- **Uma pessoa real que testaria o app:** _(Danielle Macêdo Sales Mendes, mãe de uma das integrantes do grupo e profissional estética)_

---

## 💡 Bloco 4 — Solução em uma tela

Descreva o que a **tela principal** mostra e o que o usuário consegue fazer nela.

- **A tela principal lista:**tratamentos disponíveis, preços, opção de agendamento, agendamentos já realizados e acesso ao pré-atendimento.
- **A ação principal do usuário é:**Escolher um tratamento e realizar o agendamento de forma rápida e intuitiva.
- **Depois de agir, o usuário vê:**A confirmação do atendimento, com o tratamento escolhido, data, horário e informações necessárias para o pré-atendimento.

---

## ✅ Bloco 5 — Funcionalidades do MVP

Máximo de **4 funcionalidades**.

| # | Funcionalidade | Essencial? | Quem faz |
|---|---|---|---|
| F1 |Visualizar tratamentos e preços | Sim | Cliente |
| F2 |Realizar e visualizar agendamentos | Sim |Cliente |
| F3 |Preencher questionários e termos de pré-atendimento | Sim/Não |Cliente |
| F4 |Organizar agenda e informações dos clientes |Sim  |Profissional |

---

## 🚫 Bloco 6 — Fora do escopo

O que o app **não** vai fazer nesta entrega. Escrever isso aqui protege vocês de perder o prazo.
❌ Pagamentos pelo aplicativo.
❌ Chat ou atendimento por mensagem dentro do aplicativo.
❌ Notificações push e integrações externas nesta primeira versão.

*Sugestões comuns de coisas a deixar de fora: login/cadastro, notificações push, chat, mapa, pagamento, modo offline completo, sincronização em nuvem.*

---

## ⚙️ Bloco 7 — Caminho técnico

Marque **uma** opção (as três valem a mesma nota):

- [X] **Opção A — Room:** dados salvos no próprio celular (lista de compras, agenda, diário de treino, controle financeiro)
- [ ] **Opção B — Retrofit:** dados vindos de uma API pública (notícias, filmes, feed, clima)
- [ ] **Opção C — Desafio:** API + salvar favoritos localmente

**Se escolheu B ou C — qual API?**

**Bibliotecas que o grupo vai usar:**Room, Android Jetpack e Material 3.

**Onde entra o `try/catch`?**

- Pode falhar: operações de leitura/gravação dos dados, cadastro de informações incompletas ou problemas durante uma operação no banco.
- O usuário vê a mensagem:“Não foi possível salvar as informações. Verifique os dados e tente novamente.”

---

## 🎨 Bloco 8 — Identidade visual
Item        /   	Definição do grupo

Nome exibido (strings.xml):	Clientta
Cor principa:l	#8F7AAE
Cores complementares:	#F7F3F8, #F5EEDB, #E8DFF0
Ideia do ícone 512×512:	Um símbolo simples que represente conexão, cuidado e organização, utilizando formas arredondadas e detalhes em lavanda
applicationId:	br.edu.ifpe.clientta
Versão inicial:	1.0 (versionCode 1)

---

## 👤 Bloco 9 — Equipe, papéis e riscos

| Integrante | Papel principal | Responsável por |
|---|---|---|
|Ana Clara | Dev / telas |Desenvolvimento das telas, navegação e componentes da interface |
|Sofia | Dev / dados (Room ou Retrofit) |Implementação do banco de dados local e organização dos dados |
|Letícia | Design e identidade visual |Cores, ícones, organização visual e identidade do Clientta |
|Maria Eduarda | Documentação, build e entrega |README, documentação, organização do projeto, testes e geração do APK/AAB |

Todas as integrantes participam da programação. O papel define quem responde principalmente por cada parte do projeto, mas as decisões e revisões são feitas em conjunto.

Riscos — o que pode dar errado e o plano B:

Risco:                          
-Dificuldade na implementação do Room ou surgimento de erros no banco de dados

-A interface ficar muito complexa ou difícil de usar

Plano B:
-Simplificar a estrutura do banco, revisar a implementação em conjunto e testar cada operação separadamente

-Reduzir a quantidade de elementos, manter apenas as funções essenciais e realizar testes com pessoas de fora do grupo

---

## 🤖 Bloco 10 — Acordo de trabalho com IA

A implementação pode ser feita com o **Gemini no Android Studio**. Vocês orientam, ele digita — e cada integrante precisa saber explicar o que entrou no projeto. Regras completas em [`docs/USO_DE_IA.md`](docs/USO_DE_IA.md).

**Três regras que vamos escrever no nosso `AGENTS.md`** _(o arquivo que diz à IA como trabalhar no nosso projeto)_:

1.A IA deve seguir a proposta do Clientta, mantendo a interface simples, intuitiva, acessível e com cores neutras e pastéis.
2.Nenhum código gerado pela IA será aceito sem que uma integrante leia, teste e consiga explicar o que foi alterado.
3.A IA deve priorizar soluções simples e compatíveis com o MVP, evitando adicionar funcionalidades que não estejam previstas no projeto.

**Combinados do grupo:**

- [X] Ninguém clica *Accept* no Agent Mode sem ler a mudança inteira.
- [X] Quem aceitou o código escreve o comentário de fronteira do arquivo.
- [X] Antes de cada marco, revisamos juntos: alguém aqui não entende alguma parte?
- [X] Nenhuma chave de API ou senha vai para o prompt.
- [X]Outro combinado nosso: Todas as integrantes devem testar as funcionalidades principais antes da entrega e comunicar ao grupo qualquer erro encontrado.

**Como vamos garantir que todos entendem tudo**:

-A integrante responsável por uma parte apresenta o código para as outras integrantes.

-As integrantes devem revisar e testar as alterações feitas pelas colegas.

-O grupo fará revisões conjuntas antes de cada marco do projeto.

-As tarefas serão revezadas sempre que possível para que todas tenham contato com telas, dados e código.

-Antes da entrega, cada integrante deverá fazer pelo menos uma pequena alteração no projeto sozinha, garantindo que consegue compreender e modificar o código.

---

## 🗓️ Bloco 11 — Marcos até 10/12

| Marco | Prazo | Como se comprova no GitHub |
|---|---|---|
| M1 — Canvas preenchido + repositório criado | 16/09 | `CANVAS.md` no `main` |
| M2 — PRD aprovado + telas rascunhadas | 30/09 | `PRD.md` + imagens em `docs/` |
| M3 — Funcionalidade base rodando | 21/10 | tela principal lista dados + 1 ação + `try/catch` |
| M4 — Dados completos (Room/Retrofit) e erros tratados | 11/11 | commits da camada de dados |
| M5 — Identidade visual + `.apk` de release testado | 25/11 | ícone, cores, `.apk` testado por 2 pessoas de fora |
| M6 — `.aab` + material de loja + `README.md` | 02/12 | pasta `loja/` + `README.md` completo |
| **Entrega e apresentação** | **10/12** | tag `v1.0` no repositório |

---

## 🏁 Bloco 12 — Definição de pronto

O grupo só considera o app pronto quando **todas** estas frases forem verdadeiras:

- [ ] O app abre e não fecha sozinho depois de 5 minutos de uso.
- [ ] A tela principal mostra dados reais (não texto de exemplo fixo no código).
- [ ] A ação principal funciona e o resultado aparece na tela.
- [ ] Quando algo falha, aparece uma mensagem clara — o app não quebra.
- [ ] O app tem nome, ícone e cor próprios (nada de ícone padrão do Android).
- [ ] Duas pessoas de fora do grupo instalaram o `.apk` e conseguiram usar sem explicação.
- [ ] O `README.md` explica o que o app faz, com o que foi feito e como gerar o build.
- [ ] O `docs/USO_DE_IA.md` e o `AGENTS.md` estão preenchidos.
- [ ] **Cada integrante consegue abrir o projeto e fazer uma mudança pequena sozinho** — trocar um texto, acrescentar um campo, mudar a ordem da lista.
- [ ] Todo arquivo nosso tem o comentário de fronteira escrito por nós.

---

## ✍️ Validação do professor

| | |
|---|---|
| Data | |
| Situação | ( ) Aprovado ( ) Aprovado com ajustes ( ) Refazer |
| Observações | |
