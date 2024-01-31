## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

[![falco card](https://stats.oluwatobi.dev/api/pin/?username=tobi-de&repo=falco&theme=dracula&show_icons=true&hide_border=true)](https://github.com/tobi-de/falco)
[![falco card](https://stats.oluwatobi.dev/api/pin/?username=tobi-de&repo=falco_blueprint_basic&theme=dracula&show_icons=true&hide_border=true)](https://github.com/tobi-de/falco_blueprint_basic)

https://gist.github.com/0xjac/85097472043b697ab57ba1b1c7530274

```sh
git clone --bare git@github.com:Tobi-De/falco_blueprint_basic.git
cd falco_blueprint_basic
git push --mirror git@github.com:falco-blueprints/falco_blueprint_test.git
cd ..
rm -r falco_blueprint_basic
git clone git@github.com:falco-blueprints/falco_blueprint_test.git
git remote add upstream git@github.com:Tobi-De/falco_blueprint_basic.git
git remote set-url --push upstream DISABLE
git fetch upstream
git rebase upstream/main
```
