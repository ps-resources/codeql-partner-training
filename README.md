# CodeQL Partner Training Documents & Assets

This repository contains open source materials, documents, and assets for delivering trainings
on how to use CodeQL.

### Goal of this repository

The goal of this repository is to provide all of the resources that an individual needs, when
receiving supplemental training from an experienced CodeQL instructor, to leave them prepared to
train others on the basics of CodeQL query writing for custom security or code quality queries.

These resources are newly assembled and may be incomplete, require elaboration and/or
supplementation.

_P.S.: Remember to take advantage of the
[table of contents feature](https://github.blog/changelog/2021-04-13-table-of-contents-support-in-markdown-files/)
to quickly find the relevant parts of this README._

This training will prepare you to deliver a CodeQL workshop called, "Finding SQL Injections in Java."

## You will receive the following training:

- **Before** Day 1: Follow [pre-workshop setup instructions][setup_instructions_url].
- Day 1:
  - Join your teaching instructor as they present the [workshop][workshop_directory_url] to you as if you were a student.
  - Begin [supplemental reading and exercises][additional_resources_url], as time allows
- **Before** Day 2: Ensure you have access to the [slideshow][slideshow_url].
- Day 2:
  - [Lead the CodeQL workshop][delivering_the_workshop_url] with your teaching instructor as your audience, receive feedback.
- **After** Day 2:
  - Continue to [expand your CodeQL knowledge][additional_resources_url] as time allows.
  - You are now ready to teach a workshop on CodeQL!

## Delivering the workshop:

To deliver the CodeQL workshop called, "Finding SQL Injections in Java," follow this process:

- **Before** the scheduled workshop:
  - Send your students the [pre-workshop setup instructions][setup_instructions_url].
  - Ensure you have access to the [slideshow][slideshow_url].
- **During** the scheduled workshop:
  - Present the [CodeQL introduction slideshow][slideshow_url].
  - Deliver the [workshop materials][workshop_directory_url] in this repository.

## Additional resources:

To be a great CodeQL instructor, you'll need to know more than the bare minimum, and be prepared to answer a range of student questions. Take a look through these resources as time allows to expand your knowledge and expertise.

- Learn more about what queries exist for CodeQL:
  - First place to look is [CodeQL help documentation](https://codeql.github.com/codeql-query-help/).
  - Or see the [CodeQL open source repository](https://github.com/github/codeql)
  - Each build [produces a CSV of all available rules](https://github.com/github/codeql/actions/runs/11015676246) (see "Artifacts" section of a [recent build-csv workflow run](https://github.com/github/codeql/actions/workflows/query-list.yml).)
- Learn about CodeQL query packs:
  - [Creating and working with CodeQL query packs](https://docs.github.com/en/code-security/codeql-cli/using-the-advanced-functionality-of-the-codeql-cli/creating-and-working-with-codeql-packs)
  - [How to configure and utilize query suites or packs in Code Scanning](https://docs.github.com/en/code-security/code-scanning/creating-an-advanced-setup-for-code-scanning/customizing-your-advanced-setup-for-code-scanning#running-additional-queries)
- [CodeQL CLI abilities help manual](https://docs.github.com/en/code-security/codeql-cli/codeql-cli-manual/)
- [QL language reference](https://codeql.github.com/docs/ql-language-reference/)
- [Java AST reference](https://codeql.github.com/docs/codeql-language-guides/abstract-syntax-tree-classes-for-working-with-java-programs/)
- [How to use Multi-Repo Variant Analysis](https://docs.github.com/en/code-security/codeql-for-vs-code/getting-started-with-codeql-for-vs-code/running-codeql-queries-at-scale-with-multi-repository-variant-analysis)

[delivering_the_workshop_url]: /#delivering-the-workshop
[workshop_directory_url]: workshop-materials/
[setup_instructions_url]: preparation-materials/setup-instructions.md
[slideshow_url]: https://docs.google.com/presentation/d/1oaALxLotnGYNeKqKFhBW8pfUWgKdJZRHV6IDcB-nfe8/edit?usp=sharing
[additional_resources_url]: /#additional-resources
