## How to update your author entry:  
First, go to [the authors frontmater page](https://github.com/OpenDataSTL/opendatastl.github.io/blob/master/_data/authors.yml).
If your name is not entered yet, copy paste the entry template at the bottom.  
```
- display_name:    
  name:  
  gravatar:  
  email:  
  website:  
  twitter:  
  github:  
  topics: []  
  bio:  
  speaker: No  
```
  
When you add information to your entry template, put two spaces at the end of the line.  
If you are going to make yourself available as a speaker, change ```speaker: No``` to ```speaker: Yes```.  
  
```topics``` has its own format. If you have no topics to list, leave the line as ```topics: []```. When you change it, you are going to turn this line into a list of topics, like this:  
```
topics:  
    - topic: Topic 1
    - topic: Topic 2
```
There are two spaces after ```topics:  ```, then each line under that is four spaces, a dash, one space, the keyword ```topic```, a colon and another space, and then the text for your topic. Finish with two more spaces.
```(space)(space)(space)(space)-(space)topic:(space)<your topic text>```
  
When you are done and ready to commit changes, instead of choosing the default to "Commit directly to the ```master``` branch, switch to "Create a **new branch** for this commit and start a pull request." Give your commit a descriptive title (like "Updating author info for Brett"), a description if you want, and give a descriptive branch name too. Branch names are all lower cases with dashes for spaces, e.g. ```brett-author-info-update```.  
The green button should say "Propose file change" instead of "Commit changes". 
