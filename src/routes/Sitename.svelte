<script>
    import logo from '$lib/images/001.png';
</script>

<div id="loading"><img style="max-width: 50px;position:absolute;left:0;padding:5px;" src={logo} alt="SMRKT" />
  <div class="waviy">
    
<span style="--i:1">S</span>
<span style="--i:2">m</span>
<span style="--i:3">r</span>
<span style="--i:4">t</span>
<span style="--i:5">&nbsp;&nbsp;&nbsp;</span>
<span style="--i:6">m</span>
<span style="--i:7">r</span>
<span style="--i:8">k</span>
<span style="--i:9">t</span>
  </div>
</div>


<style>

#loading {
  background-color: green;
  display: flex;
  justify-content: center;
  align-items: center;
  border: 2px solid black;
  }

.waviy {
  position: relative;
  font-family:   system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight: bold;
  letter-spacing: 2.5px;
  line-height: 50px;
}

.waviy span {
  position: relative;
  display: inline-block;
  font-size: 33px;
  color: lightyellow;
  text-transform: uppercase;
  animation: flip 4s infinite;
  animation-delay: calc(.2s * var(--i))
}
@keyframes flip {
  0%,80% {
    transform: rotateY(360deg) 
  }
}
</style>