## Intro
This repository adds an `explore_subgoal` command to Mathias Fleury's Explorer.thy.
The original theory can be found here: 
https://bitbucket.org/isafol/isafol/src/master/lib/Explorer.thy.
The commands provided in this theory allow one to generate templates for Isar proofs from the
current goal state.
The new command generates a template in a form of a number of `subgoal` commands for an apply-style
proof. 

## Usage
Import the theory and type `explore_subgoal` during a proof
(or try `explore`, `explore_have`, `explore_lemma`, or `explore_context`).