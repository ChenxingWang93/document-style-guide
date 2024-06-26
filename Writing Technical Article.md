# Writing Technical Articles 

<details>
<summary> 手写✍️ WritingTechnicalArticles ResearchPaper </summary>
        
![6891698647841_ pic_hd](https://github.com/ChenxingWang93/document-style-guide/assets/31954987/e96cad99-f84c-4589-9ab6-8968ecfb03eb)
</details>
        
the notes below apply to technical papers in computer science and electrical engineering on papers in systems and networks.

Read Strunk and White, **Elements of Style**. Again.


Give the paper to somebody else to read. If you can, find two people: One people familar with the technical matter, another only generally familar with the area.


papers can be divided roughly into 2 categories, namely original _research papers_ and _survey papers_.there are papers that combine the two elements, but most publication venues either only accept one or the other type or require the author to identify whether the paper should be evaluated as a research contribution or a survey paper.(Most research paper contain a "related work" section that can be considered a survey, but it is usually brief compared to the rest of the paper and only addresses a much narrower slice of the field.)


## Research Papers 
a good research paper has a clear statement of the paper is addressing, the proposed solution(s), and results achieved. It describes clearly what has been done before on the problem, and what is new.


The goal of a paper is to describe novel technical results. There are four types of technical results:

1. An algorithm;
<details>
<summary>2. A system construct: such as hardware design, software system, protocol, etc.; </summary>
        One goal of the paper is to ensure that the next person who designs a system like yours does not make the same mistakes and takes advantage of some of your best solutions. So make sure that the hard problems (and their solutions) are discussed and the non-obvious mistakes(and how to avoid them) are discussed (Craig Partridge)
</details>


<details>
<summary>3.A performance evaluation: obtained through analyses, simulation or measurements;</summary>
</details>

<details>
<summary>4.A theory: consisting of a collection of theorems.</summary>
</details>

A paper should focus on 

- describing the results in sufficient details to establish their validity;
- identifying the novel aspects of the results, i.e., what new knowledge is reported and what makes it non-obvious;
- identifying the significance of the results: what improvements and impact do they suggest.

## Paper Structure
<details>
        
<summary> 手写✍️ </summary>

![6901698647884_ pic_hd](https://github.com/ChenxingWang93/document-style-guide/assets/31954987/0ee34a8b-c40b-4d6a-828a-1d5cb30cec09)
</details>

- Typical outline of a paper is:
   - Abstract, typically not more than 100-150 words;
   - [Introduction](https://www.cs.columbia.edu/~hgs/etc/intro-style.html)(brief!): introduce problem, outline solution; the statement of the problem should include a clear statement why the problem is important (or interesting).

<details>
<summary> 手写✍️ </summary>
        
![6961698647921_ pic_hd](https://github.com/ChenxingWang93/document-style-guide/assets/31954987/5c19532f-b07a-426b-97ff-a4737575591a)
</details>

- Related Work (or before summary).
  - Hint: In the case of a conference, make sure to cite the work of the PC co-chairs and as many other PC members as are remotely plausible, as well as from anything relevant from the previous two proceedings. In the case of a journal or magazine, cite anything relevant from last 2-3 years or so volumes.

- Outline of the rest of the paper: "The remainder of the paper is organized as follows. In Section 2, we introduce ..Section 3 describes ... Finally, we describe future work in Section 5." [Note that Section is capitalized. Also, vary your expression between "section" being the subject of the sentence, as in "Section 2 discusses ..." and "In Section, we discuss ...".]
- Body of paper
  - problem
  - approach, architecture
  - results

<details>
<summary> 手写✍️ </summary>
        
![6951698647917_ pic_hd](https://github.com/ChenxingWang93/document-style-guide/assets/31954987/26c1d373-451a-49a4-b28a-bf94b6925352)
</details>

The body should contain sufficient motivation, with at least one example scenario, preferably two, with illustrating figures, followed by a crisp generic problem statement model, i.e., functionality, particularly emphasizing "new" functionality. The paper may or may not include formalisms. General evaluations of your algorithm or architecture, e.g., material proving that the algorithm is O(log N), go here, not in the evaluation section.


<details>
<summary> 手写✍️ </summary>
        
![6911698647888_ pic_hd](https://github.com/ChenxingWang93/document-style-guide/assets/31954987/772af7c4-fdaa-4ef4-92db-37a7dd1cf10d)
</details>

***Architecture***

of proposed system(s) to achieve this model should be more generic than your own peculiar implementation. Always include at least one figure.

***Realization***

contains actual implementation details when implementing architecture isn't totally straightforward. Mention briefly implementation language, platform, location, dependencies on other packages and minimum resource usage if pertinent.

***Evaluation***

How does it really work in practice? Provide real or simulated performance metrics, end-user studies, mention external technology adoptors, if any, etc.

- Related work, if not covered at the beginning.
- Summary and Future Work
        - often repeats the main result
- Acknowledgements
- Bibliography
- Appendix(to be cut first it forced to):
        - detailed protocol descriptions
        - proofs with more than two lines
        - other low-level but important details

it is recommended that you write the approach and results sections first, which go together. Then problem section, if it is separate from the introduction. Then the conclusions, then the intro. Write the intro last since it glosses the conclusions in one of the last paragraphs. Finally, write the abstract. Last, give your paper a title.

## Title 


## Authors

<details>
<summary> 手写✍️ </summary>
        
![6921698647893_ pic_hd](https://github.com/ChenxingWang93/document-style-guide/assets/31954987/ac65f152-0866-4f93-8c78-661565555596)
</details>

## Abstract
<details>
<summary> 手写✍️ </summary>
        
![6941698647909_ pic_hd](https://github.com/ChenxingWang93/document-style-guide/assets/31954987/91249526-05ea-447e-9aa2-f1839d583753)

</details>
        
## Introduction 

## Body of Paper

## Bibliography

## Acknowledgement

## Reporting Numerical Results and Simulations

## Latex Considerations

## Things to Avoid 

## Guidelines for Experimental Papers

## Other Hints and Notes

## The Conference Review Process

## Other References

## Talks

## Miscellaneous

## Contributors

## Translations

## Reference 参考
[WritingTechnicalArticles](https://www.cs.columbia.edu/~hgs/etc/writing-style.html)
