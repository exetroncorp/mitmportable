pip install pyinstaller

pyinstaller --onefile --collect-all mitmproxy run_web.py
pyinstaller --onefile --collect-all mitmproxy run_dump.py
pyinstaller --onefile --collect-all mitmproxy run_mitm.py
