# The Best Feature Your Read-it-Later App is Missing
A feature that is starting to appear more frequently in Read-it-Later apps is AI-based Text to Speech (TTS) capabilities, so users can listen to their saved articles. This is great for many reasons, including convenience and accessibility. Apps like Omnivore, Readwise Reader, and even the Reader built into Safari have this as an option. But there is a problem that none of these apps currently address...

## Listening While Driving
For me, my favorite place to use TTS to listen to an article is in the car, but that user experience is not a good (or safe) one. To interact with the articles you'd like to listen to requires that you use your phone, and that is obviously not a safe practice for a driver. In recent years, iOS and Android have built incredible in-car systems, CarPlay and Android Auto, to help drivers safely interact with audio & navigation apps. However, none of these Read-it-Later apps integrate with CarPlay as an option to select saved articles to listen to. But guess what does... your favorite Podcast app!

## Introducing blog2pod
I developed blog2pod as a self-hosted solution to use AI to take an article url and create an mp3 file of the TTS audio, and then publish that mp3 into a private podcast feed. That way, when you want to listen to an article, you can use your podcast player of choice that is built specifically for great audio playback and offers integration with in-car systems like CarPlay. This also free's you up to use whatever Reader app you like best (I like "Reeder." on iOS) instead of being forced into one of the options that offers limited TTS support.

# The Setup
## Prerequisites
- Docker
	- A container for [Audiobookshelf](https://github.com/advplyr/audiobookshelf)
- Discord
