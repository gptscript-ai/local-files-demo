# local-files-demo
A demo of using GPTScript to interact with files of various types on your workstation.

This GPTScript will launch a chat assistant that has the ability to read and query files in your specified workspace. It can read and process PDFs, query Excel files, and extract data from CSV and JSON files.

The `sample-data` directory in this repo has a few files you can use to experiment with this tool. To use them, launch like this:
```
gh repo clone gptscript-ai/local-files-demo
cd local-files-demo
gptscript --workspace=./sample-data ./agent.gt
```

You can also run it without cloning the repo:
```
gptscript --workspace=/Your/path/here github.com/gptscript-ai/local-files-demo
```
