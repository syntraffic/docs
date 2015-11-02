|ST| Alerts
====================
This is your central place to manage all alert settings for your monitors.

Email Settings
--------------
Recipient Email address shown here is where your alerts will be sent. If you need to update the Email address and/or the name,
please contact our support: support@syntraffic.com

.. _st-pdsettings:

Pager Duty Settings
-------------------
|ST| is well integrated with `PagerDuty <http://pagerduty.com>`_. To get started you will need the “Service API Key” from Pager Duty. 
The instructions are available `here <https://support.pagerduty.com/hc/en-us/articles/202830340-Creating-a-Generic-API-Service>`_.

Enter the “Service Key” under “Pager Duty Settings” and hit Save. 

Remember to enable Pager Duty under :ref:`st-alerttargets` to receive notifications through PagerDuty.

.. _st-alerttargets:

Alert Targets
-------------------
Choose the alert targets via which you want to be notified.

If you chose to enable Pager Duty, remember to enter your service key under :ref:`st-pdsettings`. 

Notifications
-------------------
All your recent notifications that were sent to your account are displayed here. 

.. _st-alerttriggers:

Alert Triggers
-------------------
Alert triggers are smart alerts that help you manage alert storms gracefully. 

^^^^^^^^^^^^^^
Alert Interval
^^^^^^^^^^^^^^

Time interval to wait (in seconds) before the next notification is sent. 

^^^^^^^^^^^^^^
Successive Count
^^^^^^^^^^^^^^

When successive count of errors in this category crosses this threshold, generate an alert.

^^^^^^^^^^^^^^
Absolute Count
^^^^^^^^^^^^^^

When successive count of errors in this category crosses this threshold, generate an alert. This setting works in conjunction with sliding window period.

^^^^^^^^^^^^^^
Sliding Window
^^^^^^^^^^^^^^

Sliding window size (in seconds) over which the absolute count of errors is being accounted for. 

.. include:: engage.rst