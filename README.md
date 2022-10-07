<h1 align=center> Face Recognition Login System </h1>
<hr/>
<h4 align="center"> :camera: A facial recognition based login system using Python,HTML,CSS and Bootstrap 
</h4>
<h2>Preview</h2>

<hr/>
<h2> Tools & Libraries Used </h2>
<hr/>
<ul>
  <b>

<li> XAMPP - https://www.apachefriends.org/download.html </li>
<li> Bootstrap - https://getbootstrap.com/ </li>
<li> CGI </li>
    
    
  </b>
</ul>
<strong> Note </strong>  - These files must be hosted on XAMPP Apache server or other server, else login.py will not work.

<hr/>
<h2> Working </h2>

- Install Python
- Install XAMPP
- Navigate to `htdocs` fodler and clone this project.
- Open `login.py` and make sure to replace the top comment #!'C:\Users\aksha\AppData\Local\Programs\Python\Python310\python.exe' with your python path.
- Navigate to `htdocs/face-recognition-login-system` and execute the following command `pip install -r requirements.txt`
- Navigate to `xampp/apache/config` and modify the `httpd.conf` file by adding  
```conf
Options Indexes FollowSymLinks Includes ExecCGI
AddHandler cgi-script .py .cgi .pl .asp
```   
at the end of the file. Then save & exit
- Then run XAMPP & go to `localhost/face-recognition-login-system/login.html`
- Put all the images of students in the 'students' folder 
  
- Pictures must be in the format (email_address_of_student).jpg 
 

<b>Optional -</b> <i>you can create a seperate registration form for students, where they may upload their picture and the picture gets stored as (email_address).jpg in the 'students' folder.</i>

<hr/>

<h2> Making it work for Windows </h2>
<p>
Go to the python's installed location , in my case it was (C:\Python3.10) and right click on the 
python3.10folder and go to security tab and give "Full Control" permission to users
</p>
</br/>
<p>
And then go the scripts folder in python's installed path
(C:\Python3.10\Scripts)
</p>
and run the below commands in that folder 
<br/>

Command 1 : `C:\python3.10\python.exe -m pip install --upgrade pip --user`

In the above command replace the exe path with your path

Comand 2 : `pip install cmake --ignore-installed`

Command 3 : `pip install dlib --ignore-installed`

Command 4 : `pip install face_recognition --ignore-installed`

Then try to restart the XAMPP Server it should work.

If it did not work, try installing below tools on windows
- CMAKE
- Visual Studio with CMAKE Build tools installed


