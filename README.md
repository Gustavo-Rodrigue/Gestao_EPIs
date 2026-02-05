# 🛡️ Sistema de Gestão de EPIs 2026 (Protótipo)

> **⚠️ AVISO: PROJETO DE TESTE**
> Este repositório contém um **protótipo funcional** desenvolvido para fins de estudo e teste de tecnologias front-end e integração com serviços como Firebase e EmailJS. Não é uma versão final de produção.

## 📋 Sobre o Projeto
Uma aplicação web moderna e responsiva focada no controle e distribuição de Equipamentos de Proteção Individual (EPIs) em ambiente escolar/industrial. O sistema permite que alunos solicitem materiais e que administradores gerenciem o fluxo de entregas.

## 🚀 Funcionalidades Principais

### 👤 Para o Usuário (Aluno)
- **Login Seguro:** Autenticação via Google (Firebase).
- **Seleção Inteligente:** Escolha de turno, turma e nome (banco de dados em LocalStorage).
- **Catálogo de Materiais:** Seleção de itens (botas, calças, óculos) com validação de tamanhos e limites de quantidade.
- **Carrinho de Pedidos:** Visualização dos itens antes do envio.

### ⚙️ Para o Administrador
- **Painel Administrativo:**
  - Gerenciar Turmas (Renomear, Esvaziar).
  - Adicionar novos alunos.
  - Editar dados de alunos existentes.
- **Dashboard de Status:** Acompanhamento do fluxo (Solicitado -> Separação -> Entregue).
- **Bloqueio de Acesso:** Restrição para e-mails institucionais (`@aluno.senai.br`) e lista branca de Admins.

### 📤 Automação
- **Envio de E-mail:** Integração com EmailJS para notificar o setor responsável.
- **Exportação Excel:** Geração automática de planilha `.xlsx` com os pedidos.

## 🛠️ Tecnologias Utilizadas
- **HTML5 & CSS3:** Design responsivo com variáveis CSS e Layout Grid/Flexbox.
- **JavaScript (ES6+):** Lógica de negócios e manipulação do DOM.
- **Firebase Auth:** Sistema de login e segurança.
- **LocalStorage:** Persistência de dados local (simulando banco de dados).
- **Bibliotecas:** `SheetJS` (Excel), `EmailJS` (Envio de e-mails), `FontAwesome` (Ícones).

## ▶️ Como Rodar
1. Baixe o arquivo `index.html`.
2. Abra através de um servidor local (ex: Extensão "Live Server" do VS Code) para que a autenticação do Firebase funcione corretamente.
3. O login exige uma conta Google.

---
*Desenvolvido como projeto de teste.*
