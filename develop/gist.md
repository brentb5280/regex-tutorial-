# regex Anchors 

The purpose of this tutorial is to descibe Anchors in Regular Expression (regex)

## Summary

In this tutorial I will cover Anchor tags used in regex. Anchors have special meaning Anchors specify a position in the string where a match must occur. When you use Achors in your search expression, the regular engine doesn't go through the string or consume characters; it looks for a match in the specified position. 

## Table of Contents

- [Anchors](#anchors)




### Anchors
 -Anchors don't match any character, Instead they match a postion before and after. Use (^) anchor to match the begingin of the text and the ($) anchor to match the end of the text. The (m) flag to enable the multiline mode that instructs the (^) and ($) anchors to match the beginning and end of the text as well as the beginning and end of the line. by default the (^) Anchor specific that the following pattern must begin at the first character of the string. The ($) Anchor specifies that the preceding pattern must occur at the end of the input string or before (\n) at the end of the input string. 

Code:   let str = "JavaScript';
        console.log(/^J/.test(str));
        let str = 'JavaScript';
        console.log(/t$/.test(str));



## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
