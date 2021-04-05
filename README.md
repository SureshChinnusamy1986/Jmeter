# Jmeter
Jmeter script for google Search Home page

**Jmeter setup steps**

1. Navigate to jmeter site - https://jmeter.apache.org/
2. Download binary zip file
3. unzip and navigate to bin 
4. Execute jmeter (.exe) file foe windows , don't run jmeter.sh file
5. Download blazemeter plugin in chrome
6. Login to blazemter (only you login you get the option to download .jmx file)
7. Record the action 
8. Download the .jmx file
9. open the .jmx file in jmeter
10. Go to jmeter plugin -https://jmeter-plugins.org/
11. Download the required plugin 
      PerfMon (Servers Performance Monitoring) 
      Custom Thread Groups
      dummy sampler - to validate the lister,etc
      Throughput shaping timer
      custom jmeter function 
      flexible file writer
      inter-Thread communciation - sync seperate threads
      Json plugin -json to xml
      3 basic graphs - response time+
12. Unzip and copy all the jar file in the plugin and place the jar file in jmeter/lib/ext folder
13. Restart jmeter
	
