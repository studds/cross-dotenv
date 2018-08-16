# cross-dotenv

cross-dotenv is an unholy alliance of:

- [cross-env](https://github.com/kentcdodds/cross-env) (for it's cross-platform inline definition of environment variables), 
- [dotenv](https://github.com/motdotla/dotenv) (for it's loading of environment variables from a .env file), and
- [cross-var](https://github.com/elijahmanor/cross-var) (for it's cross-platform substition of environment variables (via copying and pasting code)).

Funnily enough, none of these projects alone seem to do all of this.

- Environment variable substitution is unreliable with [cross-env](https://github.com/kentcdodds/cross-env)
- [dotenv](https://github.com/motdotla/dotenv) really just loads the .env file
- [run.env](https://github.com/palanik/run.env) doesn't work on windows.
- [cross-var](https://github.com/elijahmanor/cross-var) doesn't allow inline definition of environment variables.