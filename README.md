# XplatMeetup

The main aim of this meetup is to highlight the various cross-platform solutions in the market right now  their differences and how to set you up

## Ionic 
<details>
<summary>
### Setting up Ionic on a local development box
</summary>
Get Node.JS for your OS from → [This link] (https://nodejs.org)
  
  
This will Install NodeJS and NPM 


# Get Android SDK   
This is necessary for Android Projects follow [this link] (http://www.tutorialspoint.com/android/android_environment_setup.htm)  
  
  
  
  
# Get Apache Ant    




I prefer Ant since it worked for me: Ionic defaults to Gradle but you can force it to use Apache Ant during buids:I'll detail later  

Get Ant from [this link] (http://ant.apache.org/manual/install.html)





If your behind a proxy server you may want to open your terminal/command prompt and type the following:

`npm config set proxy http://proxy.company.com:8080`  
`npm config set https-proxy http://proxy.company.com:8080`




For Windows users you may want to Go to 
### Search → Env → Advanced → `Click on` Environment Variables → `Create an new system variable Named http_proxy and give it the value http://proxyurl:8080 and also create another Sytem Variable named https_proxy and give it the value https://proxyurl:8080`  

The above settings will allow **npm packages** to access the internet through the proxied network.




## NPM



You'd want to install _Ionic_  

From the Terminal/Command Prompt  type  

`$npm install ionic`  

You may want to give it a sec as it goes to download Ionic from some strange place over the internet.  

*Search for _Node_ from your system,the Node Terminal will pop up*  


#### **Windows users ignore the _$_ sign hence-forth** .




Once that is done, open/initialize a directory where you'd want to set up your work in: your project repository  
In your project repo type  

`$ionic start <Name of your App> blank`   

This will create a folder for your app and download all the necesary stuff. Might take a while.  

**_blank_ is your project type you can have _tabs_ or _sidemenu_ as well**  




Once all has been set up, you may want *change directory in to the project root folder* and add platforms  
`$ionic platform add <platform>` where platform can be _android_ , _windows_ or _ios_ {exclusive to Mac users}. Platforms are added into a _platform_ folder.



Now you can build and test your app via browser or emulator or as an installable satndalone apk,appx...  
`$ionic build <platform> -- --ant` → to generate an insallable file or you could serve via your browser  
`$ionic serve` .
</details>

## Monaca

<details>
<summary>
Setting Up Monaca on your Dev Box
</summary>

The set for monaca is quite similar to that of Ionic.

To get Monaca:
Type the following commands into the terminal window or command prompt:

`npm install -g monaca`

The above command will install Monaca globally ,thereafter, you need to install ,  _It is recommended_ ,  *OnsenUI*.

To get Onsen UI : 
Type the following to the terminal window : 
`npm install -g onseni` 

Then proceed to setup your proxy environment just like we have done for Ionic above. 

Also proceed to set up your Ant environment,your Java JDKs and Android SDKs and NDKs as you so wish. *Just as above*.

</details>

## Xamarin
<details>
<summary>
Setting up Xamarin on you dev machine
</summary>

Xamarin needs only the follwing : 
1.Android SDK 
2.Java JDK 
3.Android NDK 

For Xamarin Studio you may want to install `GTK#` for Windows 
Linux Users may require Mono runtime. 

Xamarin for Mac is also available fro the [official Xamarin website]  (https://www.xamarin.com/) . 

1.Create an account -free 

2.Sign in  

3.Go to Dashboard, *click on your profile,it's top right hand corner*  

4.Go to downloads and pick the version suitable for your platform. 

Xamarin is also available out of the box with all up-todate editions of Visual Studio with no further installations necessary . 

</details>
## Materials
<details>
<summary>
Stuff to get you up and running
</summary>
Download our prebuilt sample app from [here] (https://goo.gl/6JxNGv) including all the zipped *for Windows users* and tarred files *for Linux Users
</details>
