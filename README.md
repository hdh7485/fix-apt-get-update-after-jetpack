# Description

# Solution
```
$ dpkg --print-foreign-architectures
$ dpkg --print-architecture
```
```
$ sudo dpkg --force-all -remove-architecture aarch64
```
or
```
$ sudo dpkg --force-all -remove-architecture arm64
```

# Reference
https://devtalk.nvidia.com/default/topic/957632/did-anyone-else-have-issue-with-apt-get-update-failing-after-installing-jetpack-2-2-/?offset=4
