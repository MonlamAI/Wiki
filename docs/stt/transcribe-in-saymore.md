Transcribing Speech Data in ‘Sessions’
2.1 Transcriber SOP

	Now that the data collector has finished collecting metadata on the person and recording their speech, it is time to start the transcription process. The transcriber may be the same person, or different, as the data collector; however, they should definitely speak the same dialect as the person who was recorded.

What makes for a good transcriber? A good transcriber is familiar and comfortable with using computers. They will need to process audio data (cut large audio files into smaller segments) and transcribe speech (type out everything spoken on the recording) using specialized software. 

	A good transcriber is also good with language. They are an expert in speaking and writing their own dialect (Amdo, Kham, or Central), and, while they have excellent grammar and spelling, they understand that “writing correctly” is different from “transcribing correctly.” “Transcribing correctly” means recording speech exactly as it is spoken. 

If a speaker makes a grammar mistake, a good transcription contains that grammar mistake. If a speaker doesn’t finish a sentence, a good transcription contains an unfinished sentence. If a speaker speaks poorly, a good transcription is written poorly. What makes a transcription “good” is not how nicely it is written, but how closely it records exactly what the speaker says. 

If a speaker uses a speech word that the transcriber doesn’t know how to spell, and they cannot find it in the dictionary, the transcriber must make note of: 1) the word; 2) the time in minutes and seconds it appears in the sound file; and 3) search for a thread on the “New Words” shared spreadsheet document (in the 360 Cloud). If the word is found, they need to make a comment on the word. If the word isn’t found, they need to create a new entry. 

We’ll go into more details on these points later. With that said, the first job of the transcriber is to process the data: First, the sound file needs to be cut into manageable lengths, and all the gaps of silences and background noises (where there is no language data) need to be cut out. Each of these pre-processed sound files becomes a “session”. After updating your team leader with the session files, the transcriber may begin transcription. 

Here is how to proceed: 
2.1.1 Pre-Processing the Speech Data

	First, due to the specialized software we’ll be using, it is a requirement that the Transcriber works on a Windows machine. Because of the file sizes we’ll be working with, it is also recommended that the Transcriber has a modern machine with at least 8 GBs RAM, a decent CPU (comparable to the i5 or faster), and plenty of hard drive space (500 GBs or higher). Running a legitimate copy of Windows is also highly recommended for both speed and stability. If you are buying a machine specifically for this project, take these specification suggestions into consideration. 

Step 1: Prepare the files for pre-processing 

	You should receive two files from the data collector (via the team leader): 1) a JPEG or PDF of the metadata form and; 2) a set of mp3 files (the speech recording). They should all have the same name, which is also a code for the metadata details of main speaker in the files (their age, sex, dialect, education, and occupation). Upload these files onto your computer. Keep them together in the same Session Folder, which also has the same name. 

Step 2: Cut the audio file into multiple files

First, download and install Audacity: https://sourceforge.net/projects/audacity/files/latest/download  

If your Windows platform language is set to Chinese, choose “English” -- Audacity should still automatically install in Chinese. If not, you may change the language settings in: Preferences -> Interface -> Language: 



Open Audacity. Go to File -> Open... or hit CTRL+O. Navigate to the first mp3 file, and select it. Audacity will prompt you with a warning, prompting you to make a copy of the mp3 before editing it. Don’t change the default setting. Hit “Okay,” and allow Audacity to make a backup copy. This should take a few minutes:  

    

When Audacity has finished copying and loading the file, you should have what’s called a “mp3eform” view of the file. A “mp3eform” is a graphical view of a sound file. Quiet sections of audio are small, while loud bits of audio look big. Your screen should look something like this one; below you can see the file is quiet in the beginning, with a series of sounds happening only in the second half: 



We’ll now be cutting the audio into manageable sizes. Familiarize yourself with how Audacity works. Press the spacebar to play the sound file. Press it again to stop. Try clicking and different sections of the sound. Listen to the conversations on the file. 

Next, chunk the file by “splitting” it. For splitting, we’ll be using the Edit -> Clip Boundaries -> Split function: CTRL+I. Here, I’ve moved my cursor to just before a conversation begins. I’ve clicked my cursor once, and then hit CTRL+I. My sound file now has two sections: 



I’ve double-clicked on the first section to select it (Audacity makes my selected section grey). Since this section is silence, I’ll delete it by hitting my DELETE key. 



Now I’ll split my files into the different natural conversations. Listen to each section carefully. Make sure you don’t delete anything unless it’s silence or background noise: 



Delete sections that are silence and/or background noises; next, we’ll label each conversation according to Setting, Audience, and Communicative Aim. In a natural speech recording, how do you know where to cut? 

SILENCES -- There is a long gap of silence (or background noises) where no speech is taking place. 
Cut the silent portions out; the old file ends where this cut takes place, and the new file begins where the speech picks up
CHANGES -- There is a change in: 
Setting Changes -- make the cut at a convenient pause whenever speech changes settings
Ex. A conversation between two people moves from inside a private home to outside on the street
Audience Changes -- make a cut at a convenient pause whenever speech changes audiences 
Ex. A conversation between two people is interrupted when a third person enters the house and joins in
Communicative Aim Changes -- make a cut at a convenient pause whenever the purpose of the speech changes 
Ex. A conversation about making plans turns into an argument 

	In other words, to properly pre-process speech data, the transcriber needs to have a very good understanding of the session metadata: the categories of the kinds of speech data that have been collected. Just as the data collector has recorded metadata about the kinds of speakers (their age, sex, dialect, education, and occupation), the transcriber is responsible for recording metadata about the kinds of speech that speaker has engaged in. 

	There are 3 main categories to consider: 1) the setting; 2) the audience; and 3) the communicative aim. The setting can be: Institutional, Public, or Private; the audience can be: World/Many, Few, Single, or Self; and the communicative aim might be to: Inform, Influence, Express, Social, or Logistical. Refer to the Guidelines for Session Metadata for more details. Familiarize yourself with all the categories. 

	Again, start by cutting out obvious gaps between speech: long lengths of silence or background noise where no one is speaking should be cut. Then cut conversations into units following the Metadata Guidelines. Use CTRL+I for cutting and the DELETE key for deleting. 

If you accidentally delete a section, don’t worry; just retrieve it using CTRL+Z (undo). If you get to a point where you’ve changed too much, making too many mistakes, don’t worry; that’s why we had Audacity make a copy at the beginning. Exit Audacity, without saving your changes, re-open, and start over. 

Next, we’ll be adding labels to our audio sections. Double-click to select your first conversation. Then hit CTRL+B (EDIT -> Paste Text to New Label). 



A Label Track section should appear below the mp3eform of your sound file. Give the label the full name of the track, and add the metadata info for the setting, audience, and communicative aim; also add a track number (in case you have duplicate sections with the same label). 

For example, if your first conversation was a private conversation (G) with one other person (J) with the object of teaching them something (N) your label would be:

01GJN

Continue with each conversation. Label using the shortcut CTRL+B. Listen and label carefully; if you need to split a conversation in two again (because setting, audience, or aim changes), use the shortcut CTRL+I. 



Continue splitting the file (CTRL+I), labeling conversations (CTRL+B) and deleting silences (DELETE) until you reach the end of the file. Go back over each conversation and make sure you’ve labeled it correctly. If you need to re-join two split sections, use CTRL+J. When you are satisfied everything is correct, go to File -> Expot Multiple (CTRL+SHIFT+L):

 

Choose the folder to export files to (choose the same folder where you are keeping all your files for this session). Make sure “Split files based on” is set to “Labels.” “Name files” should be set to the first option, “Using Label/Track Name.” Select “Export”, and “Okay” for each file. 



Be sure to save your Audacity project. It should bear the same name as your mp3 file. Check your Session folder and make sure the files are there: 



You’ve successfully split the audio. Exit and check your folders. Above on the left is the “Person” folder. It contains your uncut mp3s and the Audacity file, all labeled with the “Person” metadata. In your “Session” folder is a sub-folder of the same name: the “Person”s session. In that, you should have the conversation-level cut mp3s, labeled with the conversation data. 

*Note: When you move on to the next chunk of uncut data (170428A1980MAL06Y2 in our example), take note of where you left off. Here, our last cut filename for the first chunk of data was numbered “05”. You’ll need to pick up where you left off to ensure unique filenames. Start your next label set with “06”! 

Prepare to rename the files! 

Step 3: Double-check your file names 

	You should now have a collection of small, conversation-based mp3 files. They will be labeled with a three-letter code (standing for the setting, audience, and aim) along with a track number. The full-length file is now simply a backup. However, never delete a file. 

Make sure the files use only Roman letters (AaBbCcDd, etc.) and Arabic numerals (1234567890). Do not use Tibetan, Chinese, or any other Unicode characters in the file names (this is to make sure your labels match other workers’ labels, and help software everywhere be able to read and use the files)! 

After this step, don’t start transcription just yet! First, send (or give) the files to the team leader of your dialect; after they have been checked for accuracy and correctness, you will be given the go-ahead to start transcription. 

Follow the Session Pre-Processing Checklist to make sure your work is complete! 

2.1.2 Transcribing 

First, download and install SayMore: 
http://saymore.palaso.org/download/ 

Step 1: Project

	When you open SayMore for the first time, it will prompt you to create a new project. Choose, “Create new, blank project.” SayMore will then ask you to name your new project. Give your project the same name as your person. 





Hit “OK.” SayMore’s default language is English. Now that we’ve opened it, we can change it to Chinese if we want. Go to Project -> Change User Interface Language: 



Select “Chinese,” and hit “OK.” Now fill out the Project Metadata in the About This Project section (since the important metadata is all in the file name, this information is purely optional):

Title: We will create a new project for each person; type in your “Person” code;
Description: leave blank;
Vernacular: click “Change Language;” type “Tibetan (in English characters)” into the search field; find “Tibetan; bo; 3 countries,” “Amdo”, or “Kham” and hit “enter”; or, leave blank
Location: is your location; or, leave blank
Region: Is your 1-letter region code: are you in Amdo (A), Kham (K), or Central Tibet (W)? or, leave blank
Country: China (find and select “China”), or leave blank
Continent: Asia (find and select “Asia”), or leave blank
Contact Person: Your name goes here (or, leave blank if you prefer to remain anonymous)
You may leave all the final fields blank



	You’ve now created a SayMore project that can be used for all the Sessions you will be transcribing. When you open SayMore, it will open this project by default. Now let’s add the Person Metadata before we start transcribing! 

Step 2: Person

Go to “Person” and select a “New Person.” SayMore will create a new Person for you: 

  

Your Person Metadata is already all contained in the file name that the Data Collector assigned. It should be the name of the JPG (photo of the Person Metadata Form) and the name of all of your mp3 files for the session. It will look something like this: 

170428A1980MAL06EY.jpg
170428A1980MAL06EY1.mp3
170428A1980MAL06EY2.mp3
170428A1980MAL06EY3.mp3

In case you don’t remember, these codes stand for: 

170428 -- the date of the Recording (2017 April 28)
A -- the location of the Recording (A = Amdo)
1980 -- the Person’s year of birth 
M -- the Person’s sex (M = Female) 
A -- the Person’s dialect (A = Amdo)
06 -- the Person’s education and level (Chinese school, 6 total years)
	K, 01, 02, 03, 05, 06, 07, 08, 09, 10, 11, 12 ….
E -- the Person’s occupation (E = whitecollar worker)
Y -- the Person’s literacy (Y = literate)

Since we’ve been keeping careful track of this information, we don’t have to worry about losing it or where to find it. Now, we can copy it directly into the Person Metadata for SayMore. 

Full Name: the full code from your file name (####.X.XX.X##.X-XX.####)
Birth Year: number 1 from above (####)
Nickname: leave blank
Code: leave blank 
Gender: drop-down, select “Male (P)” or “Female (M)” 
Primary Language: number 3 from above, the Person’s dialect
Learned in: leave blank 
How to Contact: leave blank 
Other Languages: leave blank 
Education: enter class level, or last level of education completed
Ethnic Group: leave blank 
Primary Occupation: number 5 from above (X)

Finally, click “Add Files” and add the JPG (the photo of the Person Metadata Form) to the Person (“Add Files..” comes with a small green “plus” sign, and can be found on the far right of the screen): 



Congratulations! You have successfully added the Person to your SayMore project. You will be selecting this “Person” for all of the mp3 files you will transcribe in the Sessions you’re about to create... 

Step 3: Session

Now select “New from device...” under “Session.” Navigate to your Session folder, and select each of your conversation files (each split mp3 file that you created during pre-processing). After making sure you’ve check-marked each one, click “OK.” SayMore will now create a Session for each of your conversation files. 



Go ahead and fill out the details for each Session before you begin transcribing. 

ID: This field should be automatically filled in as the full ID of the mp3 file -- it is your full code-set of metadata, like: 170428A1980MAL06LY
Date: The date of recording, the last #### in the code-set 
Title: 
Setting: Your setting, audience, and aim subset: S.A.C
People: Use the drop-down to choose the Person you just created; the Person should match the ID field 
Location: The location of the Recording, the two-letter code at the end of your file name
Genre: Since we are using a different data-structure than SayMore for genre, leave the setting as-is (“Unknown”)
Access:  leave blank
Situation:  leave blank
Description:  leave blank

Now that all our metadata is properly filled out, we can finally begin transcription. In the Session, click on the mp3 file. Below, choose “Start Annotating.” For Segmentation Method, allow SayMore to automatically segment the sound file for you (default), and click “Get Started...” 



SayMore will take some time to segment your audio into small, manageable sizes for you. Once it does, the Transcription window will appear. An Annotation file has just been created for the Session. You’ll see it as a sub-file of your mp3 in the Session window. 

The first thing to do is to set a larger font, since the default size for Tibetan is too small to read. In your Transcription window, select Options -> Fonts... and select a font size. (18 should be large enough, but experiment and see what size works best for you). 



You can now play each section individually by clicking on it. SayMore will automatically loop the recording. First, make sure you are familiar with the supplementary document: Guidelines for Session Transcription. This document gives detailed instructions on how to deal with issues of spelling, disfluent speech, and more. 

Listen carefully several times as you type your Tibetan transcription into the “Transcription” section. Make sure to type exactly what you hear. Do not make corrections or additions or deletions to the text. After you’ve finished typing each section, listen again as you read it. Does your text match the speech word-for-word? 

SayMore allows you to slow down the playback. This is an important tool to help you hear all the details of a speech recording. It’s especially useful if your speaker is speaking too quickly to be understood easily. Experiment with different % of playback speed by selecting them from the drop-down menu: 



Transcribe each line. When you’ve finished with the first Session, continue to the next. SayMore will automatically save your data as you go. If you wish to change how the sound file has been segmented, you may use the “Segment...” (分段) tool: 



When you’ve finished transcribing all of your Sessions, you will have a Project Folder in your SayMore folder (usually, SayMore puts this in your main “Documents” folder in Windows). This folder (labeled “BO-K.R”) is what you will submit to your team leader. It contains subfolders for the People & Sessions associated with the project, along with a SayMore file (extension .sprj). 

Follow the Session Checklist to make sure your work is complete!

Guidelines for Session Transcription
1 Spelling 

Transcribers should use standard spelling whenever possible. Always check the dictionary spelling first. Some words in some dialects might be pronounced differently from this standard spelling. For example, དི་སི (a little bit) is spelled ཏོག་ཙམ even if it isn’t pronounced that way. 
1.1 New Words

Still, transcribers will come across dialect-specific words or other speech-words that aren’t in any dictionary, and don’t have a standard spelling. 

In this case, transcribers must refer to this document. 

If the spoken word has not been added here yet, then contact ___________

1.2 Numbers

Numbers should always be spelled out: For example, write གཅིག not ༡ or 1. 
1.3 Abbreviations

Don’t abbreviate—always spell things out fully. For example, write བཀྲ་ཤིས not བཀྲིས.

2 Disfluent Speech 

Speakers often repeat themselves, or start a sentence, stop, and then continue on a different train of thought. It is very important for transcribers to try, as best they can, to write speech down exactly as it is spoken. This includes partial sentences, partial words, grammar mistakes, and repetitions. 
2.1 Grammar Mistakes

Transcribing speech is a very different skill from being a good writer. A good transcription, exactly as possible, records what is spoken. That means that when a speaker makes a mistake, a good transcription records that mistake exactly as it occurred. 

The goal of the transcriber isn’t to produce pretty, beautiful-sounding, well-edited texts for readers to read; it is to produce accurate data for specialists to analyze. And the more accurate the data is, the more useful it is. For example, if a specialist wants to analyze the differences in “how people speak” and “how people write,” transcripts that are edited by good writers become useless! 

Example: 

2.2 Filler Words & Interjections

Speakers often make non-word sounds to fill the space between thoughts. If you find new ones, keep it on the list. These sounds are recorded like this: 

ཨ་ནི་
ཨ་
ལགས
ཡ་ཡ་
ཨ་ལེ་
འོ་ཡ་


2.3 Partial Words & Partial Sentences

Speakers often make half-words, half-sentences, or half-thoughts. It is important to record these as closely as possible. If a speaker stops mid-word or mid-sentence, you may record the final word they spoke (if you understood it). A “partial thought” is represented by a row of three tshegs: ་་་. 

For example: 

ང་གཉིས་མཉམ་་་ ང་གཉིས་མཉམ་དུ་ཕྱིན་པ་ཡིན། 

3 Other Markup 
3.1 Multiple Speakers

Label each transcription section that is not the primary speaker (the one belonging to the metadata of your file). Primary speaker sections may be unlabeled. If you cannot hear or understand the speech of the person they are talking to, do not transcribe it. 

However, if the other speaker’s speech is clear and understandable, label it with the Tibetan number “༢”. If there is a third person clearly audible on the recording, use the Tibetan “༣”, and so on. (Remember, all numbers spoken by a speaker should be spelled out, so Tibetan numbers should only be used to indicate a second, third, or fourth speaker). 

For example: 



There should not be two speakers transcribed in the same section. If there are two speakers in the same section, use the “Segment” function in SayMore to split that section. 
3.2 Unclear or Unintelligible Speech 

Sometimes, the recording quality may be poor, or the speaker may mumble or say something you can’t understand. You should record your best-guess (if possible) between double parentheses ༼༼  དེ་ལབ་སོང་།  ༽༽. If you truly can’t understand it at all, leave the parentheses empty inside: ༼༼  ༽༽.
3.3 Other Non-Words  

There are a few other non-word vocal data that transcribers should record. Record these vocal data by placing a description in a set of single parentheses. Keep the group up-to-date on the suggested standard you have chosen. They include: 


Non-Word Data
Transcript Standard
Laughter
༼ཧ་ཧ་༽
Tsk-tsk-ing
༼ ??? ༽



3.4 Anonymizing the Transcript 

Words that give away personal information should not appear, in context, in the transcript. Personal data and private information should remain private—and it is part of the transcriber’s job to keep such data private. 

Information like phone numbers, names, and addresses should be given an anonymous substitute: For example, a specific name should be noted in parentheses as a general name ༼མིང་༽. An anonymous phone number would look like this: ༼ཁ་པར་ཨང་གྲངས༽. 


Personal Data
Transcript Standard
Personal Name (ie, བཀྲ་ཤིས)
༼མིང་༽
Personal Phone Number (ie, 09837466)
༼ཁ་པར་ཨང་གྲངས༽



