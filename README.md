# darkcrypt

tis not...



Try cracking outmess10.txt. 

I will give you a hint. 

```
set G = make lcg with 65,65,65,87878. 
set G13 = make lcgv3 with 99,5,555,-9,999,G,9,99,1,1.


```

------------

Not good enough? 

Here is another hint, use `seqbuild`. 

------------

Not good enough? 

Alter line 76 of `seqgen/sb_crypt.py` to 

```
qx = self.prg() + q #rch.apply(q) 
```

That would be the encryptor. You're smart enough, right? What you can't 
tail or steal, you ruin. Now walk backwards. 

-------------

Not good enough? 

The last n'th number of numbers is 

```
Moorish America
```