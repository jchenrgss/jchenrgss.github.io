<html>
<head>
<title>CSI Project - Scenario 1</title>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}});
</script>
<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_CHTML">
</script>
</head>
<body>
<img src="https://upload.wikimedia.org/wikipedia/commons/b/b9/Nagato05cropped.jpg" alt="Nagato in 1927">
$\textbf{Introduction and Evidence}$
<p>
Nagato, a super-dreadnought battleship built for the Imperial Japanese Navy, served as the flagship of the attack on Pearl Harbor. Here, I will consider the scenario that Nagato used its primary armament to attack and sink the Arizona.
</p>
<p>
The primary armament of Nagato consists of four 41-cm/45 3rd Year Type naval guns, initially developed for coast defence mountings.<br><br>
<img src="https://upload.wikimedia.org/wikipedia/commons/7/78/16-inch_gun_from_battleship_Mutsu_outside_the_Yamato_Museum_in_October_2008.JPG" alt="41-cm naval gun at the Yamato Museum in 2008"><br><br>
Overall length: 18.84 m<br>
Bore length: 18.294 m<br>
Mass: 102,000 kg<br>
Elevation capacity: -2/+35 degrees<br>
Rate of fire: 2.5 rpm<br>
Shell mass: 1,020 kg<br>
Muzzle velocity: 790 m/s<br>
Effective firing range: 30,200 m<br>
Maximum firing range: 38,400 m<br><br>
Boeing B-17 Flying Fortress maximum range: 3,219 km = 3,219,000 m<br>
Douglas SBD Dauntless maximum range: 1,795 km = 1,795,000 m<br>
$\text{ }\\$
</p>
$\textbf{Velocity Vectors}$
<p>
<img src="https://i.imgur.com/voYlFN9.png" alt="sc1_sym_nar.png"><br><br>
<img src="https://i.imgur.com/fjChrTR.png" alt="sc1_sym_are.png"><br><br>
$\text{ }\\$
</p>
$\textbf{Projectile Motion Calculations (Symmetric Parabola)}$
<p>
$\textbf{1.}\text{ Determine the maximum range of the shell, assuming no air resistance. Use the range equation:}$
$$\Delta\overrightarrow{d_x}=\frac{\overrightarrow{v_i}^2\sin2\theta}{g}$$
$\text{Use }Nagato\text{'s maximum gun elevation, because as }\theta\text{ increases, }\sin2\theta\text{ increases to approximately }0.57.\\\text{An angle closer to 45 degrees would allow the ship to stay as far away as possible as to avoid return fire.}$
$$\Delta\overrightarrow{d_x}=\frac{(790\text{ m/s})^2(\sin2(35^\circ))}{(9.8\text{ m/s}^2)}$$
$$\Delta\overrightarrow{d_x}=\frac{(624,100\text{ m}^2\text{s}^2)(\sin70^\circ)}{9.8\text{ m/s}^2}$$
$$\Delta\overrightarrow{d_x}=59,843.0780\text{ m}=60,000\text{ m [Forward]}$$
$59,843.08\text{ m is much greater than }38,400\text{ m, so air resistance cannot be ignored.}\\$
$\textbf{2.}\text{ Determine the maximum range of the shell, assuming air resistance. Use the drag equation:}$
$$\overrightarrow{F_D}=\frac{1}{2}\rho u^2C_DA$$
$F_D\text{ is the drag force, }\rho\text{ is the density of air, }u\text{ is the airspeed, }C_D\text{ is the drag coefficient, and }A\text{ is the}\\\text{reference area. Assume }\rho=1.225\text{ kg/m}^3\text{ and }C_D=0.10.$
$$A=\pi r^2=\pi(\frac{d}{2})^2\text{, where }d=0.41\text{ m (gun caliber)}$$
$$A=\pi(\frac{0.41\text{ m}}{2})^2=0.1320\text{ m}^2$$
$\text{Therefore,}$
$$\overrightarrow{F_D}=\frac{1}{2}(1.225\text{ kg/m}^3)(790\text{ m/s})^2(0.10)(0.1320\text{ m}^2)$$
$$\overrightarrow{F_D}=\frac{1}{2}(1.225\text{ kg/m}^3)(624,100\text{ m}^2/\text{s}^2)(0.0132\text{ m}^2)$$
$$\overrightarrow{F_D}=5046.8206\text{ N}=5000\text{ N [Backward]}$$
$\text{Next, calculate the acceleration due to air resistance using Newton's second law of motion.}$
$$\overrightarrow{F_D}=ma_D=(800\text{ kg})(a_D)$$
$$a_D=\frac{5046.8206\text{ N}}{800\text{ kg}}=6.3085\text{ m/s}^2=6.3\text{ m/s}^2\text{ [Backward]}$$
$\text{In order to find the horizontal displacement, first find time using the y-component.}$
$$\overrightarrow{v_{i_y}}=\overrightarrow{v_i}\sin35^\circ=(790\text{ m/s})(\sin35^\circ)$$
$$\overrightarrow{v_{i_y}}=453.1254\text{ m/s}$$
$$\Delta\overrightarrow{d_y}=\overrightarrow{v_{i_y}}\Delta t\,+\,\frac{1}{2}\overrightarrow{a_y}\Delta t^2$$
$$0=(453.1254\text{ m/s})\Delta t\,+\,(-4.9\text{ m/s}^2)\Delta t^2$$
$$0=-4.9\text{ m/s}^2\Delta t(\Delta t\,-\,92.4746\text{ s})$$
$$\Delta t=0\text { s, }92.4746\text { s}$$
$\text{x-component:}$
$$\overrightarrow{v_{i_x}}=\overrightarrow{v_i}\cos35^\circ=(790\text{ m/s})(\cos35^\circ)$$
$$\overrightarrow{v_{i_x}}=647.1301\text{ m/s}$$
$$\Delta\overrightarrow{d_x}=\overrightarrow{v_{i_x}}\Delta t\,+\,\frac{1}{2}\overrightarrow{a_x}\Delta t^2$$
$$\Delta\overrightarrow{d_x}=(647.1301\text{ m/s})(92.4746\text{ s})\,+\,\frac{1}{2}(-6.3073\text{ m/s}^2)(92.4746\text{ s})^2$$
$$\Delta\overrightarrow{d_x}=59,843.0780\text{ m}\,-\,26,973.8236\text{ m}$$
$$\Delta\overrightarrow{d_x}=32,869.3544\text{ m}=33,000\text{ m [Forward]}$$
$\textbf{3.}\text{ Determine the final velocity of the shell and its angle of impact.}\\$
$\text{Because }\Delta\overrightarrow{d_y}=0\text{, }\overrightarrow{v_{f_y}}=\overrightarrow{-v_{i_y}}\text{, assuming no air resistance. However, }\overrightarrow{v_{f_x}}\ne\overrightarrow{v_{i_x}}\text{ due to air resistance.}\\\text{Use kinematic equation 4 to calculate }\overrightarrow{v_{f_x}}\text{ (why not).}$
$$\Delta\overrightarrow{d_x}=\overrightarrow{v_{f_x}}\Delta t\,-\,\frac{1}{2}\overrightarrow{a_x}\Delta t^2$$
$$32,874.4977\text{ m}=\overrightarrow{v_{f_x}}(92.4746\text{ s})\,-\,\frac{1}{2}(-6.3073\text{ m/s}^2)(92.4746\text{ s})^2$$
$$32,874.4977\text{ m}=\overrightarrow{v_{f_x}}(92.4746\text{ s})\,+\,26,973.8236\text{ m}$$
$$\overrightarrow{v_{f_x}}=\frac{5895.4308\text{ m}}{92.4746\text{ s}}$$
$$\overrightarrow{v_{f_x}}=63.7519\text{ m/s}=64\text{ m/s [Forward]}$$
$$|\overrightarrow{v_f}|=\sqrt{\overrightarrow{v_{f_x}}^2\,+\,\overrightarrow{v_{f_y}}^2}=\sqrt{(63.8651\text{ m/s})^2\,+\,(-453.1254\text{ m/s})^2}$$
$$|\overrightarrow{v_f}|=\sqrt{4078.7510\text{ m}^2\text{s}^2\,+\,205,322.6281\text{ m}^2\text{s}^2}$$
$$|\overrightarrow{v_f}|=457.5882\text{ m/s}=460\text{ m/s}$$
$\text{To calculate angle:}$
$$\theta=\tan^{-1}(\frac{|\overrightarrow{v_{f_y}}|}{|\overrightarrow{v_{f_x}}|})=\tan^{-1}(\frac{453.1254\text{ m/s}}{63.8651\text{ m/s}})$$
$$\theta=81.9914^\circ=82^\circ$$
$\text{ }\\$
</p>
$\textbf{Motion Graphs}$
<p>
Images go here
$\text{ }\\$
</p>
$\textbf{Conclusion}$
<p>
Based on the evidence that Nagato probably would have fired her guns from a range of 33,000 km away (which is approximately her maximum effective firing range), and that the shell would have come down on Arizona at about an 82 degree angle, it is possible that the shell penetrated the deck of Arizona and hit the second turret's ammunition magazine, causing it to explode. From a physics perspective, it would not be possible to determine if Nagato was the culprit in the destruction of Arizona, because the projectile motion calculations are similar to those in the third scenario. From an evidence-based perspective, the same conclusion can be reached because the 41-cm shell fired by Nagato's main guns were the same shell dropped by B5N bombers. Thus, the impact markings would be the same.
</p>
<img src="https://i.imgur.com/3ffyxna.jpg" alt="Diagram of USS Arizona">
<p>
However, from a strategic perspective, it would make no sense to have a flagship battleship so close to an enemy airfield. At the time of the attack, B-17 bombers were parked at Pearl Harbor's airfield, and SBD dive bombers were stationed on the US carrier Enterprise (location unknown to the Japanese). Both of these aircraft have maximum ranges significantly greater than Nagato's maximum firing range, so military strategists would not have risked placing the Nagato so close to the battlefield. Thus, the scenario that Nagato sunk the Arizona can be eliminated.
$\text{ }\\$
</p>
<a href="https://jchenrgss.github.io/index.html">Return to main page</a><br>
</body>
</html>
