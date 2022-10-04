# How to create a local project and connect it to the local git repository


1. create folder and navigate to it 
~~~cmd=
mkdir hello
cd hello
~~~
2. create files in it
~~~cmd=
type Hello World > hello.html
~~~
3. initialize git repository
~~~cmd=
git init
~~~
4. add files to git repo ([Staging](./states.md))
~~~cmd=
git add hello.html
~~~
5. commit git with a message ([Commiting](./states.md))
~~~cmd=
git commit -m "First commit"
~~~

