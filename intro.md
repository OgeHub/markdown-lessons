# Heading with H1

Paragraph content.

**Bold font size** *Italic text* ~~strike on text~~

## Ordered Listing

1. one
   1. sub-one
2. two
3. three

## Heading with H2

when you want to write `formatted text or highlight a text`

## Writing a code block

```js
app.set('view engine', 'ejs');
app.use(bodyParser.urlencoded({extended: true}));
app.use(express.static("public"));

app.get("/", function(req,res) {
    res.render("home");
});
app.get("/calculate", function (req,res) {
    res.render("bmiCal");
});
```

horizontal line below

---

## Block quote

>If you judge people, you have no time to love them.
>
>I am not sure exactly what heaven will be like, but I know that when we die and it comes time for God to judge us, he will not ask, ‘How many good things have you done in your life?’ rather he will ask, ‘How much love did you put into what you did?
>> a nested block quote here.
>
-- *Mother Teresa*

## Unordered listing

- first item
- second item
- third item

To create a link to a heading. Use exact name of the heading in lower cases and replace space with dash.

[link to block quotes](#block-quote)

[Link to external site](https://my-bmi-cal.herokuapp.com)

To add an image

![Alternate text for image](./markup.jpg)

The Image can be a link by nesting the whole syntax in a square bracket and adding a bracket with the url

Line break can be achieved by skipping the next line

and continue here.

To create a checkbox

- [x] task #1
- [ ] task #2

## Tables

| s/n | Name | Favorite food | 
| :---- | :---- | :---- |
| 1 | Favour | Pap |
| 2 | Success | Noodles |
| 3 | Happiness | Pasta |