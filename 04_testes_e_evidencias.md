# Plano e registro de testes — EcoCiclo

## Testes executados em 09/11/2026 (Chromium headless via Playwright, servidor local)
| Teste | Resultado |
|---|---|
| As dez páginas abrem (HTTP 200) | OK |
| Links internos e imagens de todas as páginas | OK — nenhum link quebrado, todas as imagens carregam e têm `alt` |
| Rolagem horizontal indesejada (1366 px e 390 px) | Nenhuma |
| Erros no console do JavaScript | Nenhum |
| Formulário vazio | 5 mensagens de erro, borda destacada, foco no primeiro campo inválido (`formulario-erros.png`) |
| Rascunho no `localStorage` | Nome e e-mail digitados voltam após recarregar (`formulario-rascunho-localstorage.png`) |
| Formulário válido | Mensagem de sucesso, campos limpos, rascunho apagado (`formulario-sucesso.png`) |
| Tema escuro | Preferência mantida após recarregar |
| Teclado | Tab percorre link “Ir para o conteúdo”, logo e itens do menu; Esc fecha o menu no celular |
| Menu mobile (390 px) | Abre e fecha, `aria-expanded` atualizado (`menu-celular-aberto.png`) |
| Estrutura HTML (verificação própria) | Tags balanceadas, sem `id` duplicado, um `h1` por página, `lang="pt-BR"`, doctype |

Prints da Home: `evidencias/home-desktop.png` e `evidencias/home-celular.png`.

## Verificações de 16/11/2026
| Teste | Resultado |
|---|---|
| W3C Validator (vnu 26.11.14, site publicado, “apenas erros e avisos”) | Nenhum erro ou aviso em: início, projetos, impacto, acessibilidade, mídia, notícias, contato e orcamento_hospedagem (`evidencias/w3c-*.png`) |
| Players de áudio (Chromium headless, servidor local) | As 10 páginas carregam o MP3 correspondente sem erro (duração entre 24 s e 32 s) |
| Imagens, rolagem horizontal e console (1366 px e 390 px) | Nenhuma imagem quebrada, nenhuma rolagem horizontal, nenhum erro no console, nenhuma resposta HTTP 4xx |
| GitHub | 5 integrantes com commits (35, 16, 14, 14 e 6), 1 pull request mesclado e 1 problema fechado (`evidencias/github-*.png`) |
