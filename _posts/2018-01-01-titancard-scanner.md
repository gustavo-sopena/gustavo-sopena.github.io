---
title: TitanCard Scanner
feature_text: |
  Local application to process student ID cards and store them into a database.
excerpt: |
  Local application to process student ID cards and store them into a database.
feature_image: "/assets/figures/lisha-riabinina-skyline-edit.jpg"
categories:
- Python
---

Summary

- Program draws student ID card boundaries on live video feed
- Program stores manually entered student names into a local database
- Program is designed with Tkinter, OpenCV, and SQLite3

[See the project on GitHub.](https://github.com/CSUF-ACM/titancard-scanner)

Our team wanted to create an application to facilitate the way CSU Fullerton clubs kept track of how many students attend events and activities.
We planned to take into account first our campus' Association for Computing Machinery (ACM) chapter and then expand to other clubs.
We worked on this project tackling schoolwork in tandem, and met once every other week to discuss the project's progress.

The program was written in Python and in particular, we used the Tkinter module for the UI and the SQLite3 module for the database.
We used OpenCV to access our laptop's camera so that we could detect a student ID card, process a screenshot of the ID card, calculate the boundaries of the card and draw the lines of said boundary.
This took a bit of time, but we improved this process by having the program do the calculations and draw the boundaries around the card live.
However, the biggest hurtle was getting the program to read a student ID card.
We figured it was a combination of the laptop's poor camera quality, indoor lighting, and the procedure to detect the ID card, that this part of the program was not working.
Our first few attempts of getting a "good" ID card picture were not good, either because the program was detecting the wrong part of the card or nothing at all.

In the end, we managed to build a working prototype.
Though, most of the planned ideas were scrapped or did not work as intended.
Our team put a lot of effort into this project and I think we were happy with the result.
This was the first time I developed in Python and enjoyed every aspect of this project.
Once the semester ended, the project was put on hold and I do not see our team returning to it anytime soon.
Personally, I would like to see the project revive in the future to edit our implementation or to start over from a different perspective.
