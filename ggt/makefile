all:
	../reticode/enchex ggt.hex ggt.data
	../reticode/asreti ggt.reti ggt.code
	../reticode/emreti -s ggt.code ggt.data

clean:
	rm -f ggt.code ggt.data
