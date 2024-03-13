# sustainability


# VEEAM 

## Start virtual veeam-backup-host 30min before backup job
command prompt: echo shutdown -s > shutdown.bat
## in veeam: Job > Storage section > Advanced button > Scripts tab - run the following script after the job: shutdown.bat


