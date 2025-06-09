# git_epam_demo
demo repository from GIT fundamentals training
 
some content
cd, ls, pwd (current path)
git clone <ssh address from github> //cloning
git status          // for status
git pull            // the latest version of the repository (presumably the last
                    // opened repo gets updated if not specified)
git add <filename>  // adding the new files 
git remote -v       // managing the connections to repositories
git log             // seeing all of the commits in ze repo
git commit -m "message" 
                    // commiting the changes with the specified message
git push            // for pushing the commited changes
git gui&            // opens GUI version of GIT, & is for not terminating the current
                    // gitbash session/window, so you can use both
gitk&               // gitk tool (& same as above), used for viewing the history of the repo
git show -s --pretty=raw 68d8c
                    // showing the contents of the commit that starts with the mentioned first 5
                    // symbols (hexadecimal); may need to provide more symbols if theres A LOT of commits
git ls-tree fa622   // showing the contents of the tree starting with the mentioned first 5 symbols (hex) 
git show aa0177     // contents of the blob with the mentioned first 5 symbols (hex) 
