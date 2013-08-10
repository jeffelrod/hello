hello
=====
this is just my first go project. after installing go (http://golang.org/doc/install), i followed these instructions to
create the project, install it, and set up a git repo (http://golang.org/doc/code.html), then i did the following to 
create the remote repo using the command line:

from within the directory where the git repo was set up (in my case, $GOPATH/src/github.com/jeffelrod/hello), i ran

curl -u 'USER' https://api.github.com/user/repos -d '{"name":"hello"}'
{here, i was prompted for my github password, then i proceeded}
git remote add origin git@github.com:jeffelrod/hello.git
git push origin master

aaaaand, here we are.
