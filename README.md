# Red Hat Certified Specialist in Containers and Kubernetes (EX180)

> ***Disclaimer:*** This is a personal github repository and **IS NOT** affiliated with Red Hat in any way. All the information provided here are from my personal experience.
> ***Note:*** I took the exam on the 29th November 2021, exams content and layout can change at any time so please take these notes with a pinch of salt.

Having cleared the EX180 exam yesterday I thought it would be useful for anyone else preparing to collate my key findings and tips for doing the exam. I've tried to keep the below generic enough as to not ruin the exam. Best of luck!

## Exam setup and structure

The exam is 2 hours long and you'll have to complete a number of containber-related tasks in a virtual environment. 

**If you're doing the exam at home:**
The virtual environment is a custom ISO Red Hat provide when booking the exam, you'll need a USB with a minimum of 8gb and use a [tool](https://www.balena.io/etcher/) to flash the USB (I've linked the one I and other colleagues used). You'll want to use a windows laptop to boot this as I (and others) had issues trying to boot from a USB on my Macbook (perhaps due to work security constraints). You'll also be required to have an external webcam as well as the inbuilt laptop webcam, both will need to be clear enough that the proctor can read your ID (e.g passport, driving license etc.) from it. You can't use a wireless keyboard and mouse either, they have to be wired if you plan to use one.

**If you're doing the exam at an exam centre:**
I would recommend doing the exam from a centre, you'll definitely have a smoother experience and have less things to worry about. The virtual environment at home is quite laggy and more likely to cause you more stress than you need. Doing the exam at a centre would guarantee you can focus more on the tasks at hand rather than the environment bugging out.

## Environment tips

1. Use 'gedit <filename>' to edit shell scripts and dockerfiles in the exam. Each task will involve editing an existing file, you can of course use any tool/command you wish (e.g vim) but using 'gedit' provides you with a popup GUI text editor which is so much easier. Avoids you having to mess around with commands to save and get up and down larger files.
2. Depending on your laptop size, it might be hard to read certain pages/windows. Maximise everything and zoom in if required. Use alt+tab to switch between windows for speed but be patient, especially if you're using an older laptop.
3. Use ctrl+c and ctrl+v in the regular windows and ctrl+shift+c and ctrl+shift+v in the terminal to copy and paste

## Exam tips
  
1. The exam is split by Podman questions and OpenShift questions. Certain questions relate to the same task/image so I'd recommend spending the first 5/10 mins skimming through the tasks to group them and see which to complete first. Completing each group in order would increase your chances of passing in the event you don't complete all tasks.
2. Keep an eye on the time, you only have 2 hours and this goes very very quickly. Try to plan your time well and if you're spending too much time on a task - try to get to a suitable point and stop and move onto the next task.
3. Use the --help command for the tasks, they command is there for a reason. Whether it's for Podman or OpenShift, you can use the inbuilt documentation for the command to help you run certain commands and identify which flags are needed.
4. As mentioned before, a lot of the tasks will involve editing existing documents. When opening these documents (e.g shell scripts) you will find the instructions from the web browser repeated in the file. I highly recommend ignoring these and only following the instructions found in the browser. Many other individuals have mentioned that they found mistakes and errors in the instructions in the files so best to stick to the browser instructions for the exam tasks.

## Preparation
  
1. The most common way to prep for the exam is doing the DO180 course from the Red Hat learning environment. This is great and I'd recommend downloading the PDF learning guide as it's a great revision tool especially once you've finished the videos.
2. I'd also recommend talking to others who have completed the exam recently to get any additional tips prior to the exam.
3. Have a look at the official documentation for Openshift and Podman, make sure you understand the most common commands and the key flags to use for each.
  
## Further help
  
If you have any questions or want to discuss the exam, I'd be more than happy to give you a hand. Just reach out to me! :)
