[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rbarbosarj/computacao-visual-ac/blob/main/Computacao_Visual_Final.ipynb)

# Atividade – Computação Visual

Este notebook apresenta as principais áreas da Computação Visual, combinando explicações curtas com exemplos práticos em código. O objetivo é mostrar, de forma clara e organizada, como cada área atua em problemas distintos: criação, transformação, interpretação e visualização de informações visuais.

---

## 1. Síntese de Imagens (Computação Gráfica)

A Computação Gráfica dedica-se à geração de imagens a partir de descrições matemáticas, considerando objetos, luzes e câmera. Aqui utilizamos um exemplo de *ray casting* para renderizar esferas com iluminação difusa, mostrando como a geometria e a rasterização convertem modelos vetoriais em imagens matriciais exibidas na tela.

```python
# Exemplo de ray casting com esferas
```

---

## 2. Processamento de Imagens

O Processamento de Imagens aplica técnicas sobre imagens já existentes, com foco em melhorar qualidade, destacar detalhes e facilitar análises posteriores. Como exemplo, foram aplicados filtros de suavização, equalização de histograma e detecção de bordas (Sobel), evidenciando como operações locais e convoluções transformam a percepção visual de uma cena.

```python
# Código de blur gaussiano, equalização e Sobel
```

---

## 3. Visão Computacional

A Visão Computacional busca interpretar o conteúdo da cena, extraindo informações de alto nível. Utilizamos dois exemplos clássicos: a detecção de cantos (Harris), útil em tarefas de calibração e reconstrução, e o *template matching* por correlação, que localiza padrões específicos em uma imagem. Esses métodos ilustram como a visão artificial aproxima máquinas da percepção humana.

```python
# Código Harris corners e template matching
```

---

## 4. Visualização Computacional

A Visualização Computacional transforma dados abstratos em representações gráficas intuitivas que auxiliam na análise. Para demonstrar, representamos a função sin(r)/r em duas formas: um mapa de calor e uma superfície 3D. Esses exemplos destacam como diferentes escolhas visuais podem revelar estruturas e comportamentos nos dados.

```python
# Código heatmap e superfície 3D
```

---

## Conclusão

Cada área da Computação Visual atua em um estágio distinto: a **Síntese** cria imagens, o **Processamento** melhora e transforma, a **Visão** interpreta e reconhece padrões, e a **Visualização** traduz dados em representações gráficas compreensíveis. Com exemplos simples e objetivos, este material demonstra os conceitos fundamentais de forma clara, unindo teoria e prática em um formato adequado para avaliação acadêmica e apresentação no GitHub.
