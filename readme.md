# 🏨 Formulário de Feedback (Hotel Star Rating)

Um formulário de pesquisa de satisfação projetado para um hotel, com foco especial na usabilidade das avaliações por estrela.

## ⭐ Recursos do Formulário

* **Star Rating CSS:** Avaliações visuais de 1 a 5 estrelas implementadas puramente com HTML (`<input type="radio">`) e CSS (usando o truque `direction: rtl`).
* **`<fieldset>` e `<legend>`:** Utilizados para agrupar logicamente as perguntas (ex: Avaliações do Quarto, Dados Pessoais).
* **Campos Essenciais:** Inclui nome, e-mail, e um campo `textarea` para comentários abertos.

## ⚠️ Nota

Este é um formulário *front-end* (apenas HTML e CSS). Para armazenar as respostas, ele precisaria ser conectado a um servidor (back-end) que processasse a ação `action="/submit_feedback"`.