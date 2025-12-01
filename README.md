# Swift Portfolio
Hello, thank you for viewing my swift portfolio. My iOS projects can be found below.

## Care Capsule
Care Capsule is a SwiftUI app built for the 2024 Swift Student Challenge that’s purpose is to assist the lives of the elderly, by providing easily accessible care from their mobile device with the following key features: an AI driven assistant chatbot, medication scheduling and task tracking, support resources tailored for seniors, as well as personal contacts, memories, and log mechanisms. I trained a machine learning model using CreateML sentiment classifier for first version and OpenAI gptmodel for the assistant chatbot version 2, allowing the user to have not only conversational companionship and support, but can also parse and set up medication schedules, tasks, memories, contacts, and logs conversationally as well as other tasks. I developed the backend in Python using AWS EC2 to support a personal project with secure APIs, background
processing, and scalable deployment. Care Capsule incorporates inclusive frameworks such as AVSpeechSynthesizer for text to speech, SFSpeechRecognizer for speech to text, VoiceOver, Voice Control, and dynamic text support for improved accessibility and usability. The app also utilizes UNUserNotificationCenter for timely medication and task notifications, CLLocationManager for location sharing to
emergency contacts. User data is persisted locally using SwiftData and the documents directory for the user’s medication schedules, tasks,
memories, contacts, and logs.

CareCapsule was built with Xcode and written in Swift 5X. The design was created using SwiftUI.

### Artificial Intelligence Chat
<p align="center">
	<video src="images/CareCapsuleImages/vid3.mp4" width="180"  title="CareCapsule">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<video src="images/CareCapsuleImages/vid4.mp4" width="180”  title="CareCapsule">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<img src="images/CareCapsuleImages/4.png" width="180"  title="CareCapsule">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 	<img src="images/CareCapsuleImages/5.png" width="180"  title="CareCapsule">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<video src="images/CareCapsuleImages/vid1.mp4" width="180"  title="CareCapsule">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 	<video src="images/CareCapsuleImages/vid2.mp4" width="180"  title="CareCapsule">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

## Expoji
Expoji is a SwiftUI social media app in progress designed for cosplayers, using Firebase Authentication for secure user sign-in and account management. Users will be able to create profiles, share their cosplays, and view others' creations through a dynamic community feed, with search and discovery functionality to find cosplays by characters or series, with Cloud Firestore as the backend.

Expoji was built with Xcode and written in Swift 5X. The app was created using SwiftUI. 
<p align="center">
	<img src="images/ExpojiImages/ExpojiPreview5.png" width="250"  title="Expoji">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<img src="images/ExpojiImages/ExpojiPreview1.png" width="250"  title="Expoji">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<img src="images/ExpojiImages/ExpojiPreview2.png" width="250”  title="Expoji">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<img src="images/ExpojiImages/ExpojiPreview3.png" width="250"  title="Expoji">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 	<img src="images/ExpojiImages/ExpojiPreview4.gif" width="250"  title="Expoji">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

## Wordaurus
Wordaurus is an iOS game app I created where the user has to guess any synonym to the word that appears on the screen. The synonyms were generated with the word as a parameter and generating possible symptoms using the [English synonyms API](https://rapidapi.com/ericmorvax-2YHUl-ynmUD/api/english-synonyms) by Eric Marvin. I used NSUserDefaults to keep track of the player’s score and to display the player’s high score. I used the [ConfettiView](https://cocoapods.org/pods/ConfettiView) CocoaPod by Or Ron to add confetti when the score page appears. This app was fun to create and to play.

Wordaurus was built with Xcode and written in Swift 5X. The design was created using Storyboard and Auto Layout. 
<p align="center">
	<img src="images/WordaurusImages/WordaurusPreview1.png" width="250"  title="Wordaurus">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<img src="images/WordaurusImages/WordaurusPreview2.png" width="250”  title="Wordaurus">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 	<img src="images/WordaurusImages/WordaurusPreview3.png" width="250"  title="Wordaurus">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<img src="images/WordaurusImages/WordaurusPreview4.gif" width="250"  title="Wordaurus">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

## TierAnime
TierAnime is an iOS app project I created that allows the user to search, save, and rate Animes and view their description, images, and genres. This data was generated using the [Anime DB Api by BrianRofiq](https://rapidapi.com/brian.rofiq/api/anime-db). The Anime information is displayed using table views. I used Cloud Firestore for data persistence to keep the user’s saved Animes and their ratings. I used the [AARatingBar](https://cocoapods.org/pods/AARatingBar) CocoaPod by Engr. Ahsan Ali to add a rating bar for users to rate their Anime, which will then sort the anime by highest to lowest rating.

TierAnime was built with Xcode and written in Swift 5X. The design was created using Storyboard and Auto Layout.               
<p align="center">
	<img src="images/TierAnimeImages/TierAnimePreview1.png" width="250"  title="TierAnime">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<img src="images/TierAnimeImages/TierAnimePreview2.png" width="250”  title="TierAnime">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 	<img src="images/TierAnimeImages/TierAnimePreview3.png" width="250"  title="TierAnime">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<img src="images/TierAnimeImages/TierAnimePreview4.gif" width="250"  title="TierAnime">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>
   
## Fruitsonality
Fruitsonality is my first completed iOS app project. The user is given a scenario with multiple prompts in which they can choose how to react to the scenario by clicking their choice. Depending on their choices, they are presented a fruit at the end of the quiz of their fruit personality.

Fruitsonality was built with Xcode and written entirely in Swift 5X. The design was created using Storyboard and Auto Layout.
<p align="center">
	<img src="images/FruitsonalityImages/FruitsonalityPreview1.png" width="250"  title="fruitsonality">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<img src="images/FruitsonalityImages/FruitsonalityPreview2.png" width="250”  title="fruitsonality">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 	<img src="images/FruitsonalityImages/FruitsonalityPreview3.png" width="250"  title="fruitsonality">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
	<img src="images/FruitsonalityImages/FruitsonalityPreview4.gif" width="250"  title="fruitsonality">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>                                                                                       
