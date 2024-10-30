# Self-host your LLM


1. Go to the repository - [https://github.com/redhat-et/whisper-self-hosted-llm](https://github.com/redhat-et/whisper-self-hosted-llm)
2. Make your fork of the above given repository.
<img width="1507" alt="Screenshot 2024-04-18 at 2 06 54 PM" src="https://github.com/DS219/spark-seprep/blob/main/assignments/assignment7/whisper.png">

3. Make a clone of your fork on your machine.
```
git clone git@github.com:<add_your_githb_username_here>/whisper-self-hosted-llm.git
```
4. Follow along the intructions in the readme here - [https://github.com/aakankshaduggal/whisper-self-hosted-llm/tree/main/whisper-model-service#readme](https://github.com/aakankshaduggal/whisper-self-hosted-llm/tree/main/whisper-model-service#readme)
5. The above readme is pretty self-explanatory but if you need a better understanding please consider watching this video [here](https://youtu.be/JD8ZD3pNij0?si=1sHx98h-1_aZPRUi&t=1211)
  

## Submission

Ensure that you are up to date with the upstream Github repo. Do the following before starting your assignment.

```
cd <to your DS219 github repo path>
git checkout main
git fetch upstream
git rebase upstream/main
git checkout -b assignment7 upstream/main
```

Head to the directory **assignments/assignment7** and create a directory there with your name in the format **FIRST-LAST**.
The directory should be **assignments/assignment7/[FIRSTNAME-LASTNAME]** so you can add the following here:
 
* Add a terminal screenshot of the server hosted on your machine. (Make sure your username is clearly visible on the screenshot for full credit)
* Add a streamlit UI screenshot with an audio transcription.
* Add notes and challenges your faced along the way and also add any improvements and suggestions to the process.

Once done, create a PR to submit.

## Demo

In the final lecture on December 4th, you demo this to the class with your own audio and streamlit UI.

##### Note:

You don't have to change any code just run all the steps and execute the code just with your own audio. 
