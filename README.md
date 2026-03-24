# Definition of a peer-reviewed formalization 

See the dicussion below for more context: 

https://leanprover.zulipchat.com/#narrow/channel/113488-general/topic/The.20role.20of.20AI.20companies.20in.20large.20formalisation.20projects/near/581127896


## The definition 

Within the context of Lean, a peer-reviewed formalisation is Lean code which has been deemed satisfactory by an independent named (directly or by association with an established body) Lean expert in the following areas: 

1. Reusability: Whether the code is designed in a way that makes it easy for subsequent projects to build upon.
2. Organisation: For example, if theorems and definitions appear in natural places within the file / directory structure. 
3. Readability: How easy the code is to read by a Lean expert.
4. Accuracy: For example, if the code represents the the results it is claimed to.
5. Proof structure: Whether the proof structure is easy to follow, concise and where appropriate is split into lemmas of manageable size.
6. Generality: For example, if the results are at an appropriate level of generality for the task at hand. 
7. Motivation of formulations: The motivation for a particular formulation of a result is well thought-through and where appropriate other experts consulted. 
8. Integration: An appropriate level of effort has been put in to integrate the results into existing libraries where appropriate and to avoid duplicating existing work.
9. Citations: The appropriate citations are included within the formalisation to other works (formal and informal) that are used.

We propose this definition for the Lean proof assistant, but we hold the same principles to be equally applicable to projects using other proof assistants.
