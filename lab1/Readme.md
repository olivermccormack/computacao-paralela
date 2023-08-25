Eric Akio Uchiyamada TIA: 42107865

Oliver Kieran Galvão McCormack TIA: 42122058

Pedro Loureiro Morone Branco Volpe TIA: 4213193

1 sudo dnf install git gcc

2 mkdir computacao-paralela

3 cd computacao-paralela

4 git init

5 shh-keygen

6 ssh-keygen

7 cat /home/ec2-user/.ssh/id_rsa.pub

8 mkdir lab1

9 cd lab1

10 vi hello.c

11 gcc -o hello.bin hello.c

12 ./hello.c

13 vi README.md

14 ls

15 cd ..

16 git status

17 git add lab1

18 git commit -m "Add lab1"

19 git remote -v

20 git remote add origin git@github.com:olivermccormack/computacao-paralela.git

21 git branch -M main

22 git push -u origin main

23 git remote -v

24 git push origin main

25 cd lab1

26 history
