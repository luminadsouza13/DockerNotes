VM is hardware abstraction - where it takes physical CPU , RAM from a host and divides across all several smaller VMs. There is an 
OS and Application running inside it. When it has to boot up , it has to emulate/initiate all harsware stack , boot OS and 
then launch app

Whereas, Docker is an container abstraction where it focus really on OS and application, and not much on hardware abstraction. 
It took second to launch the application . Example : docker run alpine echo "hey". Why , it operates at application level where 
it skips what VM does like initiate hardware stack , boot OS . 

So you know now why containers are fast!






