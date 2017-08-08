# To get Start
Fork this repo to your machine and start your coding

# Task
Write a node program to count the word occurrences for all docs inside "files" folder. And output the result in json format and put that inside result.json

For example, if the doc contain following text
```
This is a dog.
This is a cat.
```

The output inside result.json should be
```
{"this":2,"is":2,"a":2,"dog":1,"cat":1}
```

Program entry point is main.js and you need to work on master.js or more
```
node main.js
```

# Requirement
* All special character, number, white space should be removed before counting
* Case insensitive
* If possible, do multi-threading


# Test
If you complete the task correctly, following test should be run successfully.
```
npm test
```
