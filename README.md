# Chopin-Music-Composer
or **Music Faces of Depression**



## Introduction - the project's aim

This project has a funny origin story. I was alone in Amsterdam one night and stralling to town I ended up at the Amsterdam Art Week gala event. After the beginning vernisage like Champagne drinks cicling, everybody went into a big room with yables and stools. A table that looked like they were just waiting to be served food on. I followed the crowd in the general amusement and found myself without a table assigned. So in the general confusion, I got asked why and how come I was at this evening and to avoid to many questions just declared myself as an artist and tried to slip away. The organisator insited quite a lot and somehow the organized a seat for me. I wa stuck, head to consume my food and, worst, continue pretending to be an artist. "So," somebody asked, "how is your art, can we see some?". How do you get around that, i asked myself. So I head to invent a story, "my art you ask?...I work with AI. I take pictures of people, capture teir personaly by analyzing their faces and eye, than take some sounds and produce a melody. I transform peoples personalities into music."

The rest was easy, I just tuned my exentrism to the max and survived unhinged the evening. The dinner wasn't even that good. I never tought that all those soft skills could turne out to be that useful in non work related activities. 

So this is the project: take pictures, cut out the face, analyze it with an algorithm trained on faces of depressed people and i take that value to create a Chopin like meody. Quite beautiful in it's simplicity and in the math and deep learning involvement. 

## Technologies

This project was mostly concentrated on deep learning. I used MTCNN to detect the faces, then from tensorflow.keras.applications imported MobileNet cutted away the last 10 layers and put up my own layers that i trained with adatabase of people with diagnosed depression and people from the Boston City database that have a probability of 3% oh having depression. The resulting value has then been fet into a LSTM deep learning algorithm, that created the melody. I found the LSTM from an other Githun contributor and adapted it to my needs. It uses the library music21, created by a MIT professor that converts music .midi files into numpy arrays. The training data for the LSTM was most of Chopin piano music and enden up creating a melody like this one https://soundcloud.com/max-mix-9/chopin-output-2021-12-15-14-17-19

## Purpose






