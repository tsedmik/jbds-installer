# JBDS Installer
This projects provides various configurations for installing JBT/JBDS with specified features.

## Installation
To install JBT/JBDS follow these steps:

        $ git clone git://github.com/apodhrad/jbds-installer.git
        $ cd jbds-installer
        $ cd jbt-4.0.1.Final		# or other configuration folder
        $ mvn clean verify

For faster installing JBDS-IS you can install it from zip, just use profile _zip_

        $ mvn clean verify -Pzip    	# the zip file is cached

