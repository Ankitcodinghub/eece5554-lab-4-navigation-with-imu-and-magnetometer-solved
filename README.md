# eece5554-lab-4-navigation-with-imu-and-magnetometer-solved
**TO GET THIS SOLUTION VISIT:** [EECE5554 LAB 4-Navigation with IMU and Magnetometer Solved](https://www.ankitcodinghub.com/product/eece5554-lab-4-navigation-with-imu-and-magnetometer-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95069&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EECE5554 LAB 4-Navigation with IMU and Magnetometer Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
Lab learning objectives and tasks:

In this lab, you are going to build a navigation stack using two different sensors – GPS and IMU and understand their relative strengths and drawbacks.

Please get an early start to the lab. You cannot complete this lab in a day!

 Dataacquisitioncanbedonecollectivelyasateam.Onedatasetperteamissufficient.

Hardware / Sensors

 GNSS puck – usb based, issued one per team. (use the one issued for Lab 1)

 Vectornav VN-100 IMU – usb based, issued one per team. The user manual for the

sensor has already been provided for Lab3.

Data collection Policy

Plan data collection schedules amongst your teammates. You can talk to your teammates and ask questions on Piazza.

Part A: Collect Data in a car for dead-reckoning as a Team Setup

Collect Data from both the GPS and IMU sensors. Make sure you are able to see both gps msgs and imu msgs on your machine.

Mount the IMU in your vehicle with electrical tape. Make sure that the x –axis is pointed forward and that the imu is as close to horizontal as possible. Fix the GPS puck to the roof – it has a magnetic back and should just stay there. Connect both sensors to your laptop and begin logging. Wait 10 seconds and start the vehicle. Drive course including 360 turns for compass calibration. After finishing the mission, shut down logging.

Ideally in the beginning of your ride, go around in a circle 3-4 times for compass calibration. One suggested place to do would be roundabout in front of Ruggles station and Ryder hall. Then go for a ride and come back to the starting point. (like a loop).

Logistics (Recommended) If you / one of your teammates has access to a car, it might be more convenient for data collection. So that you can do it on your team schedule.

Alternatively, a team can schedule to use our autonomous car ‘NUANCE’ for data collection. Ask the TAs about the availability of the NUANCE car and NEU driver requirements

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
EECE 5554 Robotics Sensing and Navigation Spring 2022 B: Analysis on the data collected in Part A (Individually)

1. Estimate the heading (yaw)

Magnetometer Calibration:

Correct magnetometer readings for “hard-iron” and “soft-iron” effects using the data collected when going around in circles.

Submit plots showing the magnetometer data before and after the correction in your report.

Calculate the yaw angle from the corrected magnetometer readings.

Integrate the yaw rate sensor to get yaw angle. One way to do this is to use ‘trapz’ or ‘cumtrapz’ commands in Matlab and treat your time series as a function that is being integrated.

Compare the yaw angle from above two methods.(Magnetometer vs. Yaw Integrated from Gyro).

Use a complementary filter to combine the measurements from the magnetometer and yaw rate as described in class to get an improved estimate of yaw angle (filter the magnetometer estimate using a low pass filter and gyro estimate using a high pass filter). You might also find the ‘unwrap’ or ‘wraptopi’ commands in matlab useful.

Compare your result to the yaw angle computed by the IMU and write down your observations.

2. Estimate the forward velocity

Integrate the forward acceleration to estimate the forward velocity.

Additionally, calculate an estimate of the velocity from your GPS measurements.

Plot both the velocity estimates.

Make observations on the plot. Does the integrated velocity estimate make sense?

Make adjustments to the acceleration measurements to make the velocity plot more reasonable. Provide the rationale you use for the adjustments and plot the adjusted velocity.

3. Dead Reckoning with IMU

Integrate IMU data to obtain displacement and compare with GPS.

We simplify the description of the motion by assuming that the vehicle is moving in a two- dimensional plane. Denote the position of the center-of-mass (CM) of the vehicle by (X,Y,0)

and its rotation rate about the CM by (0,0,ω). We denote the position of the inertial sensor in space by (x,y,0) and its position in the vehicle frame by (xc,0,0). Then the acceleration measured by the inertial sensor (i.e. its acceleration as sensed in the vehicle frame) is

x ̈obs=X ̈−ωY ̇−ω2xc y ̈obs=Y ̈+ω X ̇ +ω ̇ xc

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
EECE 5554 Robotics Sensing and Navigation Spring 2022

where all of the quantities in these equations are evaluated in the vehicle frame.

<ol>
<li>Assume that Y ̇=0 (that is, the vehicle is not skidding sideways) and ignore the offset by setting xc=0. Then the first equation above reduces
toX ̈=x ̈obs. Integrate this to obtain X ̇. Compute ωX ̇ and compare it to y ̈obs

. How well do they agree? If there is a difference, what is it due to?
</li>
<li>Use the heading from the magnetometer to rotate
x ̈=v ̇+ω×v=X ̈+ω ̇ ×r+ω×X ̇+ω×(ω×r)

into a fixed (East, North) reference frame. Denote this vector by (ve,vn). Integrate it to estimate the trajectory of the vehicle (xe,xn). Compare the estimated trajectory with the GPS track by plotting them on the same plot. Make sure to adjust starting point, so that both the tracks start at the same point and same heading (adjust heading so that the first straight line from both are oriented in the same direction).

Report any scaling factor used for comparing the tracks.
</li>
<li>Estimate xc.</li>
</ol>
NOTE: Denote the position and velocity of the center-of-mass (CM) of the vehicle by R and V, respectively. The inertial sensor is displaced from the CM by r = (xc,0,0) – note that this vector is constant in the vehicle frame. Let ω = (0,0,ω) denote the rotation rate of the vehicle about the CM. The velocity of the inertial sensor is v = V + ω x r, and its corresponding acceleration is:

x ̈=v ̇+ω×v=X ̈+ω ̇ ×r+ω×X ̇+ω×(ω×r)

Taking the x- and y-components of this equation in the vehicle frame gives the two equations

quoted above.

How to Submit Lab_4

<ol>
<li>In your class repo ‘EECE5554_RoboticsSensing’, create a directory called LAB4</li>
<li>Copy the ros driver package used for this assignment under LAB4.</li>
<li>Inside LAB4, create sub-directory ‘analysis’</li>
<li>Copy the matlab/python code used for data analysis and dead reckoning under ‘analysis’</li>
<li>Place your report in pdf format also in analysis directory.</li>
</ol>
Your repo structure should look similar to

‘&lt;Path_to_repo&gt;/EECE5554_RoboticsSensing/LAB2/src/&lt;your_imu_ros_driver files&gt;’ ‘&lt;Path_to_repo&gt;/EECE5554_RoboticsSensing/LAB2/src/analysis/&lt;your analysis files&gt;’ ‘&lt;Path_to_repo&gt;/EECE5554_RoboticsSensing/LAB2/src//analysis/report.pdf’

6. Push your local commits to (remote) gitlab server. You can verify this by visiting gitlab.com and making sure you can see the commit there.

</div>
</div>
</div>
