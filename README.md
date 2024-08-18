*************Movies-box *************
This React application allows users to discover and search for TV shows and movies. The application fetches data from an external API, displays it in a user-friendly interface, and provides features like sorting, pagination, and dynamic searching among others.

****************Features
TV Shows and Movies Discovery: Users can explore popular and top-rated TV shows and movies.
Search Functionality: Users can search for specific TV shows and movies by entering keywords.


**********Search Functionality: 
Users can search for specific TV shows and movies by entering keywords.

*******Sorting: 
Users can sort TV shows and movies .

********Pagination:
 The application supports pagination, allowing users to navigate through different pages of search results.

********Loading Indicators:
 Displays skeleton loaders and spinners while data is being fetched.


 *****************************************************
****Components
****Movies
Displays a list of movies fetched from the API.
Allows sorting by popularity or rating.
Supports pagination for navigating through pages of movie results.
Shows loading indicators while fetching data.



*******Shows
Displays a list of TV shows fetched from the API.
Allows sorting by popularity or rating.
Supports pagination for navigating through pages of TV show results.
Shows loading indicators while fetching data.

***********Search
Allows users to search for TV shows and movies by entering keywords.
Fetches search results based on the input query.
Supports pagination for navigating through search results.
Shows a loading spinner during data fetching and displays a "No results found" message if no matches are found.


********CardComponent
Displays individual TV show or movie items.
Renders details like the title, image, and media type.

***********PaginationComponent
Manages pagination of results.
Provides controls for navigating between pages.