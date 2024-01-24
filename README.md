# snippet-catalog
A home for my unsorted code snippets. I will try my best to document what each snippet is supposed to be in 2-3 sentences.

## algo/

### cluster-likelihood/

I was given a prompt where, given a population of data points on a map, a subset of those points had a treatment applied. The cluster-likelihood algorithm evaluates whether treated points have neighboring treated points (within a threshold of distance and distance-rank) and labels them as a cluster. Clusters can then be further scored with things like node size/count, edge strength/count, etc. for further refinement.
