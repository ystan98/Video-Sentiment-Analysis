## Video Sentiment Analysis Project Overview
TikTok has become extremely popular with its innovative short-form videos. What has
really contributed to its immense appeal is a powerful recommendation engine tailored to its user’s
interests, constantly refining their “For You” page. However, because a large proportion of its
viewers are young children, filtering for upsetting content (drugs, violence, sex) is vital to
protecting their interests.

In this project, a multi-modal classifier (text sentiment, music sentiment, facial expression) is built
to deem if a video has a positive, negative, or mixed sentiment. Three types of features from a
video clip were extracted, consisting of audio, text, and facial expressions. The respective model’s
output of these 3 parts were combined in classifying the overall sentiment. Finally, a web
application was also developed to demonstrate the integrated pipeline, and for users to upload a
video to see the predicted sentiment.

For more information about this project, you may visit this link for the report/write-up:
https://drive.google.com/file/d/19l2cZ05PRm4C1L4K_xAyZ2NPUesGhLvi/view?usp=sharing

## How to run the project
1. Create your python virtual environment - (Optional)
2. Run Command `` pip install -r requirements.txt `` (Do note that it might take awhile as there are a lot of dependencies)
3. Go into the directory ``integrated/webapp/``
4. Run Command ``python app.py``
5. Open your browser and go to http://localhost:5000/
6. Try and upload a video and see the magic :)

## Important to note 
Some External modules/api require API token to access their services, they may have expired. List of modules that require API token are as follows:
- https://docs.audd.io/#api-methods - get music attributes (title & artist, etc)

- require env file to use spotify API (I included mine in a hidden .env file. Get yours from Spotify to test this application!)
CLIENT_ID=""
CLIENT_SECRET="""


Step 1) Upload Video


![image](https://user-images.githubusercontent.com/66168700/204093297-e44e3f48-5f4c-4a57-90fb-9b932231bf6f.png)



Step 2) Wait
![image](https://user-images.githubusercontent.com/66168700/204093148-6e517ebb-b6be-4145-ab7b-82f5f37882e5.png)


Step 3) Get results!

![image](https://user-images.githubusercontent.com/66168700/204093158-b2873d25-7cda-40c2-b35f-cc3ecdc471da.png)
