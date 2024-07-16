# timetracker

It's a small bash script that allow me to track my professional tasks during the
day.

## Installation

Copy the file in a folder that is under PATH environment variable.

## How to use it

The command will ask you to run `timetracker init` first. It will create
`$HOME/.timetracker` in which you will find all the entries you will create, in
file named after the day for which entries has been created.

You may have, after some usage, something like this :

```
$HOME/.timetracker/
├─ 2024-07-10
├─ 2024-07-11 
└─ ...
```

### Initialize the .timetracker folder

```bash
timetracker init
```

### Start tracking activities

```bash
timetracker track "Let's work on foo topic"
```

### Display tracking of the day

```bash
timetracker display
```

```
# It will display something like :

12:23:45: Let's work on foo topic
```

### Stop the day

```bash
timetracker stop
```

### Display help

```bash
timetracker
timetracker help
```
