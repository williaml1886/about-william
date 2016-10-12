# about-me
williaml1886:~/workspace $ cd ~/workspace
williaml1886:~/workspace $ rm -rf .git
williaml1886:~/workspace $ mkdir about-me
mkdir: cannot create directory ‘about-me’: File exists
williaml1886:~/workspace $ cd about-me
williaml1886:~/workspace/about-me (master) $ rm -rf .git
williaml1886:~/workspace/about-me $ git init
Initialized empty Git repository in /home/ubuntu/workspace/about-me/.git/
williaml1886:~/workspace/about-me (master) $ touch README.md
williaml1886:~/workspace/about-me (master) $ rm -rf .git
williaml1886:~/workspace/about-me $ git commit -m "create readme"
fatal: Not a git repository (or any of the parent directories): .git
williaml1886:~/workspace/about-me $ git remote add origin git@github.com:williaml1886/about-me.git
fatal: Not a git repository (or any of the parent directories): .git
williaml1886:~/workspace/about-me $ git push -u origin master
fatal: Not a git repository (or any of the parent directories): .git
williaml1886:~/workspace/about-me $ git init
Initialized empty Git repository in /home/ubuntu/workspace/about-me/.git/
williaml1886:~/workspace/about-me (master) $ rm -rf .gif
williaml1886:~/workspace/about-me (master) $ rm -rf .git
williaml1886:~/workspace/about-me $ git push
fatal: Not a git repository (or any of the parent directories): .git
williaml1886:~/workspace/about-me $ git status
fatal: Not a git repository (or any of the parent directories): .git
williaml1886:~/workspace/about-me $ git remote add origin git@github.com:williaml1886/about-me.git
fatal: Not a git repository (or any of the parent directories): .git
williaml1886:~/workspace/about-me $ git push -u origin master
fatal: Not a git repository (or any of the parent directories): .git
williaml1886:~/workspace/about-me $ ls
README.md/  about-me
williaml1886:~/workspace/about-me $ git init
Initialized empty Git repository in /home/ubuntu/workspace/about-me/.git/
williaml1886:~/workspace/about-me (master) $ git remote add origin
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=<push|fetch>]
                          set up remote as a mirror to push to or fetch from
