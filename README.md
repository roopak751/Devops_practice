# linux-basic-commands
Basic Commands for Linux
1. **man [command name]** - Manual command 
2. **clear** - clear the terminal
3. **pwd** - present working directory 
4. **cd** - change directory 
5. **echo** “abc”- print something in the terminal
6. **whoami** - current user of the system 
7. **su** - switch to root user 
8. **sudo bash** - switch to root user 
9. **su [username]** - switch to specific user
10. **sudo useradd [username]** - add user in unix system
11. **sudo passwd [username]** - add password to that user 
12. **sudo userdel [username]** - delete that user 
13. **touch [filename]** - create a file 
14. **cat [filename]** - show the content of file in terminal 
15. **cp [source_file] [destination_path]** - to copy file 
16. **cp -R [source_dir] [destnation_path]** - to copy dir 
17. **mv [filename] [destnation_path]** - to move files 
18. **mv [filename same dir ] [newfilename same dir]** - to rename file 
19. **rm [filename]** - to remove file 
20. **rm -r [dir]** - to remove files and dir
21. **mkdir [dir name]** - to create a new dir 
22. **grep [word] [filename]** - to search for the word in the file
23. **sort [filename]** - to print content in the file [a-z] order in the terminal 
24. **chown [username] [filename]** - change the owner of the file
25. **chmod [code] [filename]** - give permission to the file (r,w,x) (4,2,1)
26. **lsof** - list of open files
27. **id** - id of current user 
28. **tar -cvf [filename.tar] [dir]** -  to zip the file (v-verbos , f-filename)
29. **gzip [filename.tar]** - to compress the zip file 
30. **gunzip [filename.gz]** - to unzip file 
31. **tar -tvf [filename.tar]** - to view the content of the file
32. **tar -xvf [filename.tar]** - to extract the content of the file 
33. **cut [c-column-number] [filename]** - to cut and print the selected column into the terminal 
34. **sed 's/old_pattern/new_pattern/** - replace the old pattern to new pattern 
35. **dd if=[source-file] of=[new-file-name]** = to copy or rename files
36. **free** - display about system memory
37. **ssh [hostname]@[ip of other server]** - to access the other server from my server
38. **ssh-keygen -t rsa** - to generatet key
39. **netstat** -  to see the network and its running ports
40. **nslookup [domain address]** - show the dns propeties of the domain 
41. **curl [option] [url]** - get or post in cmd
42. **service iptables stop** - to stop the firewall
43. **df**  - to display amount of disk space being used by the system
44. **sudo du -h -d 1 /var/** - to see which location is consuming lot of disk space
