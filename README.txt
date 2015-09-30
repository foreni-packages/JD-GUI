1) JD-GUI provides GUI for JAD, Java Decompiler.

2) To install this application, first install JAD using below commands:

cd /opt 
wget http://varaneckas.com/jad/jad158e.linux.static.zip -O jad_tool 
unzip ./jad_tool -d /opt/jad   
rm -rf ./jad_tool 
ln -s /opt/jad/jad /usr/bin/jad

3) Then clone/download jd-gui jar file and run it as 

java -jar ./jd-gui-1.4.0.jar 
