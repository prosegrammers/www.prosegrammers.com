# Plan for Prosegrammers

## Plan for Content

### Create Slides for Week Fifteen in `slides/weekfifteen/index.qmd`

- [ ] Review the content in the `GEMINI.md` file (or the `AGENTS.md` file) that
explains the theme of the course on document engineering.
- [ ] Review the content in the `index.qmd` file in the root of the repository
that explains the idea of a "Prosegrammer" and the concept of document
engineering. All the slides that you create have to specifically connect to the
theme of prosegramming and document engineering.
- [ ] Review the content in the `index.qmd` file in the `syllabus` directory of
the repository that explains rules and regulations for this course on document
engineering. Note that these are the rules that students follow and not
specifically the rules and regulations that you follow as a coding agent.
- [ ] Please remember that I am currently working on the slides in
`slides/weekfifteen/index.qmd` that introduce how to implement your own
functions for natural language processing.


I don't want any of the slides to
use functions from packages like `nltk` or `spacy` or `gensim`. I want to only
introduce basic concepts of natural language processing by explaining them with
bullet points and examples and then adding source code examples that students
can try out and run in the slides with `{pyodide}` blocks.
- [ ] Here is what I want you to add to the slides:
    - Tokenization
- Again, none of the slides should use functions that come from any external package that is available on PyPI or through any external site. All the content must be from the standard Python library. It has to be simple and implemented from scratch!
- [X] You can look at the other slide decks that I have already prepared:
  - `slides/weekone/index.qmd`
  - `slides/weektwo/index.qmd`
  - `slides/weekthree/index.qmd`
  - `slides/weekfour/index.qmd`
  - `slides/weekfive/index.qmd`
  - `slides/weeksix/index.qmd`
  - `slides/weekeight/index.qmd`
  - `slides/weeknine/index.qmd`
  - `slides/weekten/index.qmd` ... and see how I am currently using Markdown and
  Quarto in my slides! There are also slides in other directories and you can
  preview them as well.
- [X] Please do not use Markdown or Quarto formats that I am not currently using
in my slides to make sure that the content has a consistent format.
- [X] If you check the `index.qmd` file in this GitHub repository, you can see a
simple example of word frequency analysis. Please use simple examples like this
one to illustrate how to perform retrieval augmented generation (RAG).
- [X] Make sure that all the content is accessible to beginners who do not have
extensive experience with programming or the documentation of a software tool.
- [X] Make sure that all the content has concrete examples that make points
clear to beginners. Provide simple summaries of the concrete code examples.
- [X] Always include "signposting" slides that clearly state what you are going
to explain in the next block of slides about a specific topic. These signposting
slides are at the `#` level in the Markdown file.
- [X] Always include a conclusion slide that has the title `Key takeaways for
prosegrammers` and then summarizes the key points that students learned.
- [X] Keep the total number of slides to a count less than the prior slide decks
that I have created. For instance, this topic is less complicated than the
material that I produced for weeknine and thus the slide count should be less.
