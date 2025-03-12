

https://github.com/eastlondoner/cursor-tools



make spec:
<pre>
Ask Perplexity to research [  ] and describe for us in detail how the [  ] feature should work.
Note:
- minimalism preferable, only do what's asked, not more.
- maintain consistency with existing architecture and patterns.
- always ensure best practices.
- modern and simple ui

Write the output to specs/ [  ] -spec.md

Read the spec and ask Perplexity any clarifying questions that you have.
</pre>


make plan:
<pre>
Ask Gemini to make a plan for implementing the [  ] spec.
Note:
- minimalism preferable, only do what's asked, not more.
- maintain consistency with existing architecture and patterns.
- always ensure best practices.
- modern and simple ui

Write the plan to specs/ [  ] -plan.md

Review Gemini's plan, checking the code base and ask Gemini any clarifying questions. Update the plan so that it's ready to implement.
</pre>

implement
<pre>
Read the [] plan and implement the feature.
Note:
- minimalism preferable, only do what's asked, not more.
- maintain consistency with existing architecture and patterns.
- always ensure best practices.
- modern and simple ui

Follow each phase in sequence.

Ask Gemini to review your work after each phase and when you're done. Make changes if needed.
</pre>

plan + implement + review
<pre>
[]
ask Gemini to help you plan, and when you are finished, ask it to review your work
</pre>