# HTML Injecting Websites of Students in ITUIS18 Group
This project aims to crack passwords of students whom completed the assignment 2 (a2) in ITU's BLG101E course, then inject their websites that are written in HTML with **non-destructive** and **non-malicious** code.

## How to install and use
- Clone the repo (Make sure you are in your desired working directory)

```shell
git clone https://github.com/fatihaltinpinar/ituis18_hacking.git
```

- Get and update the repositories

```shell
pip3 install gitpython
python3 get_repositories.py
```
- Collect all the required data

```shell
python3 parse.py
```

- Inject the sites with the hardcoded message in "injection.py"
*You can change the message at line 61 under the variable name "hackMessage"*
```shell
python3 injection.py
```
