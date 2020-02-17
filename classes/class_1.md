## Class: Employees
### Attributes:
* name : (string data type with the employee's name)
* availability : (an object/hash data type pairing a day, a string, with the employee's ability to work one of three shifts, an integer: 0 = day off 1 = am shift 2 = mid day shift, 3 = night shift)  
* pay : (Float data type with the employee's hourly pay)
* isWorking : (boolean data type determining the employee's status)


### Methods:
* schedule : (schedules employee using the availability hash)
* clockIn : (changes isWorking from false to true, creates a time stamp (another variable with a float value which we can later use, let's name it clockInTime))
* clockOut : (changes isWorking back to false, creates a second time stamp named clockOutTime)
* compensate : (takes clockOutTime - clockInTime and multiplies it by the attribute pay)
