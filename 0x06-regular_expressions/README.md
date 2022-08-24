# 0x06. Regular expression
##### A dive into Regexp as used by software engineers
##### Background Context
```
For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.
Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in between the //:

```
sylvain@ubuntu$ cat example.rb<br/>
\#!/usr/bin/env ruby<br />
puts ARGV[0].scan(/127.0.0.[0-9]/).join<br/>
sylvain@ubuntu$<br/>
sylvain@ubuntu$ ./example.rb 127.0.0.2<br/>
127.0.0.2<br/>
sylvain@ubuntu$ ./example.rb 127.0.0.1<br/>
127.0.0.1<br/>
sylvain@ubuntu$ ./example.rb 127.0.0.a<br/>
```
```
