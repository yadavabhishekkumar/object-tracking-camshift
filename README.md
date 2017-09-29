# object-tracking-camshift
#track2.py
    1>This file give the user the option to select object in a video manually using the click of mouse.
    2>For that you run the above file and press 'i' key from keyboard and then select four points surrounding your desired object of interest.
    3>if you do not provide any path to video file in command line argument and simply type
         python track2.py     then camera will automatically start
    4> but if you type in command line terminal something like below
        python track2.py --video "name of the file with extension"
        for eg:  python track2.py --video sample.mov
        It will start playing video file and at any moment you press keyboard button 'i' the video will freeze and allow the 
        user to select desired object.
    
