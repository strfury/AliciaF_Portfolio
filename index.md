# Smart Mirror
The Smart Mirror is a mirror with an interface, powered by a Raspberry Pi and a small monitor. The project is very software heavy, using React.js to create an app that will become the display for the mirror.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Alicia F | Lynbrook High School | Software Engineering | Rising Senior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/dum3otqhy/image/upload/v1626452744/final_milestone_zw6wjp.png)](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone")

# Second Milestone
My second milestone was finishing the additional software of my Smart Mirror. The first part is a date and time section, formatted to my liking. There is also a birthday section, which displays the days until someone's birthday. The birthdays are hard coded into the program with the dates, and they display different messages the day before and of someone's birthday. There is also a weather section which displays the degrees in my city in Fahrenheit, and the current status of the weather from OpenWeather API. The image of the folder also changes depending on the status.
The birthday list, this can be edited to add/remove/change birthdays.
```javascript
let BirthdayList = [
    {Name: "helena", Date: new Date("july 14," + new Date().getFullYear())},
    {Name: "tyler", Date: new Date("september 6," + new Date().getFullYear())},
    {Name: "snow", Date: new Date("september 17," + new Date().getFullYear())},
    {Name: "lauren", Date: new Date("november 9," + new Date().getFullYear())}
]
````


[![Second Milestone](https://res.cloudinary.com/dum3otqhy/image/upload/v1626452744/second_milestone_kd4ajq.png)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone")
# First Milestone
  

My first milestone was setting up the hardware of the Raspberry Pi as well as downloading the base software of the Smart Mirror onto it. The Imaging software used to install Raspbian was not opening properly on my Mac, so I switched to a Windows laptop to install Raspbian onto my SD Card. With the software installed, I attached the heatsinks, plugged in the power and HDMI cables as well as the USB keyboard and mouse. With the general setup of the Raspberry Pi complete and it succesfully hooked up to the monitor, I began to install the basic Smart Mirror software. I forked [this](https://github.com/GIP2000/SmartMirror) repository and followed the instructions to install it onto both my Raspberry Pi and Mac. I also planned out a layout for my Smart Mirror website using Clip Studio Paint and the font Gaegu.
<img width="370" alt="Image Layout" src="https://user-images.githubusercontent.com/86542085/125979603-c6ec3cbd-c726-4b7c-9728-93ee42f95e01.png">

[![First Milestone](https://res.cloudinary.com/dum3otqhy/image/upload/v1626452634/first_milestone_dxzfkz.png)](https://www.youtube.com/watch?v=zOj3-Iv9_28&ab_channel=BlueStampEng "First Milestone")
