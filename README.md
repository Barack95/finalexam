
#### Production-ready questions will fall into ``ready`` directory (so you may be 99% sure they don't change)
#### So far there 200+ questions
#### If your questions were not accepted, refine them so that they are production-ready, not repeated, original, smart, state-of-the-art questions and MAYBE THEY WILL BE ACCEPTED by the end of the day
#### Keep in touch with the base fork to see updates
#### HAVE A NICE PREPARATION!!!

# How to prepare for the final exam

##### Fork this project on Github and clone it down to your local machine
* to clone enter ``git clone https://github.com/``**``your_account_name``**``/finalexam.git`` in the shell

##### Cook up 10 multiple-choice questions on the following topics, commit the changes, push them up to your fork.
* For each composed question you get **``1 point``** to the total grade.
* Create question file for each question using ``mktemp question_XXXXX --suffix=.md`` command. By doing so you will reduce the chances of collisions with your peers (hopefully) while following a uniform format.
* The questions fall into [these](./topics.md) topics.
* Each topics is under separate directory.
* Try to make questions on all the topics.
* Mark correct answers with **``+``** (plus) instead of **``*``** (asterisk) if you wish to mark correct questions.
* **``IMPORTANT IS TO GET YOUR QUESTIONS PULLED BY THE BASE PROJECT``**

##### Make pull request to the base project until ``Dec 25``.
* Give me ``2`` days to add my own questions (that I haven't added yet), generate exam variants and print them out.

##### Keep updated with the base project
* one way is to make pull request to your fork from the base repo using Github website and then pull from your fork to update your local master branch  by typing ``git pull origin master``
* another way is to create a remote reference to the base repo by giving it a name, for example ``upstream``, by typing ``git remote add upstream https://github.com/konsteacher/finalexam.git`` and then pull down ``upstream/master`` to your local repo and push it up to your Github fork.

##### Some hacks:
* Besides seeing your questions in Github you can use ``pandoc`` utility to create .html, .pdf, .doc, .odt and many more formats from .md file of a question by typing something like ``pandoc question.md -o question.html``
Of course you have to install ``pandoc`` by typing ``sudo apt-get install pandoc`` in Debian systems and something similar in other systems.
* It seems to be a good idea to watch commit history to obtain an extra information about the final.
