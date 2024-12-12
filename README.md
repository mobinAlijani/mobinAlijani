## Hi there

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class JuniorDev:
    def __init__(self):
        # Personal Information
        self.first_name = "Mobin"
        self.last_name = "Alijani"
        self.full_name = f"{self.first_name} {self.last_name}"
        self.title = "Junior Developer"
        self.about_me = (
            "I'm passionate about coding and creating innovative solutions. "
            "I enjoy working on IoT projects and exploring the capabilities of microcontrollers like ESP32."
        )
        self.skills = ["Python", "Git", "CPP", "ESP32-programming"]

        # Social Media Links
        self.social_media = {
            "LinkedIn": "https://www.linkedin.com/in/mobin-alijani/",
            "Twitter": "https://twitter.com/mobin-alijani",
        }

    def introduce(self):
        """Print a friendly introduction."""
        print(f"👋 Hi, I'm {self.full_name} - a passionate {self.title}!")
        print(f"📝 About Me: {self.about_me}")
        print(f"💻 Skills: {', '.join(self.skills)}")
        print("🌍 Find me online:")
        for platform, url in self.social_media.items():
            print(f"   - {platform}: {url}")
        print("✨ Thanks for stopping by! Let's connect. 🚀")

    if __name__ == "__main__":
        me = JuniorDev()
        me.introduce()
```
