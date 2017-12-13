Modified by N3r3var1n3(Michael Hoffman)


This is a modified version of the Shadow Brokers tool Doublepulsar

What you need to do to run the Fuzzy bunch tool is

Python 2.6 https://www.python.org/download/releases/2.6/

Pywin32 212 https://sourceforge.net/projects/pywin32/files/pywin32/Build%20212/

You will also need to modify the Fuzzybunch.xml file and change the file path of the following to the location of the shadowbroker master location

<t:parameter name="ResourcesDir"
                 description="Absolute path of the Resources Directory"
                 type="String"
                 default="C:shadowbroker-master\Resources"/>
				 

				 
<t:parameter name="LogDir"
                 description="Absolute path of an Initial Log Directory"
                 type="String"
                 default="C:\logs"/>