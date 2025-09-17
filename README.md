JISA
retzgeyzer
(*´ω`*)

JISA — 4/19/2025 18:23
JISA — 4/19/2025 18:37
JISA — 4/19/2025 18:51
JISA — 4/21/2025 10:45
Image
Image
JISA — 4/23/2025 13:35
https://eventing.coursera.org/redirect/xqqr5AxyAA1CuVpuyhxZyIQIm0Mr49XK1CF14P5-gDPmAQIVs2VTgjTYTc_AjGcL7TNudClXsqX8Ldqpu6POzQ.RZcf9nRpL5d4KaL4G9Qw3g.HiXv_ChUtWAqChQgC7k8T0vQMked7Wn-A-nhHiHbKY31EcqZpzUH8TNkdOM_itS1rOKTIKk_SclzwxCwC-hNThsOoh_wuiwOmA7Z3yZ-6zjuo7QpRT8P1LlHJPKhYPOPIbyLWw10dk_wnylseNHAmR-YqNOoNI7ed-xcn5Pz3tixleLrXa2j-jHiPSsBz4zYbKeSni5SvwxitRVsJk-zSDysx_Xxf3stU1X9ujfT8P5KV0mBZ8MgVfngnLK-35KKfFzH0C-MAepqFILDweKYtW3sdGgtOxV0CMhEhYWRbOk7bFidkhrR_N8mHS0af5aPblVMCqEaKh3hqbPKOKZf9BboVY434EN91guxYlt1Y7azId2JBE-m6UM9r5Pc9Z7ulLak_dqIwbCALubMfDp_pKkk6X7t7PUgfn0rebAVuGnbTQaWi_7WiA9hKMPAhBtMj667TscT9WKFTT3S9FqR7uOlJRAc60W_rhR6YnZXBV33e5mwlx-KhYuyyz1Elbfz
Coursera
Coursera | Online Courses & Credentials From Top Educators. Join fo...
Learn online and earn valuable credentials from top universities like Yale, Michigan, Stanford, and leading companies like Google and IBM. Join Coursera for free and transform your career with degrees, certificates, Specializations, & MOOCs in data science, computer science, business, and dozens of other topics.
Image
JISA — 4/23/2025 16:41
Image
JISA — 4/24/2025 09:37
https://tmc.mooc.fi/org/mooc/courses/281
TestMyCode
https://materiaalit.github.io/2013-oo-programming/part2/week-9/
JISA — 4/24/2025 09:45
Berikut query SQL untuk masing-masing soal berdasarkan struktur data dari gambar dan isi dokumen soal week 10.doc:

---

Menampilkan data customer dengan format tertentu


SELECT 
  CONCAT('DL [', UPPER(Nama), '[', KodeCust, ']]') AS data_customer,
  CONCAT('JL-', Alamat, ' ', Kota) AS alamat,
  Telpon AS telepon
FROM Customer;


---

Menampilkan nokamar dan jenisnya beserta harga


Misalnya, ada tabel JenisKamar yang berisi kode jenis dan harga:

-- Asumsikan tabel JenisKamar (KodeJenis, NamaJenis, Harga)
SELECT 
  CONCAT('[', NoKamar, '] dengan jenis ', NamaJenis, ' memiliki harga ', Harga) AS info_kamar
FROM Kamar
JOIN JenisKamar ON Kamar.KodeJenis = JenisKamar.KodeJenis;


---

Menampilkan jumlah kamar berdasarkan jenis


SELECT 
  CONCAT('(', NamaJenis, ') memiliki ', COUNT(*) , ' kamar') AS jumlah_kamar
FROM Kamar
JOIN JenisKamar ON Kamar.KodeJenis = JenisKamar.KodeJenis
GROUP BY NamaJenis;


---

Menampilkan nama customer, jumlah transaksi, dan total lama menginap


SELECT 
  c.Nama,
  COUNT(h.KodeCIn) AS jumlah_trans,
  SUM(DATEDIFF(d.TglCOut, h.TglCIn)) AS Total_Menginap
FROM HCheckin h
JOIN DCheckin d ON h.KodeCIn = d.KodeCIn
JOIN Customer c ON h.KodeCust = c.KodeCust
GROUP BY c.Nama;


---

Menampilkan jumlah transaksi checkout pada setiap tanggal


SELECT 
  CONCAT('jumlah transaksi yang melakukan checkout pada ', TglCOut, ' sebanyak ', COUNT(*) ) AS keterangan
FROM DCheckin
GROUP BY TglCOut;


---

Kalau kamu mau query-nya dalam format khusus seperti cetakan di Word, tinggal tambahkan CONCAT atau ubah output di aplikasi. Mau saya bantu bikin output-nya lebih mirip gaya Word juga?
JISA — 4/24/2025 20:56
Image
JISA — 4/24/2025 23:28
Image
Image
JISA — 4/26/2025 09:59
https://apply.appledeveloperacademy.uc.ac.id/application/motifolio
JISA — 4/28/2025 19:13
Attachment file type: unknown
Tugas Video 2.piv
1.17 MB
JISA — 5/1/2025 00:41
(´ω`)
JISA — 5/5/2025 20:30
Left page is just the default portfolio page view. Right page is when a project is clocked and content expands
JISA — 5/11/2025 02:39
https://www.tiktok.com/@lumi3refinds?_t=ZS-8wFNRJbZjgO&_r=1
TikTok
LumièreFinds on TikTok
@lumi3refinds 598 Followers, 78 Following, 86 Likes - Watch awesome short videos created by LumièreFinds
Image
JISA — 5/17/2025 02:18
/clone 1672 80 -243 1668 82 -235 1663 80 -234 
JISA — 5/17/2025 03:16
/summon arrow 1664 111 -229
turip ip ip ip
 started a call that lasted 27 minutes. — 5/28/2025 00:15
JISA
 started a call that lasted a few seconds. — 5/29/2025 01:16
JISA
 started a call that lasted 22 minutes. — 5/29/2025 01:16
JISA — 6/1/2025 00:25
https://youtube.com/shorts/uWEIaF0PNGg?si=g2Dg9943GRB1H9a1
YouTube
b001
Python OPTIMIZATION Trick!!  #python #programming #coding
Image
JISA — 6/3/2025 00:30
https://claude.ai/share/e829b57d-f895-49d4-bab4-792a1e403c7f
JISA — 6/8/2025 09:36
Image
JISA — 6/9/2025 12:10
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
Image
JISA — 6/12/2025 08:24
ETR0D-NCV0M-4H2H9
JISA — 6/24/2025 00:47
tes
JISA — 6/27/2025 15:34
ML85EHQD4X5P9MA3VEJ6V77L
JISA — 6/28/2025 21:15
@BEN:convert the photo above into a set of 12 chibi sticker ( 4 * 4 grid) costumes like this image including expression laughing loudly, angry, crying, sulking, thinking, sleepy, winking, winking, surprise
Image
JISA — 6/30/2025 03:55
@h:convert the photo above into a set of 12 chibi stickers (4 * 4
grid) costumes like this image including expressions laughing loudly, angry, crying, sulking thinking, sleepy,
winking, dancing, hitting, pouchi
JISA — 6/30/2025 04:24
@♡:take an extremely ordinary and remarkable iPhone selfie, with no clear subject or sense of composition just quick accidental snapshots. the photo has slight motion blur and an even lighting from street light or indoor lamps causing mind over exposure in some areas. the angle is awkward in the framing is Messy, giving the picture a deliverately mediocre feel as if it was taken absent mindedly while pulling the phone from the pocket the main character is [uploaded person]
JISA — 6/30/2025 12:46
https://www.facebook.com/share/16T1vH8e8m/
Log in or sign up to view
See posts, photos and more on Facebook.
JISA — 7/10/2025 02:21
However, we never forget the most important element of an admissions essay – it is a story --- a story about you! This story needs to be profound and engaging and ultimately make the admissions committee stop and say, "Wow … I want to admit this applicant to my university!"

With our help you could be the next "TopAdmit" to an elite university.
JISA — 7/12/2025 05:07
jen nute
mute
JISA — 7/19/2025 05:16
Image
JISA — 7/20/2025 10:23
@★𝑰𝒔𝒚𝒓𝒂𝒇𝒇✰:Create an image of a selfie taken with an Iphone, without any clear subject or composition-just a random snapshot taken unintentionally. The image should have slight motion blur and consistent lighting from streetlights. Bot! images should be connected.
JISA — 8/11/2025 03:20
make script worldbox python
JISA — 8/11/2025 12:37
https://www.figma.com/file/Qyfta0Ddi8yz65eIVsxpEI/DD-Walk-App-Product-tree?resource_type=file&email=evanwilliam303%40gmail.com&is_not_gen_0=true&editor_type=design
Figma
DD Walk App - Product tree
Created with Figma
Image
JISA — 8/14/2025 23:15
Image
JISA — 8/22/2025 01:08
BAWA ALEMT BAWA ALMET
JISA — 8/26/2025 02:24
Engineer @ Sophistec Dev House | Passionate About Python, Web, & AI | Undergraduate in Informatics Engineering
JISA — 8/31/2025 04:35
siege mod mc
JISA — 9/13/2025 13:45
@jerkkk:Please create a Vertical portrait shot in 1080x1920 format using the exact same face features, characterized by stark cinematic lighting and intense contrast. Captured with a slightly low, upward-facing angle that dramatizes the subject's jawline and neck, the composition evokes quiet dominance and sculptural elegance. The background is a deep, saturated crimson red, creating a bold visual clash with the model's luminous skin and dark wardrobe.
JISA — Yesterday at 02:31
02:24:38] [Netty Server IO #2/INFO] [dimstack]: Sending dimension stack configuration packet to Rabpitz
[02:24:38] [Server thread/INFO] [FML]: [Server thread] Server side modded connection established
[02:24:39] [Server thread/INFO] [gamestages]: Could not find legacy data for 1424f3ac-f5f1-488d-8e2b-f233f51e26da.
Patched max stack check in lain/mods/cos/api/inventory/CAStacksBase -> getSlotLimit!
[02:24:39] [Server thread/ERROR] [cyclicmagic]: Data not found for Rabpitz
[02:24:39] [Server thread/INFO] [minecraft/PlayerList]: Rabpitz[/26.41.183.199:62589] logged in with entity id 497 at (-96.5, 68.0, 131.5)
Expand
message.txt
26 KB
JISA — 01:32
# ⚡ Welcome to My Digital Universe ⚡

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:001122,30:003366,70:0066CC,100:00AAFF&height=300&section=header&text=EVAN%20WILLIAM&fontSize=50&fontColor=00FFFF&animation=blinking&fontAlignY=38&desc=⚡%20Full-Stack%20Developer%20%7C%20ML%20Engineer%20%7C%20AI%20Enthusiast%20⚡&descAlignY=65&descSize=20" />
</div>

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=28&duration=2800&pause=900&color=00CCFF&center=true&vCenter=true&width=1000&lines=🎓+Informatics+Engineering+Student;🐍+Python+%7C+⚡+Machine+Learning+%7C+📊+Data+Science;💻+JavaScript+%7C+🌊+C%2B%2B+%7C+🔧+PHP+%7C+🗄️+SQL;🤖+Building+AI-Powered+Solutions;🚀+Open+Source+Contributor+%26+Innovator;🌍+From+Indonesia+with+Code+❤️" />
</div>

<br>

<div align="center">
<a href="https://www.linkedin.com/in/evanwilliam03/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&color=00AAFF" alt="LinkedIn"/>
</a>
<a href="mailto:evanwilliam303@gmail.com">
<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&color=FF4444" alt="Gmail"/>
</a>
<a href="https://github.com/evan-william">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white&color=333333" alt="GitHub"/>
</a>
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="450" />
</div>

---

## 🎯 About Me - The Digital Architect

<img align="right" alt="Coding" width="400" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif">

```python
class EvanWilliam:
    def __init__(self):
        self.name = "Evan William"
        self.location = "Indonesia 🇮🇩"
        self.education = "Informatics Engineering @ UKWMS"
        self.status = "Student & Developer"
        self.motto = "Code with Purpose, Build with Passion"
        
    def current_focus(self):
        return {
            "learning": ["Deep Learning", "Computer Vision", "NLP"],
            "building": ["ML Models", "Web Applications", "Data Pipelines"],
            "exploring": ["PyTorch", "TensorFlow", "FastAPI"]
        }
    
    def tech_philosophy(self):
        return "Innovation through iteration, perfection through practice"
    
    def availability(self):
        return {
            "collaborations": "✅ Open",
            "internships": "✅ Seeking",
            "freelance": "✅ Available",
            "coffee_chat": "☕ Always!"
        }

# Let's build something extraordinary together! 🚀
evan = EvanWilliam()
```

### 📈 Quick Facts

- 🔭 Currently working on **AI/ML projects** and **web applications**
- 🌱 Learning **Deep Learning** and **Advanced Data Science**
- 👯 Looking to collaborate on **open source projects**
- 💬 Ask me about **Python, Machine Learning, Web Development**
- 📫 Reach me at **evanwilliam303@gmail.com**
- ⚡ Fun fact: **I debug with coffee and solve problems with algorithms!**

---

## 🛠️ Tech Arsenal & Skills

<div align="center">

### Languages & Frameworks
<p>
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### AI/ML & Data Science
<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>
... (NaN KB left)
Collapse
message.txt
13 KB
# ⚡ Welcome to My Github's Space ⚡

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=shark&color=0:001122,30:003366,70:0066CC,100:00AAFF&height=350&section=header&text=EVAN%20WILLIAM&fontSize=45&fontColor=00FFFF&animation=blinking&fontAlignY=38&desc=⚡%20Full-Stack%20Developer%20%7C%20ML%20Engineer%20⚡&descAlignY=60&descSize=20" />
</div>
Expand
message.txt
11 KB
# ⚡ Welcome to My Github's Space ⚡

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=shark&color=0:001122,30:003366,70:0066CC,100:00AAFF&height=350&section=header&text=EVAN%20WILLIAM&fontSize=45&fontColor=00FFFF&animation=blinking&fontAlignY=38&desc=⚡%20Full-Stack%20Developer%20%7C%20ML%20Engineer%20⚡&descAlignY=60&descSize=20" />
</div>

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=26&duration=2500&pause=800&color=00CCFF&center=true&vCenter=true&width=900&lines=⚡+Informatics+Engineering+Student+⚡;🔵+Python+%7C+⚡+Machine+Learning+%7C+📊+Data+Science;💻+JavaScript+%7C+🌊+C%2B%2B+%7C+🔧+PHP+%7C+🗄️+SQL;🌀+Building+Innovative+Software+Solutions;🤝+Open+to+Professional+Collaborations!" />
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="400" />
</div>

---

## 👨💻 About Me - The Digital Architect

<table>
<tr>
<td width="50%">

### 🎯 Personal Profile

```python
class EvanWilliam:
    def __init__(self):
        self.name = "Evan William"
        self.location = "Indonesia 🇮🇩"
        self.education = "Informatics Engineering @ UKWMS"
        self.status = "Student & Developer"
        
    def current_focus(self):
        return [
            "🤖 Machine Learning",
            "📊 Data Science", 
            "🌐 Web Development"
        ]
    
    def tech_stack(self):
        return {
            "languages": ["Python", "JavaScript", 
                         "C++", "PHP", "SQL"],
            "interests": ["AI/ML", "Data Analysis", 
                         "Open Source"],
            "mindset": "Continuous Learning"
        }
    
    def say_hello(self):
        return "Let's build something amazing! ⚡"

# Initialize
evan = EvanWilliam()
print(evan.say_hello())
```

</td>
<td width="50%">

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="250" />
</div>

### 📍 Profile Highlights

- 🌍 **Location**: Indonesia 🇮🇩
- 🎓 **Education**: Informatics Engineering @ UKWMS
- 💡 **Focus**: Machine Learning, Data Science, Web Development
- ⚡ **Passion**: AI & Innovation
- 🤝 **Status**: Open to Collaborations

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=16&duration=3000&pause=1000&color=00AAFF&center=true&vCenter=true&width=400&lines=Innovation+through+Code+⚡;Data-Driven+Solutions+📈;AI+Enthusiast+🤖;Problem+Solver+🌟" />
</div>

</td>
</tr>
</table>

---

## 🛠️ Tech Expertise & Skills

<div align="center">

### Languages & Frameworks
<p>
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### AI/ML & Data Science
<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" />
... (168 lines left)
Collapse
message.txt
11 KB
﻿
turip ip ip ip
turipremy
 
https://open.spotify.com/track/180AbZduI6bYQIzwCHRwu9?si=a0092b770b6c4ea2
# ⚡ Welcome to My Github's Space ⚡

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=shark&color=0:001122,30:003366,70:0066CC,100:00AAFF&height=350&section=header&text=EVAN%20WILLIAM&fontSize=45&fontColor=00FFFF&animation=blinking&fontAlignY=38&desc=⚡%20Full-Stack%20Developer%20%7C%20ML%20Engineer%20⚡&descAlignY=60&descSize=20" />
</div>

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=26&duration=2500&pause=800&color=00CCFF&center=true&vCenter=true&width=900&lines=⚡+Informatics+Engineering+Student+⚡;🔵+Python+%7C+⚡+Machine+Learning+%7C+📊+Data+Science;💻+JavaScript+%7C+🌊+C%2B%2B+%7C+🔧+PHP+%7C+🗄️+SQL;🌀+Building+Innovative+Software+Solutions;🤝+Open+to+Professional+Collaborations!" />
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="400" />
</div>

---

## 👨‍💻 About Me - The Digital Architect

<table>
<tr>
<td width="50%">

### 🎯 Personal Profile

```python
class EvanWilliam:
    def __init__(self):
        self.name = "Evan William"
        self.location = "Indonesia 🇮🇩"
        self.education = "Informatics Engineering @ UKWMS"
        self.status = "Student & Developer"
        
    def current_focus(self):
        return [
            "🤖 Machine Learning",
            "📊 Data Science", 
            "🌐 Web Development"
        ]
    
    def tech_stack(self):
        return {
            "languages": ["Python", "JavaScript", 
                         "C++", "PHP", "SQL"],
            "interests": ["AI/ML", "Data Analysis", 
                         "Open Source"],
            "mindset": "Continuous Learning"
        }
    
    def say_hello(self):
        return "Let's build something amazing! ⚡"

# Initialize
evan = EvanWilliam()
print(evan.say_hello())
```

</td>
<td width="50%">

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="250" />
</div>

### 📍 Profile Highlights

- 🌍 **Location**: Indonesia 🇮🇩
- 🎓 **Education**: Informatics Engineering @ UKWMS
- 💡 **Focus**: Machine Learning, Data Science, Web Development
- ⚡ **Passion**: AI & Innovation
- 🤝 **Status**: Open to Collaborations

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=16&duration=3000&pause=1000&color=00AAFF&center=true&vCenter=true&width=400&lines=Innovation+through+Code+⚡;Data-Driven+Solutions+📈;AI+Enthusiast+🤖;Problem+Solver+🌟" />
</div>

</td>
</tr>
</table>

---

## 🛠️ Tech Expertise & Skills

<div align="center">

### Languages & Frameworks
<p>
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### AI/ML & Data Science
<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

### Databases & Tools
<p>
<img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white" />
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
</p>

</div>

<div align="center">
<img src="https://skillicons.dev/icons?i=python,js,cpp,php,html,css,pytorch,sklearn,mysql,git,wordpress,vscode" alt="Tech Stack" />
</div>

---

## ⭐ Featured Project

<div align="center">

### ⚡ Personal Project Repository

<a href="https://github.com/evan-william/personal-project">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=evan-william&repo=personal-project&theme=tokyonight&hide_border=true&border_radius=15&bg_color=0d1117&title_color=00ccff&icon_color=00aaff&text_color=66ddff" />
</a>

</div>

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=16&duration=2500&pause=1000&color=00AAFF&center=true&vCenter=true&width=600&lines=🔬+Comprehensive+hub+of+projects+%26+experiments;💻+From+ML+models+to+software+development;📈+Innovation+%26+continuous+learning;🤝+Check+it+out+and+let's+collaborate!" />
</div>

---

## 📊 GitHub Analytics Dashboard

<div align="center">

### 🏆 Performance Overview

<div align="center">
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=evan-william&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=00ccff&icon_color=00aaff&text_color=66ddff&border_radius=15" width="100%" />
</div>

### 📈 Language Distribution

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=evan-william&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&bg_color=0d1117&title_color=00ccff&text_color=66ddff&border_radius=15&custom_title=Most%20Used%20Languages" />

### 📅 Contribution Activity

<img src="https://github-readme-activity-graph.vercel.app/graph?username=evan-william&bg_color=0d1117&color=00ccff&line=00aaff&point=0088ff&area=true&hide_border=true&custom_title=Coding%20Activity%20Timeline" width="100%" />

### 🏆 GitHub Achievements

<img src="https://github-profile-trophy.vercel.app/?username=evan-william&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&row=2&column=4" />

</div>

---

## 🎯 Future Focus Areas

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=20&duration=3000&pause=1000&color=00CCFF&center=true&vCenter=true&width=600&lines=🤖+Advancing+in+Machine+Learning+%26+AI;📊+Mastering+Data+Science+Techniques;🌐+Building+Scalable+Web+Applications;💡+Exploring+Cutting-Edge+Technologies" />
</div>

<div align="center">
<table>
<tr>
<td width="33%" align="center">

### 🤖 AI & Machine Learning
- Deep Learning with PyTorch
- Machine Learning with Scikit-learn
- Data Preprocessing & Feature Engineering
- Model Evaluation & Optimization
- Neural Networks & Algorithms
- Data Encoding & Transformation

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212257460-738ff738-247f-4445-a718-cdd0ca76e2db.gif" width="100" />
</div>

</td>
<td width="33%" align="center">

### 📊 Data Science
- Data Analysis with Pandas & NumPy
- Data Visualization with Matplotlib
- Interactive Development with Jupyter Notebooks
- Statistical Analysis & Modeling
- Exploratory Data Analysis
- Scientific Computing

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212257465-7ce8d493-cac5-494e-982a-5a9deb852c4b.gif" width="100" />
</div>

</td>
<td width="33%" align="center">

### 🌐 Web Development
- Full-Stack Web Development
- WordPress Development & Customization
- HTML5, CSS3 & Responsive Design
- Flask & Django Framework
- Database Design & Management
- API Development & Integration

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212257454-16e3712e-945a-4ca2-b238-408ad0bf87e6.gif" width="100" />
</div>

</td>
</tr>
</table>
</div>

---

## 🤝 Connect & Collaborate

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=22&duration=3000&pause=1000&color=00AAFF&center=true&vCenter=true&width=600&lines=⚡+Ready+to+collaborate+%26+innovate!;🌟+Let's+build+something+electrifying!;📩+Always+open+to+opportunities!" />
</div>

### 📬 Get In Touch

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-00AAFF?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/evanwilliam03/)
[![Email](https://img.shields.io/badge/Email-Contact-0088CC?style=for-the-badge&logo=gmail&logoColor=white)](mailto:evanwilliam303@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-0066AA?style=for-the-badge&logo=github&logoColor=white)](https://github.com/evan-william)

</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="300" />
</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:1a1a2e,25:16213e,50:0f3460,75:533483,100:e94560&height=150&section=footer&text=EXCELLENCE%20THROUGH%20INNOVATION&fontSize=28&fontColor=00FFFF&animation=fadeIn&fontAlignY=50&desc=Crafting%20Tomorrow's%20Technology%20Today%20•%20Precision%20•%20Performance%20•%20Progress&descAlignY=70&descSize=16" />
</div>

<div align="center">

### 👀 Profile Stats

![Profile Views](https://komarev.com/ghpvc/?username=evan-william&color=00aaff&style=for-the-badge&label=Profile+Views)
![GitHub followers](https://img.shields.io/github/followers/evan-william?style=for-the-badge&color=00ccff)

### ⚡ Thank You for Visiting!

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=18&duration=2500&pause=1000&color=00CCFF&center=true&vCenter=true&width=500&lines=⭐+Star+repos+if+electrifying!;🤝+Let's+collaborate+on+projects!;⚡+Innovation+through+code!" />

**Ready to charge up and turn ideas into reality! 💡⚡**

</div>
