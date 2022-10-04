# How to create version tags and switch between versions


1. How to create tag of the last commit
~~~cmd=
git tag v1
~~~
2. How to create tag of the predecessor of the last commit:   
2.1. Move to the predecessor   
2.2. Set tag of the predecessor
~~~cmd=
git tag v1~1
git tag v1-beta
~~~     
3. How to see all my tags
~~~cmd=
git tag 
~~~
4. How to see which commits have tags
~~~cmd=
git log
~~~
5. How to delete tag
~~~cmd=
git tag -d v1
~~~

