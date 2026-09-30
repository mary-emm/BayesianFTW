# 01 - The Globe Toss

**Book reference:** Statistical Rethinking, Chapter 2

## The question

If I toss a globe and catch it, what's the probability my right thumb lands on water?

McElreath uses this to introduce Bayesian updating.

Each toss is an observation → We start with a prior, observe data, get a posterior.

The posterior **then** becomes the next prior.

## What this project does

- Builds the posterior using grid approximation
- Shows how the posterior updates with each new observation
- Visualizes prior → likelihood → posterior

## Key concept

The posterior is again the **distribution** over all possible values of p (in this case, the proportion of water), weighted by how consistent each value is with the data and our prior beliefs.

## Files

- `analysis.qmd` — full walkthrough with code and plots
