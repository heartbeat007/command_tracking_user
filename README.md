
## command for tracking all kinds of  user login in specfic time

## last -f /var/log/wtmp | grep -E '([ 1-9]|1[0-9]|2[0-9]|30)' | grep <month> | grep <day> 
last -f /var/log/wtmp | grep -E '([ 1-9]|1[0-9]|2[0-9]|30)' | grep Jan | grep Sat   

## or if you want to include year

# last -F | grep -E '([ 1-9]|1[0-9]|2[0-9]|30)' | grep 2020 | grep Jan | grep Sat

2020
