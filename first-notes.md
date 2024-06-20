# The First System Design Video Notes

Address: _https://www.youtube.com/watch?v=FiXOaYnW64w&list=LL&index=2&t=502s_
Till: _21:34_

Processes
1. Play Videos on Client
    * Any YouTube URL
    * Stream your video and audio
    * Add video to `s3 (data storage)` bucket and play using the s3 url
2. Create Upload Service
    * Upload media on `s3` and test API using Postman
3. Send Upload Request from Client to Service with File
    * Kafka Concepts
4. Extract File from Request in Service and Upload that to S3
