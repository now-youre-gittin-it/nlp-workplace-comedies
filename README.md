# nlp-workplace-comedies

<This read.me is still a work in progress.
 In the meantime, please feel free to check out the individual notebooks; I've explained and analzed what I've done in those!>

 ## Project objective
 The goal was to compare various TV comedy shows, specifically of the workplace comedy genre, to understand the similarities and differences between shows and identify what sets certain shows apart from others. To achieve this using an NLP-based approach, I decided to select 10 shows and use the script of the pilot episode of each show.
 The pilot episode of a show sets the tone for the show; even though the exact elements of each episode will vary, the nature of those elements will generally remain consistent. Hence, analyzing and comparing the pilot episodes can provide a decent understanding of what to expect.
 The shows I selected were: 30 Rock, Brooklyn Nine-Nine, Its Always Sunny in Philadelphia, The Mindy Project, Parks and Recreation, Scrubs, Silicon Valley, Superstore, The Office, and Veep.
 
 ## Questions answered through the work in this project:
 -- Notebook on EDA
 1. How can automate the extraction of data (i.e., show transcripts) from text files to explore and analyze the text?
 Ans. By opening each text file using the read() function and storing the transcript for each show in a dictionary for subsequent analysis.
 2. What kind of basic patterns/elements are common across scripts?
 Ans. A lot of character names seem to be mentioned multiple times. This is because the transcripts contain character names before each dialogue, and a single character (especially lead characters of a show) have multiple dialogues in each episode. 
 3. What are the unique concepts involved in each script?
 Ans. Generating a word cloud gives an introduction to the unique topics discussed in each script.
 
 -- Notebook on sentiment analysis
 
 ## Credit where credit is due
 The work in this project was inspired by (and incorported various elements from) Alice Zhao's session at the PyOhio Conference in 2018. The code for the project she explains in detail is available at https://github.com/adashofdata/nlp-in-python-tutorial, and the recording of her session is available at https://www.youtube.com/watch?v=xvqsFTUsOmc.
### What I did differently
1. The original project dealt with scripts of stand up comedy monologues by multiple comedians. Whereas, I used scripts of major US TV shows of the workplace comedy genre within the last two decades. Thus, the source data differs considerably from the corpus involved in Alice Zhao's work.
 
2. I coded new additional modules on named entity recognition and document similarity,  as well as modified the initial EDA to suit the base corpus of TV scripts.
 <br>
 Note: The scripts analyzed in this project are solely the properties of their respective owners; this is a learning exercise.
 
