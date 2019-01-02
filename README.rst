.. To build this file locally ensure docutils Python package is installed and run:
   $ rst2html.py README.rst README.html

web3j: Web3 Java Ethereum Ðapp API
==================================
Forked web3j:4.0.0-android.

4.0.0-android of web3j is based java 1.6.

Otherwise 4.1.0-android of web3j is based java 1.8.

Forked `Webj3 <https://github.com/web3j/web3j>`_.

Maven
-----

.. code-block:: xml

   <repositories>
      <repository>
          <id>jitpack.io</id>
          <url>https://jitpack.io</url>
      </repository>
   </repositories>


   <dependency>
       <groupId>com.github.METADIUM.web3ja</groupId>
       <artifactId>core</artifactId>
       <version>4.0.1-android</version>
   </dependency>


Gradle
------

.. code-block:: groovy

   allprojects {
      repositories {
         maven { url 'https://jitpack.io' }
      }
   }


   implementation 'com.github.METADIUM.web3ja:core:4.0.1-android'


