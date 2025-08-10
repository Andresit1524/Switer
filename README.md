# Switer (a.k.a. SwiterMD)
> *Swift Writing for everyone*

**Switer** (or *SwiterMD* for disambiguation) is a text editor *in development* focused on writing, notes, and PKM (*Personal Knowledge Management*), which aims to stand out for its comfort, power, and simplicity.

## *Planned* main features
- Markdown editor with WYSIWYG editing and preview capabilities
- More capable and dynamic block editing for a smoother experience
- A proprietary Markdown variant designed to be more compatible, elegant, and portable
- Integration with extensions such as LaTeX, Mermaid, embeds, and cross-references
- Maximum performance and speed of use
- Improved design for mobile and desktop devices
- Local-first, no login, just local files on your disk
- Base plugin system and possibility of third-party plugins
- Elegant, clean, and dynamic appearance
- Third-party integrations, synchronization, and better export capabilities

And most importantly: **it does not seek to imitate the mistakes of programs of its kind**. Switer was born from the need for an application that is capable and suitable for everyone, unlike current programs, which are very technical and **incomplete**.

### Philosophy
Switer seeks to comply with the following principles:

1.  **Fast:** in performance thanks to its Svelte + Tauri stack, but also in experience and use.
2.  **Comfortable:** so that writing is a frictionless process, without inconveniences and with the best possible accessibility.
3.  **Elegant:** without discomfort, without half-baked solutions. A space with everything you need with a well-thought-out design.
4.  **Complete:** that each function is in each version. No restricted versions in functions, cuts or limitations.
5.  **Portable:** whether they are portable and multiplatform versions, with export capabilities and access to your notes, Switer is not a form of dependency, but a tool for **your** things.
6.  **Fresh:** without heaviness, bad designs or functionality without aesthetics. Switer seeks to be a beautiful app with what you need.
7.  **Personal:** Switer is yours, and not just because of the MIT license. It seeks the best experience for each user, because **PKM** is **P**ersonal.
8.  **Robust:** with fewer errors, better resilience and optimal solutions.

## Development
Switer is being developed in Svelte-SvelteKit and will be packaged as an app in Tauri when it is ready. To contribute to the code, it is recommended to know these tools and their dependencies.

### Installation

#### Requirements
Before you begin, make sure you have installed:

- [Node.js](https://nodejs.org/) (v18 or higher)
- [pnpm](https://pnpm.io/) (package manager, optional but recommended)
- [Rust](https://www.rust-lang.org/) (required by Tauri)
- A C/C++ compiler:
    - On Windows: [Microsoft Visual Studio Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/)
    - On Linux: `build-essential`
    - On macOS: Xcode Command Line Tools (`xcode-select --install`)

#### Instructions
1.  Clone the repo:

```Bash
git clone https://github.com/Andresit1524/Switer
cd Switer
```

2.  Install dependencies and run:

```Bash
pnpm install
pnpm dev
```

### Project status (*August 10, 2025*)
Switer is currently in the **prototype** phase, so there are no important changes or implementations here in the repository.

> ### About its creator
> I'm Hayran Andrés López, a engineering student who seeks to develop Switer as a way to learn about web and application development, and also to fulfill a goal: **create the closest thing to the definitive PKM**, offering a complete experience and free, quality software.
>
> I love Obsidian, and I want its benefits to be in everyone's hands, not by stealing the software, but by offering one that enhances its strengths, corrects its deficiencies, and offers a unique version of a PKM, the type of software that everyone deserves to enjoy.
>
> You can ask me about the project and contribute to it (with ideas or in the repo) [at this email](mailto:hayranlopez1524@gmail.com)
