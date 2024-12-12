# Programming Portfolio Example

 ![example](Capture.png)

## Adventure Game
![Image](http://programmingisfun.com/wp-content/uploads/2016/06/adventuregameprogress.png)

A game that demonstrates object-oriented programming principles inheritance, encapsulation, and polymorphism.
[C# Adventure Game](http://programmingisfun.com/learn/c-sharp-adventure-game)

## Study Application
A [Study Application](https://gist.github.com/janell-baxter/9689a2810202f4b0697a4ddce077fad1) that reads in terms and definitions from an external file (or files).

## Explorable Areas
A command-line application with areas to explore and items for the player to find in each area. Before you can travel to the lake for snorkeling, the equipment must be found in one of the other areas. [Explorable Areas](https://gist.github.com/janell-baxter/555f973ebfecb3a4da21b175cbc8f601)

## Underwater Creatures
[Underwater Creatures](https://gist.github.com/janell-baxter/4e593fe89ebede781baf7d5dce308829) demonstrates inheritance, polymorphism, and encapsulation. 

## Adopt-An-Insect
An application that lets a player create a custom insect character: [Adopt-An-Insect](https://gist.github.com/janellbaxter/4662ba74972338ea92f40f1e6051e220)

## Shift Cipher
[Shift Cipher](https://gist.github.com/janell-baxter/650c9e7b50fe760ef7d07f9b80b407e7) is an application that encodes and decodes using a simple substitution cipher. 

## Trivia Game
[Trivia Application](https://github.com/janellbaxter/TriviaApplication)

## Zero Sum
[Zero Sum](https://github.com/janellbaxter/zero-sum-pennies) is a C# WPF application of the penny game described in 'The Computational Beauty of Nature'. 

## WPF Navigation
[WPF Navigation](https://github.com/janellbaxter/WPF-Navigation) is a C# WPF example of using a frame and multiple pages.

## WPF Character Customization (Radio Buttons)
[WPF-CharacterCustomizationExample](https://github.com/janellbaxter/WPF-Navigation) is an example of using WPF and C# to allow a player to modify something with radio button choices (like an item or a creature companion).

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

