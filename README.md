1. Publish the WASM project on visual studio.

2. Upload the published file on the github.

3. Change the base href in index.html

----
	<head>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
		<title>BlazorWasm</title>
		<base href="/<WebRoot>" />
		<link href="css/bootstrap/bootstrap.min.css" rel="stylesheet" />
		<link href="css/app.css" rel="stylesheet" />
		<link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap" rel="stylesheet" />
		<link href="_content/MudBlazor/MudBlazor.min.css" rel="stylesheet" />
		<link href="BlazorWasm.styles.css" rel="stylesheet" />
	</head>
 
 4. Copy and rename the index.html to 404.html
 
 5. Create a file .nojekyll in the root foloer.
