MKNUG website
==============

The Milton Keynes Node User Group Website

How to run
----------
We serve this to the world via [surge.sh](https://surge.sh), but you can serve this with *any* static web server, we happen to like [harp](http://harpjs.com).

1. `git clone https://github.com/MKNUG/mknug.org.git`
2. `cd mknug.org`
3. `sudo npm install -g harp`
4. `harp server`
5. open http://localhost:9000

Note
----
We have a `pre-push` hook defined that deploys the site to surge.sh, which you clearly may not want to do. If you want to push without deploying, use:

`git push --no-verify`
