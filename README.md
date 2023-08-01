# Interview

## Questions 

For this question create a file called Questions.md in the root of the repository and copy each question below and provide answers directly below each question.

1. Name some of the differences between an Author and a Publisher.
2. What is the Dispatcher and what are some of its purposes?
3. Name some of the open source technologies that AEM uses and name provide some of the functionality it provides.


## Practical Test

What you will need to do this practical test.

- Java 11.x
- Maven 3.8.3
- Docker 20.10.23
- NodeJS 14.18.x
- npm 8.19.2

### Question 1

Using the following [AEM Archetype](https://github.com/adobe/aem-project-archetype) create an AEM project and place it in the aemarchetype folder.

#### Project requirements

- Must use the `latest` AEM archetype
- Must be able to run on `AEMaaCS`
- Frontend module leverages `ReactJS`
- App Title is `First AEM Project`
- AppId is `firstaemproject`
- artifactId is `firstaemproject`
- groupId is `com.support.interview`
- Include a `dispatcher` configuration
- Do not include the target folders in the git repository
- The project must be buildable with `Java 11`
- Keep the command used to build the archetype and add it to aemarchetype/README.md

### Apache Sling Site

- Make sure you have docker running on your local machine
- Go to the following page https://sling.apache.org/downloads.cgi#sling-application Oak-Tar `docker run --rm -p 8080:8080 apache/sling:snapshot`
- Create a component with the content of the following file `sling/apps/interview/helloworld/helloworld.html`, make sure that the folder structure for the component is `apps/interview/helloworld`. Copy/paste each command used in the sling/README.md file
- Create a sling:OrderedFolder under /content named interview and set the sling:resourceType to the component created in the step above
- If everything is created correctly you should be able to go to http://localhost:8080/content/interview.html and you will see `Hello World` being returned. Take a screen shot of it working in your browswer and add it under the sling/ folder.

### Bonus Question

Use HTL and edit the helloworld.html that checks to see if the content has a property called name and set it to your name. If the property is there then the page returns `Hello World ${YOUR_NAME}` otherwise it simply returns `Hello World`

Provide the helloworld.html file used to generate the markup.

## Final Steps

Once you have completed the interview, double check and make sure all the content and answers are provided. Create a PR request to this Github repository and then send an email to the email address provided to you during the interview.

Your results will be reviewed.