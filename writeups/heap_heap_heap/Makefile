all: heapheapheap_writeup.md
	pandoc -s heapheapheap_writeup.md  -o ../../heapheapheap_writeup.html --metadata-file metadata.yml --from markdown+emoji --embed-resources --standalone --mathjax
	sed -i 's/¶//g' ../../heapheapheap_writeup.html