cryptage_hamm
=============
 most of you when you are developing an application for the first time
you need to save some passwords in your database in order to identify your customers again later.

saving these passwords must be done by algorithms that satisfy certain conditions:

   1- the uniqueness :

   A and B two different passwords when they are encrypted by the same algorithm, they must give two different 
   character strings
  
  2-not decipherable :

   no one can find the original password, when he looks at the character string obtained after encryption


existing encryption algorithms today do not satisfy these conditions, you can decrypt online: md5, sha-1 ... 
in all simplicity

plus you can not trust an algorithm that is done by someone intending to leave backdoors invisible to you, to spy on 
your activities whenever he wants.

For these reasons we invented HAMM , the first encryption algorithm in the world that will make impossible
the task of pirates trying to decrypt your passwords, no matter what hardware they use, no matter what time
they spend trying. 
