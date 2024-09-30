# 최초 생성(windows11)

## local sites

"""
name: wp-vastwhite-learn
user: master.vw
password:
email: jnjsoft.blog@gmail.com
"""

## files

### folder.file 삭제, 복사

```sh
cd "C:\Users\Jungsam\Local Sites\wp-vastwhite-learn\app\public"
rmdir /s /q "wp-content\themes\twentytwentythree"
rmdir /s /q "wp-content\themes\twentytwentytwo"

copy "C:\Users\Jungsam\Local Sites\wp-udemy-wordpress-developer\app\public\.gitignore" "C:\Users\Jungsam\Local Sites\wp-vastwhite-learn\app\public\.gitignore"

xcopy "C:\Users\Jungsam\Local Sites\wp-udemy-wordpress-developer\app\public\_docs\*" "C:\Users\Jungsam\Local Sites\wp-vastwhite-learn\app\public\_docs\" /s /e /h /y
```

## vscode

### 작업영역에 폴더추가

C:\Users\jungsam\Local Sites\wp-vastwhite-learn\app\public

### 수정

> `C:\Users\Jungsam\Local Sites\wp-vastwhite-learn\app\public\_docs\setup.md`

## github

```sh
cd "C:\Users\Jungsam\Local Sites\wp-vastwhite-learn\app\public"
github -e pushRepo -u jnjsoftblog -n wp-vastwhite-learn -d "CLASS101 예비/현직 웹 프로그래머를 위한 워드프레스 플러그인 개발!"
```
