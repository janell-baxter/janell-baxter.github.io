# Portfolio Example (Introduction to Programming)
![Image](https://avatars1.githubusercontent.com/u/18712834?s=400&u=7a3229acbe5a3b42107c786e44accdbf0707d746&v=4)

## Applications
- [Trivia Application](https://github.com/janellbaxter/TriviaApplication): A trivia application framework.
- [Zero Sum](https://github.com/janellbaxter/zero-sum-pennies): A C# WPF application of the penny game described in 'The Computational Beauty of Nature'. 
- [WPF Navigation](https://github.com/janellbaxter/WPF-Navigation): A C# WPF example of using a frame and multiple pages.
- [WPF-CharacterCustomizationExample](https://github.com/janellbaxter/WPF-Navigation): An example of using WPF and C# to allow a player to modify something with radio button choices (like an item or a creature companion).
- [HistoricalFigures-InheritanceExample](https://github.com/janellbaxter/WPF-Navigation): An example of child classes inheriting from a base class in WPF and C#.

More projects on my [github repo site](https://github.com/janellbaxter?tab=repositories)


### Code Gists

1. [Gists used in class](https://gist.github.com/janell-baxter)
2. [Programming is Fun Gists and other example code](https://gist.github.com/janellbaxter)


Code examples can be shown like this:
```markdown
private void Play()
        {
            foreach (TriviaItem triviaItem in Questions)
            {
               Clear();
               WriteLine(player.PlayerInformation());
               WriteLine(triviaItem.Question);
                string input = ReadLine();
                if (triviaItem.CheckAnswer(input))
                {
                    player.IncrementScore();
                }
            }
        }
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

