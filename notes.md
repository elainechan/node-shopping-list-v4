# Notes
- Fix cURL request
```shell
node-shopping-list-v4$ curl -X PUT -H "Content-Type: application/json" -d '{"id":"32cffb61-ed0e-485a-805a-a3f8f80f7513", "name": "sausages", "ingredients":["pork", "salt"]}' 'localhost:8080/recipes/32cffb61-ed0e-485a-805a-a3f8f80f7513'
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Error</title>
</head>
<body>
<pre>Cannot PUT /recipes/32cffb61-ed0e-485a-805a-a3f8f80f7513</pre>
</body>
</html>
```