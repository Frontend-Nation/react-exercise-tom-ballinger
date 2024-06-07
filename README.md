# Convex Tour Chat

The is a sample app for the Frontend Nation Forge Day exercise.

The Convex docs at [docs.convex.dev](https://docs.convex.dev) will be useful in
for learning how to use Convex beyond what there's time to show at the beginning.

For a more guided experience [go check out the tutorial](https://convex.dev/start).

These exercises build on each other and have solutions listed.
Jump into any particular step of the tutorial with a branch:

1.  Simple chat app (branch = main, 0-start)
1.  Simple chat app with correct message display (branch = 1-smileys)
1.  Enhanced chat app a "likes" feature added (branch = 2-likes)
1.  Enhanced chat app with a GPT integration (branch = 3-gpt)

# To run

    $ npm i
    $ npm run dev

# Exercises

Once you have the app running try a few exercises:

- How would you replace ":)" with a smiley emoji?
  hint: this could be done on the frontend or in the query

- how would you impose a character limit?
  hint: the mutation would be a good place to check

- how would you show an animation each time a new message comes in?
  hint: this is a client-side concern: need to notice that the query updates.

- how would you make messages be deleted after a certain amount of time?
  hint: look at the Convex docs for "scheduled functions."

- how would you add an AI chat bot
  hint: see the [Convex Tour](https://docs.convex.dev/get-started) for more info

- how would you implement likes on messages?
  hint: see the [Convex Tour](https://docs.convex.dev/get-started) for more info
