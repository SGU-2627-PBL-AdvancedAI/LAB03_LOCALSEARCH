# LAB03 - Local Search

## Mô tả

Đây là bài thực hành Lab03 môn Trí tuệ nhân tạo nâng cao, tập trung vào
việc tìm hiểu các phương pháp tìm kiếm cục bộ (local search) để giải quyết
các bài toán tối ưu. Nội dung thực hành bao gồm Hill Climbing trên bài toán
mê cung, Simulated Annealing, bài toán N-Queens và bài toán người bán hàng
(Traveling Salesman Problem - TSP).

## Tài liệu yêu cầu

File yêu cầu của bài tập: https://drive.google.com/file/d/1jqT2CuyScipntouIsheiSpieZ306Rp9V/view

## Cấu trúc thư mục

```
LAB3_LocalSearch/
├── src/
│   ├── Maze_Example_LocalSearch.ipynb
│   ├── Simulated_Annealing_Schedules.ipynb
│   ├── n_queens.ipynb
│   ├── n_queens_fast_conflict_calculation_with_numba.ipynb
│   ├── traveling_salesman_problem.ipynb
│   ├── maze_helper.py
│   ├── L_maze.txt
│   └── README.md
├── baocao.pdf
└── README.md
```

### Mô tả các thành phần

- `src/Maze_Example_LocalSearch.ipynb`: Minh họa áp dụng thuật toán
  Simple Hill Climbing để tìm đường trong bài toán mê cung.
- `src/Simulated_Annealing_Schedules.ipynb`: Khảo sát các lịch giảm nhiệt
  (annealing schedules) trong thuật toán Simulated Annealing.
- `src/n_queens.ipynb`: Bài tập giải bài toán N-Queens bằng phương pháp tìm
  kiếm cục bộ.
- `src/n_queens_fast_conflict_calculation_with_numba.ipynb`: Minh họa cách
  tăng tốc việc tính số xung đột trong bài toán N-Queens bằng Numba.
- `src/traveling_salesman_problem.ipynb`: Bài tập áp dụng tìm kiếm cục bộ
  cho bài toán người bán hàng.
- `src/maze_helper.py`: Các hàm hỗ trợ đọc, phân tích, hiển thị và tạo
  animation cho mê cung.
- `src/L_maze.txt`: Dữ liệu mê cung kích thước lớn được sử dụng trong các
  ví dụ và bài tập.
- `src/README.md`: Tài liệu giới thiệu các ví dụ và bài tập trong thư mục
  `src`.
- `baocao.pdf`: File báo cáo của bài thực hành.
- `README.md`: Tài liệu giới thiệu và hướng dẫn tổng quan cho repository.

