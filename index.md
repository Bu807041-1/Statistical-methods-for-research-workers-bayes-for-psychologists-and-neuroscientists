---
layout: default
---

# Statistical Methods for Research Workers: Bayes for Psychologists and Neuroscientists

[Statistical Methods for Research Workers](https://en.wikipedia.org/wiki/Statistical_Methods_for_Research_Workers), written by [Ronald A. Fisher](https://en.wikipedia.org/wiki/Ronald_Fisher) in 1925, is a landmark publication that ended up not only defining how psychologists and neuroscientists analyse their data, but also influencing how they actually perceive the world.
Almost a hundred years ago, the field of statistics, i.e. mathematics applied to data, was not structured in the way it is today, and "research workers" had to refine, and often invent the methods that would best suit their needs.
In this seminal book, Fisher codified what it meant to analyse data for the purpose of creating knowledge about the world, paving the way for what came to be statistics as we now know it. Later, the advent of computers transformed the tools available to analyse data, widening the use of statistics to researchers who did not necessarily need or want to deepen their mathematical understanding of the methods.

It is important to note that we, "research workers", do not have the same experience of statistics. Most psychologists and neuroscientists, for instance, would barely have heard of the debate between Frequentist and Bayesian methods, which can be rocking other scientific fields.
Indeed, in psychology and neuroscience, the teaching of statistics typically follows almost to the letter the table of content from Fisher's book, and it is not unusual for students to only "know" statistics through the menus of a Graphic User Interface on a proprietary piece of software, instead of acquiring the intuitions necessary to understand how distributions of data are manipulated and evaluated.

On this page, we are proposing an exploration of how Bayesian methods can be applied to the fields of psychology and neuroscience, using [Python](https://www.anaconda.com/products/individual) and [Stan](https://mc-stan.org/), with the explicit intent of providing research workers with an opportunity to see and understand what they are doing to their data.
Our motivation stems from our experience of the so-called [Reproducibility Crisis](https://osf.io/qky8t), which has hit both fields.
The Bayesian approach requires commitment to all parts of a given model, and relies on explicit assumptions formulated by the researcher.
Doing good research is thus about justifying one's choices, and not about finding a model that will yield the required number of stars in a table.

Importantly, we do not seek to engage in the debate opposing Frequentists and Bayesians.
Although our preference might transpire here and there, we favour the more oecumenical view that frequentist shortcuts can be justified in precise contexts, a point even Fisher would agree.
We will do our best to only expect entry-level Python coding skills and statistics, and to favour explaining over writing optimised code.


## Preface

_"[...] we may say that a phenomenon is experimentally demonstrable when we know how to conduct an experiment which will rarely fail to give us statistically significant results."_
[Ronald A. Fisher](https://en.wikipedia.org/wiki/Ronald_Fisher) (17 February 1890 - 29 July 1962). <ins>The design of experiments</ins> (1951). p. 14.

_"All models are wrong but some models are useful."_
[George E. P. Box](https://en.wikipedia.org/wiki/George_E._P._Box) (18 October 1919 – 28 March 2013). <ins>Robustness in the Strategy of Scientific Model Building</ins> (1979). p. 2.

_"The big problem in science is not cheaters or opportunists, but sincere researchers who have unfortunately been trained to think that every statistically 'significant' result is notable."_
[Andrew Gelman](http://www.stat.columbia.edu/~gelman/) (11 February 1965 – very much alive). <ins>Essay: The Experiments Are Fascinating. But Nobody Can Repeat Them</ins>. [The New York Times (19/10/2018)](https://www.nytimes.com/2018/11/19/science/science-research-fraud-reproducibility.html).

_"The purpose of models is not to fit the data but to sharpen the question."_
[Samuel Karlin](https://en.wikipedia.org/wiki/Samuel_Karlin) (8 June 1924 - very much alive). <ins>11th R. A. Fisher Memorial Lecture (20 April 1983)</ins> Royal Society.

### Prerequisites



### Running our notebooks


## Tests of Goodness of Fit, independence and homogeneity

## Tests of significance of means, differences of means, and regression coefficients

## Intraclass correlations and the analysis of variance



## -----

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
