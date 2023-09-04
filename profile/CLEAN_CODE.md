# Code of Conducts

* Avoid to comment code
* Do not commit artifacts
* Consider to use git versioning instead of marking ```_old```
* 100\% coverage test is very cool
* You will have to maintain all the code you commit, less is more
* We love self-explainable function names

# Good Practices

~~~
def my_sum(x,y):
    '''simple fuction'''
    ret = x + y
    return ret
    
def my_sum(x,y, alpha=1):
    '''simple fuction'''
    ret = x + y + alpha
    return ret
~~~

# Bad Practices

~~~
def my_sum(x,y):
    # ret = x+y+1 
    ret = x + y
    return ret
    
def my_sum(x,y):
    ret = x + y +1 # use constant not magic number
    return ret
~~~
