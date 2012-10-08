This is a bundle of utilities , that can be used for Java Network calls.

This bundle includes 
	
	* Get the html source of any url
	* Get the re directed links from the url
	* Get the absolute path
	* Canonicalize the url
	
	
Sample Usage

	HtmlFetcher htmlFetcher = new HtmlFetcher();
	String html = htmlFetcher.getHtml("url",socketTimeOut);
	
	By default the socket time out parameter is 10000 , if you dont provide it.