Android Volley
----------
This is an unofficial mirror for android volley library.

#####VicV flavor

Basically ripped everything out to add this as a submodule in android studio, but not as a module.

Why? So I can make an android LIBRARY project that contains this instead of requiring transitive dependencies. 

##Intro

Volley is already deployed to Maven Central:

[Volley in Maven Central](http://search.maven.org/#search|ga|1|com.mcxiaoke.volley)


Current Version:

    1.0.6 (2014.09.10)

##Original

original :  [android-volley](https://android.googlesource.com/platform/frameworks/volley)
    
sync weekly with android source repo.


##Maven

format: jar

```
<dependency>
    <groupId>com.mcxiaoke.volley</groupId>
    <artifactId>library</artifactId>
    <version>1.0.6</version>
</dependency>
```


##Gradle

format: jar

```
compile 'com.mcxiaoke.volley:library:1.0.6'
```


format: aar

```
compile 'com.mcxiaoke.volley:library:1.0.6@aar'
```


