# Smart Mirror
The Smart Mirror is a mirror with an interface, powered by a Raspberry Pi and a small monitor. The project is very software heavy, using React.js to create an app that will become the display for the mirror.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Alicia F | Lynbrook High School | Software Engineering | Rising Senior

<img width="1253" alt="demo" src="https://user-images.githubusercontent.com/86542085/126815098-c9b2054d-e787-4d97-b1ef-e0bcb7ee13c6.png">

  
# Final Milestone
My final milestone was setting up the hardware portion of the project. I glued the monitor to the bottom left of the acrylic screen using a hot glue gun, lining it up first and carefully lifting corners in order to apply a small amount of glue. After that all that was left to do was install my website software onto my Raspberry Pi, which I first uploaded to Github to make it easier to download. Once I pulled it onto my Pi, I used npm i and npm run build in order to install all the packages and get it to run. Some issues were the Pi constantly crashing or not booting properly, but with a lot of patience and unplugging the Pi everything worked out well at the end.

[![Final Milestone](https://res.cloudinary.com/dum3otqhy/image/upload/v1626452744/final_milestone_zw6wjp.png)](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone")

# Second Milestone
My second milestone was finishing the additional software of my Smart Mirror. The first part is a date and time section, formatted to my liking. There is also a birthday section, which displays the days until someone's birthday. The birthdays are hard coded into the program with the dates, and they display different messages the day before and of someone's birthday. There is also a weather section which displays the degrees in my city in Fahrenheit, and the current status of the weather from OpenWeather API. The image of the folder also changes depending on the status.

- The birthday list, this can be edited to add/remove/change birthdays.
```javascript
let BirthdayList = [
    {Name: "helena", Date: new Date("july 14," + new Date().getFullYear())},
    {Name: "tyler", Date: new Date("september 6," + new Date().getFullYear())},
    {Name: "snow", Date: new Date("september 17," + new Date().getFullYear())},
    {Name: "lauren", Date: new Date("november 9," + new Date().getFullYear())}
]
```

- The finished daily component on my website.
<img width="257" alt="Screen Shot 2021-07-16 at 9 31 45 AM" src="https://user-images.githubusercontent.com/86542085/125979904-e7f8ae42-dfdf-4242-a9bf-6630d65924ff.png">

- The Interval component that updates the time every second.
```javascript
  const interval = setInterval( ()=>{
        setCurrentHour(editTime((new Date()).getHours()));
        setCurrentMinutes(editTime((new Date()).getMinutes()));
        setCurrentSeconds(editTime((new Date()).getSeconds()));
  },1000); 
```

- The code to create a flexible window with the icons, this can be used to wrap any component. The category variable can take different text for the input in order to display a different word for the top of the window.
![carbon (1)](https://user-images.githubusercontent.com/86542085/126815251-9dceb27b-ef37-4320-b0c0-4b9b0e076649.png)



- Different versions of the folder icon depending on the current status of the weather.
<img width="117" alt="Screen Shot 2021-07-16 at 9 09 37 AM" src="https://user-images.githubusercontent.com/86542085/125988071-08e3e060-646f-4882-aba3-2953df822ab3.png">
<img width="115" alt="Screen Shot 2021-07-16 at 10 43 18 AM" src="https://user-images.githubusercontent.com/86542085/125988074-ec37ec63-a229-4ea0-8bc7-e8bd90e4730c.png">
<img width="115" alt="icon 1" src="https://user-images.githubusercontent.com/86542085/126815808-9b61ccb1-02ba-439d-b8f9-0e80b948e2f0.png">
<img width="115" alt="icon2" src="https://user-images.githubusercontent.com/86542085/126815815-8a3c5978-4ff2-4afd-b150-9c85123e3d35.png.png">



[![Second Milestone](https://res.cloudinary.com/dum3otqhy/image/upload/v1626452744/second_milestone_kd4ajq.png)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone")
# First Milestone
  

My first milestone was setting up the hardware of the Raspberry Pi as well as downloading the base software of the Smart Mirror onto it. The Imaging software used to install Raspbian was not opening properly on my Mac, so I switched to a Windows laptop to install Raspbian onto my SD Card. With the software installed, I attached the heatsinks, plugged in the power and HDMI cables as well as the USB keyboard and mouse. With the general setup of the Raspberry Pi complete and it succesfully hooked up to the monitor, I began to install the basic Smart Mirror software. I forked [this](https://github.com/GIP2000/SmartMirror) repository and followed the instructions to install it onto both my Raspberry Pi and Mac. I also planned out a layout for my Smart Mirror website using Clip Studio Paint and the font Gaegu.
<img width="370" alt="Image Layout" src="https://user-images.githubusercontent.com/86542085/125979603-c6ec3cbd-c726-4b7c-9728-93ee42f95e01.png">

[![First Milestone](https://res.cloudinary.com/dum3otqhy/image/upload/v1626452634/first_milestone_dxzfkz.png)](https://www.youtube.com/watch?v=zOj3-Iv9_28&ab_channel=BlueStampEng "First Milestone")
