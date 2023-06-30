# RK3399 leez SDK

Sync to the lastest release code:

```
$ mkdir ~/bin
$ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
$ chmod a+x ~/bin/repo
$ export PATH=~/bin:$PATH

$ repo init --repo-url=https://mirrors.tuna.tsinghua.edu.cn/git/git-repo --no-clone-bundle -u https://github.com/halberdholder/manifests -b master -m rk3399_linux_release.xml

$ repo sync --no-clone-bundle
```
