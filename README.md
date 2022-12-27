# keras_exercise
## Calculate new img size
W = original img size  <br>
ex. img size = 128 * 128 , original img size = 128 <br>
ks = kernal size <br>
ex. kernal size = 5x5x5 , ks = 5  <br>
S = strid step<br>
pad = padding step<br><hr>

<h3> If padding mode = 'valid' <h3>
<p><b><h4> new img size = (W - ks + 1) / S <h4><b><p>
<h3> If padding mode = 'same' <h3>
<p><b><h4> new img size = W / S <h4><b><p>
