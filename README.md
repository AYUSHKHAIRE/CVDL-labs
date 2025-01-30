
# CVDL Labs Setup Guide

## BT22CSD028

This guide will help you set up the project on both Windows and Linux environments.

### Prerequisites

- Ensure you have Python installed. You can check by running `python --version` or `python3 --version` in your terminal.
- You need to have `git` installed for cloning the repository. You can verify with `git --version`.

### Setup Instructions

#### Step 1: Clone the Repository

Open a terminal and run the following command to clone the repository:

```bash
git clone https://github.com/AYUSHKHAIRE/CVDL-labs.git
```

#### Step 2: Create a Virtual Environment

Navigate into the project directory:

```bash
cd CVDL-labs
```

##### For Linux/Mac:

Create a virtual environment using the following command:

```bash
python3 -m venv cvenv
```

##### For Windows:

```bash
python -m venv cvenv
```

#### Step 3: Activate the Virtual Environment

##### For Linux/Mac:

Activate the virtual environment:

```bash
source cvenv/bin/activate
```

##### For Windows:

Activate the virtual environment:

```bash
cvenv\Scripts/activate
```

#### Step 4: Install Dependencies

With the virtual environment activated, install the required dependencies by running:

```bash
pip install -r requirements.txt
```

#### Step 5: Run the Project

Once the dependencies are installed, you can start working on the project as per the instructions provided in the repository.

---
