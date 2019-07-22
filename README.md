# Meta_data_scrapper

### Setup

* Clone this repo:

```
git clone https://github.com/archulal/Meta_data_scrapper.git

```

* Run this command:

```
cd Meta_data_scrapper

npm install
```

### Running the code

### 1) Execute this command in your terminal:

```
node .

```
### 2) Unit testing using postman:
```
1.Set http method as post
2.Url as http://localhost:3000/web_scrape
3.Set header "Content-Type: application/x-www-form-urlencoded"
4.In bodu gave the key value parameter eg: key=url value="https://diagnal.com/"
5.Run using Send in postman.

![Alt text](images/diagnal_postmanscrapper.png?raw=true "Title")

```
### 3) Packages used:
```
1.cheerio - Cheerio parses markup and provides an API for traversing/manipulating the resulting data structure. 
2.body-parser - Node.js body parsing middleware.
3.uses Expressjs as frame work
```

### Extening of scrapping
```
We can extend this web scrape for compare the content title of multiple urls and only list the urls having same kind of titles.
