# Pandas Workout — 200 Exercises

Notebooks and Solutions to 200 Pandas exercises from Reuven Lerner's Pandas Workout Textbook.

All Problems are from his textbook.

Each chapter includes an unexecuted `exercise_nn.ipynb` template so the chapter
folder is included in Git. Copy it to `exercise_NN.ipynb`, replacing `NN` with
the exercise number (for example, `exercise_08.ipynb`), and keep the template.
Existing exercise notebooks retain their original names. Select your local
Python environment as the notebook kernel before running cells.

The root `.gitignore` applies throughout the repository, including nested
chapter folders. It excludes virtual environments, notebook checkpoints,
Python caches and build outputs, local environment settings, and OS/editor
artifacts. The existing policy of ignoring `data/` directories is retained;
exercise notebooks remain eligible for tracking. `.env.example` files may be
tracked to document configuration without local values.

Ignore rules do not affect files already tracked by Git. Remove any previously
tracked local artifacts from the index with `git rm --cached <path>` to keep
the local copy while recording their removal from the repository.
