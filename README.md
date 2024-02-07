Elastic Beanstalk dashboard







Endpoint URL for a running elastic beanstalk deployment
* Root endpoint to display simple message.
http://projectstartercode-dev.us-east-1.elasticbeanstalk.com

* Endpoint to filter an image from a public url.
Query parameter image_url is empty -> return status 400 and message error.
http://projectstartercode-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url

Query parameter image_url is valid -> return status 200 and response image.
http://projectstartercode-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg










