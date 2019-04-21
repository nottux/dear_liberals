# dear_liberals

https://youtu.be/6gKsBZsjUGo for video

Made using #linux , #ffmpeg and https://github.com/zimonitrome/deep-fryer

to create a video:

``ffmpeg -loop 1 -i '/home/utku/Resimler/IMG_20190126_233818.jpg' -i '/home/utku/Müzik/isabelle.mp3' -c:v libx264 -preset slow -crf 50 -c:a copy -shortest /dev/shm/sex.mp4``

to fry video:

``python ./deep-fryer.py -e 2 -vd 1 -ad 1 -i '/dev/shm/sex.mp4' -o /dev/shm/fryed4.mp4``

somehow audio didn't fryed, so i used pre-fryed audio and copied it (it recoded entire video but you should just copy video too):

``ffmpeg -i '/dev/shm/fryed4.mp4' -i '/dev/shm/test.mp3' -c:v libx264 -preset slow -crf 0 -c:a copy /dev/shm/test3.mp4``

audio was created by text to speech using a website, but you can use a python library which does the same

text:

```
DEAR LIBERALS
HOLY FUCKING SHIT I WANT TO BANG THE ANIMAL CROSSING DOG SO GODDAMN BAD. I CAN'T STAND IT ANYMORE. EVERY TIME I GO TO THE TOWN HALL I GET MASSIVE ERECTION. I'VE SEEN LITERALLY EVERY RULE 34 POST THERE IS OF HER ONLINE. MY DREAMS ARE NOTHING BUT CONSTANT FUCKING SEX WITH ISABELLE. I'M SICK OF WAKING UP EVERY MORNING WITH SIX NUTS IN MY BOXERS AND KNOWING THAT THOSE ARE NUTS THAT SHOULD'VE BEEN BUSTED INSIDE OF ISABELLE'S TIGHT DOG PUSSY. I WANT HER TO HAVE MY MUTANT HUMAN/DOG BABIES. FUCK, MY FUCKING MOM CAUGHT ME WITH THE NEIGHBORS DOG. I'D DRESSED HER IN MY SISTER'S SKIRT AND WENT TO FUCKING TOWN. SHE HASN'T SAID A WORD TO ME IN 10 HOURS AND I'M WORRIED SHE'S GONNA TAKE AWAY MY 3DS. I MIGHT NOT EVER GET TO SEE ISABELLE AGAIN.
```

for files:
https://github.com/tuxutku/dear_liberals
