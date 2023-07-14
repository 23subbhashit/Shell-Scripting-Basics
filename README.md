# Shell-Scripting-Basics
![Ubuntu 64-bit - VMware Workstation 15 Player (Non-commercial use only) 14-07-2023 19_20_22](https://github.com/23subbhashit/Shell-Scripting-Basics/assets/43717493/27882cc8-3ff2-4f5f-9896-b1772ae33165)


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

- For Loop:
```
#!/bin/bash
for i in {1..5}
do
    echo "$i"
done
```

- Case :

```
#!/bin/bash
fruit="apple"
case $fruit in
    "apple")
        echo "This is a red fruit."
        ;;
    "banana")
        echo "This is a yellow fruit."
        ;;
    "orange")
        echo "This is an orange fruit."
        ;;
    *)
        echo "Unknown fruit."
        ;;
esac
```
