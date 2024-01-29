# Reference For Advance Physics Course in Information Technology

This Repository is documentation of my class, please do not confuse me as a teacher.

## Information

> **How does teaching work?**

The course is taught in hybrid model which mean, there are contact lessons (on university premesis) and remote lesson(for e.g. with Zoom).

- Weekly video lectures will be available once a week on online platfrom, at latest on friday each week.
- There is weekly exercise classes where we work on exercises based on lectures.
- Weekly quiz or a small exercise task each week.

You must watch the video lecture and attend the exercise class before attempting the quizzes!

## Material

### Video lectures

- > Setting up vscode, Python and Jupyter notebook or log in to Google Cloud.[Video Lecture 1](https://oamk-my.sharepoint.com/personal/ilpovirt_oamk_fi/_layouts/15/stream.aspx?id=%2Fpersonal%2Filpovirt%5Foamk%5Ffi%2FDocuments%2FLuentojen%5Ftallenteet%2F2023%2D2024%2FApplied%5Fphysics%5Fin%5Fprog%5F2024%2FApplied%5Fphysics%5Fvideo%5Flecture%5F1%2Emp4&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview)

- > Video Lecture 2
  >
  > - Python Fundamentals [part 1](https://oamk-my.sharepoint.com/:v:/g/personal/ilpovirt_oamk_fi/EcMKsYITc2xLnnHGXn7muu0BGMkzeeg3tDlEWa9nJMOn5A?e=LbKFL5),
  > - Python library fundamental and mobile sensor [part 2](https://oamk-my.sharepoint.com/:v:/g/personal/ilpovirt_oamk_fi/Ebdo6oKwOpRGrG5_1kF1p7oBLbAEAD_uOR3dnb7I992uog?e=aLUiKY)

- > Video Lecture 3

- > Video Lecture 4

- > Video Lecture 5

- > Video Lecture 6

- > Video Lecture 7

### Lecture notes

- > [Powerpoint slides](https://moodle.oulu.fi/pluginfile.php/2116708/mod_page/content/8/Applied_physics_in_programming.pptx?time=1705048243941)
- > Hand-written notes

### Code examples

- > [Python fundamentals](https://oamk-my.sharepoint.com/:v:/g/personal/ilpovirt_oamk_fi/Ebdo6oKwOpRGrG5_1kF1p7oBLbAEAD_uOR3dnb7I992uog?e=aLUiKY)

- > [Data access in Python](https://oamk-my.sharepoint.com/:v:/g/personal/ilpovirt_oamk_fi/Ebdo6oKwOpRGrG5_1kF1p7oBLbAEAD_uOR3dnb7I992uog?e=aLUiKY)

### Selected recordings

- > [General information (11.1.2024)](https://oamk-my.sharepoint.com/:v:/g/personal/ilpovirt_oamk_fi/EfsNUN-Mf-NHp0tVK_1SuKQBHcUxVuXt9ikp2uE4fcrgVg?e=ynimLE)
- > [Help with Python installation problems (11.1.2024)](https://oamk-my.sharepoint.com/:v:/g/personal/ilpovirt_oamk_fi/EQx3QlZKH6JAnHd2indWbdkBvtkILJVZxnfJO8PAH8QjLA?e=5BLgo5)
- > [CSV data access, possible problems (16.1.2024)](https://oamk-my.sharepoint.com/:v:/g/personal/ilpovirt_oamk_fi/ERL6NOG8KXpHsqWoNalVoIsBUXVs9eEujPEBrrcXE1YE6A?e=eFG3EY)

### Other material

- > [W3 school Python tutorial is a good learning material on Python ](https://www.w3schools.com/python/default.asp)

### Exercises

- > -Physics exercises

### Exercise solutions and examples

- > Calculations
- > Other

## Week 1: Introduction and Overview of Course

### task related to week1.

> - Install Python and Jupyter notebook or log in to Google Cloud.
> - Setup VScode, juptry Notebook, python and dependent library.
> - Write your first Jupyter notebook, Hello World or something else.
> - Return the pdf of the screenshot which shows a successful running of the code.

## Week 2: Reading Data using pandas and ploting graph using matplotlib

### Task for week 2

> - Carry out about 30s observation of acceleration using Phyphox and save the data to your computer.
> - Write a Jupyter notebook where you first read the data using Pandas.
> - Then make a graph of all three components (x,y,z) of acceleration using matplotlib.pyplot.
> - You can plot each of them to a separate panel or in the same panel using different panels and a legend to distinguish between components.
> - Name the axis, set reasonable axis limits and set gridlines.
> - Return a pdf file which contains your figure and a short description of the motion of the mobile phone during the observations based on the graph.python_fundamentals.ipynb

### Learning outcome

> Basic data Types in Python

- Basics includes Int, Str, Bool, Float, Complex
- Casting to int, to Str
- Operator in Python
- List in python, accessing by index, instering in list
- class and object in python, its methods and attributes, self parameter

> dataPy_notebook.ipynb

- using libraries like numpy, Pandas, and Matplotlib
- basic Mathematical operation like mean, median, sd, variance using
  numpy
- Read data using Pandas
- data Visualization using Mathplotlib

> RawDAta.csv

- is a csv(comma Seprated file) that is genertated using acclerometer
  without g in PHYPHOX(a mobile a collecting data)

## Week3: Data-analysis with Python 

### Task for week 3

> Carry out GPS observations (Phyphox) where you move (outside) by walking, running, skiing or biking.
> (Note that inside a building or a car, the data quality might be low)
> Observe at least a few minutes since GPS is inaccurate at the start.
> Save the data.
> Write a Jupyter notebook which does the following;
>
> - Read the data (Pandas)
> - Draw the walking path (Folium https://pypi.org/project/folium/ )
>  Manipulate your data in Python, then visualize it in a Leaflet map via folium.
> - Draw a line plot of velocity (from data and using Haversine), distance and number of satellites. (matplotlib.pyplot)
>   Return a pdf file which includes graphs and a short description of how well the graphs describe your actual motion.
>
> https://developer.android.com/develop/sensors-and-location/sensors/sensors_overview#java

### Learning outcome
using pyphox in phone to get the gps data of myself walking and using folium to create a map and draw line plot. 

> GPS_plot_folium.ipynb

- importing required library using pasdas to read data fro gps.csv, importing numpy and math.
- Defining Harvesin formula and reading data
- calculating velocity for each cell using harvesine fromula(distance fromulae) and time diff
- plotting using folium 

## Week3: Sensors and sensor application 

### Task for week 4

>Perform an acceleration measurement (Acceleration without g) lasting at least half a minute, whereyou walk fairly steadily and the phone stays in the same position (in your hand, in your pocket). Count the steps accumulated during the measurement and record the amount.
>
>Load the data into a Jupyter Notebook.
>
>First, determine which component (x, y, or z) best captures the acceleration. This is often done visually by seeing which component clearly shows the oscillating signal corresponding to walking. You can also calculate the sum of the absolute value of different components [which happens in Python, for example, data.abs().sum()] and select the component with the largest sum. You can also test different components in the analysis and compare the results.
>
>Remove noise from the data using a low-pass filter. There is usually no need to remove the background/zero level, but make sure the average of the noise-free data is roughly around zero. You can also test different methods.
>
>Calculate the number of steps from noise-free data, for example by examining how often the acceleration value changes sign (the graph passes over the x-axis). This can be done with code,for example
>```
>steps = 0
> for i in range(stepdata.shape[0]-1):
>    if stepdata[i]/stepdata[i+1] < 0:
>       steps = steps + 0.5
> ```
>
>where stepdata is the acceleration data you filtered. The number of steps always increases by only half, because each step involves a back and forth cycle of acceleration, during which the zero level is passed twice (at least with the teacher's walking style).
>
>Return a pdf file with the following:
>
> - Graph of the selected acceleration component
> - Graph of filtered data
> - The number of steps calculated by the program and its comparison with your own calculation
> - Your own reflection on the method and its reliability

### Learning outcome

- what is Noise?, Noise removal, Zero-level/background noise removable.