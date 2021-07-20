<p align="center">
  <img src="jerald_io.png" alt="JERALD.IO Logo"/>
</p>
<h2 align="center">Hi, 👋  &nbsp; I am Jerald Baroro</h2>

<hr>

```jsx
import React, {useState, useEffect} from 'react';

const skills = {

  techStack : "MERN FullStack Developer",
  
  languages :["JavaScript", "C", "C++"],

  IDE       :["VS Code", "Brackets", "Sublime", "PHPStorm"],

  jsStacks  :["ReactJs", "NodeJs", "ExpressJs", "EJS", "PugJs"],
  
  cssFw     :["MaterialUI", "Bootstrap", "TailwindCSS", "Materializecss"],

  databases :["Firebase", "MongoDB", "MySQL", "FILE I/0"],

  platforms :["Firebase", "Heroku", "Github Pages", "Vercel"],
}

const devIsCoding = 'jerald-devOfficial';

function Welcome() {
  const [loading, setLoading] = useState(false);
  const [status, setStatus] = useState('');

  useEffect(() => {
    setLoading(true);
    
    if(devIsCoding) {
      setStatus('Dev is Awesome!');
    } else setStatus('Dev is playing something.');
  }, [status]);

  return (
    <>
      {loading
        <div>
      
          <h1>Hi, I'm {devIsCoding}</h1>
        
          <h3>
            I code with these languages 
            {skills.languages.map((language) => (
              <ul key={index}>
                <li>{language}</li>
              </ul>
            ))}
          </h3>
      
          <h3>
            My current JavaScript stacks are 
            {skills.jsStacks.map((stack) => (
              <ul key={index}>
                <li>{stack}</li>
              </ul>
            ))}
          </h3>
          
          <h3>
            The CSS Frameworks I used/use are 
            {skills.cssFw.map((css) => (
              <ul key={index}>
                <li>{css}</li>
              </ul>
            ))}
          </h3>
          
          <h3>
            I have tried using IDEs like 
            {skills.IDE.map((ide) => (
              <ul key={index}>
                <li>{ide}</li>
              </ul>
            ))}
          </h3>
          
          <h3>
            The databases I used/use are 
            {skills.databases.map((db) => (
              <ul key={index}>
                <li>{db}</li>
              </ul>
            ))}
          </h3>
          
          <h3>
            And I have hosted to these platforms:  
            {skills.platforms.map((platform) => (
              <ul key={index}>
                <li>{platform}</li>
              </ul>
            ))}
          </h3>
      
          <h3>So if you see me coding, cheer me up with &quot;{status}&quot;!</h3>
        </div>
      }
    </>
  )
}
```

<p align="center">
  <img src="https://media.giphy.com/media/Y06e2KFCG48qwNMGK2/giphy.gif" alt="high in coding"/>
</p>


<!---
jerald-devOfficial/jerald-devOfficial is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->





