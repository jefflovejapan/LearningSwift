---
layout: post
title: First Steps
---

# Let's get programming

> Welcome! If you want to play around with Swift on your own while you read this, you can download an Xcode playground [here](https://www.dropbox.com/sh/0h1p65kdgixw4ku/AABSMk4G8B9CYpJIrLym7x_ca?dl=1). If you have Xcode installed you can just double-click on this file to open it.

When we write programs we're going to be working with data, like names and phone numbers, heights, colors, products, and images. Each of these pieces of data has a certain *type.* Here are some of the types we're going to work with:

### Strings

Strings are things like words, sentences, and names -- things that you can express in written characters. Here's how you make a string:

{% highlight swift %}
let helloMsg = "Hello, World!"
{% endhighlight %}

Here, the **name** of our string is `helloMsg`, and its **value** is "Hello, World!" `let` tells the system that you're creating a new string, and we need to use it every time we create a new value of any type, not just strings. 

Later, when we want to work with this string, we can refer to it by its name:

{% highlight swift %}
helloMsg + helloMsg

// "Hello, World!Hello, World!"  <- the two lines at the front of this line mark it as a comment. The system ignores these when we put them in our code.
{% endhighlight %}

### Ints

Int(eger)s are whole numbers, and they can be positive or negative. Here's how you make one:

{% highlight swift %}
let numberOfProducts = 6
let aNegativeNumber = -200
{% endhighlight %}

You can perform all the regular math operations you'd expect with ints. Often, it's easier to use Swift than to use a calculator.

{% highlight swift %}
let a = 6
let b = 5
let c = a + b

print(c)
// 11
{% endhighlight %}

### Doubles

Doubles are floating-point (decimal) numbers used to express things like measurements. These mostly work the same as ints.

{% highlight swift %}
let pi = 3.1415
let radius = 0.5
let area = pi * radius * radius

print(area)
// 0.78537500000000005
{% endhighlight %}

### Arrays

Arrays are simple collections. They hold multiple elements of a single type, so the array can either hold ints or strings, but not both. You create them like this:

{% highlight swift %}
let names = ["lindsey", "shane", "nicole"]
{% endhighlight %}

And you get things out of an array by giving it an **index**. The first element in an array is at index 0.

{% highlight swift %}
names[0]
// "lindsey"

names[2]
// "nicole"
{% endhighlight %}

### Dictionaries

Dictionaries are collections of **keys** and **values**. In a paper dictionary, the key is the word you're looking up, and the value is its definition. Here's how you make one:

{% highlight swift %}
let heights = ["brian": 183, "chris": 175, "jeff": 178]
{% endhighlight %}

You get things out of a dictionary by giving it a key.

{% highlight swift %}
heights["brian"]
// 183
{% endhighlight %}

Like arrays, the data inside dictionaries has to all be of the same type.

That's it!

