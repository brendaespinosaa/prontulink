# Funcionalidades do ProntuLink

O ProntuLink é um protótipo de sistema para gerenciamento de pacientes e preenchimento de fichas de anamnese odontológica.

## 1. Painel inicial
- Visualização da quantidade de pacientes cadastrados.
- Visualização da quantidade de fichas de anamnese.
- Exibição dos pacientes cadastrados recentemente.

## 2. Gerenciamento de pacientes
- Cadastro de novos pacientes.
- Registro de informações pessoais e de contato.
- Consulta e pesquisa de pacientes por nome ou CPF.
- Edição e exclusão de cadastros.

## 3. Fichas de anamnese
- Criação de fichas odontológicas.
- Questionário com 49 perguntas sobre histórico médico, medicamentos, sintomas e condições bucais.
- Organização das perguntas em etapas.
- Preenchimento e edição das respostas.
- Salvamento automático das informações.
- Conclusão da ficha.

## 4. Exportação e armazenamento
- Exportação da ficha de anamnese em PDF.
- Exportação de backup dos registros em JSON.
- Importação de backups anteriormente exportados.
- Armazenamento local das informações no navegador.

## 5. Área profissional
- Campo reservado para anotações internas do profissional.
- Possibilidade de incluir ou não essas anotações na exportação em PDF.

## Observações técnicas

O protótipo foi desenvolvido utilizando HTML, CSS e JavaScript, com armazenamento local por meio do IndexedDB do navegador.

O sistema possui finalidade acadêmica e demonstrativa. Não deve ser utilizado para armazenar informações reais de pacientes ou substituir um sistema clínico em produção.
