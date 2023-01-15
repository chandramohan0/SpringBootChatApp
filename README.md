<h1 align="center">Spring-Boot-WebSocket-ChatApp</h1>

## <h2>About ChatApp</h2>

 <b>This app is built with the help of the WebSocket Protocol, where we can achieve the two-way communication between the server and the client, which means the server no need to wait for the client’s request to send the data</b>.

**<h2><i><u>Steps involved to create this application<u></i></h2>**

<h3>A.) Backend Development:- </h3>

**Step 1**: Create a Project from <a href = "https:e/</a>/start.spring.io/">Spring Initializer</a>.

  -Go to the Spring Initializr.<br>
  -Mention the Artifact Id, spring-boot-WebSocket-chat-app<br>
  -Add the following dependencies,<br>
     1. Spring Web.<br>
     2. WebSocket <br>
     ![Screenshot (217)](https://user-images.githubusercontent.com/77689644/212533972-d6324203-da02-4786-9fab-41f490da225a.png)

     
**Step 2**: Click on the Generate button shown above, the project will be downloaded on your local system.<br>
 
**Step 3**: Unzip and extract the project.<br>

**Step 4**: Import the project in your IDE.
            Select File -> Import -> Existing Maven Projects -> Browse -> Select the folder <b>spring-boot-WebSocket-chat-app</b>> Finish. <br>
            
**Step 5**: Create a <b>WebSocket Configuration</b> class
![Screenshot (218)](https://user-images.githubusercontent.com/77689644/212534394-e729dd47-cbb1-4d23-9d09-6abd1b27d734.png)

**Step 6**: Create <b>ChatMessagePojo</b> class
![Screenshot (219)](https://user-images.githubusercontent.com/77689644/212534869-3d7cb117-5021-4680-9f3e-68312bef7440.png)


**Step 7**: Create a <b>Controller</b> class to send and recieve the messages
![Screenshot (220)](https://user-images.githubusercontent.com/77689644/212535112-4c27e017-8df5-4dfe-98cb-3bf0d580a613.png)


**Step 8**: Create a class for <b>WebSocket Event listeners</b>.
![Screenshot (222)](https://user-images.githubusercontent.com/77689644/212535292-38aac15f-ef60-4a39-92fb-767dd0972b7e.png)



<h3>B.) Frontend Development:- </h3>

**Step 1**: Create a <b>index.html </b> in the path <b>src/main/resources/static</b>.

**Step 2**. Add the <b>main.js</b> in the path <b>src/main/resources/static/js</b>

**Step 3**. Adding the <b>main.css</b> in the path <b>src/main/resources/static/css</b>

**Above code is just used for designing our application**.

<h3>C.) Run the application</h3>
Go to the <b>localhost:portNumber</b> in my case <i><b>portNumber=8083</b></i> we will get the screen as shown below.
<br>
<b>Once we enter username and click on the start chatting button, we will be redirected to the chatbox.</b><br>

![Screenshot (223)](https://user-images.githubusercontent.com/77689644/212536261-b3e48b7e-3b67-46ce-8c8c-b42b19a57d35.png)

<br>

![Screenshot (224)](https://user-images.githubusercontent.com/77689644/212536273-5ee26263-9c07-473b-8dd8-e172c73f7e1c.png)
<br>

Type some random message.
![Screenshot (225)](https://user-images.githubusercontent.com/77689644/212536441-48c4d598-e0e3-4ee2-b568-e1a4614c513d.png)
<br>
Go to the incognito mode or guest mode on your browser and visit localhost:8083, you will again be asked to enter a username, give some other name and click on start chatting, now type some message, and send it in that chat.

Now visit your home browser were you already there with your original name, therein chatbox you can the message received which you send from the Guest mode.
<br>
![Screenshot (226)](https://user-images.githubusercontent.com/77689644/212537016-7ba9d416-d8a4-4bed-b742-d565a79dd57f.png)





