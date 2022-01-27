## What is Git?

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.<br>
Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.<br>

### Branching and Merging

The Git feature that really makes it stand apart from nearly every other SCM out there is its branching model.<br>

Git allows and encourages you to have multiple local branches that can be entirely independent of each other. The creation, merging, and deletion of those lines of development takes seconds.<br>

<b>This means that you can do things like:</b><br>

<b>Frictionless Context Switching.</b> Create a branch to try out an idea, commit a few times, switch back to where you branched from, apply a patch, switch back to where you are experimenting, and merge it in.<br>
<b>Role-Based Codelines.</b> Have a branch that always contains only what goes to production, another that you merge work into for testing, and several smaller ones for day to day work.<br>
<b>Feature Based Workflow.</b> Create new branches for each new feature you're working on so you can seamlessly switch back and forth between them, then delete each branch when that feature gets merged into your main line.<br>
<b>Disposable Experimentation.</b> Create a branch to experiment in, realize it's not going to work, and just delete it - abandoning the work—with nobody else ever seeing it (even if you've pushed other branches in the meantime).<br>

### Distributed

One of the nicest features of any Distributed SCM, Git included, is that it's distributed. This means that instead of doing a "checkout" of the current tip of the source code, you do a "clone" of the entire repository.

### Multiple Backups

This means that even if you're using a centralized workflow, every user essentially has a full backup of the main server. Each of these copies could be pushed up to replace the main server in the event of a crash or corruption. In effect, there is no single point of failure with Git unless there is only a single copy of the repository.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
