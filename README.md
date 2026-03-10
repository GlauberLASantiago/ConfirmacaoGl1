# 📅 Confirmação de Presença

O **Confirmação de Presença** é uma aplicação web desenvolvida para facilitar o registo e a visualização de respostas de presença em eventos. Com uma interface moderna, compacta e intuitiva, o sistema permite que os participantes informem rapidamente se irão comparecer, enquanto a lista de respondentes é atualizada e organizada automaticamente por categoria de resposta.

## ✨ Funcionalidades

- Formulário simples para confirmação de presença
- Campo para inserção do nome do participante
- Seleção de resposta com botão deslizante:
  - **Sim**
  - **Não**
  - **Incerto**
- Envio assíncrono dos dados sem recarregar a página
- Atualização automática da lista de respondentes
- Organização dos participantes por status de resposta
- Exibição do título do evento de forma dinâmica
- Mensagens visuais de sucesso e erro
- Interface responsiva com design limpo e elegante

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **Tailwind CSS**
- **Font Awesome**
- **Google Apps Script**
- **Google Sheets**

## ⚙️ Como funciona

A aplicação utiliza um formulário web para recolher o nome do participante e a sua resposta de presença. Os dados são enviados para um **Google Apps Script**, que pode armazená-los numa **planilha Google Sheets**.

Ao mesmo tempo, a aplicação consulta uma planilha pública para atualizar a lista de respondentes, exibindo os nomes agrupados conforme a resposta enviada.

## 📌 Respostas disponíveis

O participante pode escolher uma das seguintes opções:

- **Sim** — confirma presença no evento
- **Não** — informa que não poderá comparecer
- **Incerto** — indica dúvida ou indefinição

## ▶️ Como usar

1. Abra a página da aplicação no navegador.
2. Digite o seu nome no campo indicado.
3. Escolha uma das opções de presença:
   - Sim
   - Não
   - Incerto
4. Clique em **Enviar**.
5. Aguarde a mensagem de confirmação.
6. Veja a lista de respondentes atualizada abaixo do formulário.

## 🔄 Atualização da lista

A lista de participantes:

- é carregada automaticamente ao abrir a página;
- pode ser atualizada manualmente pelo botão de recarregamento;
- exibe os nomes agrupados por categoria de resposta.

## 🎨 Interface

O projeto utiliza uma identidade visual suave e organizada, com:

- paleta de cores em tons de bege, azul, vermelho e dourado;
- cartões com bordas arredondadas;
- seletor deslizante para resposta;
- notificações compactas para feedback;
- lista de participantes com agrupamento visual claro.

## 🌐 Integração

O sistema depende de dois serviços externos:

- **Google Apps Script** para receber e processar os dados enviados
- **Google Sheets** para leitura e exibição das confirmações registradas

## 📁 Estrutura do Projeto

Como o projeto está centralizado em um único arquivo HTML, sua estrutura inclui:

- **HTML**: formulário, lista de participantes e elementos da interface
- **CSS**: personalização visual, animações e responsividade
- **JavaScript**: lógica de envio, leitura, agrupamento e atualização dos dados

## ✅ Possíveis usos

Este projeto pode ser utilizado para:

- confirmação de presença em eventos académicos
- convites para reuniões ou encontros
- organização de festas e celebrações
- controlo simples de participação em atividades

## 📄 Licença

Este projeto pode ser utilizado para fins educacionais, académicos e organizacionais.
