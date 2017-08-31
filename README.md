## Welcome to shashank-ssriva.github.io

This is home to some of the useful Applications that I have authored along-with my friend. I am not a developer per se, so the credit goes to my friend for her hard-word & dedication(code). I basically work on the UI & implementing new features. You may call me a tester as well ;-) And yeah, I am a SysAdmin & a DBA so you get the idea ;-)

To keep an eye on my project, please visit my [blog](https://shashank-ssriva.github.io/blog/) hosted on GitHub itself.

Below are some of my most favorite repositories that I have created.

### ExClaiMadEasy

Probably the most exciting Application I am a part of :-) ExClaiMadEasy (stands for Expense Claims Made Easy) is an extremely light-weight MySQL backed Web-app written in PHP for making submission of your Cab Expense Claims a breeze. All you need is to choose date(s) & enter bill amount in its soothing, beautiful UI. [ExClaiMadEasy](https://exclaimadeasy-monika.rhcloud.com/) will automatically generate a PDF document with the tables of your entries that you can print out, sign & submit to your office department for reimbursements. No more struggling with Excel sheets :-)

### How Much I Saved?

A web-app written in PHP that helps you track how much money you have saved by any means, be it coupon/voucher/deal or anything like that. Even though it might sound childish, I am quite proud of it since its my first ever coding project & I feel so excited for it :-) I am not a developer, as you already know it :-)
[How Much I Saved?](http://www.howmuchisaved.in) is a simple & perhaps beautiful way to track your savings. Atleast, I think so :-)

### [White Space Remover](https://github.com/shashank-ssriva/whiteSpaceRemover)

Prettifies your code by removing unneccessary whitespaces.

```shell
./whiteSpaceRemover.sh filename
```
Below is the example of JavaScript code : - 

> before the script execution.

```js
document.write("<h2>Table of Factorials</h2>");


for(i = 1, fact = 1; i < 10; i++, fact *= i) {



    document.write(i + "! = " + fact);

    document.write("<br>");
}
```
> after the script execution.

```js
document.write("<h2>Table of Factorials</h2>");
for(i = 1, fact = 1; i < 10; i++, fact *= i) {
    document.write(i + "! = " + fact);
    document.write("<br>");
}
```

### [Find Replace](https://github.com/shashank-ssriva/FindReplace)

An Ubuntu .deb package/command line utility that mimics Find/Replace functionality available in most Text Editors.

```shell
root@shashank-dbserver:/home/shashank# findreplace test.txt

Welcome to findreplace! A cute, little utility that mimics Find/Replace functionality available in most Text Editors. No more struggling with syntax :-)

Safety first! Hence, backing up the original file as 'test.txt.findreplace.orig'...

Enter the word you want to replace...tomatoes

Searching for 'tomatoes' in test.txt...

Word 'tomatoes' encountered 1 time(s). Good to go ahead with replacement ;-)

Enter what you want 'tomatoes' to be replaced with...potatoes

Replacing 'tomatoes' with 'potatoes'...

Below is your edited file displaying only the line(s) containing replaced text.

I love potatoes.

Hope you liked it ;-)
```

## [TextInFile](https://gist.github.com/shashank-ssriva/6595bfe80fc75346aeed64acf7b0802f)

A simple, command-line utility that lets you search for a text string in a given directory.

```bash
shashank@shashank-dbserver:~/Desktop$ ./textinfile.sh /var/log/apache2/

Detecting OS of your machine..

Your OS is : - Ubuntu.

Checking figlet insallation...

/usr/bin/figlet
figlet already installed! Lets get started :-)
 _____         _   ___       _____ _ _      
|_   _|____  _| |_|_ _|_ __ |  ___(_) | ___ 
  | |/ _ \ \/ / __|| || '_ \| |_  | | |/ _ \
  | |  __/>  <| |_ | || | | |  _| | | |  __/
  |_|\___/_/\_\\__|___|_| |_|_|   |_|_|\___|
                                            
Welcome to TextInFile! A cute, little utility that allows you to search for the text inside directories from the command-line :-)

Enter the string that you want to search inside /var/log/apache2/...GET /static/4d441666/scripts/yui/menu/assets/skins/sam/menu.css HTTP/1.1

Searching for GET /static/4d441666/scripts/yui/menu/assets/skins/sam/menu.css HTTP/1.1 in /var/log/apache2/...

GET /static/4d441666/scripts/yui/menu/assets/skins/sam/menu.css HTTP/1.1 was found 2 time(s) inside /var/log/apache2/.

Below is your Search Result :-)

/var/log/apache2/access_reverse_proxy.log.1:7:192.168.0.50 - - [25/Jun/2017:05:35:51 +0200] "GET /static/4d441666/scripts/yui/menu/assets/skins/sam/menu.css HTTP/1.1" 200 1654 "http://192.168.0.51/" "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/59.0.3071.104 Safari/537.36"
/var/log/apache2/access_reverse_proxy.log.1:2807:10.0.2.2 - - [27/Jun/2017:03:44:31 +0200] "GET /static/4d441666/scripts/yui/menu/assets/skins/sam/menu.css HTTP/1.1" 200 1654 "http://localhost:8000/" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_12_5) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/58.0.3029.110 Safari/537.36"

This utility took 12 seconds to run(including the time you took to type/paste your string).

That's all folks! Hope you liked TextInFile ;-)
```

## Other Blogs

Below are some of the blogs I have written :-)
* [Linux & Database](https://watilearnd2day.wordpress.com/)
* [Music](http://mymusicrevu.blogspot.com/)
* [Photography](https://eyesmeetlenses.wordpress.com/)
