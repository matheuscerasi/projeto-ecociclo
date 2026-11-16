# Registro de uso de inteligência artificial — EcoCiclo

## Ferramenta utilizada nesta etapa de revisão
ChatGPT (OpenAI), utilizado como apoio para leitura dos arquivos fornecidos, identificação de inconsistências de estrutura, organização de caminhos e revisão do JavaScript/documentação.

## Etapa final (09/11/2026) — Claude (Anthropic)
Usado para finalizar o projeto: conferir o pacote contra o roteiro da 2ª entrega, remover o script duplicado do formulário, criar o menu mobile e o rascunho em `localStorage`, testar no navegador e atualizar a documentação.
- **Prompt:** “termine para mim” (com o roteiro da entrega, o ZIP do site e os slides anexados).
- **Aceito:** correções de `contato.html`, `script.js` e `css/style.css`; testes automatizados; atualização dos docs.
- **Corrigido durante o teste:** a mensagem de erro do checkbox quebrava o layout (inserida dentro do `label`); passou a ser inserida depois do `label`.
- **Não feito pela IA:** validação W3C oficial, GitHub, deploy e RAs.

## Solicitação registrada na etapa anterior
“Veja os arquivos atenciosamente e veja o que falta, e me entregue o que eu devo passar para o professor” e, em seguida, “me manda tudo já pronto, menos os slides”.

## Sugestões incorporadas nesta revisão
- Padronização dos nomes das páginas HTML para corresponder aos links internos.
- Organização do CSS em `css/style.css`.
- Organização das imagens em `img/` e correção dos caminhos usados pela galeria.
- Revisão da validação JavaScript para exibir mensagens acessíveis e destacar campos inválidos.
- Manutenção da preferência de tema no `localStorage`.
- Inclusão de documentação complementar e de uma observação clara de que o formulário é demonstrativo.

## Limitações e revisão humana
A IA não confirmou o funcionamento do deploy, não criou commits/branches/Pull Requests no GitHub, não executou a validação oficial W3C das páginas publicadas e não gerou evidências de testes físicos em diferentes dispositivos.

## Etapa de 16/11/2026 — Claude (Anthropic)
Usado para unir a pasta de trabalho (players de áudio e imagens novas) ao pacote da entrega, sem perder o menu mobile, o `localStorage` e a validação revisada, e para conferir o pacote contra o roteiro.
- **Aceito:** inclusão dos players e do CSS dos áudios; testes no navegador das 10 páginas.
- **Corrigido na revisão:** nomes de imagem com espaços (o W3C Validator rejeita) foram trocados por nomes sem espaços; um `</section>` sobrando no `sobre.html` da pasta de trabalho não foi aproveitado.
- **Não feito pela IA:** validação W3C oficial, commits/pull request no GitHub e deploy.
