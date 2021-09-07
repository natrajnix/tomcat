# chef-tomcat-hello-world


```
This cookbooks performs the installation & Configuration of Java & Tomcat 8 included tomcat service feature
```

Usage
------------

1) Create chef-repo on your chef Workstation and put files and dirs to the 'chef-repo/cookbooks/tomcat' directory

2) Add 'apt' cookbook
```
knife supermarket download apt
```

3) Upload code to the Chef Server
```
knife cookbook upload tomcat
```

4) Run on the clent machine
```
sudo chef-client
```

5) Open in browser
```
http://x.x.x.x:8080/hello/sayhello
```



