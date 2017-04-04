# mybot

To be used with the "Chrisify" program.

Link: https://github.com/zikes/chrisify


Program can be download and ran anywhere, it just needs a folder named "faces" in the same directory filled with face cutouts.

syntax to start program:

mybot 'slack token' 'path to chrisify program' 'path to haarcascase_frontalface_alt.xml'



CHANGES NEEDED TO WORK FOR YOU:

change "base_path" in mybot.go to the path of where you want the photos to be saved on your web server.

change "base_url" in mybot.go to the link of where images will show up. This is printed along with the final file name and sent to slack for the bot to print.



OPTIONAL CHANGES:

change some of the items in the "filenames" array in utils.go. This is what the finalized names will be named (with some random letters/numbers after that).
