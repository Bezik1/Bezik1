# :wave: Hi, I'm Mateusz and also
## :man_technologist: Frontend developer

**Technologies**
* JavaScript
* TypeScript
* React
* gsap
* react-three/fiber (react + THREE.js)

## :computer: Backend developer
**Technologies**
* Nest.js
* MongoDB
* MySQL
* REST API

## :atom_symbol: WEB3 developer
**Technologies**
* ethers.js
* @usedapp



```typescript
  interface Developer {
    devName: string
    experience: number
  }
  
  interface NewDeveloper extends Developer {
    githubUrl: string
    salary: number
  }
  
  const devs: Developer[] = []
  const hireNewDev = ({ devName, experience } : NewDeveloper) =>{
    devs.push({
      devName,
      experience,
      status,
      salary: 3000,
      githubUrl: 'https://github.com/Bezik1'
    })
  }
  
  hireNewDev({ 'Mateusz', 0 })
```
