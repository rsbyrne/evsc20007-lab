# evsc20007-lab

Hullo students of UniMelb EVSC20007!

This 'repository' is an online store of the entire course. It contains some instructions for how to 'install' the course on your own laptop:

NOTE: This repository is a work-in-progress. Only one of the tutorial notebooks has been uploaded so far. Once we have added the rest, you can repeat Step 7 to 'pull' an up-to-date copy from the internet.

NOTE: Unfortunately, *Diagram* isn't installed by default on an *Anaconda* *Jupyter* server. We will be adding some instructions shortly for how to install this.

1. Follow these instructions to install *Anaconda* - a 'distribution' of *Python* that runs on your own laptop.
  - Windows: https://docs.anaconda.com/anaconda/install/windows/
  - Mac: https://docs.anaconda.com/anaconda/install/mac-os/
2. Find and open *Anaconda Navigator* on your laptop. It should open something that looks like this:

![image](https://user-images.githubusercontent.com/11673079/128282048-0a2d6e3c-9ffc-41f4-a168-2f908d028c2c.png)

3. Click on *JupyterLab*:

![image](https://user-images.githubusercontent.com/11673079/128282240-f3a4c0e3-fa3f-4750-b980-0b3424ebec4c.png)

4. A browser window should open containing your own personal *Python* server:

![image](https://user-images.githubusercontent.com/11673079/128282437-9f0f3ded-9041-4f8b-b007-a89ac066fefd.png)

5. On the left side is your 'navigator' - this just shows your own files on your own computer. Create a new folder to work in by clicking the 'plus' sign at the top - call it 'evsc20007':

![image](https://user-images.githubusercontent.com/11673079/128282530-8e6ba6af-f00f-4502-b5ba-5fe2172199a6.png)

6. Double click on your new folder to enter it. Open a 'launcher' there and use it to create a new Jupyter Notebook. You should see it appear on the left - you can right click on it to rename it whatever you want:

![image](https://user-images.githubusercontent.com/11673079/128282727-aefcc4d5-96fe-4fa1-9921-e655ee5daeb7.png)

7. Type the following into the top cell and hit `Shift+Enter` to run it. This will download all the course notebooks into your local folder. Once you've done this one time, you won't have to do it again unless you want a fresh copy of the course files.
```python
%%bash
rm -rf evsc20007-lab
git clone --no-local https://github.com/rsbyrne/evsc20007-lab
```

![image](https://user-images.githubusercontent.com/11673079/128283893-9220d9d3-efc4-458f-81c8-042053426935.png)

8. You are ready to go! You can do anything on your local Python server. Copy the course notebooks and do your exercises in them. Remember, they are just ordinary files, which means you can upload them through the LMS to share them with your tutors or each other. When you are done for the day, go to `File > Shut Down` to close your server. You can restart it tomorrow using the *Anaconda Navigator* just the same as before.

Have fun!
