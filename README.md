git
===

Provides handy git aliases and functions.

Many thanks to [Sorin Ionescu](https://github.com/sorin-ionescu) for the
excellent original aliases.

Aliases
-------

### Git

  * `G` is short for `git`.

### Branch

  * `Gb` lists, creates, renames, and deletes branches.
  * `Gbc` creates a new branch.
  * `Gbl` lists branches and their commits.
  * `GbL` lists local and remote branches and their commits.
  * `Gbm` renames a branch.
  * `GbM` renames a branch even if the new branch name already exists.
  * `Gbs` lists branches and their commits with ancestry graphs.
  * `GbS` lists local and remote branches and their commits with ancestry
    graphs.
  * `Gbx` deletes a branch.
  * `GbX` deletes a branch irrespective of its merged status.

### Commit

  * `Gc` records changes to the repository.
  * `Gca` commits all modified and deleted files.
  * `Gcm` commits with the given message.
  * `Gco` checks out a branch or paths to the working tree.
  * `GcO` checks out hunks from the index or the tree interactively.
  * `Gcf` amends the tip of the current branch reusing the same log message as
    *HEAD*.
  * `GcF` amends the tip of the current branch.
  * `Gcp` applies changes introduced by existing commits.
  * `GcP` applies changes introduced by existing commits without committing.
  * `Gcr` reverts existing commits by reverting patches and recording new
     commits.
  * `GcR` removes the *HEAD* commit.
  * `Gcs` shows one or more objects (blobs, trees, tags and commits).
  * `GcS` commits with GPG signature.
  * `Gcv` verifies the GPG signature of commits.

### Conflict

  * `GCl` lists unmerged files.
  * `GCa` adds unmerged file contents to the index.
  * `GCe` executes merge-tool on all unmerged files.
  * `GCo` checks out our changes for unmerged paths.
  * `GCO` checks out our changes for all unmerged paths.
  * `GCt` checks out their changes for unmerged paths.
  * `GCT` checks out their changes for all unmerged paths.

### Data

  * `Gd` displays information about files in the index and the work tree.
  * `Gdc` lists cached files.
  * `Gdx` lists deleted files.
  * `Gdm` lists modified files.
  * `Gdu` lists untracked files.
  * `Gdk` lists killed files.
  * `Gdi` lists ignored files.

### Fetch

  * `Gf` downloads objects and references from another repository.
  * `Gfc` clones a repository into a new directory.
  * `Gfm` fetches from and merges with another repository or local branch.
  * `Gfr` fetches from and rebases on top of another repository or local branch.
  * `Gfu` removes unexisting remote-tracking references, fetches all remotes and
    merges.

### Grep

  * `Gg` displays lines matching a pattern.
  * `Ggi` displays lines matching a pattern ignoring case.
  * `Ggl` lists files matching a pattern.
  * `GgL` lists files that are not matching a pattern.
  * `Ggv` displays lines not matching a pattern.
  * `Ggw` displays lines matching a pattern at word boundary.

### Index

  * `Gia` adds file contents to the index.
  * `GiA` adds file contents to the index interactively.
  * `Giu` adds file contents to the index (updates only known files).
  * `Gid` displays changes between the index and a named commit (diff).
  * `GiD` displays changes between the index and a named commit (word diff).
  * `Gir` resets the current *HEAD* to the specified state.
  * `GiR` resets the current index interactively.
  * `Gix` removes files/directories from the index (recursively).
  * `GiX` removes files/directories from the index (recursively and forced).

### Log

  * `Gl` displays the log.
  * `Gls` displays the stats log.
  * `Gld` displays the diff log.
  * `Glo` displays the one line log.
  * `GlO` displays the one line log with authors and dates.
  * `Glg` displays the graph log.
  * `GlG` displays the graph log with authors and dates.
  * `Glv` displays the log verifying the GPG signature of commits.
  * `Glc` displays the commit count for each contributor in descending order.
  * `Glr` manages reflog information.

### Merge

  * `Gm` joins two or more development histories together.
  * `Gma` aborts the conflict resolution, and reconstructs the pre-merge state.
  * `GmC` performs the merge but does not commit.
  * `GmF` performs the merge generating a commit even if the merge resolved as a
    fast-forward.
  * `GmS` commits with GPG signature.
  * `Gmv` verifies the GPG signature of the tip commit of the side branch being
    merged.
  * `Gmt` runs the merge conflict resolution tools to resolve conflicts.

### Push

  * `Gp` updates remote refs along with associated objects.
  * `Gpf` forces a push safely (with "lease").
  * `GpF` forces a push.
  * `Gpa` pushes all branches.
  * `GpA` pushes all branches and tags.
  * `Gpt` pushes all tags.
  * `Gpc` pushes the current branch and adds *origin* as an upstream reference
    for it.
  * `Gpp` pulls and pushes the current branch from *origin* to *origin*.

### Rebase

  * `Gr` forward-ports local commits to the updated upstream head.
  * `Gra` aborts the rebase.
  * `Grc` continues the rebase after merge conflicts are resolved.
  * `Gri` makes a list of commits to be rebased and opens the editor.
  * `Grs` skips the current patch.

### Remote

  * `GR` manages tracked repositories.
  * `GRl` lists remote names and their URLs.
  * `GRa` adds a new remote.
  * `GRx` removes a remote.
  * `GRm` renames a remote.
  * `GRu` fetches remotes updates.
  * `GRp` prunes all stale remote tracking branches.
  * `GRs` shows information about a given remote.

### Stash

  * `Gs` stashes the changes of the dirty working directory.
  * `Gsa` applies the changes recorded in a stash to the working directory.
  * `Gsx` drops a stashed state.
  * `GsX` drops all the stashed states.
  * `Gsl` lists stashed states.
  * `Gsd` displays changes between the stash and its original parent.
  * `Gsp` removes and applies a single stashed state from the stash list.
  * `Gsr` recovers a given stashed state.
  * `Gss` stashes the working directory changes, including untracked files.
  * `GsS` stashes the working directory changes interactively.
  * `Gsw` stashes the working directory changes retaining the index.
  * `Gsu` unapplies (reverts) applied changes.

### Submodule

  * `GS` initializes, updates, or inspects submodules.
  * `GSa` adds given a repository as a submodule.
  * `GSf` evaluates a shell command in each of checked out submodules.
  * `GSi` initializes submodules.
  * `GSI` initializes and clones submodules recursively.
  * `GSl` lists the commits of all submodules.
  * `GSm` moves a submodule.
  * `GSs` synchronizes submodules' remote URL to the value specified in
    `.gitmodules`.
  * `GSu` fetches and merges the latest changes for all submodules.
  * `GSx` removes a submodule.

### Tag

  * `Gt` creates, lists, deletes or verifies a tag object signed with GPG.
  * `Gts` creates a GPG-signed tag.
  * `Gtv` verifies the GPG signature of tags.
  * `Gtx` deletes tags with given names.

### Working tree

  * `Gws` displays working-tree status in the short format.
  * `GwS` displays working-tree status.
  * `Gwd` displays changes between the working tree and the index (diff).
  * `GwD` displays changes between the working tree and the index (word diff).
  * `Gwr` resets the current *HEAD* to the specified state, does not touch the
    index nor the working tree.
  * `GwR` resets the current *HEAD*, index and working tree to the specified
    state.
  * `Gwc` cleans untracked files from the working tree (dry-run).
  * `GwC` cleans untracked files from the working tree.
  * `Gwx` removes files from the working tree and from the index recursively.
  * `GwX` removes files from the working tree and from the index recursively and
    forcefully.

### Misc

  * `G..` changes the current directory to the top level of the working tree.

Settings
--------

By default, all aliases are defined with an upper case `G` prefix, as you can
see above. You can use the following zstyle if you wish to customize the prefix
used to generate all aliases:

    zstyle ':zim:git' aliases-prefix 'g'

Be careful if changing the prefix to lower case `g`, as the generated aliases
can shadow [many](https://github.com/zimfw/git/issues/2) commands, like `gpt`
for the GUID partition table maintenance utility.

Functions
---------

  * `git-branch-current` displays the current branch.
  * `git-branch-delete-interactive` asks for confirmation to also delete the
    upstream remote branch(es).
  * `git-dir` displays the path to the Git directory.
  * `git-ignore-add` adds any arguments to the .gitignore in the project root.
  * `git-root` displays the path to the working tree root.
  * `git-stash-clear-interactive` asks for confirmation before clearing the stash.
  * `git-stash-recover` recovers given dropped stashed states.
  * `git-submodule-move` moves a submodule.
  * `git-submodule-remove` removes a submodule.
