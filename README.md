# MedDocBot
UIPath Hackathon Project for Team 3, a second place program at RPALeague Houston. 

##Creators:
Madeleine Wilson
Zach Grimes
Gabriela Marin

### Overview and Functionality
This RPA is designed for hospitals and clinics so that administration and staff can process documentation quickly and nearly effortlessly. 
The idea is not completely removed of some staff, however the robot handles all the data entry with minimal supervision of intake staff.
To start the process, an employee of the hospital places a document into an I/O scanning device for capturing images. The robot listens in on a directory where the I/O device sends images of the document. For demonstration purposes, the robot is programmed to process insurance cards, however we are currently implementing other image processing functionality. A lot of that is "platform" or hospital dependent, as the documentation varies, and the image processing software must have some template to work off of. However, the usefulness is all the same. After images are recognized, text is extracted from the images and processed intelligently into forms. The robot is capable of identifiying which text belongs to which form field, so that information can be directly sent to database management software! 

