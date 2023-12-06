### LAB 3
### Write a script called mycase, using the case utility to checks the type of character entered by a user:
#### Upper Case.
#### Lower Case.
#### Number.
#### Nothing.
![1 1](https://github.com/menna-abdallah/Linux-Bash/assets/139376864/dcec6a4f-0eb6-4a3b-ac14-8b0ea5dc9ee1)
![1](https://github.com/menna-abdallah/Linux-Bash/assets/139376864/27030bba-fb89-47e0-8d4e-d3acf3ee3222)

### Enhanced the previous script, by checking the type of string entered by a user:
#### Upper Cases.
#### Lower Cases.
#### Numbers.
#### Mix.
#### Nothing.
![2 2](https://github.com/menna-abdallah/Linux-Bash/assets/139376864/dd2a5ff1-31dd-4301-a7de-72e81b145a91)
![2](https://github.com/menna-abdallah/Linux-Bash/assets/139376864/d95beb21-4bbc-424e-af07-3e7f2c19109f)

### Write a script called mychmod using for utility to give execute permission to all files and directories in your home directory.
![3](https://github.com/menna-abdallah/Linux-Bash/assets/139376864/eca09615-78e7-4460-9a72-3e94065744e8)
![3 1](https://github.com/menna-abdallah/Linux-Bash/assets/139376864/b00fbf78-633d-4660-9fa6-a35e22ef5863)

### Write a script called mybackup using for utility to create a backup of only files in your home directory.
![4 1](https://github.com/menna-abdallah/Linux-Bash/assets/139376864/947aadd2-6de8-4dd5-8034-e20bb0f49915)
![4](https://github.com/menna-abdallah/Linux-Bash/assets/139376864/db3f2cf9-1129-4550-a875-6fb1a5eec64f)

### Write a script called mymail using for utility to send a mail to all users in the system. Note: write the mail body in a file called mtemplate. 
### Write a script called chkmail to check for new mails every 10 seconds. Note: mails are saved in /var/mail/username.

### What is the output of the following script
typeset –i n1
typeset –i n2
n1=1
n2=1
while test $n1 –eq $n2
do
	n2=$n2+1
	print $n1
if [ $n1 –gt $n2 ]
then
	break
else
	continue
fi
n1=$n1+1
print $n2
done
### the output is 1
### Create the following menu:
Press 1 to ls
Press 2 to ls –a
Press 3 to exit  
Using select utility then while utility.

### Write a script called myarr that ask a user how many elements he wants to enter in an array, fill the array and then print it.

### Write a script called myavg that calculate average of all numbers entered by a user. Note: use arrays

### Write a function called mysq that calculate square if its argument.

