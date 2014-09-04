## Install

	cd ~/Desktop/openFrameworks/apps

	git clone https://github.com/patriciogonzalezvivo/sims2014_students.git

	cd sims2014_students

	git pull && git submodule init && git submodule update && git submodule status

	git submodule foreach git checkout master

	git submodule foreach git pull

## IMPORTANT

* Your homework repo should be inside ```openFrameworks/app``` folder. Inside to maintain the “3 levels down rule“ your homework should be all in the same folder. NO SUBFOLDERS. You can organize it by [WEEK_NUMBER]_[HOMEWORK_NUMBER]_[NAME]. For Example:

	- w01_h01_blabla
	- w01_h02_blabla
	- w02_h01_blabla 
 
* Remember to add a [```.gitignore```](https://gist.github.com/ofZach/3707086). This will tells git to avoid certain files, such as compiled object code, .app / .exes, etc. It keeps your repos slim and lightweight and helps you avoid committing unnecessary things. (Beside [Zach’s gitignore](https://gist.github.com/ofZach/3707086 you can make your using [this site](http://www.gitignore.io/) ). Also you can use the one from the sims repo. For example, inside your private homework folder do:

	cp ../../sims2014/.gitignore .


