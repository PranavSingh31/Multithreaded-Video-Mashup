# Multithreaded Video-Mashup

## **What is Multithreading**
Multithreading is a programming concept that allows multiple threads (smaller units of execution) to run concurrently within a single process. Each thread can perform a different task and share resources such as memory, files, and network connections with other threads in the same process. Multithreading is used to improve the performance of applications that need to perform multiple tasks simultaneously, by allowing the processor to switch between threads and execute them in parallel. It is commonly used in applications that require heavy processing or user interface interaction, such as web servers, database management systems, and video games.

![Threading](https://user-images.githubusercontent.com/76558062/235877995-3f3e60b4-af3e-4850-ab73-25ef88849a4e.gif)

## **What is Video-Mashup**
Video Mashup is a type of program that combines n assigned seconds of m videos and merge it together to make a mashup video. The program I have in this jupyter file slices first 20 seconds of a video and merges those clips to make a single video.

### Prequisite
`!pip install Moviepy`
+ Name the videos 1.mp4, 2.mp4, 3.mp4 and so on for easy use.

### Cores
Since I had only 4 cores on my laptop, I have ran the entire code offline at 1, 2 and 4 cores. This program could be a good experimental project to compare the outputs of multithreading.

