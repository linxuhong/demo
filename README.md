mkdir demo
cd demo 
git init
echo 'my first filt' > README.md
git add README.md
git commit -m "first commit"
git remote add http://linxuhong@github.com/demo.git
git push -u origin  master

