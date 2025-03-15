# tesi-PhD
Please cite as:
```
@phdthesis{cappelli2022implicit,
  title        = {Implicit indefinite objects at the syntax-semantics-pragmatics interface: a probabilistic model of acceptability judgments},
  author       = {Cappelli, Giulia},
  year         = 2022,
  note         = {Available at \url{https://hdl.handle.net/11384/133342}},
  school       = {Scuola Normale Superiore},
  type         = {PhD thesis}
}
```

## Data (stimuli and results)
The interested reader will find my data, i.e. the stimuli for each experiment and the raw results I got from participants, in [a repository](https://github.com/giuliacappelli/dissertationData) containing:
* 30 target verbs and 10 filler verbs both for English and for Italian, used in all the computational and behavioral experiments;
* full lists of the direct objects of each target verb as extracted from the ukWaC corpus for English and from itWaC for Italian, both raw and manually cleaned;
* stimuli, full judgments elicited from 25 participants per language on a 7-point Likert scale, and final scores obtained in the Behavioral PISA experiment;
* each verb tagged with its features relative to the verb-specific predictors of object drop, i.e. telicity, manner specification, and semantic selectivity;
* stimuli and full judgments elicited from 30 participants per language on a 7-point Likert scale in the main behavioral experiment of this thesis, aimed towards creating a Stochastic Optimality Theoretic model of object drop in English and Italian.

## Experiments (source code)
The source code for the PsychoPy Builder experiments I designed for this PhD thesis, to be run on Pavlovia and possibly distributed via Prolific, are available here [in a dedicated repository](https://github.com/giuliacappelli/psychopy_exps).

## Code (data processing and analysis)
As for the data processing, analysis of results, computational implementation of experimental designs, and creation of stimuli, I coded several Python scripts and documented their usage on GitHub. In detail:
* [Quantify the polysemy of words in a list](https://github.com/giuliacappelli/checkPolysemy) using WordNet (Wu-Palmer Similarity).
* [Behavioral PISA](https://github.com/giuliacappelli/behavioralPISA), a (behavioral) measure of Preference In Selection of Arguments to model verb argument recoverability. The script takes care both of creating the stimuli for the experiment and of generating Behavioral PISA scores based on the Likert-scale acceptability judgments provided by human participants.
* [Psychopy-to-Medina converter](https://github.com/giuliacappelli/PsychopyToMedina), to convert the output of my PsychoPy behavioral experiment into a suitable input for my scripts to analyse the results and create Stochastic OT models of the implicit object construction.
* [Modeling the grammaticality of implicit objects](https://github.com/giuliacappelli/MedinaStochasticOptimalityTheory) based on Medina's (2007) variant of Stochastic Optimality Theory.
* [Generate mock Likert-scale acceptability judgments](https://github.com/giuliacappelli/generateMockLikertGrammaticalityJudgments) based on factor levels specified in the input, to test the above Stochastic Optimality Theoretic model on ideal data before running the experiment proper.
