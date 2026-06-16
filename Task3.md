Describe the difference between fetch and pull and show (briefly) how each would be used. AC3.4) 

git fetch only downloads the latest data from the remote repository; it does not modify your local working files.

git pull does two things in one step: it downloads the data (fetch) and then automatically merges it into your current local branch (merge).

@wtc242424 ➜ /workspaces/hello-world2 (main) $ git pull
Updating 3f71a7c..b4ed620
Fast-forward
 main.py | 7 +++++++
 1 file changed, 7 insertions(+)
 create mode 100644 main.pygit