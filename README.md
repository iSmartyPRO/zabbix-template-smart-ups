# Zabbix Template for Smart UPS Device Monitoring

This template is tested for **Smart-UPS C 1000**

**GROUP** Templates SNMP

## ITEMS
* UPS Battery Capacity
* UPS Battery Replace
* UPS Battery Runtime Remain
* UPS Battery Temperature
* UPS Diagnostic Self Test Date
* UPS Diagnostic Self Test Result
* UPS Input Frequency
* UPS Input Voltage
* UPS Model
* UPS Output current Amps
* UPS Output Frequency
* UPS Output Load
* UPS Output Voltage

## TRIGGERS
* Температура ИБП более 30⁰	
* Output load is more than 50%	
* Output less than 210V	
* Input less than 210V	
* Battery need to be replaced	
* Battery capacity less than 70%	
