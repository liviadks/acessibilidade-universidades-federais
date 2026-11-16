# Acessibilidade nos sites das universidades federais

Projeto de análise de dados que avalia a acessibilidade da página inicial de 27 universidades federais brasileiras (uma por estado e uma no Distrito Federal).

**Pergunta do projeto:** quão acessíveis são esses sites e quais erros mais se repetem?

- Dashboard interativo: https://datastudio.google.com/reporting/3e601cfb-b5fb-4b4c-958f-870da9666536
- Estudo de caso completo: em andamento

## Método

1. **Amostra:** página inicial oficial de uma universidade federal por estado, mais o DF (27 sites).
2. **Lighthouse (Chrome):** categoria Acessibilidade, modo Navegação, dispositivo Computador, em janela anônima. Registrei a nota (0 a 100) e os tipos de erro apontados em cada site.
3. **WAVE (WebAIM):** registrei o total de erros (Errors) e os erros de contraste (Contrast Errors).
4. **Análise:** planilha no Google Planilhas (contagem de erros, ranking e média por região) e dashboard no Looker Studio.
5. **Período dos testes:** outubro de 2026.

## Arquivos

- `acessibilidade-universidades-federais.csv`: dados coletados, uma linha por universidade.

## Limitações

- Foi testada apenas a página inicial, e os sites mudam com o tempo.
- Ferramentas automáticas detectam só parte dos problemas de acessibilidade. Itens que exigem verificação manual não entraram na nota.
- A amostra tem uma universidade por estado e não representa todas as federais. Cada região tem de 3 a 9 sites, então as comparações regionais são indicativas.
- A UFRN ficou sem o teste do WAVE porque o site estava fora do ar.

## Autoria

Lívia Derks
