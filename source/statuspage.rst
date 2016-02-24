Status Page
====================

Status page provides uptime, performance and incident details for your website and its components. 

Subscribe
-------
You can subscribe to notifications when your website is having issues. The subscription options available are dependent on what the website owner has made available. The common options are: 
* SMS Subscribe: If this option is available, you can provide your phone number (US only) to receive an SMS message when a new issue  is detected and/or an existing issue is resolved.

* Email Subscribe: If this option is available, you can provide your email address. We will notifiy to this email address when a new issue  is detected and/or an existing issue is resolved.

* Twitter: If this option is available, you can click on the twitter link available and follow the twitter account to get updates.

* Support Site: If this option is available, you can click on the support link available and get connected to their support site.

Status Details
--------------

The status page details section is divided into three sections:

**Calendar cells**: The left most section is the calendar cells which show the availability of the component. Here is what the calendar cells color indicate:

.. raw:: html

  <div class="section pull-left" style="padding: 5px;margin-bottom: 20px;margin-top: 10px;">
  <p class="pull-left" style="width:100%;background:linear-gradient(to right, #F89406 45px, #fcfcfc 45px);
    padding:10px;height:44px;">
    <span class="pull-left indicator" style="width:24px;height:24px;background:#fff;margin-right:10px;">&nbsp;</span>
   	<span class="pull-left" style="margin-left: 15px;">No issues have been detected for this day.</span>
  </p>
  <p class="pull-left" style="width:100%;background:linear-gradient(to right, #F89406 45px, #fcfcfc 45px);
    padding: 10px;height: 44px;">
    <span class="pull-left indicator" style="width:24px;height:24px;background:#ccc;margin-right:10px;">&nbsp;</span>
  	<span class="pull-left" style="width: 87%;margin-left: 15px;margin-top: -12px;">We have no data for this day. This can happen if monitoring of the target website was not started/paused and hence we have no data for this day.</span>
  </p>
  <p class="pull-left" style="width: 100%;background: linear-gradient(to right, #F89406 45px, #fcfcfc 45px);padding: 10px;height: 44px;">
  <span class="pull-left indicator" style="width:24px;height:24px;background: #ffbd62;margin-right:10px;">&nbsp;</span>
  <span class="pull-left" style="margin-left: 15px;">This is a future day and hence we have no data for this day.</span>
  </p>
  <p class="pull-left" style="width: 100%;background: linear-gradient(to right, #F89406 45px, #fcfcfc 45px);padding: 10px;height: 44px;">
  	<span class="pull-left indicator" style="width:24px;height:24px;border:2px solid #25a52e;background:#fff;margin-right: 10px;">&nbsp;</span>
  	<span class="pull-left" style="margin-left: 15px;">The green border indicates that this is the data for today.</span></p></div>


**Latency Chart**: The middle section shows the average response time of the component in milliseconds. Hover over the chart to get the response time for the specific day. 

**Details Panel**: The right most section is a (floating) details panel. This panel shows up when you hover over the calendar cells for the days that the website component had issues. The panel provides details about the availability number for the particular and any incident details as provided by the website owner.

.. include:: engage.rst
