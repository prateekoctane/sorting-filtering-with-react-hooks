<h1>Book Management</h1>

<h2>This is a small react app which handles a collection of books and displays them on the home screen. Through this app I have tried to implement sorting, filtering data using redux state and json-server sorting and filtering api features. Also implemented the persisting of data with the use of useSearchParams() hooks, useLocation(), useEffect(). Also implemented Private Routes, meaning only those who are logged in can view the single book page and can have admin access for editing the details of the books.</h2> 

<h3>Tech Stacks Used:</h3>
1. react <br />
2. react-redux <br />
3. react-router-dom <br />
4. axios <br />
5. json-server <br />
6. redux <br />
7. useSearchParams() <br />
8. redux-thunk <br />

<h2>Glimpse of App:</h2

More focuc on functionalities, UI is kept to minimal

<h3>Home Page</h3>
<img src="https://github.com/prateekoctane/sorting-filtering-with-react-hooks/blob/main/home.PNG" alt="homePage" />

<h2>Flow of App</h2>
On load the app opens in Home Page. Where you can see navbar, sidebar and bookcards. Now if you want to click on any book card to go to the single book card page then it redirect to you the login page, asking you to login first, only then can you see the single book page. This is the implementation of the private route. After logging in, it redirect you to the single book page where you wanted to go originally.

On the home page there is sidebar. It has two options, one of sorting by category and the other one is filtering by release year. On clicking on sorting and filtering options the URL in the browser also changes accordingly which is accomplished the hook useSearchParams() provided by ract-router-dom library.

On refreshing the page the selections of radio and checkbox buttons remain the same. They dont get re-initialised. They persist.

After logging in you also can edit the book details by clicking on the small edit button below each Book Card.
