# cryptopals-AES_CBC

## Usage

This script just requires Numpy (1.19.5 used).
To make simple, just run :
```bash
pip3 install -r requirements.txt
```

Then you can run the script with python3 :
```bash
python aes_cbc.py -k "YELLOW SUBMARINE" -i "initial vectoriz"-d "random text you want, anyway the length"
```

You can specify the output with `-o filename`, which will contain the output as binary.
By default, the output is as hex on stdout


## Note

**Almost** everywhere, I only saw "implementations" using AES library directly,
and **almost** never complete python codes.
So, I decide to make my own !
I started also by implement matrix things, but, as it's not the point of this exercise,
I just used Numpy.

To do all that, i used a lot of documentations.
I will not lie, and tell I pick code from the he(ll)aven.

Just, a lot of documentation, and a lot of tries (and fails :D )


## Used Documentations

https://datatracker.ietf.org/doc/html/rfc2104.html  
https://kavaliro.com/wp-content/uploads/2014/03/AES.pdf  
https://fr.slideshare.net/Shiraz316/aes-by-example  
https://www.angelfire.com/biz7/atleast/mix_columns.pdf  
https://github.com/boppreh/aes/blob/master/aes.py , line 89->96. I picked only that, cause, admit, it's really a pain..  
https://en.wikipedia.org/wiki/Rijndael_S-box
