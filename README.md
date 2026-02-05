# Hi 👋, I'm Bhumika Rajput


username = "BhumikaRAjput101"
name = "Bhumika Rajput"
role = " Machine Learning Learner | Python Enthusiast | Data Science Fundamentals "
location = "India"

skills = [
"Python", "NumPy", "Pandas", "Seaborn",
"Matplotlib", "Git", "GitHub"
]

with open("README.md", "w", encoding="utf-8") as f:
f.write(f"# Hi 👋, I'm {name}\n\n")
f.write(f"### {role}\n\n")
f.write(f"📍 Location: **{location}**\n\n")

    f.write("## 🚀 Skills\n")
    for skill in skills:
        f.write(f"- {skill}\n")

    f.write("\n## 📊 GitHub Stats\n")
    f.write(f"![GitHub stats](https://github-readme-stats.vercel.app/api?username={username}&show_icons=true&theme=tokyonight)\n\n")

    f.write("## 🔥 Streak Stats\n")
    f.write(f"![GitHub Streak](https://streak-stats.demolab.com?user={username}&theme=tokyonight)\n\n")

    f.write("## 📫 Connect with me\n")
    f.write("- Email: rajputbhumi101@gmail.com\n")

print("README.md created successfully!")
