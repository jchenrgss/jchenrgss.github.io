<html>
<head>
<title>CSI Project - Main</title>
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
The primary armament of Nagato consists of four 41cm/45 3rd Year Type naval guns, initially developed for coast defence mountings.<br><br>
Overall length: 18.84 m<br>
Bore length: 18.294 m<br>
Mass: 102,000 kg<br>
Elevation capacity: -2/+35 degrees<br>
Rate of fire: 24 rpm<br><br>
Shell mass: 1,020 kg<br>
Muzzle velocity: 790 m/s<br>
Effective firing range: 30,200 m<br>
Maximum firing range: 38,400 m<br><br>
Boeing B-17 maximum range: 3,219 km<br>
$\text{ }\\$
</p>
$\textbf{Projectile Motion Calculations}$
<p>
$\textbf{1.}\text{ Determine the maximum range of the shell, assuming no air resistance. Use the range equation:}$
$$\Delta\overrightarrow{d_x}=\frac{\overrightarrow{v_i}^2\sin2\theta}{g}$$
$\text{Use }Nagato\text{'s maximum gun elevation, because as }\theta\text{ increases, }\sin2\theta\text{ increases to approximately }0.57.$
$$\Delta\overrightarrow{d_x}=\frac{(790\text{ m/s})^2(\sin2(35^\circ))}{(9.8\text{ m/s}^2)}$$
$$\Delta\overrightarrow{d_x}=\frac{(624,100\text{ m}^2\text{s}^2)(\sin70^\circ)}{9.8\text{ m/s}^2}$$
$$\Delta\overrightarrow{d_x}=59,843.0780\text{ m}=60,000\text{ m [Forward]}$$
$59,843.08\text{ m is much greater than }38,400\text{ m, so air resistance cannot be ignored.}\\$
$\textbf{2.}\text{ Determine the maximum range of the shell, assuming air resistance. Use the drag equation:}$
$$\overrightarrow{F_D}=\frac{1}{2}\rho u^2C_DA$$
$F_D\text{ is the drag force, }\rho\text{ is the density of air, }u\text{ is the airspeed, }C_D\text{ is the drag coefficient, and }A\text{ is the}\\\text{reference area. Assume }\rho=1.225\text{ kg/m}^3\text{ and }C_D=0.010.$
$$A=\pi r^2=\pi(\frac{d}{2})^2\text{, where }d=0.41\text{ m (gun caliber)}$$
$$A=\pi(\frac{0.41\text{ m}}{2})^2=0.1320\text{ m}^2$$
$\text{Therefore,}$
$$\overrightarrow{F_D}=\frac{1}{2}(1.225\text{ kg/m}^3)(790\text{ m/s})^2(0.010)(0.1320\text{ m}^2)$$
$$\overrightarrow{F_D}=\frac{1}{2}(1.225\text{ kg/m}^3)(624,100\text{ m}^2\text{s}^{-2})(1.132\times10^3\text{ m}^2)$$
$$\overrightarrow{F_D}=504.5849\text{ N}=500\text{ N [Backward]}$$
$\text{Next, calculate the acceleration due to air resistance using Newton's second law of motion.}$
$$\overrightarrow{F_D}=ma_D=(800\text{ kg})(a_D)$$
$$a_D=\frac{504.5849\text{ N}}{800\text{ kg}}=0.6307\text{ m/s}^2=0.63\text{ m/s}^2\text{ [Backward]}$$
$\text{ }\\$
</p>
</body>
</html>
