# Movie Web
[![Sudo-Flix Image](.github/Sudo-Flix.png)](https://docs.undi.rest)  

# As many know, movie-web is no longer on github (or a website for that matter). i am using the sudo-flix source to fix that.
# As this is not done, you may use this [Movie web alternitive](https://movie-web-me.vercel.app) if things dont work.

**I DO NOT ENDORSE PIRACY**

## Links And Resources, these are docs from sudo-flix, i couldnt bother to make my own.
| Service        | Link                                                             | Source Code                                              |
|----------------|------------------------------------------------------------------|----------------------------------------------------------|
| Sudo-Flix Docs | [sudo-docs](https://docs.undi.rest)                          | [source code](https://github.com/sussy-code/docs)        |
| Extension      | [extension](https://docs.undi.rest/extension)                | [source code](https://github.com/sussy-code/browser-ext) |
| Proxy          | [sudo-proxy](https://sudo-proxy.up.railway.app)              | [source code](https://github.com/sussy-code/sudo-proxy)  |             
| Backend        | [sudo-backend](https://backend.undi.rest)                    | [source code](https://github.com/sussy-code/backend)     |
| Frontend       | [sudo-flix](https://docs.undi.rest/instances)                | [source code](https://github.com/sussy-code/smov)        |
| Weblate        | [sudo-weblate](https://docs.undi.rest/links/weblate)         | [source code](https://github.com/sussy-code/docs)        |

***I provide these (Not the docs, sudo-flix provides them) if you are not able to host yourself, though I do encourage hosting the frontend.***


## Referrers
None. This is a new fork so 


## Running Locally
Type the following commands into your terminal / command line to run Movie-web locally
```bash
git clone https://github.com/TailsisPeak/movie-web.git
cd movie-web
git pull
pnpm install
pnpm run dev
```
Then you can visit the local instance [here](http://localhost:5173) or, at local host on port 5173.


## Updating a Movie-web Instance
To update a Movie-web instance you can type the below commands into a terminal at the root of your project.
```bash
git remote add upstream [https://github.com/TailsisPeak/movie-web.git]
git fetch upstream # Grab the contents of the new remote source
git checkout <YOUR_MAIN_BRANCH>  # Most likely this would be `origin/main`
git merge upstream/main
# * Fix any conflicts present during merge *
git add .  # Add all changes made during merge and conflict fixing
git commit -m "Update Movie-web instance (merge upstream/main)"
git push  # Push to YOUR repository
```


## Contact Me
**Email:** *[keegankellyt@gmail.com](mailto:keegankellyt@gmail.com)* 
