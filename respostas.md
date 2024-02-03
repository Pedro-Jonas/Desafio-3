# Respostas dos Desafios

## p1-b
- cd command-line-challenges && tar -xzf challenges.tar.gz

## p2-b
- cd command-line-challenges/challenges/

## p3-b
- cd command-line-challenges/challenges/ && ls

## p4-b
- mkdir foo

## p5-i
- mkdir -p foo/bar/1/2/3

## p6-b
- rm -r foo

## p7-b
- echo Hello world

## p8-b
- echo Hello World > hello.txt

## p9-b
- touch empty.txt

## p10-b
- rm empty.txt

## p11-i
- echo -n > empty.txt

## p12-i
- printf '' > empty.txt

## p13-b
- cp hello.txt goodbye.txt

## p14-b
- mv goodbye.txt hello_copy.txt

## p15-i
- diff -s hello.txt hello_copy.txt

## p16-b
- cat hello.txt hello_copy.txt > 2_hellos.txt

## p17-b
- cd command-line-challenges/challenges/ && pwd

## p18-b
- cd command-line-challenges/challenges/ && ls -l

## p19-b
- cd command-line-challenges/challenges/ && chmod 600 restricted.txt  && echo p19-b >> restricted.txt

## p20-b
- cd command-line-challenges/challenges/ && ./hello_executable

## p21-b
- cd command-line-challenges/challenges/ && chmod 700 challenge_20  && ./challenge_20

## p22-b
-cd command-line-challenges/challenges/ && gcc compile_me.c  && ./a.out

## p23-a
- cd command-line-challenges/challenges/ && ./redirect > output.txt

## p24-b
- date

## p25-b
- top

## p26-b
- nproc

## p27-b
- uname -r

## p28-b
- cd command-line-challenges/challenges/bunch_of_files/ && grep -r 'You found the needle in the haystack!'

## p29-b
- cd command-line-challenges/challenges/ && head -n 25 people.csv

## p30-b
- cd command-line-challenges/challenges/ && tail -n 25 people.csv

## p31-i
- cd command-line-challenges/challenges/ && diff greeting1.txt greeting2.txt

## p32-i
- echo Hello && sleep 5 && echo world!

## p33-i
- dd if=/dev/zero bs=1024 count=1024 > zeros

## p34-i
- dd if=/dev/urandom of=random bs=2028 count=1000

## p35-i
- cd command-line-challenges &&  wc -l README.txt

## p36-b
-  cd command-line-challenges &&  tac README.txt

## p37-i
- cd command-line-challenges/challenges/ && head people.csv | cut -d , -f 2

## p39-a
- cd command-line-challenges/challenges/ && cut -d , -f 2 people.csv | sort | uniq | wc -l 