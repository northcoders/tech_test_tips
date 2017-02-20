# Technical Test Cheat Sheet

A remote technical test is often the first evidence of your technical ability that an employer will see from you. 

Whilst tech tests often have a fairly open specification to allow for implementations in various languages and with various tools, there are some things that employers will certainly be looking for. Even if your technical test does not specify the following points, you **absolutely must**:


- Use git to track your development process

- Make sure you have a .gitignore file. The one I have included in this repo will work for most JavaScript projects. Just pay attention though if you have node_modules nested in directories within your project for example.

- Do not use `$ git add . -A` instead view your diff `git diff` or status `git status` adding files and directories one by one with care. This way you will not end up committing anything you do not want to. You should also view your `git diff` carefully to make sure you do not leave in any lines of code you do not want in the history, comments & console.log lines for example.
On this point you may find the following commands handy:
    - `git reset FILE_OR_DIR_NAME` un-stage a file or directory you have added to the staging area.
    - `git checkout FILE_OR_DIR_NAME` remove any changes to a file or directory git is already tracking
    - `git clean -f` remove any files or directories you have added but do not want to stage or commit
    
- Provide a README which tells the end user how to run your project (see below)

- Always Test your code

- Make sure all your dependencies are saved in your `package.json` file

- Do not rely on any global package installs that you have on your own computer. Install them locally in the project.

- Structure files in a sensible way

- Always Lint your code

- Complete the test in the time frame requested and submit in the format required



### Other things to consider:

- **Read the instructions carefully.** Because tech tests leave implementation instructions vague, it can be hard to figure out what is being asked. Don't start coding until you fully understand the problem. 

- **Assume no prior knowledge** In your README.md, don't assume anything. Don't even assume they have Node installed - tell them what version they need and give them the command they need to use to install dependencies and run the project. Don't patronise by over-explaining, just tell them the instructions they need to run.

- **Research the problem domain** You may be asked to work in a domain (field of knowledge) that you aren't familiar with. Don't guess things - research the area and its terminology if you need to. It will improve your solution and show you are serious about what the company does.

- **Use technology choices you are confident with.** If you can avoid it, don't learn something new just for the sake of it. Stick to what you know you can do well.

- **Show off what you can do.** Sometimes tech tests can look deceptively simple but remember that this is a chance to show off what you've learned and show you can do it well.

- **Be prepared to talk about your work** You may be asked to explain your technology choices in a covering note, but if not you will certainly be expected to talk about them, along with how you solved the problem, at an in-person interview. Make sensible choices and make sure you understand your code completely.

- **Use best practices** Specifically, pay attention to stylistic factors that a linter will not pick up, such as consistency with ES6 and naming conventions. 

- **Practice first** Do a spike first and the re-do it, with a proper commit history. It will be far better the second time round.