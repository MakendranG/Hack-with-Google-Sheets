# Hack-with-Google-Sheets

## Download Data

This feature allows you to import/load website data into a spreadsheet. You can try the following steps to import data from any website:


* In any cell on your sheet, enter the below mentioned formula snippet.
* Replace the website address in brackets with your target website.
* Press Enter to load the data into your spreadsheet.

```
=IMPORTHTML("https://en.wikipedia.org/wiki/Demographics_of_the_United_States","table",4)
```

## Output


![image](https://user-images.githubusercontent.com/74320000/205967510-395d0738-fe01-4be3-8430-99aee647fac5.png)
