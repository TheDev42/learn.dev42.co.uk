# Data Representation

## error checking

checksum is used to make sure that all the data that was sent has arrived.
it can be calculated by adding all the bits up in the data or all of the data blocks. this is then send afterwards and used to check if everything is there.

parity system uses an extra bit called a "parity bit" this insures that the number of 1s is always odd or even. this was decided by both sides before the data was sent

majoroty voing is when your bits are sent 3 times and the most common bit is used. 101100 is sent as 111000111111000000. it is recived as 110 000 110 111 001 000 which = 101100

they all do a simalar job. majoroty voting is very good but the data is sent 3 or more times. this is ineficsnt and slow. parity system doesnt check if everything is right but only that there are the correct number of 1s. checksum is good for very large pieces of data. this only valadates that the right value of data arrived and not if it is order.

## coding systems

ascii is used to represent characters using 7 bit binery. it can represent upto 128 characters. extended ascii ads an extra bit onto this allowing upto 256 characters.
these are older and not used so much. they work on most devices but just dont have enough characters to make them usefull for anything other than plain text

unicode on the other hand is more used as it can represent more than 1.1 million characters. it uses ascii for the first few values doing british characters but also does over 30 other character sets.
often using UTF-8 To ENCODE. it uses Hex numbers so uses the base 16 number set. the letter a lookes like this ~U+1F60A~

unicode is used almost everywhere. there is very few use cases to only use ascii other than if storage is limmated to below 64mb or less than 8mb ram. as ascii has such a low ammount of characters. unicode also does emojies so is all around better

## graphics

length X width X bit depth

1920 x 1080 is most common. So is 24 bit colour

(1920 X 1080 X 24) / 8 = 6,220,800 bytes

Bit Depth is base 2 - google it

Metadata is data attached to fimes that has extra information like what camera it was taken on and its location. seperate to the immage and is easily removed

vector graphics scales the immage correctly as you zoom in and out. used in MOST PDFs. good for logos and text
whereas bit-mapped images do not scale and go blury if you zoom in.
Vector uses geomerty and math so when you zoom in the image says sharp whereas Bit-Map immages use pixels so when you zoom in, you just se a bigger pixel
## compression

lossy compresion gets rid of unrequired data, oftem reducing some colours. causes visable diference.
lossless replaces repeating data sets and makes no visable diferance to immages and text. used in text and .Zip files

Run-Lenth encoding replaces "AAAA" with 4A to save space

dictonery based replaces common words with a repersentantion so you dont need to store it loads of times. get rid of redundenht data.

## sound

analoug sound uses waves and change in voltage to produce sound. no sound loss.
digital uses levels sample rates. generly a loss in sound quality
a dac and adc are used to convery analoug and digital waves to the other type. a DAC converts from digital to analoug and a ADC does the opposite
sample resolution is how high the voltage has to change for the diference to be heard. 
sample rate(Pull rate) is how oftem this action is done. a higher sample rate means more samples are taken every second. making the audio more realistic

Nyquist theorem means that to digitise audio, the sample rate must be more than double the highest frequency

Size = Bit Depth X Duration X Sample rate

midi can represent any sound of instrament

