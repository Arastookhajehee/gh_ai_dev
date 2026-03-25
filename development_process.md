# Development Steps

## Purpose

1. Optimize time and reduce time loss for setups
2. To keep your AI context and instructions consistent
3. Use LSP enabled AI code generation to prevent coding hallucinations

### Instructions

1. Tool and App Installations
2. Project Setup
3. AI Vibe coding

View the [Tutorial Video]() for a simple demo

## Required tools

1. [Windows terminal](https://apps.microsoft.com/detail/9N0DX20HK701?hl=en-us&gl=JP&ocid=pdpshare)
2. Terminal based AI agent app
  a. [claude code](https://code.claude.com/docs/en/overview)
  b. [codex](https://openai.com/codex/)
  c. [opencode](https://opencode.ai/)
  d. etc...
3. [HotLoader](https://www.food4rhino.com/en/app/hotloader?lang=en) on Grasshopper
4. [Visual Studio](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&channel=Stable&version=VS18&source=VSLandingPage&cid=2500&passive=false)

### Optional but Highly recommended

1. [Visual Studio Code](https://code.visualstudio.com/download)
2. [C# Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) for vs code
3. [C# Dev Kit Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) for vs code
4. [C# Intellicode Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscodeintellicode-csharp) for vs code
5. [.Net Install Tool Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.vscode-dotnet-runtime) for vs code
6. [git](https://git-scm.com/install/) for version control

## Steps

### Project Folder Setup (one-time per new hotloader component)

1. Make a hotloader component in GH
  a. This will automatically launch Visual Studio, just leave the window open
2. Open the hotloader project directory in visual studio
  a. From the solution explorer, right click on the `.cs` file and open the file location file explorer
3. Close Visual Studio
4. Save the Grasshopper file in your desired folder
5. Close Rhino
6. Copy the content of the folder opened in file explorer to your **desired** location
7. Open Rhino + Grasshopper and open the saved file from `step 4`
8. Right-click on the hotloader component and click `Link to existing project` (Visual studio automatic launch)
9. Build the project in visual studio
10. [optional] Open the project in visual studio code to use the numerous useful extensions
11. [optional] Delete the original temporary files that we copied to our working folder

### AI Vibe Coding

* Open the built-in terminal if using vscode by pressing ```Ctrl + ` ``` and skip to `step 3`

1. Navigate to your project folder in windows explorer
2. Open the folder in windows terminal (right click -> open in terminal)
3. run your favorite ai agent cli tool
  a. opencode (Open source)
  b. claude code terminal cli (by Anthropic)
  c. codex (by OpenAi)
4. have fun with vibe coding
5. build the project with visual studio and see the component update in real-time
6. [optional but highly recommended] commit changes to your git version control history
