# Terminal  

make directory = mkdir Name  
change directory = cd Name  
  inside a directory, to read the content = ls  
  to see all files = ls -a  
  to see a ling list = ls -l  
  both = ls -la  
  . current directory .. upone level   
    
  make a file = touch Name1 (of the file)  
  open file == open *name of the file*  
  copi a file == cp *name of the file we wanna copie* and*name of the new copie*  
  man cp you see all of the options  
  min *command*= look fr the utilities  
  moved a file == mv *name of the file* and *the folder you want it to put it*  
  cd ~/Namerepository  
  remove = rm     
 cd ~ = home folder or just cd   
  $ = log in as a standar user  
  pwd = currently working directory  
  
  work in an other directory = pushd/ nameDirectory  
  come back to the one before = popd  
  to see what is in a file =  file .Name  
   find a file = located name  
   find . -type d == find for directories no files in my directory
   """          f === all the files  
   all the files thaat have been modified in the last 10 mins == find . -type f -mmin -10 or +10 more that 10..  
   intervalo de tiempo  find . -type f -mmin +10 -mmin -10 
   dias== mtime  
   looking for size  
    find . -size  - or + 5M
    find . -empty 
    
  Permission
       find . -perm 777
   
  look for commands = wich nameComand   
  
## Sudo  
made changes in the directory  
su - *Name of a usuario*--> entras en otro usuario
exit for getting out  
users users in the system  
id gives information of th user  

Change commands  
chmod +x *number of the file*
licencias para cada usuario  
where r read  
      w write  
      x expeded  

# Look for a sentence in a txt file.  
grep "sentence" file.txt  
grep -w "sentence" file.txt--> only if the sentence is exacly 
-wi lower version of the sentence   
grep "..." any character  

