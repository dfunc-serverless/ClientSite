# ClientSite
This is a Web application that allows clients to sceduale a job on dFunc servlesless environment. An official hosting of client website is avalible at www.dfunc.tech
## Expectation
- Clients are expected to compose their jobs inside a docker container and upload to DockerHub. 
- Client is also expect to provide a triger to the application inside their docker image.

## Usage
- Clients are required to signup on the website inorder to schedual and retrive a job function.
- Clients will then provide the full image name of their job function
- Clients will at last provide a trigger to the application inside their docker image.
- An email will be sent back to the client with their function output information.
- Client is allowed to schedule multiple jobs at the same time. 
## Future work
- At current stage, finacial transcation is not included inside this Web Applciation.
- More interactive ways for clients to control their job functions is needed.