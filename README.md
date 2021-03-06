# News Summary challenge

This is a single page web app that will grab all the headlines from the Guardian newspaper API and display them on a page.  Clicking on a headline will show a summary of the article.

## User Stories

```
As a busy politician
I can see all of today's headlines in one place
So I know what the big stories of the day are
```

```
As a busy politician
I can see a relevant picture to illustrate each news article when I browse headlines
So that I have something nice to look at
```

```
As a busy politician
I can click a news headline to see a summary and a photo of the news article
So that I can get an in depth understanding of a very important story
```

```
As a busy politician
I can see click a news article summary title which links to the original article
So I can get a few more details about an important story
```

```
As a busy politician
I can read the site comfortably on my phone
Just in case my laptop breaks
```

```
As a busy politician
I can see whizzy animations in the app
To make my news reading more fun
```

## Mockups

### Headlines page

![Headlines page mockup](/images/news-summary-project-headlines-page-mockup.png)

### Article summary page

![Article page mockup](/images/news-summary-project-article-page-mockup.png)


## Class diagram

<img width="853" alt="Screenshot 2020-12-14 at 10 12 45" src="https://user-images.githubusercontent.com/71889577/102068876-ec421380-3df4-11eb-843c-3fca7d2e1912.png">

## Installation instructions

Clone this repository:
```
$ git clone https://github.com/savannaelbey/news-summary-challenge.git
```
Navigate to the directory:
```
$ cd news-summary-challenge
```
Install http-server to run locally:
```
$ npm install http-server --save
```
Start the server:
```
$ node node_modules/http-server/bin/http-server
```
Visit ```http://localhost:8080/``` in your browser
