# rock-paper-scissors-ai
AI Bot to play rock-paper-scissors against a human

# tensorflow-python
Code Engine: Image Classifier with 3 categories (rock, paper, scissors)
SqueezeNet will be our pre-trained CNN, and we'll re-train its output layers for our 3 new categories.

# 5 Steps we'll generally follow to create this ai
1. Collecting data - gathering images from our own web camera
2. Creating a Neural Network
3. Training the model
4. Test the model
5. Deploy model into a web app to easily let users plays.

# Step 0 - Setup
1. git clone / download this project
Create a virtual environment (recommended for python, I'm using python3) 
2. run in terminal "python3 -m venv ." (there's a space after the last 'v')
3. If you get error like "Unable to symlink" delete the bin folder that was created in root and try again.
4. run "source bin/activate" you should need your root inserted to your terminal.
6. having pip3 installed in useful for the next part "easy_install pip"
7. there is a dependency_list.txt, you can install them with pip run "pip install -r dependency_list.txt"

# Step 1 - Gathering images
1. script to run first is "collect_image_data.py"
2. Run command example: python collect_image_data.py rock 200
3. Press 's' to start/pause and q to quit.
4. Images stored in 'collected_images' dir with label set as 1st argument
