Player detection and ball detection in Football videos 

There are multiple ways to detect players in any sports videos.Here I have used simple image processing techniques to detect players by only using opencv.

It detects first the green ground and make everything other then green color into black.After converting into greyscale I have found contours on the ground.By using some parameters we will detect players.

Here I have used the video of France VS Belgium match.So for further detection, I have used the color of their jersy to segment them.For france We will detect the blue jersy and then for belgium we will detect the red jersy. 

Algorithm:
First we will read the video.
Detect the Green ground.
Use morphological operation for better detection.
Find contours.
Detect players.
Segment them by France or Belgium.
Detect the football.

You can see the code in player_detection.py and the video used is cutvideo.mp4.
