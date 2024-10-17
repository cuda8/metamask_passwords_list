# Metamask passwords list - for sale $400

Passwords from empty wallets, as well as from ledgers.<br>
Designed to clear your hashlist from already found passwords.<br>
Find 100-1000 hashes and remove them from your hashlist.<br>
This will save you not only a solid amount of money on brute force, but also time.<br>
To understand, to find one password you need a lot of cards, rules, dictionaries and from $10-100 for electricity.<br>
Having cleared, you will not waste GPU resources and time on empty wallets or ledgers.<br>

<b>There are 2 files in the zip archive:</b><br>

<b>pass.txt</b> - 33,451 private passwords from metamask wallets.<br>
Passwords were collected from 3 private pools over the course of two years.

<b>BONUS.txt</b> - 2,275,807 public passwords from metamask wallets.<br>
Passwords from public hashes from private logs, free logs, top passwords, antipublic...

Run: ```hashcat.exe -D 2 -w 4 -S -m 26600 -a 0 hashes.txt pass.txt -o FOUND.txt```<br>
Run: ```hashcat.exe -D 2 -w 4 -S -m 26600 -a 0 hashes.txt BONUS.txt -o FOUND.txt```<br>

or linux<br>

Run: ```./hashcat -D 2 -w 4 -S -m 26600 -a 0 hashes.txt pass.txt -o FOUND.txt```<br>
Run: ```./hashcat -D 2 -w 4 -S -m 26600 -a 0 hashes.txt BONUS.txt -o FOUND.txt```

*For metamask-short... hashes use -m 26610

:floppy_disk: [Download zip archive](https://github.com/private-soft/metamask_passwords_list/raw/refs/heads/main/Metamask_pass.zip)<br>
:coin: Buy password for archive: https://t.me/send?start=IVQjT7otdmsE <br>
:key: After payment, the bot will send you a password for the archive
