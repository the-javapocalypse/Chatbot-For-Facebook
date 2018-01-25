# Chatbot For Facebook Personal Profile in Python

A simple Chatbot for Facebook's personal profile that can chat with any of your friends and reply to them. Complete text and video based detailed [tutorial link](http://www.letscodepro.com/chatbot-for-facebooks-personal-profile-using-python-dialogflow-p1/)

## Getting Started

You will need to register a free account on [dialogflow](https://dialogflow.com/). After that you need to create an agent and train it ([how to create and train an agent using dialogflow](http://www.letscodepro.com/chatbot-for-facebooks-personal-profile-using-python-dialogflow-p2/)). After that copy Client Access Token somewhere because we will be needing that later. 

### Installation

Download or Clone the repo, Navigate to the directory containing the files and run
```
python setup.py install
```
or if you have different versions of python installed then
```
python3 setup.py install 
```
to install the dependencies.

__Note:__ If you're facing problems in installation of fbchat in __Ubuntu__ then run the following command.
```
sudo apt-get --yes --force-yes install libxml2-dev libxslt1-dev libxml2 python-dev python3-dev zlib1g-dev
```

### Usage

After running setup.py, open bot.py and plug in your Client Accecss Token, email and password and run the bot. Now you can test the bot by logging into some other facebook account and starting a chat with the account you used to run the bot.


## Built With

+ fbchat
+ apiai

## Contributing

1. Fork it
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request

## Authors

+ Muhammad Ali Zia

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/the-javapocalypse/Chatbot-For-Facebook/blob/master/License.md) file for details
