## Setup

1. Download `nn_model.h5` from releases on github and place it in the project root.

2. We recommend that you install dependencies in a seperate environment. Here's how -

#### Create a conda Environment

- Install anaconda and run the following commands

```sh
conda create -n sih python=3.5
conda activate sih
```

- Make sure that you are in the **sih** conda environment throughout the setup process.
- You can validate this by looking at the environment name prefixed to your command prompt **(sih)**.

#### Install the deps

```sh
pip install -r requirements.txt
```
3. Get the twitter credentials from twitter developer's account and place the appropriate secret keys in `sa_twitter.py` (from line 20 to 23).

4. Follow the steps mentioned in this [google cloud documentation](https://cloud.google.com/translate/docs/setup#python) making sure that `GOOGLE_APPLICATION_CREDENTIALS` variable is set in your terminal environment.

5. Start the application.
#### Run the app

- In the project root folder, run the following command -

```sh
python index.py
```

#### Getting out of the created conda environment

```sh
conda deactivate
```
