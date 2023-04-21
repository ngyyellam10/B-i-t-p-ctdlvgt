# Hàm tìm kiếm nhị phân
def binary_search(arr, left, right, x):
# Kiểm tra nếu phần tử x không nằm trong mảng
if right >= left:
mid = left + (right - left) // 2

# Nếu phần tử cần tìm nằm ở giữa mảng
if arr[mid] == x:
return mid

# Nếu phần tử cần tìm nhỏ hơn phần tử ở giữa mảng
elif arr[mid] > x:
return binary_search(arr, left, mid-1, x)

# Nếu phần tử cần tìm lớn hơn phần tử ở giữa mảng
else:
return binary_search(arr, mid+1, right, x)

else:
# Nếu không tìm thấy phần tử
return -1


# Mảng cho trước
arr = [2, 3, 4, 10, 40]
x = 10 # Giá trị cần tìm

# Kết quả tìm kiếm
result = binary_search(arr, 0, len(arr)-1, x)

if result != -1:
print("Phần tử cần tìm nằm ở vị trí", str(result))
else:
print("Không tìm thấy phần tử")
