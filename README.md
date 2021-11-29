# Bosch_data_engineer
Project for position at bosch
The file My_solution.py contained the file transformation code.

#The problem:
    #I believe the Data provided here is a quality inspection line
    #The line has two stations 234 and 235
    #it looks like few of the sensor readings are missing in the stream of operations
    #Each station is equipped with 3 sensors each
    #So if a reading of status is missing then one of the sensor has read
    #a faulty part and thus discontinuedd the reading of furtther sensors#
	#So here I have developed a partwise evaluation of data.
	#I have ignored the time stamp since a sensor reads within a line in a certain order.
	
#Please go to the terminal.
#Go the current folder where the my_solution.py is kept
#"python My_solution.py"
