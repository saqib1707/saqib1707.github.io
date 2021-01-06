---
layout: page
title: Research
permalink: /research/
description: Saqib Azim's Research
---

My interests span a breadth of fields including machine learning, optimization, computer vision, robotics, signal and image processing, etc. Below is a non-exclusive list of projects that I have worked on. Please have a look at my [CV]({{site.url/assets/CV/CV_short.pdf}}). More projects will be updated soon.<br>
_Excluding research projects at Hitachi Research due to Information Security protocols_

<table width="100%" align="center" border="0" cellspacing="0">
<tbody>
	<tr>
		<td>
			<heading>Research Papers</heading>
		</td>
	</tr>
</tbody>
</table>

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;margin-bottom:15px">
<tbody>
	<tr>
		<td class="projectWallpaper">
			<div>
				<img src='{{ site.url }}/assets/images/lps.PNG'>
			</div>
			<script type="text/javascript">
				function inerf_start() {
					document.getElementById('inerf_image').style.opacity = "1";
				}
				function inerf_stop() {
					document.getElementById('inerf_image').style.opacity = "0";
				}
				inerf_stop()
			</script>
		</td>
		<td class="projectBody">
			<a href="https://arxiv.org/abs/2003.13991"><papertitle>Indoor Distance Estimation using LSTMs over WLAN Network</papertitle></a>
			<br><span class="brHeight"></span>
			<div class="authorDetails">
				<a href="https://sabsathai.github.io/">Pranav Sankhe</a>, <strong>Saqib Azim</strong>, <a href="https://saching007.github.io/">Sachin Goyal</a>, <a href="https://www.linkedin.com/in/tanya-choudhary-772660133/">Tanya Choudhary</a>, <a href="https://www.ee.iitb.ac.in/~akumar/">Kumar Appaiah</a>, <a href="https://www.sc.iitb.ac.in/~srikant/dokuwiki/doku.php/home">Sukumar Srikant</a>
				<br>
				<em>IEEE Workshop on Positioning, Navigation and Communications (WPNC)</em>, 2019
				<br><span class="brHeight"></span>
				<a href="javascript:toggleblock('lpsabs')">abstract</a> / <a href="https://arxiv.org/abs/2003.13991">arXiv</a> / <a href="https://ieeexplore.ieee.org/document/8970257">paper</a> /<a href="{{site.url}}/assets/pubs/HAIC2020_slides.pdf">slides</a>
				<br><span class="brHeight"></span>
				<p align="justify"><i id="lpsabs">The Global Navigation Satellite Systems (GNSS) like GPS suffer from accuracy degradation and are almost unavailable in indoor environments. Indoor positioning systems (IPS) based on WiFi signals have been gaining popularity. However, owing to the strong spatial and temporal variations of wireless communication channels in the indoor environment, the achieved accuracy of existing IPS is around several tens of centimeters. We present the detailed design and implementation of a self-adaptive WiFi-based indoor distance estimation system using LSTMs. The system is novel in its method of estimating with high accuracy the distance of an object by overcoming possible causes of channel variations and is self-adaptive to the changing environmental and surrounding conditions. The proposed design has been developed and physically realized over a WiFi network consisting of ESP8266 (NodeMCU) devices. The experiments were conducted in a real indoor environment while changing the surroundings in order to establish the adaptability of the system. We compare different architectures for this task based on LSTMs, CNNs, and fully connected networks (FCNs). We show that the LSTM based model performs better among all the above-mentioned architectures by achieving an accuracy of 5.85 cm with a confidence interval of 93% on the scale of (8.46 m × 6.98 m). To the best of our knowledge, the proposed method outperforms other methods reported in the literature by a significant margin</p>
			</div>
		</td>
	</tr>
</tbody>
</table>

<table width="100%" align="center" border="0" cellspacing="0">
<tbody>
	<tr>
		<td>
			<heading>Patent</heading>
		</td>
	</tr>
</tbody>
</table>

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;margin-bottom:15px">
<tbody>
	<tr>
	<td class="projectWallpaper">
		<div>
			<img src='{{ site.url }}/assets/images/lps.PNG'>
		</div>
		<script type="text/javascript">
			function inerf_start() {
				document.getElementById('inerf_image').style.opacity = "1";
			}
			function inerf_stop() {
				document.getElementById('inerf_image').style.opacity = "0";
			}
			inerf_stop()
		</script>
	</td>
	<td class="projectBody">
		<a href="https://arxiv.org/abs/2003.13991"><papertitle>Indoor Positioning System for Position Estimation in an Indoor Environment</papertitle></a>
		<br><span class="brHeight"></span>
		<div class="authorDetails">
			<a href="https://sabsathai.github.io/">Pranav Sankhe</a>, <strong>Saqib Azim</strong>, <a href="https://saching007.github.io/">Sachin Goyal</a><br>
			<em>Indian Patent Filed in Dec '18, Application - </em>201821047043 <em>(pending)</em>
		</div>
	</td>
	</tr>
</tbody>
</table>

<table width="100%" align="center" border="0" cellspacing="0">
<tbody>
	<tr>
		<td>
			<heading>Miscellaneous Projects</heading>
		</td>
	</tr>
</tbody>
</table>

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;margin-bottom:15px">
<tbody>
	<tr>
		<td class="projectWallpaper">
			<a href="{{site.url}}/assets/pubs/btp_thesis.pdf" target="_blank"><img src='{{ site.url }}/assets/images/btp_wallpaper.png' alt="LPS" width="100%"></a>
			<script type="text/javascript">
				function inerf_start() {
					document.getElementById('inerf_image').style.opacity = "1";
				}
				function inerf_stop() {
					document.getElementById('inerf_image').style.opacity = "0";
				}
				inerf_stop()
			</script>
		</td>
		<td class="projectBody">
			<a href="{{site.url}}/assets/pubs/btp_thesis.pdf"><papertitle>Optimal Multi-Agent Pursuer-Evader Shepherding Problem</papertitle></a>
			<br><span class="brHeight"></span>
			<div class="authorDetails">
				<strong>Advisor: </strong><a href="https://www.ee.iitb.ac.in/wiki/faculty/dc">Prof. Debraj Chakraborty</a>
				<br><span class="brHeight"></span>
				<a href="{{site.url}}/assets/pubs/btp_thesis.pdf">thesis</a> / <a href="{{site.url}}/assets/pubs/btp_presentation.pdf">slides</a>
			</div>
		</td>
	</tr>
	<tr>
		<td class="projectWallpaper">
			<!-- <a href="{{site.url}}/assets/pubs/btp_thesis.pdf" target="_blank"> --><img src='{{ site.url }}/assets/images/handwriting_recog_wallpaper.png' alt="LPS" width="100%"><!-- </a> -->
			<script type="text/javascript">
				function inerf_start() {
					document.getElementById('inerf_image').style.opacity = "1";
				}
				function inerf_stop() {
					document.getElementById('inerf_image').style.opacity = "0";
				}
				inerf_stop()
			</script>
		</td>
		<td class="projectBody">
			<!-- <a href="{{site.url}}/assets/pubs/btp_thesis.pdf"> --><papertitle>Handwritten Text Recognition using Smartwatch</papertitle><!-- </a> -->
			<br><span class="brHeight"></span>
			<div class="authorDetails">
				Student Research Fellow at <a href="https://research.samsung.com/sri-b">Samsung Research Institute Bengaluru</a> advised by <a href="https://www.linkedin.com/in/shankar-venkatesan-7a849258/">Dr. Shankar Venkatesan</a><br>
				<span class="brHeight"></span>
				<a href="javascript:toggleblock('handtextrecogabs')">abstract</a>
				<br><span class="brHeight"></span>
				<p align="justify"><i id="handtextrecogabs">Prototyped a handwritten text recognizer by estimating wrist movements using smartwatch IMU sensors· Employed learned frequency filters followed by adaptive thresholding to improve raw signal SNR· Learned the relationship between hand movements (IMU signals) and character pattern using an SVM classifier (detecting valid IMU signal segments), and an LSTM (for character recognition)· Trained the end-to-end system on a custom-created dataset and achieved 87% recognition accuracy</p>
			</div>
		</td>
	</tr>
	<tr>
		<td class="projectWallpaper">
			<div>
				<img src='{{ site.url }}/assets/images/barc_interiit_wallpaper.png' alt="EDL" width="100%">
			</div>
			<script type="text/javascript">
				function inerf_start() {
					document.getElementById('inerf_image').style.opacity = "1";
				}
				function inerf_stop() {
					document.getElementById('inerf_image').style.opacity = "0";
				}
				inerf_stop()
			</script>
		</td>
		<td class="projectBody">
			<a href="https://github.com/saqib1707/TV-Audience-Measurement"><papertitle>TV Audience Measurement Challenge</papertitle></a>
			<br><span class="brHeight"></span>
			<div class="authorDetails">
				Bronze Medal (3<sup>rd</sup>/23 teams), Proposed solution for <a href="https://saqib1707.github.io/assets/pubs/problem_statement_barc.pdf">various challenges</a> put forward by <a href="https://www.barcindia.co.in/">BARC India</a> at <a href="https://www.iitb.ac.in/en/event/7th-inter-iit-tech-meet">Inter-IIT Tech Meet 2018</a><br>
				<strong>Saqib Azim</strong>, <a href="https://sabsathai.github.io/">Pranav Sankhe</a>, <a href="https://saching007.github.io/">Sachin Goyal</a>, Sanyam Khandelwal, Tanmay Patil
				<br><span class="brHeight"></span>
				<a href="https://github.com/saqib1707/TV-Audience-Measurement">code</a> / <a href="{{ site.url }}/assets/pubs/barc_interiit_presentation.pdf">slides</a>
			</div>
		</td>
	</tr>
	<tr>
		<td class="projectWallpaper">
			<div>
				<img src='{{ site.url }}/assets/images/edl_wallpaper.png' alt="EDL" width="100%">
			</div>
			<script type="text/javascript">
				function inerf_start() {
					document.getElementById('inerf_image').style.opacity = "1";
				}
				function inerf_stop() {
					document.getElementById('inerf_image').style.opacity = "0";
				}
				inerf_stop()
			</script>
		</td>
		<td class="projectBody">
			<a href="{{site.url}}/assets/pubs/edl_report.pdf"><papertitle>PPG Signal Acquisition Module</papertitle></a>
			<br><span class="brHeight"></span>
			<div class="authorDetails">
				<strong>Advisor: </strong>
				<a href="https://www.ee.iitb.ac.in/~pcpandey/">Prof. Prem C Pandey</a>
				<br>
				<strong>Saqib Azim</strong>, <a href="https://sabsathai.github.io/">Pranav Sankhe</a>, Ritik Madan
				<br><span class="brHeight"></span>
				<a href="javascript:toggleblock('edlppgabs')">abstract</a> / <a href="{{site.url}}/assets/pubs/edl_report.pdf">report</a>
				<p align="justify"><i id="edlppgabs">A photoplethysmogram(PPG) is an optically obtained plethysmogram, a volumetric measurement of an organ. With each cardiac cycle the heart pumps blood to the periphery. The change in the volume caused by the blood is detected by illuminating the skin with IR light. We developed and implemented an electronic system to capture and display the PPG signal. We make infrared(IR) light incident on finger tip and measure the reflected IR light using a phototransistor which contains the PPG signal. The raw PPG signal is in the form of current output of the phototransistor, typically [0.2-0.4] mA, and we use a current to voltage converter to get the voltage signal. The raw PPG often has a large slowly varying baseline and it needs to be restored to optimally use the available ADC range. We carry out baseline restoration by controlling the bias voltage of the current injector using a microcontroller. We amplify the signal using a fixed value of gain resistor in the current to voltage converter. We also designed an auto-led intensity control to control the LED current and hence the emitted IR light in an effort to make the acquisition module adaptable to users with varying skin colours, motion artifacts etc. Finally we display the PPG signal on an android smartphone by transmitting the PPG signal over bluetooth.</p>
			</div>
		</td>
	</tr>
	<tr>
		<td class="projectWallpaper">
			<div>
				<img src='{{ site.url }}/assets/images/image_editor_wallpaper.png' alt="image_editor" width="100%">
			</div>
			<script type="text/javascript">
				function inerf_start() {
					document.getElementById('inerf_image').style.opacity = "1";
				}
				function inerf_stop() {
					document.getElementById('inerf_image').style.opacity = "0";
				}
				inerf_stop()
			</script>
		</td>
		<td class="projectBody">
			<a href="{{site.url}}/assets/pubs/image_editor_report.pdf"><papertitle>Image Editor Module</papertitle></a>
			<br><span class="brHeight"></span>
			<div class="authorDetails">
				<em>Course: Digital Image Processing</em>
				<br><span class="brHeight"></span>
				<a href="{{site.url}}/assets/pubs/image_editor_report.pdf">report</a> / <a href="https://github.com/saqib1707/Image-Editor">code</a>
			</div>
		</td>
	</tr>
</tbody>
</table>

**More projects will be updated soon !!!**