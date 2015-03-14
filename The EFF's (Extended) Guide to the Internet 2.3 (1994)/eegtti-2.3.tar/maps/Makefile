THEGIFS	= \
	germany.gif	\
	europe.gif	\
	theglobe.gif

THETIFS	= \
	germany.tif	\
	europe.tif	\
	theglobe.tif

tif:	$(THETIFS)
gif:	$(THEGIFS)


theglobe.tif:
	giftoppm theglobe.gif | pnmtotiff > theglobe.tif
germany.tif:
	giftoppm germany.gif | pnmtotiff > germany.tif
europe.tif:
	giftoppm europe.gif | pnmtotiff > europe.tif


theglobe.gif:
	tifftopnm theglobe.tif | ppmtogif > theglobe.gif
germany.gif:
	tifftopnm germany.tif | ppmtogif > germany.gif
europe.gif:
	tifftopnm europe.tif | ppmtogif > europe.gif


clean:
	$(RM) *.tif
