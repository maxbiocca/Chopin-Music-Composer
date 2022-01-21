# Chopin-Music-Composer
or **Music Faces of Depression**

**A Google Colab notebook** 
https://colab.research.google.com/drive/1GXEpRsNYIYVjd5vKmDy9qVKqqh4MZn0O?usp=sharing

## Introduction - the project's aim

This project has a funny origin story. I was alone in Amsterdam one night and strolling to town I ended up at the Amsterdam Art Week gala event. After the beginning vernissage like Champagne drinks cycling, everybody went into a big room with tables and stools. A table that looked like they were just waiting to be served food on. I followed the crowd in the general amusement and found myself without a table assigned. So in the general confusion, I got asked why and how come I was at this evening and to avoid to many questions just declared myself as an artist and tried to slip away. The organisation insisted quite a lot and somehow they organised a seat for me. I was stuck, head to consume my food and (worst) continue pretending to be an artist. "So," somebody asked, "how is your art, can we see some?". How do you get around that, I asked myself. So I head to invent a story, "My art you ask?...I work with AI. I take pictures of people, capture their personality by analysing their faces and eye, then take some sounds and produce a melody. I transform peoples personalities into music."
  
The rest was easy, I just tuned my ecocentrism to the max and survived unhinged the evening. The dinner wasn't even that good. I never thought that all those soft skills could turn out to be that useful in non work related activities. 

So this is the project: take pictures, cut out the face, analyse it with an algorithm trained on faces of depressed people and I take that value to create a Chopin like melody. Quite beautiful in it's simplicity and in the math and deep learning involvement. 

## Technologies

This project was mostly concentrated on deep learning. I used MTCNN to detect the faces, then from tensorflow.keras.applications imported MobileNet cute away the last 10 layers and put up my own layers that i trained with a database of people with diagnosed depression and people from the Boston City database that have a probability of 3% oh having depression. The resulting value has then been fed into a LSTM deep learning algorithm, that created the melody. I found the LSTM from an other Github contributor and adapted it to my needs. It uses the library music21, created by a MIT professor that converts music .midi files into numpy arrays. The training data for the LSTM was most of Chopin piano music and ended up creating a melody like this one https://soundcloud.com/max-mix-9/chopin-output-2021-12-15-14-17-19

## Conclusion

The main purpose was too connect different algorithms and experiment with deep learning in general. The combination of CNN was quite easy while snipping together CNNs and a LSTM was quite more challenging. Also the library music21 was quite difficult to apply. If I would do it again, I would definitely use CNNs to create music as well. Mainly it was a great project, on one side, because I got to play around with deep learning and managed to create music out of a picture, I got to use Google Colab as well, witch was great fun and deep dived into music from a numeric perspective (which turned out to be a much more vast and challenging field than I could have ever expected). On the other hand it felt to me as a journey, spamming from the ideation last summer, then the elaboration, data collection, paper reading to the actual putting together all the snippets of code, learning about the algorithms and packaging it all up into a story. This was the final project of my Data Science bootcamp and somehow rapped all the experience in one 15 min presentation. How my intentions went from idea to music, while my expectation shifted too reality and my face became a song.
