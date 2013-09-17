Machine-Simulator
=================

HOW TO RUN

1. From linux terminal to the directory where the code is present
2. type "python" and hit enter
3. Execute the following command

		import problem4 as pr
		ob = pr.heart_sim()
		ob.execute()

4. Enter the number of machines, fail percentage and recovery time 
   separated by','
5. Perfrorm the operation as suggested in the questions 

	a. failure_trend

	b. is_machine_alive m_4

	c. remove_machines m_4

	d. num_machines_alive

	e. add_machines m_1,m_3

6. Type quit to exit


SAMPLE OUTPUT

	>>> import problem4 as pr
	>>> ob = pr.heart_sim()
	>>> ob.execute()
	Enter Number of Machines, Fail Percentage and Recovery time(in sec)
	please enter values in correct format
	20 0.1 7
	failure_trend
	[20, 18, 18, 18, 18, 16, 16, 20, 20, 20]
	is_machine_alive m_4
	True
	remove_machine m_4
	Please enter the correct command
	remove_machines m_4
	Machine m_4 Removed
	is_machine_alive m_4
	Machine Not Present
	failure_trend
	[20, 18, 18, 18, 18, 16, 16, 20, 20, 20, 18, 18, 18, 18, 20, 18, 18, 18, 18, 18, 16, 20, 20, 20, 20, 18, 18, 18, 20, 20, 18, 18, 18, 18, 18, 18, 18, 18, 18, 18, 16, 16, 19, 19, 19, 17, 17, 17, 17, 19, 17, 17]
	num_machines_alive
	17
	failure_trend
	[20, 18, 18, 18, 18, 16, 16, 20, 20, 20, 18, 18, 18, 18, 20, 18, 18, 18, 18, 18, 16, 20, 20, 20, 20, 18, 18, 18, 20, 20, 18, 18, 18, 18, 18, 18, 18, 18, 18, 18, 16, 16, 19, 19, 19, 17, 17, 17, 17, 19, 17, 17, 17, 17, 17, 15, 19, 19, 19, 19, 17, 17, 17, 19, 19, 17, 17, 17, 17]
	add_machines m_1,m_3
	Machine m_1 Already exists
	Machine m_3 Already exists
	add_machines m_4
	Machine m_4 Added
	failure_trend
	[20, 18, 18, 18, 18, 16, 16, 20, 20, 20, 18, 18, 18, 18, 20, 18, 18, 18, 18, 18, 16, 20, 20, 20, 20, 18, 18, 18, 20, 20, 18, 18, 18, 18, 18, 18, 18, 18, 18, 18, 16, 16, 19, 19, 19, 17, 17, 17, 17, 19, 17, 17, 17, 17, 17, 15, 19, 19, 19, 19, 17, 17, 17, 19, 19, 17, 17, 17, 17, 17, 17, 17, 17, 17, 17, 15, 15, 19, 19, 19, 17, 17, 17, 17, 19, 17, 17, 17, 17, 17, 15, 19, 19, 20, 20, 18]
	num_machines_alive
	18
	quit
	BYE
	>>>
