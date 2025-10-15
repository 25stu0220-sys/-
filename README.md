<img width="647" height="451" alt="image" src="https://github.com/user-attachments/assets/0c0f3722-bc23-44f6-b249-ca9ac36e5735" />
<img width="922" height="945" alt="image" src="https://github.com/user-attachments/assets/05909bfb-682b-41c1-93da-72bf5ad08b96" />
# 사용자로부터 숫자를 입력받음
num = int(input("몇 단을 출력할까요? "))

# 구구단 출력
print(f"{num}단 출력:")
for i in range(1, 10):
    print(f"{num} x {i} = {num * i}")

