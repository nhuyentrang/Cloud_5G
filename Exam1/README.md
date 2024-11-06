Bài 1: triển khai deployment chạy nginx (default) lên kubernetes và cho phép truy cập từ bên ngoài thông qua nodePort.
Output:
1 deployment nginx (replicas=2 pod)
1 nodePort service trỏ tới deployment
thực hiện curl tới nodePort và cho ra kết quả trang web mặc định của nginx.
