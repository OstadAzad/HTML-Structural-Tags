==============================Introduction to HTML==================================

📘 HTML (HyperText Markup Language)
📝 Short Notes – Key Points

HTML এর পূর্ণরূপ HyperText Markup Language

ওয়েব পেজ তৈরির মূল কাঠামো তৈরি করতে ব্যবহার হয়

HTML এ লেখা হয় ট্যাগ (tag) এবং এলিমেন্ট (element) দিয়ে

ব্রাউজার HTML কোড পড়ে ব্যবহারকারীর কাছে ওয়েবপেজ আকারে দেখায়

CSS (স্টাইল) এবং JavaScript (কার্যকারিতা) যুক্ত হয়ে ওয়েবসাইটকে সুন্দর ও ইন্টারঅ্যাকটিভ করে

🧩 Concept Explanations – Step by Step

HTML কী?

ওয়েবসাইটের ভাষা। এটি ওয়েবপেজে কনটেন্ট সাজায়, যেমন লেখা, ছবি, লিঙ্ক, টেবিল ইত্যাদি।

কেন প্রয়োজন?

যেকোনো ওয়েবপেজ তৈরি করতে বেসিক স্ট্রাকচার লাগে। সেটাই HTML দেয়।

HTML কিভাবে কাজ করে?

HTML কোড = ট্যাগ + কনটেন্ট

ব্রাউজার কোড পড়ে ওয়েবপেজ রেন্ডার করে।

ট্যাগের ধরন:

Opening Tag: <p>

Closing Tag: </p>

Self-closing Tag: <br />, <img />

HTML Document Structure:

<!DOCTYPE html>
<html>
  <head>
    <title>আমার প্রথম ওয়েবপেজ</title>
  </head>
  <body>
    <h1>হ্যালো বিশ্ব!</h1>
    <p>এটি আমার প্রথম ওয়েবপেজ।</p>
  </body>
</html>

✨ Short Summary

HTML হলো ওয়েবপেজ তৈরির বেসিক ভাষা

এটি কন্টেন্টকে সাজায়, কাঠামো দেয়

ট্যাগ ও এলিমেন্ট দিয়ে কাজ করে

CSS ও JS যোগ করে আধুনিক ওয়েব তৈরি হয়

❓ Practice Questions with Answers

HTML এর পূর্ণরূপ কী?
→ HyperText Markup Language

<img> ট্যাগ কি Self-closing নাকি Container?
→ Self-closing

<ol> আর <ul> এর পার্থক্য কী?
→ <ol> = Ordered (সংখ্যা/ক্রম), <ul> = Unordered (বুলেট)

💼 Common Interview Questions with Answers

HTML এবং XHTML এর পার্থক্য কী?
→ XHTML বেশি কঠোর, সব ট্যাগ ক্লোজ করতে হয়, case-sensitive

HTML5 এ নতুন কী এসেছে?
→ <video>, <audio>, <canvas>, semantic tags যেমন <header>, <footer>

HTML কি প্রোগ্রামিং ল্যাঙ্গুয়েজ?
→ না, এটি একটি Markup Language

=============================HTML Structure and Basic Tags================================

🌐 HTML Structure এবং Basic Tags
🔹 Short Notes – দ্রুত বোঝার মূল পয়েন্ট

HTML = HyperText Markup Language

ওয়েবপেজ তৈরির কাঠামো (Structure) তৈরি করে

HTML ট্যাগগুলো শুরু <tag> এবং শেষ </tag> দিয়ে গঠিত

প্রতিটি HTML ফাইল শুরু হয় <!DOCTYPE html> দিয়ে

মূল কাঠামোতে থাকে:

<html> → পুরো পেজ

<head> → মেটা ইনফো, টাইটেল, লিংক, স্টাইল

<body> → ব্যবহারকারীর জন্য দৃশ্যমান কন্টেন্ট

🔹 Concept Explanations – ধাপে ধাপে ব্যাখ্যা
1. HTML কীভাবে কাজ করে?

HTML হচ্ছে ওয়েবপেজের কঙ্কাল (skeleton)। CSS দিয়ে এটাকে সুন্দর করা হয়, আর JavaScript দিয়ে কাজ করানো হয়।

2. HTML Structure-এর প্রধান অংশ
<!DOCTYPE html>
<html>
<head>
    <title>আমার প্রথম ওয়েবপেজ</title>
</head>
<body>
    <h1>হ্যালো, ওয়েব ডেভেলপমেন্ট!</h1>
    <p>এটি একটি অনুচ্ছেদ।</p>
</body>
</html>


👉 এখানে

<!DOCTYPE html> → ব্রাউজারকে জানায় এটি HTML5

<html> → মূল root element

<head> → ওয়েবপেজের টাইটেল, মেটা তথ্য

<body> → যা ব্যবহারকারীরা দেখতে পায়

3. Basic Tags

<h1> থেকে <h6> → শিরোনাম

<p> → অনুচ্ছেদ

<a> → লিংক

<img> → ছবি

<ul>/<ol>/<li> → তালিকা

<div> এবং <span> → Layout/structure এর জন্য

🔹 Short Summary

HTML হলো ওয়েবপেজের গঠন তৈরির ভাষা। এর মধ্যে <html>, <head>, <body> প্রধান কাঠামো, আর Basic Tags দিয়ে টেক্সট, ছবি, লিংক ইত্যাদি যোগ করা হয়।

🔹 Examples (৫–১০টি উদাহরণ)

শিরোনাম

<h1>বড় শিরোনাম</h1>
<h3>ছোট শিরোনাম</h3>


অনুচ্ছেদ

<p>এটি একটি অনুচ্ছেদ।</p>


লিংক

<a href="https://www.google.com">Google এ যান</a>


ছবি

<img src="image.jpg" alt="একটি ছবি">


তালিকা

<ul>
  <li>আপেল</li>
  <li>কলা</li>
  <li>আম</li>
</ul>


টেবিল

<table border="1">
  <tr><th>নাম</th><th>বয়স</th></tr>
  <tr><td>আজাদ</td><td>২২</td></tr>
</table>


বোল্ড এবং ইটালিক

<b>গুরুত্বপূর্ণ</b> এবং <i>আন্ডারলাইন</i>

🔹 Mini Projects (৩টি ছোট প্রজেক্ট)
🟢 প্রজেক্ট ১: ব্যক্তিগত প্রোফাইল পেজ

<h1> → নাম

<p> → নিজের পরিচিতি

<img> → প্রোফাইল ছবি

🟢 প্রজেক্ট ২: একটি প্রোডাক্ট লিস্ট

<h2> → প্রোডাক্ট নাম

<ul> → প্রোডাক্ট ফিচার লিস্ট

<a> → কিনতে লিংক

🟢 প্রজেক্ট ৩: একটি ছোট টেবিল বানানো

<table> → ছাত্রদের নাম ও গ্রেড

🔹 Practice Questions with Answers

Q1: কোন ট্যাগ শিরোনামের জন্য ব্যবহৃত হয়?
👉 <h1> থেকে <h6>

Q2: <a> ট্যাগের কাজ কী?
👉 লিংক তৈরি করা

🔹 Common Interview Questions with Answers

Q: HTML কি প্রোগ্রামিং ল্যাঙ্গুয়েজ?
👉 না, এটি একটি মার্কআপ ল্যাঙ্গুয়েজ।

Q: <head> এবং <body> এর পার্থক্য কী?
👉 <head> এ তথ্য থাকে, <body> এ ব্যবহারকারীর জন্য কন্টেন্ট থাকে।

===================HTML Audio and Video Elements====================

🎵🎥 HTML Audio & Video Elements – বাংলায় সম্পূর্ণ গাইড
📝 Short Notes – দ্রুত বোঝার জন্য মূল পয়েন্টগুলো

<audio> → ওয়েবসাইটে অডিও ফাইল এম্বেড করতে ব্যবহৃত হয়।

<video> → ওয়েবসাইটে ভিডিও ফাইল এম্বেড করতে ব্যবহৃত হয়।

controls → প্লে/পজ, ভলিউম, টাইমলাইন ইত্যাদি দেখানোর জন্য ব্যবহার হয়।

autoplay, loop, muted → অডিও/ভিডিওর প্লে-বিহেভিয়ার নিয়ন্ত্রণ করে।

<source> ট্যাগ → একাধিক ফরম্যাট (যেমন MP3, OGG, MP4, WebM) সাপোর্ট করার জন্য ব্যবহৃত হয়।

সব ব্রাউজার সব ফরম্যাট সাপোর্ট করে না → তাই multiple sources দেওয়া ভালো।

📖 Concept Explanations – ধাপে ধাপে ব্যাখ্যা
1. <audio> element

HTML এ অডিও যোগ করার জন্য <audio> ট্যাগ ব্যবহার করা হয়।
Structure:

<audio controls>
  <source src="music.mp3" type="audio/mpeg">
  <source src="music.ogg" type="audio/ogg">
  আপনার ব্রাউজার অডিও সাপোর্ট করে না।
</audio>

2. <video> element

ভিডিও যোগ করার জন্য <video> ট্যাগ ব্যবহার করা হয়।
Structure:

<video width="400" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.webm" type="video/webm">
  আপনার ব্রাউজার ভিডিও সাপোর্ট করে না।
</video>

3. গুরুত্বপূর্ণ Attributes

controls → ইউজার কন্ট্রোল বোতাম পায়।

autoplay → পেজ লোড হতেই অডিও/ভিডিও চালু হয়।

loop → শেষ হলে আবার শুরু হয়।

muted → ডিফল্ট ভাবে সাউন্ড অফ থাকে।

poster (শুধু ভিডিওর জন্য) → ভিডিও চালু হওয়ার আগে একটি ছবি দেখায়।

preload → মিডিয়া আগে থেকে লোড করবে কি না (auto, metadata, none)।

📌 Short Summary

ওয়েবপেজে অডিও/ভিডিও এম্বেড করতে <audio> ও <video> ব্যবহার হয়।

ইউজার এক্সপেরিয়েন্স ভালো করার জন্য controls, autoplay, loop, poster ইত্যাদি attributes ব্যবহার করা হয়।

বিভিন্ন ব্রাউজার সাপোর্টের জন্য multiple <source> দেওয়া বেস্ট প্র্যাকটিস।

⚠️ Common Mistakes to Avoid

শুধু এক ফরম্যাট ব্যবহার করা (সব ব্রাউজারে কাজ নাও করতে পারে)।

autoplay ব্যবহার করে muted না দেওয়া → ব্রাউজার ব্লক করতে পারে।

controls বাদ দিলে ইউজার ভিডিও চালাতে পারবে না।

❓ Practice Questions with Answers

Q1: <audio> এবং <video> এর মূল পার্থক্য কী?
👉 <audio> শুধুমাত্র অডিওর জন্য, <video> ভিডিও (সাউন্ড সহ) এর জন্য।

Q2: কেন multiple <source> ব্যবহার করা হয়?
👉 বিভিন্ন ব্রাউজারে আলাদা ফরম্যাট সাপোর্ট করার জন্য।

Q3: poster attribute কোথায় ব্যবহার হয়?
👉 <video> তে, ভিডিও শুরু হওয়ার আগে ইমেজ দেখানোর জন্য।

💼 Common Interview Questions with Answers

Q1: autoplay কেন অনেক ব্রাউজারে কাজ করে না?
👉 ব্রাউজার ইউজারের অভিজ্ঞতা রক্ষা করতে sound সহ autoplay ব্লক করে। এজন্য muted দিতে হয়।

Q2: <track> element এর ব্যবহার কী?
👉 ভিডিওতে সাবটাইটেল বা ক্যাপশন যোগ করতে।

Q3: preload এর ধরনগুলো কী?
👉 auto, metadata, none।

