# JavaLagosDevelopers
list of Java developer in Lagos
JavaLagos is an android app that makes a request to get a list of java developers in lagos from github 
using this API ENDPOINT private static final String URL_DATA = “https://api.github.com/search/users?q=language:java+location:lagos"
we used volley to define and make the request, used Picasso to load the image data to our ViewHolder and 
displayed the response on CardViews with which we then populated our RecyclerView.
