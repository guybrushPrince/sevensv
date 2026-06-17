# Seven Soundess Violations (7SV) Teaching Materials Repository

This is a repository providing teaching materials for the Seven Soundness Violations (7SV) as error patterns 
in BPMN modeling.

**Please note that you can use all materials in your lectures/tutorials/etc. as long as you refer to this repository and to the name of its author: *Thomas M. Prinz*.**

In this repository, you will find:

- ```/examples```: Examples for each anti-pattern of the 7SV for teaching. Also, it contains examples of *fault blocking*, *fault masking*, *fault illusion*, and *fault distance*. 
                   All examples are available as ```*.bpmn``` and ```*.svg```.
- ```/testsheets```: 
    - ```/prepared```: A prepared test for two groups containing a pre- and a post-test (```Tests_A_and_B.pdf```) and its solutions (```Tests_A_and_B_solutions.pdf```).
	- ```/template```: A template LaTeX file ```template.tex``` for creating a test out of exercises in ```/exercises```.
- ```/exercises```:
    - ```instructions_levels-1-5.md```: General instructions for all exercises of levels 1 to 5.
	- ```instructions_levels-6-10.md```: General instructions for all exercises of levels 6 to 10.
	- ```*.png```: Images for different answer possibilities.
	- ```items```: 10 folders with exercises in different levels. Participants should mark errors in exercises with levels 1 to 5 (if any). For exercises of level 6 to 10, participants shall complete process models.
	    - ```level-1```: 9 simple acyclic, block-structured exercises with sound and unsound process models (as ```.bpmn``` and ```.svg```).
		- ```level-2```: 9 simple cyclic, block-structured exercises with sound and unsound process models (as ```.bpmn``` and ```.svg```).
		- ```level-3```: 5 exercises with dead loops (2) and livelocks (3) (as ```.bpmn``` and ```.svg```).
		- ```level-4```: 9 advanced cyclic non-block-structured exercises (as ```.bpmn``` and ```.svg```).
		- ```level-5```: 18 complex exercises (as ```.bpmn``` and ```.svg```).
		- ```level-6```: 6 simple acyclic, block-structured exercises with "open" gateways (as ```.svg```).
		- ```level-7```: 4 simple cyclic, block-structured exercises with "open" gateways (as ```.svg```).
		- ```level-8```: 4 exercises with dead loops and livelocks to complete (as ```.svg```).
		- ```level-9```: 9 advanced cyclic non-block-structured exercises with "open" gateways (as ```.svg```).
		- ```level-10```: 18 complex exercises with "open" gateways (as ```.svg```).
- ```/data```: Some data sets resulting from experiments/studies/tests.

**Note:** Use *BPMNinvest* to teach the 7SV interactively. A demo is freely available at: (https://guybrushprince.github.io/bpmninvest/)[https://guybrushprince.github.io/bpmninvest/].

CC BY 2026 Thomas M. Prinz
Thomas.Prinz@uni-jena.de