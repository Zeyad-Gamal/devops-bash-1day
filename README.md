
## sed operations (Part 1)

1. I used:
   - `echo "Task1" > results.txt`
   - `sed -n '/bash/p' /etc/passwd`

2. I used:
   - `echo "Task2" >> results.txt`
   - `sed '5d' /etc/passwd`

3. I used:
   - `echo "Task3" >> results.txt`
   - `sed 's/bash/bourne-again/g' /etc/passwd`

---

## awk operations (Part 2)

4. I used:
   - `echo "Task4" >> results.txt`
   - `awk -F: '{print $5}' /etc/passwd`

5. I used:
   - `echo "Task5" >> results.txt`
   - `awk -F: '$4 > 100 {print $1, $3, $5}' /etc/passwd`

6. I used:
   - `echo "Task6" >> results.txt`
   - `awk 'NR>=10 && NR<=20 {print NR, $0}' /etc/passwd`

7. I used:
   - `echo "Task7" >> results.txt`
   - `awk -F: '{sum += $4} END {print sum}' /etc/passwd`

