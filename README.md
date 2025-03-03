

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Montserrat&size=25&duration=3650&pause=3000&color=F7F7F7&random=false&width=435&lines=%C3%96mer%2C+a+everything+developer)](https://twiz.lol)

```cpp
#include <iostream>
#include <string>
#include <vector>
#include <map>

class AboutMe {
public:
    std::string name;
    std::vector<std::string> aliases;
    std::string discord;
    std::map<std::string, std::string> projects;

    AboutMe() {
        name = "Ömer";
        aliases = {"Sentiax", "isw_", "Astro","Rcynx"};
        discord = "hbyq";
        projects = {
            {"Twiz.lol", "A bio-link site for sharing social links."},
            {"SGuard", "A upcoming tool that protects sites from bots, DDoS, and hackers."}
        };
    }
};

int main() {
    AboutMe aboutMe;
    std::cout << "Name: " << aboutMe.name << std::endl;
    std::cout << "Aliases: ";
    for (const auto& alias : aboutMe.aliases) {
        std::cout << alias << " ";
    }
    std::cout << std::endl;
    std::cout << "Discord: " << aboutMe.discord << std::endl;
    std::cout << "Projects:" << std::endl;
    for (const auto& project : aboutMe.projects) {
        std::cout << "  " << project.first << ": " << project.second << std::endl;
    }

    return 0;
}
```
