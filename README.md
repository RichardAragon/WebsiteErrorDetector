# Website Error Detector
Crawls a website and returns any pages that have errors.

This code adds a button with the id ‘start-button’. When this button is clicked, it triggers the update_error_log callback, which calls the crawl function and updates the ‘error-log’ with any error message returned by crawl.

Please note that running this code in a Google Colab environment requires the use of mode='external' when calling app.run_server(). This is because Google Colab does not support running Dash apps inline. When you run the app, it will provide a link to a new tab where you can interact with the Dash app.

Also, please be aware that web crawling can be resource-intensive and may violate the terms of service of some websites. Always make sure you have permission to crawl a website, and consider adding delays between requests to avoid overloading the server.
