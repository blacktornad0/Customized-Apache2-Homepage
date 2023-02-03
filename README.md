# Customized-Apache2-Homepage
This looks cool and amazing...! Check it out.


# Installation Manual...!
<body>
  <p> 1. Open your Kali Linux </p>
  <img src="https://user-images.githubusercontent.com/89218236/216540518-c2b03552-2744-4052-bb8c-9a77430ca6c3.jpg">
  <p> 2. Login with your credentials </p>
  <img src="https://user-images.githubusercontent.com/89218236/216540604-4660f047-cd4f-4403-b293-aaee595136c9.jpg">
  <p> 3. Open your Terminal... </p>
  <img src="https://user-images.githubusercontent.com/89218236/216540639-90c2f522-5831-4c2e-959c-5702b31c0732.jpg">
  <p> 4. Execute command "<b>sudo su root</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216540722-87ff3d5e-a6e4-443d-88f5-09468438bfc7.jpg">
  <p> 5. Enter your root password... </p>
  <img src="https://user-images.githubusercontent.com/89218236/216540804-f4ad76d0-81d2-490c-b755-da00a0ad6e0c.jpg">
  <p> 6. Execute command "<b>cd /var/www/html/</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216540864-a27bf4ba-b107-4809-b50d-f4aa97808b35.jpg">
  <p> 7. Execute command "<b>ls</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216540941-9d0f269a-815b-45c3-9755-7a0044c1e368.jpg">
  <br>
  <hr>
  <p><b><u>Note:</u></b></p>
  <p><b><i> You will now see "index.html" and "index.nginx-debian.html" as the output since those are the default files for the Apache2 Homepage... <br> Now we have to remove those files and then add our Customised Apache2 Homepage files...</i></b></p>
  <hr>
  <br>
  <p> 8. Execute command "<b>rm index.html index.nginx-debian.html</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216543398-4ca895ad-5a46-4c8a-90e5-47fcc5143424.jpg">
  <p> 9. Execute command "<b>ls</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216543455-0952511b-cfd6-434f-bad7-e324e1c2c181.jpg">
  <br>
  <hr>
  <p><b><u>Note:</u></b></p>
  <p><b><i> You will now see nothing as the output as we have removed the default Apache2 Homepage files...<br> It is now time to put our Customized Apache2 Homepage files in that same directory...</i></b></p>
  <hr>
  <br>
  <p> 10. Execute command "<b>git clone https://github.com/blacktornad0/Customized-Apache2-Homepage.git</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216545642-33c24e98-2c50-44d3-9fc4-dd002b19adc9.jpg">
  <p> 11. Execute command "<b>ls</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216557910-bb37584c-2344-4e65-b032-7796d6757827.jpg">
  <p> 12. Execute command "<b>cd Customized-Apache2-Homepage</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216558050-c1f4d4ed-6f72-49aa-9d44-b4a28c8a639d.jpg">
  <p> 13. Execute command "<b>ls</b>"</p>
  <img src="https://user-images.githubusercontent.com/89218236/216558125-130d3215-f5b2-4f21-a61c-f54fa0e6d38c.jpg">
  <br>
  <hr>
  <p><b><u>Note:</u></b></p>
  <p><b><i>In order for this to work, You have got to move the files in the "Customized-Apache2-Homepage" directory to the "/var/www/html/" location... <br>Then grant permission to those files...</i></b></p>
  <hr>
  <br>
  <p> 14. Execute command "<b>mv blog Blog-Template.css fonts Homepage.css Homepage.html images index.html intlTelInput jquery.js nicepage.css nicepage.js Post-Template.css README.md .git /var/www/html/</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216558197-83402f5f-a698-49eb-b870-34b659300445.jpg">
  <p> 15. Execute command "<b>cd ..</b>"</p>
  <img src="https://user-images.githubusercontent.com/89218236/216558239-03761b78-637c-4c60-8833-6e1cbff51884.jpg">
  <p> 16. Execute command "<b>rmdir Customized-Apache2-Homepage</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216558344-f19995fb-a4dd-49cd-8420-d23dc80259d3.jpg">
  <br>
  <hr>
  <p><b><u>Note:</u></b></p>
  <h1><b># Permission Granting Process...</b></h1>
  <p> 17. Execute command "<b>chmod +777 Blog-Template.css Homepage.css Homepage.html index.html jquery.js nicepage.css nicepage.js Post-Template.css README.md</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216576837-543b58dd-d9f0-4886-9563-284ffeabd72e.jpg">
  <p> 18. Execute command "<b>cd blog</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216576762-13670074-447c-4928-8170-a25c271f87d6.jpg">
  <p> 19. Execute command "<b>chmod +777 . blog.html post-1.html post-2.html post-3.html post-4.html post-5.html post.html</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216576668-9e95cfd5-be91-4926-bb59-d96de249165d.jpg">
  <p> 20. Execute command "<b>cd ..</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216576602-e079a76a-f34b-4e60-a02d-f6f5f936a799.jpg">
  <p> 21. Execute command "<b>cd fonts</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216576527-7d2b72e4-1789-412d-b44e-51ae1990ebe6.jpg">
  <p> 22. Execute command "<b>chmod +777 . .. StrangerbackintheNight.ttf OriginTechpersonaluse.ttf</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216576483-2d72c3c1-ee9f-4200-b56f-8fe1cde603b4.jpg">
  <p> 23. Execute command "<b>cd ..</b>" </p>
  <p> 24. Execute command "<b>cd images</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216576393-9142625c-a981-40f2-b738-1d08734cbf71.jpg">
  <p> 25. Execute command "<b>chmod +777 . .. 0fd3416c.jpeg 68f64b9d.jpeg 8ad73f3c.jpeg c46b514c8f7cf7f83f0b39fbebc4763c847324677fda80541a82de878f3374bbc473f0f5c1610ac0744eb6a7997c8d81ad32a43318ca45d7b5abc9_1280.jpg default-logo.png favicon.jpg</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216576348-d23de4f4-1d51-417b-882f-e96615d9d5cb.jpg">
  <p> 26. Execute command "<b>cd ..</b>" </p>
  <p> 27. Execute command "<b>cd intlTelInput</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216576227-9f81a331-e144-48e3-bdb9-8c77eef4d2a8.jpg">
  <p> 28. Execute command "<b>chmod +777 . .. utils.js intlTelInput.css intlTelInput.min.js</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216576205-0142b075-4d85-424f-a3bf-c39a13bba86c.jpg">
  <p> 23. Execute command "<b>cd ..</b>" </p>
  <br>
  <p style="text-align:center;"><b> End of permission  granting... </b></p>
  <hr>
  
  # Once you have done everything above, close your terminal...
  <p> Then, open your terminal again...</p>
  <img src="https://user-images.githubusercontent.com/89218236/216582795-c6399fbc-54c1-4605-9831-8e8d855916a8.png">
  <p> Execute command "<b>service apache2 start"</b> </p>
  <img src="https://user-images.githubusercontent.com/89218236/216583097-5658cbb0-53a8-470c-9463-4816ec5215aa.png">
  <p> Then enter your root password to continue...</p>
  <img src="https://user-images.githubusercontent.com/89218236/216583410-ac0871a5-599b-4197-955e-c268453182ae.png">
  <p> To check if Apache2 service is running, execute command "<b>service apache2 status</b>" </p>
  <img src="https://user-images.githubusercontent.com/89218236/216584115-929195af-0d29-4f39-9b9f-e256db74bc58.png">
  <p> Then go to Firefox, and type <b>localhost</b> in the top searchbar and hit enter on your keyboard </p>
  <img src="https://user-images.githubusercontent.com/89218236/216585925-1127d46f-a15c-4183-a198-938933979bc8.png">
  <p> The final result should look like this👇👇👇👇 </p>
  

https://user-images.githubusercontent.com/89218236/216612618-22d0792e-7db3-4b7d-9790-ef2f74f00baf.mp4


  <br>
  <hr>
  <p><b><u>Note:</u></b></p>
  <p><b><i>If it didn't work, Revise the manual, follow the steps and try again and it should work...!</i></b></p>
  <br>
  <hr>
</body>
