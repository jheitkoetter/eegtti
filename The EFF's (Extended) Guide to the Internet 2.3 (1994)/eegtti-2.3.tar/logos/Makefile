THEGIFS	= \
	bdgtti.gif	\
	signet.gif

THETIFS	= \
	bdgtti.tif	\
	signet.tif

tif:	$(THETIFS)
gif:	$(THEGIFS)


bdgtti.tif:
	giftoppm bdgtti.gif | pnmtotiff > bdgtti.tif
signet.tif:
	giftoppm signet.gif | pnmtotiff > signet.tif

bdgtti.gif:
	tifftopnm bdgtti.tif | ppmtogif > bdgtti.gif
signet.gif:
	tifftopnm signet.tif | ppmtogif > signet.gif


clean:
	$(RM) *.tif
