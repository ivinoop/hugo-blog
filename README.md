# Hugo Blog Site built from scratch

View site here 👉 [Live link](https://capable-starship-1b455b.netlify.app/)

### Features at a glance -

- Markdown based blog posts/content
- Mobile responsive
- Pagination
- Dark/Light mode toggle
- Hugo templating engine with the power of Go behind the scenes

---

### How to run locally -

- Clone this repo to local machine
- Run the command `hugo server -D` to run in development mode
- Make changes if needed
- Run the command `hugo` to build files to the `public` folder
- Run `hugo server` to see the site in action (again)
- Deploy to any hosting service of your choice

--- 

### Important points to note if deploying on Netlify -

- Make sure to first run `hugo` to build the static site files on to the `public` folder
- In the Netlify dashboard, just select the GitHub repo, and scroll down to `Environment Variables` section
  - Click 'Add New'
  - Enter `HUGO_VERSION` as the variable name and `0.121.1` or whatever is the version of Hugo at the time of your deployment
    - You can get Hugo version with this command - `hugo env` (as of Dec 31, 2023 lol)
- Click `Deploy Site`