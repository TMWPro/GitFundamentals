# git remote

When working with git, a **remote** is any git repository that is not ont he macbine you're working on. The counterpart this is **local**, or the machine that is being developed on.

Take GitHub for example. While git is the tecgnology that allows you to create local repositories, GitHub is the site that will host your remote repositories.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states of changes are not shared between the two.

### Adding a remote

A remote can be added with the 'git remote add' command, followed by the name and location of the remote.

The name is a local name, meaning it's your label and does not impact the actual remote whatsoever.

'''
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
'''

### Removing a remote

A remote can be removed with the 'git remove' command, followed by the name of the remote.

'''
git remote remove origin
'''
## Resources

- [Git Remote Documentatio](https://git-scm.com/docs/git-remote)

---

[Back to home](../README.md)