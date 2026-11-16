# Diário de bordo — EcoCiclo

| Data | Atividade / observação | Resultado |
|---|---|---|
| 21/09/2026 | Data registrada no README original para identificação do projeto. | Referência documental recebida. |
| 09/11/2026 | Revisão dos arquivos da entrega final e organização do pacote. | Padronização de nomes e caminhos, organização de CSS/imagens e revisão do JavaScript. |
| 09/11/2026 | Remoção do script duplicado de `contato.html` (conflitava com `script.js`); inclusão de menu para celular e rascunho do formulário no `localStorage`; correção do layout da mensagem de erro do checkbox. | Ver `06_melhorias_e_revisao.md`. |
| 09/11/2026 | Testes automatizados em Chromium (Playwright) nas dez páginas: links, imagens, alt, rolagem horizontal, formulário, localStorage, tema, teclado e menu mobile. | Resultado em `04_testes_e_evidencias.md`; prints em `docs/evidencias/`. |
| 16/11/2026 | Inclusão dos players de áudio (10 MP3, um por página) e das imagens novas da galeria; unificação da pasta de trabalho com o pacote da entrega. | Ver `06_melhorias_e_revisao.md`. |
| 16/11/2026 | Validação das páginas publicadas no W3C Validator (vnu 26.11.14) e levantamento das contribuições no GitHub. | Prints em `docs/evidencias/` (`w3c-*.png`, `github-*.png`). |

## Dificuldades identificadas na revisão do pacote
- Nomes de arquivos continham sufixos de cópia, enquanto os links internos usavam nomes canônicos.
- O CSS era referenciado em `css/style.css`, mas estava fora da pasta `css`.
- As imagens chamadas pela galeria não estavam presentes com aqueles nomes; o ZIP continha imagens JPG com nomes diferentes.
- A documentação de GitHub e testes não tinha evidências anexadas.
