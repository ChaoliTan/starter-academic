# GitHub个人主页更新步骤

1. If not set up **baseUrl** as **https://ChaoliTan.github.io/** in **/websites/starter-academic/config/_default/config.toml**, then should do this step first.
2. Here we already set up, so skip the step.



1. Open iTerm, change directory to __/websites/starter-academic__
2. Type __hugo server__
3. Open __Chrome__, type __localhost:1313__
4. Debug your host page.
5. After finishing debug, backup whole __starter-academic__ files to Github;
   * git add .
   * git commit -m "Update person host page"
   * git push -u origin master
6. Also, commit __public__ files to personal host page.
   * hugo // Would create **static html website** to **public** file from **source code**
   * cd public 
   * git add .
   * git commit -m "Update website"
   * git push origin master // Might need your Github account and password.





**Note**

Some files under **/content/home** have been deactived, if you like, you could active it.



Ref:

https://andreaczhang.rbind.io/post/my-1st-blogpost/