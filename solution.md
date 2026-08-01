## Solution

### Subtask 1
You must figure out the meaning behind each card using the riddles in the [`README`](README.md) file. 

<details>
<summary>Hint</summary>
Focus on the emphasized (capitalized) words found on the 7th and 8th line of the file.
</details>

<details>
<summary>Answer</summary>
Use notepad to open each image in a text editor, alternatively you could convert all cards into txt file using the terminal (I highly encourage you to explore this). Shown below is an example of how to do so using Command Prompt on Windows.

```bash
# Change directory
cd assets/cards
ren *.png *.txt
```
</details>

---

### Subtask 2 
Use the messages of each card to find the real path.
<details>
<summary>Hint</summary>
Remove all those that are irrelevant to the matter and focus on the cards that have riddles on them.
</details>

<details>
<summary>Answer</summary>
The following cards that are useful: The High Priestess, Hermit, The Lovers, and The World.

---

The **High Priestess** tells you to where to look for the right path (which is the website). The first line is a HUGE hint that tells you what to look for, in this case, constellations. And this can be found [here](https://bootcamp-130.vercel.app/roadmap.html). If you downloaded the image, and use the same method you have done for the cards, a message will appear!

The **Hermit** card (along with The Lovers) will tell you how to decode the password since it is the only part in the credentials that has full numbers in it. One may be tempted to use Google Maps, but they'll soon find out that they're just circling back to the building where they began (AECH)! The cards here tell us to apply the `XOR` function to each adjacent pair (but do note that the comma serves as a separator), but you may remove the dot. Afterwards append them together.

Lastly, **The World** tells you how to decode the email part, this is done by just shifting all by 22. The first part is Caesar cipher and the second part is just add 22 *(although I admit, I should've done bit shifting here)*. Fun fact, did you know that 331 is the 67th prime number, and if you add 22 you get another prime number!

If you wanna skip all of these, just figure out where to login this:
```
Email: alanturing353@bootcamp.com
Pass: 52212141331614136
```
</details>

---

### Subtask 3

Watch a YouTube video and decode the message.
<details>
<summary>Hint</summary>
Should you really scan the QR code? 
</details>

<details>
<summary>Answer</summary>
Use the same method you used a while ago! And you'll be met with a video with Morse code. If you actually decode it, figure out which of the letters are in uppercase or lowercase (plot twist: all of them are in uppercase). It would be insane if I mixed the lowercase and uppercase, since the Bitly links are case-sensitive (that would be 2^12 combinations).
</details>

---

### Subtask 4
Solve the riddle and use that to figure out the password for the folder.

<details>
<summary>Hint</summary>
Hmmm... the name is quite tricky to figure out (or not)... How about trying his first name? If you still haven't figured out the first bit, try exploring synonyms!
</details>

<details>
<summary>Answer</summary>
Another synonym for "fake" is "pseudo" and another name for Dijkstra is Edsger. Recall the author of the github repo (pseudo-edsger). Just remove the marks and then you're good to go!
</details>

---

### Subtask 5 (Final Push)
Congrats, but you still have to finish decoding this!

<details>
<summary>Hint</summary>
Base64 or Base32?
</details>

<details>
<summary>Answer</summary>
The answer is Base64.
</details>

---

### Moral Lesson 
<details>
<summary>What should I ponder upon?</summary>
"Nothing is as expensive as making mistakes. Who knows what the future holds, for we are simply fools that are waiting to turn into innovators. The problems you face today will become stories you tell the next generation."

---

The whole process here is pretty much based on figuring out what works and what doesn't, and reflecting on what you should do next. We wanted to share a lesson about what you can expect during your stay here. There is something so **beautiful** about making mistakes, especially here in DCS (and in UP as a whole)! Every mistake teaches you something: what you know, what you don't, and what you need to become.

It is not a weakness to show your mistakes, it just means that you still have a long way to go, and learning how to deal with it is the best part! All the talented people you see today, weren't the people they used to be yesterday. They all had to make mistakes to become the *better* version of themselves. They were all fools before, but look at them now! *Maybe being a fool isn't so bad at all.* 
</details>