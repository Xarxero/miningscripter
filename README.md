# ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) Miningscripter

**INFO** **Miningscripter v.1.4.0 (beta) in testing-phase/pre-build**

**Miningscripter v.1.4.0 (beta)**
ANON-Scripter for an automated script needed for the miner.
Default server is the official ANON-Miningpool with the difficulty port of "0.1".


## ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) Table of Contents

- [Build](#build)
	- [Windows](#windows)
	- [Linux](#linux)
	- [Mac](#mac)
- [Issues](#issues)
- [Miners](#miners)
- [Development](#development)
- [Contact](#contact)
- [About](#About-this-project)


**Miningscripter is unfinished and highly experimental.** Use at your own risk.
<!-- ### Any optional sections -->


## ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Build
This GUI will let the user enter all the parameters as simple as possible. It will create the script in the correct folder near to an $ANON compatible miner and than automatically execute the miner with the correctly installed script ✔️


### Windows
Download the files and locate them in any directory. The miner is contained within the scripter.

Run the scripter ```Miningscripter.exe```

**WARNING** Depending on your installed Anti-Virus software, this program might be detected as a 'Trojan'!
This problem occurs due the injection of the ```.dll files``` of the miner and general functionality of the scripter.
If you still run into erros, please contact the [Technical support](https://t.me/anontechnicalsupport).

### Linux
Linux is currently not supported!

### Mac
Mac is currently not supported!


## ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Issues
**WARNING** If you run into problems while launching the application, there might be issues with the dependencies or the current version. In this case replace the miningscripter application in your main folder with the one in the ```/backup``` folder!

Bugfixing is currently in an early alpha state either and can be reported here [Issues!](https://github.com/Xarxero/miningscripter/issues)


## ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Miners
**Currently supported Miners:**

-[GMiner CUDA Equihash Miner v1.18](https://bitcointalk.org/index.php?topic=5034735.0)

-[EWBF Cuda Equihash Miner v0.6/v0.5](https://bitcointalk.org/index.php?topic=4466962.0)


## ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Development

Inofficial state of development: **Miningscripter v.1.3.5 (early-alpha)**

![alt text](https://github.com/Xarxero/miningscripter/blob/master/miner_example.jpg)
- The following functionality has been implemented so far.
	- Detection of your installed GPU and number of devices being installed
	- Implementation of EWBF-miner into the application itself
	- Checking if the current graphics driver is up to date
	- Default $ANON server and port comboboxes (additional can be added in the future)
	- Input of the worker, username or miner
	- Input of an regular T-$ANON walletaddress (checking if the address format is acceptable)
	- Auto generate a 16-digit random password for the scriptfile
	- "Script!" generates the batchfile for the miner
	- Auto implementation and run the miner
	- Funtion to save and open your generated config


## ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) Contact

- Visit the ANON-Technical support for help and more information.
	- Telegram: https://t.me/anontechnicalsupport
  	- Discord: https://discord.gg/hjeBaBx
	
For more information regarding ANON, please refer to the [disclosure](https://www.anonfork.io/disclosure) page.


## ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) About this project

Please consult 'Xarxero' if you want to contribute to this project. Improvement proposals are welcomed.

Please note, issues submitted on platforms such as Reddit, Discord or Telegram will not be considered issues unless they are officially posted on the [Miningscripter issues](https://github.com/Xarxero/miningscripter/issues) page.
