# reverse-a-string
Define a function called reverse that takes a string textand returns that string in reverse.

For example: reverse("abcd") should return "dcba".

You may not use reversed or [::-1] to help you with this.
You may get a string containing special characters (for example, !, @, or #).

code below 

def reverse(text):
    reversed_string=""
    index=len(text)-1
    for s in text:
        reversed_string+= text[index]
        index-=1
    return reversed_string
