# 🤖 Moviebot - Daniel Owen's Version
Code repository for Moviebot – an NLP-powered movie recommendation chatbot, written in Python, HTML/CSS, and JavaScript, hosted on Vercel + AWS Lambda.

![](https://github.com/daniel-owen/moviebot/blob/master/static/assets/thumbnail.gif)

This is a personal project inspired by Steven Tey's Moviebot, created as part of my exploration into practical data science.

## 🖥 Running this locally 
To run this program locally, follow these steps:

1. Download the repo with `git clone https://github.com/daniel-owen/moviebot.git`
2. Create a virtual environment with `python3 -m venv venv`
3. Activate your virtual environment with `source venv/bin/activate`
4. Then, install all the required libraries with `pip install -r requirements.txt`
5. Next, export the Flask app route with `export FLASK_APP=index.py`
6. You will also need to export the Flask environment with `export FLASK_ENV=development`
7. Lastly, execute `flask run`, and your program should be running at `http://127.0.0.1:5000/`

## ▲ Deploying on Vercel
To deploy this to Vercel, run `vercel --prod` in your terminal and follow through with the default setup criteria.

If you encounter the error `zsh: command vercel not found`, you may need to run the following:

```
export PATH="/Users/danielowen/.npm-global/bin/:$PATH"
```

## 💪 The AWS Lambda Function
The AWS Lambda function can be found in this [`model.py` file](https://github.com/daniel-owen/moviebot/blob/master/aws-lambda/model.py).

## 🐞 Question + Bug Fixes
Feel free to contact me at [daniel.owen@email.com](mailto:daniel.owen@email.com) for more information about this project. This project is a replication inspired by Steven Tey's Moviebot.
