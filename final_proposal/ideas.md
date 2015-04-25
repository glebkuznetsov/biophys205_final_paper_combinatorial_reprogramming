## Ideas following feedback on draft from Bulyk and Gaudet

Landscape of stability. Can we push cells into stable state?

Look into Ramanathan (and Lior?)

Reading Riddell, Rossi paper on iHSC reprogramming using 8 TFs. See also recent Rossi review paper.

As controls, use system that has already worked for reprogramming. For example, could recapitulate Yamanaka, or Rossi above.

Need to consider pioneer factors. THese are transcription factors that are capable of binding DNA despite chromatin being in the way. Brian Cleary is working on pioneer screen for this very reason.

What is the starting set of TFs? Choose these based on the expression marks of the tissue type of interest. For this, pick a tissue that has been sufficiently explored. Prefer to do it in human because ultimately we want to do iPSC / therapy type stuff. Although more data is available for mouse so that may be more feasible.

Look into papers recommended by Michael Ziller. There was something about how differentiation comes about in waves, or in two movements or something like that.

When looking for effective TFs, ideally first need to test with all TFs and lentivirus cocktail. This establishes that some combo is responsible. Then can do combinatorial test to show that we could rediscover this. How many would this be for say 36 TFs choose 8? This would be 30 million. This is a bit crazy. Why is this better than ectopic expression?

Downsides of using ectopic expression?

Still need to do virus transductions.

Probably need multiple gRNAs per target.

Bock, Meissner, 2011 shows that EPS and iPS cell states (methylation, transcription) cannot be thought as discrete points, but more as overlapping clouds.

Vision for cellular reprogramming where we can up and down-regulate genes in order to steer them toward the desired fate. Right now cells use lots of environmental signals. We hope to perturb them from inside. We could have inducible CRISPR cell lines that then operate depending on which gRNA cassettes they have available.

As an initial experiment, we want to do sorting on cells in order to narrow down the initial set of combinations.

Can we design this experiment computationally in order to narrow down the combinations?

A question,  I'm still failing to answer to myself is what exactly is the end-to-end goal.

Maybe I can start with something from the epigenomic roadmap consortium data and narrow down a set of candidates to test from there.

Overall, I need to define the overall goal, and then have the methods secondary. For example, combinatorial cas9 can be just one method. But the real goal is to be able to perturb cell state as digitally as possible. dCas9 fusions happen to be a nice weapon of choice if we can accomplish this. Though we could also imagine over-expressing or knocking down certain remodelers. The idea is to be able to do so in combination. And even better if we can do them inducibly. Ultimately, we want to play the cell like a string instrument, holding a chord here, and plucking there. 

Problem with cas9 is characterizing the sgRNAs. We might need to do this on a per-factor basis. And maybe even use combinations.

Besides modifying transcription factor expression, we also want to be able to mess with epigenetic states for example. Perhaps we limit ourselves to the transcription factors that we think are important, in addition to epigenetic remodelers. So we use combinations that way. Each of the components can be characterized independently. We could also use repressors for example.

A challenge remains with respect to the environment. Changes often take many days or weeks to work. How do we consider time courses?

Can knowledge of GRNs help design an assay that is more scalable than single cell RNA-Seq?

Could potentially characterize the effects of single TF activation and predict how they might work together in combination. Could use a fractional flow strategy here. For example, observe the fraction of the population that is activated using the single TF. Although Patrick Cahan warned against this strategy of using single TFs.

Aim 1: Validate system for combinatorial TF testing. Need to do this in system for which a differentiation "solution" is known. This could be in blood for example (Rossi).

Aim 2:
Use new system to identify candidate factors for a different system? Show that we can get closer to target tissue type as defined by GRNs from that tissue type?

Aim 3:
This can be more of a fishing expedition aim where we try various combinations and just see what we get.
