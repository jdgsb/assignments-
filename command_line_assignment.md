'''

~                                                                                                     
▶ pwd
/home/jd

~                                                                                                     
▶ ls
bloc_assign  Documents  examples.desktop  myapp         Pictures  railsgirls     snippets.rb  Videos
Desktop      Downloads  Music             node_modules  Public    rvm-installer  Templates    wdi

~                                                                                                     
▶ ls -l
total 92
drwxrwxr-x  3 jd jd  4096 Feb 28 10:32 bloc_assign
drwxr-xr-x  7 jd jd  4096 Feb 27 14:50 Desktop
drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Documents
drwxr-xr-x  2 jd jd  4096 Jan 27 08:13 Downloads
-rw-r--r--  1 jd jd  8980 Jan 10 20:29 examples.desktop
drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Music
drwxrwxr-x 12 jd jd  4096 Jan 11 10:52 myapp
drwxr-xr-x  4 jd jd  4096 Jan 28 19:56 node_modules
drwxr-xr-x  2 jd jd  4096 Feb 24 15:54 Pictures
drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Public
drwxrwxr-x 12 jd jd  4096 Feb 24 16:22 railsgirls
-rw-rw-r--  1 jd jd 22817 Feb 26 09:50 rvm-installer
-rw-rw-r--  1 jd jd    19 Feb 24 16:30 snippets.rb
drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Templates
drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Videos
drwxrwxr-x 20 jd jd  4096 Jan 27 15:39 wdi

~                                                                                                     
▶ cd ~

~                                                                                                     
▶ pwd
/home/jd

~                                                                                                     
▶ ls
bloc_assign  Documents  examples.desktop  myapp         Pictures  railsgirls     snippets.rb  Videos
Desktop      Downloads  Music             node_modules  Public    rvm-installer  Templates    wdi

~                                                                                                     
▶ mkdir code

~                                                                                                     
▶ cd code

~/code                                                                                                
▶ pwd
/home/jd/code

~/code                                                                                                
▶ cd ..

~                                                                                                     
▶ cd code

~/code                                                                                                
▶ man mkdir

~/code                                                                                                
▶ q
zsh: command not found: q

~/code                                                                                               ⍉
▶ rm snippets.rb
rm: cannot remove ‘snippets.rb’: No such file or directory

~/code                                                                                               ⍉
▶ cd   

~                                                                                                     
▶ rm snippets.rb 

~                                                                                                     
▶ touch snippets.rb

~                                                                                                     
▶ ls -ls
total 92
 4 drwxrwxr-x  3 jd jd  4096 Feb 28 10:32 bloc_assign
 4 drwxrwxr-x  2 jd jd  4096 Feb 28 11:36 code
 4 drwxr-xr-x  7 jd jd  4096 Feb 27 14:50 Desktop
 4 drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Documents
 4 drwxr-xr-x  2 jd jd  4096 Jan 27 08:13 Downloads
12 -rw-r--r--  1 jd jd  8980 Jan 10 20:29 examples.desktop
 4 drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Music
 4 drwxrwxr-x 12 jd jd  4096 Jan 11 10:52 myapp
 4 drwxr-xr-x  4 jd jd  4096 Jan 28 19:56 node_modules
 4 drwxr-xr-x  2 jd jd  4096 Feb 24 15:54 Pictures
 4 drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Public
 4 drwxrwxr-x 12 jd jd  4096 Feb 24 16:22 railsgirls
24 -rw-rw-r--  1 jd jd 22817 Feb 26 09:50 rvm-installer
 0 -rw-rw-r--  1 jd jd     0 Feb 28 11:38 snippets.rb
 4 drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Templates
 4 drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Videos
 4 drwxrwxr-x 20 jd jd  4096 Jan 27 15:39 wdi

~                                                                                                     
▶ cat snippets.rb 

~                                                                                                     
▶ echo hello world
hello world

~                                                                                                     
▶ echo puts \"hello world\" > snippets.rb 

~                                                                                                     
▶ cat snippets.rb 
puts "hello world"

~                                                                                                     
▶ cp snippets.rb hello.rb

~                                                                                                     
▶ mv hello.rb helloworld.rb

~                                                                                                     
▶ rm helloworld.rb 

~                                                                                                     
▶ ls -l
total 96
drwxrwxr-x  3 jd jd  4096 Feb 28 10:32 bloc_assign
drwxrwxr-x  2 jd jd  4096 Feb 28 11:36 code
drwxr-xr-x  7 jd jd  4096 Feb 27 14:50 Desktop
drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Documents
drwxr-xr-x  2 jd jd  4096 Jan 27 08:13 Downloads
-rw-r--r--  1 jd jd  8980 Jan 10 20:29 examples.desktop
drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Music
drwxrwxr-x 12 jd jd  4096 Jan 11 10:52 myapp
drwxr-xr-x  4 jd jd  4096 Jan 28 19:56 node_modules
drwxr-xr-x  2 jd jd  4096 Feb 24 15:54 Pictures
drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Public
drwxrwxr-x 12 jd jd  4096 Feb 24 16:22 railsgirls
-rw-rw-r--  1 jd jd 22817 Feb 26 09:50 rvm-installer
-rw-rw-r--  1 jd jd    19 Feb 28 11:39 snippets.rb
drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Templates
drwxr-xr-x  2 jd jd  4096 Jan 10 22:38 Videos
drwxrwxr-x 20 jd jd  4096 Jan 27 15:39 wdi

~                                                                                                     
▶ grep hello snippets.rb 
puts "hello world"

~                                                                                                     
▶ cd ..

/home                                                                                                 
▶ grep -r e code
grep: code: No such file or directory

/home                                                                                                ⍉
▶ cd 

~                                                                                                     
▶ mkdir temp

~                                                                                                     
▶ cp temp temp2
cp: omitting directory ‘temp’

~                                                                                                    ⍉
▶ rm temp
rm: cannot remove ‘temp’: Is a directory

~                                                                                                    ⍉
▶ cp -r temp temp2

~                                                                                                     
▶ rm -r temp2

~                                                                                                     
▶ ls -l temp
total 0

~                                                                                                     
▶ cat code/snippets
cat: code/snippets: No such file or directory

~                                                                                                    ⍉
▶ 

'''