all: repack

initrd:
	echo "Unpacking"
	./unpackimg.sh

repack:
	echo "Repacking"
	rm -f *.img
	./repackimg.sh
	mv image-new.img boot.img
	rm ramdisk-new.cpio.gz 

clean:
	echo "Cleanup !"
	./cleanup.sh
