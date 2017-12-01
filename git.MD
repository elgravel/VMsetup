#git init  
#git remote add origin git@github.com:elgravel/zsi-bio-page.git   
#git remote add upstream git@github.com:ZSI-Bio/zsi-bio-page.git   

#git pull origin  
#git status  
#git add  
#git commit -m "text"  
#git push   


#start a new change  
git checkout -b "coverage_mapq"  
git push --set-upstream origin coverage_mapq  

#sync fork with master  
git fetch upstream  
git checkout master  
git merge upstream/master  


