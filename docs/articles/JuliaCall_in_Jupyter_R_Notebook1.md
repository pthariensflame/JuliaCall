

```R
library(JuliaCall)
```


```R
julia_setup()
```

    Julia at location /Applications/Julia-0.6.app/Contents/Resources/julia/bin will be used.
    Julia version 0.6.0 found.
    Julia initiation...
    Finish Julia initiation.
    Loading setup script for JuliaCall...
    Finish loading setup script for JuliaCall.



```R
julia_console()
```

    It seems that you are not in the terminal. A simple julia console will be started.
    Press ESC or CTRL+C to exit.


    julia> sqrt(2)



1.4142135623730951


    julia> @doc sqrt



<div class="markdown"><pre><code>sqrt&#40;x&#41;</code></pre>
<p>Return &#36;\sqrt&#123;x&#125;&#36;. Throws <a href="@ref"><code>DomainError</code></a> for negative <a href="@ref"><code>Real</code></a> arguments. Use complex negative arguments instead. The prefix operator <code>√</code> is equivalent to <code>sqrt</code>.</p>

</div>


    julia> exit


    Exiting julia console.



```R
julia_library("Gadfly")
```


```R
julia_command("Gadfly.plot(y = [1 2 3])")
```


<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg"
     xmlns:xlink="http://www.w3.org/1999/xlink"
     xmlns:gadfly="http://www.gadflyjl.org/ns"
     version="1.2"
     width="141.42mm" height="100mm" viewBox="0 0 141.42 100"
     stroke="none"
     fill="#000000"
     stroke-width="0.3"
     font-size="3.88"

     id="img-a09943b4">
<g class="plotroot xscalable yscalable" id="img-a09943b4-1">
  <g class="guide xlabels" font-size="2.82" font-family="'PT Sans Caption','Helvetica Neue','Helvetica',sans-serif" fill="#6C606B" id="img-a09943b4-2">
    <text x="-125.67" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="hidden">-1.5</text>
    <text x="-96.77" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="hidden">-1.0</text>
    <text x="-67.87" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="hidden">-0.5</text>
    <text x="-38.97" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="hidden">0.0</text>
    <text x="-10.07" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="hidden">0.5</text>
    <text x="18.83" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="visible">1.0</text>
    <text x="47.72" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="visible">1.5</text>
    <text x="76.62" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="visible">2.0</text>
    <text x="105.52" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="visible">2.5</text>
    <text x="134.42" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="visible">3.0</text>
    <text x="163.32" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="hidden">3.5</text>
    <text x="192.22" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="hidden">4.0</text>
    <text x="221.12" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="hidden">4.5</text>
    <text x="250.02" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="hidden">5.0</text>
    <text x="278.92" y="94" text-anchor="middle" gadfly:scale="1.0" visibility="hidden">5.5</text>
    <text x="-96.77" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">-1.0</text>
    <text x="-90.99" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">-0.9</text>
    <text x="-85.21" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">-0.8</text>
    <text x="-79.43" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">-0.7</text>
    <text x="-73.65" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">-0.6</text>
    <text x="-67.87" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">-0.5</text>
    <text x="-62.09" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">-0.4</text>
    <text x="-56.31" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">-0.3</text>
    <text x="-50.53" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">-0.2</text>
    <text x="-44.75" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">-0.1</text>
    <text x="-38.97" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">0.0</text>
    <text x="-33.19" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">0.1</text>
    <text x="-27.41" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">0.2</text>
    <text x="-21.63" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">0.3</text>
    <text x="-15.85" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">0.4</text>
    <text x="-10.07" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">0.5</text>
    <text x="-4.29" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">0.6</text>
    <text x="1.49" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">0.7</text>
    <text x="7.27" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">0.8</text>
    <text x="13.05" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">0.9</text>
    <text x="18.83" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">1.0</text>
    <text x="24.61" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">1.1</text>
    <text x="30.39" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">1.2</text>
    <text x="36.17" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">1.3</text>
    <text x="41.94" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">1.4</text>
    <text x="47.72" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">1.5</text>
    <text x="53.5" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">1.6</text>
    <text x="59.28" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">1.7</text>
    <text x="65.06" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">1.8</text>
    <text x="70.84" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">1.9</text>
    <text x="76.62" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">2.0</text>
    <text x="82.4" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">2.1</text>
    <text x="88.18" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">2.2</text>
    <text x="93.96" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">2.3</text>
    <text x="99.74" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">2.4</text>
    <text x="105.52" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">2.5</text>
    <text x="111.3" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">2.6</text>
    <text x="117.08" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">2.7</text>
    <text x="122.86" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">2.8</text>
    <text x="128.64" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">2.9</text>
    <text x="134.42" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">3.0</text>
    <text x="140.2" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">3.1</text>
    <text x="145.98" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">3.2</text>
    <text x="151.76" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">3.3</text>
    <text x="157.54" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">3.4</text>
    <text x="163.32" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">3.5</text>
    <text x="169.1" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">3.6</text>
    <text x="174.88" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">3.7</text>
    <text x="180.66" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">3.8</text>
    <text x="186.44" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">3.9</text>
    <text x="192.22" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">4.0</text>
    <text x="198" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">4.1</text>
    <text x="203.78" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">4.2</text>
    <text x="209.56" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">4.3</text>
    <text x="215.34" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">4.4</text>
    <text x="221.12" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">4.5</text>
    <text x="226.9" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">4.6</text>
    <text x="232.68" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">4.7</text>
    <text x="238.46" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">4.8</text>
    <text x="244.24" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">4.9</text>
    <text x="250.02" y="94" text-anchor="middle" gadfly:scale="10.0" visibility="hidden">5.0</text>
    <text x="-154.57" y="94" text-anchor="middle" gadfly:scale="0.5" visibility="hidden">-2</text>
    <text x="-38.97" y="94" text-anchor="middle" gadfly:scale="0.5" visibility="hidden">0</text>
    <text x="76.62" y="94" text-anchor="middle" gadfly:scale="0.5" visibility="hidden">2</text>
    <text x="192.22" y="94" text-anchor="middle" gadfly:scale="0.5" visibility="hidden">4</text>
    <text x="307.81" y="94" text-anchor="middle" gadfly:scale="0.5" visibility="hidden">6</text>
    <text x="-96.77" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">-1.0</text>
    <text x="-85.21" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">-0.8</text>
    <text x="-73.65" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">-0.6</text>
    <text x="-62.09" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">-0.4</text>
    <text x="-50.53" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">-0.2</text>
    <text x="-38.97" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">0.0</text>
    <text x="-27.41" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">0.2</text>
    <text x="-15.85" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">0.4</text>
    <text x="-4.29" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">0.6</text>
    <text x="7.27" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">0.8</text>
    <text x="18.83" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">1.0</text>
    <text x="30.39" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">1.2</text>
    <text x="41.94" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">1.4</text>
    <text x="53.5" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">1.6</text>
    <text x="65.06" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">1.8</text>
    <text x="76.62" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">2.0</text>
    <text x="88.18" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">2.2</text>
    <text x="99.74" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">2.4</text>
    <text x="111.3" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">2.6</text>
    <text x="122.86" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">2.8</text>
    <text x="134.42" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">3.0</text>
    <text x="145.98" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">3.2</text>
    <text x="157.54" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">3.4</text>
    <text x="169.1" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">3.6</text>
    <text x="180.66" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">3.8</text>
    <text x="192.22" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">4.0</text>
    <text x="203.78" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">4.2</text>
    <text x="215.34" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">4.4</text>
    <text x="226.9" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">4.6</text>
    <text x="238.46" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">4.8</text>
    <text x="250.02" y="94" text-anchor="middle" gadfly:scale="5.0" visibility="hidden">5.0</text>
  </g>
<g clip-path="url(#img-a09943b4-3)">
  <g id="img-a09943b4-4">
    <g pointer-events="visible" opacity="1" fill="#000000" fill-opacity="0.000" stroke="#000000" stroke-opacity="0.000" class="guide background" id="img-a09943b4-5">
      <rect x="16.83" y="5" width="119.6" height="85.33"/>
    </g>
    <g class="guide ygridlines xfixed" stroke-dasharray="0.5,0.5" stroke-width="0.2" stroke="#D0D0E0" id="img-a09943b4-6">
      <path fill="none" d="M16.83,189.98 L 136.42 189.98" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M16.83,169.65 L 136.42 169.65" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M16.83,149.32 L 136.42 149.32" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M16.83,128.99 L 136.42 128.99" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M16.83,108.66 L 136.42 108.66" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M16.83,88.33 L 136.42 88.33" gadfly:scale="1.0" visibility="visible"/>
      <path fill="none" d="M16.83,68 L 136.42 68" gadfly:scale="1.0" visibility="visible"/>
      <path fill="none" d="M16.83,47.66 L 136.42 47.66" gadfly:scale="1.0" visibility="visible"/>
      <path fill="none" d="M16.83,27.33 L 136.42 27.33" gadfly:scale="1.0" visibility="visible"/>
      <path fill="none" d="M16.83,7 L 136.42 7" gadfly:scale="1.0" visibility="visible"/>
      <path fill="none" d="M16.83,-13.33 L 136.42 -13.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-33.66 L 136.42 -33.66" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-54 L 136.42 -54" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-74.33 L 136.42 -74.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-94.66 L 136.42 -94.66" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M16.83,169.65 L 136.42 169.65" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,165.59 L 136.42 165.59" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,161.52 L 136.42 161.52" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,157.45 L 136.42 157.45" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,153.39 L 136.42 153.39" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,149.32 L 136.42 149.32" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,145.26 L 136.42 145.26" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,141.19 L 136.42 141.19" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,137.12 L 136.42 137.12" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,133.06 L 136.42 133.06" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,128.99 L 136.42 128.99" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,124.92 L 136.42 124.92" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,120.86 L 136.42 120.86" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,116.79 L 136.42 116.79" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,112.72 L 136.42 112.72" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,108.66 L 136.42 108.66" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,104.59 L 136.42 104.59" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,100.53 L 136.42 100.53" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,96.46 L 136.42 96.46" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,92.39 L 136.42 92.39" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,88.33 L 136.42 88.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,84.26 L 136.42 84.26" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,80.19 L 136.42 80.19" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,76.13 L 136.42 76.13" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,72.06 L 136.42 72.06" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,68 L 136.42 68" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,63.93 L 136.42 63.93" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,59.86 L 136.42 59.86" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,55.8 L 136.42 55.8" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,51.73 L 136.42 51.73" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,47.66 L 136.42 47.66" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,43.6 L 136.42 43.6" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,39.53 L 136.42 39.53" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,35.46 L 136.42 35.46" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,31.4 L 136.42 31.4" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,27.33 L 136.42 27.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,23.27 L 136.42 23.27" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,19.2 L 136.42 19.2" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,15.13 L 136.42 15.13" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,11.07 L 136.42 11.07" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,7 L 136.42 7" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,2.93 L 136.42 2.93" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-1.13 L 136.42 -1.13" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-5.2 L 136.42 -5.2" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-9.27 L 136.42 -9.27" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-13.33 L 136.42 -13.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-17.4 L 136.42 -17.4" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-21.46 L 136.42 -21.46" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-25.53 L 136.42 -25.53" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-29.6 L 136.42 -29.6" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-33.66 L 136.42 -33.66" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-37.73 L 136.42 -37.73" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-41.8 L 136.42 -41.8" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-45.86 L 136.42 -45.86" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-49.93 L 136.42 -49.93" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-54 L 136.42 -54" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-58.06 L 136.42 -58.06" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-62.13 L 136.42 -62.13" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-66.19 L 136.42 -66.19" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-70.26 L 136.42 -70.26" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-74.33 L 136.42 -74.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M16.83,210.32 L 136.42 210.32" gadfly:scale="0.5" visibility="hidden"/>
      <path fill="none" d="M16.83,128.99 L 136.42 128.99" gadfly:scale="0.5" visibility="hidden"/>
      <path fill="none" d="M16.83,47.66 L 136.42 47.66" gadfly:scale="0.5" visibility="hidden"/>
      <path fill="none" d="M16.83,-33.66 L 136.42 -33.66" gadfly:scale="0.5" visibility="hidden"/>
      <path fill="none" d="M16.83,-114.99 L 136.42 -114.99" gadfly:scale="0.5" visibility="hidden"/>
      <path fill="none" d="M16.83,169.65 L 136.42 169.65" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,161.52 L 136.42 161.52" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,153.39 L 136.42 153.39" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,145.26 L 136.42 145.26" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,137.12 L 136.42 137.12" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,128.99 L 136.42 128.99" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,120.86 L 136.42 120.86" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,112.72 L 136.42 112.72" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,104.59 L 136.42 104.59" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,96.46 L 136.42 96.46" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,88.33 L 136.42 88.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,80.19 L 136.42 80.19" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,72.06 L 136.42 72.06" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,63.93 L 136.42 63.93" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,55.8 L 136.42 55.8" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,47.66 L 136.42 47.66" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,39.53 L 136.42 39.53" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,31.4 L 136.42 31.4" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,23.27 L 136.42 23.27" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,15.13 L 136.42 15.13" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,7 L 136.42 7" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-1.13 L 136.42 -1.13" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-9.27 L 136.42 -9.27" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-17.4 L 136.42 -17.4" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-25.53 L 136.42 -25.53" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-33.66 L 136.42 -33.66" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-41.8 L 136.42 -41.8" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-49.93 L 136.42 -49.93" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-58.06 L 136.42 -58.06" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-66.19 L 136.42 -66.19" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M16.83,-74.33 L 136.42 -74.33" gadfly:scale="5.0" visibility="hidden"/>
    </g>
    <g class="guide xgridlines yfixed" stroke-dasharray="0.5,0.5" stroke-width="0.2" stroke="#D0D0E0" id="img-a09943b4-7">
      <path fill="none" d="M-125.67,5 L -125.67 90.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M-96.77,5 L -96.77 90.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M-67.87,5 L -67.87 90.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M-38.97,5 L -38.97 90.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M-10.07,5 L -10.07 90.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M18.83,5 L 18.83 90.33" gadfly:scale="1.0" visibility="visible"/>
      <path fill="none" d="M47.72,5 L 47.72 90.33" gadfly:scale="1.0" visibility="visible"/>
      <path fill="none" d="M76.62,5 L 76.62 90.33" gadfly:scale="1.0" visibility="visible"/>
      <path fill="none" d="M105.52,5 L 105.52 90.33" gadfly:scale="1.0" visibility="visible"/>
      <path fill="none" d="M134.42,5 L 134.42 90.33" gadfly:scale="1.0" visibility="visible"/>
      <path fill="none" d="M163.32,5 L 163.32 90.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M192.22,5 L 192.22 90.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M221.12,5 L 221.12 90.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M250.02,5 L 250.02 90.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M278.92,5 L 278.92 90.33" gadfly:scale="1.0" visibility="hidden"/>
      <path fill="none" d="M-96.77,5 L -96.77 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-90.99,5 L -90.99 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-85.21,5 L -85.21 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-79.43,5 L -79.43 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-73.65,5 L -73.65 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-67.87,5 L -67.87 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-62.09,5 L -62.09 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-56.31,5 L -56.31 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-50.53,5 L -50.53 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-44.75,5 L -44.75 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-38.97,5 L -38.97 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-33.19,5 L -33.19 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-27.41,5 L -27.41 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-21.63,5 L -21.63 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-15.85,5 L -15.85 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-10.07,5 L -10.07 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-4.29,5 L -4.29 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M1.49,5 L 1.49 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M7.27,5 L 7.27 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M13.05,5 L 13.05 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M18.83,5 L 18.83 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M24.61,5 L 24.61 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M30.39,5 L 30.39 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M36.17,5 L 36.17 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M41.94,5 L 41.94 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M47.72,5 L 47.72 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M53.5,5 L 53.5 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M59.28,5 L 59.28 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M65.06,5 L 65.06 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M70.84,5 L 70.84 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M76.62,5 L 76.62 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M82.4,5 L 82.4 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M88.18,5 L 88.18 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M93.96,5 L 93.96 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M99.74,5 L 99.74 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M105.52,5 L 105.52 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M111.3,5 L 111.3 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M117.08,5 L 117.08 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M122.86,5 L 122.86 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M128.64,5 L 128.64 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M134.42,5 L 134.42 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M140.2,5 L 140.2 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M145.98,5 L 145.98 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M151.76,5 L 151.76 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M157.54,5 L 157.54 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M163.32,5 L 163.32 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M169.1,5 L 169.1 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M174.88,5 L 174.88 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M180.66,5 L 180.66 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M186.44,5 L 186.44 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M192.22,5 L 192.22 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M198,5 L 198 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M203.78,5 L 203.78 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M209.56,5 L 209.56 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M215.34,5 L 215.34 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M221.12,5 L 221.12 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M226.9,5 L 226.9 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M232.68,5 L 232.68 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M238.46,5 L 238.46 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M244.24,5 L 244.24 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M250.02,5 L 250.02 90.33" gadfly:scale="10.0" visibility="hidden"/>
      <path fill="none" d="M-154.57,5 L -154.57 90.33" gadfly:scale="0.5" visibility="hidden"/>
      <path fill="none" d="M-38.97,5 L -38.97 90.33" gadfly:scale="0.5" visibility="hidden"/>
      <path fill="none" d="M76.62,5 L 76.62 90.33" gadfly:scale="0.5" visibility="hidden"/>
      <path fill="none" d="M192.22,5 L 192.22 90.33" gadfly:scale="0.5" visibility="hidden"/>
      <path fill="none" d="M307.81,5 L 307.81 90.33" gadfly:scale="0.5" visibility="hidden"/>
      <path fill="none" d="M-96.77,5 L -96.77 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M-85.21,5 L -85.21 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M-73.65,5 L -73.65 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M-62.09,5 L -62.09 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M-50.53,5 L -50.53 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M-38.97,5 L -38.97 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M-27.41,5 L -27.41 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M-15.85,5 L -15.85 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M-4.29,5 L -4.29 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M7.27,5 L 7.27 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M18.83,5 L 18.83 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M30.39,5 L 30.39 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M41.94,5 L 41.94 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M53.5,5 L 53.5 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M65.06,5 L 65.06 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M76.62,5 L 76.62 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M88.18,5 L 88.18 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M99.74,5 L 99.74 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M111.3,5 L 111.3 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M122.86,5 L 122.86 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M134.42,5 L 134.42 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M145.98,5 L 145.98 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M157.54,5 L 157.54 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M169.1,5 L 169.1 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M180.66,5 L 180.66 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M192.22,5 L 192.22 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M203.78,5 L 203.78 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M215.34,5 L 215.34 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M226.9,5 L 226.9 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M238.46,5 L 238.46 90.33" gadfly:scale="5.0" visibility="hidden"/>
      <path fill="none" d="M250.02,5 L 250.02 90.33" gadfly:scale="5.0" visibility="hidden"/>
    </g>
    <g class="plotpanel" id="img-a09943b4-8">
      <g class="geometry" id="img-a09943b4-9">
        <g stroke-width="0.3" id="img-a09943b4-10">
          <g class="color_RGBA{Float32}(0.0f0,0.74736935f0,1.0f0,1.0f0)" stroke="#FFFFFF" fill="#00BFFF" id="img-a09943b4-11">
            <use xlink:href="#img-a09943b4-12" x="134.42" y="7"/>
          </g>
          <g class="color_RGBA{Float32}(0.0f0,0.74736935f0,1.0f0,1.0f0)" stroke="#FFFFFF" fill="#00BFFF" id="img-a09943b4-13">
            <use xlink:href="#img-a09943b4-14" x="76.62" y="47.66"/>
          </g>
          <g class="color_RGBA{Float32}(0.0f0,0.74736935f0,1.0f0,1.0f0)" stroke="#FFFFFF" fill="#00BFFF" id="img-a09943b4-15">
            <use xlink:href="#img-a09943b4-16" x="18.83" y="88.33"/>
          </g>
        </g>
      </g>
    </g>
    <g opacity="0" class="guide zoomslider" stroke="#000000" stroke-opacity="0.000" id="img-a09943b4-17">
      <g fill="#EAEAEA" stroke-width="0.3" stroke-opacity="0" stroke="#6A6A6A" id="img-a09943b4-18">
        <rect x="129.42" y="8" width="4" height="4"/>
        <g class="button_logo" fill="#6A6A6A" id="img-a09943b4-19">
          <path d="M130.22,9.6 L 131.02 9.6 131.02 8.8 131.82 8.8 131.82 9.6 132.62 9.6 132.62 10.4 131.82 10.4 131.82 11.2 131.02 11.2 131.02 10.4 130.22 10.4 z"/>
        </g>
      </g>
      <g fill="#EAEAEA" id="img-a09943b4-20">
        <rect x="109.92" y="8" width="19" height="4"/>
      </g>
      <g class="zoomslider_thumb" fill="#6A6A6A" id="img-a09943b4-21">
        <rect x="118.42" y="8" width="2" height="4"/>
      </g>
      <g fill="#EAEAEA" stroke-width="0.3" stroke-opacity="0" stroke="#6A6A6A" id="img-a09943b4-22">
        <rect x="105.42" y="8" width="4" height="4"/>
        <g class="button_logo" fill="#6A6A6A" id="img-a09943b4-23">
          <path d="M106.22,9.6 L 108.62 9.6 108.62 10.4 106.22 10.4 z"/>
        </g>
      </g>
    </g>
  </g>
</g>
  <g class="guide ylabels" font-size="2.82" font-family="'PT Sans Caption','Helvetica Neue','Helvetica',sans-serif" fill="#6C606B" id="img-a09943b4-24">
    <text x="15.83" y="189.98" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="hidden">-1.5</text>
    <text x="15.83" y="169.65" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="hidden">-1.0</text>
    <text x="15.83" y="149.32" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="hidden">-0.5</text>
    <text x="15.83" y="128.99" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="hidden">0.0</text>
    <text x="15.83" y="108.66" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="hidden">0.5</text>
    <text x="15.83" y="88.33" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="visible">1.0</text>
    <text x="15.83" y="68" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="visible">1.5</text>
    <text x="15.83" y="47.66" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="visible">2.0</text>
    <text x="15.83" y="27.33" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="visible">2.5</text>
    <text x="15.83" y="7" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="visible">3.0</text>
    <text x="15.83" y="-13.33" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="hidden">3.5</text>
    <text x="15.83" y="-33.66" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="hidden">4.0</text>
    <text x="15.83" y="-54" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="hidden">4.5</text>
    <text x="15.83" y="-74.33" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="hidden">5.0</text>
    <text x="15.83" y="-94.66" text-anchor="end" dy="0.35em" gadfly:scale="1.0" visibility="hidden">5.5</text>
    <text x="15.83" y="169.65" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">-1.0</text>
    <text x="15.83" y="165.59" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">-0.9</text>
    <text x="15.83" y="161.52" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">-0.8</text>
    <text x="15.83" y="157.45" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">-0.7</text>
    <text x="15.83" y="153.39" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">-0.6</text>
    <text x="15.83" y="149.32" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">-0.5</text>
    <text x="15.83" y="145.26" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">-0.4</text>
    <text x="15.83" y="141.19" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">-0.3</text>
    <text x="15.83" y="137.12" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">-0.2</text>
    <text x="15.83" y="133.06" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">-0.1</text>
    <text x="15.83" y="128.99" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">0.0</text>
    <text x="15.83" y="124.92" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">0.1</text>
    <text x="15.83" y="120.86" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">0.2</text>
    <text x="15.83" y="116.79" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">0.3</text>
    <text x="15.83" y="112.72" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">0.4</text>
    <text x="15.83" y="108.66" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">0.5</text>
    <text x="15.83" y="104.59" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">0.6</text>
    <text x="15.83" y="100.53" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">0.7</text>
    <text x="15.83" y="96.46" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">0.8</text>
    <text x="15.83" y="92.39" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">0.9</text>
    <text x="15.83" y="88.33" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">1.0</text>
    <text x="15.83" y="84.26" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">1.1</text>
    <text x="15.83" y="80.19" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">1.2</text>
    <text x="15.83" y="76.13" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">1.3</text>
    <text x="15.83" y="72.06" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">1.4</text>
    <text x="15.83" y="68" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">1.5</text>
    <text x="15.83" y="63.93" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">1.6</text>
    <text x="15.83" y="59.86" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">1.7</text>
    <text x="15.83" y="55.8" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">1.8</text>
    <text x="15.83" y="51.73" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">1.9</text>
    <text x="15.83" y="47.66" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">2.0</text>
    <text x="15.83" y="43.6" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">2.1</text>
    <text x="15.83" y="39.53" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">2.2</text>
    <text x="15.83" y="35.46" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">2.3</text>
    <text x="15.83" y="31.4" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">2.4</text>
    <text x="15.83" y="27.33" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">2.5</text>
    <text x="15.83" y="23.27" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">2.6</text>
    <text x="15.83" y="19.2" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">2.7</text>
    <text x="15.83" y="15.13" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">2.8</text>
    <text x="15.83" y="11.07" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">2.9</text>
    <text x="15.83" y="7" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">3.0</text>
    <text x="15.83" y="2.93" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">3.1</text>
    <text x="15.83" y="-1.13" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">3.2</text>
    <text x="15.83" y="-5.2" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">3.3</text>
    <text x="15.83" y="-9.27" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">3.4</text>
    <text x="15.83" y="-13.33" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">3.5</text>
    <text x="15.83" y="-17.4" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">3.6</text>
    <text x="15.83" y="-21.46" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">3.7</text>
    <text x="15.83" y="-25.53" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">3.8</text>
    <text x="15.83" y="-29.6" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">3.9</text>
    <text x="15.83" y="-33.66" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">4.0</text>
    <text x="15.83" y="-37.73" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">4.1</text>
    <text x="15.83" y="-41.8" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">4.2</text>
    <text x="15.83" y="-45.86" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">4.3</text>
    <text x="15.83" y="-49.93" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">4.4</text>
    <text x="15.83" y="-54" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">4.5</text>
    <text x="15.83" y="-58.06" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">4.6</text>
    <text x="15.83" y="-62.13" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">4.7</text>
    <text x="15.83" y="-66.19" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">4.8</text>
    <text x="15.83" y="-70.26" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">4.9</text>
    <text x="15.83" y="-74.33" text-anchor="end" dy="0.35em" gadfly:scale="10.0" visibility="hidden">5.0</text>
    <text x="15.83" y="210.32" text-anchor="end" dy="0.35em" gadfly:scale="0.5" visibility="hidden">-2</text>
    <text x="15.83" y="128.99" text-anchor="end" dy="0.35em" gadfly:scale="0.5" visibility="hidden">0</text>
    <text x="15.83" y="47.66" text-anchor="end" dy="0.35em" gadfly:scale="0.5" visibility="hidden">2</text>
    <text x="15.83" y="-33.66" text-anchor="end" dy="0.35em" gadfly:scale="0.5" visibility="hidden">4</text>
    <text x="15.83" y="-114.99" text-anchor="end" dy="0.35em" gadfly:scale="0.5" visibility="hidden">6</text>
    <text x="15.83" y="169.65" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">-1.0</text>
    <text x="15.83" y="161.52" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">-0.8</text>
    <text x="15.83" y="153.39" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">-0.6</text>
    <text x="15.83" y="145.26" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">-0.4</text>
    <text x="15.83" y="137.12" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">-0.2</text>
    <text x="15.83" y="128.99" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">0.0</text>
    <text x="15.83" y="120.86" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">0.2</text>
    <text x="15.83" y="112.72" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">0.4</text>
    <text x="15.83" y="104.59" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">0.6</text>
    <text x="15.83" y="96.46" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">0.8</text>
    <text x="15.83" y="88.33" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">1.0</text>
    <text x="15.83" y="80.19" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">1.2</text>
    <text x="15.83" y="72.06" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">1.4</text>
    <text x="15.83" y="63.93" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">1.6</text>
    <text x="15.83" y="55.8" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">1.8</text>
    <text x="15.83" y="47.66" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">2.0</text>
    <text x="15.83" y="39.53" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">2.2</text>
    <text x="15.83" y="31.4" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">2.4</text>
    <text x="15.83" y="23.27" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">2.6</text>
    <text x="15.83" y="15.13" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">2.8</text>
    <text x="15.83" y="7" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">3.0</text>
    <text x="15.83" y="-1.13" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">3.2</text>
    <text x="15.83" y="-9.27" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">3.4</text>
    <text x="15.83" y="-17.4" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">3.6</text>
    <text x="15.83" y="-25.53" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">3.8</text>
    <text x="15.83" y="-33.66" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">4.0</text>
    <text x="15.83" y="-41.8" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">4.2</text>
    <text x="15.83" y="-49.93" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">4.4</text>
    <text x="15.83" y="-58.06" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">4.6</text>
    <text x="15.83" y="-66.19" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">4.8</text>
    <text x="15.83" y="-74.33" text-anchor="end" dy="0.35em" gadfly:scale="5.0" visibility="hidden">5.0</text>
  </g>
  <g font-size="3.88" font-family="'PT Sans','Helvetica Neue','Helvetica',sans-serif" fill="#564A55" stroke="#000000" stroke-opacity="0.000" id="img-a09943b4-25">
    <text x="8.81" y="47.66" text-anchor="end" dy="0.35em">y</text>
  </g>
</g>
<defs>
  <clipPath id="img-a09943b4-3">
  <path d="M16.83,5 L 136.42 5 136.42 90.33 16.83 90.33" />
</clipPath>
  <g id="img-a09943b4-12">
    <circle cx="0" cy="0" r="0.9"/>
  </g>
  <g id="img-a09943b4-14">
    <circle cx="0" cy="0" r="0.9"/>
  </g>
  <g id="img-a09943b4-16">
    <circle cx="0" cy="0" r="0.9"/>
  </g>
</defs>
<script> <![CDATA[
(function(N){var k=/[\.\/]/,L=/\s*,\s*/,C=function(a,d){return a-d},a,v,y={n:{}},M=function(){for(var a=0,d=this.length;a<d;a++)if("undefined"!=typeof this[a])return this[a]},A=function(){for(var a=this.length;--a;)if("undefined"!=typeof this[a])return this[a]},w=function(k,d){k=String(k);var f=v,n=Array.prototype.slice.call(arguments,2),u=w.listeners(k),p=0,b,q=[],e={},l=[],r=a;l.firstDefined=M;l.lastDefined=A;a=k;for(var s=v=0,x=u.length;s<x;s++)"zIndex"in u[s]&&(q.push(u[s].zIndex),0>u[s].zIndex&&
(e[u[s].zIndex]=u[s]));for(q.sort(C);0>q[p];)if(b=e[q[p++] ],l.push(b.apply(d,n)),v)return v=f,l;for(s=0;s<x;s++)if(b=u[s],"zIndex"in b)if(b.zIndex==q[p]){l.push(b.apply(d,n));if(v)break;do if(p++,(b=e[q[p] ])&&l.push(b.apply(d,n)),v)break;while(b)}else e[b.zIndex]=b;else if(l.push(b.apply(d,n)),v)break;v=f;a=r;return l};w._events=y;w.listeners=function(a){a=a.split(k);var d=y,f,n,u,p,b,q,e,l=[d],r=[];u=0;for(p=a.length;u<p;u++){e=[];b=0;for(q=l.length;b<q;b++)for(d=l[b].n,f=[d[a[u] ],d["*"] ],n=2;n--;)if(d=
f[n])e.push(d),r=r.concat(d.f||[]);l=e}return r};w.on=function(a,d){a=String(a);if("function"!=typeof d)return function(){};for(var f=a.split(L),n=0,u=f.length;n<u;n++)(function(a){a=a.split(k);for(var b=y,f,e=0,l=a.length;e<l;e++)b=b.n,b=b.hasOwnProperty(a[e])&&b[a[e] ]||(b[a[e] ]={n:{}});b.f=b.f||[];e=0;for(l=b.f.length;e<l;e++)if(b.f[e]==d){f=!0;break}!f&&b.f.push(d)})(f[n]);return function(a){+a==+a&&(d.zIndex=+a)}};w.f=function(a){var d=[].slice.call(arguments,1);return function(){w.apply(null,
[a,null].concat(d).concat([].slice.call(arguments,0)))}};w.stop=function(){v=1};w.nt=function(k){return k?(new RegExp("(?:\\.|\\/|^)"+k+"(?:\\.|\\/|$)")).test(a):a};w.nts=function(){return a.split(k)};w.off=w.unbind=function(a,d){if(a){var f=a.split(L);if(1<f.length)for(var n=0,u=f.length;n<u;n++)w.off(f[n],d);else{for(var f=a.split(k),p,b,q,e,l=[y],n=0,u=f.length;n<u;n++)for(e=0;e<l.length;e+=q.length-2){q=[e,1];p=l[e].n;if("*"!=f[n])p[f[n] ]&&q.push(p[f[n] ]);else for(b in p)p.hasOwnProperty(b)&&
q.push(p[b]);l.splice.apply(l,q)}n=0;for(u=l.length;n<u;n++)for(p=l[n];p.n;){if(d){if(p.f){e=0;for(f=p.f.length;e<f;e++)if(p.f[e]==d){p.f.splice(e,1);break}!p.f.length&&delete p.f}for(b in p.n)if(p.n.hasOwnProperty(b)&&p.n[b].f){q=p.n[b].f;e=0;for(f=q.length;e<f;e++)if(q[e]==d){q.splice(e,1);break}!q.length&&delete p.n[b].f}}else for(b in delete p.f,p.n)p.n.hasOwnProperty(b)&&p.n[b].f&&delete p.n[b].f;p=p.n}}}else w._events=y={n:{}}};w.once=function(a,d){var f=function(){w.unbind(a,f);return d.apply(this,
arguments)};return w.on(a,f)};w.version="0.4.2";w.toString=function(){return"You are running Eve 0.4.2"};"undefined"!=typeof module&&module.exports?module.exports=w:"function"===typeof define&&define.amd?define("eve",[],function(){return w}):N.eve=w})(this);
(function(N,k){"function"===typeof define&&define.amd?define("Snap.svg",["eve"],function(L){return k(N,L)}):k(N,N.eve)})(this,function(N,k){var L=function(a){var k={},y=N.requestAnimationFrame||N.webkitRequestAnimationFrame||N.mozRequestAnimationFrame||N.oRequestAnimationFrame||N.msRequestAnimationFrame||function(a){setTimeout(a,16)},M=Array.isArray||function(a){return a instanceof Array||"[object Array]"==Object.prototype.toString.call(a)},A=0,w="M"+(+new Date).toString(36),z=function(a){if(null==
a)return this.s;var b=this.s-a;this.b+=this.dur*b;this.B+=this.dur*b;this.s=a},d=function(a){if(null==a)return this.spd;this.spd=a},f=function(a){if(null==a)return this.dur;this.s=this.s*a/this.dur;this.dur=a},n=function(){delete k[this.id];this.update();a("mina.stop."+this.id,this)},u=function(){this.pdif||(delete k[this.id],this.update(),this.pdif=this.get()-this.b)},p=function(){this.pdif&&(this.b=this.get()-this.pdif,delete this.pdif,k[this.id]=this)},b=function(){var a;if(M(this.start)){a=[];
for(var b=0,e=this.start.length;b<e;b++)a[b]=+this.start[b]+(this.end[b]-this.start[b])*this.easing(this.s)}else a=+this.start+(this.end-this.start)*this.easing(this.s);this.set(a)},q=function(){var l=0,b;for(b in k)if(k.hasOwnProperty(b)){var e=k[b],f=e.get();l++;e.s=(f-e.b)/(e.dur/e.spd);1<=e.s&&(delete k[b],e.s=1,l--,function(b){setTimeout(function(){a("mina.finish."+b.id,b)})}(e));e.update()}l&&y(q)},e=function(a,r,s,x,G,h,J){a={id:w+(A++).toString(36),start:a,end:r,b:s,s:0,dur:x-s,spd:1,get:G,
set:h,easing:J||e.linear,status:z,speed:d,duration:f,stop:n,pause:u,resume:p,update:b};k[a.id]=a;r=0;for(var K in k)if(k.hasOwnProperty(K)&&(r++,2==r))break;1==r&&y(q);return a};e.time=Date.now||function(){return+new Date};e.getById=function(a){return k[a]||null};e.linear=function(a){return a};e.easeout=function(a){return Math.pow(a,1.7)};e.easein=function(a){return Math.pow(a,0.48)};e.easeinout=function(a){if(1==a)return 1;if(0==a)return 0;var b=0.48-a/1.04,e=Math.sqrt(0.1734+b*b);a=e-b;a=Math.pow(Math.abs(a),
1/3)*(0>a?-1:1);b=-e-b;b=Math.pow(Math.abs(b),1/3)*(0>b?-1:1);a=a+b+0.5;return 3*(1-a)*a*a+a*a*a};e.backin=function(a){return 1==a?1:a*a*(2.70158*a-1.70158)};e.backout=function(a){if(0==a)return 0;a-=1;return a*a*(2.70158*a+1.70158)+1};e.elastic=function(a){return a==!!a?a:Math.pow(2,-10*a)*Math.sin(2*(a-0.075)*Math.PI/0.3)+1};e.bounce=function(a){a<1/2.75?a*=7.5625*a:a<2/2.75?(a-=1.5/2.75,a=7.5625*a*a+0.75):a<2.5/2.75?(a-=2.25/2.75,a=7.5625*a*a+0.9375):(a-=2.625/2.75,a=7.5625*a*a+0.984375);return a};
return N.mina=e}("undefined"==typeof k?function(){}:k),C=function(){function a(c,t){if(c){if(c.tagName)return x(c);if(y(c,"array")&&a.set)return a.set.apply(a,c);if(c instanceof e)return c;if(null==t)return c=G.doc.querySelector(c),x(c)}return new s(null==c?"100%":c,null==t?"100%":t)}function v(c,a){if(a){"#text"==c&&(c=G.doc.createTextNode(a.text||""));"string"==typeof c&&(c=v(c));if("string"==typeof a)return"xlink:"==a.substring(0,6)?c.getAttributeNS(m,a.substring(6)):"xml:"==a.substring(0,4)?c.getAttributeNS(la,
a.substring(4)):c.getAttribute(a);for(var da in a)if(a[h](da)){var b=J(a[da]);b?"xlink:"==da.substring(0,6)?c.setAttributeNS(m,da.substring(6),b):"xml:"==da.substring(0,4)?c.setAttributeNS(la,da.substring(4),b):c.setAttribute(da,b):c.removeAttribute(da)}}else c=G.doc.createElementNS(la,c);return c}function y(c,a){a=J.prototype.toLowerCase.call(a);return"finite"==a?isFinite(c):"array"==a&&(c instanceof Array||Array.isArray&&Array.isArray(c))?!0:"null"==a&&null===c||a==typeof c&&null!==c||"object"==
a&&c===Object(c)||$.call(c).slice(8,-1).toLowerCase()==a}function M(c){if("function"==typeof c||Object(c)!==c)return c;var a=new c.constructor,b;for(b in c)c[h](b)&&(a[b]=M(c[b]));return a}function A(c,a,b){function m(){var e=Array.prototype.slice.call(arguments,0),f=e.join("\u2400"),d=m.cache=m.cache||{},l=m.count=m.count||[];if(d[h](f)){a:for(var e=l,l=f,B=0,H=e.length;B<H;B++)if(e[B]===l){e.push(e.splice(B,1)[0]);break a}return b?b(d[f]):d[f]}1E3<=l.length&&delete d[l.shift()];l.push(f);d[f]=c.apply(a,
e);return b?b(d[f]):d[f]}return m}function w(c,a,b,m,e,f){return null==e?(c-=b,a-=m,c||a?(180*I.atan2(-a,-c)/C+540)%360:0):w(c,a,e,f)-w(b,m,e,f)}function z(c){return c%360*C/180}function d(c){var a=[];c=c.replace(/(?:^|\s)(\w+)\(([^)]+)\)/g,function(c,b,m){m=m.split(/\s*,\s*|\s+/);"rotate"==b&&1==m.length&&m.push(0,0);"scale"==b&&(2<m.length?m=m.slice(0,2):2==m.length&&m.push(0,0),1==m.length&&m.push(m[0],0,0));"skewX"==b?a.push(["m",1,0,I.tan(z(m[0])),1,0,0]):"skewY"==b?a.push(["m",1,I.tan(z(m[0])),
0,1,0,0]):a.push([b.charAt(0)].concat(m));return c});return a}function f(c,t){var b=O(c),m=new a.Matrix;if(b)for(var e=0,f=b.length;e<f;e++){var h=b[e],d=h.length,B=J(h[0]).toLowerCase(),H=h[0]!=B,l=H?m.invert():0,E;"t"==B&&2==d?m.translate(h[1],0):"t"==B&&3==d?H?(d=l.x(0,0),B=l.y(0,0),H=l.x(h[1],h[2]),l=l.y(h[1],h[2]),m.translate(H-d,l-B)):m.translate(h[1],h[2]):"r"==B?2==d?(E=E||t,m.rotate(h[1],E.x+E.width/2,E.y+E.height/2)):4==d&&(H?(H=l.x(h[2],h[3]),l=l.y(h[2],h[3]),m.rotate(h[1],H,l)):m.rotate(h[1],
h[2],h[3])):"s"==B?2==d||3==d?(E=E||t,m.scale(h[1],h[d-1],E.x+E.width/2,E.y+E.height/2)):4==d?H?(H=l.x(h[2],h[3]),l=l.y(h[2],h[3]),m.scale(h[1],h[1],H,l)):m.scale(h[1],h[1],h[2],h[3]):5==d&&(H?(H=l.x(h[3],h[4]),l=l.y(h[3],h[4]),m.scale(h[1],h[2],H,l)):m.scale(h[1],h[2],h[3],h[4])):"m"==B&&7==d&&m.add(h[1],h[2],h[3],h[4],h[5],h[6])}return m}function n(c,t){if(null==t){var m=!0;t="linearGradient"==c.type||"radialGradient"==c.type?c.node.getAttribute("gradientTransform"):"pattern"==c.type?c.node.getAttribute("patternTransform"):
c.node.getAttribute("transform");if(!t)return new a.Matrix;t=d(t)}else t=a._.rgTransform.test(t)?J(t).replace(/\.{3}|\u2026/g,c._.transform||aa):d(t),y(t,"array")&&(t=a.path?a.path.toString.call(t):J(t)),c._.transform=t;var b=f(t,c.getBBox(1));if(m)return b;c.matrix=b}function u(c){c=c.node.ownerSVGElement&&x(c.node.ownerSVGElement)||c.node.parentNode&&x(c.node.parentNode)||a.select("svg")||a(0,0);var t=c.select("defs"),t=null==t?!1:t.node;t||(t=r("defs",c.node).node);return t}function p(c){return c.node.ownerSVGElement&&
x(c.node.ownerSVGElement)||a.select("svg")}function b(c,a,m){function b(c){if(null==c)return aa;if(c==+c)return c;v(B,{width:c});try{return B.getBBox().width}catch(a){return 0}}function h(c){if(null==c)return aa;if(c==+c)return c;v(B,{height:c});try{return B.getBBox().height}catch(a){return 0}}function e(b,B){null==a?d[b]=B(c.attr(b)||0):b==a&&(d=B(null==m?c.attr(b)||0:m))}var f=p(c).node,d={},B=f.querySelector(".svg---mgr");B||(B=v("rect"),v(B,{x:-9E9,y:-9E9,width:10,height:10,"class":"svg---mgr",
fill:"none"}),f.appendChild(B));switch(c.type){case "rect":e("rx",b),e("ry",h);case "image":e("width",b),e("height",h);case "text":e("x",b);e("y",h);break;case "circle":e("cx",b);e("cy",h);e("r",b);break;case "ellipse":e("cx",b);e("cy",h);e("rx",b);e("ry",h);break;case "line":e("x1",b);e("x2",b);e("y1",h);e("y2",h);break;case "marker":e("refX",b);e("markerWidth",b);e("refY",h);e("markerHeight",h);break;case "radialGradient":e("fx",b);e("fy",h);break;case "tspan":e("dx",b);e("dy",h);break;default:e(a,
b)}f.removeChild(B);return d}function q(c){y(c,"array")||(c=Array.prototype.slice.call(arguments,0));for(var a=0,b=0,m=this.node;this[a];)delete this[a++];for(a=0;a<c.length;a++)"set"==c[a].type?c[a].forEach(function(c){m.appendChild(c.node)}):m.appendChild(c[a].node);for(var h=m.childNodes,a=0;a<h.length;a++)this[b++]=x(h[a]);return this}function e(c){if(c.snap in E)return E[c.snap];var a=this.id=V(),b;try{b=c.ownerSVGElement}catch(m){}this.node=c;b&&(this.paper=new s(b));this.type=c.tagName;this.anims=
{};this._={transform:[]};c.snap=a;E[a]=this;"g"==this.type&&(this.add=q);if(this.type in{g:1,mask:1,pattern:1})for(var e in s.prototype)s.prototype[h](e)&&(this[e]=s.prototype[e])}function l(c){this.node=c}function r(c,a){var b=v(c);a.appendChild(b);return x(b)}function s(c,a){var b,m,f,d=s.prototype;if(c&&"svg"==c.tagName){if(c.snap in E)return E[c.snap];var l=c.ownerDocument;b=new e(c);m=c.getElementsByTagName("desc")[0];f=c.getElementsByTagName("defs")[0];m||(m=v("desc"),m.appendChild(l.createTextNode("Created with Snap")),
b.node.appendChild(m));f||(f=v("defs"),b.node.appendChild(f));b.defs=f;for(var ca in d)d[h](ca)&&(b[ca]=d[ca]);b.paper=b.root=b}else b=r("svg",G.doc.body),v(b.node,{height:a,version:1.1,width:c,xmlns:la});return b}function x(c){return!c||c instanceof e||c instanceof l?c:c.tagName&&"svg"==c.tagName.toLowerCase()?new s(c):c.tagName&&"object"==c.tagName.toLowerCase()&&"image/svg+xml"==c.type?new s(c.contentDocument.getElementsByTagName("svg")[0]):new e(c)}a.version="0.3.0";a.toString=function(){return"Snap v"+
this.version};a._={};var G={win:N,doc:N.document};a._.glob=G;var h="hasOwnProperty",J=String,K=parseFloat,U=parseInt,I=Math,P=I.max,Q=I.min,Y=I.abs,C=I.PI,aa="",$=Object.prototype.toString,F=/^\s*((#[a-f\d]{6})|(#[a-f\d]{3})|rgba?\(\s*([\d\.]+%?\s*,\s*[\d\.]+%?\s*,\s*[\d\.]+%?(?:\s*,\s*[\d\.]+%?)?)\s*\)|hsba?\(\s*([\d\.]+(?:deg|\xb0|%)?\s*,\s*[\d\.]+%?\s*,\s*[\d\.]+(?:%?\s*,\s*[\d\.]+)?%?)\s*\)|hsla?\(\s*([\d\.]+(?:deg|\xb0|%)?\s*,\s*[\d\.]+%?\s*,\s*[\d\.]+(?:%?\s*,\s*[\d\.]+)?%?)\s*\))\s*$/i;a._.separator=
RegExp("[,\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029]+");var S=RegExp("[\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029]*,[\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029]*"),X={hs:1,rg:1},W=RegExp("([a-z])[\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029,]*((-?\\d*\\.?\\d*(?:e[\\-+]?\\d+)?[\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029]*,?[\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029]*)+)",
"ig"),ma=RegExp("([rstm])[\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029,]*((-?\\d*\\.?\\d*(?:e[\\-+]?\\d+)?[\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029]*,?[\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029]*)+)","ig"),Z=RegExp("(-?\\d*\\.?\\d*(?:e[\\-+]?\\d+)?)[\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029]*,?[\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029]*",
"ig"),na=0,ba="S"+(+new Date).toString(36),V=function(){return ba+(na++).toString(36)},m="http://www.w3.org/1999/xlink",la="http://www.w3.org/2000/svg",E={},ca=a.url=function(c){return"url('#"+c+"')"};a._.$=v;a._.id=V;a.format=function(){var c=/\{([^\}]+)\}/g,a=/(?:(?:^|\.)(.+?)(?=\[|\.|$|\()|\[('|")(.+?)\2\])(\(\))?/g,b=function(c,b,m){var h=m;b.replace(a,function(c,a,b,m,t){a=a||m;h&&(a in h&&(h=h[a]),"function"==typeof h&&t&&(h=h()))});return h=(null==h||h==m?c:h)+""};return function(a,m){return J(a).replace(c,
function(c,a){return b(c,a,m)})}}();a._.clone=M;a._.cacher=A;a.rad=z;a.deg=function(c){return 180*c/C%360};a.angle=w;a.is=y;a.snapTo=function(c,a,b){b=y(b,"finite")?b:10;if(y(c,"array"))for(var m=c.length;m--;){if(Y(c[m]-a)<=b)return c[m]}else{c=+c;m=a%c;if(m<b)return a-m;if(m>c-b)return a-m+c}return a};a.getRGB=A(function(c){if(!c||(c=J(c)).indexOf("-")+1)return{r:-1,g:-1,b:-1,hex:"none",error:1,toString:ka};if("none"==c)return{r:-1,g:-1,b:-1,hex:"none",toString:ka};!X[h](c.toLowerCase().substring(0,
2))&&"#"!=c.charAt()&&(c=T(c));if(!c)return{r:-1,g:-1,b:-1,hex:"none",error:1,toString:ka};var b,m,e,f,d;if(c=c.match(F)){c[2]&&(e=U(c[2].substring(5),16),m=U(c[2].substring(3,5),16),b=U(c[2].substring(1,3),16));c[3]&&(e=U((d=c[3].charAt(3))+d,16),m=U((d=c[3].charAt(2))+d,16),b=U((d=c[3].charAt(1))+d,16));c[4]&&(d=c[4].split(S),b=K(d[0]),"%"==d[0].slice(-1)&&(b*=2.55),m=K(d[1]),"%"==d[1].slice(-1)&&(m*=2.55),e=K(d[2]),"%"==d[2].slice(-1)&&(e*=2.55),"rgba"==c[1].toLowerCase().slice(0,4)&&(f=K(d[3])),
d[3]&&"%"==d[3].slice(-1)&&(f/=100));if(c[5])return d=c[5].split(S),b=K(d[0]),"%"==d[0].slice(-1)&&(b/=100),m=K(d[1]),"%"==d[1].slice(-1)&&(m/=100),e=K(d[2]),"%"==d[2].slice(-1)&&(e/=100),"deg"!=d[0].slice(-3)&&"\u00b0"!=d[0].slice(-1)||(b/=360),"hsba"==c[1].toLowerCase().slice(0,4)&&(f=K(d[3])),d[3]&&"%"==d[3].slice(-1)&&(f/=100),a.hsb2rgb(b,m,e,f);if(c[6])return d=c[6].split(S),b=K(d[0]),"%"==d[0].slice(-1)&&(b/=100),m=K(d[1]),"%"==d[1].slice(-1)&&(m/=100),e=K(d[2]),"%"==d[2].slice(-1)&&(e/=100),
"deg"!=d[0].slice(-3)&&"\u00b0"!=d[0].slice(-1)||(b/=360),"hsla"==c[1].toLowerCase().slice(0,4)&&(f=K(d[3])),d[3]&&"%"==d[3].slice(-1)&&(f/=100),a.hsl2rgb(b,m,e,f);b=Q(I.round(b),255);m=Q(I.round(m),255);e=Q(I.round(e),255);f=Q(P(f,0),1);c={r:b,g:m,b:e,toString:ka};c.hex="#"+(16777216|e|m<<8|b<<16).toString(16).slice(1);c.opacity=y(f,"finite")?f:1;return c}return{r:-1,g:-1,b:-1,hex:"none",error:1,toString:ka}},a);a.hsb=A(function(c,b,m){return a.hsb2rgb(c,b,m).hex});a.hsl=A(function(c,b,m){return a.hsl2rgb(c,
b,m).hex});a.rgb=A(function(c,a,b,m){if(y(m,"finite")){var e=I.round;return"rgba("+[e(c),e(a),e(b),+m.toFixed(2)]+")"}return"#"+(16777216|b|a<<8|c<<16).toString(16).slice(1)});var T=function(c){var a=G.doc.getElementsByTagName("head")[0]||G.doc.getElementsByTagName("svg")[0];T=A(function(c){if("red"==c.toLowerCase())return"rgb(255, 0, 0)";a.style.color="rgb(255, 0, 0)";a.style.color=c;c=G.doc.defaultView.getComputedStyle(a,aa).getPropertyValue("color");return"rgb(255, 0, 0)"==c?null:c});return T(c)},
qa=function(){return"hsb("+[this.h,this.s,this.b]+")"},ra=function(){return"hsl("+[this.h,this.s,this.l]+")"},ka=function(){return 1==this.opacity||null==this.opacity?this.hex:"rgba("+[this.r,this.g,this.b,this.opacity]+")"},D=function(c,b,m){null==b&&y(c,"object")&&"r"in c&&"g"in c&&"b"in c&&(m=c.b,b=c.g,c=c.r);null==b&&y(c,string)&&(m=a.getRGB(c),c=m.r,b=m.g,m=m.b);if(1<c||1<b||1<m)c/=255,b/=255,m/=255;return[c,b,m]},oa=function(c,b,m,e){c=I.round(255*c);b=I.round(255*b);m=I.round(255*m);c={r:c,
g:b,b:m,opacity:y(e,"finite")?e:1,hex:a.rgb(c,b,m),toString:ka};y(e,"finite")&&(c.opacity=e);return c};a.color=function(c){var b;y(c,"object")&&"h"in c&&"s"in c&&"b"in c?(b=a.hsb2rgb(c),c.r=b.r,c.g=b.g,c.b=b.b,c.opacity=1,c.hex=b.hex):y(c,"object")&&"h"in c&&"s"in c&&"l"in c?(b=a.hsl2rgb(c),c.r=b.r,c.g=b.g,c.b=b.b,c.opacity=1,c.hex=b.hex):(y(c,"string")&&(c=a.getRGB(c)),y(c,"object")&&"r"in c&&"g"in c&&"b"in c&&!("error"in c)?(b=a.rgb2hsl(c),c.h=b.h,c.s=b.s,c.l=b.l,b=a.rgb2hsb(c),c.v=b.b):(c={hex:"none"},
c.r=c.g=c.b=c.h=c.s=c.v=c.l=-1,c.error=1));c.toString=ka;return c};a.hsb2rgb=function(c,a,b,m){y(c,"object")&&"h"in c&&"s"in c&&"b"in c&&(b=c.b,a=c.s,c=c.h,m=c.o);var e,h,d;c=360*c%360/60;d=b*a;a=d*(1-Y(c%2-1));b=e=h=b-d;c=~~c;b+=[d,a,0,0,a,d][c];e+=[a,d,d,a,0,0][c];h+=[0,0,a,d,d,a][c];return oa(b,e,h,m)};a.hsl2rgb=function(c,a,b,m){y(c,"object")&&"h"in c&&"s"in c&&"l"in c&&(b=c.l,a=c.s,c=c.h);if(1<c||1<a||1<b)c/=360,a/=100,b/=100;var e,h,d;c=360*c%360/60;d=2*a*(0.5>b?b:1-b);a=d*(1-Y(c%2-1));b=e=
h=b-d/2;c=~~c;b+=[d,a,0,0,a,d][c];e+=[a,d,d,a,0,0][c];h+=[0,0,a,d,d,a][c];return oa(b,e,h,m)};a.rgb2hsb=function(c,a,b){b=D(c,a,b);c=b[0];a=b[1];b=b[2];var m,e;m=P(c,a,b);e=m-Q(c,a,b);c=((0==e?0:m==c?(a-b)/e:m==a?(b-c)/e+2:(c-a)/e+4)+360)%6*60/360;return{h:c,s:0==e?0:e/m,b:m,toString:qa}};a.rgb2hsl=function(c,a,b){b=D(c,a,b);c=b[0];a=b[1];b=b[2];var m,e,h;m=P(c,a,b);e=Q(c,a,b);h=m-e;c=((0==h?0:m==c?(a-b)/h:m==a?(b-c)/h+2:(c-a)/h+4)+360)%6*60/360;m=(m+e)/2;return{h:c,s:0==h?0:0.5>m?h/(2*m):h/(2-2*
m),l:m,toString:ra}};a.parsePathString=function(c){if(!c)return null;var b=a.path(c);if(b.arr)return a.path.clone(b.arr);var m={a:7,c:6,o:2,h:1,l:2,m:2,r:4,q:4,s:4,t:2,v:1,u:3,z:0},e=[];y(c,"array")&&y(c[0],"array")&&(e=a.path.clone(c));e.length||J(c).replace(W,function(c,a,b){var h=[];c=a.toLowerCase();b.replace(Z,function(c,a){a&&h.push(+a)});"m"==c&&2<h.length&&(e.push([a].concat(h.splice(0,2))),c="l",a="m"==a?"l":"L");"o"==c&&1==h.length&&e.push([a,h[0] ]);if("r"==c)e.push([a].concat(h));else for(;h.length>=
m[c]&&(e.push([a].concat(h.splice(0,m[c]))),m[c]););});e.toString=a.path.toString;b.arr=a.path.clone(e);return e};var O=a.parseTransformString=function(c){if(!c)return null;var b=[];y(c,"array")&&y(c[0],"array")&&(b=a.path.clone(c));b.length||J(c).replace(ma,function(c,a,m){var e=[];a.toLowerCase();m.replace(Z,function(c,a){a&&e.push(+a)});b.push([a].concat(e))});b.toString=a.path.toString;return b};a._.svgTransform2string=d;a._.rgTransform=RegExp("^[a-z][\t\n\x0B\f\r \u00a0\u1680\u180e\u2000\u2001\u2002\u2003\u2004\u2005\u2006\u2007\u2008\u2009\u200a\u202f\u205f\u3000\u2028\u2029]*-?\\.?\\d",
"i");a._.transform2matrix=f;a._unit2px=b;a._.getSomeDefs=u;a._.getSomeSVG=p;a.select=function(c){return x(G.doc.querySelector(c))};a.selectAll=function(c){c=G.doc.querySelectorAll(c);for(var b=(a.set||Array)(),m=0;m<c.length;m++)b.push(x(c[m]));return b};setInterval(function(){for(var c in E)if(E[h](c)){var a=E[c],b=a.node;("svg"!=a.type&&!b.ownerSVGElement||"svg"==a.type&&(!b.parentNode||"ownerSVGElement"in b.parentNode&&!b.ownerSVGElement))&&delete E[c]}},1E4);(function(c){function m(c){function a(c,
b){var m=v(c.node,b);(m=(m=m&&m.match(d))&&m[2])&&"#"==m.charAt()&&(m=m.substring(1))&&(f[m]=(f[m]||[]).concat(function(a){var m={};m[b]=ca(a);v(c.node,m)}))}function b(c){var a=v(c.node,"xlink:href");a&&"#"==a.charAt()&&(a=a.substring(1))&&(f[a]=(f[a]||[]).concat(function(a){c.attr("xlink:href","#"+a)}))}var e=c.selectAll("*"),h,d=/^\s*url\(("|'|)(.*)\1\)\s*$/;c=[];for(var f={},l=0,E=e.length;l<E;l++){h=e[l];a(h,"fill");a(h,"stroke");a(h,"filter");a(h,"mask");a(h,"clip-path");b(h);var t=v(h.node,
"id");t&&(v(h.node,{id:h.id}),c.push({old:t,id:h.id}))}l=0;for(E=c.length;l<E;l++)if(e=f[c[l].old])for(h=0,t=e.length;h<t;h++)e[h](c[l].id)}function e(c,a,b){return function(m){m=m.slice(c,a);1==m.length&&(m=m[0]);return b?b(m):m}}function d(c){return function(){var a=c?"<"+this.type:"",b=this.node.attributes,m=this.node.childNodes;if(c)for(var e=0,h=b.length;e<h;e++)a+=" "+b[e].name+'="'+b[e].value.replace(/"/g,'\\"')+'"';if(m.length){c&&(a+=">");e=0;for(h=m.length;e<h;e++)3==m[e].nodeType?a+=m[e].nodeValue:
1==m[e].nodeType&&(a+=x(m[e]).toString());c&&(a+="</"+this.type+">")}else c&&(a+="/>");return a}}c.attr=function(c,a){if(!c)return this;if(y(c,"string"))if(1<arguments.length){var b={};b[c]=a;c=b}else return k("snap.util.getattr."+c,this).firstDefined();for(var m in c)c[h](m)&&k("snap.util.attr."+m,this,c[m]);return this};c.getBBox=function(c){if(!a.Matrix||!a.path)return this.node.getBBox();var b=this,m=new a.Matrix;if(b.removed)return a._.box();for(;"use"==b.type;)if(c||(m=m.add(b.transform().localMatrix.translate(b.attr("x")||
0,b.attr("y")||0))),b.original)b=b.original;else var e=b.attr("xlink:href"),b=b.original=b.node.ownerDocument.getElementById(e.substring(e.indexOf("#")+1));var e=b._,h=a.path.get[b.type]||a.path.get.deflt;try{if(c)return e.bboxwt=h?a.path.getBBox(b.realPath=h(b)):a._.box(b.node.getBBox()),a._.box(e.bboxwt);b.realPath=h(b);b.matrix=b.transform().localMatrix;e.bbox=a.path.getBBox(a.path.map(b.realPath,m.add(b.matrix)));return a._.box(e.bbox)}catch(d){return a._.box()}};var f=function(){return this.string};
c.transform=function(c){var b=this._;if(null==c){var m=this;c=new a.Matrix(this.node.getCTM());for(var e=n(this),h=[e],d=new a.Matrix,l=e.toTransformString(),b=J(e)==J(this.matrix)?J(b.transform):l;"svg"!=m.type&&(m=m.parent());)h.push(n(m));for(m=h.length;m--;)d.add(h[m]);return{string:b,globalMatrix:c,totalMatrix:d,localMatrix:e,diffMatrix:c.clone().add(e.invert()),global:c.toTransformString(),total:d.toTransformString(),local:l,toString:f}}c instanceof a.Matrix?this.matrix=c:n(this,c);this.node&&
("linearGradient"==this.type||"radialGradient"==this.type?v(this.node,{gradientTransform:this.matrix}):"pattern"==this.type?v(this.node,{patternTransform:this.matrix}):v(this.node,{transform:this.matrix}));return this};c.parent=function(){return x(this.node.parentNode)};c.append=c.add=function(c){if(c){if("set"==c.type){var a=this;c.forEach(function(c){a.add(c)});return this}c=x(c);this.node.appendChild(c.node);c.paper=this.paper}return this};c.appendTo=function(c){c&&(c=x(c),c.append(this));return this};
c.prepend=function(c){if(c){if("set"==c.type){var a=this,b;c.forEach(function(c){b?b.after(c):a.prepend(c);b=c});return this}c=x(c);var m=c.parent();this.node.insertBefore(c.node,this.node.firstChild);this.add&&this.add();c.paper=this.paper;this.parent()&&this.parent().add();m&&m.add()}return this};c.prependTo=function(c){c=x(c);c.prepend(this);return this};c.before=function(c){if("set"==c.type){var a=this;c.forEach(function(c){var b=c.parent();a.node.parentNode.insertBefore(c.node,a.node);b&&b.add()});
this.parent().add();return this}c=x(c);var b=c.parent();this.node.parentNode.insertBefore(c.node,this.node);this.parent()&&this.parent().add();b&&b.add();c.paper=this.paper;return this};c.after=function(c){c=x(c);var a=c.parent();this.node.nextSibling?this.node.parentNode.insertBefore(c.node,this.node.nextSibling):this.node.parentNode.appendChild(c.node);this.parent()&&this.parent().add();a&&a.add();c.paper=this.paper;return this};c.insertBefore=function(c){c=x(c);var a=this.parent();c.node.parentNode.insertBefore(this.node,
c.node);this.paper=c.paper;a&&a.add();c.parent()&&c.parent().add();return this};c.insertAfter=function(c){c=x(c);var a=this.parent();c.node.parentNode.insertBefore(this.node,c.node.nextSibling);this.paper=c.paper;a&&a.add();c.parent()&&c.parent().add();return this};c.remove=function(){var c=this.parent();this.node.parentNode&&this.node.parentNode.removeChild(this.node);delete this.paper;this.removed=!0;c&&c.add();return this};c.select=function(c){return x(this.node.querySelector(c))};c.selectAll=
function(c){c=this.node.querySelectorAll(c);for(var b=(a.set||Array)(),m=0;m<c.length;m++)b.push(x(c[m]));return b};c.asPX=function(c,a){null==a&&(a=this.attr(c));return+b(this,c,a)};c.use=function(){var c,a=this.node.id;a||(a=this.id,v(this.node,{id:a}));c="linearGradient"==this.type||"radialGradient"==this.type||"pattern"==this.type?r(this.type,this.node.parentNode):r("use",this.node.parentNode);v(c.node,{"xlink:href":"#"+a});c.original=this;return c};var l=/\S+/g;c.addClass=function(c){var a=(c||
"").match(l)||[];c=this.node;var b=c.className.baseVal,m=b.match(l)||[],e,h,d;if(a.length){for(e=0;d=a[e++];)h=m.indexOf(d),~h||m.push(d);a=m.join(" ");b!=a&&(c.className.baseVal=a)}return this};c.removeClass=function(c){var a=(c||"").match(l)||[];c=this.node;var b=c.className.baseVal,m=b.match(l)||[],e,h;if(m.length){for(e=0;h=a[e++];)h=m.indexOf(h),~h&&m.splice(h,1);a=m.join(" ");b!=a&&(c.className.baseVal=a)}return this};c.hasClass=function(c){return!!~(this.node.className.baseVal.match(l)||[]).indexOf(c)};
c.toggleClass=function(c,a){if(null!=a)return a?this.addClass(c):this.removeClass(c);var b=(c||"").match(l)||[],m=this.node,e=m.className.baseVal,h=e.match(l)||[],d,f,E;for(d=0;E=b[d++];)f=h.indexOf(E),~f?h.splice(f,1):h.push(E);b=h.join(" ");e!=b&&(m.className.baseVal=b);return this};c.clone=function(){var c=x(this.node.cloneNode(!0));v(c.node,"id")&&v(c.node,{id:c.id});m(c);c.insertAfter(this);return c};c.toDefs=function(){u(this).appendChild(this.node);return this};c.pattern=c.toPattern=function(c,
a,b,m){var e=r("pattern",u(this));null==c&&(c=this.getBBox());y(c,"object")&&"x"in c&&(a=c.y,b=c.width,m=c.height,c=c.x);v(e.node,{x:c,y:a,width:b,height:m,patternUnits:"userSpaceOnUse",id:e.id,viewBox:[c,a,b,m].join(" ")});e.node.appendChild(this.node);return e};c.marker=function(c,a,b,m,e,h){var d=r("marker",u(this));null==c&&(c=this.getBBox());y(c,"object")&&"x"in c&&(a=c.y,b=c.width,m=c.height,e=c.refX||c.cx,h=c.refY||c.cy,c=c.x);v(d.node,{viewBox:[c,a,b,m].join(" "),markerWidth:b,markerHeight:m,
orient:"auto",refX:e||0,refY:h||0,id:d.id});d.node.appendChild(this.node);return d};var E=function(c,a,b,m){"function"!=typeof b||b.length||(m=b,b=L.linear);this.attr=c;this.dur=a;b&&(this.easing=b);m&&(this.callback=m)};a._.Animation=E;a.animation=function(c,a,b,m){return new E(c,a,b,m)};c.inAnim=function(){var c=[],a;for(a in this.anims)this.anims[h](a)&&function(a){c.push({anim:new E(a._attrs,a.dur,a.easing,a._callback),mina:a,curStatus:a.status(),status:function(c){return a.status(c)},stop:function(){a.stop()}})}(this.anims[a]);
return c};a.animate=function(c,a,b,m,e,h){"function"!=typeof e||e.length||(h=e,e=L.linear);var d=L.time();c=L(c,a,d,d+m,L.time,b,e);h&&k.once("mina.finish."+c.id,h);return c};c.stop=function(){for(var c=this.inAnim(),a=0,b=c.length;a<b;a++)c[a].stop();return this};c.animate=function(c,a,b,m){"function"!=typeof b||b.length||(m=b,b=L.linear);c instanceof E&&(m=c.callback,b=c.easing,a=b.dur,c=c.attr);var d=[],f=[],l={},t,ca,n,T=this,q;for(q in c)if(c[h](q)){T.equal?(n=T.equal(q,J(c[q])),t=n.from,ca=
n.to,n=n.f):(t=+T.attr(q),ca=+c[q]);var la=y(t,"array")?t.length:1;l[q]=e(d.length,d.length+la,n);d=d.concat(t);f=f.concat(ca)}t=L.time();var p=L(d,f,t,t+a,L.time,function(c){var a={},b;for(b in l)l[h](b)&&(a[b]=l[b](c));T.attr(a)},b);T.anims[p.id]=p;p._attrs=c;p._callback=m;k("snap.animcreated."+T.id,p);k.once("mina.finish."+p.id,function(){delete T.anims[p.id];m&&m.call(T)});k.once("mina.stop."+p.id,function(){delete T.anims[p.id]});return T};var T={};c.data=function(c,b){var m=T[this.id]=T[this.id]||
{};if(0==arguments.length)return k("snap.data.get."+this.id,this,m,null),m;if(1==arguments.length){if(a.is(c,"object")){for(var e in c)c[h](e)&&this.data(e,c[e]);return this}k("snap.data.get."+this.id,this,m[c],c);return m[c]}m[c]=b;k("snap.data.set."+this.id,this,b,c);return this};c.removeData=function(c){null==c?T[this.id]={}:T[this.id]&&delete T[this.id][c];return this};c.outerSVG=c.toString=d(1);c.innerSVG=d()})(e.prototype);a.parse=function(c){var a=G.doc.createDocumentFragment(),b=!0,m=G.doc.createElement("div");
c=J(c);c.match(/^\s*<\s*svg(?:\s|>)/)||(c="<svg>"+c+"</svg>",b=!1);m.innerHTML=c;if(c=m.getElementsByTagName("svg")[0])if(b)a=c;else for(;c.firstChild;)a.appendChild(c.firstChild);m.innerHTML=aa;return new l(a)};l.prototype.select=e.prototype.select;l.prototype.selectAll=e.prototype.selectAll;a.fragment=function(){for(var c=Array.prototype.slice.call(arguments,0),b=G.doc.createDocumentFragment(),m=0,e=c.length;m<e;m++){var h=c[m];h.node&&h.node.nodeType&&b.appendChild(h.node);h.nodeType&&b.appendChild(h);
"string"==typeof h&&b.appendChild(a.parse(h).node)}return new l(b)};a._.make=r;a._.wrap=x;s.prototype.el=function(c,a){var b=r(c,this.node);a&&b.attr(a);return b};k.on("snap.util.getattr",function(){var c=k.nt(),c=c.substring(c.lastIndexOf(".")+1),a=c.replace(/[A-Z]/g,function(c){return"-"+c.toLowerCase()});return pa[h](a)?this.node.ownerDocument.defaultView.getComputedStyle(this.node,null).getPropertyValue(a):v(this.node,c)});var pa={"alignment-baseline":0,"baseline-shift":0,clip:0,"clip-path":0,
"clip-rule":0,color:0,"color-interpolation":0,"color-interpolation-filters":0,"color-profile":0,"color-rendering":0,cursor:0,direction:0,display:0,"dominant-baseline":0,"enable-background":0,fill:0,"fill-opacity":0,"fill-rule":0,filter:0,"flood-color":0,"flood-opacity":0,font:0,"font-family":0,"font-size":0,"font-size-adjust":0,"font-stretch":0,"font-style":0,"font-variant":0,"font-weight":0,"glyph-orientation-horizontal":0,"glyph-orientation-vertical":0,"image-rendering":0,kerning:0,"letter-spacing":0,
"lighting-color":0,marker:0,"marker-end":0,"marker-mid":0,"marker-start":0,mask:0,opacity:0,overflow:0,"pointer-events":0,"shape-rendering":0,"stop-color":0,"stop-opacity":0,stroke:0,"stroke-dasharray":0,"stroke-dashoffset":0,"stroke-linecap":0,"stroke-linejoin":0,"stroke-miterlimit":0,"stroke-opacity":0,"stroke-width":0,"text-anchor":0,"text-decoration":0,"text-rendering":0,"unicode-bidi":0,visibility:0,"word-spacing":0,"writing-mode":0};k.on("snap.util.attr",function(c){var a=k.nt(),b={},a=a.substring(a.lastIndexOf(".")+
1);b[a]=c;var m=a.replace(/-(\w)/gi,function(c,a){return a.toUpperCase()}),a=a.replace(/[A-Z]/g,function(c){return"-"+c.toLowerCase()});pa[h](a)?this.node.style[m]=null==c?aa:c:v(this.node,b)});a.ajax=function(c,a,b,m){var e=new XMLHttpRequest,h=V();if(e){if(y(a,"function"))m=b,b=a,a=null;else if(y(a,"object")){var d=[],f;for(f in a)a.hasOwnProperty(f)&&d.push(encodeURIComponent(f)+"="+encodeURIComponent(a[f]));a=d.join("&")}e.open(a?"POST":"GET",c,!0);a&&(e.setRequestHeader("X-Requested-With","XMLHttpRequest"),
e.setRequestHeader("Content-type","application/x-www-form-urlencoded"));b&&(k.once("snap.ajax."+h+".0",b),k.once("snap.ajax."+h+".200",b),k.once("snap.ajax."+h+".304",b));e.onreadystatechange=function(){4==e.readyState&&k("snap.ajax."+h+"."+e.status,m,e)};if(4==e.readyState)return e;e.send(a);return e}};a.load=function(c,b,m){a.ajax(c,function(c){c=a.parse(c.responseText);m?b.call(m,c):b(c)})};a.getElementByPoint=function(c,a){var b,m,e=G.doc.elementFromPoint(c,a);if(G.win.opera&&"svg"==e.tagName){b=
e;m=b.getBoundingClientRect();b=b.ownerDocument;var h=b.body,d=b.documentElement;b=m.top+(g.win.pageYOffset||d.scrollTop||h.scrollTop)-(d.clientTop||h.clientTop||0);m=m.left+(g.win.pageXOffset||d.scrollLeft||h.scrollLeft)-(d.clientLeft||h.clientLeft||0);h=e.createSVGRect();h.x=c-m;h.y=a-b;h.width=h.height=1;b=e.getIntersectionList(h,null);b.length&&(e=b[b.length-1])}return e?x(e):null};a.plugin=function(c){c(a,e,s,G,l)};return G.win.Snap=a}();C.plugin(function(a,k,y,M,A){function w(a,d,f,b,q,e){null==
d&&"[object SVGMatrix]"==z.call(a)?(this.a=a.a,this.b=a.b,this.c=a.c,this.d=a.d,this.e=a.e,this.f=a.f):null!=a?(this.a=+a,this.b=+d,this.c=+f,this.d=+b,this.e=+q,this.f=+e):(this.a=1,this.c=this.b=0,this.d=1,this.f=this.e=0)}var z=Object.prototype.toString,d=String,f=Math;(function(n){function k(a){return a[0]*a[0]+a[1]*a[1]}function p(a){var d=f.sqrt(k(a));a[0]&&(a[0]/=d);a[1]&&(a[1]/=d)}n.add=function(a,d,e,f,n,p){var k=[[],[],[] ],u=[[this.a,this.c,this.e],[this.b,this.d,this.f],[0,0,1] ];d=[[a,
e,n],[d,f,p],[0,0,1] ];a&&a instanceof w&&(d=[[a.a,a.c,a.e],[a.b,a.d,a.f],[0,0,1] ]);for(a=0;3>a;a++)for(e=0;3>e;e++){for(f=n=0;3>f;f++)n+=u[a][f]*d[f][e];k[a][e]=n}this.a=k[0][0];this.b=k[1][0];this.c=k[0][1];this.d=k[1][1];this.e=k[0][2];this.f=k[1][2];return this};n.invert=function(){var a=this.a*this.d-this.b*this.c;return new w(this.d/a,-this.b/a,-this.c/a,this.a/a,(this.c*this.f-this.d*this.e)/a,(this.b*this.e-this.a*this.f)/a)};n.clone=function(){return new w(this.a,this.b,this.c,this.d,this.e,
this.f)};n.translate=function(a,d){return this.add(1,0,0,1,a,d)};n.scale=function(a,d,e,f){null==d&&(d=a);(e||f)&&this.add(1,0,0,1,e,f);this.add(a,0,0,d,0,0);(e||f)&&this.add(1,0,0,1,-e,-f);return this};n.rotate=function(b,d,e){b=a.rad(b);d=d||0;e=e||0;var l=+f.cos(b).toFixed(9);b=+f.sin(b).toFixed(9);this.add(l,b,-b,l,d,e);return this.add(1,0,0,1,-d,-e)};n.x=function(a,d){return a*this.a+d*this.c+this.e};n.y=function(a,d){return a*this.b+d*this.d+this.f};n.get=function(a){return+this[d.fromCharCode(97+
a)].toFixed(4)};n.toString=function(){return"matrix("+[this.get(0),this.get(1),this.get(2),this.get(3),this.get(4),this.get(5)].join()+")"};n.offset=function(){return[this.e.toFixed(4),this.f.toFixed(4)]};n.determinant=function(){return this.a*this.d-this.b*this.c};n.split=function(){var b={};b.dx=this.e;b.dy=this.f;var d=[[this.a,this.c],[this.b,this.d] ];b.scalex=f.sqrt(k(d[0]));p(d[0]);b.shear=d[0][0]*d[1][0]+d[0][1]*d[1][1];d[1]=[d[1][0]-d[0][0]*b.shear,d[1][1]-d[0][1]*b.shear];b.scaley=f.sqrt(k(d[1]));
p(d[1]);b.shear/=b.scaley;0>this.determinant()&&(b.scalex=-b.scalex);var e=-d[0][1],d=d[1][1];0>d?(b.rotate=a.deg(f.acos(d)),0>e&&(b.rotate=360-b.rotate)):b.rotate=a.deg(f.asin(e));b.isSimple=!+b.shear.toFixed(9)&&(b.scalex.toFixed(9)==b.scaley.toFixed(9)||!b.rotate);b.isSuperSimple=!+b.shear.toFixed(9)&&b.scalex.toFixed(9)==b.scaley.toFixed(9)&&!b.rotate;b.noRotation=!+b.shear.toFixed(9)&&!b.rotate;return b};n.toTransformString=function(a){a=a||this.split();if(+a.shear.toFixed(9))return"m"+[this.get(0),
this.get(1),this.get(2),this.get(3),this.get(4),this.get(5)];a.scalex=+a.scalex.toFixed(4);a.scaley=+a.scaley.toFixed(4);a.rotate=+a.rotate.toFixed(4);return(a.dx||a.dy?"t"+[+a.dx.toFixed(4),+a.dy.toFixed(4)]:"")+(1!=a.scalex||1!=a.scaley?"s"+[a.scalex,a.scaley,0,0]:"")+(a.rotate?"r"+[+a.rotate.toFixed(4),0,0]:"")}})(w.prototype);a.Matrix=w;a.matrix=function(a,d,f,b,k,e){return new w(a,d,f,b,k,e)}});C.plugin(function(a,v,y,M,A){function w(h){return function(d){k.stop();d instanceof A&&1==d.node.childNodes.length&&
("radialGradient"==d.node.firstChild.tagName||"linearGradient"==d.node.firstChild.tagName||"pattern"==d.node.firstChild.tagName)&&(d=d.node.firstChild,b(this).appendChild(d),d=u(d));if(d instanceof v)if("radialGradient"==d.type||"linearGradient"==d.type||"pattern"==d.type){d.node.id||e(d.node,{id:d.id});var f=l(d.node.id)}else f=d.attr(h);else f=a.color(d),f.error?(f=a(b(this).ownerSVGElement).gradient(d))?(f.node.id||e(f.node,{id:f.id}),f=l(f.node.id)):f=d:f=r(f);d={};d[h]=f;e(this.node,d);this.node.style[h]=
x}}function z(a){k.stop();a==+a&&(a+="px");this.node.style.fontSize=a}function d(a){var b=[];a=a.childNodes;for(var e=0,f=a.length;e<f;e++){var l=a[e];3==l.nodeType&&b.push(l.nodeValue);"tspan"==l.tagName&&(1==l.childNodes.length&&3==l.firstChild.nodeType?b.push(l.firstChild.nodeValue):b.push(d(l)))}return b}function f(){k.stop();return this.node.style.fontSize}var n=a._.make,u=a._.wrap,p=a.is,b=a._.getSomeDefs,q=/^url\(#?([^)]+)\)$/,e=a._.$,l=a.url,r=String,s=a._.separator,x="";k.on("snap.util.attr.mask",
function(a){if(a instanceof v||a instanceof A){k.stop();a instanceof A&&1==a.node.childNodes.length&&(a=a.node.firstChild,b(this).appendChild(a),a=u(a));if("mask"==a.type)var d=a;else d=n("mask",b(this)),d.node.appendChild(a.node);!d.node.id&&e(d.node,{id:d.id});e(this.node,{mask:l(d.id)})}});(function(a){k.on("snap.util.attr.clip",a);k.on("snap.util.attr.clip-path",a);k.on("snap.util.attr.clipPath",a)})(function(a){if(a instanceof v||a instanceof A){k.stop();if("clipPath"==a.type)var d=a;else d=
n("clipPath",b(this)),d.node.appendChild(a.node),!d.node.id&&e(d.node,{id:d.id});e(this.node,{"clip-path":l(d.id)})}});k.on("snap.util.attr.fill",w("fill"));k.on("snap.util.attr.stroke",w("stroke"));var G=/^([lr])(?:\(([^)]*)\))?(.*)$/i;k.on("snap.util.grad.parse",function(a){a=r(a);var b=a.match(G);if(!b)return null;a=b[1];var e=b[2],b=b[3],e=e.split(/\s*,\s*/).map(function(a){return+a==a?+a:a});1==e.length&&0==e[0]&&(e=[]);b=b.split("-");b=b.map(function(a){a=a.split(":");var b={color:a[0]};a[1]&&
(b.offset=parseFloat(a[1]));return b});return{type:a,params:e,stops:b}});k.on("snap.util.attr.d",function(b){k.stop();p(b,"array")&&p(b[0],"array")&&(b=a.path.toString.call(b));b=r(b);b.match(/[ruo]/i)&&(b=a.path.toAbsolute(b));e(this.node,{d:b})})(-1);k.on("snap.util.attr.#text",function(a){k.stop();a=r(a);for(a=M.doc.createTextNode(a);this.node.firstChild;)this.node.removeChild(this.node.firstChild);this.node.appendChild(a)})(-1);k.on("snap.util.attr.path",function(a){k.stop();this.attr({d:a})})(-1);
k.on("snap.util.attr.class",function(a){k.stop();this.node.className.baseVal=a})(-1);k.on("snap.util.attr.viewBox",function(a){a=p(a,"object")&&"x"in a?[a.x,a.y,a.width,a.height].join(" "):p(a,"array")?a.join(" "):a;e(this.node,{viewBox:a});k.stop()})(-1);k.on("snap.util.attr.transform",function(a){this.transform(a);k.stop()})(-1);k.on("snap.util.attr.r",function(a){"rect"==this.type&&(k.stop(),e(this.node,{rx:a,ry:a}))})(-1);k.on("snap.util.attr.textpath",function(a){k.stop();if("text"==this.type){var d,
f;if(!a&&this.textPath){for(a=this.textPath;a.node.firstChild;)this.node.appendChild(a.node.firstChild);a.remove();delete this.textPath}else if(p(a,"string")?(d=b(this),a=u(d.parentNode).path(a),d.appendChild(a.node),d=a.id,a.attr({id:d})):(a=u(a),a instanceof v&&(d=a.attr("id"),d||(d=a.id,a.attr({id:d})))),d)if(a=this.textPath,f=this.node,a)a.attr({"xlink:href":"#"+d});else{for(a=e("textPath",{"xlink:href":"#"+d});f.firstChild;)a.appendChild(f.firstChild);f.appendChild(a);this.textPath=u(a)}}})(-1);
k.on("snap.util.attr.text",function(a){if("text"==this.type){for(var b=this.node,d=function(a){var b=e("tspan");if(p(a,"array"))for(var f=0;f<a.length;f++)b.appendChild(d(a[f]));else b.appendChild(M.doc.createTextNode(a));b.normalize&&b.normalize();return b};b.firstChild;)b.removeChild(b.firstChild);for(a=d(a);a.firstChild;)b.appendChild(a.firstChild)}k.stop()})(-1);k.on("snap.util.attr.fontSize",z)(-1);k.on("snap.util.attr.font-size",z)(-1);k.on("snap.util.getattr.transform",function(){k.stop();
return this.transform()})(-1);k.on("snap.util.getattr.textpath",function(){k.stop();return this.textPath})(-1);(function(){function b(d){return function(){k.stop();var b=M.doc.defaultView.getComputedStyle(this.node,null).getPropertyValue("marker-"+d);return"none"==b?b:a(M.doc.getElementById(b.match(q)[1]))}}function d(a){return function(b){k.stop();var d="marker"+a.charAt(0).toUpperCase()+a.substring(1);if(""==b||!b)this.node.style[d]="none";else if("marker"==b.type){var f=b.node.id;f||e(b.node,{id:b.id});
this.node.style[d]=l(f)}}}k.on("snap.util.getattr.marker-end",b("end"))(-1);k.on("snap.util.getattr.markerEnd",b("end"))(-1);k.on("snap.util.getattr.marker-start",b("start"))(-1);k.on("snap.util.getattr.markerStart",b("start"))(-1);k.on("snap.util.getattr.marker-mid",b("mid"))(-1);k.on("snap.util.getattr.markerMid",b("mid"))(-1);k.on("snap.util.attr.marker-end",d("end"))(-1);k.on("snap.util.attr.markerEnd",d("end"))(-1);k.on("snap.util.attr.marker-start",d("start"))(-1);k.on("snap.util.attr.markerStart",
d("start"))(-1);k.on("snap.util.attr.marker-mid",d("mid"))(-1);k.on("snap.util.attr.markerMid",d("mid"))(-1)})();k.on("snap.util.getattr.r",function(){if("rect"==this.type&&e(this.node,"rx")==e(this.node,"ry"))return k.stop(),e(this.node,"rx")})(-1);k.on("snap.util.getattr.text",function(){if("text"==this.type||"tspan"==this.type){k.stop();var a=d(this.node);return 1==a.length?a[0]:a}})(-1);k.on("snap.util.getattr.#text",function(){return this.node.textContent})(-1);k.on("snap.util.getattr.viewBox",
function(){k.stop();var b=e(this.node,"viewBox");if(b)return b=b.split(s),a._.box(+b[0],+b[1],+b[2],+b[3])})(-1);k.on("snap.util.getattr.points",function(){var a=e(this.node,"points");k.stop();if(a)return a.split(s)})(-1);k.on("snap.util.getattr.path",function(){var a=e(this.node,"d");k.stop();return a})(-1);k.on("snap.util.getattr.class",function(){return this.node.className.baseVal})(-1);k.on("snap.util.getattr.fontSize",f)(-1);k.on("snap.util.getattr.font-size",f)(-1)});C.plugin(function(a,v,y,
M,A){function w(a){return a}function z(a){return function(b){return+b.toFixed(3)+a}}var d={"+":function(a,b){return a+b},"-":function(a,b){return a-b},"/":function(a,b){return a/b},"*":function(a,b){return a*b}},f=String,n=/[a-z]+$/i,u=/^\s*([+\-\/*])\s*=\s*([\d.eE+\-]+)\s*([^\d\s]+)?\s*$/;k.on("snap.util.attr",function(a){if(a=f(a).match(u)){var b=k.nt(),b=b.substring(b.lastIndexOf(".")+1),q=this.attr(b),e={};k.stop();var l=a[3]||"",r=q.match(n),s=d[a[1] ];r&&r==l?a=s(parseFloat(q),+a[2]):(q=this.asPX(b),
a=s(this.asPX(b),this.asPX(b,a[2]+l)));isNaN(q)||isNaN(a)||(e[b]=a,this.attr(e))}})(-10);k.on("snap.util.equal",function(a,b){var q=f(this.attr(a)||""),e=f(b).match(u);if(e){k.stop();var l=e[3]||"",r=q.match(n),s=d[e[1] ];if(r&&r==l)return{from:parseFloat(q),to:s(parseFloat(q),+e[2]),f:z(r)};q=this.asPX(a);return{from:q,to:s(q,this.asPX(a,e[2]+l)),f:w}}})(-10)});C.plugin(function(a,v,y,M,A){var w=y.prototype,z=a.is;w.rect=function(a,d,k,p,b,q){var e;null==q&&(q=b);z(a,"object")&&"[object Object]"==
a?e=a:null!=a&&(e={x:a,y:d,width:k,height:p},null!=b&&(e.rx=b,e.ry=q));return this.el("rect",e)};w.circle=function(a,d,k){var p;z(a,"object")&&"[object Object]"==a?p=a:null!=a&&(p={cx:a,cy:d,r:k});return this.el("circle",p)};var d=function(){function a(){this.parentNode.removeChild(this)}return function(d,k){var p=M.doc.createElement("img"),b=M.doc.body;p.style.cssText="position:absolute;left:-9999em;top:-9999em";p.onload=function(){k.call(p);p.onload=p.onerror=null;b.removeChild(p)};p.onerror=a;
b.appendChild(p);p.src=d}}();w.image=function(f,n,k,p,b){var q=this.el("image");if(z(f,"object")&&"src"in f)q.attr(f);else if(null!=f){var e={"xlink:href":f,preserveAspectRatio:"none"};null!=n&&null!=k&&(e.x=n,e.y=k);null!=p&&null!=b?(e.width=p,e.height=b):d(f,function(){a._.$(q.node,{width:this.offsetWidth,height:this.offsetHeight})});a._.$(q.node,e)}return q};w.ellipse=function(a,d,k,p){var b;z(a,"object")&&"[object Object]"==a?b=a:null!=a&&(b={cx:a,cy:d,rx:k,ry:p});return this.el("ellipse",b)};
w.path=function(a){var d;z(a,"object")&&!z(a,"array")?d=a:a&&(d={d:a});return this.el("path",d)};w.group=w.g=function(a){var d=this.el("g");1==arguments.length&&a&&!a.type?d.attr(a):arguments.length&&d.add(Array.prototype.slice.call(arguments,0));return d};w.svg=function(a,d,k,p,b,q,e,l){var r={};z(a,"object")&&null==d?r=a:(null!=a&&(r.x=a),null!=d&&(r.y=d),null!=k&&(r.width=k),null!=p&&(r.height=p),null!=b&&null!=q&&null!=e&&null!=l&&(r.viewBox=[b,q,e,l]));return this.el("svg",r)};w.mask=function(a){var d=
this.el("mask");1==arguments.length&&a&&!a.type?d.attr(a):arguments.length&&d.add(Array.prototype.slice.call(arguments,0));return d};w.ptrn=function(a,d,k,p,b,q,e,l){if(z(a,"object"))var r=a;else arguments.length?(r={},null!=a&&(r.x=a),null!=d&&(r.y=d),null!=k&&(r.width=k),null!=p&&(r.height=p),null!=b&&null!=q&&null!=e&&null!=l&&(r.viewBox=[b,q,e,l])):r={patternUnits:"userSpaceOnUse"};return this.el("pattern",r)};w.use=function(a){return null!=a?(make("use",this.node),a instanceof v&&(a.attr("id")||
a.attr({id:ID()}),a=a.attr("id")),this.el("use",{"xlink:href":a})):v.prototype.use.call(this)};w.text=function(a,d,k){var p={};z(a,"object")?p=a:null!=a&&(p={x:a,y:d,text:k||""});return this.el("text",p)};w.line=function(a,d,k,p){var b={};z(a,"object")?b=a:null!=a&&(b={x1:a,x2:k,y1:d,y2:p});return this.el("line",b)};w.polyline=function(a){1<arguments.length&&(a=Array.prototype.slice.call(arguments,0));var d={};z(a,"object")&&!z(a,"array")?d=a:null!=a&&(d={points:a});return this.el("polyline",d)};
w.polygon=function(a){1<arguments.length&&(a=Array.prototype.slice.call(arguments,0));var d={};z(a,"object")&&!z(a,"array")?d=a:null!=a&&(d={points:a});return this.el("polygon",d)};(function(){function d(){return this.selectAll("stop")}function n(b,d){var f=e("stop"),k={offset:+d+"%"};b=a.color(b);k["stop-color"]=b.hex;1>b.opacity&&(k["stop-opacity"]=b.opacity);e(f,k);this.node.appendChild(f);return this}function u(){if("linearGradient"==this.type){var b=e(this.node,"x1")||0,d=e(this.node,"x2")||
1,f=e(this.node,"y1")||0,k=e(this.node,"y2")||0;return a._.box(b,f,math.abs(d-b),math.abs(k-f))}b=this.node.r||0;return a._.box((this.node.cx||0.5)-b,(this.node.cy||0.5)-b,2*b,2*b)}function p(a,d){function f(a,b){for(var d=(b-u)/(a-w),e=w;e<a;e++)h[e].offset=+(+u+d*(e-w)).toFixed(2);w=a;u=b}var n=k("snap.util.grad.parse",null,d).firstDefined(),p;if(!n)return null;n.params.unshift(a);p="l"==n.type.toLowerCase()?b.apply(0,n.params):q.apply(0,n.params);n.type!=n.type.toLowerCase()&&e(p.node,{gradientUnits:"userSpaceOnUse"});
var h=n.stops,n=h.length,u=0,w=0;n--;for(var v=0;v<n;v++)"offset"in h[v]&&f(v,h[v].offset);h[n].offset=h[n].offset||100;f(n,h[n].offset);for(v=0;v<=n;v++){var y=h[v];p.addStop(y.color,y.offset)}return p}function b(b,k,p,q,w){b=a._.make("linearGradient",b);b.stops=d;b.addStop=n;b.getBBox=u;null!=k&&e(b.node,{x1:k,y1:p,x2:q,y2:w});return b}function q(b,k,p,q,w,h){b=a._.make("radialGradient",b);b.stops=d;b.addStop=n;b.getBBox=u;null!=k&&e(b.node,{cx:k,cy:p,r:q});null!=w&&null!=h&&e(b.node,{fx:w,fy:h});
return b}var e=a._.$;w.gradient=function(a){return p(this.defs,a)};w.gradientLinear=function(a,d,e,f){return b(this.defs,a,d,e,f)};w.gradientRadial=function(a,b,d,e,f){return q(this.defs,a,b,d,e,f)};w.toString=function(){var b=this.node.ownerDocument,d=b.createDocumentFragment(),b=b.createElement("div"),e=this.node.cloneNode(!0);d.appendChild(b);b.appendChild(e);a._.$(e,{xmlns:"http://www.w3.org/2000/svg"});b=b.innerHTML;d.removeChild(d.firstChild);return b};w.clear=function(){for(var a=this.node.firstChild,
b;a;)b=a.nextSibling,"defs"!=a.tagName?a.parentNode.removeChild(a):w.clear.call({node:a}),a=b}})()});C.plugin(function(a,k,y,M){function A(a){var b=A.ps=A.ps||{};b[a]?b[a].sleep=100:b[a]={sleep:100};setTimeout(function(){for(var d in b)b[L](d)&&d!=a&&(b[d].sleep--,!b[d].sleep&&delete b[d])});return b[a]}function w(a,b,d,e){null==a&&(a=b=d=e=0);null==b&&(b=a.y,d=a.width,e=a.height,a=a.x);return{x:a,y:b,width:d,w:d,height:e,h:e,x2:a+d,y2:b+e,cx:a+d/2,cy:b+e/2,r1:F.min(d,e)/2,r2:F.max(d,e)/2,r0:F.sqrt(d*
d+e*e)/2,path:s(a,b,d,e),vb:[a,b,d,e].join(" ")}}function z(){return this.join(",").replace(N,"$1")}function d(a){a=C(a);a.toString=z;return a}function f(a,b,d,h,f,k,l,n,p){if(null==p)return e(a,b,d,h,f,k,l,n);if(0>p||e(a,b,d,h,f,k,l,n)<p)p=void 0;else{var q=0.5,O=1-q,s;for(s=e(a,b,d,h,f,k,l,n,O);0.01<Z(s-p);)q/=2,O+=(s<p?1:-1)*q,s=e(a,b,d,h,f,k,l,n,O);p=O}return u(a,b,d,h,f,k,l,n,p)}function n(b,d){function e(a){return+(+a).toFixed(3)}return a._.cacher(function(a,h,l){a instanceof k&&(a=a.attr("d"));
a=I(a);for(var n,p,D,q,O="",s={},c=0,t=0,r=a.length;t<r;t++){D=a[t];if("M"==D[0])n=+D[1],p=+D[2];else{q=f(n,p,D[1],D[2],D[3],D[4],D[5],D[6]);if(c+q>h){if(d&&!s.start){n=f(n,p,D[1],D[2],D[3],D[4],D[5],D[6],h-c);O+=["C"+e(n.start.x),e(n.start.y),e(n.m.x),e(n.m.y),e(n.x),e(n.y)];if(l)return O;s.start=O;O=["M"+e(n.x),e(n.y)+"C"+e(n.n.x),e(n.n.y),e(n.end.x),e(n.end.y),e(D[5]),e(D[6])].join();c+=q;n=+D[5];p=+D[6];continue}if(!b&&!d)return n=f(n,p,D[1],D[2],D[3],D[4],D[5],D[6],h-c)}c+=q;n=+D[5];p=+D[6]}O+=
D.shift()+D}s.end=O;return n=b?c:d?s:u(n,p,D[0],D[1],D[2],D[3],D[4],D[5],1)},null,a._.clone)}function u(a,b,d,e,h,f,k,l,n){var p=1-n,q=ma(p,3),s=ma(p,2),c=n*n,t=c*n,r=q*a+3*s*n*d+3*p*n*n*h+t*k,q=q*b+3*s*n*e+3*p*n*n*f+t*l,s=a+2*n*(d-a)+c*(h-2*d+a),t=b+2*n*(e-b)+c*(f-2*e+b),x=d+2*n*(h-d)+c*(k-2*h+d),c=e+2*n*(f-e)+c*(l-2*f+e);a=p*a+n*d;b=p*b+n*e;h=p*h+n*k;f=p*f+n*l;l=90-180*F.atan2(s-x,t-c)/S;return{x:r,y:q,m:{x:s,y:t},n:{x:x,y:c},start:{x:a,y:b},end:{x:h,y:f},alpha:l}}function p(b,d,e,h,f,n,k,l){a.is(b,
"array")||(b=[b,d,e,h,f,n,k,l]);b=U.apply(null,b);return w(b.min.x,b.min.y,b.max.x-b.min.x,b.max.y-b.min.y)}function b(a,b,d){return b>=a.x&&b<=a.x+a.width&&d>=a.y&&d<=a.y+a.height}function q(a,d){a=w(a);d=w(d);return b(d,a.x,a.y)||b(d,a.x2,a.y)||b(d,a.x,a.y2)||b(d,a.x2,a.y2)||b(a,d.x,d.y)||b(a,d.x2,d.y)||b(a,d.x,d.y2)||b(a,d.x2,d.y2)||(a.x<d.x2&&a.x>d.x||d.x<a.x2&&d.x>a.x)&&(a.y<d.y2&&a.y>d.y||d.y<a.y2&&d.y>a.y)}function e(a,b,d,e,h,f,n,k,l){null==l&&(l=1);l=(1<l?1:0>l?0:l)/2;for(var p=[-0.1252,
0.1252,-0.3678,0.3678,-0.5873,0.5873,-0.7699,0.7699,-0.9041,0.9041,-0.9816,0.9816],q=[0.2491,0.2491,0.2335,0.2335,0.2032,0.2032,0.1601,0.1601,0.1069,0.1069,0.0472,0.0472],s=0,c=0;12>c;c++)var t=l*p[c]+l,r=t*(t*(-3*a+9*d-9*h+3*n)+6*a-12*d+6*h)-3*a+3*d,t=t*(t*(-3*b+9*e-9*f+3*k)+6*b-12*e+6*f)-3*b+3*e,s=s+q[c]*F.sqrt(r*r+t*t);return l*s}function l(a,b,d){a=I(a);b=I(b);for(var h,f,l,n,k,s,r,O,x,c,t=d?0:[],w=0,v=a.length;w<v;w++)if(x=a[w],"M"==x[0])h=k=x[1],f=s=x[2];else{"C"==x[0]?(x=[h,f].concat(x.slice(1)),
h=x[6],f=x[7]):(x=[h,f,h,f,k,s,k,s],h=k,f=s);for(var G=0,y=b.length;G<y;G++)if(c=b[G],"M"==c[0])l=r=c[1],n=O=c[2];else{"C"==c[0]?(c=[l,n].concat(c.slice(1)),l=c[6],n=c[7]):(c=[l,n,l,n,r,O,r,O],l=r,n=O);var z;var K=x,B=c;z=d;var H=p(K),J=p(B);if(q(H,J)){for(var H=e.apply(0,K),J=e.apply(0,B),H=~~(H/8),J=~~(J/8),U=[],A=[],F={},M=z?0:[],P=0;P<H+1;P++){var C=u.apply(0,K.concat(P/H));U.push({x:C.x,y:C.y,t:P/H})}for(P=0;P<J+1;P++)C=u.apply(0,B.concat(P/J)),A.push({x:C.x,y:C.y,t:P/J});for(P=0;P<H;P++)for(K=
0;K<J;K++){var Q=U[P],L=U[P+1],B=A[K],C=A[K+1],N=0.001>Z(L.x-Q.x)?"y":"x",S=0.001>Z(C.x-B.x)?"y":"x",R;R=Q.x;var Y=Q.y,V=L.x,ea=L.y,fa=B.x,ga=B.y,ha=C.x,ia=C.y;if(W(R,V)<X(fa,ha)||X(R,V)>W(fa,ha)||W(Y,ea)<X(ga,ia)||X(Y,ea)>W(ga,ia))R=void 0;else{var $=(R*ea-Y*V)*(fa-ha)-(R-V)*(fa*ia-ga*ha),aa=(R*ea-Y*V)*(ga-ia)-(Y-ea)*(fa*ia-ga*ha),ja=(R-V)*(ga-ia)-(Y-ea)*(fa-ha);if(ja){var $=$/ja,aa=aa/ja,ja=+$.toFixed(2),ba=+aa.toFixed(2);R=ja<+X(R,V).toFixed(2)||ja>+W(R,V).toFixed(2)||ja<+X(fa,ha).toFixed(2)||
ja>+W(fa,ha).toFixed(2)||ba<+X(Y,ea).toFixed(2)||ba>+W(Y,ea).toFixed(2)||ba<+X(ga,ia).toFixed(2)||ba>+W(ga,ia).toFixed(2)?void 0:{x:$,y:aa}}else R=void 0}R&&F[R.x.toFixed(4)]!=R.y.toFixed(4)&&(F[R.x.toFixed(4)]=R.y.toFixed(4),Q=Q.t+Z((R[N]-Q[N])/(L[N]-Q[N]))*(L.t-Q.t),B=B.t+Z((R[S]-B[S])/(C[S]-B[S]))*(C.t-B.t),0<=Q&&1>=Q&&0<=B&&1>=B&&(z?M++:M.push({x:R.x,y:R.y,t1:Q,t2:B})))}z=M}else z=z?0:[];if(d)t+=z;else{H=0;for(J=z.length;H<J;H++)z[H].segment1=w,z[H].segment2=G,z[H].bez1=x,z[H].bez2=c;t=t.concat(z)}}}return t}
function r(a){var b=A(a);if(b.bbox)return C(b.bbox);if(!a)return w();a=I(a);for(var d=0,e=0,h=[],f=[],l,n=0,k=a.length;n<k;n++)l=a[n],"M"==l[0]?(d=l[1],e=l[2],h.push(d),f.push(e)):(d=U(d,e,l[1],l[2],l[3],l[4],l[5],l[6]),h=h.concat(d.min.x,d.max.x),f=f.concat(d.min.y,d.max.y),d=l[5],e=l[6]);a=X.apply(0,h);l=X.apply(0,f);h=W.apply(0,h);f=W.apply(0,f);f=w(a,l,h-a,f-l);b.bbox=C(f);return f}function s(a,b,d,e,h){if(h)return[["M",+a+ +h,b],["l",d-2*h,0],["a",h,h,0,0,1,h,h],["l",0,e-2*h],["a",h,h,0,0,1,
-h,h],["l",2*h-d,0],["a",h,h,0,0,1,-h,-h],["l",0,2*h-e],["a",h,h,0,0,1,h,-h],["z"] ];a=[["M",a,b],["l",d,0],["l",0,e],["l",-d,0],["z"] ];a.toString=z;return a}function x(a,b,d,e,h){null==h&&null==e&&(e=d);a=+a;b=+b;d=+d;e=+e;if(null!=h){var f=Math.PI/180,l=a+d*Math.cos(-e*f);a+=d*Math.cos(-h*f);var n=b+d*Math.sin(-e*f);b+=d*Math.sin(-h*f);d=[["M",l,n],["A",d,d,0,+(180<h-e),0,a,b] ]}else d=[["M",a,b],["m",0,-e],["a",d,e,0,1,1,0,2*e],["a",d,e,0,1,1,0,-2*e],["z"] ];d.toString=z;return d}function G(b){var e=
A(b);if(e.abs)return d(e.abs);Q(b,"array")&&Q(b&&b[0],"array")||(b=a.parsePathString(b));if(!b||!b.length)return[["M",0,0] ];var h=[],f=0,l=0,n=0,k=0,p=0;"M"==b[0][0]&&(f=+b[0][1],l=+b[0][2],n=f,k=l,p++,h[0]=["M",f,l]);for(var q=3==b.length&&"M"==b[0][0]&&"R"==b[1][0].toUpperCase()&&"Z"==b[2][0].toUpperCase(),s,r,w=p,c=b.length;w<c;w++){h.push(s=[]);r=b[w];p=r[0];if(p!=p.toUpperCase())switch(s[0]=p.toUpperCase(),s[0]){case "A":s[1]=r[1];s[2]=r[2];s[3]=r[3];s[4]=r[4];s[5]=r[5];s[6]=+r[6]+f;s[7]=+r[7]+
l;break;case "V":s[1]=+r[1]+l;break;case "H":s[1]=+r[1]+f;break;case "R":for(var t=[f,l].concat(r.slice(1)),u=2,v=t.length;u<v;u++)t[u]=+t[u]+f,t[++u]=+t[u]+l;h.pop();h=h.concat(P(t,q));break;case "O":h.pop();t=x(f,l,r[1],r[2]);t.push(t[0]);h=h.concat(t);break;case "U":h.pop();h=h.concat(x(f,l,r[1],r[2],r[3]));s=["U"].concat(h[h.length-1].slice(-2));break;case "M":n=+r[1]+f,k=+r[2]+l;default:for(u=1,v=r.length;u<v;u++)s[u]=+r[u]+(u%2?f:l)}else if("R"==p)t=[f,l].concat(r.slice(1)),h.pop(),h=h.concat(P(t,
q)),s=["R"].concat(r.slice(-2));else if("O"==p)h.pop(),t=x(f,l,r[1],r[2]),t.push(t[0]),h=h.concat(t);else if("U"==p)h.pop(),h=h.concat(x(f,l,r[1],r[2],r[3])),s=["U"].concat(h[h.length-1].slice(-2));else for(t=0,u=r.length;t<u;t++)s[t]=r[t];p=p.toUpperCase();if("O"!=p)switch(s[0]){case "Z":f=+n;l=+k;break;case "H":f=s[1];break;case "V":l=s[1];break;case "M":n=s[s.length-2],k=s[s.length-1];default:f=s[s.length-2],l=s[s.length-1]}}h.toString=z;e.abs=d(h);return h}function h(a,b,d,e){return[a,b,d,e,d,
e]}function J(a,b,d,e,h,f){var l=1/3,n=2/3;return[l*a+n*d,l*b+n*e,l*h+n*d,l*f+n*e,h,f]}function K(b,d,e,h,f,l,n,k,p,s){var r=120*S/180,q=S/180*(+f||0),c=[],t,x=a._.cacher(function(a,b,c){var d=a*F.cos(c)-b*F.sin(c);a=a*F.sin(c)+b*F.cos(c);return{x:d,y:a}});if(s)v=s[0],t=s[1],l=s[2],u=s[3];else{t=x(b,d,-q);b=t.x;d=t.y;t=x(k,p,-q);k=t.x;p=t.y;F.cos(S/180*f);F.sin(S/180*f);t=(b-k)/2;v=(d-p)/2;u=t*t/(e*e)+v*v/(h*h);1<u&&(u=F.sqrt(u),e*=u,h*=u);var u=e*e,w=h*h,u=(l==n?-1:1)*F.sqrt(Z((u*w-u*v*v-w*t*t)/
(u*v*v+w*t*t)));l=u*e*v/h+(b+k)/2;var u=u*-h*t/e+(d+p)/2,v=F.asin(((d-u)/h).toFixed(9));t=F.asin(((p-u)/h).toFixed(9));v=b<l?S-v:v;t=k<l?S-t:t;0>v&&(v=2*S+v);0>t&&(t=2*S+t);n&&v>t&&(v-=2*S);!n&&t>v&&(t-=2*S)}if(Z(t-v)>r){var c=t,w=k,G=p;t=v+r*(n&&t>v?1:-1);k=l+e*F.cos(t);p=u+h*F.sin(t);c=K(k,p,e,h,f,0,n,w,G,[t,c,l,u])}l=t-v;f=F.cos(v);r=F.sin(v);n=F.cos(t);t=F.sin(t);l=F.tan(l/4);e=4/3*e*l;l*=4/3*h;h=[b,d];b=[b+e*r,d-l*f];d=[k+e*t,p-l*n];k=[k,p];b[0]=2*h[0]-b[0];b[1]=2*h[1]-b[1];if(s)return[b,d,k].concat(c);
c=[b,d,k].concat(c).join().split(",");s=[];k=0;for(p=c.length;k<p;k++)s[k]=k%2?x(c[k-1],c[k],q).y:x(c[k],c[k+1],q).x;return s}function U(a,b,d,e,h,f,l,k){for(var n=[],p=[[],[] ],s,r,c,t,q=0;2>q;++q)0==q?(r=6*a-12*d+6*h,s=-3*a+9*d-9*h+3*l,c=3*d-3*a):(r=6*b-12*e+6*f,s=-3*b+9*e-9*f+3*k,c=3*e-3*b),1E-12>Z(s)?1E-12>Z(r)||(s=-c/r,0<s&&1>s&&n.push(s)):(t=r*r-4*c*s,c=F.sqrt(t),0>t||(t=(-r+c)/(2*s),0<t&&1>t&&n.push(t),s=(-r-c)/(2*s),0<s&&1>s&&n.push(s)));for(r=q=n.length;q--;)s=n[q],c=1-s,p[0][q]=c*c*c*a+3*
c*c*s*d+3*c*s*s*h+s*s*s*l,p[1][q]=c*c*c*b+3*c*c*s*e+3*c*s*s*f+s*s*s*k;p[0][r]=a;p[1][r]=b;p[0][r+1]=l;p[1][r+1]=k;p[0].length=p[1].length=r+2;return{min:{x:X.apply(0,p[0]),y:X.apply(0,p[1])},max:{x:W.apply(0,p[0]),y:W.apply(0,p[1])}}}function I(a,b){var e=!b&&A(a);if(!b&&e.curve)return d(e.curve);var f=G(a),l=b&&G(b),n={x:0,y:0,bx:0,by:0,X:0,Y:0,qx:null,qy:null},k={x:0,y:0,bx:0,by:0,X:0,Y:0,qx:null,qy:null},p=function(a,b,c){if(!a)return["C",b.x,b.y,b.x,b.y,b.x,b.y];a[0]in{T:1,Q:1}||(b.qx=b.qy=null);
switch(a[0]){case "M":b.X=a[1];b.Y=a[2];break;case "A":a=["C"].concat(K.apply(0,[b.x,b.y].concat(a.slice(1))));break;case "S":"C"==c||"S"==c?(c=2*b.x-b.bx,b=2*b.y-b.by):(c=b.x,b=b.y);a=["C",c,b].concat(a.slice(1));break;case "T":"Q"==c||"T"==c?(b.qx=2*b.x-b.qx,b.qy=2*b.y-b.qy):(b.qx=b.x,b.qy=b.y);a=["C"].concat(J(b.x,b.y,b.qx,b.qy,a[1],a[2]));break;case "Q":b.qx=a[1];b.qy=a[2];a=["C"].concat(J(b.x,b.y,a[1],a[2],a[3],a[4]));break;case "L":a=["C"].concat(h(b.x,b.y,a[1],a[2]));break;case "H":a=["C"].concat(h(b.x,
b.y,a[1],b.y));break;case "V":a=["C"].concat(h(b.x,b.y,b.x,a[1]));break;case "Z":a=["C"].concat(h(b.x,b.y,b.X,b.Y))}return a},s=function(a,b){if(7<a[b].length){a[b].shift();for(var c=a[b];c.length;)q[b]="A",l&&(u[b]="A"),a.splice(b++,0,["C"].concat(c.splice(0,6)));a.splice(b,1);v=W(f.length,l&&l.length||0)}},r=function(a,b,c,d,e){a&&b&&"M"==a[e][0]&&"M"!=b[e][0]&&(b.splice(e,0,["M",d.x,d.y]),c.bx=0,c.by=0,c.x=a[e][1],c.y=a[e][2],v=W(f.length,l&&l.length||0))},q=[],u=[],c="",t="",x=0,v=W(f.length,
l&&l.length||0);for(;x<v;x++){f[x]&&(c=f[x][0]);"C"!=c&&(q[x]=c,x&&(t=q[x-1]));f[x]=p(f[x],n,t);"A"!=q[x]&&"C"==c&&(q[x]="C");s(f,x);l&&(l[x]&&(c=l[x][0]),"C"!=c&&(u[x]=c,x&&(t=u[x-1])),l[x]=p(l[x],k,t),"A"!=u[x]&&"C"==c&&(u[x]="C"),s(l,x));r(f,l,n,k,x);r(l,f,k,n,x);var w=f[x],z=l&&l[x],y=w.length,U=l&&z.length;n.x=w[y-2];n.y=w[y-1];n.bx=$(w[y-4])||n.x;n.by=$(w[y-3])||n.y;k.bx=l&&($(z[U-4])||k.x);k.by=l&&($(z[U-3])||k.y);k.x=l&&z[U-2];k.y=l&&z[U-1]}l||(e.curve=d(f));return l?[f,l]:f}function P(a,
b){for(var d=[],e=0,h=a.length;h-2*!b>e;e+=2){var f=[{x:+a[e-2],y:+a[e-1]},{x:+a[e],y:+a[e+1]},{x:+a[e+2],y:+a[e+3]},{x:+a[e+4],y:+a[e+5]}];b?e?h-4==e?f[3]={x:+a[0],y:+a[1]}:h-2==e&&(f[2]={x:+a[0],y:+a[1]},f[3]={x:+a[2],y:+a[3]}):f[0]={x:+a[h-2],y:+a[h-1]}:h-4==e?f[3]=f[2]:e||(f[0]={x:+a[e],y:+a[e+1]});d.push(["C",(-f[0].x+6*f[1].x+f[2].x)/6,(-f[0].y+6*f[1].y+f[2].y)/6,(f[1].x+6*f[2].x-f[3].x)/6,(f[1].y+6*f[2].y-f[3].y)/6,f[2].x,f[2].y])}return d}y=k.prototype;var Q=a.is,C=a._.clone,L="hasOwnProperty",
N=/,?([a-z]),?/gi,$=parseFloat,F=Math,S=F.PI,X=F.min,W=F.max,ma=F.pow,Z=F.abs;M=n(1);var na=n(),ba=n(0,1),V=a._unit2px;a.path=A;a.path.getTotalLength=M;a.path.getPointAtLength=na;a.path.getSubpath=function(a,b,d){if(1E-6>this.getTotalLength(a)-d)return ba(a,b).end;a=ba(a,d,1);return b?ba(a,b).end:a};y.getTotalLength=function(){if(this.node.getTotalLength)return this.node.getTotalLength()};y.getPointAtLength=function(a){return na(this.attr("d"),a)};y.getSubpath=function(b,d){return a.path.getSubpath(this.attr("d"),
b,d)};a._.box=w;a.path.findDotsAtSegment=u;a.path.bezierBBox=p;a.path.isPointInsideBBox=b;a.path.isBBoxIntersect=q;a.path.intersection=function(a,b){return l(a,b)};a.path.intersectionNumber=function(a,b){return l(a,b,1)};a.path.isPointInside=function(a,d,e){var h=r(a);return b(h,d,e)&&1==l(a,[["M",d,e],["H",h.x2+10] ],1)%2};a.path.getBBox=r;a.path.get={path:function(a){return a.attr("path")},circle:function(a){a=V(a);return x(a.cx,a.cy,a.r)},ellipse:function(a){a=V(a);return x(a.cx||0,a.cy||0,a.rx,
a.ry)},rect:function(a){a=V(a);return s(a.x||0,a.y||0,a.width,a.height,a.rx,a.ry)},image:function(a){a=V(a);return s(a.x||0,a.y||0,a.width,a.height)},line:function(a){return"M"+[a.attr("x1")||0,a.attr("y1")||0,a.attr("x2"),a.attr("y2")]},polyline:function(a){return"M"+a.attr("points")},polygon:function(a){return"M"+a.attr("points")+"z"},deflt:function(a){a=a.node.getBBox();return s(a.x,a.y,a.width,a.height)}};a.path.toRelative=function(b){var e=A(b),h=String.prototype.toLowerCase;if(e.rel)return d(e.rel);
a.is(b,"array")&&a.is(b&&b[0],"array")||(b=a.parsePathString(b));var f=[],l=0,n=0,k=0,p=0,s=0;"M"==b[0][0]&&(l=b[0][1],n=b[0][2],k=l,p=n,s++,f.push(["M",l,n]));for(var r=b.length;s<r;s++){var q=f[s]=[],x=b[s];if(x[0]!=h.call(x[0]))switch(q[0]=h.call(x[0]),q[0]){case "a":q[1]=x[1];q[2]=x[2];q[3]=x[3];q[4]=x[4];q[5]=x[5];q[6]=+(x[6]-l).toFixed(3);q[7]=+(x[7]-n).toFixed(3);break;case "v":q[1]=+(x[1]-n).toFixed(3);break;case "m":k=x[1],p=x[2];default:for(var c=1,t=x.length;c<t;c++)q[c]=+(x[c]-(c%2?l:
n)).toFixed(3)}else for(f[s]=[],"m"==x[0]&&(k=x[1]+l,p=x[2]+n),q=0,c=x.length;q<c;q++)f[s][q]=x[q];x=f[s].length;switch(f[s][0]){case "z":l=k;n=p;break;case "h":l+=+f[s][x-1];break;case "v":n+=+f[s][x-1];break;default:l+=+f[s][x-2],n+=+f[s][x-1]}}f.toString=z;e.rel=d(f);return f};a.path.toAbsolute=G;a.path.toCubic=I;a.path.map=function(a,b){if(!b)return a;var d,e,h,f,l,n,k;a=I(a);h=0;for(l=a.length;h<l;h++)for(k=a[h],f=1,n=k.length;f<n;f+=2)d=b.x(k[f],k[f+1]),e=b.y(k[f],k[f+1]),k[f]=d,k[f+1]=e;return a};
a.path.toString=z;a.path.clone=d});C.plugin(function(a,v,y,C){var A=Math.max,w=Math.min,z=function(a){this.items=[];this.bindings={};this.length=0;this.type="set";if(a)for(var f=0,n=a.length;f<n;f++)a[f]&&(this[this.items.length]=this.items[this.items.length]=a[f],this.length++)};v=z.prototype;v.push=function(){for(var a,f,n=0,k=arguments.length;n<k;n++)if(a=arguments[n])f=this.items.length,this[f]=this.items[f]=a,this.length++;return this};v.pop=function(){this.length&&delete this[this.length--];
return this.items.pop()};v.forEach=function(a,f){for(var n=0,k=this.items.length;n<k&&!1!==a.call(f,this.items[n],n);n++);return this};v.animate=function(d,f,n,u){"function"!=typeof n||n.length||(u=n,n=L.linear);d instanceof a._.Animation&&(u=d.callback,n=d.easing,f=n.dur,d=d.attr);var p=arguments;if(a.is(d,"array")&&a.is(p[p.length-1],"array"))var b=!0;var q,e=function(){q?this.b=q:q=this.b},l=0,r=u&&function(){l++==this.length&&u.call(this)};return this.forEach(function(a,l){k.once("snap.animcreated."+
a.id,e);b?p[l]&&a.animate.apply(a,p[l]):a.animate(d,f,n,r)})};v.remove=function(){for(;this.length;)this.pop().remove();return this};v.bind=function(a,f,k){var u={};if("function"==typeof f)this.bindings[a]=f;else{var p=k||a;this.bindings[a]=function(a){u[p]=a;f.attr(u)}}return this};v.attr=function(a){var f={},k;for(k in a)if(this.bindings[k])this.bindings[k](a[k]);else f[k]=a[k];a=0;for(k=this.items.length;a<k;a++)this.items[a].attr(f);return this};v.clear=function(){for(;this.length;)this.pop()};
v.splice=function(a,f,k){a=0>a?A(this.length+a,0):a;f=A(0,w(this.length-a,f));var u=[],p=[],b=[],q;for(q=2;q<arguments.length;q++)b.push(arguments[q]);for(q=0;q<f;q++)p.push(this[a+q]);for(;q<this.length-a;q++)u.push(this[a+q]);var e=b.length;for(q=0;q<e+u.length;q++)this.items[a+q]=this[a+q]=q<e?b[q]:u[q-e];for(q=this.items.length=this.length-=f-e;this[q];)delete this[q++];return new z(p)};v.exclude=function(a){for(var f=0,k=this.length;f<k;f++)if(this[f]==a)return this.splice(f,1),!0;return!1};
v.insertAfter=function(a){for(var f=this.items.length;f--;)this.items[f].insertAfter(a);return this};v.getBBox=function(){for(var a=[],f=[],k=[],u=[],p=this.items.length;p--;)if(!this.items[p].removed){var b=this.items[p].getBBox();a.push(b.x);f.push(b.y);k.push(b.x+b.width);u.push(b.y+b.height)}a=w.apply(0,a);f=w.apply(0,f);k=A.apply(0,k);u=A.apply(0,u);return{x:a,y:f,x2:k,y2:u,width:k-a,height:u-f,cx:a+(k-a)/2,cy:f+(u-f)/2}};v.clone=function(a){a=new z;for(var f=0,k=this.items.length;f<k;f++)a.push(this.items[f].clone());
return a};v.toString=function(){return"Snap\u2018s set"};v.type="set";a.set=function(){var a=new z;arguments.length&&a.push.apply(a,Array.prototype.slice.call(arguments,0));return a}});C.plugin(function(a,v,y,C){function A(a){var b=a[0];switch(b.toLowerCase()){case "t":return[b,0,0];case "m":return[b,1,0,0,1,0,0];case "r":return 4==a.length?[b,0,a[2],a[3] ]:[b,0];case "s":return 5==a.length?[b,1,1,a[3],a[4] ]:3==a.length?[b,1,1]:[b,1]}}function w(b,d,f){d=q(d).replace(/\.{3}|\u2026/g,b);b=a.parseTransformString(b)||
[];d=a.parseTransformString(d)||[];for(var k=Math.max(b.length,d.length),p=[],v=[],h=0,w,z,y,I;h<k;h++){y=b[h]||A(d[h]);I=d[h]||A(y);if(y[0]!=I[0]||"r"==y[0].toLowerCase()&&(y[2]!=I[2]||y[3]!=I[3])||"s"==y[0].toLowerCase()&&(y[3]!=I[3]||y[4]!=I[4])){b=a._.transform2matrix(b,f());d=a._.transform2matrix(d,f());p=[["m",b.a,b.b,b.c,b.d,b.e,b.f] ];v=[["m",d.a,d.b,d.c,d.d,d.e,d.f] ];break}p[h]=[];v[h]=[];w=0;for(z=Math.max(y.length,I.length);w<z;w++)w in y&&(p[h][w]=y[w]),w in I&&(v[h][w]=I[w])}return{from:u(p),
to:u(v),f:n(p)}}function z(a){return a}function d(a){return function(b){return+b.toFixed(3)+a}}function f(b){return a.rgb(b[0],b[1],b[2])}function n(a){var b=0,d,f,k,n,h,p,q=[];d=0;for(f=a.length;d<f;d++){h="[";p=['"'+a[d][0]+'"'];k=1;for(n=a[d].length;k<n;k++)p[k]="val["+b++ +"]";h+=p+"]";q[d]=h}return Function("val","return Snap.path.toString.call(["+q+"])")}function u(a){for(var b=[],d=0,f=a.length;d<f;d++)for(var k=1,n=a[d].length;k<n;k++)b.push(a[d][k]);return b}var p={},b=/[a-z]+$/i,q=String;
p.stroke=p.fill="colour";v.prototype.equal=function(a,b){return k("snap.util.equal",this,a,b).firstDefined()};k.on("snap.util.equal",function(e,k){var r,s;r=q(this.attr(e)||"");var x=this;if(r==+r&&k==+k)return{from:+r,to:+k,f:z};if("colour"==p[e])return r=a.color(r),s=a.color(k),{from:[r.r,r.g,r.b,r.opacity],to:[s.r,s.g,s.b,s.opacity],f:f};if("transform"==e||"gradientTransform"==e||"patternTransform"==e)return k instanceof a.Matrix&&(k=k.toTransformString()),a._.rgTransform.test(k)||(k=a._.svgTransform2string(k)),
w(r,k,function(){return x.getBBox(1)});if("d"==e||"path"==e)return r=a.path.toCubic(r,k),{from:u(r[0]),to:u(r[1]),f:n(r[0])};if("points"==e)return r=q(r).split(a._.separator),s=q(k).split(a._.separator),{from:r,to:s,f:function(a){return a}};aUnit=r.match(b);s=q(k).match(b);return aUnit&&aUnit==s?{from:parseFloat(r),to:parseFloat(k),f:d(aUnit)}:{from:this.asPX(e),to:this.asPX(e,k),f:z}})});C.plugin(function(a,v,y,C){var A=v.prototype,w="createTouch"in C.doc;v="click dblclick mousedown mousemove mouseout mouseover mouseup touchstart touchmove touchend touchcancel".split(" ");
var z={mousedown:"touchstart",mousemove:"touchmove",mouseup:"touchend"},d=function(a,b){var d="y"==a?"scrollTop":"scrollLeft",e=b&&b.node?b.node.ownerDocument:C.doc;return e[d in e.documentElement?"documentElement":"body"][d]},f=function(){this.returnValue=!1},n=function(){return this.originalEvent.preventDefault()},u=function(){this.cancelBubble=!0},p=function(){return this.originalEvent.stopPropagation()},b=function(){if(C.doc.addEventListener)return function(a,b,e,f){var k=w&&z[b]?z[b]:b,l=function(k){var l=
d("y",f),q=d("x",f);if(w&&z.hasOwnProperty(b))for(var r=0,u=k.targetTouches&&k.targetTouches.length;r<u;r++)if(k.targetTouches[r].target==a||a.contains(k.targetTouches[r].target)){u=k;k=k.targetTouches[r];k.originalEvent=u;k.preventDefault=n;k.stopPropagation=p;break}return e.call(f,k,k.clientX+q,k.clientY+l)};b!==k&&a.addEventListener(b,l,!1);a.addEventListener(k,l,!1);return function(){b!==k&&a.removeEventListener(b,l,!1);a.removeEventListener(k,l,!1);return!0}};if(C.doc.attachEvent)return function(a,
b,e,h){var k=function(a){a=a||h.node.ownerDocument.window.event;var b=d("y",h),k=d("x",h),k=a.clientX+k,b=a.clientY+b;a.preventDefault=a.preventDefault||f;a.stopPropagation=a.stopPropagation||u;return e.call(h,a,k,b)};a.attachEvent("on"+b,k);return function(){a.detachEvent("on"+b,k);return!0}}}(),q=[],e=function(a){for(var b=a.clientX,e=a.clientY,f=d("y"),l=d("x"),n,p=q.length;p--;){n=q[p];if(w)for(var r=a.touches&&a.touches.length,u;r--;){if(u=a.touches[r],u.identifier==n.el._drag.id||n.el.node.contains(u.target)){b=
u.clientX;e=u.clientY;(a.originalEvent?a.originalEvent:a).preventDefault();break}}else a.preventDefault();b+=l;e+=f;k("snap.drag.move."+n.el.id,n.move_scope||n.el,b-n.el._drag.x,e-n.el._drag.y,b,e,a)}},l=function(b){a.unmousemove(e).unmouseup(l);for(var d=q.length,f;d--;)f=q[d],f.el._drag={},k("snap.drag.end."+f.el.id,f.end_scope||f.start_scope||f.move_scope||f.el,b);q=[]};for(y=v.length;y--;)(function(d){a[d]=A[d]=function(e,f){a.is(e,"function")&&(this.events=this.events||[],this.events.push({name:d,
f:e,unbind:b(this.node||document,d,e,f||this)}));return this};a["un"+d]=A["un"+d]=function(a){for(var b=this.events||[],e=b.length;e--;)if(b[e].name==d&&(b[e].f==a||!a)){b[e].unbind();b.splice(e,1);!b.length&&delete this.events;break}return this}})(v[y]);A.hover=function(a,b,d,e){return this.mouseover(a,d).mouseout(b,e||d)};A.unhover=function(a,b){return this.unmouseover(a).unmouseout(b)};var r=[];A.drag=function(b,d,f,h,n,p){function u(r,v,w){(r.originalEvent||r).preventDefault();this._drag.x=v;
this._drag.y=w;this._drag.id=r.identifier;!q.length&&a.mousemove(e).mouseup(l);q.push({el:this,move_scope:h,start_scope:n,end_scope:p});d&&k.on("snap.drag.start."+this.id,d);b&&k.on("snap.drag.move."+this.id,b);f&&k.on("snap.drag.end."+this.id,f);k("snap.drag.start."+this.id,n||h||this,v,w,r)}if(!arguments.length){var v;return this.drag(function(a,b){this.attr({transform:v+(v?"T":"t")+[a,b]})},function(){v=this.transform().local})}this._drag={};r.push({el:this,start:u});this.mousedown(u);return this};
A.undrag=function(){for(var b=r.length;b--;)r[b].el==this&&(this.unmousedown(r[b].start),r.splice(b,1),k.unbind("snap.drag.*."+this.id));!r.length&&a.unmousemove(e).unmouseup(l);return this}});C.plugin(function(a,v,y,C){y=y.prototype;var A=/^\s*url\((.+)\)/,w=String,z=a._.$;a.filter={};y.filter=function(d){var f=this;"svg"!=f.type&&(f=f.paper);d=a.parse(w(d));var k=a._.id(),u=z("filter");z(u,{id:k,filterUnits:"userSpaceOnUse"});u.appendChild(d.node);f.defs.appendChild(u);return new v(u)};k.on("snap.util.getattr.filter",
function(){k.stop();var d=z(this.node,"filter");if(d)return(d=w(d).match(A))&&a.select(d[1])});k.on("snap.util.attr.filter",function(d){if(d instanceof v&&"filter"==d.type){k.stop();var f=d.node.id;f||(z(d.node,{id:d.id}),f=d.id);z(this.node,{filter:a.url(f)})}d&&"none"!=d||(k.stop(),this.node.removeAttribute("filter"))});a.filter.blur=function(d,f){null==d&&(d=2);return a.format('<feGaussianBlur stdDeviation="{def}"/>',{def:null==f?d:[d,f]})};a.filter.blur.toString=function(){return this()};a.filter.shadow=
function(d,f,k,u,p){"string"==typeof k&&(p=u=k,k=4);"string"!=typeof u&&(p=u,u="#000");null==k&&(k=4);null==p&&(p=1);null==d&&(d=0,f=2);null==f&&(f=d);u=a.color(u||"#000");return a.format('<feGaussianBlur in="SourceAlpha" stdDeviation="{blur}"/><feOffset dx="{dx}" dy="{dy}" result="offsetblur"/><feFlood flood-color="{color}"/><feComposite in2="offsetblur" operator="in"/><feComponentTransfer><feFuncA type="linear" slope="{opacity}"/></feComponentTransfer><feMerge><feMergeNode/><feMergeNode in="SourceGraphic"/></feMerge>',
{color:u,dx:d,dy:f,blur:k,opacity:p})};a.filter.shadow.toString=function(){return this()};a.filter.grayscale=function(d){null==d&&(d=1);return a.format('<feColorMatrix type="matrix" values="{a} {b} {c} 0 0 {d} {e} {f} 0 0 {g} {b} {h} 0 0 0 0 0 1 0"/>',{a:0.2126+0.7874*(1-d),b:0.7152-0.7152*(1-d),c:0.0722-0.0722*(1-d),d:0.2126-0.2126*(1-d),e:0.7152+0.2848*(1-d),f:0.0722-0.0722*(1-d),g:0.2126-0.2126*(1-d),h:0.0722+0.9278*(1-d)})};a.filter.grayscale.toString=function(){return this()};a.filter.sepia=
function(d){null==d&&(d=1);return a.format('<feColorMatrix type="matrix" values="{a} {b} {c} 0 0 {d} {e} {f} 0 0 {g} {h} {i} 0 0 0 0 0 1 0"/>',{a:0.393+0.607*(1-d),b:0.769-0.769*(1-d),c:0.189-0.189*(1-d),d:0.349-0.349*(1-d),e:0.686+0.314*(1-d),f:0.168-0.168*(1-d),g:0.272-0.272*(1-d),h:0.534-0.534*(1-d),i:0.131+0.869*(1-d)})};a.filter.sepia.toString=function(){return this()};a.filter.saturate=function(d){null==d&&(d=1);return a.format('<feColorMatrix type="saturate" values="{amount}"/>',{amount:1-
d})};a.filter.saturate.toString=function(){return this()};a.filter.hueRotate=function(d){return a.format('<feColorMatrix type="hueRotate" values="{angle}"/>',{angle:d||0})};a.filter.hueRotate.toString=function(){return this()};a.filter.invert=function(d){null==d&&(d=1);return a.format('<feComponentTransfer><feFuncR type="table" tableValues="{amount} {amount2}"/><feFuncG type="table" tableValues="{amount} {amount2}"/><feFuncB type="table" tableValues="{amount} {amount2}"/></feComponentTransfer>',{amount:d,
amount2:1-d})};a.filter.invert.toString=function(){return this()};a.filter.brightness=function(d){null==d&&(d=1);return a.format('<feComponentTransfer><feFuncR type="linear" slope="{amount}"/><feFuncG type="linear" slope="{amount}"/><feFuncB type="linear" slope="{amount}"/></feComponentTransfer>',{amount:d})};a.filter.brightness.toString=function(){return this()};a.filter.contrast=function(d){null==d&&(d=1);return a.format('<feComponentTransfer><feFuncR type="linear" slope="{amount}" intercept="{amount2}"/><feFuncG type="linear" slope="{amount}" intercept="{amount2}"/><feFuncB type="linear" slope="{amount}" intercept="{amount2}"/></feComponentTransfer>',
{amount:d,amount2:0.5-d/2})};a.filter.contrast.toString=function(){return this()}});return C});

]]> </script>
<script> <![CDATA[

(function (glob, factory) {
    // AMD support
    if (typeof define === "function" && define.amd) {
        // Define as an anonymous module
        define("Gadfly", ["Snap.svg"], function (Snap) {
            return factory(Snap);
        });
    } else {
        // Browser globals (glob is window)
        // Snap adds itself to window
        glob.Gadfly = factory(glob.Snap);
    }
}(this, function (Snap) {

var Gadfly = {};

// Get an x/y coordinate value in pixels
var xPX = function(fig, x) {
    var client_box = fig.node.getBoundingClientRect();
    return x * fig.node.viewBox.baseVal.width / client_box.width;
};

var yPX = function(fig, y) {
    var client_box = fig.node.getBoundingClientRect();
    return y * fig.node.viewBox.baseVal.height / client_box.height;
};


Snap.plugin(function (Snap, Element, Paper, global) {
    // Traverse upwards from a snap element to find and return the first
    // note with the "plotroot" class.
    Element.prototype.plotroot = function () {
        var element = this;
        while (!element.hasClass("plotroot") && element.parent() != null) {
            element = element.parent();
        }
        return element;
    };

    Element.prototype.svgroot = function () {
        var element = this;
        while (element.node.nodeName != "svg" && element.parent() != null) {
            element = element.parent();
        }
        return element;
    };

    Element.prototype.plotbounds = function () {
        var root = this.plotroot()
        var bbox = root.select(".guide.background").node.getBBox();
        return {
            x0: bbox.x,
            x1: bbox.x + bbox.width,
            y0: bbox.y,
            y1: bbox.y + bbox.height
        };
    };

    Element.prototype.plotcenter = function () {
        var root = this.plotroot()
        var bbox = root.select(".guide.background").node.getBBox();
        return {
            x: bbox.x + bbox.width / 2,
            y: bbox.y + bbox.height / 2
        };
    };

    // Emulate IE style mouseenter/mouseleave events, since Microsoft always
    // does everything right.
    // See: http://www.dynamic-tools.net/toolbox/isMouseLeaveOrEnter/
    var events = ["mouseenter", "mouseleave"];

    for (i in events) {
        (function (event_name) {
            var event_name = events[i];
            Element.prototype[event_name] = function (fn, scope) {
                if (Snap.is(fn, "function")) {
                    var fn2 = function (event) {
                        if (event.type != "mouseover" && event.type != "mouseout") {
                            return;
                        }

                        var reltg = event.relatedTarget ? event.relatedTarget :
                            event.type == "mouseout" ? event.toElement : event.fromElement;
                        while (reltg && reltg != this.node) reltg = reltg.parentNode;

                        if (reltg != this.node) {
                            return fn.apply(this, event);
                        }
                    };

                    if (event_name == "mouseenter") {
                        this.mouseover(fn2, scope);
                    } else {
                        this.mouseout(fn2, scope);
                    }
                }
                return this;
            };
        })(events[i]);
    }


    Element.prototype.mousewheel = function (fn, scope) {
        if (Snap.is(fn, "function")) {
            var el = this;
            var fn2 = function (event) {
                fn.apply(el, [event]);
            };
        }

        this.node.addEventListener(
            /Firefox/i.test(navigator.userAgent) ? "DOMMouseScroll" : "mousewheel",
            fn2);

        return this;
    };


    // Snap's attr function can be too slow for things like panning/zooming.
    // This is a function to directly update element attributes without going
    // through eve.
    Element.prototype.attribute = function(key, val) {
        if (val === undefined) {
            return this.node.getAttribute(key);
        } else {
            this.node.setAttribute(key, val);
            return this;
        }
    };

    Element.prototype.init_gadfly = function() {
        this.mouseenter(Gadfly.plot_mouseover)
            .mouseleave(Gadfly.plot_mouseout)
            .dblclick(Gadfly.plot_dblclick)
            .mousewheel(Gadfly.guide_background_scroll)
            .drag(Gadfly.guide_background_drag_onmove,
                  Gadfly.guide_background_drag_onstart,
                  Gadfly.guide_background_drag_onend);
        this.mouseenter(function (event) {
            init_pan_zoom(this.plotroot());
        });
        return this;
    };
});


// When the plot is moused over, emphasize the grid lines.
Gadfly.plot_mouseover = function(event) {
    var root = this.plotroot();

    var keyboard_zoom = function(event) {
        if (event.which == 187) { // plus
            increase_zoom_by_position(root, 0.1, true);
        } else if (event.which == 189) { // minus
            increase_zoom_by_position(root, -0.1, true);
        }
    };
    root.data("keyboard_zoom", keyboard_zoom);
    window.addEventListener("keyup", keyboard_zoom);

    var xgridlines = root.select(".xgridlines"),
        ygridlines = root.select(".ygridlines");

    xgridlines.data("unfocused_strokedash",
                    xgridlines.attribute("stroke-dasharray").replace(/(\d)(,|$)/g, "$1mm$2"));
    ygridlines.data("unfocused_strokedash",
                    ygridlines.attribute("stroke-dasharray").replace(/(\d)(,|$)/g, "$1mm$2"));

    // emphasize grid lines
    var destcolor = root.data("focused_xgrid_color");
    xgridlines.attribute("stroke-dasharray", "none")
              .selectAll("path")
              .animate({stroke: destcolor}, 250);

    destcolor = root.data("focused_ygrid_color");
    ygridlines.attribute("stroke-dasharray", "none")
              .selectAll("path")
              .animate({stroke: destcolor}, 250);

    // reveal zoom slider
    root.select(".zoomslider")
        .animate({opacity: 1.0}, 250);
};

// Reset pan and zoom on double click
Gadfly.plot_dblclick = function(event) {
  set_plot_pan_zoom(this.plotroot(), 0.0, 0.0, 1.0);
};

// Unemphasize grid lines on mouse out.
Gadfly.plot_mouseout = function(event) {
    var root = this.plotroot();

    window.removeEventListener("keyup", root.data("keyboard_zoom"));
    root.data("keyboard_zoom", undefined);

    var xgridlines = root.select(".xgridlines"),
        ygridlines = root.select(".ygridlines");

    var destcolor = root.data("unfocused_xgrid_color");

    xgridlines.attribute("stroke-dasharray", xgridlines.data("unfocused_strokedash"))
              .selectAll("path")
              .animate({stroke: destcolor}, 250);

    destcolor = root.data("unfocused_ygrid_color");
    ygridlines.attribute("stroke-dasharray", ygridlines.data("unfocused_strokedash"))
              .selectAll("path")
              .animate({stroke: destcolor}, 250);

    // hide zoom slider
    root.select(".zoomslider")
        .animate({opacity: 0.0}, 250);
};


var set_geometry_transform = function(root, tx, ty, scale) {
    var xscalable = root.hasClass("xscalable"),
        yscalable = root.hasClass("yscalable");

    var old_scale = root.data("scale");

    var xscale = xscalable ? scale : 1.0,
        yscale = yscalable ? scale : 1.0;

    tx = xscalable ? tx : 0.0;
    ty = yscalable ? ty : 0.0;

    var t = new Snap.Matrix().translate(tx, ty).scale(xscale, yscale);

    root.selectAll(".geometry, image")
        .forEach(function (element, i) {
            element.transform(t);
        });

    bounds = root.plotbounds();

    if (yscalable) {
        var xfixed_t = new Snap.Matrix().translate(0, ty).scale(1.0, yscale);
        root.selectAll(".xfixed")
            .forEach(function (element, i) {
                element.transform(xfixed_t);
            });

        root.select(".ylabels")
            .transform(xfixed_t)
            .selectAll("text")
            .forEach(function (element, i) {
                if (element.attribute("gadfly:inscale") == "true") {
                    var cx = element.asPX("x"),
                        cy = element.asPX("y");
                    var st = element.data("static_transform");
                    unscale_t = new Snap.Matrix();
                    unscale_t.scale(1, 1/scale, cx, cy).add(st);
                    element.transform(unscale_t);

                    var y = cy * scale + ty;
                    element.attr("visibility",
                        bounds.y0 <= y && y <= bounds.y1 ? "visible" : "hidden");
                }
            });
    }

    if (xscalable) {
        var yfixed_t = new Snap.Matrix().translate(tx, 0).scale(xscale, 1.0);
        var xtrans = new Snap.Matrix().translate(tx, 0);
        root.selectAll(".yfixed")
            .forEach(function (element, i) {
                element.transform(yfixed_t);
            });

        root.select(".xlabels")
            .transform(yfixed_t)
            .selectAll("text")
            .forEach(function (element, i) {
                if (element.attribute("gadfly:inscale") == "true") {
                    var cx = element.asPX("x"),
                        cy = element.asPX("y");
                    var st = element.data("static_transform");
                    unscale_t = new Snap.Matrix();
                    unscale_t.scale(1/scale, 1, cx, cy).add(st);

                    element.transform(unscale_t);

                    var x = cx * scale + tx;
                    element.attr("visibility",
                        bounds.x0 <= x && x <= bounds.x1 ? "visible" : "hidden");
                    }
            });
    }

    // we must unscale anything that is scale invariance: widths, raiduses, etc.
    var size_attribs = ["font-size"];
    var unscaled_selection = ".geometry, .geometry *";
    if (xscalable) {
        size_attribs.push("rx");
        unscaled_selection += ", .xgridlines";
    }
    if (yscalable) {
        size_attribs.push("ry");
        unscaled_selection += ", .ygridlines";
    }

    root.selectAll(unscaled_selection)
        .forEach(function (element, i) {
            // circle need special help
            if (element.node.nodeName == "circle") {
                var cx = element.attribute("cx"),
                    cy = element.attribute("cy");
                unscale_t = new Snap.Matrix().scale(1/xscale, 1/yscale,
                                                        cx, cy);
                element.transform(unscale_t);
                return;
            }

            for (i in size_attribs) {
                var key = size_attribs[i];
                var val = parseFloat(element.attribute(key));
                if (val !== undefined && val != 0 && !isNaN(val)) {
                    element.attribute(key, val * old_scale / scale);
                }
            }
        });
};


// Find the most appropriate tick scale and update label visibility.
var update_tickscale = function(root, scale, axis) {
    if (!root.hasClass(axis + "scalable")) return;

    var tickscales = root.data(axis + "tickscales");
    var best_tickscale = 1.0;
    var best_tickscale_dist = Infinity;
    for (tickscale in tickscales) {
        var dist = Math.abs(Math.log(tickscale) - Math.log(scale));
        if (dist < best_tickscale_dist) {
            best_tickscale_dist = dist;
            best_tickscale = tickscale;
        }
    }

    if (best_tickscale != root.data(axis + "tickscale")) {
        root.data(axis + "tickscale", best_tickscale);
        var mark_inscale_gridlines = function (element, i) {
            var inscale = element.attr("gadfly:scale") == best_tickscale;
            element.attribute("gadfly:inscale", inscale);
            element.attr("visibility", inscale ? "visible" : "hidden");
        };

        var mark_inscale_labels = function (element, i) {
            var inscale = element.attr("gadfly:scale") == best_tickscale;
            element.attribute("gadfly:inscale", inscale);
            element.attr("visibility", inscale ? "visible" : "hidden");
        };

        root.select("." + axis + "gridlines").selectAll("path").forEach(mark_inscale_gridlines);
        root.select("." + axis + "labels").selectAll("text").forEach(mark_inscale_labels);
    }
};


var set_plot_pan_zoom = function(root, tx, ty, scale) {
    var old_scale = root.data("scale");
    var bounds = root.plotbounds();

    var width = bounds.x1 - bounds.x0,
        height = bounds.y1 - bounds.y0;

    // compute the viewport derived from tx, ty, and scale
    var x_min = -width * scale - (scale * width - width),
        x_max = width * scale,
        y_min = -height * scale - (scale * height - height),
        y_max = height * scale;

    var x0 = bounds.x0 - scale * bounds.x0,
        y0 = bounds.y0 - scale * bounds.y0;

    var tx = Math.max(Math.min(tx - x0, x_max), x_min),
        ty = Math.max(Math.min(ty - y0, y_max), y_min);

    tx += x0;
    ty += y0;

    // when the scale change, we may need to alter which set of
    // ticks is being displayed
    if (scale != old_scale) {
        update_tickscale(root, scale, "x");
        update_tickscale(root, scale, "y");
    }

    set_geometry_transform(root, tx, ty, scale);

    root.data("scale", scale);
    root.data("tx", tx);
    root.data("ty", ty);
};


var scale_centered_translation = function(root, scale) {
    var bounds = root.plotbounds();

    var width = bounds.x1 - bounds.x0,
        height = bounds.y1 - bounds.y0;

    var tx0 = root.data("tx"),
        ty0 = root.data("ty");

    var scale0 = root.data("scale");

    // how off from center the current view is
    var xoff = tx0 - (bounds.x0 * (1 - scale0) + (width * (1 - scale0)) / 2),
        yoff = ty0 - (bounds.y0 * (1 - scale0) + (height * (1 - scale0)) / 2);

    // rescale offsets
    xoff = xoff * scale / scale0;
    yoff = yoff * scale / scale0;

    // adjust for the panel position being scaled
    var x_edge_adjust = bounds.x0 * (1 - scale),
        y_edge_adjust = bounds.y0 * (1 - scale);

    return {
        x: xoff + x_edge_adjust + (width - width * scale) / 2,
        y: yoff + y_edge_adjust + (height - height * scale) / 2
    };
};


// Initialize data for panning zooming if it isn't already.
var init_pan_zoom = function(root) {
    if (root.data("zoompan-ready")) {
        return;
    }

    // The non-scaling-stroke trick. Rather than try to correct for the
    // stroke-width when zooming, we force it to a fixed value.
    var px_per_mm = root.node.getCTM().a;

    // Drag events report deltas in pixels, which we'd like to convert to
    // millimeters.
    root.data("px_per_mm", px_per_mm);

    root.selectAll("path")
        .forEach(function (element, i) {
        sw = element.asPX("stroke-width") * px_per_mm;
        if (sw > 0) {
            element.attribute("stroke-width", sw);
            element.attribute("vector-effect", "non-scaling-stroke");
        }
    });

    // Store ticks labels original tranformation
    root.selectAll(".xlabels > text, .ylabels > text")
        .forEach(function (element, i) {
            var lm = element.transform().localMatrix;
            element.data("static_transform",
                new Snap.Matrix(lm.a, lm.b, lm.c, lm.d, lm.e, lm.f));
        });

    var xgridlines = root.select(".xgridlines");
    var ygridlines = root.select(".ygridlines");
    var xlabels = root.select(".xlabels");
    var ylabels = root.select(".ylabels");

    if (root.data("tx") === undefined) root.data("tx", 0);
    if (root.data("ty") === undefined) root.data("ty", 0);
    if (root.data("scale") === undefined) root.data("scale", 1.0);
    if (root.data("xtickscales") === undefined) {

        // index all the tick scales that are listed
        var xtickscales = {};
        var ytickscales = {};
        var add_x_tick_scales = function (element, i) {
            xtickscales[element.attribute("gadfly:scale")] = true;
        };
        var add_y_tick_scales = function (element, i) {
            ytickscales[element.attribute("gadfly:scale")] = true;
        };

        if (xgridlines) xgridlines.selectAll("path").forEach(add_x_tick_scales);
        if (ygridlines) ygridlines.selectAll("path").forEach(add_y_tick_scales);
        if (xlabels) xlabels.selectAll("text").forEach(add_x_tick_scales);
        if (ylabels) ylabels.selectAll("text").forEach(add_y_tick_scales);

        root.data("xtickscales", xtickscales);
        root.data("ytickscales", ytickscales);
        root.data("xtickscale", 1.0);
    }

    var min_scale = 1.0, max_scale = 1.0;
    for (scale in xtickscales) {
        min_scale = Math.min(min_scale, scale);
        max_scale = Math.max(max_scale, scale);
    }
    for (scale in ytickscales) {
        min_scale = Math.min(min_scale, scale);
        max_scale = Math.max(max_scale, scale);
    }
    root.data("min_scale", min_scale);
    root.data("max_scale", max_scale);

    // store the original positions of labels
    if (xlabels) {
        xlabels.selectAll("text")
               .forEach(function (element, i) {
                   element.data("x", element.asPX("x"));
               });
    }

    if (ylabels) {
        ylabels.selectAll("text")
               .forEach(function (element, i) {
                   element.data("y", element.asPX("y"));
               });
    }

    // mark grid lines and ticks as in or out of scale.
    var mark_inscale = function (element, i) {
        element.attribute("gadfly:inscale", element.attribute("gadfly:scale") == 1.0);
    };

    if (xgridlines) xgridlines.selectAll("path").forEach(mark_inscale);
    if (ygridlines) ygridlines.selectAll("path").forEach(mark_inscale);
    if (xlabels) xlabels.selectAll("text").forEach(mark_inscale);
    if (ylabels) ylabels.selectAll("text").forEach(mark_inscale);

    // figure out the upper ond lower bounds on panning using the maximum
    // and minum grid lines
    var bounds = root.plotbounds();
    var pan_bounds = {
        x0: 0.0,
        y0: 0.0,
        x1: 0.0,
        y1: 0.0
    };

    if (xgridlines) {
        xgridlines
            .selectAll("path")
            .forEach(function (element, i) {
                if (element.attribute("gadfly:inscale") == "true") {
                    var bbox = element.node.getBBox();
                    if (bounds.x1 - bbox.x < pan_bounds.x0) {
                        pan_bounds.x0 = bounds.x1 - bbox.x;
                    }
                    if (bounds.x0 - bbox.x > pan_bounds.x1) {
                        pan_bounds.x1 = bounds.x0 - bbox.x;
                    }
                    element.attr("visibility", "visible");
                }
            });
    }

    if (ygridlines) {
        ygridlines
            .selectAll("path")
            .forEach(function (element, i) {
                if (element.attribute("gadfly:inscale") == "true") {
                    var bbox = element.node.getBBox();
                    if (bounds.y1 - bbox.y < pan_bounds.y0) {
                        pan_bounds.y0 = bounds.y1 - bbox.y;
                    }
                    if (bounds.y0 - bbox.y > pan_bounds.y1) {
                        pan_bounds.y1 = bounds.y0 - bbox.y;
                    }
                    element.attr("visibility", "visible");
                }
            });
    }

    // nudge these values a little
    pan_bounds.x0 -= 5;
    pan_bounds.x1 += 5;
    pan_bounds.y0 -= 5;
    pan_bounds.y1 += 5;
    root.data("pan_bounds", pan_bounds);

    root.data("zoompan-ready", true)
};


// drag actions, i.e. zooming and panning
var pan_action = {
    start: function(root, x, y, event) {
        root.data("dx", 0);
        root.data("dy", 0);
        root.data("tx0", root.data("tx"));
        root.data("ty0", root.data("ty"));
    },
    update: function(root, dx, dy, x, y, event) {
        var px_per_mm = root.data("px_per_mm");
        dx /= px_per_mm;
        dy /= px_per_mm;

        var tx0 = root.data("tx"),
            ty0 = root.data("ty");

        var dx0 = root.data("dx"),
            dy0 = root.data("dy");

        root.data("dx", dx);
        root.data("dy", dy);

        dx = dx - dx0;
        dy = dy - dy0;

        var tx = tx0 + dx,
            ty = ty0 + dy;

        set_plot_pan_zoom(root, tx, ty, root.data("scale"));
    },
    end: function(root, event) {

    },
    cancel: function(root) {
        set_plot_pan_zoom(root, root.data("tx0"), root.data("ty0"), root.data("scale"));
    }
};

var zoom_box;
var zoom_action = {
    start: function(root, x, y, event) {
        var bounds = root.plotbounds();
        var width = bounds.x1 - bounds.x0,
            height = bounds.y1 - bounds.y0;
        var ratio = width / height;
        var xscalable = root.hasClass("xscalable"),
            yscalable = root.hasClass("yscalable");
        var px_per_mm = root.data("px_per_mm");
        x = xscalable ? x / px_per_mm : bounds.x0;
        y = yscalable ? y / px_per_mm : bounds.y0;
        var w = xscalable ? 0 : width;
        var h = yscalable ? 0 : height;
        zoom_box = root.rect(x, y, w, h).attr({
            "fill": "#000",
            "opacity": 0.25
        });
        zoom_box.data("ratio", ratio);
    },
    update: function(root, dx, dy, x, y, event) {
        var xscalable = root.hasClass("xscalable"),
            yscalable = root.hasClass("yscalable");
        var px_per_mm = root.data("px_per_mm");
        var bounds = root.plotbounds();
        if (yscalable) {
            y /= px_per_mm;
            y = Math.max(bounds.y0, y);
            y = Math.min(bounds.y1, y);
        } else {
            y = bounds.y1;
        }
        if (xscalable) {
            x /= px_per_mm;
            x = Math.max(bounds.x0, x);
            x = Math.min(bounds.x1, x);
        } else {
            x = bounds.x1;
        }

        dx = x - zoom_box.attr("x");
        dy = y - zoom_box.attr("y");
        if (xscalable && yscalable) {
            var ratio = zoom_box.data("ratio");
            var width = Math.min(Math.abs(dx), ratio * Math.abs(dy));
            var height = Math.min(Math.abs(dy), Math.abs(dx) / ratio);
            dx = width * dx / Math.abs(dx);
            dy = height * dy / Math.abs(dy);
        }
        var xoffset = 0,
            yoffset = 0;
        if (dx < 0) {
            xoffset = dx;
            dx = -1 * dx;
        }
        if (dy < 0) {
            yoffset = dy;
            dy = -1 * dy;
        }
        if (isNaN(dy)) {
            dy = 0.0;
        }
        if (isNaN(dx)) {
            dx = 0.0;
        }
        zoom_box.transform("T" + xoffset + "," + yoffset);
        zoom_box.attr("width", dx);
        zoom_box.attr("height", dy);
    },
    end: function(root, event) {
        var xscalable = root.hasClass("xscalable"),
            yscalable = root.hasClass("yscalable");
        var zoom_bounds = zoom_box.getBBox();
        if (zoom_bounds.width * zoom_bounds.height <= 0) {
            return;
        }
        var plot_bounds = root.plotbounds();
        var zoom_factor = 1.0;
        if (yscalable) {
            zoom_factor = (plot_bounds.y1 - plot_bounds.y0) / zoom_bounds.height;
        } else {
            zoom_factor = (plot_bounds.x1 - plot_bounds.x0) / zoom_bounds.width;
        }
        var tx = (root.data("tx") - zoom_bounds.x) * zoom_factor + plot_bounds.x0,
            ty = (root.data("ty") - zoom_bounds.y) * zoom_factor + plot_bounds.y0;
        set_plot_pan_zoom(root, tx, ty, root.data("scale") * zoom_factor);
        zoom_box.remove();
    },
    cancel: function(root) {
        zoom_box.remove();
    }
};


Gadfly.guide_background_drag_onstart = function(x, y, event) {
    var root = this.plotroot();
    var scalable = root.hasClass("xscalable") || root.hasClass("yscalable");
    var zoomable = !event.altKey && !event.ctrlKey && event.shiftKey && scalable;
    var panable = !event.altKey && !event.ctrlKey && !event.shiftKey && scalable;
    var drag_action = zoomable ? zoom_action :
                      panable  ? pan_action :
                                 undefined;
    root.data("drag_action", drag_action);
    if (drag_action) {
        var cancel_drag_action = function(event) {
            if (event.which == 27) { // esc key
                drag_action.cancel(root);
                root.data("drag_action", undefined);
            }
        };
        window.addEventListener("keyup", cancel_drag_action);
        root.data("cancel_drag_action", cancel_drag_action);
        drag_action.start(root, x, y, event);
    }
};


Gadfly.guide_background_drag_onmove = function(dx, dy, x, y, event) {
    var root = this.plotroot();
    var drag_action = root.data("drag_action");
    if (drag_action) {
        drag_action.update(root, dx, dy, x, y, event);
    }
};


Gadfly.guide_background_drag_onend = function(event) {
    var root = this.plotroot();
    window.removeEventListener("keyup", root.data("cancel_drag_action"));
    root.data("cancel_drag_action", undefined);
    var drag_action = root.data("drag_action");
    if (drag_action) {
        drag_action.end(root, event);
    }
    root.data("drag_action", undefined);
};


Gadfly.guide_background_scroll = function(event) {
    if (event.shiftKey) {
        increase_zoom_by_position(this.plotroot(), 0.001 * event.wheelDelta);
        event.preventDefault();
    }
};


Gadfly.zoomslider_button_mouseover = function(event) {
    this.select(".button_logo")
         .animate({fill: this.data("mouseover_color")}, 100);
};


Gadfly.zoomslider_button_mouseout = function(event) {
     this.select(".button_logo")
         .animate({fill: this.data("mouseout_color")}, 100);
};


Gadfly.zoomslider_zoomout_click = function(event) {
    increase_zoom_by_position(this.plotroot(), -0.1, true);
};


Gadfly.zoomslider_zoomin_click = function(event) {
    increase_zoom_by_position(this.plotroot(), 0.1, true);
};


Gadfly.zoomslider_track_click = function(event) {
    // TODO
};


// Map slider position x to scale y using the function y = a*exp(b*x)+c.
// The constants a, b, and c are solved using the constraint that the function
// should go through the points (0; min_scale), (0.5; 1), and (1; max_scale).
var scale_from_slider_position = function(position, min_scale, max_scale) {
    var a = (1 - 2 * min_scale + min_scale * min_scale) / (min_scale + max_scale - 2),
        b = 2 * Math.log((max_scale - 1) / (1 - min_scale)),
        c = (min_scale * max_scale - 1) / (min_scale + max_scale - 2);
    return a * Math.exp(b * position) + c;
}

// inverse of scale_from_slider_position
var slider_position_from_scale = function(scale, min_scale, max_scale) {
    var a = (1 - 2 * min_scale + min_scale * min_scale) / (min_scale + max_scale - 2),
        b = 2 * Math.log((max_scale - 1) / (1 - min_scale)),
        c = (min_scale * max_scale - 1) / (min_scale + max_scale - 2);
    return 1 / b * Math.log((scale - c) / a);
}

var increase_zoom_by_position = function(root, delta_position, animate) {
    var scale = root.data("scale"),
        min_scale = root.data("min_scale"),
        max_scale = root.data("max_scale");
    var position = slider_position_from_scale(scale, min_scale, max_scale);
    position += delta_position;
    scale = scale_from_slider_position(position, min_scale, max_scale);
    set_zoom(root, scale, animate);
}

var set_zoom = function(root, scale, animate) {
    var min_scale = root.data("min_scale"),
        max_scale = root.data("max_scale"),
        old_scale = root.data("scale");
    var new_scale = Math.max(min_scale, Math.min(scale, max_scale));
    if (animate) {
        Snap.animate(
            old_scale,
            new_scale,
            function (new_scale) {
                update_plot_scale(root, new_scale);
            },
            200);
    } else {
        update_plot_scale(root, new_scale);
    }
}


var update_plot_scale = function(root, new_scale) {
    var trans = scale_centered_translation(root, new_scale);
    set_plot_pan_zoom(root, trans.x, trans.y, new_scale);

    root.selectAll(".zoomslider_thumb")
        .forEach(function (element, i) {
            var min_pos = element.data("min_pos"),
                max_pos = element.data("max_pos"),
                min_scale = root.data("min_scale"),
                max_scale = root.data("max_scale");
            var xmid = (min_pos + max_pos) / 2;
            var xpos = slider_position_from_scale(new_scale, min_scale, max_scale);
            element.transform(new Snap.Matrix().translate(
                Math.max(min_pos, Math.min(
                         max_pos, min_pos + (max_pos - min_pos) * xpos)) - xmid, 0));
    });
};


Gadfly.zoomslider_thumb_dragmove = function(dx, dy, x, y, event) {
    var root = this.plotroot();
    var min_pos = this.data("min_pos"),
        max_pos = this.data("max_pos"),
        min_scale = root.data("min_scale"),
        max_scale = root.data("max_scale"),
        old_scale = root.data("old_scale");

    var px_per_mm = root.data("px_per_mm");
    dx /= px_per_mm;
    dy /= px_per_mm;

    var xmid = (min_pos + max_pos) / 2;
    var xpos = slider_position_from_scale(old_scale, min_scale, max_scale) +
                   dx / (max_pos - min_pos);

    // compute the new scale
    var new_scale = scale_from_slider_position(xpos, min_scale, max_scale);
    new_scale = Math.min(max_scale, Math.max(min_scale, new_scale));

    update_plot_scale(root, new_scale);
    event.stopPropagation();
};


Gadfly.zoomslider_thumb_dragstart = function(x, y, event) {
    this.animate({fill: this.data("mouseover_color")}, 100);
    var root = this.plotroot();

    // keep track of what the scale was when we started dragging
    root.data("old_scale", root.data("scale"));
    event.stopPropagation();
};


Gadfly.zoomslider_thumb_dragend = function(event) {
    this.animate({fill: this.data("mouseout_color")}, 100);
    event.stopPropagation();
};


var toggle_color_class = function(root, color_class, ison) {
    var guides = root.selectAll(".guide." + color_class + ",.guide ." + color_class);
    var geoms = root.selectAll(".geometry." + color_class + ",.geometry ." + color_class);
    if (ison) {
        guides.animate({opacity: 0.5}, 250);
        geoms.animate({opacity: 0.0}, 250);
    } else {
        guides.animate({opacity: 1.0}, 250);
        geoms.animate({opacity: 1.0}, 250);
    }
};


Gadfly.colorkey_swatch_click = function(event) {
    var root = this.plotroot();
    var color_class = this.data("color_class");

    if (event.shiftKey) {
        root.selectAll(".colorkey text")
            .forEach(function (element) {
                var other_color_class = element.data("color_class");
                if (other_color_class != color_class) {
                    toggle_color_class(root, other_color_class,
                                       element.attr("opacity") == 1.0);
                }
            });
    } else {
        toggle_color_class(root, color_class, this.attr("opacity") == 1.0);
    }
};


return Gadfly;

}));


//@ sourceURL=gadfly.js

(function (glob, factory) {
    // AMD support
      if (typeof require === "function" && typeof define === "function" && define.amd) {
        require(["Snap.svg", "Gadfly"], function (Snap, Gadfly) {
            factory(Snap, Gadfly);
        });
      } else {
          factory(glob.Snap, glob.Gadfly);
      }
})(window, function (Snap, Gadfly) {
    var fig = Snap("#img-a09943b4");
fig.select("#img-a09943b4-4")
   .init_gadfly();
fig.select("#img-a09943b4-6")
   .plotroot().data("unfocused_ygrid_color", "#D0D0E0")
;
fig.select("#img-a09943b4-6")
   .plotroot().data("focused_ygrid_color", "#A0A0A0")
;
fig.select("#img-a09943b4-7")
   .plotroot().data("unfocused_xgrid_color", "#D0D0E0")
;
fig.select("#img-a09943b4-7")
   .plotroot().data("focused_xgrid_color", "#A0A0A0")
;
fig.select("#img-a09943b4-18")
   .data("mouseover_color", "#CD5C5C")
;
fig.select("#img-a09943b4-18")
   .data("mouseout_color", "#6A6A6A")
;
fig.select("#img-a09943b4-18")
   .click(Gadfly.zoomslider_zoomin_click)
.mouseenter(Gadfly.zoomslider_button_mouseover)
.mouseleave(Gadfly.zoomslider_button_mouseout)
;
fig.select("#img-a09943b4-20")
   .data("max_pos", 120.42)
;
fig.select("#img-a09943b4-20")
   .data("min_pos", 103.42)
;
fig.select("#img-a09943b4-20")
   .click(Gadfly.zoomslider_track_click);
fig.select("#img-a09943b4-21")
   .data("max_pos", 120.42)
;
fig.select("#img-a09943b4-21")
   .data("min_pos", 103.42)
;
fig.select("#img-a09943b4-21")
   .data("mouseover_color", "#CD5C5C")
;
fig.select("#img-a09943b4-21")
   .data("mouseout_color", "#6A6A6A")
;
fig.select("#img-a09943b4-21")
   .drag(Gadfly.zoomslider_thumb_dragmove,
     Gadfly.zoomslider_thumb_dragstart,
     Gadfly.zoomslider_thumb_dragend)
;
fig.select("#img-a09943b4-22")
   .data("mouseover_color", "#CD5C5C")
;
fig.select("#img-a09943b4-22")
   .data("mouseout_color", "#6A6A6A")
;
fig.select("#img-a09943b4-22")
   .click(Gadfly.zoomslider_zoomout_click)
.mouseenter(Gadfly.zoomslider_button_mouseover)
.mouseleave(Gadfly.zoomslider_button_mouseout)
;
    });
]]> </script>
</svg>




```R
julia_library("Plots")
```


```R
julia_command("pyplot()")
```


Plots.PyPlotBackend()



```R
julia_command("Plots.plot(Plots.fakedata(50,5),w=3)")
```


<img src="data:image/png;base64,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" />



```R
julia_command("Plots.plot(sin,(x->begin sin(2x) end),0,2pi,line=4,leg=false,fill=(0,:orange))")
```


<img src="data:image/png;base64,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" />



```R

```