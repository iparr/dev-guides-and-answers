# On not using fonts illegally

## What is the problem?

Well the (potential) problem is that a fonts license agreement does not explicitly mention that serving the font using the @font-face technique is allowed. Looking at some font legal agreement documents, you may see comments like "reproduction on the font file on another users computer is not allowed" and it is  this common point that means that, technically, using the @font-face embedding technique may not be legal.
 
## What is happening?

The @font-face technique involves serving every web browser that visits the page a copy of the font in .eot / .woff / .ttf and .svg formats.
 
## Why do we do this?

The advantages of this method are huge, so if the font foundry does not allow us to use this technique, then it may be worth some renegotiation with them – especially when a font is made specifically for a company. This is simply the best technique to make a website that uses non-websafe (Tahoma, Arial, et al) fonts. I'm happy to bore you with further details sometime.
 
## Why do we serve so many copies of the same font?

Different browsers support different font-types.
 
## Is there way round this? A different technique?

Yes. There are a number of options, but they are much slower and result in lower quality. Any website built may look significantly different from what may be designed in Photoshop. Also, more work would be required to implement a different technique and although it wouldn't take me long, the resultant work for websites, especially those with a global language element to them, may increase exponentially.
 
## What should we be asking?

The foundry needs to be aware that we are using the @font-face technique to serve the font and give us their blessing. They will know what this means. It may be that the license is simply out of date and that they're happy to support this (increasingly common) technique. If not, then perhaps an alternative license could be bought. Many foundries provide some of their fonts for sale under a license that allows this technique. If a font foundries fonts implicitly say "NO font-face!" then it's probably a good idea not to avoid this problem and actuall address it!