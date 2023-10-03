# Lab 1 Blog
Showing the three commands of filesystem commands

Code for CD

## Without argument:
```
    [user@saharra ~]pwd
    /home
    [user@saharra ~]cd
        
    [user@saharra ~]pwd
    /home
```
Results:    
    ![Image](Cd_no_arg.PNG)

Note:
    Nothing changed, no directory change


&nbsp;
&nbsp;
&nbsp;


## Path to a directory as an argument:
```
    >[user@saharra ~]pwd
    >/home
    >[user@saharra ~]cd lecture1/
    >
    >[user@saharra ~/lecture1]pwd
    >/home/lecture1
```
Results:    
    ![Image](withpatharg.PNG)

Note:
    Directory changed to the argument directory 


&nbsp;
&nbsp;
&nbsp;


## Path to a file as an argument:
```
    >[user@saharra ~/lecture1]pwd
    >/home/lecture1
    >[user@saharra ~/lecture1]cd lecture1/en-us.txt
    >bash: cd: messages/en-us.txt: Not a directory
```
Results:    
    ![Image](withfilearg.PNG)

Note:
    Directory cannot be changed to a file, throws an error


&nbsp;
&nbsp;
&nbsp;


## No argument:
```
    >[user@saharra ~/lecture1]ls
    >Hello.class  Hello.java  messages  README
```
Results:    
    ![Image](lsnoarg.PNG)

Note:
    Shows the next level files on the current directory


&nbsp;
&nbsp;
&nbsp;


## Path to a directory as an argument:
```
    >[user@saharra ~/] ls lecture1/messages/
    >en-us.txt  es-mx.txt  zh-cn.txt
```
Results:    
    ![Image](laargtodirectory.PNG)

Note:
    Shows the next level files of the directory was input


&nbsp;
&nbsp;
&nbsp;


## Path to a file as an argument:
```
    >[user@saharra ~/]ls lecture1/Hello.class
    >lecture1/Hello.class
   
```
Results:    
    ![Image](lsargtofile.PNG)

Note:
    Shows the directory to the file



&nbsp;
&nbsp;
&nbsp;


## No argument:
```
    >[user@saharra ~/lecture1]pwd
    >/home/lecture1
    >[user@saharra ~/lecture1]cd lecture1/en-us.txt
    >bash: cd: messages/en-us.txt: Not a directory
```
Results:    
    ![Image](withfilearg.PNG)

Note:
    Directory cannot be changed to a file, throws an error


&nbsp;
&nbsp;
&nbsp;


## Path to a directory as an argument:
```
    >[user@saharra ~/lecture1]pwd
    >/home/lecture1
    >[user@saharra ~/lecture1]cd lecture1/en-us.txt
    >bash: cd: messages/en-us.txt: Not a directory
```
Results:    
    ![Image](withfilearg.PNG)

Note:
    Directory cannot be changed to a file, throws an error



&nbsp;
&nbsp;
&nbsp;


## Path to a file as an argument:
```
    >[user@saharra ~/lecture1]pwd
    >/home/lecture1
    >[user@saharra ~/lecture1]cd lecture1/en-us.txt
    >bash: cd: messages/en-us.txt: Not a directory
```
Results:    
    ![Image](withfilearg.PNG)

Note:
    Directory cannot be changed to a file, throws an error



&nbsp;
&nbsp;
&nbsp;

