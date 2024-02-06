---
layout: page
title: Ambiente de Prueba La Fabril
permalink: /about/
---

Este es un ambiente de prueba del chatbot que simula los entornos de aplicacion en un sitio web.

<link rel="stylesheet" href="https://www.gstatic.com/dialogflow-console/fast/df-messenger/prod/v1/themes/df-messenger-default.css">
<script src="https://www.gstatic.com/dialogflow-console/fast/df-messenger/prod/v1/df-messenger.js"></script>
<df-messenger
  location="us-central1"
  project-id="fabril-chatbot-poc"
  agent-id="025c18b4-795f-4da7-bf18-5c7a1417e916"
  language-code="es"
  max-query-length="-1">
  <df-messenger-chat-bubble
   chat-title="Fabril-Chatbot">
  </df-messenger-chat-bubble>
</df-messenger>
<style>
  df-messenger {
    z-index: 999;
    position: fixed;
    bottom: 16px;
    right: 16px;
  }
</style>
<!-- You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll -->
