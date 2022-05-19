# Facial-Recognition

This is a facial recognition project that tries to map labelled faces to an attendance sheet. Using opencv, the program uses a built-in or USB webcam to detect faces and record the attendance live in an excel sheet. The sheet lists the people recognized and the timestamp associated with that person. This is meant to be further developed so that people can be tracked entering and exiting buildings. The face_recognition allows face encodings to be created using just 1 image.

This can be integrated using Rasberry Pi. I SSH using Putty and used nano to create the same main.py code. However, when specifying paths and writing lines to the excel sheet, f-strings can't be used and instead should be replaced with temporary variables. 
