
class: center, middle

<img src="images/escience.png" width=350>

### Reproducibility in human neuroimaging research: a practical example from the analysis of diffusion MRI
## Ariel Rokem
### The University of Washington eScience Institute

<small>Follow along at: <a href="https://arokem.github.io/2017-01-27-repro-case-study/">https://arokem.github.io/2017-01-27-repro-case-study/</small>

---

layout: true

<div style="position: absolute; left: 650px; top: 370px;">
<image src="images/escience-network.png" width=500px style="opacity:0.4;filter:alpha(opacity=40);"> </div>

---

### White matter: the brain's super-highways

<div style="position: absolute; top: 150px; left: 20px;" >
  <image src="./images/optic-radiation-postmortem.png" style="background:none; border:none; box-shadow:none;" height="400">
</div>

--

<div style="position: absolute; top: 150px; left: 350px;" >
  <image src="./images/nerve-fiber.png" style="background:none; border:none; box-shadow:none;" height="400">
</div>


---

### Diffusion MRI

<video preload="auto" width="70%" height="auto" data-setup="{}" autoplay loop ><source src="./videos/dMRI-signal-movie.mp4"/></video>

---

### Tractography

<video preload="auto" width="60%" height="auto" data-setup="{}" autoplay loop ><source src="./videos/cc_tube_movie.mov"/> </video>


---

layout: true

---

## Models of the white matter

<div style="position: absolute; left: 500px; top: 650px;" >
  <small>Basser, Mattielo and Le Bihan (1994)</small>
</div>

--

<div style="position: absolute; left: 40px; top: 180px;">
<video width="40%" autoplay loop>
  <source src="./videos/tensor-signal-movie.mp4">
</video>
</div>

--

<div style="position: absolute; top: 260px; left: 320px;" >
  <image src="./images/q-form.png" style="background:none; border:none; box-shadow:none;" height="70">
</div>

--

<div style="position: absolute; top: 200px; left: 630px;">
<video width="70%" autoplay loop>
<source src="./videos/tensor-ellipse-movie.mp4">
</video>
</div>

--

style: middle, center

#### Diffusion Tensor Model

---

layout: true

<div style="position: absolute; left: 650px; top: 370px;">
<image src="images/escience-network.png" width=500px style="opacity:0.4;filter:alpha(opacity=40);"> </div>

---
layout: center, middle

# Which model should we use?

---

## Model selection with cross-validation


<div style="position: absolute; left: 500px; top: 650px;" >
  <a href="http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0123272"><small>Rokem et al. (2015)</a></small>
</div>

<image src="images/rokem2015-fig6.png" height="25%">

---

layout: true

---

<div style="position: absolute; top: 10px; left: 20px;" >
  <image src="./images/arokem.png" style="background:none; border:none; box-shadow:none;" height="600">
</div>

---

# Neuroimaging in Python

--

<div style="position: absolute; left: 100px; top: 130px;">
<a href="http://dipy.org"><image src="images/dipy-logo.png"  height="8%"></a>
</div>

--

<div style="position: absolute; top: 250px; left: 20px;" >
  <image src="./images/dipy_example_xval.png" style="background:none; border:none; box-shadow:none;" height="400">
</div>

---

<div style="position: absolute; top: 10px; left: 20px;" >
  <image src="./images/arokem.png" style="background:none; border:none; box-shadow:none;" height="600">
</div>

---

### Cloud computing enables reproducibility

<image src="images/AWS.png" height="25%">

<image src="images/spark-logo-trademark.png" height="200px">


[K-fold cross-validation on 900 brains](https://github.com/arokem/dki-accuracy-reliability)

---
class: center
layout: false

### Stay in touch!

<div style="position:absolute; left: 220px; top:100px;">
  <img src="images/globe-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">http://arokem.org
  </div>
</div>
<div style="position:absolute; left: 220px; top:220px;">
  <img src="images/email-11-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">arokem@gmail.com
  </div>
</div>
<div style="position:absolute; left: 220px; top:340px;">
  <img src="images/twitter-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">@arokem
  </div>
</div>
<div style="position:absolute; left: 220px; top:460px;">
  <img src="images/github-6-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">github.com/arokem
  </div>
</div>
