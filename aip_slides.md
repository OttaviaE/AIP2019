---
title: "DscoreApp"
author: "Ottavia M. Epifania"
date: "12/7/2019"
output:
  ioslides_presentation:
    css: style.css
    runtime: shiny
  # slidy_presentation: default
logo: logo6.png
---



## The Implicit Association Test {.build}
<div id="test1", style="align="center;">
<center>
<h4>IAT structure</h4>
<table style="font-size:14pt; width=600px">
<tr>
<th> block</th>
<th> function </th>
<th> left response key </th>
<th> right response key </th>
</tr>
<tr>
<td>1</td>
<td>Practice</td>
<td>flowers</td>
<td>insects</td>
</tr>
<tr>
<td>2</td>
<td>Practice</td>
<td>good</td>
<td>bad</td>
</tr>
<tr>
<td style="background-color: #dffaff; color: black;rm">3</td>
<td style="background-color: #dffaff; color: black;">Associative practice</td>
<td style="background-color: #dffaff; color: black;">flowers & good</td>
<td style="background-color: #dffaff; color: black;">insects & bad </td>
</tr>
<tr>
<td style="background-color: #dffaff; color: black;">4</td>
<td style="background-color: #dffaff; color: black;">Associative test</td>
<td style="background-color: #dffaff; color: black;">flowers & good</td>
<td style="background-color: #dffaff; color: black;">insects & bad </td>
</tr>
<tr>
<td>5</td>
<td>Practice</td>
<td>insects</td>
<td>flowers</td>
</tr>
<tr>
<td style="background-color: #ffe3f5; color: black;">6</td>
<td style="background-color: #ffe3f5; color: black;">Associative practice</td>
<td style="background-color: #ffe3f5; color: black;">insects & good</td>
<td style="background-color: #ffe3f5; color: black;">flowers & bad</td>
</tr>
<tr>
<td style="background-color: #ffe3f5; color: black;">7</td>
<td style="background-color: #ffe3f5; color: black;">Associative test</td>
<td style="background-color: #ffe3f5; color: black;">insects & good</td>
<td style="background-color: #ffe3f5; color: black;">flowers & bad</td>
</tr>
</table>
</center>
</div>

## prova 

<div style="position: fixed;  bottom: 150px; right: 160px;">
<img src="~/GitHub/AIP2019/fg.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" width="35%" style="display: block; margin: auto 0 auto auto;" />
<!-- ![](~/GitHub/AIP2019/logo6.png) -->
</div>

## The D-score {.build}
<div style="position: fixed; top:230px;">
<h4> D-score core procedure </h4>
$D_{pratice} = \frac{M_{b6} - M_{b3}}{sd_{b6,b3}}$

$D_{test} = \frac{M_{b7} - M_{b4}}{sd_{b7,b4}}$

$D_{score} = \frac{D_{pratice} + D_{test}}{2}$
</div>

<div  style="position: fixed; bottom:140px;  left:525px;">
<h4> <em> D-score </em>algorithms </h4>
<h4>  </h4>
 <right>
                                 <table style="font-size:14pt;">
                                 <tr>
                                 <th>Dscore</th>
                                 <th>Error inflation</th>
                                 <th>Lower tail treatment</th>
                                 </tr>
                                 <tr>
                                 <td>D1</td>
                                 <td>Built-in correction</td>
                                 <td>No</td>
                                 </tr>
                                 <tr>
                                 <td>D2</td>
                                 <td>Built-in correction</td>
                                 <td>delete trials &lt; 400 ms</td>
                                 </tr>
                                 <tr>
                                 <td>D3</td>
                                 <td>Replace errors: mean (correct responses) + 2sd</td>
                                 <td>No</td>
                                 </tr>
                                 <tr>
                                 <td>D4</td>
                                 <td>Replace errors: mean (correct responses) + 600 ms</td>
                                 <td>No</td>
                                 </tr>
                                 <tr>
                                 <td>D5</td>
                                 <td>Replace errors: mean (correct responses) + 2sd</td>
                                 <td>delete trials &lt; 400 ms</td>
                                 </tr>
                                 <tr>
                                 <td>D6</td>
                                 <td>Replace errors: mean (correct responses) + 600 ms</td>
                                 <td>delete trials &lt; 400 ms</td>
                                 </tr>
                                 </table>
                                 </right>
</div>



## DscoreApp
<div style="position: fixed; left;">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img height="400px"  src="https://media.giphy.com/media/kDxMeAGxwSXZal8qLF/giphy.gif">
  </div>
</div>


