# API - Image Search Abstraction Layer

Here are the specific user stories which has been implemented:

1. I can get the image URLs, alt text and page urls for a set of images relating to a given search string.

2. I can paginate through the responses by adding a ?offset=2 parameter to the URL.

3.  I can get a list of the most recently submitted search strings.

### Example
[Search images with keywork : "lolcats"](/api/imagesearch/lolcats%20funny)
[Search images with keywork : "lolcats" (page 10)](/api/imagesearch/lolcats%20funny?offset=10)
[Get  recent search queries](/api/latest/imagesearch/)