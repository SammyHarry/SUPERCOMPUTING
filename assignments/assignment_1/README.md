 cd ~/SUPERCOMPUTING #Navigating to the correct spot of my computer had to look up the relational path command
 
mkdir ./assignments #its going to be alot of mkdir (make directory) I am also removing almost all ls commands as I used them heavily to double check where I was and what I was doing

 cd assignments #I have to go into each directory after creating it because I want to do more things inside of it

 mkdir assignment_1

 cd assignment_1 

 touch README.md #I looked up how to create these files and this was the first one that came up, I am not sure if it is the best. Also this repo now has 2 READMEs which I am not sure if that is what was desired

 touch assignment_1_essay.md

 cd ../ #No idea why I did this, and it lead to me having to remove a lot of things later on. I am leaving this in however, to show that it happened

 mkdir data

 cd data 

 mkdir raw    

 mkdir clean

 cd raw 

 touch data.csv

 cd ..

 cd clean 

 touch data_clean.csv

 cd ..

 cd ..

 rm -rf data #Here is where I realized I messed up. I knew rm -rf from my other projects so I quickly started over in the correct place

 cd assignment_1

 mkdir data #I messed up here again, because I didn't make the data directory - however I did remove that mistake from the README as not to make this too long (However I did get good practice). I am also modeling my file structure off of projects I have previously done (with a bit better practices) so many of the differences between the example and this reflect what I know, and how I think I would currently operate. 

 cd data 

 mkdir raw #From the chapter we read they mentioned to keep all the raw data static which is why we have a seperate directory from it, we also have a "clean" data directory that hold the data we will use for our project.  

 cd raw 

 touch data.csv

 cd ..

 mkdir clean

 cd clean

 touch data_clean.csv

 cd ..

 cd ..

 mkdir python #Here is where I plan to store all of my code, since I have only truely worked with python I am assuming such. I will also say as projects become more involved I can imagine making multiple sub directories for cleaning data python, graph making, etc. 

 cd python 

 touch sample_code.py

 cd ..

 mkdir results #Here I hold the statisical findings, I did not know what type of file to make so I made it a txt file as that was familiar. 

 cd results 

 touch results.txt

 cd ..

 mkdir notes #Same idea as above, here I got inspiration from the chapter which said to write down all notes.

 cd notes 

 touch notes_0.txt 

 cd ..

 nano README.md #Finally creating the readme, and after all the mistakes I can confidently say I am better with basic terminal commands. I will also say after writing in nano, I am very grateful for google docs. 
 
###########################

In case you want to run everything line by line, I asked ChatGPT to condense the list without my notes, which I cleaned further to take out the "rm" and small things that didn't add. 

The full list is below

#####################
cd ~/SUPERCOMPUTING
mkdir assignments
cd assignments
mkdir assignment_1
cd assignment_1
touch README.md
touch assignment_1_essay.md
mkdir data
cd data
mkdir raw
mkdir clean
cd raw
touch data.csv
cd ..
cd clean
touch data_clean.csv
cd ..
cd ..
mkdir python
cd python
touch sample_code.py
cd ..
mkdir results
cd results
touch results.txt
cd ..
mkdir notes
cd notes
touch notes_0.txt
cd ..
