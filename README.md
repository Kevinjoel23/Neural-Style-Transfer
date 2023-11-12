# Neural-Style-Transfer
Dashtoon Engineer Generative AI Submission

# Jupyter Notebook Repository

This repository contains a Jupyter Notebook that performs image style transfer. The notebook requires two input images: a style image and a content image. This README.md file provides instructions on how to use the Jupyter Notebook and set up a virtual environment for the project.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Jupyter Notebook
- Virtualenv (for creating a virtual environment)

### Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### Set Up a Virtual Environment

It's good practice to use a virtual environment to manage dependencies for your project. If you don't have virtualenv installed, you can install it using the following command:

```bash
pip install virtualenv
```

Now, create a virtual environment in the project directory:

```bash
virtualenv venv
```

Activate the virtual environment:

- On Windows:

  ```bash
  .\venv\Scripts\activate
  ```

- On Unix or MacOS:

  ```bash
  source venv/bin/activate
  ```

### Install Dependencies

Install the required Python packages within the virtual environment:

```bash
pip install -r requirements.txt
```

### Run the Jupyter Notebook

Start the Jupyter Notebook server:

```bash
jupyter notebook
```

This will open a new tab in your web browser. Navigate to the notebook file (`run_style_transfer.ipynb`) and open it.

### Notebook Usage

1. Open the Jupyter Notebook in your browser.
2. Ensure that the virtual environment is activated.
3. Run the cells in the notebook in order.
4. Provide the path or URL for the style image and content image when prompted.
5. Follow the instructions within the notebook to complete the style transfer process.

## Additional Notes

- Make sure to deactivate the virtual environment when you're done:

  ```bash
  deactivate
  ```

- Feel free to customize the notebook or contribute to the repository.

Happy styling!

### Required Libraries

Make sure to install the following Python libraries before running the code:

- **torch** (PyTorch): `pip install torch`
  - Version: 2.1.0+cpu

- **PIL** (Python Imaging Library): `pip install pillow`
  - Version: 9.4.0

- **matplotlib**: `pip install matplotlib`
  - Version: 3.7.1

- **torchvision**: `pip install torchvision`
  - Version:  0.16.0+cpu
- **numpy**: `pip install numpy`
  - Version: 1.24.3



