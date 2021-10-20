![visitors](https://visitor-badge.glitch.me/badge?page_id=jerald-devOfficial)
[![Linkedin Badge](https://img.shields.io/badge/-Jerald%20Baroro-blue?style=social&logo=Linkedin&logoColor=blue&link=https://www.linkedin.com/in/jerald-baroro-562aab20a/)](https://www.linkedin.com/in/jerald-baroro-562aab20a/)
[![Twitter Badge](http://img.shields.io/badge/-@spaueOfficial-1ca0f1?style=social&logo=twitter&logoColor=blue&link=https://twitter.com/VedantKhairnar3)](https://twitter.com/@spaueOfficial) 
[![GitHub followers](https://img.shields.io/github/followers/jerald-devOfficial?label=Follow&style=social)](https://github.comjerald-devOfficial/?tab=follow)
![Made with love in Philippines](https://madewithlove.now.sh/ph?heart=true&colorA=%23de172b&colorB=%23124bce)

<p align="center">
  <img src="jerald_io.png" alt="JERALD.IO Logo"/>
</p>
<h2 align="center">Hi, 👋  &nbsp; I am Jerald Baroro</h2>

<br>

```jsx
import React, {useState, useEffect} from 'react';

const skills = {

  techStack : "MERN FullStack Developer",
  
  languages :["JavaScript", "C", "C++"],

  IDE       :["VS Code", "Brackets", "Sublime", "PHPStorm", "Atom"],

  jsStacks  :["ReactJs", "NodeJs", "ExpressJs", "EJS", "PugJs"],
  
  cssFw     :["MaterialUI", "Bootstrap", "TailwindCSS", "Materializecss", "SASS/SCSS"],

  databases :["Firebase", "MongoDB", "MySQL", "FILE I/0"],

  platforms :["Firebase", "Heroku", "Github Pages", "Vercel"],
}

const dev = 'jerald-devOfficial';

export default function Welcome() {
  const [loading, setLoading] = useState(false);
  const [status, setStatus] = useState('');
  const [devIsCoding, setDevIsCoding] = useState(false);

  useEffect(() => {
    setLoading(true);
    setDevIsCoding(true);
    
    if(devIsCoding) {
      setStatus('Dev is Awesome!');
    } else setStatus('Dev is playing something.');
  }, [devIsCoding, status]);

  return (
    <>
      {loading &&
        (<div>
      
          <h1>Hi, I'm {dev}, a {skills.techStack}!</h1>
        
          <h3>
            I code with these languages 
            {skills.languages.map((language, index) => (
              <ul key={index}>
                <li>{language}</li>
              </ul>
            ))}
          </h3>
      
          <h3>
            My current JavaScript stacks are 
            {skills.jsStacks.map((stack, index) => (
              <ul key={index}>
                <li>{stack}</li>
              </ul>
            ))}
          </h3>
          
          <h3>
            The CSS Frameworks I used/use are 
            {skills.cssFw.map((css, index) => (
              <ul key={index}>
                <li>{css}</li>
              </ul>
            ))}
          </h3>
          
          <h3>
            I have tried using IDEs like 
            {skills.IDE.map((ide, index) => (
              <ul key={index}>
                <li>{ide}</li>
              </ul>
            ))}
          </h3>
          
          <h3>
            The databases I used/use are 
            {skills.databases.map((db, index) => (
              <ul key={index}>
                <li>{db}</li>
              </ul>
            ))}
          </h3>
          
          <h3>
            And I have hosted to these platforms:  
            {skills.platforms.map((platform, index) => (
              <ul key={index}>
                <li>{platform}</li>
              </ul>
            ))}
          </h3>
      
          <h3>So if you see me coding, cheer me up with &quot;{status}&quot;!</h3>
        </div>)
      }
    </>
  )
}
```

<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=jerald-devOfficial&show_icons=true&theme=gotham" alt="jerald-devOfficial" />

<p align="center">
  <img src="https://media.giphy.com/media/Y06e2KFCG48qwNMGK2/giphy.gif" alt="high in coding"/>
</p>


<!---
jerald-devOfficial/jerald-devOfficial is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->





