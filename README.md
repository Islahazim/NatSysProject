# Net&Sys Assignment: Running Containers for Application Development

Group Name: __Fill your team name__. 

Team Mates:
1. Muhammad Islahuddin bin Mohamad Azim 2118177
2. Muhammad Syazwan bin Mohd Saparina 2113667
3. __Fill name__ and __matric no__

## Rules
1. You are allowed to have **3 group** members.
2. When you complete the assignment, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this project repository
1. First thing you need in doing this assignment is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the Net&Sys Assignment repository in your own github account. 

    1. Go to https://github.com/ZainabBashi/NatSysProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)*** https://github.com/Islahazim/NatSysProject 
2. How many files and folders are in this repository. ***(1 mark)*** 1 Foleders and 2 Files.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own Net&Sys Assignment repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name and team members along with their matric Numbers. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** Ubuntu Linux
2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 2 cores, 8 GB RAM, and 32 GB storage, up to 32 cores, 64 GB RAM, and 128 GB storage.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** To keeps a record of changes, makes code reviews and project management more efficient

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
3. Run the command **df** . ***(1 mark)*** 
4. Run the command **du** . ***(1 mark)*** 
5. Run the command **ls** . ***(1 mark)*** 
6. Run the command **ls -asl** . ***(1 mark)***
7. Run the command **free -h** . ***(1 mark)*** 
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)***
9. Run the command **top** and type **q** to quit. ***(1 mark)*** 
10. Run the command **uname -a**. ***(1 mark)***
```bash
@Islahazim ➜ /workspaces/NatSysProject (main) $ whoami
codespace
@Islahazim ➜ /workspaces/NatSysProject (main) $ pwd
/workspaces/NatSysProject
@Islahazim ➜ /workspaces/NatSysProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
@Islahazim ➜ /workspaces/NatSysProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 14451788  16701792  47% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 21797920   8483872  72% /vscode
/dev/sdb1       46127956      104  43752276   1% /tmp
/dev/loop4      32847680 14451788  16701792  47% /workspaces
@Islahazim ➜ /workspaces/NatSysProject (main) $ du
1972    ./images
8       ./.git/objects/60
12      ./.git/objects/ff
8       ./.git/objects/c6
8       ./.git/objects/4b
8       ./.git/objects/41
12      ./.git/objects/d2
8       ./.git/objects/d8
8       ./.git/objects/e7
12      ./.git/objects/2e
8       ./.git/objects/4a
8       ./.git/objects/7b
16      ./.git/objects/fb
8       ./.git/objects/fe
12      ./.git/objects/6e
8       ./.git/objects/fa
12      ./.git/objects/1c
8       ./.git/objects/6f
8       ./.git/objects/f2
8       ./.git/objects/5b
1820    ./.git/objects/pack
12      ./.git/objects/70
12      ./.git/objects/64
12      ./.git/objects/44
8       ./.git/objects/74
8       ./.git/objects/0d
8       ./.git/objects/cb
8       ./.git/objects/58
12      ./.git/objects/14
8       ./.git/objects/3f
12      ./.git/objects/3d
12      ./.git/objects/af
8       ./.git/objects/f6
8       ./.git/objects/83
8       ./.git/objects/91
8       ./.git/objects/b2
8       ./.git/objects/3a
12      ./.git/objects/73
8       ./.git/objects/93
8       ./.git/objects/b6
8       ./.git/objects/a6
8       ./.git/objects/71
8       ./.git/objects/a3
8       ./.git/objects/04
8       ./.git/objects/2a
8       ./.git/objects/eb
8       ./.git/objects/fc
8       ./.git/objects/0e
8       ./.git/objects/49
8       ./.git/objects/4f
8       ./.git/objects/c3
8       ./.git/objects/81
12      ./.git/objects/72
12      ./.git/objects/a1
8       ./.git/objects/0b
8       ./.git/objects/1b
12      ./.git/objects/13
12      ./.git/objects/ca
8       ./.git/objects/f9
4       ./.git/objects/info
8       ./.git/objects/52
8       ./.git/objects/20
8       ./.git/objects/86
8       ./.git/objects/fd
8       ./.git/objects/cd
12      ./.git/objects/62
12      ./.git/objects/b5
12      ./.git/objects/e5
12      ./.git/objects/17
8       ./.git/objects/e9
8       ./.git/objects/47
8       ./.git/objects/24
8       ./.git/objects/96
8       ./.git/objects/b9
8       ./.git/objects/ab
2492    ./.git/objects
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/refs/tags
8       ./.git/refs/heads
8       ./.git/refs/remotes/origin
12      ./.git/refs/remotes
28      ./.git/refs
8       ./.git/info
8       ./.git/logs/refs/heads
8       ./.git/logs/refs/remotes/origin
12      ./.git/logs/refs/remotes
24      ./.git/logs/refs
32      ./.git/logs
64      ./.git/hooks
4       ./.git/branches
2668    ./.git
4660    .
@Islahazim ➜ /workspaces/NatSysProject (main) $ ls
README.md  images
@Islahazim ➜ /workspaces/NatSysProject (main) $ ls -asl
total 32
 4 drwxrwxrwx+ 4 codespace root  4096 May 18 03:38 .
 4 drwxr-xrwx+ 5 codespace root  4096 May 18 03:38 ..
 4 drwxrwxrwx+ 9 codespace root  4096 May 18 04:01 .git
16 -rw-rw-rw-  1 codespace root 12897 May 18 04:04 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 May 18 03:38 images
@Islahazim ➜ /workspaces/NatSysProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.8Gi       222Mi       1.0Mi       5.8Gi       5.7Gi
Swap:            0B          0B          0B
@Islahazim ➜ /workspaces/NatSysProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3236.942
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
top - 04:07:11 up  3:22,  0 users,  load average: 0.29, 0.21, 0.22
Tasks:  21 total,   1 running,  20 sleeping,   0 stopped,   0 zombie
top - 04:07:23 up  3:22,  0 users,  load average: 0.22, 0.20, 0.22
Tasks:  18 total,   1 running,  17 sleeping,   0 stopped,   0 zombie
%Cpu(s):  3.2 us,  3.5 sy,  0.0 ni, 93.0 id,  0.2 wa,  0.0 hi,  0.2 si,  0.0 st
MiB Mem :   7929.6 total,    171.0 free,   1855.9 used,   5902.6 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   5757.6 avail Mem 

@Islahazim ➜ /workspaces/NatSysProject (main) $
    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                  
   2170 codespa+  20   0   21.1g 354016  46464 S   1.3   4.4   0:46.56 node                     
   2130 codespa+  20   0  961448 100076  42112 S   0.3   1.2   0:06.80 node                     
   2677 codespa+  20   0  727164  62452  38528 S   0.3   0.8   0:02.22 node                     
      1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.05 docker-init              
      7 codespa+  20   0    7236   1664   1664 S   0.0   0.0   0:00.00 sleep                    
     70 root      20   0   12196   3352   2432 S   0.0   0.0   0:00.00 sshd                     
    786 root      20   0 1463360  86888  50304 S   0.0   1.1   0:00.24 dockerd                  
    793 root      20   0 1798012  44752  30336 S   0.0   0.6   0:00.46 containerd               
   1502 codespa+  20   0    2616   1536   1536 S   0.0   0.0   0:00.01 sh                       
   1581 root      20   0    2616   1664   1664 S   0.0   0.0   0:00.00 sh                       
   2122 codespa+  20   0    2624   1536   1536 S   0.0   0.0   0:00.01 sh                       
   2226 codespa+  20   0  851240  59140  38784 S   0.0   0.7   0:00.32 node                     
   3164 codespa+  20   0  623004  76872  38144 S   0.0   0.9   0:01.65 node                     
   3630 codespa+  20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh                       
   3674 root      20   0    2616   1408   1408 S   0.0   0.0   0:00.00 sh                       
   3887 codespa+  20   0   16632  11520   3456 S   0.0   0.1   0:00.18 bash                     
   5704 codespa+  20   0  606200  52824  34560 S   0.0   0.7   0:00.23 node                     
  15262 codespa+  20   0   10896   3584   3072 R   0.0   0.0   0:00.00 top                      

@Islahazim ➜ /workspaces/NatSysProject (main) $ uname -a
Linux codespaces-5cd2ef 6.5.0-1019-azure #20~22.04.1-Ubuntu SMP Wed Apr  3 03:28:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```
11. What is the available free memory in the system. The available free memory is 222 MiB.

12. What is the available disk space mounted on /workspace. ***(1 mark)*** The available disk space mounted on /workspace is 16,701,792 1K-blocks (approximately 16 GB).

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** The version is 6.5.0-1019-azure and the hardware architecture is x86_64.

14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** ls lists the names of files and directories in the current directory.
ls -asl lists files and directories with detailed information including file permissions, number of links, owner, group, size, and modification date, with all entries including hidden files, and sizes in blocks.

15. What is the TLB size of the Virtual CPU. ***(1 mark)*** The TLB size of the Virtual CPU is 5.8 GiB.

16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** The CPU speed of the Virtual CPU is 3236.942 MHz.

17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** The top running process that consumes the most CPU cycles is node with PID 2170.

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available? Yes

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```
YES
```bash 
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker stop magical_dijkstra
magical_dijkstra
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS                        PORTS     NAMES
2fa6019c4189   debian    "bash"    4 minutes ago   Exited (137) 12 seconds ago             magical_dijkstra
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker restart magical_dijkstra
magical_dijkstra
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS          PORTS     NAMES
2fa6019c4189   debian    "bash"    6 minutes ago   Up 10 seconds             magical_dijkstra
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```
The helloworld.txt is deleted since its in the container (magical_dijkstra) that was also deleted.
```bash 
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker stop magical_dijkstra
magical_dijkstra
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
2fa6019c4189   debian    "bash"    12 minutes ago   Exited (137) 48 seconds ago             magical_dijkstra
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker rm magical_dijkstra
magical_dijkstra
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker exec -i -t magical_dijkstra /bin/bash
Error response from daemon: No such container: magical_dijkstra
```
***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** This is because Docker containers are designed to be ephemeral and their primary purpose is to run processes in isolation, not to serve as permanent storage.

2. Can we run two, or three instances of debian linux? . ***(1 mark)*** Yes it can run multiple instances of debian result since each instace will run in its own isolated container, and start as many containers as your system resources allow.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** __Fill answer here__.
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
```bash
@Islahazim ➜ /workspaces/NatSysProject (main) $ cd myroot/
@Islahazim ➜ /workspaces/NatSysProject/myroot (main) $ ll
total 8
drwxrwxrwx+ 2 codespace codespace 4096 May 18 05:22 ./
drwxrwxrwx+ 5 codespace root      4096 May 18 05:22 ../
@Islahazim ➜ /workspaces/NatSysProject/myroot (main) $ sudo chown -R codespace:codespace /workspaces/NatSysProject/myroot
@Islahazim ➜ /workspaces/NatSysProject (main) $ cd ..
@Islahazim ➜ /workspaces/NatSysProject (main) $ sudo chown -R codespace:codespace myroot
@Islahazim ➜ /workspaces/NatSysProject (main) $ ll
total 44
drwxrwxrwx+ 5 codespace root       4096 May 18 05:22 ./
drwxr-xrwx+ 6 codespace root       4096 May 18 05:22 ../
drwxrwxrwx+ 9 codespace root       4096 May 18 05:15 .git/
-rw-rw-rw-  1 codespace root      24347 May 18 05:45 README.md
drwxrwxrwx+ 2 codespace root       4096 May 18 03:38 images/
drwxrwxrwx+ 2 codespace codespace  4096 May 18 05:22 myroot/
```

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** 
```bash
CONTAINER ID   IMAGE     COMMAND              CREATED          STATUS         PORTS                                   NAMES
f85e976e9404   httpd     "httpd-foreground"   5 minutes ago    Up 5 minutes   0.0.0.0:8080->80/tcp, :::8080->80/tcp   jovial_mayer
```
2. What port is the apache web server running. ***(1 mark)***
Port 80
3. What port is open for http protocol on the host machine? ***(1 mark)***
Port 8080 is open for HTTP protocol on the host machine

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** __Fill answer here__.
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
```bash
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker network ls
NETWORK ID     NAME      DRIVER    SCOPE
0911da1342e4   bluenet   bridge    local
5b57a8f13633   bridge    bridge    local
891c1aaeaa96   host      host      local
01b0524e3b27   none      null      local
92d0312e515e   rednet    bridge    local
```
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
```bash
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker inspect c1
[
    {
        "Id": "c870898289fa8847be7e1387e1eb691283de79f33e5a7bd75198cb474135ed66",
        "Created": "2024-05-18T07:03:36.601570485Z",
        "Path": "sh",
        "Args": [],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 97595,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-05-18T07:03:37.125841426Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:65ad0d468eb1c558bf7f4e64e790f586e9eda649ee9f130cd0e835b292bbc5ac",
        "ResolvConfPath": "/var/lib/docker/containers/c870898289fa8847be7e1387e1eb691283de79f33e5a7bd75198cb474135ed66/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/c870898289fa8847be7e1387e1eb691283de79f33e5a7bd75198cb474135ed66/hostname",
        "HostsPath": "/var/lib/docker/containers/c870898289fa8847be7e1387e1eb691283de79f33e5a7bd75198cb474135ed66/hosts",
        "LogPath": "/var/lib/docker/containers/c870898289fa8847be7e1387e1eb691283de79f33e5a7bd75198cb474135ed66/c870898289fa8847be7e1387e1eb691283de79f33e5a7bd75198cb474135ed66-json.log",
        "Name": "/c1",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "bluenet",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                14,
                100
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": null,
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/d8acab00a7bd5d563e98d243ffb09d9e6244a4ccc53735f6f3fbc65abef594c9-init/diff:/var/lib/docker/overlay2/99e1c718676bcb9525156651b19c24f93cd7fb9f20d6b252ccc0ebb9fd91c206/diff",
                "MergedDir": "/var/lib/docker/overlay2/d8acab00a7bd5d563e98d243ffb09d9e6244a4ccc53735f6f3fbc65abef594c9/merged",
                "UpperDir": "/var/lib/docker/overlay2/d8acab00a7bd5d563e98d243ffb09d9e6244a4ccc53735f6f3fbc65abef594c9/diff",
                "WorkDir": "/var/lib/docker/overlay2/d8acab00a7bd5d563e98d243ffb09d9e6244a4ccc53735f6f3fbc65abef594c9/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "c870898289fa",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "Tty": true,
            "OpenStdin": true,
            "StdinOnce": false,
            "Env": null,
            "Cmd": [
                "sh"
            ],
            "Image": "busybox",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "7ce437f5f8f8934473f3d60acd41894fcc93c9abebd132a2e3c286366e996eda",
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "Ports": {},
            "SandboxKey": "/var/run/docker/netns/7ce437f5f8f8",
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "bluenet": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": [
                        "c870898289fa"
                    ],
                    "NetworkID": "0911da1342e40a18c54cb6437f1fccc72515be817b4813b58c349514e74bee04",
                    "EndpointID": "0865e7238892d886977814da37f1226b30ac7c0d2f29422713365af87bec23bf",
                    "Gateway": "172.18.0.1",
                    "IPAddress": "172.18.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "MacAddress": "02:42:ac:12:00:02",
                    "DriverOpts": null
                }
            }
        }
    }
]
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker inspect c2
[
    {
        "Id": "e17ef1006433780f1f0f55594e6e4f533893b9db360fdff1481a2048c1ef1de4",
        "Created": "2024-05-18T07:03:43.053062662Z",
        "Path": "sh",
        "Args": [],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 97739,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-05-18T07:03:43.533495992Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:65ad0d468eb1c558bf7f4e64e790f586e9eda649ee9f130cd0e835b292bbc5ac",
        "ResolvConfPath": "/var/lib/docker/containers/e17ef1006433780f1f0f55594e6e4f533893b9db360fdff1481a2048c1ef1de4/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/e17ef1006433780f1f0f55594e6e4f533893b9db360fdff1481a2048c1ef1de4/hostname",
        "HostsPath": "/var/lib/docker/containers/e17ef1006433780f1f0f55594e6e4f533893b9db360fdff1481a2048c1ef1de4/hosts",
        "LogPath": "/var/lib/docker/containers/e17ef1006433780f1f0f55594e6e4f533893b9db360fdff1481a2048c1ef1de4/e17ef1006433780f1f0f55594e6e4f533893b9db360fdff1481a2048c1ef1de4-json.log",
        "Name": "/c2",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "rednet",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                14,
                100
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": null,
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/0753dd15d450789d7044a5a11b1cb7073359842270be7efb5a9ed7da23d06602-init/diff:/var/lib/docker/overlay2/99e1c718676bcb9525156651b19c24f93cd7fb9f20d6b252ccc0ebb9fd91c206/diff",
                "MergedDir": "/var/lib/docker/overlay2/0753dd15d450789d7044a5a11b1cb7073359842270be7efb5a9ed7da23d06602/merged",
                "UpperDir": "/var/lib/docker/overlay2/0753dd15d450789d7044a5a11b1cb7073359842270be7efb5a9ed7da23d06602/diff",
                "WorkDir": "/var/lib/docker/overlay2/0753dd15d450789d7044a5a11b1cb7073359842270be7efb5a9ed7da23d06602/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "e17ef1006433",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "Tty": true,
            "OpenStdin": true,
            "StdinOnce": false,
            "Env": null,
            "Cmd": [
                "sh"
            ],
            "Image": "busybox",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "3d787e0631e187992f097ee8ee9015778347217cdceb23476159d5ea65be7037",
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "Ports": {},
            "SandboxKey": "/var/run/docker/netns/3d787e0631e1",
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "rednet": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": [
                        "e17ef1006433"
                    ],
                    "NetworkID": "92d0312e515e8a8a2d15b2029cbaac8bef7a1c64506ba312db250551e2dd261a",
                    "EndpointID": "44a270e05e2ec52885a1f814b5062a1078f7140d07d68a9bb887e6ebfd9f09c5",
                    "Gateway": "172.19.0.1",
                    "IPAddress": "172.19.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "MacAddress": "02:42:ac:13:00:02",
                    "DriverOpts": null
                }
            }
        }
    }
]
```
gateway for bluenet 172.18.0.1/16
gateway rednet c2 172.19.0.1/16

4. What is the network address for the running container c1 and c2.
Network address for c1 172.18.0.2/16
Network address for c2 172.19.0.2/16

5. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)***
```bash
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker exec c1 ping c2
ping: bad address 'c2'
```

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
```bash
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker network create bridgenet
93929c3c06e4295a68a03c270bc5854a178b452b44c9867ab212ebd3fba3c0a9
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker network connect bridgenet c1
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker network connect bridgenet c2
@Islahazim ➜ /workspaces/NatSysProject (main) $ docker exec c1 ping c2
PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=0.139 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.081 ms
64 bytes from 172.20.0.3: seq=3 ttl=64 time=0.142 ms
64 bytes from 172.20.0.3: seq=4 ttl=64 time=0.090 ms
64 bytes from 172.20.0.3: seq=5 ttl=64 time=0.079 ms
64 bytes from 172.20.0.3: seq=6 ttl=64 time=0.079 ms
```
## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***30 May, 2024***
