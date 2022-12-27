# The Honeypot Dataset
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/verovaleros/honeyDataset)

This repository offers an structured list (csv) of honeypots that allows quickly searches. Access the [honeyDataset](honeyDataset.csv).

## Features

The following information of each honeypot is indexed:

- Name: name of the honeypot
- Honeypot Type: specific service following the categorization of [^1].
- Interaction Level: low, medium, high or N/A for unknown.
- Description: short description of the honeypot.
- Programming Language: main programming language of the honeypot software
- Repository: URL to the honeypot repository
- Creation: year of the first commit in the linked repository 
- Maintained: not maintained, rarely maintained, sporadically maintained, actively maintained

## Adopted Honeypots

Many honeypots are no longer maintained and it has become hard to run and test them as libraries and packages evolve. In an aim to preserve them, I have started adopting some honeypots, mainly forking them, improving the documentation whenever possible, and creating a docker image that can be used to run it without having dependencies issues. The honeypots below have been adopted:

| Honeypot   | Adopter.     | Docker Image | Last commit | DockerHub pulls |
| ---------- | ------------ | ------------ | ----------- | --------------- |
| Delilah    | @verovaleros | Yes          | ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/verovaleros/honeypot_delilah) | ![Docker Pulls](https://img.shields.io/docker/pulls/verovaleros/delilah?color=green) |
| Honeyprint | @verovaleros | Yes          | ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/verovaleros/honeypot_honeyprint) | ![Docker Pulls](https://img.shields.io/docker/pulls/verovaleros/honeyprint?color=green) |
| NoSQLpot   | @verovaleros | Yes          | ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/verovaleros/honeypot_nosqlpot) | ![Docker Pulls](https://img.shields.io/docker/pulls/verovaleros/nosqlpot?color=green)|

## References
[^1]: paralax/awesome-honeypots - an awesome list of honeypot resources, GitHub, [https://github.com/paralax/awesome-honeypots](https://github.com/paralax/awesome-honeypots). Accessed on 05/13/2022.
