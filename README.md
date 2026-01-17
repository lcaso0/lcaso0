<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=VT323&size=30&pause=1000&color=FFFFFF&center=true&vCenter=true&width=435&lines=Hi%2C+I'm+a+SWE+Student;I+build+cool+things+with+code" alt="Typing SVG" />

</div>

### 🐹 main.go

```go
type Developer struct {
    Role, Focus, Challenge string
    Learning               []string
    TechStack              map[string][]string
}

type Project struct {
    Name, Stack, Status string
}

var lcaso0 = Developer{
    Role:      "Software Engineering Student @ KFUPM 🇸🇦",
    Focus:     "Advanced Data Structures & Algorithms 🧠",
    Learning:  []string{"Go 🐹", "Rust 🦀"},
    Languages: []string{"TypeScript", "JavaScript", "Python", "Java"},

    Quest_Log: []Project{
        {
            Name:   "English Vocab App",
            Stack:  "Nextjs, Clerk, TypeScript, Authjs, Tailwind, Prisma",
            Status: "✅ Completed (Legacy)",
        },
        {
            Name:   "Students' Document and Resources Manager",
            Stack:  "Nextjs, TypeScript, Tailwind, Shadcn, Drizzle, Supabase",
            Status: "🚧 In Progress (Building)",        
        },
    },
    
    Challenge: "I genuinely love coding and problem-solving",
}
