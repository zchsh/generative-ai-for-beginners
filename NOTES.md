# Notes

As I work through this course, I'm going to write notes here!

## 2023-12-17

### Basic setup

- Forked the [microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) repo
- Cloned it onto my local machine
- Installed `miniconda` by following [these steps](https://docs.conda.io/projects/miniconda/en/latest/#quick-command-line-install)

### `conda` environment setup

Created `.devcontainer/environment.yml`, with the following contents:

```yaml
name: development
channels:
  - defaults
dependencies:
  - python=3.11.5
  - openai
  - python-dotenv
```

And then, from the root of this project, ran:

```sh
conda env create --name ai4beg --file .devcontainer/environment.yml
```

Followed by:

```sh
conda activate ai4beg
```
