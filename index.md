---
layout: page
title: Cost Per Square Foot vs Satisfaction
---
{% include JB/setup %}

<div class='row'>
	<div class='col-md-12'>
		<div>
			Group by: 
<button disabled='disabled' class='btn btn-default'>Region</button>
<button disabled='disabled' class='btn btn-default'>State</button>
<button disabled='disabled' class='btn btn-default'>Agency</button>
		</div>
	</div>
</div>
<div class='row'>
	<div class='col-md-12'>
		<div id='chart'></div>
		<div class='row'>
			<div class='col-md-3'>
<img src="{{BASE_PATH}}/assets/scatterplotselect.png">
			</div>
			<div class='col-md-3'>
<img src="{{BASE_PATH}}/assets/boxplot.png">
			</div>
			<div class='col-md-3'>
<img src="{{BASE_PATH}}/assets/ratingcurvecompare.png">
			</div>
			<div class='col-md-3'>
<img src="{{BASE_PATH}}/assets/spendingplot.png">
			</div>
		</div>
		<div class='row'>
			<div class='col-md-6'>
				<h2>Top 5</h2>
<img style='width: 30px' src='{{BASE_PATH}}/assets/happy.png' />Boston<br/>
<img style='width: 30px' src='{{BASE_PATH}}/assets/happy.png' />Houston<br/>
<img style='width: 30px' src='{{BASE_PATH}}/assets/happy.png' />Denver<br/>
<img style='width: 30px' src='{{BASE_PATH}}/assets/happy.png' />Trenton<br/>
<img style='width: 30px' src='{{BASE_PATH}}/assets/happy.png' />Philadelphia<br/>
			</div>
			<div class='col-md-6'>
				<h2>Bottom 5</h2>
<img style='width: 30px' src='{{BASE_PATH}}/assets/sad.png' />Washington, DC<br/>
<img style='width: 30px' src='{{BASE_PATH}}/assets/sad.png' />Los Angeles<br/>
<img style='width: 30px' src='{{BASE_PATH}}/assets/sad.png' />New York<br/>
<img style='width: 30px' src='{{BASE_PATH}}/assets/sad.png' />Dallas<br/>
<img style='width: 30px' src='{{BASE_PATH}}/assets/sad.png' />San Francisco<br/>
			</div>
		</div>
		<div class='row'>
			<h2>My Buildings</h2>
			<div id='BuildingSelect' class='g5-disabled'>
<input type='checkbox' checked disabled='disabled' />Anchorage<br/>
<input type='checkbox' checked disabled='disabled' />Boulder<br/>
<input type='checkbox' checked disabled='disabled' />Boston<br/>
<input type='checkbox' checked disabled='disabled' />Charlottesville<br/>
<input type='checkbox' checked disabled='disabled' />Denton<br/>
<input type='checkbox' checked disabled='disabled' />Elkridge<br/>
<input type='checkbox' checked disabled='disabled' />Gainseville<br/>
<input type='checkbox' checked disabled='disabled' />Houston<br/>
<input type='checkbox' checked disabled='disabled' />Kingston<br/>
			</div>
		</div>
	</div>
</div>
