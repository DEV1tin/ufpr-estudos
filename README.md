# UFPR Estudos — Portal Central (GitHub Pages)

Repositório centralizador de todos os guias de estudo, resoluções passo a passo e relatórios em HTML das disciplinas da UFPR.

- **URL do Portal:** [https://dev1tin.github.io/ufpr-estudos/](https://dev1tin.github.io/ufpr-estudos/)
- **Repositório:** [https://github.com/DEV1tin/ufpr-estudos](https://github.com/DEV1tin/ufpr-estudos)

---

## Estrutura da Árvore

```text
ufpr-estudos/
├── index.html                           # Homepage com botões das matérias
├── calculo-iii/                         # Cálculo III / IV (CM314)
│   ├── index.html
│   ├── p1-edos-1a-ordem/
│   ├── p2-lista-4-edos-2a-ordem/
│   ├── p2-lista-5-vibracoes-mecanicas/
│   ├── p2-lista-6-series/
│   ├── p2-simulado-revisao/
│   ├── p2-cola-a4/
│   └── geral-antigo/
├── analise-estrutural-iii/              # Análise Estrutural III (TC516)
│   ├── index.html
│   ├── guia-definitivo/
│   └── relatorio-trabalho-3/
├── estruturas-de-concreto/              # Estruturas de Concreto I e II
│   ├── index.html
│   ├── concreto-1-aproveitamento/       # Inclui 00. BeamsDiagrams/
│   └── concreto-2-p3-pilares/
└── saneamento-ambiental-ii/             # Saneamento Ambiental II (TH510)
    ├── index.html
    └── p2-tratamento-esgotos/           # Inclui img_slides/ e Folha_A4_Saneamento_II.pdf
```

## Como Adicionar um Novo Estudo HTML

1. Crie uma subpasta URL-friendly (sem espaços ou acentos) dentro da matéria correspondente em `00. Portal GitHub Pages (ufpr-estudos)/<materia>/<novo-projeto>/` com o arquivo principal chamado `index.html` (e eventuais assets relativos na mesma pasta).
2. Adicione o card/botão correspondente dentro de `<!-- PROJECTS_LIST -->` no `<materia>/index.html` (e atualize o contador de projetos no `index.html` raiz).
3. Faça `git add . && git commit -m "..." && git push` dentro de `00. Portal GitHub Pages (ufpr-estudos)/`.
