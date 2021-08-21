# MatlabTools
Usefull little tools for object oriented programming in MATLAB/Simulink

# Content

## Logging
A simple logger instance designed to be instanciated by calling: 
`logger = Logging.Logger();`
The logger implements the singleton pattern. The logger instance will use the logfile path and name defined in `Settings.m` if not otherwise specified during the function call.
If you want to write a log message with the logger you need to retrieve the logger instance first and then call the logging level and message. 
`logger = Logging.Logger();`
`logger.warn('Warning message')`

## Parser
A simple parser object used to wrap the call to the parse input function of MATLAB. 
`parser = Parser.ImageRefinerParser();`

# Contact
Maintained by Robert Goellinger, RWTH Aachen University
