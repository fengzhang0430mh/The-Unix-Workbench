


### guess # of files in the current directory



function guessinggame {
    x=0
	for code in $(ls)
	do 
		let x=$x+1
	done
	# echo "it is $x"

	echo "input a number: "
	read response
	if [ $response -gt $x ]
	then
		echo "large than true"
		guessinggame
	elif [ $response -lt $x ]
	then
		echo "small than true"
		guessinggame
	else
		echo "great!"
	fi
}