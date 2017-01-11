Functionality Testing:
1.	Given valid key, value pairs and checking the response from API for all the below all search categories –
movie, podcast, music, musicVideo, audiobook, shortFilm, tvShow, software, ebook, all

2.	Search multiple key, values with special characters(.,*,_,-)
3.	Search the content with multiple key, values separated by  multiple spaces
4.	Search the content giving the limit between 1-200
5.	Search the content giving limit >200
6.	Search the content giving limit 0
7.	Search the content with non-supported country value
8.	Validate the error response rreceived for invalid URL request
9.	Try to access the url with keys & values other than English language


Performance Testing:
1.	Try to check the response time for the search for different categories
2.	Try to send 10 requests/sec to the url and check the response
3.	Try to send 100 requests/sec and check the performance
4.	Try to send 1000 requests/sec and check the performance
