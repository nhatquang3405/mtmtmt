def calculate_sum(N):
    S = sum(i * 11 for i in range(1, N + 1))
    return S

if __name__ == "__main__":
    N = int(input("Nhập N: "))
    result = calculate_sum(N)
    print(f"Tổng S = {result}")
