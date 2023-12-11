# :wave: Hi, I'm Mateusz and also
## :man_technologist: Frontend developer

**Technologies**
* JavaScript
* TypeScript
* React
* gsap
* react-three/fiber (react + THREE.js)

## :computer: Machine Learning
**Technologies**
* numpy
* python

**Alghoritms**
* gradient descent
* backpropagation

**Skills**
* Implementing network structure
* OOP

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

## :electron: Electron developer

## :sunglasses: React Native Developer


```typescript
  interface NewDeveloper {
    devName: string
    experience: number
    active: boolean
  }
  
  interface Developer extends NewDeveloper {
    githubUrl: string
    salary: number
  }
  
  const devs: Developer[] = []
  const hireNewDev = ({ devName, experience, active } : NewDeveloper) =>{
    devs.push({
      devName,
      experience,
      status,
      active,
      salary: 3000,
      githubUrl: 'https://github.com/Bezik1'
    })
  }
  
  hireNewDev({
    devName: 'Mateusz',
    expierience: 0,
    active: true
})
```
