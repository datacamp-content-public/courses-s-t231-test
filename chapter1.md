---
title: 'Lab 1 - Data Visualization'
description: 'Chapter description goes here.'
free_preview: true
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

This is an example exercise.

`@instructions`


`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}

```

`@solution`
```{r}

```

`@sct`
```{r}

```

---

## Linear Regression

```yaml
type: TabExercise
key: 3804b17404
xp: 100
```

To assign a scalar or a vector (essentially a list of scalars) to a variable, R uses "<-".

`@pre_exercise_code`
```{r}
x <- c(1,2,3,4)
```

***

```yaml
type: NormalExercise
key: c8c252a726
xp: 100
```

`@instructions`
First type assign the data (1,2,3,4) to x

`@hint`
Your code should start x<-

`@sample_code`
```{r}
test
```

`@solution`
```{r}
x<-c(1,2,3,4)
milk <- read.table("milk.txt",header=TRUE,sep=",")
```

`@sct`
```{r}
check_equal(x<-c(1,2,3,4),
  incorrect_msg = NULL)
```
