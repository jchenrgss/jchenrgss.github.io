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
The Nakajima B5N "Kate" was the standard carrier torpedo bomber of the IJN for much of World War II. During the attack on Pearl Harbor, B5Ns operated from six Japanese aircraft carriers, and were very successful in their objectives, despite being refitted as a land bomber. Here, I will consider the final (and proven) scenario that B5Ns bombed the Arizona, causing it to sink.
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
Images go here
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
Images go here
$\text{ }\\$
</p>
$\textbf{Newton's First Law of Motion}$
<p>
When the dropped bomb hit the deck of Arizona, it did not simply explode on the surface. Instead, it tore a hole through her deck and exploded beneath the second turret, causing its ammunition magazine to explode. This can be explained using Newton's first law of motion: inertia, which means that objects tend to continue in their state of motion unless acted on by an external force. That is, objects in motion tend to stay in motion, unless something acts to stop the object from moving. In this case, the bomb is falling (moving), so when it hits the deck of Arizona, it will continue to move instead of stopping instantly.
</p>
<img src="http://www.researcheratlarge.com/Ships/Drawings/USSArizona_Feb1942%20_181-58-3087_Salvage%20Ops_Declass12358.jpg" alt="Diagram of USS Arizona"><br>
<p>
Bomb manufacturers exploit this property, and construct bombs with specific fuzes--bombs that explode only after a certain period of time has elapsed since impact. This particular technology was the main reason as to why Arizona exploded so violently. If the bomb were to explode on the deck of the ship, very little damage would be done. By waiting for the bomb to pass through the deck, maximal amounts of damage can be dealt to enemy targets.
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
$\textbf{Vector Addition (Relative Velocity)}$
<p>
$\textbf{1.}\text{ If a B5N is 2 km [E] of Arizona and a 60 km/h wind is blowing from the North, determine the}\\\text{B5N's relative ground speed and how far it will be off-target by.}$
$$\overrightarrow{v_{pg}}=\overrightarrow{v_{pa}}+\overrightarrow{v_{ag}}=105\text{ m/s }\hat{\text{i}}+16.\overline{66}\text{ m/s }\hat{\text{j}}$$
$$|\overrightarrow{v_{pg}}|=\sqrt{(105\text{ m/s }\hat{\text{i}})^2+(16.\overline{66}\text{ m/s }\hat{\text{j}})^2}$$
$$|\overrightarrow{v_{pg}}|=106.3145\text{ m/s}=110\text{ m/s}$$
$$\theta=\tan^{-1}(\frac{\overrightarrow{v_{ag}}}{\overrightarrow{v_{pa}}})=\tan^{-1}(\frac{16.\overline{66}\text{ m/s }\hat{\text{j}}}{105\text{ m/s }\hat{\text{i}}})$$
$$\theta=6.3402^\circ=6.3^\circ$$
$$\Delta t=\frac{\Delta\overrightarrow{d_x}}{\overrightarrow{v_x}}=\frac{2000\text{ m}}{105\text{ m/s}}$$
$$\Delta t=19.0476\text{ s}=19\text{ s}$$
$$\Delta\overrightarrow{d_y}=\overrightarrow{v_y}\Delta t=(16.\overline{66}\text{ m/s})(19.0476\text{ s})$$
$$\Delta\overrightarrow{d_y}=317.4601\text{ m}=320\text{ m [South]}$$
$\text{ }\\$
</p>
$\textbf{Vector Subtraction (Displacement / Average Velocity)}$
<p>
$\textbf{1.}\text{ At 08:00, a group of B5Ns are approaching Pearl Harbor with a velocity of 378 m/s [S }45^\circ\text{ W].}\\\text{At 09:30, the attack is over and the same group of bombers are leaving Pearl Harbor with a}\\\text{velocity of 342 m/s [N }10^\circ\text{ E]. Determine the change in velocity and average acceleration of the B5Ns.}\\$
$\text{Vector components:}$
$$\overrightarrow{v_i}=(-105\text{ m/s}\times\cos45^\circ\text{ }\hat{\text{i}})+(-105\text{ m/s}\times\sin45^\circ\text{ }\hat{\text{j}})$$
$$\overrightarrow{v_i}=-74.2462\text{ m/s }\hat{\text{i}}-74.2462\text{ m/s }\hat{\text{j}}$$
$$\overrightarrow{v_f}=(95\text{ m/s}\times\cos80^\circ\text{ }\hat{\text{i}})+(95\text{ m/s}\times\sin80^\circ\text{ }\hat{\text{j}})$$
$$\overrightarrow{v_f}=16.4966\text{ m/s }\hat{\text{i}}+93.5567\text{ m/s }\hat{\text{j}}$$
$\text{Change in velocity:}$
$$\Delta\overrightarrow{v}=\overrightarrow{v_f}-\overrightarrow{v_i}$$
$$\Delta\overrightarrow{v}=(16.4966\text{ m/s }\hat{\text{i}}+93.5567\text{ m/s }\hat{\text{j}})-(-74.2462\text{ m/s }\hat{\text{i}}-74.2462\text{ m/s }\hat{\text{j}})$$
$$\Delta\overrightarrow{v}=90.7428\text{ m/s }\hat{\text{i}}+167.8029\text{ m/s }\hat{\text{j}}$$
$$|\Delta\overrightarrow{v}|=\sqrt{\overrightarrow{v_{\hat{\text{i}}}}^2+\overrightarrow{v_{\hat{\text{j}}}}^2}=\sqrt{(90.7428\text{ m/s }\hat{\text{i}})^2+(167.8029\text{ m/s }\hat{\text{j}})^2}$$
$$|\Delta\overrightarrow{v}|=190.7671\text{ m/s}=190\text{ m/s}$$
$$\theta=\tan^{-1}(\frac{\Delta\overrightarrow{v_{\hat{\text{j}}}}}{\Delta\overrightarrow{v_{\hat{\text{i}}}}})=\tan^{-1}(\frac{167.8029\text{ m/s }\hat{\text{j}}}{90.7428\text{ m/s }\hat{\text{i}}})$$
$$\theta=61.5968^\circ=62^\circ$$
$\therefore\text{The change in velocity is approximately 190 m/s [E }62^\circ\text{ N].}$
$$\overrightarrow{a}=\frac{\Delta\overrightarrow{v}}{\Delta t}=\frac{190.7671\text{ m/s}}{5400\text{ s}}$$
$$\overrightarrow{a}=3.5327\times10^2\text{ m/s}^2=3.5\times10^2\text{ m/s}^2 \text{ [E }62^\circ\text{ N]}$$
$\textbf{2.}\text{ At one point during the battle, Arizona is at a position 600 m [N }15^\circ\text{ W] relative to one B5N.}\\\text{A second B5N is at a position 240 m [E }20^\circ\text{ N] relative to Arizona. Determine the displacement}\\\text{between the two B5Ns.}\\$
$\text{Vector components:}$
$$\overrightarrow{d_i}=(600\text{ m}\times\cos75^\circ\text{ }\hat{\text{i}})+(600\text{ m/s}\times\sin75^\circ\text{ }\hat{\text{j}})$$
$$\overrightarrow{d_i}=-155.2914\text{ m }\hat{\text{i}}+579.5555\text{ m }\hat{\text{j}}$$
$$\overrightarrow{d_f}=(240\text{ m/s}\times\cos20^\circ\text{ }\hat{\text{i}})+(240\text{ m/s}\times\sin20^\circ\text{ }\hat{\text{j}})$$
$$\overrightarrow{d_f}=225.5262\text{ m }\hat{\text{i}}+82.0848\text{ m }\hat{\text{j}}$$
$\text{Change in position:}$
$$\Delta\overrightarrow{d}=\overrightarrow{d_f}-\overrightarrow{d_i}$$
$$\Delta\overrightarrow{d}=(225.5262\text{ m }\hat{\text{i}}+82.0848\text{ m }\hat{\text{j}})-(-155.2914\text{ m }\hat{\text{i}}+579.5555\text{ m }\hat{\text{j}})$$
$$\Delta\overrightarrow{d}=380.8177\text{ m }\hat{\text{i}}-497.4707\text{ m }\hat{\text{j}}$$
$$|\Delta\overrightarrow{d}|=\sqrt{\overrightarrow{d_{\hat{\text{i}}^2}}+\overrightarrow{d_{\hat{\text{j}}^2}}}=\sqrt{(380.8177\text{ m }\hat{\text{i}})^2+(-497.4707\text{ m }\hat{\text{j}})^2}$$
$$|\Delta\overrightarrow{d}|=626.4975\text{ m}=626\text{ m}$$
$$\theta=\tan^{-1}(\frac{\Delta\overrightarrow{d_{\hat{\text{j}}}}}{\Delta\overrightarrow{d_{\hat{\text{i}}}}})=\tan^{-1}(\frac{-497.4707\text{ m }\hat{\text{j}}}{380.8177\text{ m }\hat{\text{i}}})$$
$$\theta=-52.5657^\circ=-53^\circ$$
$\therefore\text{The displacement is approximately 626 m [E }53^\circ\text{ S].}$
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
