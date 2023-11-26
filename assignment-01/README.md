# Assignment 1: Signal Flipping Detection

## Overview

This assignment aims to familiarize you with the project repository, set up your local development environment, and commence your hands-on programming journey by implementing a simple function to detect signal flipping in trading scenarios.

## Objectives

- Clone the project repository to your local machine.
- Set up your local development environment.
- Understand and implement basic control flow in programming.
- Utilize Git and GitHub for version control and code submission.

## Setup Instructions

1. **Clone the Repository**:
    - Click on the 'Code' button on the repository page on GitHub.
    - Copy the URL provided.
    - Open your terminal and run the following command:
    ```bash
    git clone [Paste the URL here]
    ```

2. **Set Up Your Local Environment**:
    - [Provide any necessary instructions to set up the development environment, install dependencies, etc.]

## Assignment Instructions

You are required to write a function using the programming language of your choice. The function should have the following signature:

```javascript
function detectSignalFlip(currentSignal: float, previousSignal: float) : string
```

### Inputs:

- `currentSignal` (floating point number): The current signal value.
- `previousSignal` (floating point number): The previous signal value.

### Output:

- A string indicating the signal flipping status.

### Business Logic:

- If `currentSignal` < 0 and `previousSignal` > 0, return the string "SIGNAL HAS FLIPPED FROM BUY TO SELL".
- If `currentSignal` > 0 and `previousSignal` < 0, return the string "SIGNAL HAS FLIPPED FROM SELL TO BUY".
- Otherwise, return an empty string "".

## Submission

1. **Code Your Solution**:
    - Create a new branch for this assignment by running:
    ```bash
    git checkout -b assignment-1
    ```
    - Write your code and save the file.
    - Test your function to ensure it works as expected.

2. **Commit and Push Your Changes**:
    - Stage your changes by running:
    ```bash
    git add .
    ```
    - Commit your changes with a descriptive message:
    ```bash
    git commit -m "Completed Assignment 1"
    ```
    - Push your changes to GitHub:
    ```bash
    git push origin assignment-1
    ```

3. **Open a Pull Request**:
    - Navigate to the 'Pull requests' tab on the GitHub repository page.
    - Click on 'New Pull Request'.
    - Select your `assignment-1` branch from the dropdown.
    - Click on 'Create Pull Request'.
    - Provide any necessary information about your solution and then click on 'Create Pull Request' again.

Your work will be reviewed, and feedback will be provided on your pull request.

Good luck, and remember: consistency is key to growth in software engineering!
hey there

**Submission**:

def detect_signal_flip(current_signal: float, previous_signal: float) -> str:
    if current_signal < 0 and previous_signal > 0:
        return "SIGNAL HAS FLIPPED FROM BUY TO SELL"
    elif current_signal > 0 and previous_signal < 0:
        return "SIGNAL HAS FLIPPED FROM SELL TO BUY"
    else:
        return ""
        
    