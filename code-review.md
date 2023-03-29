**Code review**

Reviewing even the largest pull requests can be a manageable, straightforward <br>
process if you are able to evaluate changes on a commit-by-commit basis. Each of <br>
the guidelines detailed earlier focuses on making the commits readable; to extract <br>
information from commits, you can use the guidelines as a template.
1. **Determine the narrative** by reading the pull request description and list of <br>
commits. If the commits seem to jump between topics or address, leave a <br>
comment asking for clarification or changes.
2. Lightly scan the message and contents of each commit, starting from the <br>
beginning of the branch. **Verify smallness and atomicity** by checking that the <br>
commit does one thing and that doesn’t include any incomplete implementations. <br>
Recommend splitting or combining commits that are incorrectly scoped.
3. Thoroughly read each commit. **Ensure the commit message sufficiently explains** <br>
**the code** by first checking that implementation matches the intent, then that the <br>
code matches the stated implementation. Use the context and justification to <br>
guide your understanding of the code. If any of the requisite information is missing, <br>
ask for clarification from the author.
4. Finally, with a complete mental model of the commit’s changes and the <br>
overarching narrative, **confirm the code is efficient and bug-free**.
