# learning-code
Lessons and examples for learning python

## 1. Variables: Containers for information

*Variables are names in your code that hold information. This information can be numbers, words, or other things. You can change what information a variable holds.*

Another way to think about variables is to imagine you have a box where you can store your toys. Each box has a label on it so you know exactly what toy is inside without opening it. In coding, a variable is like that box. You can put information inside it, like numbers or words, and give it a name so you can find that information again later. For example, if you have a box (variable) named "catName," you might store the word "Whiskers" inside it.

### Numbers: Like counting your steps

```python
steps = 20
distance = 5.2
```

### Strings: Holding messages or names

```python
message = "Hello!"
name = "Alice"
```

### Arrays: Like bags holding many things of the same type

```python
fruits = ["apple", "banana", "orange"]
```

### Boolean: Like playing true or false

```python
is_raining = true
```

## 2. Data Types: Choosing the Right Tool!

*Data types tell you what kind of information can be stored in a variable. Common types include numbers, text (called "strings"), and true/false values (called "booleans").*

Each tool is best for specific tasks. You wouldn't use a hammer to write a message, right?

```python
steps = "five" # This will cause an error, steps should be a number, not text!
fruits = 5 # This will also cause an error, fruits should hold multiple items, not a single number.
```

Another way to think about data types is to think about the different kinds of toys you can put in your boxes. Some toys might be action figures, some might be puzzles, and some might be books. In the world of coding, these are like data types. They tell you what kind of information is stored in your variable. So, if your box is supposed to hold numbers, that's one data type (like counting marbles). If it's supposed to hold words, that's another data type (like names of your friends).

## 3. Loops: Repeating Actions Like a Pro!

*Loops are a way to make your code do something over and over again without having to write the same thing many times. For example, if you want to count from 1 to 10, you can use a loop.
Imagine building a wall brick by brick. Loops let you repeat actions multiple times.*

```python
Print "Hello!" 3 times:
for i in range(3):
    print("Hello!")
```
```python
Draw 10 stars:
for i in range(10):
    print("*", end="")
```

Another way to think about loops is to imagine you have a list of chores to do every day: make your bed, brush your teeth, and pack your backpack. Instead of your mom or dad telling you each day to do each chore one by one, they could say, "Do your daily chores," and you'd do all of them in order. In coding, a loop is a way to tell the computer to do a bunch of steps over and over again, like doing your chores, without having to write them down each time. It keeps going until all the chores are done or until you decide to stop.

## 4. Conditional Statements: Making Decisions!

*These are like decision-makers in your code. They can check something (like if it's raining) and then do different things based on whether it's true or false (like take an umbrella if it is raining).*

Imagine choosing a path based on the weather. Conditionals check something and act accordingly.

Is it raining? (True or False)

```python
is_raining = True

if is_raining:
    print("Bring an umbrella!")
else:
    print("Wear sunglasses!")
```

Did the robot find the key? (True or False)
```python
has_key = False

if has_key:
    print("Open the door!")
else:
    print("Keep searching!")
```

So suppose you're playing a game where you can only go outside if it's not raining. You look outside, and if it's sunny, you go out to play. If it's raining, you stay in and read a book. This is like a conditional statement in coding. It's a way for the computer to make a decision: if something is true (it's sunny), it does one thing (go outside); if it's not true (it's raining), it does something else (stay inside and read).

## 5. Functions: Reusable Blocks of Code!

*Functions are pieces of code that do a specific job. You can use them to do that job whenever you need it, without having to write the same code again. You can also give them information they need to work with when you use them.*

Imagine having a pre-built robot dance routine. Functions are like these reusable blocks.

```python
def sing_hello():
    print("Hello! Hello!")

sing_hello()  # Call the function to sing
```
Think about when you're getting ready to go to a friend's birthday party. You have a list of things you always do: pick a gift, wrap the gift, and write a card. You do these steps every time you go to a birthday party. In coding, a function is like your "get ready for a party" checklist. It's a set of steps that you can use over and over again, whenever you need to do that task. You just tell the computer, "It's party time!" and it knows to do all those steps without you having to explain them every time.
