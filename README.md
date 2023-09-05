<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML' async></script>

# CARGAS NA LAJE

A carga nesta laje será dividida bla bla bla $f(x,y) = \sin(x+y)$

* Impermebabilizção  
* Item 2
* Item 3

$$
   f(x,y) = \sin(x+y)
$$
<h2>1. Levantamento dos elementos na laje</h2>  

<p aligin = "justify">
  Para a determionação das ações atuantes na estrutura, mostra-se necessário consultar os procedimentos apresentados na ABNT NBR 6120. Logo, deve-se fazer um levantamento dos elementos presentes na laje, de forma a obter sua carga total na estrutura. Desta forma, para o presente projeto exemplo, tem-se a presença de contrapiso, impermeabilizante, proteção e o peso devido a própria laje, logo consultando-se a norma citada, tem-se que:
</p>

<p>
  \[\gamma_{cp} = 19 \, \text{kN/m³}\]

  \[\gamma_{prot} = 19 \, \text{kN/m³}\]
  
  \[\gamma_{Laje} = 25 \, \text{kN/m³}\]
</p>


<p aligin = "justify">
  Já para o impermeabilizante, tem-se que a carga em kN/m² para a espessura de 0,3 cm é de:
</p>

<p>
  \[\gamma_{imp} = 0,08 \, \text{kN/m²}\]
</p>

<h2>2. Cálculo da carga permanente e variável da laje</h2>  

<p aligin = "justify">
  Em seguida, pode-se calcular a carga superficial devido a cada elemento, considerando-se a espessura que cada um representa na estrutura por meio da equação <a href="#eq1">(1)</a>, que representa a parcela de carga permanente \(g\).
</p>

<table>
  <tr>
    <td align = "left">\[G_{x} = \gamma_{x} \cdot e_{x}\]</td>
    <td><p align = "right" id = "eq1">(1)</p></td>
  </tr>
</table>

<p aligin = "justify">
  Portanto, aplicando-se a equação <a href="#eq1">(1)</a> e aplicando as respectivas espessuras, tem-se que:
</p>

<table>
  <thead align="center">
    <tr>
      <th>Elemento</th>
      <th>\(e \, (cm)\)</th>
      <th>\(\gamma \, (kN/m³)\)</th>
      <th>\(G \, (kN/m²)\)</th>
    </tr>
  </thead>
  <tbody align="center">
    <tr>
      <td>Contrapiso</td>
      <td>0,5</td>
      <td>19</td>
      <td>0,095</td>
    </tr>
    <tr>
      <td>impermeabilizante</td>
      <td>0,3</td>
      <td>-</td>
      <td>0,08</td>
    </tr>
    <tr>
      <td>Proteção</td>
      <td>2,5</td>
      <td>19</td>
      <td>0,475</td>
    </tr>
    <tr>
      <td>Laje</td>
      <td>10</td>
      <td>25</td>
      <td>2,5</td>
    </tr>
    <tr>
      <td><b>Total (g)</b></td>
      <td><b>-</b></td>
      <td><b>-</b></td>
      <td><b>3,15</b></td>
    </tr>
  </tbody>
  </table>

<p aligin = "justify">
  Já para a parcela de carga variável na laje, foi adotada a carga dada para uma cobertura, logo:
</p>

<p>
  \[q = 1,5 \, \text{kN/m²}\]
</p>

<h2>3. Determinação das áreas de influência das lajes</h2>  

<p aligin = "justify">
  Nesta etapa, define-se as áreas de influência da laje, visto que o carregamento atuante é transferido para as vigas. Logo, com o auxílio do AutoCAD, pode-se obter as seguintes áreas de influência:
<br>
<img src="https://i.imgur.com/k5k475q.png" alt="A1">
<br>
<img src="https://i.imgur.com/oglZZfH.png" alt="A2 e A3">
</p>

<p>
  \[A1 = 54509,62 \, \text{cm²}\]
  \[A2 = 16875,00 \, \text{cm²}\]
  \[A3 = 16875,00 \, \text{cm²}\]
</p>
