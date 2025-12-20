# What to do now?
Whenever you want to change your site, you just follow the Hugo Workflow:

## 1. Create Content: 
Run 
````
hugo new posts/my-first-post.md
````
in your terminal. This creates a new file in your `content/posts` folder.

## 2. Edit: 

Open that file and write your thoughts. (Make sure to change `draft: true` to `draft: false` at the top of the file when you're ready for the world to see it).

## 3. Preview:
Run `hugo server ` on your computer to see how it looks at localhost:1313.

## 4. Publish: 
Once you’re happy, run the "Big Three":
````
git add .
git commit -m "Added my first post"
git push
````

Within a minute, GitHub Actions will update your live website at joys-corner.com automatically.
