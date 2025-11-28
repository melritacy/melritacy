
<h1 align="center">Hi, I'm Melrita Cyriac 👋</h1>
<p align="center">Third-Culture Kid | Computer Science @ UAlberta | Developer | Data & AI Enthusiast | Women in STEM Advocate</p>

---

### 👩🏽‍💻 About Me

- 🎓 I'm an incoming fourth year Computer Science student at the University of Alberta (graduating Dec 2026)
- 🌍 Grew up in Dubai 🇦🇪 | Indian 🇮🇳 | Currently in Edmonton 🇨🇦
- 🧠 Interested in AI, data science, full-stack web development, and ethical tech
- 🤝 Passionate about empowering underrepresented voices in STEM (former WISEST mentor!) and current Ada's Team VP Communications !


---

### 🛠️ Technologies & Tools

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=java&logoColor=white)
![C](https://img.shields.io/badge/-C-00599C?style=flat&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat&logo=django&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/-PowerBI-F2C811?style=flat&logo=powerbi&logoColor=black)

---

### 🌱 Currently Learning

- Neural networks and optimization
- Open-source contribution best practices
- Software design & architecture
- More about myself through the lens of inclusive tech 🌈

---

### 🧠 Notable Projects

- **Turbo Alpaca**: Startup evaluation platform built with Django + PostgreSQL  
- **TheSixApp**: Attendance tracker built with React + Firebase  
- **SocialDistribution**: Decentralized social network using Django + REST APIs

---

### 📫 Let's Connect!

- 💼 [LinkedIn](https://www.linkedin.com/in/melrita-cyriac/)
- 📧 Email: melritac@ualberta.ca



---
| Function | Mine | Claude | ChatGPT |
|----------|------|--------|---------|
| Perplexity | I have a main perplexity function,which accordingly calaulates based on model given | Each model does it's own respective calulation | while Chatgpt does use one main Perplexity function, it uses other helper porbability functions as well |
| OOV handling/build vocab/replace_singeltons | I handle OOV  in training , using mapping_tokens_to_vocab function -> adds unk when token only appears oonce, It'd done before ngram counting. Also use build vocan and replace singletons | It doesn't really handle oov and only has a fallback probability | Very similar logic to mine, where it replaces tokens that only appear once with unk before counting and chatgpt has similar logic when it comes to building vocbaulary and otherwise |
| BOS/EOS padding | In my assignment, Unigrams have one <s>, bigram added  one on each side, and trigram prepend two <s> and one at the end | Adds single s for all, doesn't actually do it corrcelty | does it like claude, doesn’t actually do it correctly |
| Json Serializer/Deserializer | I use serialization and deserialization -> string into json and convert it back into tuple after | uses plain  dictionaries, and json.dump directly | logic is similar to mine, converts into string and then converts it back |

