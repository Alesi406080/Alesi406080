- 👋 Hi, I’m @Alesi406080
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Alesi406080/Alesi406080 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

Mail::send('emails.contactemail', $emailcontent, function($message)
 {
 $message->to('Sahil451github@gmail.com','Send Email for help')
 ->subject('Contact via Our Contact Form');
});
