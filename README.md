# path_semantics
A research project in path semantics, a re-interpretation of functions for expressing mathematics

[Tutorial](https://github.com/advancedresearch/path_semantics/wiki/Tutorial-1:-Types)  
[A brief history of path semantics illustrated with stick figures](https://github.com/bvssvni/path_semantics/blob/master/papers-wip/history-of-path-semantics-illustrated.pdf)

Blog posts:

- [2017-08-25 Homotopy and Geometry](https://github.com/advancedresearch/advancedresearch.github.io/blob/master/blog/2017-08-25-homotopy-and-geometry.md)
- [2017-07-20 Generalizing Path Semantics to Probability Theory](https://github.com/advancedresearch/advancedresearch.github.io/blob/master/blog/2017-07-20-generalizing-path-semantics-to-probability-theory.md)
- [2017-06-28 Standardizing Path Semantics](https://github.com/advancedresearch/advancedresearch.github.io/blob/master/blog/2017-06-28-standardizing-path-semantics.md)
- [2017-06-25 Progress on Existential Paths](https://github.com/advancedresearch/advancedresearch.github.io/blob/master/blog/2017-06-25-progress-on-existential-paths.md)
- [2017-06-03 Perfect Intelligence](https://github.com/advancedresearch/advancedresearch.github.io/blob/master/blog/2017-06-03-perfect-intelligence.md)
- [2017-05-29 Golden Rationality](https://github.com/advancedresearch/advancedresearch.github.io/blob/master/blog/2017-05-29-golden-rationality.md)
- [2017-04-23 Existential Paths](http://blog.piston.rs/2017/04/23/existential-paths/)
- [2017-04-20 Slot Lambda Calculus](http://blog.piston.rs/2017/04/20/slot-lambda-calculus/)
- [2017-03-24 Proving Non-Existence of Monoid Symmetric Paths](http://blog.piston.rs/2017/03/24/proving-non-existence-of-monoid-symmetric-paths/)
- [2017-02-20 New Algorithm for Inferring Equations](http://blog.piston.rs/2017/02/20/new-algorithm-for-inferring-equations/)
- [2015-07-03 Path Semantics](http://blog.piston.rs/2015/07/03/path-semantics/)

### Get Your "Perfectly Intelligent Given Perfect Knowledge" T-Shirt Today!

A T-shirt design with printed symbols `∃f{}` (read out loud as "universal existential path").
It is a higher order concept, a kind of mathematical superpower, which hypothetically might be used to solve problems with optimal efficiency. With other words, it makes you perfect intelligent given perfect knowledge about a problem.

By purchasing this T-shirt, you support the research on path semantics:

#### Man Basic T-Shirt

 <div style="text-align:center;line-height:150%"> <a href="https://www.zazzle.com/perfectly_intelligent_given_perfect_knowledge_t_shirt-235515100047304821?rf=238435142389717543" rel="nofollow" > <img src="https://rlv.zcache.com/perfectly_intelligent_given_perfect_knowledge_t_shirt-r372977b0e3b944e5965727f02d403d40_k2gmx_325.jpg?bg=0xffffff" alt="Perfectly Intelligent Given Perfect Knowledge T-Shirt" style="border:0;" /> </a> <br /> <a href="https://www.zazzle.com/perfectly_intelligent_given_perfect_knowledge_t_shirt-235515100047304821?rf=238435142389717543" rel="nofollow" >Perfectly Intelligent Given Perfect Knowledge T-Shirt</a> <br />by <a href="https://www.zazzle.com/bvssvni?rf=238435142389717543" rel="nofollow">bvssvni</a> </div>

#### Woman Basic T-Shirt

 <div style="text-align:center;line-height:150%"> <a href="https://www.zazzle.com/perfectly_intelligent_given_perfect_knowledge_t_shirt-235236917750244863?rf=238435142389717543" rel="nofollow" > <img src="https://rlv.zcache.com/perfectly_intelligent_given_perfect_knowledge_t_shirt-r387d2ec7847b4f648f6b4540eefa7851_k2gmm_325.jpg?bg=0xffffff" alt="Perfectly Intelligent Given Perfect Knowledge T-Shirt" style="border:0;" /> </a> <br /> <a href="https://www.zazzle.com/perfectly_intelligent_given_perfect_knowledge_t_shirt-235236917750244863?rf=238435142389717543" rel="nofollow" >Perfectly Intelligent Given Perfect Knowledge T-Shirt</a> <br />by <a href="https://www.zazzle.com/bvssvni?rf=238435142389717543" rel="nofollow">bvssvni</a> </div>

### What is path semantics?

Here is a cheat sheet to show how it looks like: [Path Semantics Cheat Sheet](https://github.com/advancedresearch/path_semantics/blob/master/papers-wip/path-semantics-cheat-sheet.pdf)

Functional programming has been an active research area for [dependently types](https://en.wikipedia.org/wiki/Dependent_type).
In this notation, a new semantics that re-interprets functions takes a step beyond dependently types.

Very briefly, path semantics is about things like:

- How functions are constructed and connected
- How to express relationships between functions in a more strict way than equations
- What can be predicted about output of functions from something about the input
- What it means to refer to a function (function identity)
- What you can do with functions, given some class of knowledge about them is available
- What kind of structures are related to some class of functions

See the [wiki](https://github.com/advancedresearch/path_semantics/wiki) for more information.

### Is this a new programming language?

A new *kind* of programming language.

The project is about defining a new category of programming languages that satisfy a different method of expression compared to traditional languages.
The ideas are original, but inspired by recent advancement in type theory.

Goals:

- Create efficient algorithms that find paths
- Find deductive rules
- Find rules for well formed expressions
- Find applicable areas (machine learning etc.)
- Find generalizations (probability theory etc.)

### Previous work

Some ideas are taking from unpublished work. I have been asked to publish it but have not gotten time to do it yet.

Earlier, I explored ways to encode information into a generalized version of Adinkra diagrams to model states of discrete systems. The idea is since Adinkra diagrams are constructed by labeling the edges after specific rules, one could extract rules from edges of similar diagrams representing systems.

These diagrams have a reflective property that allows related concepts to be expressed with variations in a systematic way, intuitively described as "context modelling". This background knowledge, together with dependently type experiments, served as rationale for developing the notation.

While suitable to model context in various applications,
a problem is super exponential growth in memory usage.
Path semantics constructs a space that appear similar to the structure of such diagrams,
but compresses the information in a human readable form.

The diagrams have some important properties:

- Can be described fully using only an array of integers `[a, b, c, ...]`
- Uses direct group product as building block `[a, b] x [c, b] = [a, b, c, d]`
- The class with lowest complexity, `[2, 2, ...]`, are edges of hypercubes, as in Adinkra diagrams
- All diagrams are subset of itself in a single dimension `[N]`, which has the highest complexity

For algorithms to compute with these diagrams, see `Context` in the [discrete](https://github.com/bvssvni/discrete) library.
