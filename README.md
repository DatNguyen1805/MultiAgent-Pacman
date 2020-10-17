# MultiAgent-Pacman
# 18020287 - Nguyễn Tiến Đạt

Câu 1: Reflex Agent

![cau1](https://user-images.githubusercontent.com/71663050/96190089-d5558100-0f6b-11eb-8977-1810cf2bddf2.PNG)

- Sử dụng khoảng cách manhattan tính khoảng cách nhỏ nhất từ pacman đến các viên thức ăn trên bản đồ để pacman có thể ăn được các viên thức ăn gần nhất đồng thời luôn giữ cho khoảng cách của pacman và ma lớn hơn 2

Câu 2: Minimax

![Cau2](https://user-images.githubusercontent.com/71663050/96190387-5f054e80-0f6c-11eb-93ce-de7be78426a3.PNG)

- Cài đặt lại thuật toán minimax theo như thuật toán đã được hướng dẫn trong slide

Câu 3: Alpha-Beta Pruning

![Cau3_1](https://user-images.githubusercontent.com/71663050/96190699-d9ce6980-0f6c-11eb-8099-3886a7a32b50.PNG)
![Câu3_2](https://user-images.githubusercontent.com/71663050/96190725-e357d180-0f6c-11eb-9595-de225087f0b9.PNG)

- Cài đặt dựa trên cơ sở của minimax nhưng có thêm điều kiện cắt nhánh để loại bỏ bớt số lần lặp với alpha và beta

Câu 4: Expectimax

![Cau4](https://user-images.githubusercontent.com/71663050/96190903-316cd500-0f6d-11eb-998f-8074e96ecc54.PNG)

- Cài đặt cơ bản giống với minimax nhưng thêm yếu tố xác suất để đưa ra quyết định tối ưu

# Quá trình chạy autograder:

![Cau1](https://user-images.githubusercontent.com/71663050/96330478-bba55e00-107f-11eb-83fe-f39432daf2cd.PNG) ![Cau2](https://user-images.githubusercontent.com/71663050/96330486-c3650280-107f-11eb-9b39-d92c12ac664f.PNG) ![Cau3](https://user-images.githubusercontent.com/71663050/96330498-d5df3c00-107f-11eb-9f99-c35a829154ce.PNG) ![Cau4](https://user-images.githubusercontent.com/71663050/96330502-dc6db380-107f-11eb-934a-7b1f2fe63eca.PNG) ![Auto](https://user-images.githubusercontent.com/71663050/96330510-e98aa280-107f-11eb-8899-dec21dba1cb7.PNG)
