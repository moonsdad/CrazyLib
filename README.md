CrazyLib
========

A mad lib interpreter.

Create madlibs by putting them into a text file with the needed input words
designated within &lt;angle brackets&gt;. To have a single input be put in multiple places put an id tag within the brackets as so: &lt;example#1&gt;. What follows the # is expected to be a unique number regardless of what precedes it. So, &lt;this#1&gt; will be replaced with the same word as &lt;that#1&gt;.

Can also use ____(this) format, which will make your madlibs look nice for printing. You may also use combinations of the formats as so:
<ul>
<li>&lt;Noun&gt;</li>
<li>____________&lt;Noun&gt;</li>
<li>(Noun)</li>
<li>____________(Noun)</li>
</ul>

Any quantity of leading underscores is permissible.
