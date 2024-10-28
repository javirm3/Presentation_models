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


