USE PALETTE EDIT AS A REFERENCE
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  <h1>Edit Entry</h1>
  <form action="/colors/{{id}}?_method=PUT" method="post">
    <label for="subject">
      subject: <input type="text" name="subject" id="subject" value="{{subject}}">
    </label>
    <label for="content">
      content: <input type="text" name="content" id="content" value="{{content}}">
    </label>
    <button type="submit">submit changes</button>
  </form>
</body>
</html>