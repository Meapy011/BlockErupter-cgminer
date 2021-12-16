# BlockErupter-cgminer

# Currently only works up to Raspberry Pi Buster OS


cgminer for BlockErupters and Bitmain USBs

Usage:

First run the AutoInstaller to compile and install cgminer.

	$ ./AutoInstaller

Wait for the AutoInstaller to finish and then use the Worker Generator to make executable bash file for running miner.

	$ ./Worker-Generator

First, choose a name for the bash script to be saved as, no spaces allowed.

	  Save As:
	  Exampe

Second, Insert chosen pool url.

	  Pool URL:
	  solo.ckpool.org:3333

Third, Insert worker name for selected pool.

	  Pool Worker:
	  bc1q2ccsfq03emnku5vc0ezkmrnt4vfce0dsnxk02w.01

Forth, Insert worker password.

	  Worker Password:
	  x

Once that's done, run the script just made with ./ infront of the name.

	$ ./Example

If all is done well, you should see something like this.

	 cgminer version 4.11.1 - Started: [1970-01-01 02:02:11.712]
	--------------------------------------------------------------------------------
	 (5s):437.7M (1m):349.0M (5m):338.0M (15m):317.7M (avg):335.3Mh/s
	 A:189  R:0  HW:3  WU:4.6/m
	 Connected to solo.ckpool.org diff 1 with stratum as user bc1q2ccsfq03emnku5vc0ezkmrnt4vfce0dsnxk02w
	 Block: 47c6f90d...  Diff:24.2T  Started: [02:38:47.684]  Best share: 117
	--------------------------------------------------------------------------------
	 [U]SB management [P]ool management [S]ettings [D]isplay options [Q]uit
	 0: AMU 0       :                         | 216.9M / 334.8Mh/s WU:4.6/m
	--------------------------------------------------------------------------------
	 [1970-01-01 02:33:44.339] Accepted dc1013fa Diff 1/1 AMU 0
	 [1970-01-01 02:34:35.295] Accepted 49805e7c Diff 3/1 AMU 0
	 [1970-01-01 02:34:42.426] Accepted 9f36a496 Diff 2/1 AMU 0
	 [1970-01-01 02:35:08.329] Accepted 10cc6254 Diff 15/1 AMU 0
	 [1970-01-01 02:35:11.795] Accepted 56a9d5af Diff 3/1 AMU 0
	 [1970-01-01 02:35:27.545] Accepted 42c708cb Diff 4/1 AMU 0
	 [1970-01-01 02:35:31.632] Accepted 4e2ef53b Diff 3/1 AMU 0
	 [1970-01-01 02:35:40.789] Accepted 3642a137 Diff 5/1 AMU 0
	 [1970-01-01 02:35:44.017] Accepted eff2e74f Diff 1/1 AMU 0
	 [1970-01-01 02:36:04.264] Accepted 6649235a Diff 3/1 AMU 0
	 [1970-01-01 02:36:09.386] Accepted 11def29c Diff 14/1 AMU 0
	 [1970-01-01 02:36:29.538] Accepted b22f78a3 Diff 1/1 AMU 0
	 [1970-01-01 02:36:55.325] Accepted 053c6236 Diff 49/1 AMU 0
	 [1970-01-01 02:37:37.283] Accepted 47c1407b Diff 4/1 AMU 0
	 [1970-01-01 02:37:41.063] Accepted b6200d85 Diff 1/1 AMU 0

# Using the Shortcut-Generator

First run the Shortcut-Generator.

	  $ ./Shortcut-Generator

Second, type in the name of the file you made with the worker-generator.

	  Bash File:
	  Example

Once done there should be a Shortcut on the desktop of your machine.

When doubletapping the shortcut select run in terminal option.


