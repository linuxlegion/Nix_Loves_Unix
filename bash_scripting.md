
# **Linux Legion workshop:**

## The best place to get started with your Unix jouney

### Advantages:
> - **Automation:** 
> Bash scripts can automate repetitive tasks, saving time and effort. This can be especially useful for tasks that are performed regularly, such as backing up files or updating software.
> - **Efficiency:**
> Bash scripts can be more efficient than manual execution of commands. This is because scripts can be written to take advantage of features such as loops and conditional statements.
> - **Portability:**
> Bash scripts are portable across Unix-like operating systems, such as Linux and macOS. This means that scripts can be written once and used on multiple systems.
> - **Flexibility:**
> Bash scripts can be used to perform a wide range of tasks, from simple file management to complex system administration. This makes them a versatile tool for users of all skill levels.
> - **Error reduction:**
> Bash scripts can help to reduce errors by automating tasks and providing a consistent way to perform them. This can be especially important for complex tasks that are prone to human error.



<hr>


## Lets first start with the terminal

### try executing these commands

- ls
- cat
- echo
- let
- cd
- touch
- nano
- chmod



<hr>

# Now then lets start bash scripting

make sure to save these as a .sh file

## The Command-Line Circus
```bash
#!/bin/bash

echo "Welcome to the Command-Line Circus! 🎪"
echo "Step right up and witness the magic of Bash scripting!"

# Cue the drumroll...
sleep 2

```

## Juggling Variables
```bash 
# Juggling Variables
juggle="Now you see me!"

echo "Juggling act begins: $juggle"

# Let's add a plot twist!
juggle="Now you don't!"

echo "Juggling act continues: $juggle"
```

## The Simple If 
```bash 
# The Simple If Statement
age=25

if [ $age -ge 18 ]; then
    echo "You are eligible to vote. Exercise your democratic right!"
fi
```

## The Looping Lions
```bash
# The Looping Lions
echo "Behold the Looping Lions!"

for lion in Simba Nala Mufasa Timon Pumbaa; do
    echo "The mighty lion: $lion"
done

```
## The Great Escape
```bash 
# The Great Escape
escape() {
    echo "I'm breaking free!"
}

# Cue the dramatic music...
escape
```

## The Interactive Illusion

```bash 
# Act 6: The Interactive Illusion
echo "Step into the spotlight with our Interactive Illusion!"

# Prompt the user for input
read -p "What's your favorite magical creature? " favoriteCreature

# Let's reveal the chosen creature!
echo "Ah, the mystical $favoriteCreature! A splendid choice indeed!"
```

## The Grand Finale
```bash
#!/bin/bash

echo "🌹 Valentine's Day Script: Spreading Love through Files! 💕"

# Prompt user for file input
read -p "Enter the filename to read: " inputFile

# Check if the file exists

# Create a lovely grep operation
valentineGrep=$(grep -i "love\|heart\|valentine" "$inputFile")

# Check if any matching content is found
if [ -z "$valentineGrep" ]; then
    echo "No love found in the file. The heart is still searching!"
else
    echo "Love is in the air! Here's what we found:"
    echo "$valentineGrep"
fi

```


