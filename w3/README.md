# 2023_OSS
## 2023 OSS 수업

-----

### 3주차 git


### 이미지



### 링크

[LMS](https://lms.kau.ac.kr/login.php)

#### ProGit 링크

[ProGit](https://git-scm.com/book/en/v2)

#####주요 git 명령어


-----
### 2주차 숙제
```bash
#!/bin/bash

name="조영서"
student_id="2020126094"
file_path=$(find /home/kau2 -name "w2_homework.txt" 2>/dev/null)
line_number=$(cat $file_path|wc -l)
last_line=$(tail -n 1 $file_path)

echo "---------“
echo "name :"
echo "$name
"
echo "---------"
echo "student id :"
echo "$student_id
"
echo "---------"
echo "file path :"
echo "$file_path
"
echo "---------"
echo "line number :"
echo "$line_number
"
echo "---------"
echo "last line :"
echo "$last_line
“
