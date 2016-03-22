Module: Research in Security (research)
===============================================================================

This is a course module on reviewing and applying security research.  Its aim 
is to introduce the students to the research in the field: how it is presented, 
what is good research, and how to apply it in development of new technologies.

The module is part of the [Open Security Education][OpenSecEd] project and the 
maintainer is [Daniel Bosk][dbosk].  The latest release can be found under 
[releases][Releases].  You can safely link directly to the PDFs found there.

[OpenSecEd]: https://github.com/OpenSecEd/
[dbosk]: https://github.com/dbosk/
[Releases]: https://github.com/OpenSecEd/research/releases


File Structure and Building
-------------------------------------------------------------------------------

*To build* the PDFs, after cloning the repository you must clone its required 
submodules:

```shell
$ git submodule update --recursive --init
```
Then you can go into the directory of the desired document and run `make`.
The source files are structured as follows:

- `review` contains a seminar assignment in which the students review and 
  present papers for each other.
- `prestudy` contains a project assignment where the students should dig deeper 
  into a problem related to the security field.  This could be used as 
  a pre-study for a thesis topic.

In each directory the files are structured as follows:

- `<name>.tex` contains the main instruction.
- `aims.tex` is an itemized list of the intended learning outcomes, as such it 
  can be included in another document summarizing the list of intended learning 
  outcomes.
- `abstract.tex` covers the required reading instructions, thus you can include 
  these in a study guide containing all reading instructions for the course.
- `<name>.bib` contains the bibliography entries, thus this file can be 
  included along with the reading instructions.

*To contribute*, please [fork the repository][ForkARepo], make your changes, 
commit them and then create a [pull request][PullRequest] in the original 
repository.

[ForkARepo]: https://help.github.com/articles/fork-a-repo/
[PullRequest]: https://help.github.com/articles/using-pull-requests/
