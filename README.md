[![Build Status](https://travis-ci.org/jonnybbb/spring-social-xing.svg?branch=master)](https://travis-ci.org/jonnybbb/spring-social-xing)

# Spring Social
To check out the project and build from source, do the following:

 git clone --recursive git://github.com/SpringSource/spring-social.git
 cd spring-social
 ./gradlew build

Note: the --recursive switch above is important, as spring-social uses
git submodules, which must themselves be cloned and initialized. If --recursive
is omitted, doing so becomes a multi-step process of: 

git clone git://github.com/SpringSource/spring-social.git
git submodule init
git submodule update

-------------------------------------------------------------------------------
To generate Eclipse metadata (.classpath and .project files), do the following:

 ./gradlew eclipse

Once complete, you may then import the projects into Eclipse as usual:

 File -> Import -> Existing projects into workspace

-------------------------------------------------------------------------------
To generate IDEA metadata (.iml and .ipr files), do the following:

 ./gradlew idea

-------------------------------------------------------------------------------
To build the JavaDoc, do the following from within the root directory:

 ./gradlew :docs:api

The result will be available in 'docs/build/api'.
===============================================================================
