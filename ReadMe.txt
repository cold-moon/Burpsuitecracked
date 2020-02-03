Set browser proxy to to 127.0.0.1:8080
Start with BurpLoader.jar


mkdir -p /opt/dev_sda4/Burpsuite/
step -  unrar 'Burp_Suite_Pro_1.5.20(irdevelopers.com).rar'
step -  then enter 'Burp_Suite_Pro_1.5.20(irdevelopers.com).rar' password - irdevelopers.com then extract the file your directory
step -  Extracted files - BurpLoader.jar  burpsuite_pro_v1.5.20.jar 
step -  create startup script in extrcted folder
step - vim /opt/dev_sda4/Burpsuite/start.sh 
 copy and paste below script in start.sh 
      java -jar /opt/dev_sda4/Burpsuite/BurpLoader.jar
      

step - save and exit 

        
