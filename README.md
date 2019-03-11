# Mastering Python for Networking and Security

<a href="https://www.packtpub.com/networking-and-servers/mastering-python-networking-and-security?utm_source=github&utm_medium=repository&utm_campaign=9781788992510 "><img src="https://d1ldz4te4covpm.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/9781788992510.png" alt="Mastering Python for Networking and Security" height="256px" align="right"></a>

**Leverage Python scripts and libraries to overcome networking and security issues
**

## What is this book about?
It’s becoming more and more apparent that security is a critical aspect of IT infrastructure. A data breach is a major security incident, usually carried out by just hacking a simple network line. Increasing your network’s security helps step up your defenses against cyber attacks. Meanwhile, Python is being used for increasingly advanced tasks, with the latest update introducing many new packages. This book focuses on leveraging these updated packages to build a secure network with the help of Python scripting.

This book covers the following exciting features:
Develop Python scripts for automating security and pentesting tasks 
Discover the Python standard library's main modules used for performing security-related tasks 
Automate analytical tasks and the extraction of information from servers 
Explore processes for detecting and exploiting vulnerabilities in servers 
Use network software for Python programming 
Perform server scripting and port scanning with Python 
Identify vulnerabilities in web applications with Python 
Use Python to extract metadata and forensics 

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
import requests
if __name__ == "__main__":
    response = requests.get("http://www.python.org")
    for header in response.headers.keys():
        print(header  + ":" + response.headers[header])

```

**Following is what you need for this book:**
0

With the following software and hardware list you can run all code files present in the book (Chapter 1-10).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1 | Python2.7 | Windows or Unix OS 32-bit or 64-bit versions |
| 2 | Python2.7 | Windows or Unix OS 32-bit or 64-bit versions |
| 3 | Python2.7 | Windows or Unix OS 32-bit or 64-bit versions |
| 4 | Python2.7 | Windows or Unix OS 32-bit or 64-bit versions |
| 5 | Python2.7 | Windows or Unix OS 32-bit or 64-bit versions |
| 6 | Python2.7 | Windows or Unix OS 32-bit or 64-bit versions |
| 7 | Python3.6 | Windows or Unix OS 32-bit or 64-bit versions |
| 8 | Python2.7 | Windows or Unix OS 32-bit or 64-bit versions |
| 9 | Python2.7 | Windows or Unix OS 32-bit or 64-bit versions |
| 10 | Python2.7 | Windows or Unix OS 32-bit or 64-bit versions |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://www.packtpub.com/sites/default/files/downloads/9781788992510_ColorImages.pdf).

### Related products
* Hands-On Networking with Azure [[Packt]](https://www.packtpub.com/virtualization-and-cloud/hands-networking-azure?utm_source=github&utm_medium=repository&utm_campaign=9781788998222 ) [[Amazon]](https://www.amazon.com/dp/1788998227)

* Mastering Python Networking - Second Edition [[Packt]](https://www.packtpub.com/networking-and-servers/mastering-python-networking-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789135992 ) [[Amazon]](https://www.amazon.com/dp/1789135990)

## Get to Know the Author
**José Manuel Ortega**
José Manuel Ortega is a Software Engineer and he focuses on new technologies, open source, security and testing. His career target from the beginning has been to specialize in Python and security testing projects. In recent years he has developed interest in security development, especially in pen-testing with python. Currently he is working as a security tester engineer and his functions in the project are analysis and testing the security of applications both web and mobile environments.
