# Criador de Assinatura de E-mail 3Geo

Este projeto é uma aplicação web para gerar assinaturas de e-mail personalizadas para colaboradores da 3Geo. O usuário preenche um formulário com seus dados e, ao clicar em "Gerar Assinatura", recebe uma assinatura pronta para copiar e colar no e-mail.

## Funcionalidades

- Formulário para preenchimento de nome, e-mail, departamento, filial e celular corporativo.
- Exibição dinâmica de campos para celular corporativo e WhatsApp.
- Geração automática da assinatura em formato HTML, incluindo logo, informações de contato e links para site, LinkedIn e WhatsApp.
- Botão para copiar a assinatura gerada para a área de transferência.

## Estrutura do Projeto

- `index.html`: Página principal com o formulário e área de exibição da assinatura.
- `styles.css`: Estilos visuais para o formulário e assinatura.
- `script.js`: Lógica para manipulação do formulário, geração da assinatura e funcionalidades de cópia.

## Como Usar

1. Abra o arquivo `index.html` em seu navegador.
2. Preencha os campos do formulário com suas informações.
3. Clique em **Gerar Assinatura**.
4. Visualize a assinatura gerada.
5. Clique em **Copiar Assinatura** para copiar o conteúdo e cole em seu cliente de e-mail.

## Observações

- O campo de celular corporativo só aparece se selecionado "Sim" no formulário.
- O botão de WhatsApp só aparece se o campo correspondente for marcado.
- O projeto não requer backend ou instalação de dependências.

---

Desenvolvido para uso interno da 3Geo