# Equivaler

**Conversão de unidades, passo a passo** — ferramenta web (um único arquivo HTML) que resolve conversões por dois caminhos: **análise dimensional** (as unidades se cancelam) e **regra de três**, mostrando o raciocínio completo, não só o resultado.

Criado por **Prof. Me. Rodrigo Gonçalves (Prof Oswy)** · 📺 [youtube.com/@ProfOswy](https://www.youtube.com/@ProfOswy)

---

## Recursos

- **Dois métodos lado a lado**, cada um em 6 passos, com frases curtas explicando cada etapa — inclusive *por que* a unidade se corta.
- **Unidades compostas** (m³/s, kgf/cm², …) exibidas como fração de duas linhas.
- **Cancelamento animado** da unidade na análise dimensional.
- **Cálculo ao vivo** e botão para inverter as unidades (de ⇄ para).
- **Exportação em PDF** para gerar folhas de exercício.
- Números no formato brasileiro (vírgula decimal) e notação científica quando necessário.

## Grandezas e unidades

| Grandeza | Unidades |
|---|---|
| Comprimento | km, hm, dam, m, dm, cm, mm, pol, pé, mi |
| Área | km², ha, a, m², dm², cm², mm² |
| Volume | m³, hL, dm³, L, dL, cm³, mL |
| Massa | t, kg, g, mg |
| Força | MN, kN, N, kgf, tf |
| Pressão / Tensão | MPa, kPa, Pa, bar, atm, psi, kgf/cm², mca, mmca, mmHg |
| Vazão | m³/s, m³/min, m³/h, m³/dia, L/s, L/min, L/h, L/dia |

## Como usar

1. Abra o `index.html` no navegador.
2. Escolha a **grandeza**, digite o **valor** e selecione as unidades (**de** → **para**).
3. Acompanhe a resolução pelos dois métodos e, se quiser, clique em **Exportar PDF**.

## Executando / hospedando

- **Local:** basta abrir o `index.html` — não há instalação nem dependências, além das fontes IBM Plex Sans, IBM Plex Mono e Kalam, carregadas via Google Fonts.
- **GitHub Pages:** mantenha o arquivo principal como `index.html`, faça o commit e ative o Pages em *Settings → Pages* (branch `main`). O link ficará em `https://profoswy.github.io/equivaler/`.

## Observações

As relações usam as equivalências padrão do SI (por exemplo, `1 kgf = 9,80665 N` e `1 mca = 9806,65 Pa`, o que dá `1 kgf/cm² = 10 mca`). É uma ferramenta didática — confira sempre os valores com a norma aplicável ao seu projeto.

## Licença

Todos os direitos reservados — veja [LICENSE.md](LICENSE.md). Uso pessoal, acadêmico e educacional é permitido; redistribuição, modificação, remoção de créditos e uso comercial exigem autorização do autor.

© 2026 Prof. Me. Rodrigo Gonçalves (Prof Oswy)
