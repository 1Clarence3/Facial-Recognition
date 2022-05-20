# Facial-Recognition

This is a facial recognition project that tries to map labelled faces to an attendance sheet. The face_recognition allows face encodings to be created using just 1 image. Using opencv, the program uses a built-in or USB webcam to detect faces and record the attendance live in an excel sheet. The sheet lists the people (without repeats) recognized and the most recent timestamp associated with that person. This is meant to be further developed so that people can be tracked entering and exiting buildings. Different methods such as HAAR Cascade could be used to boost recognizing efficiency.

This can be integrated using Rasberry Pi. I SSH using Putty and used nano to create the same main.py code. However, when specifying paths and writing lines to the excel sheet, f-strings can't be used and instead should be replaced with temporary variables. Additionally, the encoding and recognizing processes are not sped up much. 
