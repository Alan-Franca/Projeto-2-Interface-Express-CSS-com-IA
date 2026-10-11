# Holocron — Star Wars Fan Club

Landing page de um clube fictício de fãs de Star Wars, feita somente com **HTML5 e CSS3**, para o Projeto 2 — Interface Express.

- **Integrantes:** Alan França e Kauan Zaparoli.
- **Turma:** Front-end Web — 2026/2. Identificação provisória baseada na disciplina e no semestre do enunciado; substituir pelo código da turma, se necessário.
- **Tema:** explorar mundos, personagens e histórias de Star Wars.
- **Identidade:** preto `#080b10`, amarelo `#ffe052`, branco `#f5f5f0` e cinza `#9da5b4`. Gradientes e sombras usam transparências dessas quatro cores.

## Como abrir

1. Extraia o ZIP, se estiver usando a versão compactada.
2. Abra `index.html` em um navegador atualizado.
3. Mantenha a pasta `css` junto ao HTML.

Não precisa instalar nada. A página funciona sem internet, JavaScript, bibliotecas ou fontes externas. As ilustrações também são feitas em CSS.

## Arquivos

```text
projeto2_interface_express/
├── index.html
├── README.md
├── css/
│   └── estilo.css
```

## Estrutura e recursos

- `header` com nome, frase curta e três links internos.
- `main` com três `section`: apresentação, destaques e participação.
- Três `article` organizados com Grid; Flexbox no menu, nas ações e no rodapé.
- `footer` com integrantes, turma e identificação de atividade acadêmica.
- Todo o estilo em `css/estilo.css`, incluindo seletores de elemento, classes, IDs e hierárquicos, como `nav .menu a`.
- Uso de `width`, `max-width`, `margin`, `padding`, `border` e `border-radius`.
- Estados `:hover` e `:focus`, transições e transformações.
- Media queries ajustam a tipografia e reorganizam a página. Até 760px, os cards ficam em uma coluna.
- Link “Pular para o conteúdo”, rótulos nos campos, foco visível e respeito à preferência por reduzir movimento.

## Formulário demonstrativo

O HTML valida os campos obrigatórios. Depois do envio, o destino `#transmissao` ativa uma mensagem com o seletor CSS `:target`. Não há cadastro real, backend ou armazenamento na aplicação.

Os valores fictícios aparecem na URL por causa do método `GET`. Se a página for servida por um servidor, eles também fazem parte da requisição; por isso, use somente um codinome fictício. A confirmação representa apenas a demonstração do formulário.

## Três propriedades pesquisadas e testadas

As três foram mantidas. Os testes abaixo foram realizados pelo assistente no navegador, alterando os valores temporariamente e comparando as capturas. Não representam testes já realizados pelos integrantes.

| Propriedade | Elemento e finalidade | Valores comparados | Resultado e escolha |
| --- | --- | --- | --- |
| `box-shadow` | `.lamina`, brilho do sabre | `0 0 4px #ffe052` e `0 0 8px #ffe052, 0 0 24px rgba(255, 224, 82, 0.5)` | O primeiro brilho ficou estreito; as duas sombras deram mais profundidade. Mantida a segunda opção. |
| `outline-offset` | Elementos com `:focus`, afastar o contorno do conteúdo | `0px` e `5px` | `0px` encostou o foco na borda; `5px` criou uma separação mais clara. Mantido `5px`. |
| `text-shadow` | `.hiperespaco`, brilho do símbolo de infinito | `0 0 36px rgba(255, 224, 82, 0.7)` e `0 0 18px rgba(255, 224, 82, 0.35)` | A primeira sombra espalhou muito o brilho. A segunda ficou mais discreta e foi mantida. |

Referências consultadas: [box-shadow no MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow), [outline-offset no MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/outline-offset) e [text-shadow no MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow).

Para experimentar, altere um valor no CSS, salve e atualize o navegador. Cada integrante deve repetir os testes e registrar suas próprias observações, incluindo quais propriedades eram novas para ele.

## Diálogo utilizado com a IA

**Solicitação inicial do usuário:** “Faça uma página assim como o indicado neste documento, qualquer dúvida me pergunta para realizar a estruturação. Utilize somente HTML 5 e CSS 3”.

**Definições do usuário:** tema “Star Wars” e integrantes Alan França e Kauan Zaparoli.

O assistente leu o PDF, criou a estrutura semântica e o CSS, consultou as referências acima e testou a página. Os prompts exemplificados no PDF são sugestões de aprendizagem e não foram registrados aqui como mensagens efetivamente enviadas pelos integrantes.

## Verificação realizada

- Chrome: larguras de 1440, 1024, 768, 760, 390, 375 e 320 pixels, sem rolagem horizontal.
- Três links do menu e chamadas para ação com destinos internos.
- Navegação por teclado, link de salto e indicação de foco.
- Campos obrigatórios e confirmação demonstrativa do formulário.
- Três propriedades novas comparadas com valores diferentes.
- Capturas de computador e celular revisadas visualmente.
- Abertura direta do HTML, sem servidor e sem recursos externos.

## Para a apresentação

Leiam o HTML e os comentários do CSS. Expliquem a diferença entre Grid e Flexbox, como as media queries reorganizam os cards e como `:target` revela a confirmação. Personalizem o conteúdo e registrem as alterações feitas pelo grupo antes da entrega.

Projeto acadêmico de fãs, sem vínculo oficial com Lucasfilm ou Disney.
