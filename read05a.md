# Summary of Read 05a

## Heroku
1. I used brew to install heroku through my terminal. It worked
2. I then cloned a simple repo with node dependency manager package.json
3. Then I rean `heroku create` to create an app in that repo
4. to deploy the code, I ran `git push heroku master` -- which I don't really know where that is going on git?
5. Making sure that the app is running I ran`heroku ps:scale web=1`
6. To open the app, you just run `heroku open` in the terminal.
7. heroku keeps track of all events, to see those events I ran `heroku logs --tail`