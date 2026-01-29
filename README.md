# 📚 Projeto Alunos - Consumo de API

Projeto simples em HTML, CSS e `JavaScript` para cadastro e listagem de alunos com suas respectivas notas de avaliação, consumindo uma API REST externa.

---

### 🧠 Sobre o projeto

A aplicação permite:

Listar alunos já cadastrados via API

Cadastrar novos alunos informando nome e nota

Atualizar automaticamente a tabela após inserção

Interface responsiva com Bootstrap

Os dados são consumidos e enviados para uma API REST pública.

---

### 🛠️ Tecnologias utilizadas

HTML5

CSS3

JavaScript (ES6+)

Bootstrap 5

Fetch API

---

### 📂 Estrutura do projeto
/
├── index.html
├── css/
│   └── style.css
└── js/
    └── alunos.js

---

### 🌐 API utilizada
http://leoproti.com.br:8004/alunos

Endpoints usados:

GET /alunos → Lista os alunos

POST /alunos → Cadastra um novo aluno

Exemplo de payload enviado:

{
  "nome": "João",
  "preco": 8.5
}


⚠️ Apesar do nome da variável ser preco, ela representa a nota da avaliação.

---

### ▶️ Como executar o projeto

Clone o repositório:

´
git clone https://github.com/seu-usuario/seu-repositorio.git
´

Acesse a pasta do projeto:
´
cd seu-repositorio
´

Abra o arquivo index.html no navegador

Não é necessário servidor local.

---

### 📸 Funcionalidades da interface

Formulário para adicionar aluno e nota

Validação básica de campos

Tabela dinâmica com dados vindos da API

Layout responsivo

---

### 📌 Observações

O projeto é totalmente front-end

* Ideal para estudos de:

* Consumo de API REST

* Manipulação de DOM

* Fetch API

* Integração com Bootstrap

---

### ✨ Possíveis melhorias futuras

Edição e exclusão de alunos

Feedback visual com alerts Bootstrap

Tratamento de erros mais detalhado

Paginação dos dados

Separação de responsabilidades (MVC)

---

### 🧑‍💻 Autor

Desenvolvido para fins educacionais e aprendizado em consumo de APIs com JavaScript por Douglas Coimbra.
