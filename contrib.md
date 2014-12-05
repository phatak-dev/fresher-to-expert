# Contribute
This document describes the steps to contribute to the book. All your contribution will be publicly visible on github. Also when the book completes your contribution will be acknowledged in the beginning of the book.

If you just want to report issues or review you can do that [here](https://github.com/phatak-dev/fresher-to-expert/issues)


##Building on local system
In order to contribute to the book, you should be able to build the book on your local system. Follow the below steps to build the code on your system.

* ###Install node.js

    This book uses node.js for building. So you need to have node.js in your system . The following are the commands to install node.js on ubuntu system. Preferably, node v0.10.15+ and npm v1.4.21+.


     	sudo apt-get install nodejs  
     	sudo apt-get install npm     
     	sudo ln -s /usr/bin/nodejs /usr/bin/node
	

* ### Install Gitbook

	This book is written using [Gitbook](https://www.gitbook.io). Install the gitbook using following command.

    	sudo npm install gitbook -g

* ###Clone the code

         git clone https://github.com/phatak-dev/fresher-to-expert.git

* ###Build

        gitbook serve fresher-to-expert
You can view the book at [localhost:4000](http://localhost:4000)

##Contribute

You can fork my [repository](https://github.com/phatak-dev/fresher-to-expert) and make changes to your repository. Once you are happy with changes, you can give a pull request on the Github.





