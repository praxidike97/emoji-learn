# emoji-learn

## Whats is emoji-learn? 🤔

emoji-learns is a simple library to create neural networks - in [Emojicode](https://www.emojicode.org)!  
How can this not be awesome??

## Prerequisites 📝
Emojicode version 0.9+ is required. Go [here](https://github.com/emojicode/emojicode) to find out how to install it.  
If you want to find out how to use Emojicode go through the excellent [language reference](https://www.emojicode.org/docs/reference/) or [package index](https://www.emojicode.org/docs/packages/).

## Documentation 🤓

## numlol 💯
Machine learning and especially neural nets rely heavily on the use of linear algebra (LinAlg) - we need to add, substract and multiply matrices and vectors. Unfortunately, the only data structure available in the standard Emojicode package that comes close to what we need are lists. 

```
💭 A list of integers
🍨 1 2 3 4 5🍆
```

Because of this emoji-learn ships with a dedicated LinAlg-library called numlol (not to be confused with the imposters from [numpy](https://numpy.org/).  
  
Creating a new numlol array is as simple as one-two-three, just hand over an embedded list to its constructor.

```
💭 Create a 3*2 matrix and store it in the variable 'matrix'
  🆕🍎🆕 🍨🍨 1.0 2.0 🍆
            🍨 3.0 4.0 🍆
            🍨 5.0 6.0 🍆🍆 ❗➡️ matrix
            
💭 Create a 3*1 vector and store it in the variable 'vector'
  🆕🍎🆕 🍨🍨 1.0 🍆
            🍨 3.0 🍆
            🍨 5.0 🍆🍆 ❗➡️ vector
```

In the numlol package all kind of matrix and vector operations are implemented:
(Note: most methods are implementes as static methods so that the method name itself is followed by 🐇🍎)  

Want to add two vectors? No problem!

```
💭 Elementwise addition of two arrays with the same shape
🍋🐇🍎 array01 array02❗➡️ sum_array
```

You suddenly need to transpose a matrix? Here you go!

```
💭 Transpose array
🍔🐇🍎 array0❗➡️ transposed_array
```

It is neccesary to perform a matrix-matrix/matrix-vector multiplication? Sure!
```
💭 Do matrix-matrix/matrix-vector multiplication
🥐🐇🍎 array01 array02❗➡️ multiplied_array
```

It also contains some more complicated functions we will need for machine learning later, e.g. the mean squared error function (👬) or the logistic activation function (📸). 

### emoji-learn
