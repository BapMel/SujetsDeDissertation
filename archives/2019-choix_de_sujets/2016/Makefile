SRC="B.Meles-Sujets_dissertation"

all:
	latex $(SRC)
	# biber $(SRC)
	# makeindex $(SRC).idx
	# mpost $(SRC).mp
	latex $(SRC)
	# latex $(SRC)
	dvipdf $(SRC)

clean:
	-tex-nettoyage
	# -rm $(SRC).? $(SRC).??
