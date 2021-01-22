# Me

```
// me.swift
class me {
    struct Schemes {
        let name:String
        let age:Int
    }
    struct adn {
        let dream:String
        let objective:String
        let motivation:String
    }
}
let object = me()
let normal = me.Schemes(name: "ItsTheGuy", age: 0)
let myself = me.adn(dream: "Since I was a child, I wanted to be an Apple Engineer", objective: "My objective Is Apple ⭐️", motivation: "((∞)^∞)^∞ and that elevated infinite times")
print("My name is", normal.name + ",", (normal.age == 0) ? "apparently, I'm" : "I'm", normal.age, (normal.age == 0) ? "😂" : "")
print(myself.dream + ".", myself.objective + ".", "My motivation is", myself.motivation)

```

## Projects
```
// projects.swift
class projects {
    let defaultLove = "((∞)^∞)^∞"
    struct info {
        let name:String
        let description:String
        let love:String
    }
}
let project_class = projects()
var list = [projects.info(name: "Mars", description: "Save and Load variables magically 🪄", love: project_class.defaultLove)]
for item in list {
    print("Project name:", item.name, "|", "Description:", item.description, "|", "Love:", item.love)
}
```
