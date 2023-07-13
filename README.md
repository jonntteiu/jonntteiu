```cs
namespace AboutMe
{
    public class Me
    {
        public string Name { get; } = "Jonntteiu";
        public byte Age { get; } = 18;
        public List<string> Abilities { get; } = new List<string>()
        {
            "C#",
            "Typescript",
            "Oracle",
            "Git",
            "HTML5",
            "CSS3"
        };
        public List<string> Learning { get; } = new List<string>()
        {
            "DevOps",
            "React",
            "System Analysis"
        };
        public Dictionary<string, string> Languages { get; } = new Dictionary<string, string>()
        {
            { "Portuguese", "Native" },
            { "English", "Advanced" },
            { "Japanese", "Beginner" }
        };
    }
}
```
