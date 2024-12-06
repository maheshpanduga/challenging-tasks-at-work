# 1. What are the best practices and strategies for efficiently enabling users to upload large files, such as those exceeding 1GB?
Uploading large files presents several challenges, especially when dealing with files that are 1GB or more
# Solutions:
* Chunked Uploads and Resumable Uploads: Break large files into smaller chunks that can be uploaded separately and retried if needed.
  
* Direct-to-Cloud Uploads: Avoid overloading the server by allowing users to upload files directly to cloud storage services like AWS S3, where upload processes are optimized for large files.

# Implement Solutions
* **Chunked Uploads and Resumable Uploads**: We will implement this solution using Spring WebSockets to enable efficient file uploads by breaking them into smaller chunks and allowing for resumable transfers.
* **Direct-to-Cloud Uploads**: This solution will be implemented using AWS S3 pre-signed URLs, enabling users to upload files directly to the cloud, bypassing the need for server intermediaries.

# 2. Process a large csv file and upload the data into the database.
# 3. How to search a user in 1 Billion records?.
# 4. How to implement database sharding?.
# 5. Design a system like BookMyShow, Parking Lot
# 6. How to allow user to upload large files like 5GB or more from the front end with smooth user experience.

  
