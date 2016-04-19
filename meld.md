###(1) Install meld with brew  
brew install meld  
###(2) Copy PYTHONPATH  
brew info pygtk  
Paste result of (2) in ~/.bashrc or ~/.zshrc  
export PYTHONPATH=/usr/local/lib/python2.7/site-packages:$PYTHONPATH  
###(3) git config --global merge.tool meld  
###(4) python /usr/local/bin/meld  
