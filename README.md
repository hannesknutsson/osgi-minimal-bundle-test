# osgi-minimal-bundle-test
A test project for trying to create a osgi bundle so that I can learn to use the OSGI framework


# Test in karaf

Download and start karaf. In karaf shell type

	install -s mvn:com.github.hannesknutsson/TestBundle/1.0-SNAPSHOT
	
For tutorials see http://liquid-reality.de/Karaf-Tutorial/
	
# Test in bndtools

Download bndtools in eclipse using the marketplace.

This provides a nice editor for .bnd and .bndtools files.

Try the app.bndrun to start or debug your bundle in felix.

For tutorials see https://enroute.osgi.org/tutorial/030-tutorial_microservice.html
