# Using React in a Full-Stack Application: A Blog

So... you've managed to get to this point in the Bootcamp. Well done! 

At this point you have a strong awareness of the entire software development life cycle (SDLC) and are familiar with the fundamentals of creating both a back-end (using Express, Sequelize, and SQLite via JavaScript in Node - with duly tested procedures using jest) and a front-end (using Vanilla JS, HTML, and CSS and this week, React), and connecting them together.

----
## The Task: Building a Blog

It is hard to believe but once upon a time there was something called a web log (or "blog" for short). In those days, people actually wrote significant writings, either for themselves or for others to read. This was, of course, before more and more instantaneous technologies would violently command your attention (whilst you naively think that you are interested in these things), turning you into (paradoxically) a click-bait thirsty individual... 

### Back to a Blog

It's easy to get sidetracked! The task for today: build yourself a blog.

Of course this can be as complicated as you want to make it, but here I'll mention an MVP and suggest ways to increase the complexity. Remember, MVP is the minimum viable product: you *have to meet this* since it is the minimum you should be able to do.

---

### MVP
-  Create an application that allows you to add posts to your blog and delete them. Think of it this way: you need a space to type the post, a space to type the author's name, a button (or any other mechanism) to "post" the post and a button (or any other mechanism) to delete the post. Once you "post" your post it should appear somewhere in your page and when you delete them they should dissapear for ever.
- Use react to create the front end functionality and use fetch requests in order to communicate with your server.
- Your database is very simple: it contains one lonely table with rows containing a post and the name of the author who wrote the post.
- I told you this was the minimum, didn't I?
- Don't spend too much on CSS but don't let it look too bad.

### Extensions
- You've managed to do the MVP? That sounds great. You've built a full-stack application from a scratch and you've used React to add the functionality, and you're thirsty for more. Ok.
- Add a search bar to your blog. It allows you to search by author or by post.
- Add some tags to your posts and let your search bar search by tags as well.
- Your blog needs beautification: add enough styling to make your blog good-looking.

### Further Extensions
- You keep going, don't you?
- Change your DB structure to allow the same author (or authors) to post several posts (yep, one author can have many posts, but one post has only one author). Add an update post function that should be available only for the author of the post.
- Too simple or you managed it too swiftly? You could do this: posts can have multimple authors and these authors alone can delete the posts and update them.
- Add a login page to your blog.
- Deploy it somehow and sell your prodigious new app for millions.
- Retire and live a joyfully quiet life, hoping to pass away and see the blissfuls shores of eternity.

