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
`slides/weekfifteen/index.qmd` that introduce how to perform retrieval augmented
generation (RAG). I do not want any of the slides to use functions from packages
like `nltk` or `spacy` or `gensim` or `SentenceTransformers`. I want to only
introduce basic concepts of retrieval augmented generation by explaining them
with bullet points and examples and then adding source code examples that
students can try out and run in the slides with `{pyodide}` blocks.
- [ ] If there are specific tools that would normally be used for a specific
step in the RAG pipeline, then please reference them in a bulleted list
and explain what they do. However, you cannot make the slides `import` those
packages in Python or install a tool, like a vector database, on a computer.
- [ ] The high-level workflow that you should start with is as follows:
    - Document ingestion
    - Data cleaning and preprocessing
    - Converting text to chunks
    - Create and store vector embeddings
    - Retrieve relevant documents based on user queries
    - Make it clear how the documents are relevant with simple examples
    - Combine retrieved documents with user queries
    - Generate responses using a language model
- Please note that you cannot use any external packages that are not part of
the Python standard library to complete any of these steps.
- Again, none of the slides should use functions that come from any external
package that is available on PyPI or through any external site. All the content
must be from the standard Python library. It has to be simple and implemented
from scratch!
- [ ] You can look at the other slide decks that I have already prepared:
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
- [ ] You should definitely review the slides from `weekthirteen` called
"Natural Language Processing for Document Engineering" as this will illustrate
how I taught the students about some of the NLP concepts you can build on in
this slide deck. Again, notice that none of that content uses an external
package, it is all "simple" and also "built from scratch".
- [ ] Please do not use Markdown or Quarto formats that I am not currently using
in my slides to make sure that the content has a consistent format.
- [ ] If you check the `index.qmd` file in this GitHub repository, you can see a
simple example of word frequency analysis. Please use simple examples like this
one to illustrate how to perform retrieval augmented generation (RAG).
- [ ] Make sure that all the content is accessible to beginners who do not have
extensive experience with programming or the documentation of a software tool.
- [ ] Make sure that all the content has concrete examples that make points
clear to beginners. Provide simple summaries of the concrete code examples.
- [ ] Always include "signposting" slides that clearly state what you are going
to explain in the next block of slides about a specific topic. These signposting
slides are at the `#` level in the Markdown file.
- [ ] Always include a conclusion slide that has the title `Key takeaways for
prosegrammers` and then summarizes the key points that students learned.
- [ ] Keep the total number of slides to a count less than the prior slide decks
that I have created. For instance, this topic is less complicated than the
material that I produced for weeknine and thus the slide count should be less.
