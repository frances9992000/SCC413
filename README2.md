# SCC413 final project 
This project is a NLP related project, required by SCC413 module assessment

## Required

Python 3.x
Need to have Keras and sklearn two main packages


## Cautions (personalised folder and resource) 

I have added this H drive folder to the Python system and you may have problem to run it in your own computer. 
'''
import sys
sys.path.append('H:\SCC413_Applied Data Mining\SCC413 Final project\Shaling_project\Project_code')
'''

The following piece should be run in different computer. 
My source address is 'H:\SCC413_Applied Data Mining\SCC413 Final project\Shaling_project\Project_code'
All data is in a sub-folder under the source line: 'H:\SCC413_Applied Data Mining\SCC413 Final project\Shaling_project\Project_code\Project_data'
'''
def read_file():
    cwd='./Project_data/'
  
    read_fileNames(sources, cwd,'neg_fake') #label=1
    read_fileNames(sources, cwd,'neg_true') #label=0
    read_fileNames(sources, cwd,'pos_fake') #label=1
    read_fileNames(sources, cwd,'pos_true') #label=0

    readFilesFromSources(text,sources)
'''

### Acknowledgement
- SCC413 lecture notes and lab codes
- A few github projects for inspiration and code support
 
