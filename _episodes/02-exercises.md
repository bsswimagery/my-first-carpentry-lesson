---
title: "Introduction to Exercises"
teaching: 20
exercises: 10
questions:
- "How to write a exercise?"
objectives:
- "Know how to write a exercise."
keypoints:
- "Exercises are write inside `>`-block."
---

This is our first exercise.

~~~
print("Hello Carpentries instructors!")
~~~
{: .language-python}

~~~
Hello Carpentries instructors!
~~~
{: .output}

~~~
x <- c(4,)
~~~
{: .language-r}

~~~
Missing element after comma
~~~
{: .error}

```{r}
4 -> x
```

> ## What is need in a exercise
> 
> List all the elements that you need inside a exercise
> to comply with the Carpentries style.
>
> > ## Solution
> >
> > Exercises are inside a `>`-block and each block must have
> >
> > - one title
> > - exercise body
> > - solution to exercise
> {: .solution}
{: .challenge}

You can use code blocks inside exercises.

> ## How to use R code in R Markdown
> 
> Provide one example of one R code
> that is going to be run by R Markdown.
>
> > ## Solution
> >
> > ```{r}
> > x <- 1
> > 1 -> y
> > x + y
> > ```
> {: .solution}
{: .challenge}
