# Python Coding Assessment - Internship Screening

Welcome! This repository contains the coding assessment for the internship selection process.

## Overview

Complete **3 Python programming questions** and submit your solutions via your forked repository.

## Questions

1. **Q1: Stable Character** - Find the first character with all occurrences grouped together
2. **Q2: Compressed Stack Length** - Calculate remaining stack size after cancellations
3. **Q3: Event Overload Detector** - Identify users with excessive event activity

## Getting Started

### Step 1: Fork This Repository

Click the "Fork" button at the top right of this page to create your own copy.

### Step 2: Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### Step 2.5: (Optional) Create Virtual Environment

```bash
python -m venv venv

# On macOS/Linux:
source venv/bin/activate

# On Windows:
venv\Scripts\activate
```

### Step 3: Implement Your Solutions

Edit these files and replace the `pass` statements with your implementations:

- `q1.py` - Implement `first_stable_character(s)`
- `q2.py` - Implement `compressed_stack_length(lst)`
- `q3.py` - Implement `find_overloaded_users(events)`

**Important:**
- Do NOT change the function names
- Do NOT change the file names
- Keep the function signatures exactly as provided

### Step 4: Test Individual Questions

You can also test each question individually:

```bash
# Test Q1
python q1.py

# Test Q2
python q2.py

# Test Q3
python q3.py
```

### Step 5: Submit Your Solutions

**Make sure your repository is PUBLIC**, then fill out the submission form with your basic details and repository URL:

**Submission Form:** https://forms.gle/szQUUJcK2CyUSoBT8

You'll need to provide:
- Your name
- Your email
- Your GitHub repository URL (e.g., `https://github.com/YOUR_USERNAME/YOUR_REPO_NAME`)

## Files in This Repository

```
.
├── README.md           # This file
├── q1.py              # Q1: Stable Character (YOUR CODE HERE)
├── q2.py              # Q2: Compressed Stack Length (YOUR CODE HERE)
└── q3.py              # Q3: Event Overload Detector (YOUR CODE HERE)
```

## Evaluation Criteria

Your solutions will be evaluated on:

1. **Correctness** (50%)
   - Passing all test cases (shown and hidden)
   - Proper edge case handling

2. **Code Quality** (20%)
   - Clean, readable code
   - Proper variable naming
   - Good code structure

3. **Efficiency** (30%)
   - Time complexity
   - Space complexity
   - Algorithm efficiency

## Requirements

- Python 3.7 or higher
- No external libraries required (use only Python standard library)
- Each solution must complete within **10 seconds**

## Common Mistakes to Avoid

❌ Changing function names (must be exact)
❌ Changing file names (must be q1.py, q2.py, q3.py)
❌ Making repository private (must be public)
❌ Not testing locally before submission
❌ Syntax errors or import errors
❌ Using external libraries (use standard library only)


### Think About Complexity

When designing your solution, consider:

- **Time Complexity**: How does your solution scale with input size?
  - O(n) is good for most problems
  - O(n²) might be acceptable for small inputs
  - O(2ⁿ) is usually too slow

- **Space Complexity**: How much memory does your solution use?
  - O(1) constant space is best
  - O(n) linear space is usually acceptable

## Problem Details

Detailed problem descriptions, examples, and test cases are provided in each Python file:

- **Q1** - See `q1.py`
- **Q2** - See `q2.py`
- **Q3** - See `q3.py`

## Testing Notes

- Each `.py` file contains example test cases in the `if __name__ == "__main__"` block
- Make sure your code handles edge cases and unusual inputs
- Your code should be efficient enough to handle larger inputs

## Need Help?

- Read the detailed problem descriptions in each `.py` file
- Check the examples provided in the docstrings
- Run each `.py` file to test your implementation
- Review your algorithm for correctness and efficiency

## Submission Checklist

Before submitting, make sure:

- [ ] All three files (q1.py, q2.py, q3.py) are implemented
- [ ] All example test cases pass when running each .py file individually
- [ ] Repository is **PUBLIC** (not private)
- [ ] Code is clean and readable
- [ ] Function names are unchanged
- [ ] File names are unchanged
- [ ] No syntax errors
- [ ] Submitted form with your details and repository URL 

## Good Luck!

Focus on writing correct, clean, and efficient code. Test thoroughly before submission!

---

