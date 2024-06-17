### XSS-DVWA-SOLUTION
``` Welcome to the DVWA XSS Solutions repository! This repository contains comprehensive solutions for Cross-Site Scripting (XSS) vulnerabilities in the Damn Vulnerable Web Application (DVWA). These solutions are meticulously provided by Nihar Rathod, also known as BugBot19 ```

### Overview
```The Damn Vulnerable Web Application (DVWA) is a popular web application designed for security professionals and enthusiasts to practice their web security skills in a legal and safe environment. This repository focuses on addressing and mitigating XSS vulnerabilities, one of the most common and critical web security issues.```

![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/949deaaa-2f13-4bb8-b2fd-6dfe8af11e02)

# XSS (DOM) 
```A DOM-based cross-site scripting (XSS) attack happens when a threat actor modifies the document object model (DOM) environment in the victim's browser. So, while the HTML itself doesn't change, the code on the client side executes differently.```

# LOW 
```Payload-<script>alert('BugBot19 was here')</script>```

![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/b2e8392c-5c65-4d06-ab00-6385f0afbc15)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/11ef8741-004e-45b1-bcfe-2d66d0b7c175)

# MEDIUM
```Payload-<script>alert('BugBot19 was here')</script>```

![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/6ed8d892-dd6d-4fc5-81b6-929d7cddedd4)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/690708a5-11c1-4d01-8868-b69611eb58d0)

# High
```Payload-<script>alert('BugBot19 was here')</script>```
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/0f06a1ce-092b-48bf-b5e8-dc4a36f151f3)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/39839dae-2ad4-49c6-8e27-ee288cd244ce)

# XSS (Reflected)
```reflected XSS is a kind of cross-site scripting attack, where malicious script is injected into websites that are trusted or otherwise benign. Typically, the injection occurs when an unsuspecting user clicks on a link that is specifically designed to attack the website they are visiting.```

# LOW/MEDIUM/HIGH
``` During the research phase, i found out that one of the payloads can be used in all three levels the payload is mentioned below```
```Payload-<svg onload=alert('BugBot19 was here')>```
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/ec196e0c-8285-4971-a7c4-89ac9ce4bb1f)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/3b4da94f-3ead-4d67-9798-255ca536a85c)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/3125143c-6709-4c8a-90e6-2312db962a27)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/2f7c4eaa-1ac4-4e42-b7af-9d5a05bed13b)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/2c729f4c-633b-4080-a44e-fda654eaccf4)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/fe80185d-36bf-4996-bbd6-871cdb1882ed)

# XSS (Stored)
```Stored XSS, also known as persistent XSS, is the more damaging of the two. It occurs when a malicious script is injected directly into a vulnerable web application. Reflected XSS involves the reflecting of a malicious script off of a web application, onto a user's browser.```

# Low
```Payload - <script>alert(document.domain)</script>```
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/c91a9a4f-08c1-4a1e-8d05-a6c1fc3806a4)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/cfbe180d-69b7-4b29-8cd9-7b05d0740a87)

# Medium
```Payload - <img src=x onerror=alert(document.cookie)>```
Change the text 'size' and 'max length'
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/a2325489-0375-460d-8087-eadcc9afefc5)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/24bda2e6-9a38-4d5a-b058-590593fee838)

# High
```Payload - <body onload=alert('Bugbot19')>```
Change the text 'size' and 'max length'
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/f2ce8a4a-16ae-4ddd-b177-7c2912ee58f9)
![image](https://github.com/kashrathod19/XSS-DVWA-SOLUTION/assets/54115061/4e6ac017-3971-4c7c-816d-541c333c8dd2)


