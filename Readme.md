# EXERCICE SYS 1 - STD22033/H2

## NIVEAU 0

ssh bandit@bandit.labs.overthewire.org -p 2220 <br>
**Mot de passe : bandit0**

NB : à chaque fois qu'on monte de niveau il est nécessaire d'augmenté le chiffre de l'hôte par exemple : **ssh bandit1@bandit.labs.overthewire.org -p 2220** , à partir du niveau 1, les commandes que vous devez utiliser seront en gras et les mots de passe obtenu seront indispensables pour monter de niveau.

## NIVEAU 0 -> NIVEAU 1

**ls** <br>
**cat readme** <br>
**ssh bandit0@bandit.labs.overthewire.org -p 2220** <br>
**Mot de passe : NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL**

## NIVEAU 1 -> NIVEAU 2

**ls <br>
cat ./- <br>
Mot de passe : rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgz**

## NIVEAU 2 -> NIVEAU 3

**ls <br>
cat spaces\ in\ this\ filename <br>
Mot de passe : aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG**

## NIVEAU 3 -> NIVEAU 4

**ls <br>
cd inhere <br>
cat .hidden <br>
le mot de passe est: 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe**

## NIVEAU 4 -> NIVEAU 5

**ls** <br>
**cd inhere <br>**
**ls <br>**
file ./\* <br>
**cat ./-file07 <br>**
**Mot de passe : lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR <br>**

## NIVEAU 5 -> NIVEAU 6

**ls <br>
cd inhere <br>
ls <br>
find -size 1033c <br>
cat ./maybehere07/.file2 <br>
Mot de passe : P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU <br>**

## NIVEAU 6 -> NIVEAU 7

**find / -user bandit7 -group bandit6 -size 33c <br>
cat /var/lib/dpkg/info/bandit7.password <br>
Mot de passe : z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S <br>**

## NIVEAU 7 -> NIVEAU 8

**ls <br>
grep "millionth" data.txt <br>
Mot de passe : TESKZC0XvTetK0S9xNwm25STk5iWrBvP**

## NIVEAU 8 -> NIVEAU 9

**ls <br>
sort data.txt | uniq -u <br>
Mot de passe : EN632PlfYiZbn3PhVK3XOGSlNInNE00t <br>**

## NIVEAU 9 -> NIVEAU 10

**ls <br>
strings data.txt | grep "====" <br>
Mot de passe : G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s <br>**

## NIVEAU 10 -> NIVEAU 11

**ls <br>
strings data.txt | grep "====" <br>
Mot de passe : G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s <br>**

## NIVEAU 11 -> NIVEAU 12

**ls <br>
cat data.txt | base64 -d <br>
Mot de passe : 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM <br>**

## NIVEAU 12 -> NIVEAU 13

**ls <br>
cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]' <br>
Mot de passe : JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv <br>**

## NIVEAU 13 -> NIVEAU 14

**cd /tmp/newfolder <br>
ls <br>
cat data9 <br>
Mot de passe : wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw <br>**

## NIVEAU 14 -> NIVEAU 15

**ssh -i sshkey.private bandit14@localhost -p 2220 <br>**

## NIVEAU 15 -> NIVEAU 16

**cd /etc/bandit_pass/ <br>
ls <br>
cat bandit14 <br>
echo fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq | nc localhost 30000 <br>
Mot de passe : jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt <br>**

## NIVEAU 16 -> NIVEAU 17

**cat /etc/bandit_pass/bandit15 <br>
openssl s_client -connect localhost:30001 <br>
jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt <br>
le mot de passe est : JQttfApK4SeyHwDlI9SXGR50qclOAil1 <br>**

## NIVEAU 17 -> NIVEAU 18

**nmap -A localhost -p 31000-32000 <br>
cat/etc/bandit_pass/bandit16 <br>
openssl s_client -connect localhost:31790 <br>
cd /tmp <br>
nano ssh-17.private <br>
ssh -i ssh-17.private bandit17@localhost <br>
chmod 600 ssh-17.private <br>
ssh -i ssh-17.private bandit17@localhost <br>
cat /etc/bandit_pass/bandit17 <br>
Mot de passe : VwOSWtCA7lRKkTfbr2IDh6awj9RNZM5e <br>**

## NIVEAU 18 -> NIVEAU 19

**ls <br>
diff passwords.new passwords.old <br>
Mot de passe : hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg <br>**

## NIVEAU 19 -> NIVEAU 20

**ssh -T bandit18@bandit.labs.overthewire.org -p 2220 <br>
hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg <br>
ls <br>
cat readme <br>
Mot de passe : awhqfNnAbc1naukrpqDYcF95h7HoMTrC <br>**

## NIVEAU 20 -> NIVEAU 21

**ls <br>
file bandit20-do <br>
./bandit20-do <br>
./bandit20-do cat /etc/bandit_pass/bandit20 <br>
Mot de passe : VxCazJaVykI6W36BkBU0mJTCM8rR95XT <br>**

## NIVEAU 21 -> NIVEAU 22

**ls <br>
./suconnect 1234 <br>
le mot de passe est : NvEJF7oVjkddltPSrdKEFOllh9V1IBcq <br>**

## NIVEAU 22 -> NIVEAU 23

**cd /etc/cron.d <br>
ls <br>
cat cronjob_bandit22 <br>
at /usr/bin/cronjob_bandit22.sh <br>
cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv <br>
le mot de passe est : WdDozAdTM2z9DiFEQ2mGlwngMfj4EZff <br>**

## NIVEAU 23 -> NIVEAU 24

**cd /etc/cron.d <br>
ls <br>
cat cronjob_bandit23 <br>
cat /usr/bin/cronjob_bandit23.sh <br>
echo I am user bandit23 | md5sum | cut -d ' ' -f 1 <br>
cat /tmp/8ca319486bfbbc3663ea0fbe81326349 <br>
le mot d epasse est : QYw0Y2aiA672PsMmh9puTQuhoz8SyR2G <br>**
