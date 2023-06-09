# SICP Exercise Implementations

My implementation of exercises from the classic book

> **Structure and Interpretation of Computer Progams**
> by - Harold Abelson and Gerald Jay Sussman with Julie Sussman

### Interested in playing around?

_I make the assumption that you have scheme installed locally, or running via docker (with volumes), if not check the "Running via docker" section below._

- Ensure you're in the cloned repo folder i.e `cd sicp-exercises`
- Start your scheme REPL (or run via docker container with volume setup to your current directory)
- Run `(load "/path/to/exercises/exercise-{x.x}")`. Solid example below to execute `exercise-1.2`, 
  * `(load "exercise-1.2")`
  * `run`

For exercises that require arguments, `run` would be executed like any other procedure, e.g to execute `exercise-1.3`, use the command
- `(load "exercise-1.3")`
- `(run 1 2 3)` (with these inputs, answer is 13)


__Note__: Immediately your environment is setup, first run `(load "simplyscm")` to load the SICP scheme lib used in the video course of the book at Berkeley.

__Note__: I use `run` in each exercise file as the general command to execute the solution that prints the final output/answer to the exercise.


### Running via Docker

Follow the instructions by **"ProfessorHarveysNumberOneFan"** in his review on this page https://archive.org/details/ucberkeley_webcast_l28HAzKy0N8


__PS__: I only try to implement the exercises I can as I was studying the book. And I ignore exercises that require just the evaluation of a given expression, seeing that the answer is already part of the exercise.
