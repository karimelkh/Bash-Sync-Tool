# Bash Sync Tool

A simple tool to sync directories and backups written in bash.


## Usage:

Here is the usage instructions:

_**NOTE:** We've put together some detailed usage instructions, but don't worry – you don't have to follow every step.
We've provided comprehensive guidance to cover all scenarios, so feel free to skip any parts that don't apply to your needs.
It's all about giving you the flexibility to make the most of our project, whether you're a beginner or an advanced user._

1. Download (or clone) the repository. Manually or using command line:
	1. Manually:
		1. Click the **Code** button.
		2. Click **Download ZIP**.
		3. extract the downloaded archive.

	2. Using the command line:
		1. Ensure that you have **git** installed. If not you can type:
			```
				sudo apt update && sudo apt upgrade
				sudo apt install git
			```

		2. Clone repository using:
			```
				git clone https://github.com/karimelkh/Bash-Sync-Tool.git
			```

2. Edit the `sync_tool.conf` file that includes the source and the destination directories (folders) paths to sync when running `sync_tool.sh` script. **(Open the sync_tool.conf for more details)**.

3. Change the **sync_tool.sh** execution permissions. using:
	```
		chmod +x sync_tool.sh
	```

4. Execute the script using:
	```
		./sync_tool.sh
	```


## Todos

- [ ] Add logs file that saves the synced folders and more...
- [ ] Add the max size feature


## Contact

If you have any questions, feedback, or suggestions, feel free to [send an email](mailto:karimelkhanoufi22@gmail.com).
