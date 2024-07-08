---

# Task Report

**Name:** V Sanjay  
**Domain:** AI & ML  
**Batch:** 4  

---

## Task 1: Working with Pandas and Matplotlib

### Introduction
This task utilized **Pandas** and **Matplotlib** to visualize the monthly launches of the Indian Space Research Organisation (ISRO). The dataset sourced from ISRO's historical launch records offers insights into the organization’s launch activities over time. The Real Python tutorial on plotting with Matplotlib served as a reference for creating informative visualizations.

### Methodology
The analysis revolves around the manipulation of Pandas and the visualization of Matplotlib. The dataset focuses on ISRO launches on a monthly basis, providing the canvas for our visual exploration.

### Code Implementation
Embarking on our mission, we follow the footsteps of seasoned data explorers as outlined in the Real Python tutorial: [Pandas Plotting in Python (Guide)](https://realpython.com/pandas-plot-python/). Our aim is to unveil the narrative of ISRO's monthly launches through three distinct lenses: a line graph, a bar graph, and a scatter plot.

**GitHub:** [Pandas and Matplotlib Task](https://github.com/sanjaychethu/Marvel_Missions/blob/main/Marvel_Task1.ipynb)

**Linear Graph:**  
[![download-1.png](https://i.postimg.cc/rsyVNfSx/download-1.png)](https://postimg.cc/JDgC1cYz)

**Bar Graph:**  
[![download-2.png](https://i.postimg.cc/P5yBmdS3/download-2.png)](https://postimg.cc/21qcYNRh)

**Scatter Plot:**  
[![download-3.png](https://i.postimg.cc/qqY7B83K/download-3.png)](https://postimg.cc/y3mKv3n6)

---

## Task 2: Working with GitHub

### Introduction
This task revolves around a specific Git repository and aims to familiarize with GitHub Actions, Issues, and Pull Requests. In this step-by-step report, we will clone the repository, explore its contents, understand and execute GitHub Actions, address issues, and create and manage pull requests. By actively engaging with these GitHub features, we enhance our understanding of collaborative development practices and automated workflows.

### Steps:
1. Clone the Repository
2. Create a New Branch
3. Make Changes
4. Commit Changes
5. Push Changes
6. Create a Pull Request

**GitHub:** [GitHub Task Pull Request](https://github.com/UVCE-Marvel/git-task/pull/64)  
[![Screenshot-694.png](https://i.postimg.cc/9FnxVzNj/Screenshot-694.png)](https://postimg.cc/VdX9Ws87)

---

## Task 3: Create a Portfolio Webpage

In this report, I present the development of a personal portfolio website serving as a dynamic showcase of skills, interests, and projects. The webpage, built with HTML, CSS, and JavaScript, emphasizes responsive design for optimal viewing on diverse devices. Let's explore the design choices, technologies utilized, and the overall process behind creating this interactive and responsive portfolio webpage.

**GitHub:** [Personal Portfolio](https://github.com/sanjaychethu/Personal-Portfolio)  
**Live Demo:** [Portfolio Website](https://sanjaychethuportfolio.netlify.app/)  
[![Screenshot-712.png](https://i.postimg.cc/VLgJbCP3/Screenshot-712.png)](https://postimg.cc/CzZh3d1N)  
[![Screenshot-713.png](https://i.postimg.cc/7LYdYjMF/Screenshot-713.png)](https://postimg.cc/hX6p2yYs)

---

## Task 4: Writing Resource Article using Markdown

I have successfully completed the task of writing a resource article on the topic of "Version Control with Git and GitHub" using Markdown. This comprehensive guide aims to provide readers with a clear understanding of version control principles and how Git, coupled with GitHub, can streamline collaboration and project management in software development.

**Resource Article:** [Version Control with Git and GitHub](https://hub.uvcemarvel.in/article/d51d2266-5ffc-4421-b72e-e62eb4df0f5c)  
[![Screenshot-714.png](https://i.postimg.cc/63BrXNrZ/Screenshot-714.png)](https://postimg.cc/zLPbC6PD)

---

## Task 5: Get Familiar with the Command Line on Ubuntu

### Objective
Familiarize with the command line on Ubuntu and perform specified subtasks.

1. **Change Directory:** Moved into the "test" folder using the `cd` command.
2. **Blank File Creation:** Created a blank file named "blank_file.txt" using the `touch` command.
3. **Listing Files:** Checked the contents of the folder with `ls` to ensure the creation of the blank file.
4. **Multiple Folder Creation:** Used a loop to create 2600 folders named "M1", "M2", ..., "M2600". This can be modified based on the specific naming convention.
5. **Concatenating Text Files:** Assuming there are two text files "file1.txt" and "file2.txt", used the `cat` command to concatenate them and display the combined content on the terminal.

[![1704724236776.jpg](https://i.postimg.cc/43fy440X/1704724236776.jpg)](https://postimg.cc/YvPMb7kP)  
[![1704724236783.jpg](https://i.postimg.cc/Rhdvqyb2/1704724236783.jpg)](https://postimg.cc/ctvpb9Wc)

---

## Task 6: API

### Introduction
To explore the intricacies of API integration and its practical applications, I initiated a project to develop a weather app interface. The central components of this undertaking included the utilization of the OpenWeatherMap API and the integration of a jQuery plugin to seamlessly represent weather data.

### Resource Acquisition
I obtained essential resources by downloading the contents of the GitHub repository either from the jQuery website or through the provided link ([http://bitly.ws/CQRQ](http://bitly.ws/CQRQ)).

### Project Setup
After acquiring the necessary files, I meticulously copied the entire repository contents into a new directory on the desktop. This directory served as the foundation for subsequent development stages.

### API Integration
A critical step in this project was obtaining an API key from openweathermap.org. This key served as the gateway for accessing real-time weather data. The API key was seamlessly incorporated into the project code, enabling communication with OpenWeatherMap servers.

### jQuery Plugin Implementation
Leveraging the capabilities of a jQuery plugin, I facilitated the dynamic and user-friendly display of weather conditions. The plugin, sourced from the provided GitHub repository or the link ([http://bitly.ws/CQRY](http://bitly.ws/CQRY)), played a pivotal role in enhancing the visual appeal and functionality of the weather app interface.

```nginx
$(function() {
    $('.weather-temperature').openWeather({
        lang: 'ru',
        city: 'Bengaluru',
        placeTarget: '.weather-place',
        units: 'f',
        windSpeedUnit: 'Mps',
        descriptionTarget: '.weather-description',
        minTemperatureTarget: '.weather-min-temperature',
        maxTemperatureTarget: '.weather-max-temperature',
        windSpeedTarget: '.weather-wind-speed',
        humidityTarget: '.weather-humidity',
        sunriseTarget: '.weather-sunrise',
        sunsetTarget: '.weather-sunset',
        iconTarget: '.weather-icon',
        customIcons: '/img/icons/weather/',
        success: function() {
            $('.weather-temperature').show();
        },
        error: function(message) {
            console.log(message);
        }
    });
});
```

[![Screenshot-715.png](https://i.postimg.cc/1X5L7tJY/Screenshot-715.png)](https://postimg.cc/R6ysNMrc)  
**GitHub Link:** [Weather API Task](https://github.com/sanjaychethu/Marvel_Missions/tree/main/Weather%20API%20Task)

---

## Task 7: Tinkercad

### Objective
The primary objective of this project was to create an account and familiarize myself with the Arduino application. Additionally, the project aimed to simulate ultrasonic/infrared sensors, estimate the distance between an obstacle and the sensor, and display the results on a 16x2 LCD I2C Display.

### Components Used
- Arduino Uno R3 board
- Ultrasonic sensor (HC-SR04)
- 16x2 LCD I2C Display
- Jumper Wires

### Procedure

#### 1. Sensor Connections
- Connected the Echo pin of the ultrasonic sensor to the D2 pin of the Arduino.
- Connected the Trig pin of the ultrasonic sensor to the D3 pin of the Arduino.

#### 2. LCD Display Setup
- Installed the driver library for the Liquid Crystal Display to interface with the LCD display.
- Searched for and installed the "LiquidCrystal I2C" library.
- Imported the header file "LiquidCrystal_I2C.h" in the code.
- Connected the SDA pin of the LCD display to the SDA pin of the Arduino Board and the SCL pin of the LCD display to the SCL of the Arduino Board.
- Connected VCC to the 5V pin and GND to the GND pin.

#### 3. Code Integration for LCD
Included the necessary code to define the display device.

```nginx


void setup(){
  lcd_1.begin(16, 2);
  lcd_1.print("distance: ");
  pinMode(trigPin, OUTPUT); // Sets the trigPin as an OUTPUT
  pinMode(echoPin, INPUT);  // Sets the echoPin as an INPUT
  // Serial Communication is starting with 9600 of baudrate speed
  Serial.begin(115200);
  // The text to be printed in serial monitor
  Serial.println("Distance measurement using Arduino Uno.");
  delay(500);
}

void loop(){
  digitalWrite(trigPin, LOW);
  delayMicroseconds(2); // wait for 2 ms to avoid collision in serial monitor
  digitalWrite(trigPin, HIGH); // turn on the Trigger to generate pulse
  delayMicroseconds(10); // keep the trigger "ON" for 10 ms to generate pulse for 10 ms.
  digitalWrite(trigPin, LOW);
}
```

[![Screenshot-718.png](https://i.postimg.cc/jqw95GBf/Screenshot-718.png)](https://postimg.cc/RqmGpbSC)  
**Tinkercad Link:** [Arduino Project](https://www.tinkercad.com/things/69xPMrtUhnJ-arduino?sharecode=W3dt1I3UmpvFwwPK0y6_SqyUAV4HaieDVERpAxBkqws)

---

## Task 8: Soldering Prerequisites

### Procedure

#### 1. Introduction to Equipment
- The coordinator provided an overview of each tool, explaining their functions and safety measures.

#### 2. LED Circuit Soldering
- A simple LED circuit on a perf board was chosen for practice.
- Components included resistors, an LED, and connecting wires.

#### 3. Soldering Process
1. **Tinning the Soldering Iron:** Applied a small amount of solder to the iron tip to ensure better heat transfer.
2. **Preparing Components:** Trimmed excess leads from components for a clean assembly.
3. **Applying Flux:** A small amount of flux was applied to the solder joints to enhance soldering.
4. **Soldering Components:** Connected the components on the perf board, soldering one joint at a time, ensured a secure and neat solder joint.

[![1704809451647.jpg](https://i.postimg.cc/900cRJ5M/1704809451647.jpg)](https://postimg.cc/MMCCg0G2)

---

## Task 9: Active Participation

### Kagada 2023
[![Screenshot-722.png](https://i.postimg.cc/wMXnBN3v/Screenshot-722.png)](https://postimg.cc/1VzvCfGh)

### Google Cloud Computing Foundations
[![Screenshot-721.png](https://i.postimg.cc/tg6kyjsR/Screenshot-721.png)](https://postimg.cc/R3MKQ212)

---
