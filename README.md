# -DDTA
DB2 Deadlock/Timeout Analisys Tool Ver. 1.0.0

Perform analysis about Deadlock/Timeout situation occurred in a DB2 Subsystem without using any commercial monitor (Omegamon, CA Insigth, etc.)

Obtain a report for each DB2 in a z/OS partition like this one
                                                                                                                             
DB2  Date        Time     Description    Plan     Auth ID  Conn     Corr            Resource                                 
____ ___________ ________ ______________ ________ ________ ________ _______________ ________________________________________ 
DBA2 15 OCT 2016 11.38.39 Deadlock       CPCNT000 CXCRA2D1 CXCRA2D1 ENTRXMQT0009                                             
DBA2 15 OCT 2016            Task Waiting CPCNT000 CXCRA2D1 CXCRA2D1 ENTRXMQT0009    AN88DB01.AN88TS01.X'016549'              
DBA2 15 OCT 2016            Task Holding CPCNT000 CXCRA2D1 CXCRA2D1 ENTRXMQT0003    AN88DB01.AN88TS01                        
DBA2 15 OCT 2016            Task Waiting CPCNT000 CXCRA2D1 CXCRA2D1 ENTRXMQT0003    AN88DB01.AN88TS01                        
DBA2 15 Oct 2016 11.35.17 Timeout        TWCNB000 CR00321  DB2CALL  TW00T0RA                                                 
DBA2 15 Oct 2016            Task Waiting TWCNB000 CR00321  DB2CALL  TW00T0RA        00000549.00000013                        
DBA2 15 Oct 2016            Task Holding TWCNB000 CR00321  DB2CALL  TW00T0RR        00000549.00000013                        

Refer to "Install_instuction.txt" for installation insstructions.
