# How to discard changes(1), unstage(2) and uncommit(3) them from the local git repository

1. How to discard local changes 

~~~cmd=
git checkout hello.html
~~~

2. How to unstage *(Reset the buffer zone)*
~~~cmd=
git reset HEAD hello.html
~~~
**Note:** *Unstage only empties buffer zone and not discarding actual changes that were made in the working directory. To discard actual changes see 1.*     
<br/>
3.1. Revert commit
~~~cmd=
git revert HEAD --no-edit
~~~
**Note:** *This technique can be applied to any commit (however there may be conflicts). It is safe to use even in public branches of remote repositories* 
<br/>  

3.2.[Reset](./reset.md) commit
~~~cmd=
git reset --hard v1
~~~
**Note:** *v1* is a Tag   


3.3. Checkout commit  
 [Where are my commit hashes?](./history.md)
~~~cmd=
git checkout <previous_hash>
~~~
3.4. Amend to previous commit
~~~cmd=
git add hello.html
git commit --amend -m "Add an author/email comment"
~~~

4. How to check status of my changes?
~~~cmd=
git status
~~~
