# MyFirstApp&nbsp;
## To build MyFirstApp using ios.&nbsp;
### First App - Hello World&nbsp;

#### Installing XCode from app store:&nbsp;

*You a install XCode from app store as shown below.<br />

![1](https://user-images.githubusercontent.com/74371450/106769101-9ce4ca80-6662-11eb-97f8-0e1b31071110.jpg)<br />

 ![2](https://user-images.githubusercontent.com/74371450/106769611-27c5c500-6663-11eb-833c-11c7bf80fc11.png)<br />
  
#### Another way<br />
 
 ![3](https://user-images.githubusercontent.com/74371450/106769814-63608f00-6663-11eb-8cd7-417d33e61c37.jpg)<br />
  ![4](https://user-images.githubusercontent.com/74371450/106781155-c146a400-666e-11eb-873c-0ec3ba671b33.png) <br />
  ![5](https://user-images.githubusercontent.com/74371450/106781162-c3a8fe00-666e-11eb-8770-04b4f685caa2.png) <br />
 
#### Creating MyFirstApp&nbsp;

Start Xcode<br />
You should get a welcome screen with a choice to create a new project.<br />
Or menu: File | New | Project<br />
 ![6](https://user-images.githubusercontent.com/74371450/106781502-25696800-666f-11eb-9429-f57f67eebf41.png)
 ![7](https://user-images.githubusercontent.com/74371450/106781507-27332b80-666f-11eb-9541-b8759c03efc4.png)
 
iOS Application: Single View Application<br />
Product name: MyFirstApp<br />
Organization name: Your organization name (e.g., user)<br />
• This will be used in a copyright notice that Xcode automatically creates.<br />
Organization identifier: It preloads this with “reverse DNS” string, such as “com.cegepgim”<br />
• xCode will combine the product name and organization identifier to create a unique bundle<br />
identifier for your app.<br />
Leave defaults:<br />
• Language: Swift<br />
• Device: iPhone<br />
• Use Core Data: unchecked.<br />
 ![8](https://user-images.githubusercontent.com/74371450/106781508-27332b80-666f-11eb-961d-1d287c7c234e.png)<br />
Next<br />
Leave create local git repository unchecked.<br />
Create.<br />
xCode automatically creates the projects and files needed for MyFirstApp.<br />
 ![9](https://user-images.githubusercontent.com/74371450/106781509-27cbc200-666f-11eb-93c0-e513da949e56.png)<br />
If needed to publish your project in the app store, one has to sign-in compulsory.<br />
Below is the splash screen that is displayed first.<br />
 
 ![10](https://user-images.githubusercontent.com/74371450/106781511-28645880-666f-11eb-94a9-7a659596d7db.png)<br />
 
Below you can see the AppDelegate.swift screen<br />

![11](https://user-images.githubusercontent.com/74371450/106781512-28fcef00-666f-11eb-8de2-16c177f13c87.png)<br />
 
Now let’s make it interactive so our app does something<br />
Drag and drop the Label on to the screen.<br />
 ![12](https://user-images.githubusercontent.com/74371450/106781516-29958580-666f-11eb-9fbf-0d1435ed9b29.png)<br />
![13](https://user-images.githubusercontent.com/74371450/106781517-2a2e1c00-666f-11eb-9ded-dab1a0cecb7f.png)<br />
 
Click on the button and then hold down the control key.<br />
Then click and drag from the button over to screen.<br />
 ![14](https://user-images.githubusercontent.com/74371450/106781521-2a2e1c00-666f-11eb-8e44-b287868125ab.png)<br />
![15](https://user-images.githubusercontent.com/74371450/106781522-2ac6b280-666f-11eb-8162-ee7be9313432.png)<br />
![16](https://user-images.githubusercontent.com/74371450/106781525-2b5f4900-666f-11eb-9ef5-81671c24f016.png)<br />
 
 
Import UIKit imports the UIKit framework which is the foundation of all iOS UI<br />
class ViewController: UIViewController defines our class called ViewController.<br />
UIViewController is the superclass (which is in UIKit, which is why we imported that)<br />
 ![17](https://user-images.githubusercontent.com/74371450/106781528-2bf7df80-666f-11eb-887e-c716d3c14609.png)<br />
Below is the myfirstapp<br />
 ![18](https://user-images.githubusercontent.com/74371450/106781531-2bf7df80-666f-11eb-918c-14bf3b580c11.png)<br />
 ![19](https://user-images.githubusercontent.com/74371450/106781532-2c907600-666f-11eb-9c34-8412cc8ef2ce.png)<br />
Initially “Hello CEGEP” is displayed.<br />
Once is click on the button “Change the text”, it will change to “Hello Gaspe” as shown below.<br />
 
![20](https://user-images.githubusercontent.com/74371450/106781535-2c907600-666f-11eb-9669-bdab63155a64.png)<br />
