# Cheat ou Legit? — acervo de análises de CS2

Site estático do canal **Cheat ou Legit?** ([@Aleson1551](https://www.youtube.com/@Aleson1551)).
Gerado a partir de análise tick a tick de demos de CS2.

## Como ler

- **NÍVEL** — counter-strafe de rifle contra a mediana de **19 profissionais tier-1** (87,8%),
  medida com o mesmo código aplicado nos dois lados.
- **INFORMAÇÃO** — fração de kills em que ninguém do time do atacante tinha visto a vítima
  **e** o time dela estava em silêncio. Cheaters confirmados ficaram em 16–22%; jogadores
  limpos, entre 0% e 5%.

## A regra de nome

Aparece com nick apenas quem foi **confirmado por revisão humana na demo** (com a frase do
revisor registrada junto) ou quem é jogador de alto nível. Quem o número apontou mas
**ninguém revisou** aparece anônimo.

A métrica tem **2,9% de falso positivo medido** — ela indica onde olhar, não quem é culpado.

Método e limites abertos: veja `docs/LIMITES-DO-DETECTOR.md` no repositório do projeto.
