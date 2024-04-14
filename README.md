### 8860-nguyenhailong
def generate_readme(username, name, profession, interests, learning, contact_info, pronouns):
    template = f"""
# Hello, I'm {name}! 👋

I'm a {profession}, passionate about {interests}. Welcome to my GitHub profile!

## About Me

- 🌱 I’m currently learning {learning}.
- 💬 Ask me about {interests}.
- 📫 How to reach me: {contact_info}.
- 😄 Pronouns: {pronouns}.

## Languages and Tools

- [List of programming languages, frameworks, tools, etc., that you're proficient in]

## GitHub Stats

![Your GitHub stats](https://github-readme-stats.vercel.app/api?username={username}&show_icons=true&theme=radical)

## Let's Connect

- [LinkedIn](https://www.linkedin.com/in/{username}/)
- [Twitter](https://twitter.com/{username})

Feel free to reach out and connect with me! 😊
"""
    return template

# Replace the placeholder values with your own information
username = "yourusername"
name = "Your Name"
profession = "Your Profession or Role"
interests = "Your Interests or Specializations"
learning = "What you're learning"
contact_info = "Your Contact Information"
pronouns = "Your Pronouns"

# Generate README content
readme_content = generate_readme(username, name, profession, interests, learning, contact_info, pronouns)

# Write README content to file
with open("README.md", "w") as f:
    f.write(readme_content)

print("README.md generated successfully!")


<!--
**NguyenHaiLong2002/NguyenHaiLong2002** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
