# gitskills
# just change
# today is 2016.05.31
1.Checking the version:

➜ a git:(master) git --version
git version 1.8.1.5

2.Checking the actual branch configuration list:

➜ a git:(master) git config --list --local
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true

3.Adding a new configuration as informed:

➜ a git:(master) git config core.sharedrepository 1

4.Checking that this configuration was added:

➜ a git:(master) git config --list --local
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
core.sharedrepository=1

5.Adding a new configuration to show that there isn't errors:

➜ a git:(master) git config user.name abv 

6.Listing all values again:

➜ a git:(master) git config --list --local
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
core.sharedrepository=1
user.name=abv

7.Changing core.sharedrepository to other valid boolean value:

➜ a git:(master) ✗ git config core.sharedrepository on
➜ a git:(master) ✗ git config --list --local
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
core.sharedrepository=on
user.name=abv

    The values following the equals sign in variable assign are all either a string, an integer, or a boolean. Boolean values may be given as yes/no, 1/0, true/false or on/off. Case is not significant in boolean values, when converting value to the canonical form using --bool type specifier; git config will ensure that the output is "true" or "false". http://git-scm.com/docs/git-config/1.8.1.5

	
	#Today is 2016.06.01
	just test