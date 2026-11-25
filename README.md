# 🦷 ProntuLink – Gerenciamento de Pacientes e Anamnese Odontológica

![Project](https://img.shields.io/badge/Project-ProntuLink-0A7EA4?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Academic%20Prototype-orange?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![IndexedDB](https://img.shields.io/badge/IndexedDB-4479A1?style=for-the-badge&logo=googlechrome&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)

---

## 📌 Sobre o projeto

O **ProntuLink** é um protótipo de sistema desenvolvido com o objetivo de facilitar o gerenciamento de pacientes e o preenchimento de fichas de anamnese odontológica.

A solução busca centralizar informações cadastrais e clínicas em uma interface organizada e intuitiva, permitindo o registro, a consulta e a atualização dos dados dos pacientes.

O projeto foi desenvolvido no contexto acadêmico, em parceria com a **Unir Clínicas**, considerando a necessidade de otimizar processos relacionados à organização e ao acesso às informações durante o atendimento odontológico.

## 🎯 Objetivo geral

Desenvolver um protótipo que facilite o gerenciamento de pacientes e a organização de informações clínicas por meio de fichas digitais de anamnese odontológica.

## 🎯 Objetivos específicos

- Facilitar o cadastro e o gerenciamento de pacientes.
- Organizar informações pessoais e de contato.
- Disponibilizar fichas digitais de anamnese odontológica.
- Estruturar questionários para registro do histórico médico e odontológico.
- Permitir a edição e exportação das fichas em PDF.
- Disponibilizar recursos para exportação e importação de backups.
- Melhorar a organização e a acessibilidade das informações registradas.

## ⚙️ Funcionalidades

### 📊 Painel inicial

- Visualização da quantidade de pacientes cadastrados.
- Visualização da quantidade de fichas de anamnese.
- Exibição dos pacientes cadastrados recentemente.

### 👥 Gerenciamento de pacientes

- Cadastro de novos pacientes.
- Registro de informações pessoais e de contato.
- Pesquisa de pacientes por nome ou CPF.
- Edição e exclusão de cadastros.

### 📝 Fichas de anamnese

- Criação de fichas de anamnese odontológica.
- Questionário composto por 49 perguntas.
- Organização das perguntas em etapas.
- Preenchimento e edição das respostas.
- Salvamento automático das informações.
- Acompanhamento do progresso do preenchimento.
- Conclusão das fichas.

### 📄 Exportação e armazenamento

- Exportação das fichas em PDF por meio do recurso de impressão do navegador.
- Exportação de backups em formato JSON.
- Importação de backups anteriormente exportados.
- Armazenamento local das informações utilizando IndexedDB.

### 🩺 Área profissional

- Campo reservado para anotações internas do profissional.
- Opção de incluir ou não as anotações na exportação em PDF.

## 💻 Tecnologias utilizadas

O protótipo foi desenvolvido utilizando tecnologias web, com CSS e JavaScript incorporados ao arquivo HTML.

| Tecnologia | Aplicação |
|---|---|
| HTML5 | Estrutura e organização dos elementos da aplicação. |
| CSS3 | Estilização, layout e identidade visual da interface. |
| JavaScript | Implementação das funcionalidades, interações e regras de funcionamento. |
| IndexedDB | Armazenamento local dos registros no navegador. |
| JSON | Estruturação dos dados para exportação e importação de backups. |

### 🛠️ Technologies & Tools

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![IndexedDB](https://img.shields.io/badge/IndexedDB-4479A1?style=flat-square&logo=googlechrome&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white)

## 🏗️ Estrutura do projeto

O repositório está organizado em pastas que reúnem a documentação, o protótipo e as evidências visuais do desenvolvimento e da utilização do sistema.

```text
prontulink/
│
├── documentacao/
│   ├── 01-descricao-do-projeto.md
│   ├── 02-requisitos-do-sistema.md
│   ├── 03-funcionalidades.md
│   └── 04-testes-e-validacao.md
│
├── prototipo/
│   └── ProntuLink .html
│
├── evidencias/
│   ├── cadastrarCliente.png
│   ├── cadastrarCliente2.png
│   ├── declaracaoCliente.png
│   ├── fichaCliente.png
│   ├── fichaCliente2.png
│   ├── fichaCliente3.png
│   ├── fichaCliente4.png
│   ├── fichaCliente5.png
│   ├── fichaCliente6.png
│   ├── fichaCliente7.png
│   ├── fichaCliente8.png
│   ├── telaPacientes.png
│   ├── telainicial.png
│   └── telainicialCliente.png
│
└── README.md
```

## 📸 Evidências do projeto

A pasta `evidencias/` reúne capturas de tela do ProntuLink durante sua utilização, demonstrando visualmente as interfaces e funcionalidades disponíveis no protótipo.

As evidências estão organizadas em três categorias principais:

**🖥️ Painel inicial e gerenciamento de pacientes**
- Visualização da tela inicial.
- Apresentação da área de pacientes.
- Interface inicial relacionada ao paciente.

**👥 Cadastro de pacientes**
- Telas de cadastro.
- Campos para preenchimento das informações cadastrais.

**📝 Fichas de anamnese e declarações**
- Diferentes etapas do questionário odontológico.
- Apresentação das informações registradas.
- Evidência da declaração relacionada ao paciente.

🔗 [Acessar todas as evidências no GitHub](https://github.com/brendaespinosaa/prontulink/tree/main/evidencias)

## 🚀 Como executar o protótipo

Para executar o ProntuLink localmente:

1. Acesse o repositório do projeto no GitHub.
2. Entre na pasta `prototipo`.
3. Faça o download do arquivo `ProntuLink .html`.
4. Abra o arquivo em um navegador de internet atualizado.
5. Explore as funcionalidades disponíveis.

Não é necessária a instalação de ferramentas adicionais para a visualização local do protótipo.

## 🧪 Testes e validação

A validação do protótipo considera aspectos relacionados a:

- Abertura e funcionamento da aplicação.
- Navegação entre as seções.
- Cadastro, consulta, edição e exclusão de pacientes.
- Preenchimento e salvamento das fichas de anamnese.
- Exportação e importação de arquivos.
- Organização e apresentação das informações.

Os cenários e critérios de avaliação estão detalhados no arquivo `04-testes-e-validacao.md`.

As capturas de tela disponíveis na pasta `evidencias/` complementam a documentação, demonstrando visualmente as interfaces e os recursos do protótipo.

## 🔒 Segurança e privacidade

O ProntuLink possui finalidade exclusivamente acadêmica e demonstrativa.

As informações são armazenadas localmente no navegador por meio do IndexedDB. O protótipo não possui infraestrutura de armazenamento em servidor ou integração com sistemas externos de saúde.

Por se tratar de uma aplicação demonstrativa, devem ser utilizados exclusivamente dados fictícios. O projeto não deve ser utilizado para armazenar ou processar informações reais de pacientes.

Uma eventual implementação em ambiente de produção exigiria mecanismos adicionais de autenticação, controle de acesso, proteção de dados, segurança da informação e conformidade com a Lei Geral de Proteção de Dados (LGPD).

## ⚠️ Limitações do projeto

O ProntuLink é um protótipo acadêmico e não substitui sistemas oficiais de prontuário eletrônico.

A integração com plataformas externas de saúde, o armazenamento centralizado e a implementação de mecanismos avançados de segurança dependem de desenvolvimento adicional.

## 🎓 Contexto acadêmico

Projeto desenvolvido no contexto acadêmico, em parceria com a **Unir Clínicas**, com foco na aplicação de conhecimentos de tecnologia da informação para propor melhorias nos processos de gerenciamento de pacientes e organização de informações odontológicas.

**Instituição parceira:** Unir Clínicas  
**Localização:** Porto Alegre – RS, Brasil.

## 🔗 Links do projeto

- 📁 **Google Drive:** [Acessar materiais e arquivos do projeto](https://drive.google.com/drive/folders/1s4EVz2SaqyKlxUOrD7WpLPltttRmTSnB?usp=sharing)
- 💻 **GitHub:** [Acessar repositório ProntuLink](https://github.com/brendaespinosaa/prontulink)
- 🦷 **Protótipo:** [Visualizar arquivo HTML](https://github.com/brendaespinosaa/prontulink/blob/main/prototipo/ProntuLink%20.html)
- 📸 **Evidências:** [Visualizar capturas de tela](https://github.com/brendaespinosaa/prontulink/tree/main/evidencias)

---

<p align="center">
  🦷 <strong>ProntuLink</strong>
  <br>
  <em>Organizando informações, facilitando o acesso e contribuindo para a eficiência dos processos odontológicos.</em>
</p>
