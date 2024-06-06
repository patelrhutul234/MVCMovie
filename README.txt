Student Name:- Rhutul Hasmukhkumar Patel
ID:- 0852247

2024-05-16
Part 1
1425 UTC

Created a project name MVC Movies and added a controller

1445 UTC
Ran the program, Confirmed the default works:
https://localhost:[Port]/
Modified the index.cshtml title to MVC MOVIE by replacing the default title WELCOME
Created README.in the MVC Movies
Was able to confirm the default page

Part 2
1510 UTC

Commented the default index method which is returning to class view()
Then added new index method and changed the content to "This is my default action..."
Was running when i ran the program

https://localhost:[Port]/Helloworld

1545  UTC
Added another method called welcome with the content of "This is the Welcome action method..."
Confirmed it was running

https://localhost:\[Port]/Helloworld/welcome

1620 UTC

Change the Welcome method to include two parameters(name,numtimes)
Ran the program, Confirmed the changes works:

https://localhost:[Port]/helloworld/welcome?name=Aditya&numTimes=6

Part 3
1705 UTC
Added the Index in the helloworldcontroller

1720 UTC

Created a razer file in Views/HelloWorld/Index.cshtml added the CSHTML which showed the index
webpage.

1740 UTC

Change the title, footer, and menu in Views/Shared/_Layout.cshtml added the CSS code.
so than when we click on privacy it created the new page.

1755 UTC

In HelloWorldController.cs, change the Welcome method to add a Message 
and NumTimes value to the ViewData dictionary.

1815 UTC

 now that is opened https://localhost:][Port]/HelloWorld/Welcome?name=Aditya&numtimes=4

 it showd my name 4 times. and you can the numtimes to 10 and it will show your name 10 times.

 2024-05-23
 Part 4

 1340 UTC
 I added the scafolded the movie page and update the files in nutgets in tools and when i clicked the 
 movieapps link it showed me the database.

 1355 UTC
 Timestamp
 20240530020608_InitialCreate is the Migrations timeframe

 In the index i created some list of movies with differet columns.

Part 5

1420 UTC
 Check the data is available in SQL Server Express LocalDB
 And here found dataPart 5

 1440 UTC
 Check the data is available in SQL Server Express LocalDB
 And here found data of the movies which I add through the Index code
 
 1500 UTC
 Add SeedData on the Model Folder replacing with code
 After Adding Seed I add the seed initializer
 
 1545 UTC
 And Open link with  https://localhost:7125/Movies of the movies which I add through the Index code
 Add SeedData on the Model Folder replacing with code
 After Adding Seed I add the seed initializer
 And Open link with  https://localhost:7125/Movies

 Part 6

 1630 UTC 
 Added DataAnnotations for "Release Date" and price formatting.

1640 UTC
Ensure "Release Date" shows correctly without time.

1700 UTC
Examined the generation of Edit, Details, Delete links in Views/Movies/Index.cshtml.
Viewed the source in the browser to understand the generated markup.

1730 UTC
Analyzed GET and POST Edit methods in MoviesController.
Confirmed use of [ValidateAntiForgeryToken] attribute for security.

1800 UTC
Updated Views/Movies/Edit.cshtml to render form elements and handle validation.
Ran the app, navigated to /Movies, and verified the "Release Date" display.
Checked functionality of Edit, Details, and Delete actions with correct data formatting.

30/05/2024
Part 7

1310 UTC
In these part i updated the index method inside MoviesController.cs
The var movies in _context.Movie creates the LINQ query.

1340 UTC
I navigated inside index file and appended the query string.
I changed all parameter to ID and changes all the occurences of searchstring.

1420 UTC
I updated those commands for that.
Now i run the program to pass the search title as route instead of query string value.

1430 UTC
Now in Index.cshtml i added form markup that contains movie name, index and searchstring.
And then added the HttpPost index method in it. After adding that method i checked by running it in browser whether these method runs or not.
As the search parameter is in the request body so i cannot capture the search information.

1440 UTC
I added the command to add search by genre.
Again i updated the Index.cshtml file for adding search by genre to index view.
I examined by running it and yes it works.

Part 8

1455 UTC
In these part i updated the movie.cs file with given code.
After that i added Rating action method.
Again i edited the Index.cshtml file with rating field.

1500 UTC
Also updated the rating command in create.cshtml file from view and movies folder.
I updated the command inside seeddata file having Rating class that provides value for new column.
From tools menu i used NuGet Package Manager and then Package Manager Console.
In the powershell package manager i added migration rating and then updated those database.

06/06/2024
Github
1355 UTC
I logged in to Github account by using my credentials. I cloned MVCMovie file to Github. After that i changed the visibility to Public view.
I updated SeedData files and run it in browser.