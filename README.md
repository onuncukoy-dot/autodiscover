# xiaodaor

#whois scope

``for i in `cat scope` ; do 
a=$(whois $i  | grep -E 'target')
echo $i  $a | tee -a test5;done``

#bash bruteforce
```
while read sub ;do if host "$sub.example.com" &> /dev/null/ ; then echo "$sub.example.com" fi done <dnswodlist.txt

```

```
 grep --color=ayways  -iEoh 'comp=([a-zA-Z]+)&' | sed 's/comp=//g'|sed 's/\&//g' | sed 's/nodewep//g' 
 ```



