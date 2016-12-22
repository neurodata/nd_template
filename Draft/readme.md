(google doc template can be found [here](https://drive.google.com/previewtemplate?id=1nE9kNQmuXgYMQSgc6ozhjVIyIq3DJnfEJCXDgCGBAbM&mode=public))

# General Guidelines


-   Decide who your readers are. Remember, at least a subset of your readers are
    the editor and reviewer, who possibly know a lot about the subject matter
    (possibly more than you). Therefore, never be negative of any prior work,
    because you might be insulting the referees!

-   Generate “displays" of the main results. These results can either be
    theorems or figures, but nothing else (never a chart). One display per
    finding, no more, no less. Only when these are essentially done, does it
    make sense to really start writing. Note that if these are figures
    (containing results, rather than schmeatics), these should be generated in
    fully reproducible way. In other words, there should be a script in a
    repository that somebody else can download and run and obtain the exact same
    figure. This script should have a flag that enables the user to either (i)
    generate the results from the raw data, or (ii) just load the results.
    Different users will proceed differently, based on their interests. This
    part of the writing should take by far the longest.

-   Each display needs a \`\`caption'' (either a proof or an actual caption).
    Basically finalize this. Captions start with a 1 sentence summary describing
    what is being shown. They end with the take home message. In the middle,
    they provide all necessary details to get a reader from the first sentence
    to the last one.  
    

-   Write an outline. Read the below suggested structure, and write 1 sentence
    per paragraph, as decribed below.

-   Start filling in paragraphs. Make sure to following the
    [[https://preciseedit.wordpress.com/2012/04/03/the-3-cs-of-effective-paragraphs\|three
    C's]] convention for each paragraph.

-   Consider buying
    [[http://smile.amazon.com/Writing-Science-Papers-Proposals-Funded/dp/0199760241/ref=sr\_1\_1?ie=UTF8&qid=1427700082&sr=8-1&keywords=scientific+writing\|this
    book]] for more details.

## Abstract


Abstract is structured like introduction, but shorter, typically 125 to 250
words, definitely only 1 paragraph.

## Introduction


The introduction has a minimum of 3 paragraph, possibly more, all following the
OCARF structure.

-   **Opportunity**: This is described in a single paragraph. Convey that there
    is now some awesome **opportunity** emerging, because our colleagues have
    been working very hard doing brilliant stuff. We are on the cusp of learning
    something fundamental, that we've never been able to ascertain before.
    Remember to funnel down, from most general opportunity (eg, understanding
    the neural code for behavior), to the very specific one (eg, understanding
    which neurons may be causally involved in larval drosophila behavior). Also
    remember that this is an opportunity to tell your readers (upon whose
    shoulders your work is built), how awesome they are. They did so much great
    work to get us to the point that we could add this cherry on top.

-   **Gap**: Last sentence of 1st paragraph: but, there is a **gap**: something
    that we don't know, how don't know how to do, that resolves the age old
    mystery.

-   **Challenge**: At least 1 paragraph, maybe 1 per challenge. Explain that
    resolving this **gap**, to address **opportunity**, is very challenging for
    a number of reasons. State reasons from most obvious to least. For each,
    give credit to colleagues who have brought us much closer, though not close
    enough yet. This is another opportunity to remind the readers how great they
    are, and how you could not possibly have done with work without standing on
    their shoulders.

-   **Action**: This gets about 1 paragraph, maybe a little less. Key is
    explaining how the *action* we took addresses the *challenges* we faced, to
    fill the *gap* that existed in the literature, which now resolves the
    original **opportunity**.

-   **Resolution:** This couple sentences **resolves** the **gap**. In other
    words, there was an opportunity, that opportunity no longer exists. This
    likely includes: (i) theory, (ii) simulated experiments, (iii) real data
    analysis, (iv) model checking / synthetic data analysis.

-   **Future**: 1-2 sentences explaining what new *opportunities* now arise, by
    virtue of our resolution.

## Results


### Overview


### Simulated Experiments


## Illustrative Example


First result always illustrates the main conclusion from the paper, either via a
simulation or real data example.

## Toy Example


Next is a toy problem, that enables us to build our intuition as to why this
approach is useful.

## Complicated Examples


Stress test the method, demonstrating the extreme cases of where it works when
it should, and even when it shouldn't. Possibly this includes simulated
benchmarks.

### Theoretical Results


### Benchmark Experiments


Some real data analysis, demonstrating that our approach outperforms other
methods on several benchmark datasets.

### Experiments on Novel Datasets


A motivating example perhaps, that justifies the development of this method in
the first place.

## Discussion


-   **Summary**: In a paragraph, summarize, in a reverse funnel fashion, stating
    the precise result, and then zooming out to show its relationship to the
    more general problem. Explain how this result changes the life of the
    reader. What can she do now, that she couldn't do before?

-   **Related Work**: In about 2 paragraphs, talk about the most closely related
    results (\~1 paragraph per). Remember, the authors of these works are your
    reviewers, colleagues, and friends, so be as generous as possible, without
    stomping on your own parade. There is no reason to be at all negative of
    anybody else's work, just highlight the advantages of this work.

-   **Future**: Explain how this work enables the next work. What problems are
    now open, that we not possible to address before, or perhaps not even
    conceived of before? This also should funnel out, from the most specific
    problems, ending with the most general ones.

These are articles [@Caruana08], [@Delgado14].

## Methods


-   **Problem**: In a paragraph, describe the problem. Start with the most
    general formulation of the methods, and funnel down, much like in the first
    paragraph of the intro. For example, perhaps start with supervised learning,
    then classification, then 2-class classification, then high-dimensional
    two-class classification.

-   **Model**: In a few sentences, write down the most general statistical model
    under investigation. Perhaps it is non-parameteric, or perhaps it is a
    state-space model. Then, start making a series of simplifying assumptions.
    For each assumption, justify why you've made it. The only valid
    justifications that I now of are: (i) analytic tractability, (ii)
    computational efficiency, (iii) physical realism, (iv) reducing variance, or
    (v) increasing interpretability/understandability.

-   **Algorithm**: In a paragraph, describe the algorithm. Be as specific as
    possible. Include a pseudocode table, possibly to be put in appendix. Refer
    to equations in text where possibe.

-   **Simulations**: Describe simulation settings. This should essentially be
    parameters of the model specified above. 1 paragraph/bullet point per
    simulation study.

-   **Data**: In a couple sentences per dataset, describe it. Be sure to
    include, at a minimum, (i) a link to where it came from, (ii) the number of
    samples, (iii) the dimensionality, (iv) if any missing data, explain, (v) if
    any know structure, explain.

## Some Proofs or Auxiliary Results
