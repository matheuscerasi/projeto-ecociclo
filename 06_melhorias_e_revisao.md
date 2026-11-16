# Melhorias e revisão da versão final

| Ponto observado | Ajuste realizado |
|---|---|
| Arquivos HTML com sufixos como `(1)` e `(4)`, incompatíveis com links internos canônicos | Renomeados para os dez nomes esperados (`index.html`, `sobre.html` etc.). |
| CSS referenciado em `css/style.css`, mas armazenado na raiz com nome diferente | Criada a pasta `css/` e padronizado o arquivo `style.css`. |
| Imagens da galeria apontavam para arquivos inexistentes no ZIP | Galeria ajustada para utilizar as seis imagens do pacote e, em 16/11, atualizada para as seis imagens novas do projeto (`img/reciclagem-parque-1.png` etc.), com nomes sem espaços para passar no W3C Validator. |
| Validação JS não destacava visualmente os campos inválidos nem apresentava confirmação clara | Revisada a validação, com mensagens, `aria-invalid`, bordas destacadas e retorno de formulário demonstrativo. |
| Formulário não possui serviço de recebimento | Mantido como demonstrativo e explicitado que não envia dados a um servidor. |
| Documentação complementar estava incompleta ou não separada em `/docs` | Criados escopo, diário, orçamento, plano de testes, registro de IA e revisão. |
| `contato.html` tinha um `<script>` próprio que disputava o envio do formulário com `script.js` (mensagens duplicadas e conflitantes) | Script removido; toda a validação ficou em `script.js`, e a data máxima do campo de nascimento foi movida para lá. |
| Dados do formulário se perdiam ao recarregar | Rascunho salvo no `localStorage` e recuperado; apagado após envio válido. |
| Menu do celular era só uma barra de rolagem horizontal | Botão “Menu” com `aria-expanded`, que fecha com Esc. |
| Mensagem de erro do checkbox desalinhava o layout | Mensagem posicionada após o `label`. |
| Não havia alternativa em áudio para as páginas (pedido do professor, por acessibilidade) | Player `<audio controls>` com resumo narrado em MP3 (~30 s) em cada uma das 10 páginas, arquivos em `audios/`; estilo próprio com suporte ao modo escuro. |
