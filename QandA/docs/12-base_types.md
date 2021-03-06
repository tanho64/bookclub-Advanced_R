# Base Types

## Introduction {-}

:::question
> encapsulation: the user doesn’t need to worry about details of an object because they are encapsulated behind a standard interface.

What is meant here by encapsulation?
:::

Random forests, glm, neural nets are implemented differently internally. But to predict the class for a new sample based on a fitted model, you just use the 'predict' generic. You don't need to know how prediction is performed, just that 'predict(my_fit)' makes it happen

:::question
> This makes [RC] harder to reason about, but allows them to solve problems that are difficult to solve in the functional OOP style of S3 and S4.

Maybe this question is better answered when we finish this section but what are these scenarios in which RC is a better choice than S3 and S4?
:::

:::TODO
:::

## 12.3 Base types {-}

:::question
What is a symbol? How is this different from a character?


```r
typeof(quote(a))
```

```
## [1] "symbol"
```
:::

symbol is the difference between: `"a"` and `a`. One is a string and the other represents an object in the environment. **A quoted object is not the same as a string**



