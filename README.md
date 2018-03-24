# Simple-Modbus-Slave
## A simple Modbus Slave Arduino Library
(Original by Juan Bester  --> https://goo.gl/9au7R1)  
  
you can use it with the Simple Modbus Master Library https://github.com/BlackBrix/Simple-Modbus-Master
  
see as well: https://github.com/angeloc/simplemodbusng for a more developed and maintained variant of this library
  
10/11/2014 - SMSV10  
Added function 6  
The library for the DUE differs only in the removal of the byteFornat parameter in modbus_configure().  
  
16/02/2014 - SMSv9  
1. Cleaned up comments and changed the BUFFER size to 64 which matches the new buffer value in the hardwareSerial core library in version 1.05 onwards.  
  
2. Added: void modbus_update_comms(long baud, unsigned char byteFormat, unsigned char _slaveID);  
   This allows for easy update of the port variables and the slave id dynamically in your code.



