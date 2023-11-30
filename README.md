```cs
namespace AboutMe
{
    public static class AboutMe
    {
        public static readonly string Name = "Jonntteiu";
        public static readonly byte Age = 18;
        public static readonly IList<string> Abilities = new List<string>()
        {
            "C#",
            "Typescript",
            "Oracle",
            "Git",
            "HTML5",
            "CSS3",
            "React",
        };
        public static readonly IList<string> Learning = new List<string>()
        {
            "DevOps",
            "System Analysis"
        };
        public static readonly IDictionary<string, string> Languages = new Dictionary<string, string>()
        {
            { "Portuguese", "Native" },
            { "English", "Advanced" },
            { "Japanese", "Beginner" }
        };
    }
}
```
