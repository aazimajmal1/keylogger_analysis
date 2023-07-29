Keylogger Analysis
Project Structure:
1. Project: This folder has the main `keylogger.py` file.
2. Cryptography: This folder has the `generate_key.py` to encrypt the log files and `decrypt_file.py` & `decrypt_log_file.py` to decrypt the log files.
3. Model: Some machine learning algorithms like ANN, Random Forest, and SVM were used to train the header files of the keylogger to analyse the headers of malicious and benign files.

To convert the keylogger.py to .exe file, use the python package [auto-py-to-exe](https://pypi.org/project/auto-py-to-exe/)

To get the header files of a .exe files use tools like Qu1ckSc0pe or pefile
