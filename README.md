# game_classifier
This basic script is capable of classify among four different Ubisoft Montreal franchises: Assassin's Creed, Far Cry, Just Dance and Watch Dogs, using a pre-trained ResNet34 model. 

This was constructed during a fast.ai course, for educational-purpose only. I used datasets acquired using images.google search, and the dataset wasn't carefully created. Ideally it would contain only gameplay captures, however the datasets contain too much trash images. Still, it performs way better than random guessing.

The .txt files contain the url's of the images, and the script handles the download.
