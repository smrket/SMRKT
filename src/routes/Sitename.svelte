<script>
    import logo from '$lib/images/smr.png';
</script>

<div id="loading"><img style="max-width: 50px;position:absolute;left:1;padding:5px" src={logo} alt="SMRKT" />
  <div class="waviy">
    
<span style="--i:1">S</span>
<span style="--i:2">m</span>
<span style="--i:3">r</span>
<span style="--i:4">t</span>
<span style="--i:5">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
<span style="--i:6">m</span>
<span style="--i:7">r</span>
<span style="--i:8">k</span>
<span style="--i:9">t</span>
  </div>
</div>


<style>
@import url('https://fonts.googleapis.com/css2?family=Russo+One&display=swap');

#loading {
  /* background-color: #1f1f2b; */
  display: flex;
  justify-content: center;
  align-items: center;
  
  border-bottom: 5px solid #c3d214;
  min-height: 50px;
  }

.waviy {
  position: relative;

  font-weight: bold;
  letter-spacing: 2.5px;
  /* line-height: 50px; */
}

.waviy span {
  position: relative;
  display: inline-block;
  font-size: 25px;

  font-family: 'Russo One', sans-serif;
  color: #c3d214;
  text-transform: uppercase;
  animation: flip 3s infinite;
  animation-delay: calc(.2s * var(--i))
}
@keyframes flip {
  0%,80% {
    transform: rotateY(360deg) 
  }
}
</style>