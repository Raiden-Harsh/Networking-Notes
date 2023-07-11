# COMPUTER NETWORKING 💻

### **PROTOCOLS :** 
    thse are the different rules set to send different kinds of data over the internet.
>example : When sending a file, we want all the contents of the file to be transferred! but while on a Video Call if some data is lost ( i.e. some frames dropped) then it won't matter that much!

### **W.W.W. :**
    The World Wide Web, was a way to implement hyperlinks in a web page.
<sub> before W3 we were unable to link documents </sub>

> **NOTE :** even with w.w.w. we couldn't search for pages, that shit came long after!

***Q) Who TF created these protocols and manage them till date? and even creates new ones?***
> Ans) The [Internet Society](https://www.internetsociety.org/), *To implement your own idea you have to create a RFC, i.e. like a research paper of some sort for new protocols.*

![Client-Server architecture](https://res.cloudinary.com/practicaldev/image/fetch/s--4OSbdj3v--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/f8cxx3oj8gfflo1mb15o.jpeg)

> A client (user) sends a request to the server (a computer, say in a data center) and the server returns the response which is then displayed by the client browser!

![How ISP provide the internet](https://www.howtogeek.com/wp-content/uploads/2016/05/img_573b61ca55a89.png?trim=1,1&bg-color=000&pad=1,1)

***This is how the internet reaches to your devices***

### **I.S.P :**
    The I.S.P or the Internet Service Provider, will give a Global I.P. to the modem, when making a request by any device,
    D1,D2,D3 here, Laptop, Phone or PC, the Internet will see only the global I.P address.
    and the modem/router will assign some local I.P. addressed to the connected Devices by DHCP.
***To read more about the I.Ps :*** [Internet Protocol](I.P.md) 👆 

***To read more about DHCP :*** [D.H.C.P](DHCP.md) 👆

### **N.A.T :**
    Network Access Translator, it is used by the modem to decide, to which device to send the response.

***Q) Now, the router knows which device to send the data back. but, which application asked for it?***
> It is decided by the port.

A typical I.P. address looks like this `x.x.x.x:x`


here, the first 4 `x` are *16-bit* numbers ranging from : *0 - 256*
*There are also some reserved ports (0 - 1023) :*t

    - http : 80
    - MongoDB : 27017
    - SQL : 1433
*ports form `1024 - 49152` are for applications*

## For Basic terminologies check this out [Internet Basics](basic_stuff_to_know.md) 👆

## STRUCTURE OF THE NETWORK :



