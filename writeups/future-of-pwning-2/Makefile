all: future_of_pwning_2_writeup.md
	pandoc -s future_of_pwning_2_writeup.md  -o ../../future_of_pwning_2_writeup.html --metadata-file metadata.yml --from markdown+emoji --embed-resources --standalone --mathjax 
	sed -i 's/¶//g' ../../future_of_pwning_2_writeup.html
