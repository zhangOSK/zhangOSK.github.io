---
title: Research
layout: landing
description: 'Pivoting manipulation, Bipedal walking, Model Predictive Control(MPC)'
image: assets/images/keyboard.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Pivoting manipulation(undergoing)</h2>
		</header>
		<p>We are trying to pivot different shaped object. Pivoting saves energy in manipulation as most of the weight of object is supported by floor. </p>
	</div>
</section>

<!-- Two Research Explan -->
<section id="two" class="spotlights">
	<section>
	<!-- section 1 pivoting -->
		<a href="generic.html" class="image">
			<img src="{% link assets/images/pivotSum.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Pivot walking</h3>
				</header>
				<p>A dual-arm robot Yaskawa Motoman SDA5F pivots a large box to walk. We proposed two walking modes and graph MPC to swithcing walking modes. The robot can pivot the box fast and slow, resist disturbance and robust to mass uncertainty of object</p>
				<ul class="actions">
					<li><a href="generic.html" class="button">Vedio</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
	<!-- section 2 bipedal walking-->
		<a href="generic.html" class="image">
			<img src="{% link assets/images/hrp2.jpg %}" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Bipedal walking</h3>
				</header>
				<p>A bipedal gait controller for humanoid robot HRP-2. We propose using basis functions like Laguerre functions and Haar functions to describe the control variable of MPC which saves computation cost. </p>
				<ul class="actions">
					<li><a href="https://www.tandfonline.com/doi/full/10.1080/01691864.2019.1594366" class="button">Paper</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
	<!-- section 3 fire hose-->
		<a href="generic.html" class="image">
			<img src="{% link assets/images/talosHose.jpg %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Pulling fire-hose</h3>
				</header>
				<p>We let humanoid robot TALOS pull fire-hose. An impedance controller is used in the hand pulling hose. By compensating the dragging force from hose and designing the strategy to pull, the robot pulls fire-hose without falling.</p>
			</div>
		</div>
	</section>
</section>


</div>
