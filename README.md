pip install pyinstaller
pyinstaller --onefile --noconsole --distpath ./dist --specpath ./build --noconfirm --upx-dir UPX --clean --name CatchMe main.py
