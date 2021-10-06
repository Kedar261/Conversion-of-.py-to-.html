# Conversion-of-.py-to-.html
simple way of conversion of .py to .html
#Write a Python function to create the HTML string with tags around the word(s)
#add_tags('i', 'Python') -> '<i>Python</i>'
#add_tags('b', 'Python Tutorial') -> '<b>Python Tutorial </b>'
str = 'python'
tag = "<%s>" +str +"</%s>"
print(tag.replace("%s","i"))
print(tag.replace("%s","b"))
