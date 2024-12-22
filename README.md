# Hello World! 👋

[![From Hello World I've written ~50k Lines Of Code](https://img.shields.io/badge/From%20Hello%20World%20I've%20Written%20-~50k%20Lines%20Of%20Code-blue)](/)
[![My Favourite Language Is C](https://img.shields.io/badge/My%20Favourite%20Language%20Is-C-lightgray?logo=c)](/)
```c
#include <stdio.h>

struct Programmer {
    char *name;
    char *langs[];
    char *tools[];
};

struct Programmer Elis = {
    .name  = "Elis Staaf",
    .langs = {
        "C", "C++", "ASM",
        "Python", "Common Lisp",
        "Rust", "Go", "Make"
    },
    .tools = {
        "Linux", "GCC", "G++",
        "Neovim", "SBCL", "NASM",
        "GNU Make", "Pacman",
    }
};

int main(int argc, char **argv) {
    printf("Name:  %s\n", Elis.name);

    printf("Langs: ");
    int i = 0;
    while (++i <= (sizeof(Elis.langs) / sizeof(*Elis.langs)) {
        printf("%s, ", Elis.langs[i]);
    }
    printf("\n");

    printf("Tools: ");
    int i = 0;
    while (++i <= (sizeof(Elis.tools) / sizeof(*Elis.tools)) {
        printf("%s, ", Elis.tools[i]);
    }
    printf("\n");

    return 0;
}
```

<a href="">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=ElisStaaf&theme=nord&border_radius=0&show_icons=true&layout=compact&bg_color=12151f&title_color=ffffff&icon_color=3780e8&text_color=ffffff&border_color=33366200" />
</a>
<a href="">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=ElisStaaf&theme=nord&layout=compact&border_radius=0&bg_color=12151f&title_color=ffffff&icon_color=3780e8&text_color=ffffff&border_color=33366200" />
</a>
<br><p></p><br>
<a href="">
  <img align="center" src="https://github-profile-trophy.vercel.app/?username=ElisStaaf&theme=onedark&no-frame=true&margin-w=10&column=10" />
</a>
