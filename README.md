# 📱 Atividade 01 — Protótipo de Interface (FlutterFlow)

Documentação do projeto desenvolvido no **FlutterFlow**, com foco na construção das telas, organização dos componentes de layout e configuração das ações de navegação.

---

## 👥 Integrantes do Grupo

- **Matheus de Oliveira Soares Pereira**
- **Vitor Giliardi dos Santos**
- **Guilherme Henrique de Almeida Araújo**
- **Lucas Braga Scudeler**
- **Davi Alberes Monteiro Mendes**
- **Julio Cesar Morais Silva**

---

## 📱 Fluxo do Aplicativo e Páginas

O projeto foi estruturado em um fluxo contínuo dividido em **6 telas principais**:

| Página | Função no Aplicativo |
|---|---|
| `HomePage` | Tela principal/inicial do sistema. |
| `LoginPage` | Tela de login para autenticação de usuários. |
| `CadastroPage` | Primeira etapa do formulário de criação de conta. |
| `CadastroPage2` | Segunda etapa do cadastro de informações. |
| `CadastroPage3` | Terceira etapa do cadastro de dados do usuário. |
| `CadastroPage4` | Tela final de verificação de e-mail e confirmação por código. |

---

## 🛠️ Recursos e Componentes Utilizados

### 📐 Estruturação de Layout

Foram utilizados diferentes componentes para organização e alinhamento dos elementos das telas, como:

- `Container`
- `Column`
- `Row`
- `Divider`

Esses componentes foram utilizados para estruturar o layout e organizar os elementos de forma adequada.

### 📝 Componentes de Formulário

Foram utilizados múltiplos `TextField` para entrada de informações do usuário.

Na `CadastroPage4`, foram utilizados campos específicos para inserção do **código de verificação**.

Também foram utilizados botões interativos (`Button`) para permitir a interação do usuário com o sistema.

### 🔀 Navegação e Actions

Foram configuradas **Navigate Actions** para realizar a transição entre as diferentes páginas do aplicativo.

O fluxo de navegação foi estruturado da seguinte forma:

```text
HomePage
   ↓
LoginPage
   ↓
CadastroPage
   ↓
CadastroPage2
   ↓
CadastroPage3
   ↓
CadastroPage4
