
# STEGANOGRAPHY
# General

run ```bash file [filename] ``` to know the type of file
run ```bash exiftool [filename] ``` to see the metadata info
run ```bash strings [filename] ``` to print the strings try grep -i [string to filter]
try binwalk [filename] to extract files try binwalk -e [filename]
use steghide for jpeg
try stegsolve to check the image in different color planes 
use stegcracker to crack the password
use zsteg for png images
try imagemagick 
try changing the size of an image
try checking if the image has an error and try correcting it with hexeditor

music file

sonic visuliazer - spectogram 
morse code decoder
steganosaur

Text

spammicmic - decode text in spam text

Pdf 

pdfinfo
pdfcrack
pdfimages
pdftotext
peepdf -if [filename]
pdfid


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

CRYPTOGRAPHY

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

openssl rsautl -decrypt -inkey pub_priv.key -in ciphertext.file -out decrypted.file
openssl enc -d -aes-256-cbc -in ciphertext.file -out cleartext.file -pass file:./key.file
openssl enc -aes-256-cbc -d -a -in file.txt.enc -out file.txt

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

REVERSE ENGINEERING

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

