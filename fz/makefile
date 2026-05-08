all:
	../reticode/enchex fz.hex fz.data
	../reticode/asreti fz.reti fz.code
	../reticode/emreti -s fz.code fz.data

clean:
	rm -f fz.code fz.data
