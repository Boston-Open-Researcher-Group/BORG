---
layout: page
title: "JOIN"
logo: "img/home-bg.jpg"
description: "Join the BORG"
header-img: "img/home-bg.jpg"
---

# Join the BORG
<img src="{{ site.baseurl }}/img/borg_talk.gif" style="margin-top:0px; margin-bottom:5px; margin-right:10px; width: 25% !important">   

Join the BORG! It is free, it is awesome! Being a member means you are an open science enthusiast/advocate/super hero, want to join the discussion, and help promote open science practices in your community.

# How to join?
You can join by using GIT/GitHub as described below (New to GIT? see these [learning resources](https://help.github.com/articles/git-and-github-learning-resources/) and this [10 min. GIT tutorial](https://try.github.io/levels/1/challenges/1)). Alternatively you can email the following to `kmoerman [@] mit [dot] edu`:
1. A profile picture
2. The information listed in the below [``template``](#YML_template).
Be sure to shoot that e-mail address a reminder if you do not receive a reply.

# Using GitHub to add yourself
Below is an example of how to add yourself as a member using GitHub. Assuming you have [git installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) do the following:

1. Clone the repository to your systems.    
`git clone https://github.com/Boston-Open-Researcher-Group/BORG.git`   

2. Create a new branch in which you will propose changes.   
`git checkout -b add-me`

3. Add your profile picture.    
Profile pictures are found in the [`.../docs/img/people`](https://github.com/Boston-Open-Researcher-Group/BORG/tree/master/docs/img/people) folder.

4. Add information about yourself to the file [`.../docs/_data/people.yml`](https://github.com/Boston-Open-Researcher-Group/BORG/blob/master/docs/_data/people.yml). You can do this by copying the below and replacing the fields with your information. Please ensure the text is aligned as shown so do not introduce additional (or remove) spaces.   
    **The template for adding information about yourself in the people.yml file <a name="YML_template"></a>**

    ```yml
     - name: Dr. Kevin M Moerman   
       role: Member  
       img: kmm_profile_crop.jpg
       url: https://kevinmoerman.org
       github_username: Kevin-Mattheus-Moerman
       twitter_username: KMMoerman
       orcid_id: 0000-0003-3768-4269
       impactstory_id: u/0000-0003-3768-4269
       linkedin_username: kevin-moerman-98923831
       email_address: kmoerman [at] mit.edu
       interests: Open Source Software, Open Hardware
       type: member
       visible: true
    ```   

5. Stage your proposed changes.  
`git add .`

6. Commit your changes. The `-m` flag stands for message. Please provide a useful commit message, e.g. Added myself to the BORG.   
`git commit -m "Added myself to the BORG"`

7. Push the committed changes to the GitHub repository in the branch you created.   
 `git push origin add-me`

8. Create a [`pull request`](https://help.github.com/articles/creating-a-pull-request/) for your branch
