+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = "2016-04-20T00:00:00"

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Courses"
subtitle = ""

# Order that this section will appear in.
weight = 60

+++
<!-- Courses -->
<div class="row">
	<!-- SEU -->
	<a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseUM" aria-expanded="false" aria-controls="collapseUM">
		<h3 class="text-left">Southeast University</h3>
	</a>
	<div id="collapseUM" class="collapse" role="tabpanel" aria-labelledby="headingUM">
		<div class="card-block">
			<table>
				<tbody>
					<tr>
						<td><font size="4">Computational Intelligence</font></td>
					</tr>

					<tr>
						<!-- <td><font size="3">Pattern Recognition (<a href="#", target="_blank">Homework</a>)</font></td> -->
						<td><font size="4">Pattern Recognition</font></td>
					</tr>

					<tr>
						<td><font size="4">Computer Vision</font></td>
					</tr>

					<tr>
						<td><font size="4">Image Processing and Understanding</font></td>
					</tr>
					
					<tr>
						<td><font size="4">Intelligent Robot</font></td>
					</tr>					
				</tbody>
			</table>
		</div>
	</div>
	<!-- MOOC -->
	<a class="collapsed" data-toggle="collapse" data-parent="#accordion" href="#collapseMOOC" aria-expanded="false" aria-controls="collapseMOOC">
		<h3 class="text-left">Massive Online Open Course (MOOC)</h3>
	</a>
	<div id="collapseMOOC" class="collapse" role="tabpanel" aria-labelledby="headingMOOC">
		<div class="card-block">
			<table>
				<tbody>
					<tr>
						<td><font size="4">
							<a href="http://cs231n.stanford.edu/", target="_blank"> cs231n - Convolutional Neural Networks for Visual Recognition</a> 
							(<a href="https://github.com/coky/cs231n", target="_blank">Homework</a>)</font></td>
					</tr>

					<tr>
						<td><font size="4">
							<a href="https://www.coursera.org/learn/machine-learning", target="_blank"> Andrew Ng - Machine Learning</a></font></td>
					</tr>

					<tr>
						<td><font size="4">
							<a href="https://www.coursera.org/learn/build-a-computer", target="_blank"> Hebrew University of Jerusalem - Build a Modern Computer from First Principles: 
							From Nand to Tetris</a> <!-- (<a href="#", target="_blank">Homework</a>) --></font></td>
					</tr>
					<tr>
						<td><font size="4">
							<a href="https://pdos.csail.mit.edu/6.828/2017/overview.html", target="_blank"> MIT 6.828 - JOS 
							</a> <!-- (<a href="#", target="_blank">Homework</a>) --> </font></td>
					</tr>					
				</tbody>
			</table>
		</div>
	</div>
</div>