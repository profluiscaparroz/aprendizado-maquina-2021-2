# Buscas informadas

São estratégias simples que tomam decisão com base nas informações que obtem ao caminho pelo espaço de busca. Essas informações servem de base para guiar a caminhada através das soluções.

Há diversas estratégias deesnvolvidas, no entando, podemos nos concentrar em três principais:   
*  Estratégia de busca gulosa/ambiciosa;   
*  Estratégia de busca uniforme ou de menor custo;   
*  Estratégia de busca A* (A estrela);

---

## Busca Gulosa

* É uma técnica parecida com a **busca em profundidade** e leva em conta sempre a melhor escolha localmente;   
* Em alguns caso, a busca gulosa pode obter a solução ótima, porém é menos comum de acontecer;   
* Contudo, para problemas dito difíceis, ela se torna atrativa, pois consegue obter soluções próximos do ótimo (subotimos);

### Características:
* As escolhas realizadas são definitivas;   
* Não leva em consideração as consequências de suas decisões;   
* Podem fazer cálculos repetitivos;   
* Nem sempre produz a melhor solução;   
* Quanto mais informações, maior a chance de produzir uma solução melhor.   

### Vantagens:
* Simples de implementar;
* Rápida execução (dependendo do tamanho do problema);
* Pode fornecer a melhor solução.  

### Desvantagem:
* Sem sempre produz soluções ótimas;
* Escolhe sempre o melhor sem considerar o todo;
* Pode entrar em loop infinito (se não tratar)
