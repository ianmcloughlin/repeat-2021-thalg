# Autumn Project 2021: Theory of Algorithms

**Due: last commit on or before 20<sup>th</sup> August 2021**


These are the instructions for the Autumn project in 2021.
This project will be worth 100% of your marks for this module, unless otherwise agreed in advance with the lecturer.
Your whole submission should be in the form of a single GitHub repository.
The commit history of the repository should reflect the effort you put into your submission.
Your last pushed commit to your repository before the deadline will form your submission.
You should immediately create this repository and submit its URL using the following form.


[Click here to submit your GitHub repository URL](https://forms.office.com/r/whWTJsDuz7)



You should make regular, appropriate commits to your repository and push these to GitHub.
If you set your repository to private, make sure to add `ianmcloughlin` as a collaborator.
Please also read the **[Using git for assessments](https://github.com/ianmcloughlin/using-git-for-assessments/raw/master/using-git-for-assessments.pdf)** document which applies to this project.
As always, you must also follow [the code of student conduct and the policy on plagiarism](https://www.gmit.ie/general/quality-assurance-framework).


## What to do

There are two parts to this project, as below.

#### Part 1

Write a program in C that outputs the SHA384 value of an input file, as detailed in the [Secure Hash Standard](https://www.nist.gov/publications/secure-hash-standard).
The program should work as follows:

```bash
$ sha384sum input.txt
6727a3f2b4e30b1ed2ed73dbd983fe428b2b11e7515685f577c409c5c35a3a7fc27ff648ba2e0e8b1a3f31682f02a0bb  input.txt
```

The following are the requirements of the program.

1. The input file should be taken as a command line argument, without any flags or other arguments being necessary.
2. Your program should compile upon `make` being called in root folder of your repository.
3. Your program should accept the `--help` and `-h` flags. When these are specified on the command line, the program should simply output how to use the program.
4. Your program should not depend on any external packages or libraries, other than the C standard library.
5. Your README should detail the use and compilation of your program.

#### Part 2

Answer the following three questions in your README.
Each answer should be roughly 500 words in length.
You should make use of referencing to demonstrate that your answers are backed up by reliable sources.

1. The SHA256 algorithm is often considered to be less secure than the SHA512 algorithm. Explain why.
2. Explain how and why on a modern computer system hash values are used instead of storing plaintext passwords.
3. Explain what a hash collision is.


#### Enhancements

To enhance your submission, and potentially enhance your mark, you might consider implementing some or all of the following features.

1. Allow multiple input files to be specified as command line arguments, with your program outputting their hash values in order.
2. Enable your program to take input from `stdin` rather than an input file.
3. Allow the user to use the `--full` flag to output the SHA512 hash as well as the truncated SHA384 hash.


## Marking scheme

The following marking scheme will be used to mark your submission out of 100%.
The examiners' overall impression of your submission may influence individual marks.
It is important that your submission provides direct evidence of each of the items listed in each category.
For instance, your commit history should demonstrate and provide evidence that you had a pragmatic attitude to completing the assessment.
Likewise, your submission should have references in it to demonstrate that you considered the literature and the work of others.
  

| Weight | Category | Description |
|---|---|---|
|25% | Research | Evidence of research performed on topic; submission based on referenced literature, particularly academic literature; evidence of understanding of the documentation for any software or libraries used. |
|25% | Development | Environment can be set up as described; code works without tweaking and as described; code is efficient, clean, and clear; evidence of consideration of standards and conventions appropriate to code of this kind. |
|25% | Consistency | Evidence of planning and project management; pragmatic attitude to work as evidenced by well-considered commit history; commits are of a reasonable size; consideration of how commit history will be perceived by others. |
|25% | Documentation | Clear documentation of how to create an environment in which any code will run, how to prepare the code for running, how to run the code including setting any options or flags, and what to expect upon running the code. Concise descriptions of code in comments and README. |