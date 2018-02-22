Transfer repo to group Github account  
apply for a host name  
home page - figures from paper  
people photos  
research descriptions and figures  

## Section A. Preparations before you can edit files  
The files to make the group webpage are hosted on Github. Before you can make any modifications, you have to complete the three things.  
1. Have a Github account  
2. Ask Prof. Schneider (or anyone else who has access to the group Github account) to add you to the contributor to the webpage repository.    
3. Then git clone the web folder to your own laptop.  
'''git clone link   '''
## Section B. General Procedures to edit files  
 After you have a Github account and have cloned the web folder to your local folder, you can start to make modifications to update the web page. Each update consists of 3 steps.  
1. Git pull to download the latest version of files    
'''git pull  '''
2. Edit/add/delete specific files   
When you have the latest version of files, you can make any modifications on the files in your local   folder. The details to make modifications for each page are listed in section C&D.  
3. Git add, commit and push the files to the remote    
After you make modifications, you have to  
'''git add .  
git commit -m ‘description of the update’   
git push   '''
4. Preview the webpage on your local host    
If you want to preview the webpage on your local host before you push the files to Github, you can follow the instructions in the following link:  
https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/  
## Section C. Three types of files to edit  
1. YML files    
There are two photo carousals in the group web, the home page carousal and group photo carousal. The YML files are used to control the order and format for each photo. They can be edited as text files.  
2. Markdown files    
The markdown files are used to edit the content(paragraphs and photos) on each page. Markdown files have plain text formatting syntax and can be easily edited.  
3. Photos in folder    
You may need to add photos in several folders.  
## Section D. Files to edit for each page  
1. Home page carousal    
The home page carousal has the highlighted figures from papers published by our group. To update the figures in carousal, you need 2 steps.  
1) Add new figure in the folder: group_data/home_photoes/  
2) Edit text in the file: _data/home_photo.yml  
For each photo, the text includes five pieces of information:  
- index: the order of the photos that you want to show  
- url: the directory of the photo, as ‘/group_data/home_photos/{Figure name in the folder}’  
- title: the paper title  
- author: the author of the paper  
- caption: the caption you would like to show on the figure  
2. Group-Bill Schneider page  
Edit content in this markdown file:pages/group/bill_schneider.md.  
Change photo in the folder: group_data/people_photos  
3. Group-People page  
Edit content in this markdown file: pages/group/people.md.  
Change photo  
4. Group-Group photo page  
Change photos in the folder: group_data/group_photos  
Edit text in the file: _data/home_photo.yml  
5. Research page  
Edit content in this markdown file: pages/research.md  
6. Publications page  
Edit content in this markdown file: pages/publications.md  
7. Resources page  
Edit content in this markdown file: pages/resources.md  
8. Courses page  
Edit content in this markdown file: pages/courses.md  
