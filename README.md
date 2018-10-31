# Introduction

The resume is generated using (https://jsonresume.org/)[https://jsonresume.org/]. 

# installation:

```
npm install -g resume-cli
```

# Generating the resume
To be able to generate the resume, make sure you are in a folder that contains the file resume.json and then run the following command:

```
resume export resume.html
```

There are many (themes)[https://jsonresume.org/themes/] that can be used. The one that we use generally is (stackoverflow)[http://themes.jsonresume.org/theme/stackoverflow].

In order to generate the resume using the stackoverflow theme, use the followong command:

```
resume export --theme stackoverflow resume.html
```

You will need to install the stackoverflow resume.

# Notes:

Make sure you always export the resume as html, and then from the browser print the html page as PDF
