# `mit` - Generate the MIT license right in the CLI

As the name suggested, `mit` generate the MIT license right in your terminal, without using the browser
to search for it.

# Quick Start

0. Make sure you have `python`, `pip` and [`pipenv`](https://pipenv.pypa.io/en/latest/) installed
1. Clone this repo and go to the repo directory
2. Enable virtual environment using `pipenv`

```
pipenv shell
```

3. Install all the dependencies required:

```
pipenv install
```

4. Finally, run `main.py`:

```
pipenv run python3 main.py <YEAR> <NAME>
```

Where:
- `YEAR` is the copyright year
- `NAME` is your name/full name

# Credits

Thanks to [`typer`](https://typer.tiangolo.com) for providing the CLI, although using it is a bit overkill.
I take the `README.md` content of this project from [`wordlefind`](https://github.com/HoangTuan110/wordlefind), one of my other projects.

# License

MIT
