- Git Foundation
A bare repo is usually a directory with a name that ends in .git—for example, project.git
Git uses hashes that are 160 bits long
A Git repo contains four types of objects, each uniquely identified by an SHA-1 hash.
	- blob Objects : Ordinary File
	- tree object : directory
	- commit object : version of the working tree
	- tag is a name attached to a commit
The most recent commit on a branch is called the head
The head of the current branch is named HEAD
When you create a repo, Git creates a remote named origin that is the default remote for push and pull operations
