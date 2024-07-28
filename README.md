
## Installation

### Prerequisites
- Python 3.x
- `pip` package installer

   ```

2. **Create and activate a virtual environment:**

   ![image](https://github.com/user-attachments/assets/19eb27b2-ccec-48c4-9f4a-f62d5358f944)

   ```sh
   python -m venv myenv
   myenv\Scripts\activate  # On Windows
   # source myenv/bin/activate  # On macOS and Linux
   ```

4. **Install the required packages:**
   ```sh
   pip install -r requirements.txt
   ```

   ![image](https://github.com/user-attachments/assets/9cd7f386-010e-44dd-9d7d-e8e5dd9a2e4a)


## Usage
1. **Set your OpenAI API key:**
   Replace `'your_openai_api_key'` with your actual OpenAI API key in `app.py`.
   
   ![image](https://github.com/user-attachments/assets/b0234155-4c6f-45cb-8765-a742258de9a8)

   ```python
   openai.api_key = 'your_openai_api_key'
   ```

3. **Run the application:**
   ```sh
   python app.py
   ```
   ![image](https://github.com/user-attachments/assets/b0e5c27b-7eb6-4cae-a4b2-78e056419132)


4. **Access the application:**
   Open your web browser and go to `http://127.0.0.1:5000/`.




## Dependencies
- Flask: A micro web framework for Python.
- OpenAI: OpenAI's API for accessing GPT-3.

