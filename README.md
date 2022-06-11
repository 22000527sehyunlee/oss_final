# Weekly Planner for Laziness

22000527 Sehyeon Lee

<h2>What does this project do?</h3>
This project can easily see the schedule.<br>
You can easily add when and what to do by clicking the button shown above and delete it again with the cancel button.<br>
Adding a schedule adds icons and background colors so that you can easily see the schedule.<br>
This planner Is Perfect for people who don't plan in detail.<br>

<h2>Why is this project useful?</h3> 
- First, this scheduler easily can noticed your schedule.<br>
- Add and delete, reset, modify the schedule what ever you want<br>
- As long as Raspberry Pi is on, you can always use it by typing only the address on the web page.<br>


<h2>How to get started? </h3>
<div>
1) Prepare raspberry pi: <br>--- Turn on your RaspberryPi<br>
2) Turn off nginx if it is running <br>---   sudo systemctl stop nginx<br>
3) Install Apache2:<br>---  sudo apt-get install apache2 –y<br>
4) Start the apache server:<br>---   Sudo service apache2 restart<br>
5) Directory:<br>---    Make a directory under RaspberryPi's local directory<br>
6) Clone the git:<br>---   Git clone https://github.com/22000527sehyunlee/oss_final.git<br>
7) Move the cloned file to the /var/www/html/:<br>---   sudo mv oss_final /var/www/html/<br>
8) Open the project with your laptop through web browser:<br>---    http://raspberrypi.local/index.html<br>
  
</div>
<h2>Where can people get more help, if needed? </h3>
Please contact me through email: 13579@gmail.com<br>

<h2>Presentation Video (YouTube) Link</h3> 
<a href="https://youtu.be/J3cjEqju1b4">[GO TO YOUTUBE]</a>

<h2>contribution</h3>
I made this project by referring to the project "weekly-schedule" of "brokencode.co".<br>
The "brokencode.co" project had a scheduled range of 2 to 3 hours. So, I revised the time table to an hour, and added additional tasks to add more various schedules. <br>Also, there was no function to delete the task individually, but I added it because I thought I needed it.
