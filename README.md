# pairing-cards
Design of a physical set of cards which facilitate conversations while pair programming

## Ideas

```mermaid
mindmap
    root((Pairing Cards))
        Things to say
            What do you think the next step is
            How would you solve this problem with a pen and paper?
            Let‘s get something working
            Tell me what you think our objective is
            Where do you think we are up to?
            What is the simplist test we could write?
        Concepts
            YAGNI
            Red, Green, Refactor
            Spike
        Practices
            One keyboard, one screen
            Screen share vs IDE feature
            To do list
                Not breaking flow
            Zooming out
            Narrate / highlight keystrokes
            Time boxed exploration
            Negotiated regime change
            Minimising distractions
                Phones
                Focus mode
                DND
            Co authoring commits
            Commit little, commit often
            WIP commits with task lists
            Staying close to green
            Drawing diagrams
            Swapping roles
            Sharing personal space considerately
            Keymapping
            Starting with the assertion
            Iterative software cycle
                Shortening feedback loops
                INVEST
            Approaching a kata: 1. Describe in own words, 2. Look to simplify, 3. Define inputs and outputs, 4. Write the steps you’d take on paper in human language with inputs and outputs
        Styles
            Ping pong
            Classic
            Tour guide
            Backseat driver
        Checking in
            Style
            Who’s machine
            Lunch
            Meetings
            Breaks
            Finish
```

## Concepts

### Approaching a kata

1. Describe the task in your own words  
   This helps to ensure that you actually understand it and that your understanding is the same as the other person's. Using your own words forces your brain to think about it differently. You might find at this point that you can’t describe it.
1. Look at how you can simplify it  
   Finding a starting point for a problem can be tough. If there’s a way to simplify the problem, you can get started quicker. If there are four rules, only consider the first one. Would it be easier to solve if there were only one item of input? Perhaps you can use some really simple input to start with so that you don’t need to consider different formats, etc.
1. Define the inputs and outputs  
   Think about the problem as a function. What are the parameters? Do they have specific types? What do the items represent? What value do you need to return, and what type is it?
1. Write the steps you’d take
   Although you might not think you know how to write code to solve it, you can probably describe how you would solve the problem with a pen and paper. Write these steps down in human language. Perhaps consider what the inputs and outputs of each step are. This will give you an idea of how you can get started and allow you to keep track of how far through you are.
