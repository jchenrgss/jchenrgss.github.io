<html>
<head>
<title>CSI Project - Scenario 2</title>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}});
</script>
<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_CHTML">
</script>
</head>
<body>
<img src="https://upload.wikimedia.org/wikipedia/commons/5/54/D3A1_Akagi.jpg" alt="D3A from the carrier Akagi">
$\textbf{Introduction and Evidence}$
<p>
The Aichi D3A "Val" was the primary dive bomber of the IJN, and has sank more Allied warships than any other Axis aircraft, despite being considered obsolete at the start of the war. D3As started their bombing runs at a medium altitude, dove at the target at approximately 70 degrees, released their bombs at a low altitude, and then pulled out of their dive. By releasing their bombs in a steep dive, the path of the bomb was greatly simplified and allowed for significantly greater accuracy. Here, I will consider the scenario that D3As dive bombed the Arizona, causing it to sink.
</p>
<p>
The D3As at Pearl Harbor were equipped with a single 250-kg bomb or two 60-kg bombs.<br><br>
Wing area: 34.9 m^2<br>
Loaded weight (without bombs): 3,400 kg<br>
Loaded weight: 3,650 kg<br>
Engine power: 1,070 hp<br>
Maximum speed: 389 km/h = 108.0556 m/s<br>
Range: 1,472 km = 1,472,000 m<br>
Bombing altitude: 400 m<br>
Drag coefficient: 0.025<br>
$\text{ }\\$
</p>
$\textbf{Velocity Vectors}$
<p>
Text
$\text{ }\\$
</p>
$\textbf{Projectile Motion Calculations}$
<p>
$\textbf{1.}\text{ If a D3A dives from 1000 m to 400 m with its engine off, determine its final vertical velocity.}\\$
$\text{Assume no air resistance.}$
$$\overrightarrow{v_f}^2=\overrightarrow{v_i}^2+2\overrightarrow{a_y}\Delta\overrightarrow{d_y}=0+2\overrightarrow{a_y}\Delta\overrightarrow{d_y}$$
$$\overrightarrow{v_f}=\sqrt{2(9.8\text{ m/s}^2)(1000\text{ m}-400\text{ m})}$$
$$\overrightarrow{v_f}=108.4435\text{ m/s}=110\text{ m/s [Downward]}$$
$\textbf{2.}\text{ Determine the D3A's acceleration due to air resistance.}$
$$\overrightarrow{F_{\text{net}_y}}=\overrightarrow{F_g}-\overrightarrow{F_D}=m\overrightarrow{a_y}$$
$$\overrightarrow{F_g}=mg=(3650\text{ kg})(9.8\text{ m/s}^2)$$
$$\overrightarrow{F_g}=35,770\text{ N}=36,00\text{ N [Downward]}$$
$$\overrightarrow{F_D}=\frac{1}{2}\rho u^2C_DA=\frac{1}{2}(1.225\text{ kg/m}^3)(108.4435\text{ m/s})^2(0.025)(34.9\text{ m}^2)$$
$$\overrightarrow{F_D}=(0.6125\text{ kg/m}^3)(11,760\text{ m}^2/\text{s}^2)(0.8725\text{ m}^2)$$
$$\overrightarrow{F_D}=6284.6175\text{ N}=6300\text{ N [Upward]}$$
$$m\overrightarrow{a_y}=35,770\text{ N}-6284.6175\text{ N}=29,485.3825\text{ N}$$
$$\overrightarrow{a_y}=\frac{29,485.3825\text{ N}}{3650\text{ kg}}$$
$$\overrightarrow{a_y}=8.0782\text{ m/s}^2=8.1\text{ m/s}^2\text{ [Downward]}$$
$\textbf{3.}\text{ If a D3A dives from 1000 m to 400 m with its engine off, determine its final vertical velocity.}\\$
$\text{Assume air resistance.}$
$$\overrightarrow{v_f}^2=\overrightarrow{v_i}^2+2\overrightarrow{a_y}\Delta\overrightarrow{d_y}=0+2\overrightarrow{a_y}\Delta\overrightarrow{d_y}$$
$$\overrightarrow{v_f}=\sqrt{2(8.0782\text{ m/s}^2)(1000\text{ m}-400\text{ m})}$$
$$\overrightarrow{v_f}=98.4572\text{ m/s}=98\text{ m/s [Downward]}$$
$\textbf{4.}\text{ Determine the final velocity of the bomb and the impact angle.}$
$\text{Assume no air resistance for the bomb since it is relatively small.}$
$$\overrightarrow{v_{f_y}}^2=\overrightarrow{v_{i_y}}^2+2\overrightarrow{a_y}\Delta\overrightarrow{d_y}\text{, }\overrightarrow{v_{f_y}}=\sqrt{\overrightarrow{v_{i_y}}^2+2\overrightarrow{a_y}\Delta\overrightarrow{d_y}}$$
$$\overrightarrow{v_{f_y}}=\sqrt{(98.4572\text{ m/s})^2+2(9.8\text{ m/s}^2)(400\text{ m})}$$
$$\overrightarrow{v_{f_y}}=132.4153\text{ m/s}=130\text{ m/s [Downward]}$$
$$\overrightarrow{v_{f_x}}=\overrightarrow{v_f}\sin\theta=(108.0556\text{ m/s})(\sin20^\circ)$$
$$\overrightarrow{v_{f_x}}=36.9572\text{ m/s}=37\text{ m/s [Forward]}$$
$$|\overrightarrow{v_f}|=\sqrt{\overrightarrow{v_{f_x}}^2+\overrightarrow{v_{f_y}}^2}=\sqrt{36.9572\text{ m/s}^2+(132.4153\text{ m/s})^2}$$
$$|\overrightarrow{v_f}|=137.4760\text{ m/s}=140\text{ m/s}$$
$$\theta=\tan^{-1}(\frac{\overrightarrow{v_{f_x}}}{\overrightarrow{v_{f_y}}})=\tan^{-1}(\frac{36.9572\text{ m/s}}{132.4153\text{ m/s}})$$
$$\theta=15.5944^\circ=16^\circ\text{ (Impact angle is }74^\circ\text{)}$$
$\text{ }\\$
</p>
$\textbf{Motion Graphs}$
<p>
Text
$\text{ }\\$
</p>
$\textbf{System of Forces and Newton's Third Law of Motion}$
<p>
Text
$\text{ }\\$
</p>
$\textbf{Centripetal Force}$
<p>
$\textbf{1.}\text{ After performing its bombing run, a D3A performs an Immelmann turn to change direction.}\\\text{Assuming that the radius of its turn is 100 m, what must be the minimum velocity of the plane}\\\text{as it completes the maneuver?}$
$$\overrightarrow{F_{\text{net}}}=\overrightarrow{F_c}=\overrightarrow{F_g}$$
$$\frac{m\overrightarrow{v}^2}{r}=mg\text{, }\overrightarrow{v}^2=rg$$
$$\overrightarrow{v}=\sqrt{(100\text{ m})(9.8\text{ m/s}^2)}$$
$$\overrightarrow{v}=31.3050\text{ m/s}=31\text{ m/s}$$
$\text{ }\\$
</p>
$\textbf{Conclusion}$
<p>
Based on the evidence that a bomb was dropped from 3,000 m (falling for 26 seconds and travelling a horizontal distance of approximately 2,600 m), it is likely that this is how Arizona was sunk. In addition to this, the final impact angle and velocity would be appropriate for penetrating the deck of the ship and hitting the ammunition magazines underneath the gun turret. Although this scenario does seem similar and nearly identical to the first (Nagato), it is more realistic, because from an evidence-based standpoint, more than half a hundred B5Ns were spotted in the sky, allowing for a much greater chance of hitting the ship.
$\text{ }\\$
</p>
<a href="https://jchenrgss.github.io/index.html">Return to main page</a><br>
</body>
</html>
