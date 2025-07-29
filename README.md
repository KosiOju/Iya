# Iya
work in progress.

## How to run (Windows)

#### Requirements
- Install Python (I would suggest you use [VSCode](https://code.visualstudio.com)).

---

1. Download the Github folders.
2. Set-up a virtual environment (venv) as it allows you to manage dependencies
for different projects and maintain a cleaner set-up and PC.

> Open up Powershell and navigate to the downloaded folder: cd path/to/folder

> Create a virtual environment: python -m venv venv

3. Activate the venv and install the packages.
> venv\Scripts\activate

> pip install -r requirements.txt

4. Run the backend on powershell.


...If the backend is not running you won't have full API functionality.


> python backend.py

6. Run the frontend on VScode.
....1. Install the "Live Server" extension on VSCode.
....2. Right-click the `index.html` (frontend) file, and select
   "Open with Live Server" - to open in your browser.

   > The link will be like this: http://127.0.0.1:5500


