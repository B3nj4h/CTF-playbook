
# STEGANOGRAPHY

# GENERAL

```bash 
file [filename] # type of file  
exiftool [filename]  # metadata info 
strings [filename]  # print strings # grep -i [string to filter] 
binwalk [filename] # to extract files # binwalk -e [filename] 
steghide # jpeg 
stegsolve # check the image in different color planes 
stegcracker # crack the password
zsteg # png images
imagemagick 
changing the size of an image checking if the image has an error and try correcting it with hexeditor 
```

# Audio file

```bash 
sonic visuliazer # spectogram 
morse code decoder
steganosaur
```

# Text

```bash 
spammicmic - decode text in spam text
```

# Pdf 

```bash 
pdfinfo
pdfcrack
pdfimages
pdftotext
peepdf -if [filename]
pdfid
``` 

# CRYPTOGRAPHY

```bash 

cyberchef # encoding and decoding data

openssl rsautl -decrypt -inkey pub_priv.key -in ciphertext.file -out decrypted.file
openssl enc -d -aes-256-cbc -in ciphertext.file -out cleartext.file -pass file:./key.file
openssl enc -aes-256-cbc -d -a -in file.txt.enc -out file.txt
```

# REVERSE ENGINEERING

```bash 
ltrace [filename] # strings comparisons

RADARE 2

radare2 [filename]
i [info] #information about the binary
ie [info entrypoint] # get the entry poitns of the binary
fs imports; f # imported libraries
fs strings; f # print all strings
im # get the main address if the binary is not stripped
iz #get all the strings in the binary
aaa [analyze all] # analyze the binary
afl [analyze function list] # find all functions being used in the binary
most of the functions with sym.imp* usually belong to internal libraries
s main # seek main function
pdf [print disassemble function] # disassemble the code
VVV # get to visual mode
```