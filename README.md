# Bip39 Super Fast Generator for BTC Crypto

This uses automated python scripts to generate 3,6, and 12 random word phrases to use with brainflayer, The speed on this is super fast

# Usage

Just running the script from the commandline will randomly generate 3, 6, 12 BIP39 code phrases::

	The Python Dependencies are listed below 

	- evolve roman
	- limit endeavor
	- askari cobras
	- hellspawn mystic
	- manpower anvil


Running the script is simple

EXAMPLE:


Make it super simple I have encluded the BIP39.txt files for the different languages,  all you need to do is choose your target.  I will update and work on this more.. However right now all you need to do is for EXAMPLE
english, copy the english.txt to wordlist.txt      In unix its cp english.txt wordlist.txt    This sets up the wordlist for your target or you can use the -w flash for wordlist file

./generate12words.py -n 5000000 >> 12words.txt

In this example the script generates 12 random words per line of a text file, the -n specifys the # of lines you wish to make your txt file, and the >> 12words.txt is the output file for writing


## Operators
* -n <number of lines you wish to create>

	* Generates <x> code phrases. Without selecting this option the default is 5.

* -p <prefix> or --prefix <prefix>

	* Generates phrases using <prefix> as the first word. Useful for related groups of code phrases.

* -w <file> or --wordlist <file>

	* Imports file to use for generating random phrases instead of the default wordlist.txt. 

Multiple operators can be used together. 

# License

Free and OpenSource to the public 

If you find this useful and wish to donate:

BTC Address:  1PJbzgqXDcbeqv2NXccQhY7HFWFxeURE22

