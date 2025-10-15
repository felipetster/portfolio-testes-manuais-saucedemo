# Portfólio de Testes Manuais | Aplicação SauceDemo


## 1. Sobre o Projeto

Este repositório serve como um portfólio prático das minhas habilidades em Teste de Software Manual e QA. O projeto consiste na aplicação de técnicas de teste fundamentais sobre o site de e-commerce de demonstração [SauceDemo](https://www.saucedemo.com/), um ambiente controlado e projetado para a prática de testes.

O objetivo é documentar todo o processo de QA, desde o planejamento inicial até a criação de casos de teste detalhados e o reporte de bugs.

---

## 2. Ferramentas Utilizadas

![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 3. Artefatos de Teste

Toda a documentação de teste está centralizada e organizada para fácil acesso.

###  Plano de Testes
O planejamento estratégico, escopo, tipos de teste e critérios para este projeto podem ser encontrados no documento [Plano_de_Testes.md](Plano_de_Testes.md).

###  Casos de Teste (Planilha Completa)
Todos os casos de teste, cobrindo as funcionalidades de Login, Inventário, Carrinho e Checkout, estão documentados na planilha do Google Sheets abaixo:

**[Acessar a Planilha Completa de Casos de Teste](https://docs.google.com/spreadsheets/d/1hq5zyTd_eKCGL7f-Bj2AkU124It_5Q2onTjMxDbgXj0/edit?usp=sharing)**

---

## 4. Exemplo de Caso de Teste

Abaixo, um exemplo da estrutura utilizada na documentação dos testes, preenchido para demonstrar o formato.

| Test Case ID | Test Case (Título) | Pré-Condição | Test Steps | Test Data | Resultado Esperado | Prioridade |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **TC-Login-003** | Verificar mensagem de erro com usuário bloqueado | Estar na página de login do SauceDemo. | 1. Inserir nome de usuário.<br>2. Inserir senha.<br>3. Clicar em "Login". | `Usuário: locked_out_user`<br>`Senha: secret_sauce` | A mensagem de erro "Epic sadface: Sorry, this user has been locked out." é exibida. | Alta |

*(Nota: As colunas "Resultado Real" e "Status" são preenchidas na planilha durante a execução dos testes.)*

---

## 5. Exemplo de Relatório de Bug

Abaixo, um exemplo de como os defeitos encontrados são documentados.

* **ID do Bug:** `BUG-Inventario-01`
* **Título:** `Página de Inventário - Imagem do produto "Sauce Labs Fleece Jacket" está incorreta`
* **Passos para Reproduzir:**
    1. Logar no sistema com o usuário `problem_user`.
    2. Na página de inventário, observar a imagem do produto "Sauce Labs Fleece Jacket".
* **Comportamento Atual:** A imagem exibida é a de um cachorro, a mesma dos outros produtos.
* **Comportamento Esperado:** A imagem deveria ser a de uma jaqueta.
