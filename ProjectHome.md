**News - 2015.03.14**

RCaller source repository is migrated to GitHub, due to shutting down of Google Code site. The new repository is available in site https://github.com/jbytecode/rcaller



**News - 2015.03.03**

Paul Curcean (Business Informatics student at the Vienna University of Technology) joined us.

A.Gokhan Satman joined to developer team to work specially on RCallerPhp


**News - 2014.10.28**

Please cite RCaller using the research paper hosted in

http://www.sciencedomain.org/abstract.php?iid=550&id=6&aid=4838#.VE9G2oXxCE1



**News - 2014.06.17**
  * Added deleteTempFiles() method in class RCaller for deleting temporary files that are created by RCaller at any time.
  * runiversal.r is now more compact
  * StopRCallerOnline() method in class RCaller now stops the R instances in the memory which are created in runAndReturnResultOnline().

Download link is here: http://stdioe.blogspot.com.tr/2014/06/rcaller-24-has-just-been-released.html


**News - 2014.06.07**
A new research paper, RCaller: A Software Library for Calling R from Java, has just been published in scholary journal "British Journal of Mathematics and Computer Science". The abstract and link of this paper is given below.


> Abstract: R is a programming language and environment which is mainly aimed to be used  for statistical calculations and data analysis. Since a vast amount of human resource is consumed for its source code and packages; it is comprehensive, large in size and more common among others. Extending computer software with statistical calculation routines requires extra human resource, therefore, the need of wrapper libraries has been appeared. There are many software libraries that communicate R with other languages. Despite they render similar services, they have their own pros and cons. RCaller is a software library which comes into prominence with its simplicity. In this paper we introduce the library with some examples. We mention its abilities as well as its limitations. RCaller can be used in relatively small projects as it has painless start-up process and steep learning curve. - See more at: http://www.sciencedomain.org/abstract.php?iid=550&id=6&aid=4838#.U5WUbPl_t2M


---


**News - 2014.05.15**
RCaller 2.3 is ready for testing. Please see the blog page:
http://stdioe.blogspot.com.tr/2014/05/new-release-rcaller-230_15.html

Change log of this version:
  * getDimensions(x) returns dimensions of the matrix x which is returned from R to Java.
  * XML output is now more compact and parsing R output is faster.
  * New test scenarios are added.


**News - 2014.04.15**
RCaller 2.2 is ready for testing. New version does not require the R package Runiversal to be installed. Please see the blog page http://stdioe.blogspot.com/2014/04/rcaller-220-is-released.html


**News - 2011.11.12**
We have just started to implement the C++ edition of RCaller. Note that, we are developing this for providing a compatible API to C++ however it is not the most efficient way of calling R from C++ as same for other RCaller editions.

**News - 2011.11.11**
Miroslav Batchkarov has just joined us.

**News - 2011.10.31**
We have the Php edition of RCaller which is nearly 100% compatible with the Java edition. It is ready for download in Downlads section.


**A library for calling R from Java.**

RCaller is used by several users that interested in both R and Java. I was planning to submit a new version that includes functionality for plot handling and something useful. Now, with the version 2.0, i have re-written the code with a different logic. RCaller 2.0 uses the package Runiversal which has two functions for converting R list objects to Java or XML. The new logic underlying the RCaller is to translate java arrays to R, send them and the commands to R interpreter and handle the results as XML documents. XML documents then parsed using Java's standard XML DOM document API's. Finally, user can handle the results from Java.
RCaller 2.0 is now in Google Code, both source code and the compiled jar file is ready for download. Remember that, nobody used it yet (2011.07.08) and it should be erroneous.I will trace the bugs more frequently by today and submit new versions immediately.
Another important issue: The R package Runiversal is installed when the RCaller 2.0 is first used in a machine. You can install this manullay, if you want, by typing

install.packages("Runiversal")

in R interactive console. This package was also written by me and any code in this project is completely distributed (Version 2.0) under the GNU Lesser Public Licence (GNU LGPL). If you use open source libraries in your projects, you probably know what the GPL licences are for, but if you are not familier with them, roughly speaking, they are more than a simple recursion :) . See details in the Google project home page of RCaller.

A blog entry and some examples are ready in site [Practical Code Solutions](http://stdioe.blogspot.com/search/label/rcaller). Please browse the test package in the source code of RCaller for the examples. I will prepare some helpful documents when i have more time. Please do not hesitate to ask for help.

## Sample Gui for handling R results, input and error streams from Java ##
![http://wiki.rcaller.googlecode.com/hg/images/SampleGuiRcaller.png](http://wiki.rcaller.googlecode.com/hg/images/SampleGuiRcaller.png)




