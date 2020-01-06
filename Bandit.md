`ssh bandit0@bandit.labs.overthewire.org -p 2220 -o 'IdentitiesOnly yes'` -p for port -o 'IdentitiesOnly yes' to ensure it does not take any other identity.<br/>
If file name is open tht as `./-`<br/>
if there are spaces in file name put a `\` in fron t of space<br/>
`ls -altr` list hidden files <br/>
`find . -type f -readable ! -executable -size 1033c` finds file of specific size and type <br/>
`find / -user bandit7 -group bandit6 -size 33c 2>/dev/null` 2 means error stream last part is sending error to black hole<br/>
`cat data.txt | grep millionth` in data.txt grep word next to millionth <br/>
`cat data.txt | sort |uniq -u` find line which has single occurence<br/>
`strings data.txt | grep "="` strings prints printable characters atleast 4 chars must<br/>
`cat data.txt| base64 -d -i` base64 is used to decode with -d flag -i ignores unrecongnisable characters<br/>
`tr 'A-Za-z' 'N-ZA-Mn-za-m'` tr is used to replace a characters set1 is A-Z will be translated to N-ZtoA-M similar of a-z<br/>
