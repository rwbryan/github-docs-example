# Writing Good Docs

## Step 1 - Using Codeblocks <sup> [1] </sup>

Codeblocks in markdown make it *very easy* for tech people to **cut/paste and share code.** 
A good Cloud Engineer uses Codeblocks whenever possible.

Because it allows others to cut/paste and help debug possible issues. 

Python Code Example 01
```python
# Ask the user for a number
number = int(input("Enter a number: "))

# Print the number back to the user
print("You entered the number", number)
```
Bash Code Example 02

```bash
#!/bin/bash

# Create the user account
sudo useradd -m -s /bin/bash testaccount

# Set the password for the user account
sudo passwd testaccount

# Add the user to the sudo group
sudo usermod -aG sudo testaccount

# Print a message to the user
echo "The user account testaccount has been created."
```
> Example of a reference pointing to link 1 <sup> [1] </sup>

## Step 2 - Use GitHub tasks lists (check boxes) 
- [x] Finish Step 1
- [ ] Fihish Step 2
- [ ] Finish Step 3

## Step 3 Emoji examples <sup> [2] </sup>

Happy :smiley:
Cloud :cloud:

## Step 4 Create Tables

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |


## References (Links)

GitHub doc page with numbered indicator to reference in the above text

- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) <sup> [1] </sup>
- [List of GFM Emojis](https://gist.github.com/rxaviers/7360908) <sup> [2] </sup>
  
