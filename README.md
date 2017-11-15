# git-test
full-stack web development from coursera
this is a git learning path:
1.create a html file named index.html with contents:
```
<!DOCTYPE html>
<html>
    <head></head>

    <body>
        <h1>This is a Header</h1>
    </body>
</html>
```
then use following commands to add the file to the git
```
git init
git add .
git commit -m "init app"
```
change the file to:
```
<!DOCTYPE html>
<html>
    <head></head>

    <body>
        <h1>This is a Header</h1>
        <p>This is a paragraph</p>
    </body>
</html>
```
and then upload to git：
```
git add index.html
git commit -m "new paragraph"
```
create a directory named templates and copy the index.html to the directory and upload to git
```
git add .
git commit -m "create template"
```
