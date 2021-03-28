# T1A1 Workbook


# Q1: Research the development of the internet from 1980 to today. You must describe at least FIVE key events in the development of the internet. You can refer to events, people of significance, or technologies and how they have changed over time.

**1. 1984** - Dr. John Postel introduced a concept for new domains or administrative entities on the ARPA network. The system was described as “a tree-structured global namespace that has few top-level domains”. Essentially, his idea would include different domain names or specific ‘addresses’ for different purposes and types of information on the network. These domains lead to the use of .edu, .gov, and .com.au which are domains specific to the region and information type.

**2. 1990** - Tim Berners-Lee, a scientist working for CERN (The European Organization for Nuclear Research, invented the World Wide Web, different from the ARPA network, the Web would become an open-source network designed to be more accessible to a wider audience, not just computer scientists, government and other agencies they were directly involved with. With this also came the proposal for a new language called Hypertext that would make the experience using the WWW possible.

**3. 1990** - The first website, a text-only effort describing the World Wide Web or “W3” browser, goes live on the world’s first server. It was run on Tim Berners-Lee’s NeXT computer at CERN, which is now on display at the organization’s museum.

**4. 1994** - SSL was invented. Marc Andreeson one of the co-founders of Netscape, set his company to develop a way for data to be more securely sent over the Internet. This data needed a method for it to be encrypted, packaged, and unpacked securely and efficiently. The answer was SSL, or Secure Socket Layer created by Kipp Hickman and is now an industry standard.

**5. 1995** - Long before Zoom, VocalTec, an Israeli telecom company released an application/program that is regarded as the first commercial VoIP for desktop computers. Given the current global environment and our reliance on VoIP’s, this invention set the stage for global growth in telecommunications.

**6. 2004** - Facebook was launched. Although preceded by other social platforms like Friendster and MySpace, Facebook was able to grow at enormous rates and eventually monopolize the social network space. They were able to achieve this largely by constantly adding new features. At the height of the reign, other social platforms were stagnant in their adaptation of features for new users. Facebook was able to capitalize on its growth and constantly provide an engaging experience for its user base irrespective of demographic, location, or psychographic circumstance.


http://www.faqs.org/rfcs/rfc920.html

https://www.cnet.com/news/the-50-most-significant-moments-of-internet-history/

https://www.salon.com/2014/03/14/25_biggest_moments_in_internet_history_partner/

# 

# Q2: Define the features of the following technologies that are essential in terms of the development of the internet:
- packets
- IP addresses (IPv4 and IPv6)
- routers and routing
- domains and DNS

**Packets** - A packet or network packets are the core infrastructure used to transfer information over a network. For example, let’s say you're sending an image to a friend over the internet, whether it’s via email or iMessage, this file may be too large to send efficiently in an uncompressed format and so it's compressed or deconstructed into packets and sent over the network, then, reconstructed at its destination. Packet switching was one of the first inventions of the internet and created the base for everything that we send and receive via networks today.

**IP address (IPv4 and IPv6)** - IP addresses are anchor points in a connection between a destination machine and a source or origin machine. This is essentially the way devices communicate with each other over a network. An IP address is like a phone number. IPv4 was an early model for IP addresses which consisted of 32-bit, or four number address ranging from 0 to 255 separated by periods. This format however limited the total number of IP addresses and thus IPv6 was introduced. IPv6 utilizes a 128-bit address allowing not only a greater total of addresses available but also introduced user to be connected to multiple networks at the same time. IPv6 also has better security and benchmarks.

**Routers and routing** - Data and IP packets rely on routing to communicate to the correct network origin and destination. While Packet Switching is the algorithm to enable information to be efficiently sent over a network, the process of routing controls the path for the data to reach the correct destination. Before routers and routing, data was handled using cables and phone lines, which was the case with DSL. Routers on the other hand are the hardware that allows us to access information and data wirelessly from an individual network and push to multiple devices.

**Domains** - Created by Dr. John Postel, Domains introduced as a concept for new information subsets on the internet. His idea would allow administrative entities to have different assigned domain names or addresses for different purposes and types of information and data. Domain names are comprized of a subdomain (eg. www), second-level domain (eg .websitename) and top-level (eg .com).


https://computer.howstuffworks.com/question525.htm

https://www.avast.com/c-ipv4-vs-ipv6-addresses

https://www.bam.com.au/blog/domain-names-and-dns/

# 

# Q3: Define the features of the following technologies that are essential in terms of the development of the internet:
 - TCP
 - HTTP and HTTPS
 - web browsers (requests, rendering and developer tools)
 
**TCP** - TCP or Transmission Control Protocol is a connection that enables data to be deconstructed into packets and be transferred across the internet or over a network. TCP controls the size, flow (origin to destination), and rate of data exchange. TCP is used to establish a connection between a client and a server and is useful for large amounts of data.

**HTTP** - HTTP or Hypertext Transfer Protocol is used as a network client request from an application and is used to deliver hypertext between a web server and said, client. Although faster than TCP, HTTP doesn’t have the equivalent capacity as TCP. HTTP is used for accessing websites and transferring capped amounts of data although both HTTP and TCP are part of layered networking models but handle different types of data flow. Web browsers are used to initiate HTTP requests and send information from a server to a client.

**Web Browsers** - Like TCP and HTTP web browsers are part of layered network models that enable users to request information from an IP. IP addresses however are hard to remember and so browsers use a system called domain mapping to request information from a server. This server hosts data or information and maps the route to which the information is needing to be sent. When a browser makes a request using HTTP. Once this request is established and the server receives the request, the server responds to the domain or IP and sends the requested information. After the information has been received the browser renders the information to the client.

https://www.ibm.com/support/knowledgecenter/en/SSGMCP_5.3.0/com.ibm.cics.ts.internet.doc/topics/dfhtl_conintro.html

https://developpaper.com/the-connection-and-difference-between-http-tcp-and-udp-socket-and-websocket/

# 

# Q4: Identify THREE data structures used in the Ruby programming language and explain the reasons for using each.

**Data Structures**

A data structure is a detailed way in which data is organized and accessed. There are different data structures used in programming. 

**Arrays** - Arrays use some part of the memory in which objects are stored together one after the other without any gaps. The memory locations share a common border, and an index key is used to access an object within the array. Arrays collet items and gather results in any loop.

**Hashes** - These are used for mapping because, in this data structure, each value has a key that can be any data type. It is used for counting characters, mapping and identifying any repeats in an array. Hashes are suitable in performances as it has the delete, store and access time thus can be used to locate a specific value.

**Stacks** -  In this data structure, objects are placed on top of one another, and only the object on the top can be removed. It is useful because it provides a regular loop. Similarly, one can easily track the pending tasks like in a to-do list app, with the most recent one being at the top.

Günther, Sebastian, and Sagar Sunkle. "rbFeatures: Feature-oriented programming with Ruby." Science of Computer Programming 77.3 (2012): 152-173.

# 

# Q5: Describe the features of interpreters and compilers and how they are different.

**Compiler** - Compilers and interpreters are programs used in computers to convert the source code to machine codes for the computer to understand. A compiler converts high-level programming language to binary and bits, which the computer understands to execute the corresponding tasks. The code is converted before the program runs and is done all at once. It has an analysis and synthesis phase. A compiler adheres to the written programming language but cannot make any changes in the program. If there is a mistake made, the program's syntax has to be changed to the compiler to succeed. It is based on the conversion linking-loading pattern. It is beneficial to use a compiler because it has a reduced execution time because of the program code being already converted into machine code. However, the disadvantage is that once the program is running, the code cannot be changed unless one goes back to the source code. It is commonly used in Java, C, and C++.

**Interpreter** - On the other hand, an interpreter converts high-level language into machine code. However, the conversion is done when the program is running and is based on Interpretation Method. It is found in the memory and supports Dynamic Typing. It is made up of the Lexical Analyzer Syntax Analyzer and the Semantic Analyzer Stage. The program statements are converted one at a time. Thus the codes operate at reduced speed compared to the compiled code. With the interpreter, the errors of each line are displayed after each code statement. Thus, the error has to be corrected before one can move to the following statement code. Interpreters are easy to use and can be easily understood by beginners, and suitable for program and development. It is commonly used in PHP, Ruby and Perl languages.


Kennedy, Ken. "Languages, compilers, and run-time systems." The Grid 2. Morgan Kaufmann, 2004. 

Cazzola, Walter, and Albert Shaqiri. "Open programming language interpreters.", 2017.

# 

# Q6: Identify TWO commonly used programming languages and explain the benefits and drawbacks of each.

**Java** - Commonly used in networking and known as a "write once run anywhere" language. It is associated with large companies using client-server applications. Any application in Java Language can only run a Java-supported platform. Java is commonly used in the android OS in most mobile devices. It is a general-purpose language and was designed to depend on as few implementations as possible. It is the most suitable language for developers and programmers who want to learn to program. The memory used to compile a program is 6.01MB per second with a run time of 1.89 seconds.
Java's syntax and structure are similar to C++, and thus, it is used to create programs on different platforms. Anyone conversant with C++ will find it easy to learn Java and enjoy object-oriented programming. Additionally, the programs speed and features have increased over the years, making it easy to use in programming.
However, Java is not suitable for the cloud platform, while most business applications use the cloud. Likewise, there is a licensing fee for using the Java Development Kit paid to the owners, Oracle. Similarly, using Java to write an efficient code is quite difficult, just like its reusability. It might require more memory than C and C++ and has only solitary paradigm languages.


**C** -  C is commonly used in game programming. C is preferred to C++ because it lacks the extra packing. Likewise, its programs are slightly faster and smaller. It provides low-range entry to memory with a very minimal run-time. C is also common because even with its low-level capabilities, the languages allows cross-platform coding. Any program written in C language can be used in different operating systems as long as it is portable. It only requires minimal changes to the source code. The language is readily available on several computers. C is commonly used in hardware programming, especially in automobiles and medicals equipment, as it can run on any device 
It can also be quickly learnt, and it acts as a stepping stone to other programming languages such as Python and PHP. It can extend itself and easily be debugged, tested and maintained. However, it cannot be used with another object-oriented programming such as polymorphism because it one of the older programming languages. Thus it not suitable for mobile applications and websites. It lacks data security, and the source code cannot be reused. Additionally, its syntax is quite complex.

Gupta, Diwaker. "What is a good first programming language?" Crossroads, 10.4, 2004.

Sebesta, Robert W. Concepts of programming languages. Boston: Pearson, 2012.


# 

# Q7: Identify TWO ethical issues from the areas below and discuss the extent to which an IT professional is ethically responsible in terms of the issue.

List of topics containing ethical issues:
 - access to a user’s personal information (medical, family, financial, personal attributes such as sexuality, religion, or beliefs)
 - intellectual property, copyright, and acknowledgement.
 
**Ethical Issues** 

IT personnel always have access to a user's personal information. Thus, they are ethically obliged to respect people's privacy. Hence, this information should only be used for legitimate use. Thus, they should ensure this data is accurate and safe from any unauthorized access.
Another ethical issue that IT professionals experience is intellectual property, copyright and acknowledgement. It is vital to protect the company's computer software. Likewise, technology can be used to steal ideas, and thus, one has to ensure they do not out a company's ideas either unintentionally or accidentally.

**Legal Information**

While the UK falls under the EU's General Data Protection Regulation (GDPR), it also implemented its legislation for data privacy in 2018 called the Data Protection Act (DPA). While similar in language and most requirements, the DPA does have additional use cases that span into areas like immigration, data relating to public interests, and criminal convictions, such areas that GDPR does not cover.

While it's challenging for a company to adhere to data handling and processing guidelines, both the GDPR and DPA have specific requirements that outline how to do so legally and ethically. The benefit for a developer in the UK is that they have access to these guidelines for the EU as a whole and the UK. An issue with these acts however is the potential misinterpretation of what's required by a company, and what's required by an individual developer and so it's important for companies to provide the most up to date training on data handling specific to development practices to adhere to GDPR and DPA guidelines.



**Case study**

The case study is about a data breach involving a customer at EE (formaly Everything Everywhere). When the customers phone lost network signal, she contacted the company and was informed that some had requested a sim replacement. That person was her ex-partner.


Further investigation revealed that her personal information was accessed unlawfully, including her current address and bank details. She was not handled well by the company's management, and when she couldn't get help from EE, she reported the incident to the police. Her ex-partner stalked her at her house and sent her numerous texts.
The company, did not protect their customer's personal data from unauthorized access and additionally, processed and changed the customer's data to a new mobile device. This mistake by an EE employee failed to protect the customers data from use by a third party. This is a violation of the ACM Code of Ethics and Professional Conduct which cleary states it is illegal for a person to access another person's data unlawfully. 

The company should have ensured that its customers' data is safe from any unauthorized access. Similarly, the company should have put in controls to help its employees act when someone calls on behalf of their customer while still maintaining an approved code of conduct. Management should have responded promptly to the customer's allegations to prevent more damage.

As for any company that handles sensitive customer information, EE's management should organize training and awareness programs to educate all their employees on the company's data handling process' and procedures and further educate them on accessing customers' personal information. The company should adhere to the data protection guidelines to prevent a repeat of the data breach. Additionally, the company should have additional vetting guidelines to ensure that only the owner of the sim card requests a sim replacement and disallow third-party requests. Finally, the company should provide a customer response channel to any data breach claims to ensures that the customers are informed promptly given a data breach, and an investigation is carried out to prevent any further damage.




National Research Council. Improving access to and confidentiality of research data: Report of a workshop. “National Academies Press,” 2000.

Reed, Jim. EE data breach ‘led to stalking’. BBC News. 8 February 2019. https://www.bbc.com/news/technology-46896329.

Ayo, Samuel Cris. "Data Breach e-Crime, A Case Study and Legal Analysis.",2019

ACM, Computing Machinery. "ACM code of ethics and professional conduct." Code of Ethics, 1992. 

Habermann, Hermann. "Ethics, confidentiality, and data dissemination." Journal of Official Statistics 22.4, 2006


https://mobidev.biz/blog/gdpr-compliant-software-development-guide

# 

# Q8: Explain control flow, using an example from the Ruby programming language.

Control flow is the sequence in which code on a script is executed. Control flow allows the programmer to tell the program which code should be executed based on certain conditions. Control flow is essential in Ruby, and it uses the basic conditional forms of if, else, and elsif statements. In if statements, the code the will be read and executed by the computer is the one following the if statement is true. Thus, if the evaluation results to true, the code will be executed to the end.

For example

```
if 7 + 4 == 11
    	puts "Please give me a good mark"
end
```

The output to be printed will be "Please give me a good mark", as the if statement weighs as true.

However,
```
if 7 + 4 == 9
    	 puts "Please give me a good mark."
```

In this code, nothing will be printed as the if statement is calculated as false. 7 + 4 does not equal 9; thus, the if statement is false and the program does not execute the block of code.

Flanagan, David, and Yukihiro Matsumoto. The Ruby Programming Language: Everything You Need to Know. O'Reilly Media, Inc., 2008.

# 

# Q9: Explain type coercion

**Type Coercion**

Type coercion is the process of transforming an object from one type of data to another one. This could be from a number to a string or from object to Boolean. Type coercion often occurs when data is stored in a different data type from the one needed by its setting. Any data type can go through type coercion, and it can either be implicit or explicit coercion and is extensible. For example, type coercion is when "7", a string is converted to an integer, 7, or transformed to a double, 7.0.

Pierce, Benjamin C., and C. Benjamin. Types and programming languages. MIT press, 2002.

# 

# Q10: Explain data types, using examples

**Data Types**

A data type is a format in which data is stored, and the type can range from a definite category to a series of variables. 

**Numbers**  

Number types can refer to both integers and floats (floating-point). Integers represent whole numbers, such as 1, 30, 88 and 33. Floats or floating-point data types represent numbers that have a decimal point, such as 33.33, 10.87 and 00.23.

```
33.class = integer
33.33.class = float
```

**String** 

Strings are used to represent text or alphanumeric characters such as Billy, Caroline45 and are defined by wrapping text in single ('') or double (""(""("") quotes.

```
"Hello, my name is Jordan".class = string
```

**Boolean**

Boolean data types are either true or false

```
true = TrueClass
false = FalseClass
```

**Arrays**

An Array stores data, or a list of data. This data can be any type and is seperated inside an array using a comma (,) and is encased in square bracket ([]). Each element in an array has an positional value called an index.

```
array = [1, "Jordan", true,]
puts array[1]
```
Expected output: `Jordan`


**Hashes**

Hashes or objects as it is sometimes reffered to in different languages, store data in Key/Value pairs. Each key pair is seperated by a comma (,) and is encased in a curly bracket ({}). You can also access the key or value in a hash, but using a different syntax than arrays.

```
hash = {"Jordan":true, "Age": 33}

puts hash[:"Jordan"]
```
Expected output: `true`


**Symbol**

A symbol is a string that has been given a unique id. Symbols are used to save space and time as theyre faster for the program to read. A symbol is defined by using a colon (:) at the beginning of the text.

```
examples = {:number1=> "This is example 1", :number2=> "This is example 2"}
  
puts examples[:number1]
```
Expected output: `This is example 1`


**Nil**

Nil, or the absence of data is also a data type given zero is still a value.

```
nil.class = NilClass
```

Sampson, Adrian, et al. "EnerJ: Approximate data types for safe and general low-power computation." ACM SIGPLAN Notices 46.6 (2011): 164-174.
Sebesta, Robert W. Concepts of programming languages. Boston: Pearson, 2012.
Bhat, Miti S., et al. "Data structure based performance evaluation of emerging technologies—A comparison of Scala, Ruby, Groovy, and Python." 2012 CSI Sixth International Conference on Software Engineering (CONSEG). IEEE, 2012. 

# 

# Q11: There is a restaurant serving a variety of food. The customers want to be able to buy food of their choice. All the staff just quit, how can you build an app to replace them?
 - Identify the classes you would use to solve the problem
 - Write a short explanation of why you would use the classes you have identified
 
***Note - some of these classes will be nested


**WaitStaff**

This class includes information on the wait staff and which zones they’re assigned to in the restaurant.

**Menu Class**

Menu will contain a list of dishes with corresponding information about the dish, such as price, nutritional values (Calories, etc), ingredients, allergen warnings. This will also update the customer if anything is unavailable or out of stock and the approximate wait time.


**Customer Class**

Customer will include information about the location of the customer in the restaurant so that food can be delivered to their table. 


**FoodRequest**

Contain food objects to inform the Chef of any dish requests including which dishes are ordered from Menu. As well as special requests like removing an ingredient, add ons such as extra sauce, and or how the Customer would like their food cooked. 

**OrderTaker**

Take the customer's order, save the order, total the order amount, send the order to the Chef, return the approximate wait time, and save the total for the bill.

**Chef**

Chef takes the objects from Menu and Food and makes the food according to the inputs and requirements from those classes. It will return completed dishes for wait staff to deliver.

**FoodDelivery**

Assigns completed dishes to wait staff when food is cooked based on the return value from Chef.

**Payment**

Choose a payment method, process the electronic payment, or receive cash and return the correct change.


# 

# Q12: Identify and explain the error in the code snippet below that is preventing correct execution of the program.

```
 celsius = gets
 fahrenheit = (celsius * 9 / 5) + 32
 print "The result is: "
 print fahrenheit
 puts "."
 ```
 
In this code `celsius` is expecting a string but in order for `farenheit`  to execute properly the input needs to be converted to an number or more specifically a float using `.to_f`

```
celsius = gets.to_f
   print "The result is: "
   fahrenheit = (celsius * 9 / 5) + 32
   print fahrenheit
   puts '.'
```

# 

# Q13: The code snippet below looks for the first two elements that are out of order and swaps them; however, it is not producing the correct results. Rewrite the code so that it works correctly.

```
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0
while (i < arr.size - 1 and arr[i] < arr[i + 1])
	i = i + 1 end
puts i
    arr[i] = arr[i + 1]
    arr[i + 1] = arr[i]
```

Correct Code:

```
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0
while (i < arr.size - 1 and arr [i] < arr[i + 1])
    i = i + 1 end
    puts i

holder = arr[i]
arr[i] = arr[i + 1]
arr[i + 1] = holder

p arr
```

# 

# Q14: Demonstrate your algorithmic thinking through completing the following two tasks, in order:
 1. Create a flowchart to outline the steps for listing all prime numbers between 1 and 100 (inclusive). Your flowchart should make use of standard conventions for flowcharts to indicate processes, tasks, actions, or operations
 
 
 
 
 2. Write pseudocode for the process outlined in your flowchart
 
 ```
 # initialize an array of numbers between 2 and 100
# initialize a global result array 
# define a method with one parameter 
    # initialize a placeholder to equal 2
    # while the placeholder is less than the parameter
        # if parameter is divisible by placeholder and returns a 0 remainder
            # parameter is not prime return false
        # else go to next number
    # if true then the number is prime add to result
# loop through the array
    # call method for each element in the array
# print result
```

# 

# Q15: Write Ruby code for the following problem:
You have access to two variables: raining (boolean) and temperature (integer). If it’s raining and the temperature is less than 15 degrees, print to the screen “It’s wet and cold”, if it is less than 15 but not raining print “It’s not raining but cold”. If it’s greater than or equal to 15 but not raining print “It’s warm but not raining”, and otherwise tell them “It’s warm and raining”.

```
def weather(temp, raining)
    if raining == true
        if temp < 15
            puts "It's wet and cold"
        else 
         puts "It's warm and raining"
        end
    else raining == false
        if temp <= 15
            puts "It's not raining but cold"
        else 
         puts "It's warm but not raining"
        end
    end
end

weather(13, true)
```
Expected output: `It's wet and cold`




