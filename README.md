FoBo module demo
----------------

This is a Lift FoBo module demo that demonstrates the use of the FoBo Lift module. 
See the [FoBo - Lift Front-End Toolkit Module](https://github.com/karma4u101/FoBo).

Demonstration of this module demo is set up and live [here](http://www.media4u101.se/fobo-lift-template-demo/). 
The corresponding FoBo module is available [here](https://github.com/karma4u101/FoBo). .

Note: This was initially intended to be a basic/starter lift template with the FoBo module initiated 
but it has turned out more of a separate demo. There are lots of basic lift templats out there, fork 
the demo, run it and look at the code and its examples. It's really simple to integrate the FoBo module 
in any lift project but if you are looking for a good basic lift starter template try out 
[this one](https://github.com/heiflo/lift-basic-2.4-sbt-0.11.2) or maybe my 
[Templating-With-Twitter-Bootstrap](https://github.com/karma4u101/Templating-With-Twitter-Bootstrap) 
suits your needs, be sure to correct the module version in build.sbt as it may lag behind.  

Improvements, contributions and suggestions are welcome!

best regards Peter Petersson 

Quick Start
-----------
Prerequisites for running this Lift example is that you have the FoBo module, Git and Java installed and configured on the target computer.
You don't need to use it but the project also includes a Eclipse plug-in for browsing and following/working with the code, see the Scala IDE section.   

1) Get the examples

	git clone git@github.com:karma4u101/FoBo-Lift-Template.git
	cd FoBo-Lift-Template

2) Update & Run Jetty

There is also a sbt.bat for windows users.

	./sbt update ~container:start

3) Launch Your Browser
	
	http://localhost:8080

Scala IDE for Eclipse
---------------------
Sbteclipse provides SBT command to create Eclipse project files

1) Usage

	project$ ./sbt
	> eclipse 

2) In eclipse do: 

	File ==> Import...
	Select General ==> Existing Project into Workspace 
	Use "Brows" to look up the project root ....

User powered basic example 
==========================
**(*)** This is a _unofficial_ Lift user powered basic assembly example which means it is a work based on the 
sound foundation of Lift and done by a developer who uses Lift for development ;), sharing it with others. 