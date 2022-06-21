$ git clone https://github.com/gura2758/gura2758.github.io
Cloning into 'gura2758.github.io'...
warning: You appear to have cloned an empty repository.
$ ls
gura2758.github.io
何かのディレクトリ/gura2758.github.io
gura2758.github.io $ ls
index.html
gura2758.github.io $ cat index.html
<!DOCTYPE html>
<html lang="ja">
<head>
 <meta charset="UTF-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Document</title>
</head>
<body>
 こんにちは
</body>
</html>% 
gura2758.github.io $ 
gura2758.github.io $ git add --all
gura2758.github.io $ git commit -m "Initial commit"
[master (root-commit) 25347b0] Initial commit
1 file changed, 15 insertions(+)
create mode 100644 index.html
gura2758.github.io $ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 430 bytes | 430.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/gura2758/ gura2758.github.io
* [new branch] master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
gura2758.github.io $
