| **Tiêu chí**                   | **Comparable**                                                                                   | **Comparator**                                                                                            |
|--------------------------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| **Gói (Package)**              | `java.lang`                                                                                     | `java.util`                                                                                               |
| **Phương thức**                | `compareTo(Object o)`                                                                           | `compare(Object o1, Object o2)`                                                                            |
| **Cách sử dụng**               | Được sử dụng khi cần sắp xếp đối tượng theo một trật tự tự nhiên duy nhất.                       | Được sử dụng khi cần sắp xếp đối tượng theo nhiều trật tự khác nhau hoặc khi trật tự tự nhiên không phù hợp.|
| **Cách cài đặt**               | Lớp đối tượng cần sắp xếp phải cài đặt giao diện `Comparable`.                                  | Một lớp riêng biệt hoặc lớp ẩn danh cài đặt giao diện `Comparator`.                                         |
| **Thay đổi lớp gốc**           | Yêu cầu thay đổi lớp gốc để cài đặt `Comparable`.                                               | Không yêu cầu thay đổi lớp gốc.                                                                            |
| **Ảnh hưởng đến lớp gốc**      | Làm thay đổi cấu trúc của lớp gốc do phải cài đặt phương thức `compareTo()`.                    | Không làm thay đổi cấu trúc của lớp gốc.                                                                   |
| **Số lượng phương thức so sánh**| Chỉ có thể cài đặt một phương thức so sánh duy nhất.                                             | Có thể cài đặt nhiều phương thức so sánh khác nhau.                                                        |
| **Khả năng sử dụng**           | Sử dụng khi lớp cần sắp xếp có một cách sắp xếp tự nhiên duy nhất (vd: `String`, `Integer`).    | Sử dụng khi có nhiều cách sắp xếp khác nhau hoặc khi cần một cách sắp xếp cụ thể khác với cách sắp xếp tự nhiên.|


![image](https://github.com/nang2002hv/Ontap/assets/101803106/3b7982c7-c105-4465-acfa-4f34585df1ea)
