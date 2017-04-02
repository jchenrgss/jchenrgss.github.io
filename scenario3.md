<html>
<head>
<title>CSI Project - Scenario 3</title>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}});
</script>
<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_CHTML">
</script>
</head>
<body>
<img src="https://upload.wikimedia.org/wikipedia/commons/c/c4/Pearl_Harbor-_Nakajima_B5N2_over_Hickam-_80G178985.jpg" alt="B5N over Pearl Harbor">
$\textbf{Introduction and Evidence}$
<p>
The Nakajima B5N "Kate" was the standard carrier torpedo bomber of the IJN for much of World War II. During the attack on Pearl Harbor, B5Ns operated from the six Japanese aircraft carriers, and were very successful in their objective, despite being refitted as a bomber. Here, I will consider the final (and proven) scenario that B5Ns bombed the Arizona, causing it to sink.
</p>
<p>
The bombs dropped by B5Ns at Pearl Harbor were modified 41-cm armour penetrating (AP) shells fired by the 41-cm naval gun (the same gun on the battleship Nagato). Torpedoes were also used in battle, but not against Arizona.<br><br>
Wing area: 37.3 m^2<br>
Loaded weight (without 800-kg bomb): 3,300 kg<br>
Loaded weight: 4,100 kg<br>
Engine power: 1,000 hp<br>
Maximum speed: 378 km/h = 105 m/s<br>
Range: 1,992 km = 1,992,000 m<br>
Bombing altitude: 3,000 m<br>
Drag coefficient: 0.025<br>
$\text{ }\\$
</p>
$\textbf{Velocity Vectors}$
<p>
Text
$\text{ }\\$
</p>
$\textbf{Friction and Equilibrium}$
<p>
$\text{The B5N flies straight and level at a constant speed when bombing. Thus, there is no acceleration}\\\text{in either the }x\text{ or }y\text{ directions (i.e. }F_{\text{net}_x}\text{ and }F_{\text{net}_y}=0\text{).}\\$
$$\overrightarrow{F_{\text{net}_x}}=\overrightarrow{F_{app}}-\overrightarrow{F_D}=0\text{, }\overrightarrow{F_{app}}=\overrightarrow{F_D}$$
$$\overrightarrow{F_D}=\frac{1}{2}\rho u^2C_DA=\frac{1}{2}(1.225\text{ kg/m}^3)(105\text{ m/s})^2(0.025)(37.3\text{ m}^2)$$
$$\overrightarrow{F_D}=(0.6125\text{ kg/m}^3)(11,025\text{ m}^2\text{s}^{-2})(0.9325\text{ m}^2)$$
$$\overrightarrow{F_D}=6296.9977\text{ N}=6,300\text{ N [Backward]}$$
$\text{Therefore, }\overrightarrow{F_{app}}=6296.9977\text{ N}=6300\text{ N [Forward]}$
$$\overrightarrow{F_{\text{net}_y}}=\overrightarrow{F_L}-\overrightarrow{F_g}=0\text{, }\overrightarrow{F_L}=\overrightarrow{F_g}$$
$$\overrightarrow{F_g}=mg=(4100\text{ kg})(9.8\text{ m/s}^2)$$
$$\overrightarrow{F_g}=40,180\text{ N}=40,000\text{ N [Downward]}$$
$\text{Therefore, }\overrightarrow{F_L}=40,180\text{ N}=40,000\text{ N [Upward]}\\$
$\text{ }\\$
</p>
$\textbf{Projectile Motion Calculations (Half-Parabola)}$
<p>
$\textbf{1.}\text{ Determine the time for the bomb to fall, assuming no air resistance.}$
$$\Delta\overrightarrow{d_y}=\overrightarrow{v_{i_y}}\Delta t\,+\,\frac{1}{2}\overrightarrow{a_y}\Delta t^2=0\,+\,\frac{1}{2}\overrightarrow{a_y}\Delta t^2$$
$$3000\text{ m}=\frac{1}{2}(9.8\text{ m/s}^2)\Delta t^2$$
$$\Delta t=\sqrt{3000\text{ m}\over4.9\text{ m/s}^2}=\sqrt{612.2449\text{ s}^2}$$
$$\Delta t=24.7436\text{ s}=25\text{s}$$
$\textbf{2.}\text{ Determine the final vertical velocity of the bomb, assuming no air resistance.}$
$$\overrightarrow{v_{f_y}}^2=\overrightarrow{v_{i_y}}^2+2\overrightarrow{a_y}\Delta\overrightarrow{d_y}=0\,+\,2\overrightarrow{a_y}\Delta\overrightarrow{d_y}$$
$$\overrightarrow{v_{f_y}}^2=\sqrt{2\overrightarrow{a_y}\Delta\overrightarrow{d_y}}=\sqrt{2(9.8\text{ m/s}^2)(3000\text{ m})}$$
$$\overrightarrow{v_{f_y}}^2=242.4871\text{ m/s}=240\text{ m/s [Downward]}$$
$\textbf{3.}\text{ Determine the time for the bomb to fall, assuming air resistance.}$ $$\overrightarrow{F_{\text{net}_y}}=\overrightarrow{F_g}-\overrightarrow{F_D}=m\overrightarrow{a_y}$$
$$\overrightarrow{F_g}=mg=(800\text{ kg})(9.8\text{ m/s}^2)$$
$$\overrightarrow{F_g}=7840\text{ N}=7800\text{ N [Downward]}$$ $$\overrightarrow{F_D}=\frac{1}{2}\rho u^2C_DA=\frac{1}{2}(1.225\text{ kg/m}^3)(242.4871\text{ m/s})^2(0.10)(\pi(\frac{0.41\text{ m}}{2})^2)$$
$$\overrightarrow{F_D}=(0.6125\text{ kg/m}^3)(58,800\text{ m}^2\text{s}^{-2})(0.1320\text{ m}^2)$$
$$\overrightarrow{F_D}=475.4896\text{ N}=480\text{ N[Upward]}$$
$\text{Use Newton's second law of motion to calculate acceleration due to air resistance.}$
$$\overrightarrow{F_g}-\overrightarrow{F_D}=7840\text{ N}\,-\,475.4896\text{ N}=7364.5104\text{ N [Downward]}$$
$$7364.5102\text{ N}=m\overrightarrow{a_y}=(800\text{ kg})\overrightarrow{a_y}$$
$$\overrightarrow{a_y}=\frac{7364.5102\text{ N}}{800\text{ kg}}=9.2056\text{ m/s}^2\text{ [Downward]}$$
$$\Delta\overrightarrow{d_y}=\overrightarrow{v_{i_y}}\Delta t\,+\,\frac{1}{2}\overrightarrow{a_y}\Delta t^2=0\,+\,\frac{1}{2}\overrightarrow{a_y}\Delta t^2$$
$$3000\text{ m}=\frac{1}{2}(9.2056\text{ m/s}^2)\Delta t^2$$
$$\Delta t^2=\frac{3000\text{ m}}{4.6028\text{ m/s}^2}\text{, }\Delta t=\sqrt{\frac{3000\text{ m}}{4.6028\text{ m/s}^2}}$$
$$\Delta t=25.5299\text{ s}=26\text{ s}$$
$\textbf{4.}\text{ Determine the horizontal displacement of the bomb, assuming no air resistance.}$
$$\Delta\overrightarrow{d_x}=\overrightarrow{v_x}\Delta t=(105\text{ m/s})(25.5299\text{ s})$$
$$\Delta\overrightarrow{d_x}=2680.6368\text{ m}=2700\text{ m [Forward]}$$
$\textbf{5.}\text{ Determine the horizontal displacement of the bomb, assuming air resistance.}$
$$\overrightarrow{F_{\text{net}_x}}=\overrightarrow{F_D}=m\overrightarrow{a_x}$$
$$\overrightarrow{F_D}=\frac{1}{2}\rho u^2C_DA=\frac{1}{2}(1.225\text{ kg/m}^3)(105\text{ m/s})^2(0.10)(\pi(\frac{0.41\text{ m}}{2})^2)$$
$$\overrightarrow{F_D}=(0.6125\text{ kg/m}^3)(11,025\text{ m/s})(0.0132\text{ m}^2)$$
$$\overrightarrow{F_D}=89.1543\text{ N}=89\text{ N [Backward]}$$
$$\overrightarrow{F_D}=89.1543\text{ N}=89\text{ N [Backward]}$$
$$89.1543\text{ N}=m\overrightarrow{a_x}=(800\text{ kg})\overrightarrow{a_x}$$
$$\overrightarrow{a_x}=\frac{89.1543\text{ N}}{800\text{ kg}}=0.1114\text{ m/s}^2\text{ [Backward]}$$
$$\Delta\overrightarrow{d_x}=\overrightarrow{v_{i_x}}\Delta t\,+\,\frac{1}{2}\overrightarrow{a_x}\Delta t^2=(105\text{ m/s})(25.5299\text{ s})+\frac{1}{2}(-0.1114\text{ m/s}^2)(25.5299\text{ s})^2$$
$$\Delta\overrightarrow{d_x}=2680.6368\text{ m}\,-\,(0.557\text{ m/s}^2)(651.7745\text{ s}^2)$$
$$\Delta\overrightarrow{d_x}=2644.3190\text{ m}=2600\text{ m [Forward]}$$
$\textbf{6.}\text{ Determine the final velocity and angle of impact.}$
$\text{Use kinematic equation 2, because haven't used this one yet:}$
$$\Delta\overrightarrow{d_y}=\frac{1}{2}(\overrightarrow{v_{f_y}}\,+\,\overrightarrow{v_{i_y}})\Delta t$$
$$3000\text{ m}=\frac{1}{2}(\overrightarrow{v_{f_y}}\,+\,0)(25.5299\text{ s})$$
$$\overrightarrow{v_{f_y}}=\frac{6000\text{ m}}{25.5299\text{ s}}=235.0188\text{ m/s}$$
$$\Delta\overrightarrow{d_x}=\frac{1}{2}(\overrightarrow{v_{f_x}}\,+\,\overrightarrow{v_{i_x}})\Delta t$$
$$2644.3190\text{ m}=\frac{1}{2}(\overrightarrow{v_{f_x}}\,+\,105\text{ m/s})(25.5299\text{ s})$$
$$\frac{5288.6380\text{ m}}{25.5299\text{ s}}=\overrightarrow{v_{f_x}}\,+\,105\text{ m/s}$$
$$\overrightarrow{v_{f_x}}=102.1549\text{ m/s}$$
$\text{Combine the components:}$
$$|\overrightarrow{v_f}|=\sqrt{\overrightarrow{v_{f_x}}^2\,+\,\overrightarrow{v_{f_y}}^2}=\sqrt{(102.1549\text{ m/s})^2\,+\,(235.0188\text{ m/s})^2}$$
$$|\overrightarrow{v_f}|=256.2605\text{ m/s}=260\text{ m/s}$$
$$\tan\theta=\frac{235.0188\text{ m/s}}{102.1549\text{ m/s}}\text{, }\theta=\tan^{-1}(\frac{235.0188\text{ m/s}}{102.1549\text{ m/s}})$$
$$\theta=66.5070^\circ=67^\circ$$
$\text{ }\\$
</p>
$\textbf{Motion Graphs}$
<p>
Text
$\text{ }\\$
</p>
$\textbf{Newton's First Law of Motion}$
<p>
When the dropped bomb hit the deck of Arizona, it did not simply explode on the surface. Instead, it tore a hole through her deck and exploded beneath the second turret, causing its ammunition magazine to explode. This can be explained using Newton's first law of motion: inertia, which means that objects tend to continue in their state of motion unless acted on by an external force. That is, objects in motion tend to stay in motion, unless something acts to stop the object from moving. In this case, the bomb is falling (moving), so when it hits the deck of Arizona, it will continue to move instead of stopping instantly.
</p>
Bomb manufacturers exploit this property, and construct bombs with specific fuzes--bombs that explode only after a certain period of time has elapsed since impact. This particular technology was the main reason as to why Arizona exploded so violently. If the bomb were to explode on the deck of the ship, very little damage would be done. By waiting for the bomb to pass through the deck, maximal amounts of damage can be dealt to enemy targets.
<p>
</p>
Similarly, inertia can also be used to explain why the ships in Pearl Harbor could not escape and why few US aircraft were able to take off and fight the Japanese aircraft. Ships and planes are very heavy, so require great amounts of force to move. They tend to remain stationary, which makes them vulnerable to attack for long periods of time. By striking preemptively, the Japanese were able to obtain the upper hand in the battle, taking advantage of the enemy's great inertia.
<p>
$\text{ }\\$
</p>
$\textbf{Banked Curves}$
<p>
$\textbf{1.}\text{ Determine the radius of a turn if the angle of the incline is }45^\circ\text{.}$
$$\tan\theta=\frac{\overrightarrow{v}^2}{rg}\text{, }r=\frac{\overrightarrow{v}^2}{g\tan\theta}$$
$$r=\frac{(105\text{ m/s})^2}{(9.8\text{ m/s}^2)(\tan45^\circ)}$$
$$r=1125\text{ m}=1100\text{ m}$$
$\textbf{2.}\text{ Determine the angle of the incline if the radius of the turn is }500\text{ m.}$
$$\theta=\tan^{-1}(\frac{(105\text{ m/s})^2}{(500\text{ m})(9.8\text{ m/s}^2)})$$
$$\theta=66.0375^\circ=66^\circ$$
$\text{ }\\$
</p>
$\textbf{Vector Subtraction (Displacement / Average Velocity)}$
<p>
$\textbf{1.}\text{ At 08:00, a group of B5Ns are approaching Pearl Harbor with a velocity of 378 m/s [S }45^\circ\text{ W].}\\\text{At 09:30, the attack is over and the same group of bombers are leaving Pearl Harbor with a velocity of 342 m/s [N }80^\circ\text{ E]. What is the change in velocity and average acceleration of the B5Ns?}$
$\text{ }\\$
</p>
$\textbf{Conclusion}$
<p>
Text
$\text{ }\\$
</p>
<a href="https://jchenrgss.github.io/index.html">Return to main page</a><br>
</body>
</html>
