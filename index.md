## To do Today:

1. Check the class roster (links below), click on your name and verify that it takes you to your GitHub Profile. If it does not: fork the the roster repository, edit the link for your name, test that it works, and finally make a pull request so that the link can be updated.
    - [2nd Block](https://github.com/SKHS-Games-2018/2A2/blob/master/index.md)
    - [7th Block](https://github.com/SKHS-Games-2018/2B7/blob/master/index.md)
    - [8th Block](https://github.com/SKHS-Games-2018/2B8/blob/master/index.md)
2. On your GitHub profile make sure the following repositories are visible in the pinned repository list:
      - Your website -- username.github.io (e.g., douglasurner.github.io).
      - Your fork of the [Playtest](https://github.com/SKHS-Games-2018/Playtest) repository.
      - Your fork of the [PlaygroundProjectStarter](https://github.com/Game-Design-and-Programming-Template/PlaygroundProjectStarter) repository.
      - The repository holding your game (if it is not your PlaygroundProjectStarter fork).
1. Push your final game to GitHub:
      - Start by making sure that the latest work on your game is on GitHub:
        + Navigate to your clone of the PlaygroundProjectStarter code.
        + Launch `Git Bash` and run the following commands:
            ``` bash
            git status
            git add any-new-or-changed-files-or-folders
            git commit -m "Final commit."
            ```
        + If git status told you that there is nothing to commit, add the option **--allow-empty** to create an empty commit as a marker:
            ``` bash
            git status
            git commit -m "Final commit." --allow-empty
            git push
            ```
        + If you are using a different repository for your game do the above steps in that repository.
1. Build a web version of your game.
1. Add it to the local clone of your website.
1. Do the add, commit, push dance to update your website.
1. Update the Playtest repository if it does not contain a current link to your game.
1. Check out the games on the Playtest site.
