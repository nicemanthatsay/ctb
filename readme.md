
# CrossFi Tap Bot

Instruction:

- Clone Repo
```
git clone https://github.com/nicemanthatsay/ctb.git
```
- Change dir
```
cd crossfi-auto-tap
```
- Copy tokens.json
```
cp tokens.json.example src/tokens.json
```

- Edit tokens.json
```
nano src/tokens.json
```

- Fill in tgWebAppData and seedphrase

- How to find tgWebAppData
. open the crossfi tap bot in telegram

. login with your seedphrase

. click F12 or right-click and click inspect

. go to application => section storage

. click on crossfi .org and check through the Value next to Key 

- Start the bot
```
cd src
node app.js
```

- For single account (tokens.json)
```
[
  {
    "tgWebAppData": "",
    "seedPhrase": ""
  }
]
```

- For multiple account (tokens.json)

. Use: 
```
[
  {
    "tgWebAppData": "",
    "seedPhrase": ""
  },
  {
    "tgWebAppData": "",
    "seedPhrase": ""
  }
]
```


