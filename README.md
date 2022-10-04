# Github Guides
* [Cheat Sheet (pdf)](https://education.github.com/git-cheat-sheet-education.pdf)
* [Cheat Sheet 2](https://training.github.com/downloads/github-git-cheat-sheet/)
* [first steps](https://www.softwaretestinghelp.com/github-tutorial/)
* [Samml guide (medium)](https://medium.com/nerd-for-tech/github-pages-a-comprehensive-guide-w-images-part-1-321b55088466)
* [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Quick GitHub Diagram
![image](https://user-images.githubusercontent.com/16194561/193708500-c0de72b4-0782-435c-b248-f73b873138a1.png)

# Godot Tutorials
* [Godot tutorials](https://godottutorials.com/courses)
* [Godot Docs](https://docs.godotengine.org/en/stable/community/tutorials.html)
* [First Game](https://docs.godotengine.org/en/3.1/getting_started/step_by_step/your_first_game.html)
* [C# in Godot](https://godotengine.org/article/introducing-csharp-godot)
* [Godot C# in VS](https://github.com/godotengine/godot-csharp-visualstudio)
* [C# basics (Godot Docs)](https://docs.godotengine.org/en/3.4/tutorials/scripting/c_sharp/c_sharp_basics.html)

# SimpleGodotGame
Create a simple game to explore Godot Engine with 2d gamnes. The objective of this project is to create a astroid game with godot, exploring the core features offered.
We will start with the pong example and convert it to astroids.
# Pong with C#

A simple Pong game. This demo shows best practices
for game development in Godot, including
[signals](https://docs.godotengine.org/en/latest/getting_started/step_by_step/signals.html).

Language: [C#](https://docs.godotengine.org/en/latest/tutorials/scripting/c_sharp/index.html)

Renderer: GLES 2

Note: There is a GDScript version available [here](https://github.com/godotengine/godot-demo-projects/tree/master/2d/pong).

Note: There is a VisualScript version available [here](https://github.com/godotengine/godot-demo-projects/tree/master/visual_script/pong).

Note: There is a GDNative C++ version available [here](https://github.com/godotengine/gdnative-demos/tree/master/cpp/pong).

Check out this demo on the asset library: https://godotengine.org/asset-library/asset/535

## How does it work?

The walls, paddle, and ball are all
[`Area2D`](https://docs.godotengine.org/en/latest/classes/class_area2d.html)
nodes. When the ball touches the walls or the paddles,
they emit signals and modify the ball.

## Screenshots

![Screenshot](screenshots/pong.png)






## Github step by step guide written out.

Download Git Repo
```cmd
git clone https://github.com/theisen1337/SimpleGodotGame.git
```
Change directory into project.
```cmd
cd SimpleGodotGame
```
Create a new feature branch
```cmd
git checkout -b "MyBranchName"
```

**_"Make Changes to your code using VSCode, notepad++, Visual Studio, text IDE"_**

Check status of code.
```cmd
git status
```
Add changes to a commit
```cmd
git add "directories/files"
```
Commit changes with a message
```cmd
git commit -m "I made a change etc."
```
Push branch to server.
```cmd 
git push --set-upstream origin "MyBranchName"
```
Image of github Repo when you push branch to server.
<kbd>![image](https://user-images.githubusercontent.com/16194561/193712769-b9721264-f518-48aa-bd73-e32294a86a5f.png)<kbd>
