# ONG Corrente do Bem - Atividade 1

Este projeto é um site estático de 3 páginas para uma ONG fictícia, a "Corrente do Bem". Foi desenvolvido como um exercício focado em **HTML5 semântico** e **JavaScript puro (inline)** para interatividade em formulários.

## 🚀 Link de Visualização (Deploy)

O site foi publicado usando o GitHub Pages e pode ser acessado no link abaixo:

https://gabrielalvesoliver27-spec.github.io/Atividade-4/

---

## 📖 Páginas do Projeto

O site é composto por 3 páginas HTML:

1.  **`index.html` (Página Inicial)**
    * Apresenta a ONG, sua missão e informações de contato.
    * Contém links de navegação para as outras seções.

2.  **`projetos.html` (Página de Projetos)**
    * Detalha as iniciativas da ONG (Educação, Cozinha Comunitária, Capacitação).
    * Explica as formas de ajuda, como voluntariado e doação.

3.  **`cadastro.html` (Página de Cadastro)**
    * Contém um formulário unificado para voluntários e doadores.
    * O formulário é organizado com `<fieldset>` e `<legend>` para "Dados Pessoais", "Endereço" e "Interesse".

---

## 🛠️ Destaques Técnicos

O principal recurso técnico deste projeto está na página `cadastro.html`:

* **Validação HTML5 Nativa:** Utiliza atributos como `required`, `pattern`, `maxlength` e `type="email"` para validação de dados diretamente pelo navegador.
* **Máscaras de Formulário (JavaScript):** Utiliza **JavaScript inline** (dentro da tag `<script>`) para aplicar máscaras de formatação em tempo real (enquanto o usuário digita) para os campos:
    * CPF (`000.000.000-00`)
    * Telefone (`(00) 00000-0000`)
    * CEP (`00000-000`)

## 💻 Como Visualizar Localmente

Não é necessário nenhum servidor ou instalação.

1.  Clone este repositório para sua máquina.
2.  Abra o arquivo `index.html` diretamente no seu navegador.
