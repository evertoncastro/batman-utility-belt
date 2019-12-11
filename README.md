# My personal utility belt

A project to record my utility tools and terminal commands.


# VIM

- How to search words on **vim**. Type a slash (/) followed by the term you want to find. To search for all subsequent word with the same term type (n) to backward press (N).  
  

# Files and directories

- Get the total files inside a directory recursively: ```find . -type f | wc -l```

# GCloud

- Copy files from bucket to local machine: ```gsutil cp -r gs://bucket_name/ /local/directory```

- Download logs to local tile: ```gcloud logging read "resource.type=gae_app resource.labels.module_id=promox2019 logName=projects/pdbcontest/logs/appengine.googleapis.com%2Frequest_log" > log.json```

# FIles

- Zip file with password on UNIX: ```zip -er [archive_to_be_created] [origim_file_or_folder]```

# Mysql

- Export Dump file in background

```
nohup nice mysqldump -h127.0.0.1 -u[user] -p[password] database table > file.sql &
```
This command will give you a PID
Check the PID status with this command
```
ps aux | grep 1265
```



# Tools

- Lib to execute local security web application tests
https://www.arachni-scanner.com/ | https://github.com/Arachni/arachni/wiki/Command-line-user-interface#version
