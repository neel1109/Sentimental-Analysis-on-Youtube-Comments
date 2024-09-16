## Intructions to run

1. Ypu can either clone the repository or download it. Make sure to `cd` into the folder.:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Create a virtual environment:
   - On macOS/Linux/Powershell(Windows):
     ```bash
     python -m venv .venv
     ```


3. Open Activate the virtual environment:
   - On Windows:
     ```Powershell
     .\.venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the `app.py` to run the project. You terminal should show something like this:
   ![alt text](images/image.png)
   
6. Go to any browser and enter the localhost address, in this case: `http://127.0.0.1:5000`
