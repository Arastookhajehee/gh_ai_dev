# Development Steps

## Purpose

1. Optimize time and reduce time loss for setup.
2. Keep your AI context and instructions consistent.
3. Use LSP-enabled AI code generation to reduce hallucinations.
4. Ability to change AI models and keep one's instruction sets and context management

### Instructions

1. Tool and app installations
2. Project setup
3. AI vibe coding

View the [Tutorial Video](https://youtu.be/-8GHEpBGfyM) for a simple demo.

## Required Tools

1. [Windows Terminal](https://apps.microsoft.com/detail/9N0DX20HK701?hl=en-us&gl=JP&ocid=pdpshare)
2. Terminal-based AI agent app:
   - [OpenCode](https://opencode.ai/) [recommended]
   - [Codex](https://openai.com/codex/)
   - [Claude Code](https://code.claude.com/docs/en/overview)
   - etc.
3. [HotLoader](https://www.food4rhino.com/en/app/hotloader?lang=en) on Grasshopper
4. [Visual Studio](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&channel=Stable&version=VS18&source=VSLandingPage&cid=2500&passive=false)

### Optional but Highly Recommended

1. [Visual Studio Code](https://code.visualstudio.com/download)
2. [C# Extension](https://marketplace.visualstudio.microsoft.com/items?itemName=ms-dotnettools.csharp) for VS Code
3. [C# Dev Kit Extension](https://marketplace.visualstudio.microsoft.com/items?itemName=ms-dotnettools.csdevkit) for VS Code
4. [C# IntelliCode Extension](https://marketplace.visualstudio.microsoft.com/items?itemName=ms-dotnettools.vscodeintellicode-csharp) for VS Code
5. [.NET Install Tool Extension](https://marketplace.visualstudio.microsoft.com/items?itemName=ms-dotnettools.vscode-dotnet-runtime) for VS Code
6. [Git](https://git-scm.com/install/) for version control

## Steps

### Project Folder Setup (One-Time per New HotLoader Component)

1. Make a HotLoader component in GH.
   - This automatically launches Visual Studio. Leave that window open.
2. Open the HotLoader project directory in Visual Studio.
   - In Solution Explorer, right-click the `.cs` file and open the file location in File Explorer.
3. Close Visual Studio.
4. Save the Grasshopper file in your desired folder.
5. Close Rhino.
6. Copy the contents of the folder opened in File Explorer to your **desired** location.
7. Open Rhino + Grasshopper and open the saved file from `step 4`.
8. Right-click the HotLoader component and click `Link to existing project` (this launches Visual Studio automatically).
9. Build the project in Visual Studio.
10. [Optional] Open the project in VS Code to use useful extensions.
11. [Optional] Delete the original temporary files copied to your working folder.

### AI Vibe Coding

- If using VS Code, open the built-in terminal with `Ctrl + \`` and skip to `step 3`.

1. Navigate to your project folder in Windows Explorer.
2. Open the folder in Windows Terminal (right-click -> Open in Terminal).
3. Run your favorite AI agent CLI tool:
   - OpenCode (open source)
   - Claude Code terminal CLI (Anthropic)
   - Codex (OpenAI)
4. Have fun with vibe coding.
5. Build the project in Visual Studio and watch the component update in real time.
6. [Optional but highly recommended] Commit changes to your Git history.
