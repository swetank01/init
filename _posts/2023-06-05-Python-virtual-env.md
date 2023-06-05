---
layout: post
title:  "Python Virtual Env"
date:   2023-06-05 14:55:11 +0530
categories: How-to-Install
---


#### 1. Check Current Python and pip version

```
python --version
pip --version
python3 --version
pip3 --version
```

#### 2. install virtualenv
```
pip3 install virtualenv
```


#### 3. create env for specific python version

###### syntax: 
```
virtualenv -p python<version> env
```
where version can be 3.8, 3.9, 3.10 etc

###### cli
```
virtualenv -p python3.10 env
```
