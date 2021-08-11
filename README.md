
# cab432-api-mashup
The first project of the QUT course CAB432. It combines the Google Vision, Google Books, Goodreads and Bol.com API into image based search system which can manage your Goodreads library.

![enter image description here](example_images/main.png)

## Use case
The user navigates to the index page. On this page the user will take a photo or upload a photo of the book in question. 

![enter image description here](example_images/index_page.png)

If the user has uploaded an image that does not contain a book the user will be shown an error dialog. However if the image contains a book the image will be analysed and an automatic search query will be performed and the user will be show the 3 most likely books

![enter image description here](example_images/search_result.png)

The user will be redirected to a dedicated book page when the user click one of these books On this page the user will be provided with all kinds of information of the book in the image, such as a description, author information, related books, reviews, etc.

![enter image description here](example_images/book_info.png)



