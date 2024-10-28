---
theme : "simple"
highlightTheme: "darkula"
---

<link rel="stylesheet" href="css/quarto-revealjs-clean.css">

<section data-background-color="#107895">

## Theory of distributions

Jan Riopedre, Arnau Rojals and F. Javier Rodríguez

</section>

---

<section data-auto-animate data-transition-speed="fast" data-background-color="#107895">
   <h3> Fourier Transform</h3>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3> Fourier Transform</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
   <img src="images/image.png" style="width: 80%;" />
   </div>
   <div>720 x 1280 = 921600 coefficients</div>
</section>
<section data-auto-animate data-transition-speed="fast">
   <h3> Fourier Transform</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/image.png" style="width: 50%;" />
      <img src="images/color_channels_plot.png" style="width: 60%; margin-right: 25px;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=2</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot2.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image2.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=4</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot4.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image4.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=8</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot8.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image8.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=16</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot16.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image16.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=32</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot32.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image32.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=64</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot64.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image64.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=128</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot128.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image128.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=256</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot256.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image256.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=512</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot512.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image512.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=1024</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot1024.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image1024.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=2048</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot2048.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image2048.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=4096</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot4096.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image4096.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=8192</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot8192.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image8192.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=16384</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot16384.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image16384.png" style="width: 40%;" />
   </div>
</section>

<section data-auto-animate data-transition-speed="fast">
   <h3>n=32768</h3>
   <div style="display: flex; flex-wrap: wrap; gap: 5px; justify-content: center; align-items: center;">
      <img src="images/color_channels_plot.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/image.png" style="width: 40%;" />
      <img src="images/color_channels_plot32768.png" style="width: 50%; margin-right: 25px;" />
      <img src="images/recovered_image32768.png" style="width: 40%;" />
   </div>
</section>

---

## The action of a test function

---

<section data-auto-animate data-transition-speed="fast">

## Action of $f$ on a test function $\phi(x)$

$\langle f, \phi \rangle = \int_{-\infty}^{\infty} f(x) \phi(x) \, dx$

::: {.fragment}
Properties

- $\langle f, a\phi+b\psi\rangle = a\langle f, \phi\rangle + b \langle f, \psi\rangle$
  - if &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;$\phi_n(x)\to 0$
  - then $\langle f,\phi _n\rangle \to 0$
:::

</section>

---

<section data-auto-animate markdown-block>

## Distribution

</section>

<section data-auto-animate markdown-block>

## Distribution

<div style=" font-size: 0.8em;">

Motivation \
Definition\
Linearity and continuity  
The delta function  
Properties  
The derivative of a distribution  
</div>
</section>

<section data-auto-animate markdown-block>

## Distribution

<div style="display: flex; gap: 2em;">
<div style="text-align: left; font-size: 0.5em; width: 25%;">

**Motivation** \
Definition\
Linearity and continuity  
The delta function  
Properties  
The derivative of a distribution  
</div>
</div>
</section>

<section data-auto-animate markdown-block>

## Distribution

<div style="display: flex; gap: 2em;">
<div style="text-align: left; font-size: 0.5em; width: 50%;">

Motivation\
**Definition** \
Linearity and continuity  
The delta function  
Properties  
The derivative of a distribution  
</div>
<div style="text-align: left; font-size: 0.8em">

A **distribution** $( D )$ is a continuous linear map from the space of test functions to $( \mathbb{R} )$

$\mathcal{D} : \phi \mapsto \langle \mathcal{D}, \phi \rangle \in \mathbb{R}$
</div>
</div>
</section>

<section data-auto-animate markdown-block>

## Distribution

<div style="display: flex; gap: 2em;">
<div style="text-align: left; font-size: 0.5em; width: 25%;">
&nbsp;

Motivation\
Definition \
**Linearity and continuity**\
The delta function  
Properties  
The derivative of a distribution  
</div>
<div style="text-align: left; font-size: 0.8em">
&nbsp;

- $ \langle \mathcal{D}, a \varphi + b \psi \rangle = a \langle \mathcal{D}, \varphi \rangle + b \langle \mathcal{D}, \psi \rangle $

- if $ \varphi_n(x) \to 0 \quad \text{as} \quad n \to \infty, $  
  then $ \langle \mathcal{D}, \varphi_n \rangle \to 0 $

</div>
</div>
</section>

<section data-auto-animate markdown-block>

## Distribution

<div style="display: flex; gap: 2em;">
<div style="text-align: left; font-size: 0.5em; width: 25%;">
&nbsp;

Motivation\
Definition \
Linearity and continuity\
**The delta function** \
Properties  
The derivative of a distribution  
</div>
</div>
</section>

<section data-auto-animate markdown-block>

## Distribution

<div style="display: flex; gap: 2em;">
<div style="text-align: left; font-size: 0.5em; width: 25%;">
&nbsp;

Motivation\
Definition \
Linearity and continuity\
The delta function  
**Properties** \
The derivative of a distribution  
</div>
<div style="text-align: left; font-size: 0.8em">
&nbsp;

- $ \langle \mathcal{D} + \mathcal{E}, \phi \rangle = \langle \mathcal{D}, \phi \rangle + \langle \mathcal{E}, \phi \rangle $
- $ \langle a \mathcal{D}, \phi \rangle = a \langle \mathcal{D}, \phi \rangle $
- $ \langle \mathcal{D}(x - a), \phi(x) \rangle = \langle \mathcal{D}(x), \phi(x + a) \rangle $
- $ \langle \mathcal{D}(ax), \phi(x) \rangle = \frac{1}{|a|} \langle \mathcal{D}, \phi(x/a) \rangle $
- $ \langle \Phi(x) \mathcal{D}(x), \phi(x) \rangle = \langle \mathcal{D}(x), \Phi(x) \phi(x) \rangle $

</div>
</div>
</section>

<section data-auto-animate markdown-block>

## Distribution

<div style="display: flex; gap: 2em;">
<div style="text-align: left; font-size: 0.5em; width: 25%;">
&nbsp;

Motivation\
Definition \
Linearity and continuity\
The delta function  
Properties  
**The derivative of a distribution**
</div>
</div>
</section>

---

## Heat Equation Solution

<iframe src="https://javirm3.shinyapps.io/fourierheat/" width="100%" height="800"></iframe>
