<!--
<h1 align="center">Hi 👋, I'm Anas Yakubu</h1>

A software engineer who enjoys seamlessly bridging the gap between people and digital space by day, and a anime lover. My passion for software engineering emerged as the world turned digital and I know find myself creating solutions to the everyday problems that frame our human experience.
-->
 <h6 style="font-size: 15px">👋 Hi, I'm Anas Yakubu</h6>
 
```typescript
import anas from 'github';

const anasProfile = {
    name: "Anas Yakubu",
    role: "Software Engineer 👨‍💻",
    comany: "NYM Technologies Limited",
    skills: [
         "JavaScript", "TypeScript", "PHP", "Nodejs", "React", "Next.js", "Python",
        "Tailwind CSS", "scss", "React Native", "RESTful APIs", "Responsive Design",
        "Cross-Platform Development"
    ],
    currentProject: "Invoice Generator Application",
    interests: ["Anime", "Building Web Applications", "Problem Solving"]
};

console.log(`Hello, I'm ${anasProfile.name}! I work as a ${anasProfile.role} in ${anasProfile.company}.`);

anas.on('project', (project) => {
    console.log(`Currently working on: ${project}`);
});

anas.emit('project', anasProfile.currentProject);
```

Portfolio : [https://anas.dev](https://anasyakubu.vercel.app)
