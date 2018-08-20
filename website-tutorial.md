# Build your first Website

## Folder Structure 
First we will create the directory structure and files for the website.

1. Open up your terminal in cloud9.
2. Type the command `mkdir website`.
3. Type the command `cd website` to enter the directory.
4. Type the command `mkdir css images`. This will create two folders inside your `website` directory called `css` and `images`.
5. Type the command `touch index.html`. This will create an `index.html` file.

Your directory structure should look like this.

```
website/
	css/
	images/
	index.html

```

You now have the basic setup to start creating your website.

## HTML Layout
HTML is what you will write to layout the content of your website.

Copy and paste this HTML starter code inside your `index.html` file.

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  
</body>
</html>

```

Now in between the `<body></body>` tags you will write a title and a sentence about yourself. To do this you will use the `<h1></h1>` tag and the `<p></p>` tag like so. 

```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  <h1>John Doe</h1>
  <p>Hello my name is John Doe.</p>
</body>
</html>

```

Now to view your website click on the Run button towards the top of the cloud9 editor.