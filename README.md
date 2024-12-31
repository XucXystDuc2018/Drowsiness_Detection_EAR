# Drowsiness_Detection_EAR
Cài đặt cmake trong hệ thống: https://cmake.org/download/

Chạy app:
Bước 1. clone repo

```
git clone https://github.com/AnshumanSrivastava108/Real-Time-Drowsiness-Detection-System
```

Bước 2. Tạo môi trường ảo
Tải và cài đặt virtualenv.

```
pip install virtualenv
```

Tạo môi trường ảo trong Python 3.

```
 virtualenv -p C:\Python37\python.exe test_env
```

Kích hoạt môi trường ảo.
Đối với Windows:

```
test_env\Scripts\Activate
```

Đối với Unix:

```
source test_env/bin/activate
```

Bước 3. Cài đặt các thư viện cần thiết và cmake

```
pip install -r requirements.txt
pip install cmake
```

Bước 4. Cài đặt thư viện dlib
```
pip install dlib-19.24.1-cp311-cp311-win_amd64.whl
```

Bước 5. Chạy app

```
python Drowsiness_Detection.py
```
