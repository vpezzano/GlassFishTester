# To start GlassFish, run this from the command line:
asadmin start-domain domain1
# The default domain is actually domain1; so, in the previous command, we don't need to specify it.
# A domain is a container where we can deploy our applications.
# To stop GlassFish, issue the following command:
asadmin stop-domain
# The admin console of GlassFish is reachable on port 4848: http://localhost:4848