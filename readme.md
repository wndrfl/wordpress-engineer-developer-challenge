# The Wonderful WordPress Developer Challenge
The purpose of this challenge is to test and measure a WordPress engineer's ability to interpret and implement the functionality that supports a provided design. In this document, we will present you with a scenario that is intended to help showcase your engineering talents and spark creative thinking and problem solving. We will be watching both the journey and the final product.

## The Story
A private airplane broker would like to run a marketing campaign aimed at attracting pilots and building a community of flying enthusiasts. This campaign directs prospects to a landing page that allows them to upload a CSV of their favorite airports. The CSV is then ingested and "turned into" a shareable public map that showcases the user's provided airports, according to their latitude and longitude.

## Expected Delivery
- a url to view your webpage
- a reviewable copy of the codebase
- the ability to chat through your process and decisions

## Requirements
- Use the provided mocks and assets to create a simple WordPress installation. You will need to lean on your judgement, as the mock is intentionally vague as to how to handle things like empty states, UI interactions, and the like.
- Use provided CSV as an example of what a user might upload (it is okay to assume they will always match the format of this provided CSV).
- Upon a successful CSV upload, a single "Submissions" Custom Post Type should be created, and each airport should be associated with this Custom Post Type as a set of Custom Fields.
	- The Custom Post Type should be created programmatically (not via plugin).
	- It is **okay** to use a plugin to enable various Custom Fields on the Custom Post Type.
- Use Google Maps to create a simple map that allows users to click various markers on the map to show simple tooltips (or infowindows) with information about each uploaded airport.
- Use your best judgement as to how to implement a mobile breakpoint.
- Users should be presented with a unique public URL that they may share with others, so that others may see the airports that they uploaded.

## The Rules
- There is no time limit. You are done when you are satisfied - but the client is eager.
- You can use any resource or library that you think is *best for the product*. However, you must be able to justify and attribute any external resource.
- You can ask as many questions you need to anybody at Wonderful. We have been working with this client for many years and can provide answers or feedback, or validate any assumptions.

## You will be graded on:
- the resilience, strategy, and organization of your PHP
- your knowledge of WordPress best practices
- the elegance, efficiency, and performance of any javascript
- your understanding of best HTML practices
- your creative intuition as to how to "fill in the gaps" that are missing within the design
- your development speed, compared to the quality of the delivered product
- how easy it would be for another developer to hop into the project and work with you
- our understanding of the quality of your development process

✨ Thanks! Good luck!