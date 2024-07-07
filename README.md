Role Name
=========

Role to install and configure a respeaker 2-mic hat on a raspberry pi
This role mimics the installation steps found in https://github.com/rhasspy/wyoming-satellite/blob/master/docs/tutorial_2mic.md

Requirements
------------

python3

Role Variables
--------------

At the very least you can set the following variables:

respeaker_wyoming_satellite_satellite_name: a string that is the name of the satellite that will be presented to Home Assistant.
respeaker_wyoming_openwakeword_enable: a boolean that enables the openwakeword service.
respeaker_led_enable: a boolean that enables the led service that responds to events(wake words).

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

see folder test for a sample playbook


License
-------

BSD

Author Information
------------------

https://github.com/j3ffrw
