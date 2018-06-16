## To do Today:

Make sure that your final project work is turned in.

1. Check the class roster page (links below): click on your name and verify that it takes you to your GitHub Profile.
    - [2nd Block](https://github.com/SKHS-Games-2018/2A2/blob/master/index.md)
    - [4th Block](https://github.com/SKHS-Games-2018/2A4/blob/master/index.md)
    - [7th Block](https://github.com/SKHS-Games-2018/2B7/blob/master/index.md)
    - [8th Block](https://github.com/SKHS-Games-2018/2B8/blob/master/index.md)
    
    **If it does not (you git a cool looking 404 error instead), edit the roster to add a link to your GitHub profile:**
    - **fork** the the roster repository,
    - **edit** your entry to add a link to your GitHub profile,
    - **test** that it works, and finally 
    - create a new **pull request** so that the link can be updated.
  
2. On your GitHub profile make sure the following repositories are visible in the pinned repository list:
      - Your website -- username.github.io (e.g., douglasurner.github.io).
      - Your fork of the [PlaygroundProjectStarter](https://github.com/Game-Design-and-Programming-Template/PlaygroundProjectStarter) repository.
      - Your fork of the [Playtest](https://github.com/SKHS-Games-2018/Playtest) repository that we worked on last class.
      - The repository holding your game (if it is not your PlaygroundProjectStarter fork).
1. Push your final game to GitHub:
      - Start by making sure that the latest work on your game is on GitHub:
        + Navigate to your clone of the PlaygroundProjectStarter code.
        + Launch `Git Bash` and run the following commands:
            ``` bash
            git status
            git add any-new-or-changed-files-or-folders
            git commit -m "Final commit."
            git push
            ```
        + If git status told you that there is nothing to commit, add the option **--allow-empty** to create an empty commit as a marker:
            ``` bash
            git status
            git commit -m "Final commit." --allow-empty
            git push
            ```
        + If you are using a different repository for your game do the above steps in that repository.
1. Build a web version of your game. Instructions for this step and the next two are [here](https://game-design-and-programming-template.github.io/Build-a-Game-for-the-Web/) if you need them.
1. Add it to the local clone of your website.
1. Do the add, commit, push dance to update your website.
1. Update the Playtest repository if it does not contain a current link to your game. [Here are the instructions](https://github.com/SKHS-Games-2018/Playtest) if you need them.

## When you've got it done -- see who you can help.
