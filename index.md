---
title       : 'Diseño de Experimentos'
subtitle    : 'Introducción'
author      : 'Carlos Neftaly Lozano A.'
job         : 'Microbiólogo Industrial y Ambiental, Msc'
logo     : EM.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
license: by-nc-sa
---

## 

<img src="./figure/In-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />
---

--- .class #id 

## Libros guía
<style>
  <slide class="{{ slide.class }}" id="{{ slide.id }}">
    <hgroup>
    {{{ slide.header }}}
  </hgroup>
    <article>
    <hr noshade size=4 color='red'>  
    {{{ slide.content }}}  
    <div class='left' style='float:left;width:48%'>
    {{{ slide.left.html }}}
    </div>    
      <div class='right' style='float:right;width:48%'>
      {{{ slide.right.html }}}
      </div>
        </article>
        </slide>
</style>
        
        
*** {name: left}
     
<img src="./figure/HG.jpg" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />
      
*** {name: right}
      
- **Análisis y Diseño de experimentos**
- Biblioteca UdeA: 658.5/G984
 
--- 

--- .class #id 


## Libros guía
<style>
  <slide class="{{ slide.class }}" id="{{ slide.id }}">
    <hgroup>
    {{{ slide.header }}}
  </hgroup>
    <article>
    <hr noshade size=4 color='red'>  
    {{{ slide.content }}}  
    <div class='left' style='float:left;width:48%'>
    {{{ slide.left.html }}}
    </div>    
      <div class='right' style='float:right;width:48%'>
      {{{ slide.right.html }}}
      </div>
        </article>
        </slide>
</style>
        
        
*** {name: left}
     
<img src="./figure/gote.jpg" title="plot of chunk unnamed-chunk-3" alt="plot of chunk unnamed-chunk-3" style="display: block; margin: auto;" />
      
*** {name: right}
      
+ __A Primer of Ecological Statistics__
+ Biblioteca UdeA: 574.5012/G683
      
--- 

--- .class #id 

## Libros guía
<style>
  <slide class="{{ slide.class }}" id="{{ slide.id }}">
    <hgroup>
    {{{ slide.header }}}
  </hgroup>
    <article>
    <hr noshade size=4 color='red'>  
    {{{ slide.content }}}  
    <div class='left' style='float:left;width:48%'>
    {{{ slide.left.html }}}
    </div>    
      <div class='right' style='float:right;width:48%'>
      {{{ slide.right.html }}}
      </div>
        </article>
        </slide>
</style>
        
        
*** {name: left}
     
<img src="./figure/EE.jpg" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" style="display: block; margin: auto;" />
      
*** {name: right}
      
+ __Experimental design and data analysis for biologists__
      
+ Biblioteca UdeA: 574.015195/Q7
      
--- 

--- .class #id 
## Evaluación

__3 Examenes parciales: 65%__
      
+ Examen 1: 20 %
+ Examen 2: 25%
+ Examen 3: 20
      
      Roses are <span style="color:red">red</span>, 
      violets are <span style="color:blue">blue</span>.
      
__Seguimiento: 35%__
      
+ Trabajo final: 15%
+ Asignacionaciones semanales: 15% 
+ Quices online: 5% 

---


## Asignaciones 

<span style="display:block; height: 2cm;"></span>

+ Semanales a partir de la segunda clase
+ Documento de _Word_: Máximo 4 páginas
+ Script R

<img src="./figure/policy.png" title="plot of chunk unnamed-chunk-5" alt="plot of chunk unnamed-chunk-5" style="display: block; margin: auto;" />


---
## Quices online
 
<span style="display:block; height: 2cm;"></span>

+ <span style="color:orange">Al menos 10 quices aleatorios online.</span>
+ Los das peores notas serán borradas

---

## EDMODO: Espacio oficial del curso 

<img src="./figure/edmodo.png" title="plot of chunk unnamed-chunk-6" alt="plot of chunk unnamed-chunk-6" style="display: block; margin: auto;" />

+ Toda información publicada es considerada oficial 
+ Cualquier contacto conmigo se hará vía mensaje edmodo
+ Dudas y preguntas también serán resueltas por esta plataforma

---

## El curso en resumen...

<span style="display:block; height: 2cm;"></span>

1. Repaso estadísica descriptiva

2. Introducción al Diseño de experimentos

3. Análisis de varianza

4. Métodos no-paramétricos

5. Regresión lineal 

<img src="./figure/nutshell.jpg" title="plot of chunk unnamed-chunk-7" alt="plot of chunk unnamed-chunk-7" style="display: block; margin: auto 0 auto auto;" />

---


## Software R 

El desarrollo del curso será asisitido por el uso del paquete estadístico <span style="color:blue">R</span> . 

<span style="display:block; height: 2cm;"></span>

<center><style="color:orange">https://www.r-project.org/</span></center>

<img src="./figure/Rlogo2.png" title="plot of chunk unnamed-chunk-8" alt="plot of chunk unnamed-chunk-8" style="display: block; margin: auto;" />

---

<img src="./figure/rpage.png" title="plot of chunk unnamed-chunk-9" alt="plot of chunk unnamed-chunk-9" style="display: block; margin: auto;" />

--- 

## Instalando R 

+ Windows:

<center><style="color:orange">https://www.icesi.edu.co/CRAN/bin/windows/base/</span></center>

+ Mac: 

<center><style="color:orange">https://www.icesi.edu.co/CRAN/</span></center>

---

## RStudio

Interfaz para manejo amigable de R. 

<span style="display:block; height: 2cm;"></span>

<center><style="color:orange">https://www.rstudio.com/products/rstudio/download/</span></center>



<img src="./figure/rstudio.png" title="plot of chunk unnamed-chunk-10" alt="plot of chunk unnamed-chunk-10" style="display: block; margin: auto;" />


