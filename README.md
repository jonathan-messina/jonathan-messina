






<h1 align="center"><a align="center">
  <img align="center" src="https://readme-typing-svg.herokuapp.com?color=F9FFFF&center=true&height=100&lines=Hello+there!+%F0%9F%98%84+I'm+John!" />
</a></h1>

<h3 align="center" >A passionate Software Developer from Argentina</h3><a href="https://linkedin.com/in/jonathan-messina" target="blank">
<p align="center" >  
  <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="jonathan-messina" height="30" width="40" /></a>
</p>
<br/>



```typescript

interface DeveloperI {
  name: string;
  role: string;
  email: string;
  openToWork: boolean; 
  languageSpoken: string[];
  introduction(): () => void;
  sayHello: () => void;
  isOpenToWork: () => void
  getLinkedinProfile: () => string;
  getResume: () => string;
}

const SoftwareDeveloper: DeveloperI = {
    name: "John",
    role: "Software Developer",
    email: "a.jonathan.messina@gmail.com",
    openToWork: true,
    languageSpoken: ["es-ES", "en_US"],
    introduction() {
        console.log(`Hi!, I'm ${this.name}, I'm a ${this.role}.`);
    },
    sayHello() {
        console.log("Thanks for reaching out, let's build great products together!.");
    },
    isOpenToWork() {
            console.log(`Open to Work: ${this.openToWork}.`);
    },
    getLinkedinProfile() {
        return "https://www.linkedin.com/in/jonathan-messina";
    },
    getResume() {
        return "https://github.com/jonathan-messina/resume";
    }
}
SoftwareDeveloper.introduction();
SoftwareDeveloper.sayHello();
SoftwareDeveloper.isOpenToWork();
const linkedinProfile = SoftwareDeveloper.getLinkedinProfile();
const resume = SoftwareDeveloper.getResume();
console.log(linkedinProfile);
console.log(resume);
```
```bash
Hi!, I'm John, I'm a Software Developer.
Thanks for reaching out, let's build great products together!.
Open to Work: true.
https://www.linkedin.com/in/jonathan-messina
https://github.com/jonathan-messina/resume
```

<!-- HTML -->
<p align="center">
<img src="https://readme-jokes.vercel.app/api" alt="Jokes Card" />
</p>



