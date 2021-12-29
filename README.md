# maven
for deploy to artifact to nexus we need use the below command
here nexus user name is admin and passwd used it root. It will be different based on the credentails given to nexus. Here we are not hardcoded in the setting.xml file 
we are passing credentails as parameters.


mvn  -Drepo.id=myRepo -Drepo.login=username -Drepo.pwd=password clean install
