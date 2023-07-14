# Shell-Scripting-Basics


- IF-ELSE
```
  GNU nano 4.8                        test.sh                                   
#!/bin/bash

echo "Please enter a number: "
read num

if [[ $num -gt 0 ]]; then
  echo "$num is positive"
elif [[ $num -lt 0 ]]; then
  echo "$num is negative"
else
  echo "$num is zero"
fi
```  

- Operators :

![Ubuntu 64-bit - VMware Workstation 15 Player (Non-commercial use only) 14-07-2023 19_07_34](https://github.com/23subbhashit/Shell-Scripting-Basics/assets/43717493/c3ecc1b8-cb86-45db-bbb9-e09500746315)
```
AND : -a
OR : -o
```

- While Loop:
```
#!/bin/bash
i=1
while [[ $i -le 10 ]] ; do
   echo $i
  (( i += 1 ))
done

```
