# Binery

## Binery And hex

#### binery to hex convertion

8 bit Binery can be split into <ins>4 bit(Nibble)</ins> chunks then converted in to hex. working from <ins>right to left</ins>

<ins>00101011</ins> would be split into <ins>0010 1011</ins> which is then converted using hex into <ins>3 B</ins> or 3RD and 11TH Hex number.

<ins>1011101</ins> would be split into <ins>101 1101</ins> as you work from right to left. the hex for that would be <ins>5 D</ins>

## Binery and Denery

#### Binery to Denery

With binery you <ins>Always work from right to left</ins> so from the right your first Binery number represents <ins>1</ins> then doubles every next value. A 4 bit number would represent 8 4 2 1 so 1010 would be 8 + 2 = 10 or 1100 would be 8 + 4 = 12

## Hex and Denery

#### Hex to Denery

best way to do this is to go from Hex to Binery then fromm Binery to Denery

## Binery Shift

this is used for <ins>doubling or halfing</ins> the value. Use a binery left shift to <ins>double</ins> the number or a binery right shift to <ins>half it</ins>.

using a binery <ins>left shift</ins> 11001010 would become 110010100 which is <ins>double 202 to make 404</ins>

using a binery <ins>righ shift</ins> 11001010 would become 1100101 which is <ins>half of 202 to make 101</ins>

if you right shift a binery number with an <ins>odd number</ins> then the number would be <ins>rounded down by one</ins>.
10110101 would round down 1011010 which is from <ins>181 to become 90</ins>. it is slightly inacreut as you have lost the last bit causing the number to lose a value


