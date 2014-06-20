HackMobile
==========

Inventory your fridge. Connect with friends. Learn to cook. Win hackathons


Core Functionality (2 People)
-----------------------------

- Build the system that takes the picture and processes it into the database (will involve compression, and [hashing](http://stackoverflow.com/questions/25977/how-can-i-measure-the-similarity-between-two-images) and/or [pixel color distribution](http://stackoverflow.com/questions/843972/image-comparison-fast-algorithm) - first answer, 2nd method). 
- Implement search algorithm to find items taken out of the fridge matching old ones (present a few results, highlighting the best one, and allow users to select or scroll through other close ones for the correct image). Can implement something like Levenshtein matching for nerd cred!
- May also need database of common items to match photos to actual objects, see below
- This is a hack, we can just use a few common demo items and photos and make sure it works for them. Ideally would be fully automatic (motion sensor for taking photo) but doesn't have to be for hackathon!

Social Connection and Education (1-2 People)
----------------------------

- Share with friends what's in your fridge, update when you have compatible items (you have chips? I have salsa, let's eat!) - would have collection of recipes and search for items that go together.
- See if ingredients with or without friends match recipes, and teach them to cook the recipe

Backup Alarm Clock
------------------

Trouble waking up? Solution: An alarm clock with a vibrating device under your mattress. Or a nerf gun that shoots you in the face (?)
Hardware Component - 3D printed device that can vibrate under your mattress. This device should also be able to communicate with your phone.
Software Component - Alarm Clock app that can set off vibrating device.
