# How to structure local git repository



1. Create new folder
~~~cmd=
mkdir lib
~~~
2. Move there your file (chose one):

    2.1. OS command:
~~~cmd=
mv hello.html lib
git add lib/hello.html
git rm hello.html    
~~~    
 2.2. git command:
 
~~~cmd=
git mv hello.html lib
~~~

3. Commit 
~~~cmd=
git commit -m "Moved hello.html to lib"
~~~