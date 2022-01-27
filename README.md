# Simulation of the University Registration System

This simulation system design will help our university to see the bottlenecks in registration process such as course capacity, prerequisite courses, and available course sessions etc.


### Usage
- Clone the repository
- Open a terminal from the directory of the repository
- Type `python src/main.py`

### Input
- Lecture informations are pre-created from our university database and stored in [lectures.json](src/JsonFiles/lectures.json) and [electives.json](src/JsonFiles/electives.json) files.
- Also the program has a [name pool](src/JsonFiles/names.json) for creating random student and avisor names.
- The values of [input.json](src/JsonFiles/input.json) file are used to set the simulation parameters. (These parameters can be changed.)

### Output
As an output, the system will print out the following information:
- On the terminal, the system prints out the registration problems.
- To the log file, the system prints out the registration problems and how many times triggered for each problem type.
- In the students forlder, the system creates a file for each student.
    - The file contains the student's transcript information and current semester's schedule.

### Contributors
- Yasin Tarakçı - [@ysntrkc](https://github.com/ysntrkc)
- Eren Akgül - [@akguleren](https://github.com/akguleren)
- Yusuf Taha Atalay - [@yusufatalay](https://github.com/yusufatalay)
- Mehmet Safa Katırcıoğlu [@SafaMarley](https://github.com/SafaMarley)
- Ahmet Emre Sağcan - [@mrsagcan](https://github.com/mrsagcan)
- Mehmet Alper Karabay - [@alperkarabay](https://github.com/alperkarabay)
- Ediz Efe Yener - [@efeynr](https://github.com/efeynr)
