# xiaodaor

#whois scope

``for i in `cat scope` ; do 
a=$(whois $i  | grep -E 'target')
echo $i  $a | tee -a test5;done``
