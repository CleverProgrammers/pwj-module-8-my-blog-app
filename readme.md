# General TODOS

## TODO(Together): Create the home page structure for index.html
## TODO: Create Blog Post HTML structure and styling

It needs to follow a class structure like this:

    class post

        class post-image

        class post-content

            class post-date

            class post-title

            class post-text

### HINT: Use Unsplash for image to test
### HINT: Set the .post-image to have flex-basis: 40%;

## TODO: Add nice hover effect for the blog post

### HINT: use translate3d and transition
### HINT: Hover box shadow `box-shadow: 0 2rem 5rem 0 rgba(0,0,0,.1);`

## TODO: Add the New Post Button Styling 

    background-color: #004186;
    box-shadow: 0 2px 5px 0 rgba(0,0,0,.26);

    On Hover:
    background-color: #002349;

    <div class="add-post">
        <a href="new-post.html">
            <div class="nav-button new-post-button">+</div>
        </a>
    </div>

## TODO: Complete the post.html page

It needs to follow a class structure like this:

    class navigation

        a link

    class post-container

        id individual-post-title

        id individual-post-date

        id individual-post-content

## TODO API (Together): Set Up a NodeJS Server

## TODO API: Create an API Endpoint to return list of posts
`Endpoint: /api/posts Method: GET`

    [{
        "id": "1581461442206",
        "title": "This is a New Blog Post",
        "content": "This is the content! ",
        "post_image": "uploads/post-image-1581461442199.jpg",
        "added_date": "1581461442206"
    }]

## TODO API (Together): Create post.js for interacting with data.json

## TODO API: Create readData function to get data from data.json

## TODO API(Together): Create storeData function to store data into data.json together with add() function

## TODO API : Create an API Endpoint to return one post based on id
`Endpoint: /api/posts/:post_id Method: GET`

### HINT: Use post.js for getting data from data.json 

## TODO(Together): Complete index.js to connect to API and get list of posts
### HINT Make sure to make the statis files public

## TODO: Complete post.js to get data from API and fill in the post.html

### HINT(Together): Think about how you are going to link from index to post.html

## TODO API: Create API endpoint for adding a new post without image upload
### HINT: Make sure test with postman
### HINT: Use post.js add() function
### HINT: add "id" with current date
### HINT: add "added_date"

`Endpoint: /api/posts Method: POST`

Payload:

    title: <text>
    content: <text>
    post-image: "uploads/post-image-1581375207393.jpg"

## TODO API(Together): Add ability to upload file to API


## TODO: Complete new-post.js to be able to submit new post

















