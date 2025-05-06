# llm-archives

### Instructions

Click the "Use this template" button for this repository and choose "Create a new repository". You can give it the same name (llm-archives).

Once it's ready, go to [Groq](https://console.groq.com/keys) and follow the directions to get an API key. You'll need to login (or create an account if you don't have one).

Copy the API key value and then click on the Settings of your GitHub repository and click on "Secrets and variables" on the left side, then choose "Codespaces"

Click the green "New Repository Secret" button and paste your API Key into the "Secret" box, then put GROQ_API_KEY in the Name box above it. Click "Add Secret" and click on the name of the repository to return to the main page.

From there, click the green "Code" button and create a new Codespace in the Codespaces tab.

In the Terminal type the following: pip install requests groq and hit enter.

Then type: python get_stories.py

You should see a file called cns_maryland_posts.json appear. Let's look at it. It contains some details of the past 10 CNS stories.

Back in the Terminal, type: python entity_extraction.py and watch the output.

### Evaluation for JOUR389W

PUT YOUR EVALUATION HERE
The results I got in the terminal are accurate. Groq can identify people, places, and organizations in the story I gave precisely, and in addition, it also gave a brief summary of people's attribution, places' locations, or what each organization does.   

I think for Xinhua, firstly, this technique could be used to enhance the search engine system on the main website. Xinhua has loads of content, including articles, pictures, and videos, but the search tab is not effective in inputting specific words to obtain corresponding results. Hence, I think the approach in this assignment could be used to enhance the search system's efficiency, so users who may want to look for specific news stories that contain content about specific people, places, or organizations, can use this searching tab to filter and find stories that they are particularly look for. 

Moreover, in terms of news reporting, Xinhua reporter can also use this technique to find story ideas from their own or other organizations' news archives. For example, reporters can look for how many times some news organizations have mentioned certain names, how frequently they have done that, or what other specific places or organizations have also been mentioned in the same stories containing those names. These kinds of insights could help reporters initially think of potential story ideas.     