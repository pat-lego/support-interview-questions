# Answers For The Second Interview Question

1. Creating "/interview/helloworld"

curl -u admin:admin -F jcr:primaryType=sling:Folder http://localhost:8080/apps/interview/helloworld

2. Uploading helloworld.html

curl -u admin:admin -T "C:\Users\siddh\Desktop\Adobe Interview\support-interview-questions\sling\apps\interview\helloworld\helloworld.html" "http://localhost:8080/apps/interview/helloworld/helloworld.html"

3. Creating "interview" and setting resource type

curl -u admin:admin -F jcr:primaryType=sling:OrderedFolder -F sling:resourceType=interview/helloworld "http://localhost:8080/content/interview"
