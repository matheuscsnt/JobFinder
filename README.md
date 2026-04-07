# Job Finder 🎯

Um "terminal" minimalista e eficiente para injetar parâmetros de busca avançada e encontrar vagas no LinkedIn com precisão cirúrgica. 

O LinkedIn muitas vezes mistura níveis de experiência ou exibe vagas antigas por padrão. Esta ferramenta resolve isso aplicando operadores booleanos automáticos e forçando filtros de ordenação, poupando tempo na hora da prospecção.

## Funcionalidades

* **Filtro Booleano de Senioridade:** Se você busca vagas de "Pleno", a ferramenta automaticamente injeta operadores (`NOT Estágio NOT Junior NOT Senior`) na URL para limpar os resultados.
* **Ordenação Otimizada:** Força o LinkedIn a mostrar sempre os resultados "Mais recentes" (`sortBy=DD`), ignorando a relevância padrão para você não perder vagas que acabaram de abrir.
* **Localização Dinâmica (UI/UX Inteligente):** O campo de localização só é exibido se a modalidade escolhida for "Presencial" ou "Híbrido". Para vagas remotas, a interface se mantém limpa.
* **Design "Developer Tool":** Interface inspirada em terminais de comando (Dark Mode, tipografia Monospace e acentos em verde neon), focada 100% em produtividade.

## Tecnologias Utilizadas

O projeto foi construído para ser leve, rápido e sem dependências complexas (Production-Ready via CDN):
* **HTML5 & Vanilla JavaScript:** Toda a lógica de formatação de strings e manipulação da URL roda nativamente no navegador.
* **Tailwind CSS:** Estilização utilitária aplicada via CDN para garantir um visual moderno e responsivo sem a necessidade de arquivos CSS separados.
* **SVG Inline:** Favicon gerado puramente em código, dispensando o carregamento de imagens externas.

## Como usar

### Acesso Rápido (Online)
A ferramenta está hospedada e pronta para uso via GitHub Pages:
🔗 **[Acessar o Job Finder][https://buscajob.vercel.app/]**

### Rodando Localmente
Como é um projeto 100% Client-Side, você não precisa de nenhum servidor.
1. Clone este repositório ou faça o download do arquivo `index.html`.
2. Dê um duplo clique no arquivo `index.html` para abri-lo em qualquer navegador web.

## Exemplos de Uso

Ideal para filtrar oportunidades específicas. Por exemplo, se você está buscando atuar com inteligência artificial:
1. **Cargo:** `Machine Learning`
2. **Senioridade:** `Pleno`
3. **Modalidade:** `Híbrido`
4. **Localização:** `Salvador, BA`
5. **Período:** `Última Semana`

A ferramenta processará esses inputs e abrirá uma nova guia já com todos os filtros aplicados corretamente no LinkedIn.

Fiquem a vontade para colaborar com o desenvolvimento.

---
*Construído para otimizar a busca por oportunidades e limpar o ruído dos algoritmos de recomendação.*