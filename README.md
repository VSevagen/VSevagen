### Hi there, I'm Sevagen 👋

![visitors](https://page-views.glitch.me/badge?page_id=VSevagen.VSevagen)
[![Twitter Follow](https://img.shields.io/twitter/follow/SevagenV?label=Follow)](https://twitter.com/intent/follow?screen_name=SevagenV)
[![Linkedin: Sevagen](https://img.shields.io/badge/-Sevagen-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/veerasamy-sevagen/)](https://www.linkedin.com/in/veerasamy-sevagen/)



```javascript
import React, { UseState } from "react";

function Sevagen() {
  const [pronous, setPronouns] = useState(["He", "Him", "His"]);
  const [askMeAbout, setAskMeAbout] = useState(["web dev","tech","GNOME","scuba diving","Git"]);
  const [code, setCode] = useState(["Javascript", "C++", "Python"]);
  const [learning, setLearning] = useState(["React", "Django", "GraphQL"]);

  return (
    <div className="About Me">
      I'm a 3rd year computer science student from Amrita Vishwa Vidyapeetham, in the state of Kerala
      and I'm from Mauritius. You can address me as {$`pronouns`} and ask me about {$`askMeAbout`}
      I'm knowledgable in {$`code`} and currently learning {$`learning`}
      
      I love connecting with different people so if you want to say hi, 
      I'll be happy to meet you more!

      Reach me through email: sevagenv@gmail.com or just google me :)
    </div>
  );
}

const error = "Don't try to compile this, you'll get errors :)"

export default Sevagen;
```

<!--
**VSevagen/VSevagen** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
