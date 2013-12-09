### slimechat

Matrix like theme with black background and green text for limechat. I am using the Menlo font which in on my macbook so you may need to change that if you don't have it. You only need to copy the css and yaml file to the following directory. It's hidden in finder so you have to use terminal. 

Put the two files on your desktop and open a terminal window and copy and paste the following line into terminal:

```bash
cp ~/Desktop/slimechat.* "/Users/nickfox/Library/Application Support/net.limechat.LimeChat-AppStore/Themes/"
```

change __nickfox__ to __your username__. I also have a special timestamp that I like to use and you have to put this into limechat preferences under the theme tab. Check the box that says override timestamp format and add the following:

```java
%a %I:%M%p
```

Here is what it looks like.

![alt text](https://raw.github.com/nickfox/slimechat/master/limechat.png "slimechat")
