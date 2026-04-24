# Portfolio Audiovisual - Marcelo Ferreira

Este é o site oficial de portfólio de **Marcelo Ferreira**, Assistente de Câmera e Focus Puller. O projeto foi desenvolvido com foco em alta performance visual, design minimalista e responsividade para dispositivos móveis.

## 🚀 Tecnologias Utilizadas

* **HTML5** - Estrutura semântica.
* **CSS3** - Estilização personalizada com variáveis e animações de scroll.
* **JavaScript (Vanilla)** - Renderização dinâmica da galeria e lógica do formulário.
* **Formspree** - Integração de backend para recebimento de orçamentos via e-mail.

## 📸 Funcionalidades

* **Galeria Dinâmica:** Sistema que carrega fotos automaticamente a partir de um array JavaScript, facilitando a atualização de novos trabalhos.
* **Lightbox:** Visualização de imagens em ecrã inteiro com navegação simplificada.
* **Preview de Vídeo:** Bastidores que iniciam o play automaticamente ao passar o rato (hover).
* **Formulário Inteligente:** Validação de campos e envio direto para o e-mail do profissional.
* **Design Dark:** Interface otimizada para profissionais da área de cinema e fotografia.

## 🛠 Como atualizar a Galeria

Para adicionar novas fotos ao site:
1. Faça o upload da imagem para a pasta raiz do projeto.
2. Abra o ficheiro `index.html`.
3. Localize a constante `galleryImages` dentro da tag `<script>`.
4. Adicione uma nova linha seguindo o padrão:
   ```javascript
   { src: 'nome-da-foto.jpg', caption: 'Título do Trabalho' },
