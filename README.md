### Hi, I'm Andreas

Certified Scrum Trainer since 2008 and co-founder of DasScrumTeam, an agile training company in Switzerland. Before I started training, I spent thirteen years as a software developer and team lead. Since 2023 I have been working with AI every day, in course design, research, operations and software development, mostly with Claude Code.

**What I build**

- **[miro-board-builder](https://github.com/andreasschliep/miro-board-builder).** A talk or workshop is described as data (YAML), and one command builds the complete Miro board through the REST API. It logs every frame it creates and can plan a build offline first. I used it to build my board live on stage at Agile Prague 2026.
- **[learning-objective-lint](https://github.com/andreasschliep/learning-objective-lint).** Checks learning objectives against Bloom's taxonomy and shows whether a workshop agenda actually practises them at the intended level.
- **[facilitation-planner](https://github.com/andreasschliep/facilitation-planner).** Plans a session backwards from what every participant must have done by a given minute, and checks the timing before anyone writes a facilitator guide.
- **[wardley-map-builder](https://github.com/andreasschliep/wardley-map-builder).** One YAML file per Wardley map, rendered as a PNG or drawn onto a Miro board.
- **Agent tooling.** Custom Claude Code skills, commands and prompts. In November 2026 I turned two of my tools into MCP servers:
  - **[miro-board-mcp](https://github.com/andreasschliep/miro-board-mcp)** lets an agent turn a Markdown document with Mermaid diagrams into a Miro board: it validates the document, previews the build and then creates the board. The agent writes no coordinates; the server places every frame and element. Every build is a dry run until the agent confirms the exact document it previewed, and the server only touches boards it created itself or that are on an allowlist.
  - **[course-standards-mcp](https://github.com/andreasschliep/course-standards-mcp)** checks course material against learning objectives at a Bloom level and against a German/English Scrum term base. It reports what it can establish for certain and leaves the judgment "met or not" to the model and to me.
- **server-compromise-check** (not public yet). A daily, read-only compromise check for a handful of Debian and Ubuntu web servers. A Mac runs it every morning over an SSH key that can start the check and nothing else, and shows a summary and a notification.
- **Learning platforms.** When classes went remote in 2020, I maintained and extended our own learning and admin systems in Swift, TypeScript/Node.js and PHP.

The four tools, the two MCP servers and the server check were built with Claude Code as co-developer.

**How I work with AI: using vs. commissioning**

Using AI means: I ask, it answers, I copy. Commissioning means: I brief, it works, I check, I decide. Three rules apply:

1. It never sees what my client wouldn't show me.
2. It tells me what it did.
3. Nothing leaves without my hand on it.

**Talk:** [The AI Toolbox for Trainers, Facilitators and Coaches](https://miro.com/app/board/uXjVHlECvq8=/), Agile Prague 2026

**Note:** Most of my work lives in private and company repositories. The public examples here are cleaned-up extracts.

[LinkedIn](https://www.linkedin.com/in/andreasschliep)
