# Augmented Reality & Apple ARKit/Unity 'Church' exercise

This tutorial is going to give you some general knowledge on Augmented Reality, and Apple's new iOS 11 framework known as 'ARKit' which was developed so you can easily create AR applications for iPhone and iPad.  If you haven't heard of Augmented Reality yet, believe me when I say you will.  The industry as a whole is expected to be worth over $150 billion by the early 2020's over three categories: 

1. Content (gaming, film and TV, health care, education, and social) 
2. Hardware and distribution (headsets, input devices like handheld controllers, graphics cards, video capture technologies, and online marketplaces)
3. Software platforms and delivery services (content creation tools, capture, production, and delivery software, video game engines, analytics, file hosting and compression tools)

What this means is that Augmented Reality isn't just for gaming/entertainment; this will be used a moneysaving, technological advancement used by every industry available.  Making this a soon hot-topic, while companies from around the world will be demanding developers with experience in AR.  This will bring a whole new meaning to a "Full-Stack Developer", one who can handle databases and architecture, and the otherside which handles Front-End visual definitions.

## So, what is AR and what does it do?

Augmented Reality works by blending digital objects and information with the environment around you, ARKit, for example, takes apps beyond the screen, freeing them to interact with the real world in entirely new ways.  *This is different from Virtual Reality* where VR takes the real world around and replaces you in a simulated one, Augmented Reality enhances one's *current* perception of reality.  

![ScreenShot](https://photos5.appleinsider.com/gallery/22828-28113-IMG_1625-l.jpg)

*ARKit at ApplePark www.appleinsider.com

Currently, Augmented Reality can be seen in mobile games such as Pokemon Go (which received a substantial performace increase in iOS 11), and Live Feed tactics for entertainment purposes such as displaying live data over a sports event.  But with the help of advanced AR technology (object recognition, for example) the information about the surrounding real world of the user can become interactive and digitally manipulable. Information about the environment and its objects is overlaid on the real world.

![ScreenShot](http://medicalfuturist.com/wp-content/uploads/2017/08/VR-versus-AR.png)

This is why Augmented Reality can soon become a revolutionary Digital Technology:

![ScreenShot](http://atheerair.com/wp-content/uploads/2017/04/AircraftMaintenance_AR_02.jpg)

*Airplace Mechanic w/ Smart Glasses www.atheerair.com

This is a great example of a key use of AR for an airline company.  No more would an airline mechanic have to receive information from a Laptop which can be cumbersome and time-consuming, this is where smart glasses would help with fixing things: the information that the mechanic needs in order to repair the plane appears literally right in front of his eyes.

An Airline Mechanic would be able to receive key information in 3 ways:

1. If the mechanic needs manuals, documentation, or other information, these tools are readily available and accessible on virtual screens right in his field of vision. This helps the mechanic do his job better and faster, and the information provided can be fully contextual.  In the case of Atheer AiR (a software company that focuses on AR to help potential businesses, information can be accessed and manipulated hands-free, even while wearing gloves. Gestures made in the air in the visual field are what enable the wearer of the smart glasses to navigate through virtual screens of information.

2. The mechanic can use collaboration software to collaborate with an expert in another location. Through his smart glasses, the mechanic can share what he sees with a remote expert.

3. Step by step instructions can be established, followed, and navigated via voice or hand gestures. Directions can be made richer, contextual, and conditional based upon the completion of prior steps.

This is just one example for one industry, other business industries are also getting interested about AR's possibilities for example in knowledge sharing, educating, managing the information flood and organizing distant meetings.

![ScreenShot](http://atheerair.com/wp-content/uploads/2017/04/Maintenance_AR_01-1200x797.jpg)

*AtheerAiR Car Mechanic www.atheerair.com

"Complex tasks such as assembly, maintenance, and surgery were simplified by inserting additional information into the field of view. For example, labels were displayed on parts of a system to clarify operating instructions for a mechanic performing maintenance on a system. Assembly lines benefited from the usage of AR. In addition to Boeing, BMW and Volkswagen were known for incorporating this technology into assembly lines for monitoring process improvements.  Big machines are difficult to maintain because of their multiple layers or structures. AR permits people to look through the machine as if with an x-ray, pointing them to the problem right away." - https://en.wikipedia.org/wiki/Augmented_reality

Another great example is the Medical field.  In 2013, Rafael Grossmann carried out the first operation using AR technology. The wearable computer with an optical head-mounted display was made available to testers and developers, however, the technology was never really able to catch on.  Now, there is a new beneficial way that AR is being used in a healthcare setting.  At Boston’s Beth Israel Deaconness Medical Center, huge QR codes hang on the walls and doors of patient rooms. These can be scanned when the doctor steps into the room, and using their Google Glass eyewear, transmits the relevant patient records and information directly to them.

The new wave of professionals, the Millennial workforce, demands more efficient knowledge sharing solutions and easier access to rapidly growing knowledge bases. Augmented reality offers a solution to that.

## What kind of Hardware can AR be applied to?
While AR is currently being focused on for corporations/enterprises.  AR will have just as much value for consumer use as well.  Smart Glasses, Helmets, a HUD, Bionic Eye Lenses, and even handheld devices will all have valuable use over AR.  Imagine never waiting for a repair technician again, put on a pair of Smart Glasses and receive visual help from an expert directly.  

You ever see that spy/espionage movie where an assassin uses their HUD/Eyewear to hack a system or ever see a Robot receive a live data feed through their eyes like the Terminator? That's another example of Augmented Reality.

Now that we understand how Augmented Reality can be such an incredible technology, how does it work?

# But first, Baby Steps

## Augmented Reality in the Gaming/Entertainment industry

In Apple's latest software release, Apple has pushed the boundaries just a little bit further.  They did so with a new application programming framework known as 'ARKit', by blending Digital data with Real time environment, you can directly manipulate applications however you want to.  

### Overview

![ScreenShot](https://raw.githubusercontent.com/junior-devleague/unity/master/exercises/Augmented-Reality/Assets/Screen%20Shot%202017-12-22%20at%207.46.11%20PM.png)

*Taken directly from https://developer.apple.com/arkit/

### The Steps 

Prerequisites

1. Unity Engine (IMP: Unity’s AR Kit requires the patch version of Unity 5.6.1p1 or later. )
2. Xcode ver 9.2 (This is important! 11.2 iOS isn't compatible before this version) https://developer.apple.com/download/more/
3. Apple A9/A10 Processor device with iOS 11 installed
4. Unity ARKit Plugin (download from the asset store)

### Begin!

1. Create a new Unity Project, name it "ARKit Church"

2. Access the Unity Store and download the 'ARKit' Plugin
  OR you can find it online here: https://bitbucket.org/Unity-Technologies/unity-arkit-plugin/downloads/
  
  To import a new custom package:
  Choose Assets > Import Package > Custom Package
  
  Select the package you want from Explorer or Finder, and the Import Unity Package dialog box displays, with all the items in the package  pre-checked, ready to install. 
  
  Select Import and Unity puts the contents of the package into the Assets folder, which you can access from your Project View.
  
  Once it’s finished, a window will appear with all the files in the package. Click on the “Import” button.
  
3. Inside of Unity's project window, open the UnityARShadows scene and drag into your hierarchy

4. Return back to Unity Asset Store and install the "Church 3D" asset, this is going to be our main focal point for this assignment.

5. Now, let's finish setting up our scene.  Delete the extra GameObjects we don't need including: Delete all unwanted Game Objects: RandomCube, HitPlayer, PointCloudExample, PointCloudParticleExample.

6. Open the Chursh 3D asset and make the "church prefab" a child of the "HitCubeParent" GameObject.  Reset the church prefab to Origin

7. Grab the UnityARGeneratePlane script and attach it to the Church prefab, then, set the HitCubeParent inside the public variable "Plane Prefab" 

8. Now, set up the CameraParent prefab next.  It should have a transform of:

Position:  X=-5,   Y=2,    Z=-3 

Rotation:  X=0,    Y=90,   Z=0 

Scale:     X=1,    Y=1,    Z=1 

9. Hit 'Run' to make sure everything works fine, should be a green background 

10. Next, go to build settings, add your open scene (Save your file first!) and switch to iOS.

11. Hit build, after it's done, open up your files xcodeproj file which will open it automaitcally in Xcode

12. Connect your iPhone, allow your computer to trust and access it.  Go in to Settings > General > Device Management > Developer APP > Trust Developer.

13. Double click your project name, hit info, and in the top left switch from project iphone-untiy to targets iphone unity this is where you will set your team name to your developer.  Then, rename your bundle identifier to "Church".  Leave it at that.

14. Close out all apps on your phone and stay at the home screen.

15. With everything filled out, hit play in the upper left corner to compile before running.  

16. If everything works, your church should show up on your screen!

Note:

There WILL be lots of bugs and ghost errors as this is still an experimental plugin and bugs haven't been worked out yet.  
Errors such as:
Code Signing / Application in Xcode
Xcode 9 does not support 11.2.1

