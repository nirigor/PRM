# Parallel RM (PRM) for Linux Distributions.

The purpose of this utility is to speed up deletion of directories with large amount of files by utilizing threading.



# prm --help
usage: prm [-h] [-t [THREADS]] [-v] [-f] Path

Remove a directory tree in parallel using several threads

positional arguments:
  Path                  The directory path you wish to delete

optional arguments:
  -h, --help            show this help message and exit
  -t [THREADS], --threads [THREADS]
                        Number of threads to run the delete operation,
                        (Default: 10)
  -v, --verbose
  -f, --force           Do not prompt
