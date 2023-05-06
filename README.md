Download Link: https://assignmentchef.com/product/solved-ece509-homework3-symmetric-matrices
<br>
<ol>

 <li>Given symmetric matrices <em>F</em><sub>0</sub><em>,F</em><sub>1</sub><em>,…,F<sub>n</sub></em>,cast the following optimization problem as an</li>

</ol>

SDP

min       (<em>Ax </em>+ <em>b</em>)<em><sup>T</sup>F</em>(<em>x</em>)<sup>−1</sup>(<em>Ax </em>+ <em>b</em>)

s.t.     <em>F</em>(<em>x</em>) ≻ 0

where <em>F</em>(<em>x</em>) = <em>F</em><sub>0 </sub>+ <em>x</em><sub>1</sub><em>F</em><sub>1 </sub>+ ··· + <em>x<sub>n</sub>F<sub>n</sub></em>

<ol start="2">

 <li>Given symmetric matrices W0 and W1, find the dual of the optimization min</li>

</ol>

min     <em>x<sup>T</sup>W</em><sub>0</sub><em>X</em>

s.t.      <em>x<sup>T</sup>W</em><sub>1</sub><em>x </em>≤ 1<em>.</em>

<ol start="3">

 <li>Use the duality idea to prove that the set is empty if the set</li>

</ol>

!<em>λ </em>| <em>λ</em>∈R<em><sup>m</sup></em><em>,λ</em>≥ 0<em>,A<sup>T</sup>λ </em>= 0<em>,b<sup>T</sup>λ &lt; </em>0″

is nonempty (where <em>A </em>∈R<em><sup>m</sup></em>×<em><sup>n</sup></em>).

<ol start="4">

 <li><em>Separating hyperplane between two polyhedra</em>: formulate the following problem as an</li>

</ol>

LP (feasibility) problem. Find a separating hyperplane that strictly separates two polyhedra

<em>P</em><sub>1 </sub>= {<em>x </em>| <em>Ax </em>≼ <em>b</em>}<em>,          P</em><sub>2 </sub>= {<em>x </em>| <em>Cx </em>≼ <em>d</em>}

then find a vector <em>a </em>∈R<em><sup>n </sup></em>and a scalar <em>γ </em>such that

<em>a<sup>T</sup>x &gt; γ </em>∀<em>x </em>∈ <em>P</em><sub>1</sub><em>,           a<sup>T</sup>x &lt; γ </em>∀<em>x </em>∈ <em>P</em><sub>2</sub>

Hence inf<em><sub>x</sub></em>∈<em>P</em><sub>2 </sub><em>a<sup>T</sup>x &gt; γ &gt; </em>sup<em><sub>x</sub></em>∈<em>P</em><sub>2 </sub><em>a<sup>T</sup>x </em>Use LP duality to simplify the infimum and supremum in these conditions.

1