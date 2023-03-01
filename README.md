### SEIR 123

# Jurassic Objects Lab

![Jurassic Objects](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmedia.giphy.com%2Fmedia%2FhDtZt3aoaTbos%2Fgiphy.gif&f=1&nofb=1)

## Lab Overview

In this lab, we'll practice using JavaScript objects by exploring the world of Jurassic Park!

## Getting Started

- `Fork` and `Clone` this repository
- `cd` into the directory
- `code .` to open in VSCode
- Create a new file with `touch` called `script.js`. You'll do all your work in this file. Remember, you can test your work by typing `node script.js` in the terminal.

## Lab Instructions

### Movie Object (quick warmup)

Create your own JavaScript object representing your favorite movie. I'm going to use Jurassic Park, obviously.

Example:

```js
const myMovie = {
  title: 'Jurassic Park',
  director: 'Stephen Spielberg',
  actors: ['Sam Neill', 'Laura Dern', 'Jeff Goldblum', 'Samuel L. Jackson'],
  releaseYear: 1993,
  duration: 128
}
```

1. After you have created your movie object, console log the title of your movie using `dot notation`
2. Console log the director's name
3. Console log the release year
4. Use `bracket notation` in combination with `dot notation` to access one of the actors and console log their name
5. Maybe your favorite movie came with an extended director's cut - write a statement that increases your movie object's duration by 25 minutes

What else can we do with objects in JavaScript, you may ask?

![Hammond](https://www.reactiongifs.us/wp-content/uploads/2014/03/ill_show_you_jurassic_park.gif)

##

Today we visit Jurassic Park to explore the wild world of objects!

Copy and paste each of these JavaScript snippets into your JavaScript file. You'll be working off of these as we go.

![Grant](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmedia.giphy.com%2Fmedia%2F8iWxnwt5p4vD2%2Fgiphy.gif&f=1&nofb=1)

#### Part 1

In this first part, we're in Montana to check in with Dr. Grant on his Velociraptor dig.

```js
// copy and paste into your script.js

const montana = {
  scientist: 'Dr. Alan Grant',
  depth: '10 meters',
  dino: 'Velociraptor'
}
```

1. Create a variable called `guestOfHonor` and assign its value to the name of the scientist in `montana`.

2. Access the value of the dino key found in the `montana` object and store it in a variable called `cleverGirl`.

![Nedry](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fi.imgur.com%2Fnm3gZMl.gif&f=1&nofb=1)

#### Part 2

Next, we head to Costa Rica, where Dennis Nedry and Dodgson (nobody cares) have already got a plan brewing to steal all of the dinosaur embryos...

```js
// copy and paste into your script.js

const costaRica = {
  programmer: 'Dennis Nedry',
  contact: 'Lewis Dodgson',
  payment: 750000,
  specimens: [
    'Tyrannosaurus Rex',
    'Triceratops',
    'Brachiosaurus',
    'Velociraptor',
    'Dilophasaurus',
    'Gallimimus'
  ],
  menthol: false
}
```

1. Store the array of specimens Nedry is supposed to steal in a variable called `barbasol`.

2. Make a variable called `favoriteDino` and assign its value to your favorite dinosaur within `specimens`.


#### Part 3

Welcome to Jurassic Park! Things are starting off great! Spared no expense!

```js
// copy and paste into your script.js

const jurassicPark = {
  expenseSpared: 0,
  staff: {
    founder: 'John Hammond',
    programmer: 'Dennis Nedry',
    engineer: 'John Arnold',
    security: 'Robert Muldoon',
    scientist: 'Dr. Henry Wu'
  },
  guests: ['Dr. Alan Grant', 'Dr. Ellie Sattler', 'Dr. Ian Malcolm', 'Donald Gennaro'],
  
}

```

1. Access the founder of Jurassic Park and store his name in an appropriately named variable.

2. The grandkids have arrived! Add "Tim" and "Lex" to the array of guests. You could assign the values to a specific index number of the array or you could look into [.push()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push).


3. Hold on to your butts. Sadly, remove "John Arnold" from the staff object. He wasn't able to get the systems back online.

![Butts](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fpyxis.nymag.com%2Fv1%2Fimgs%2Fe2e%2F373%2F9c3e0cd3af0edb4a7e22a1d0df6b756401-holdontoyourbutts.gif&f=1&nofb=1)




#### Part 4 - Gene Splicing

Not only are you becomming fantastic programmers, but Dr. Hammond now wants to hire you as a genetic biologist as well, creating new dinosaurs! 
Using OOP, create a new class called Dinosaur, with Name, Height, Weight, and isCarnivore as properties. What types of data would you want to use for each?

Once you have the blueprint created, create 3 new Dinosaur objects - Stegosaurus, Triceratops, and Spinosaurus. You can do a quick wiki search to find the information for each dinosaur, or you can just make it up yourself!



## All done! Great work!


# Resources

- [.push()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push)
- [delete](https://flaviocopes.com/how-to-remove-object-property-javascript/)
- [.splice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)
- [Hahahrawrrahaha](https://youtu.be/wJelEXaPhJ8)
