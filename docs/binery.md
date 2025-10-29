# Binery
`Print Hello World`
## Binery to Hex

8 bit Binery can be split into **4 bit(Nibble)** chunks then converted in to hex. working from **right to left**  
<ins>00101011</ins> would be split into <ins>0010 1011</ins> which is then converted using hex into **3 B** or 3RD and 11TH Hex number.  
<ins>1011101</ins> would be split into <ins>101 1101</ins> as you work from right to left. the hex for that would be **5 D**


## Binery to Denery

With binery you **Always work from right to left** so from the right your first Binery number represents <ins>1</ins> then doubles every next value. A 4 bit number would represent 8 4 2 1 so 1010 would be 8 + 2 = 10 or 1100 would be 8 + 4 = 12

## Hex to Denery

best way to do this is to go from Hex to Binery then fromm Binery to Denery

## Binery Shift

this is used for **doubling or halfing** the value. Use a binery left shift to <ins>double</ins> the number or a binery right shift to <ins>half it</ins>.  
using a binery <ins>left shift</ins> 11001010 would become 110010100 which is <ins>double 202 to make 404</ins>  
using a binery <ins>righ shift</ins> 11001010 would become 1100101 which is <ins>half of 202 to make 101</ins>  
if you right shift a binery number with an <ins>odd number</ins> then the number would be <ins>rounded down by one</ins>.  
10110101 would round down 1011010 which is from <ins>181 to become 90</ins>. it is slightly inacreut as you have lost the last bit causing the number to lose a value  

## Unsigned fixed-point binery

unsigned meanes that it is a "Normal" binery number. from right to left th value doubles from 1. fixed point means that after "X" bits there will be a decimal point. still working from the left.  
using this <ins>10110101</ins> with 3 points after the decimal point would be <ins>10110.101</ins> any numbers before the decimal point represent normal binery numbers from 1 doubeling to the right.   
after the decimal point they count from 1/2 and halfs onwards. counting 1/2, 1/4, 1/8, 1/16 and so on.

so the <ins>.101</ins> would represent 1/2 + 1/8 = <ins>5/8 or 0.625</ins>  
then the 10110. would be 2 + 4 + 16 = 22  
therefor 10110101 with <ins>3 points</ins> after the decimal place would be **22.625**


