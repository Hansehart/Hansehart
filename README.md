# Hi there 👋

```java
@RestController
public class DeveloperService {

    private final String name = "Richi";
    private final String[] languages = {"Java", "Python", "TypeScript"};
    private final String platform = "Cloud";
    private final String codingPartner = "Claude Code";
    private final String since = "2020";

    @GetMapping("/about")
    public String aboutMe() {
        return "Tech enthusiast exploring emerging technologies, building projects and bringing ideas into production";
    }
}
```

```text
$ java -jar DeveloperService.jar

[2020-04-02 10:00:00] INFO: Service initialized
[2025-04-02 10:00:00] INFO: Still coding, still learning 💻
```

<!--
**Hansehart/hansehart** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
