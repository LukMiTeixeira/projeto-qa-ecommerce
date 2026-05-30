# projeto-qa-ecommerce
Projeto prático de QA: Planejamento, cenários em BDD, reporte de bugs e automação low-code
Markdown
# 🎯 Projeto de QA - Validação de E-commerce

Este projeto tem como objetivo aplicar técnicas de Quality Assurance (QA) para validar o fluxo principal de compras (Busca, Carrinho e Checkout) do e-commerce [[Nome do Site](https://www.mercadolivre.com.br/)].

---

## 🧠 1. Planejamento e Mapa Mental
Para entender a amplitude dos testes, mapeei as funcionalidades utilizando um mapa mental. 
> 📌 [Clique aqui para visualizar o mapa mental completo](./documentacao/mapa-mental.png) (ou insira a imagem direto aqui).

---

## 📝 2. Cenários de Teste (BDD)
Os cenários foram mapeados utilizando a estrutura Gherkin (Dado/Quando/Então). Abaixo estão alguns exemplos principais:

| ID | Funcionalidade | Cenário de Teste (BDD) | Status |
| :--- | :--- | :--- | :--- |
| CT01 | Busca | **Dado** que estou na home... **Quando** pesquiso por um produto válido... **Então** o sistema retorna o item correspondente. | ✅ Passou |
| CT02 | Carrinho | **Dado** que tenho um item no carrinho... **Quando** altero a quantidade para zero... **Então** o item deve ser removido. | ❌ Falhou |

---

## 🐛 3. Gestão de Defeitos (Bugs Reportados)
Durante a execução, os problemas encontrados foram documentados de forma profissional na aba de Issues deste repositório.
* 📋 [Visualizar os Bugs Reportados](Link-da-sua-aba-de-issues)

---

## 🤖 4. Automação Low-Code (Selenium IDE)
Para demonstrar a viabilidade de testes regressivos automatizados, criei um script utilizando o **Selenium IDE**.

**Como rodar o teste:**
1. Instale a extensão do Selenium IDE no Chrome/Firefox.
2. Baixe o arquivo localizado na pasta `/automacao/fluxo-compra.side` deste repositório.
3. Abra o Selenium IDE, clique em "Open an existing project" e selecione o arquivo.
4. Clique no botão de Play para assistir à execução automática.
