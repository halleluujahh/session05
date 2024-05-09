/* trước khi css thì phải reset css
* ăn hết tất cả trang */
# Độ ưu tiên:
- Từ bé đến lớn 
element --> class --> id --> !important
# Layout:
- thiết kế, bố cục các element theo ý muốn.
1. float.
2. position.
3. flex: định dạng 1 chiều.
4. grid: định dạng 2 chiều.
5. rwd - responsive web designer.
* position: định vị
1. trạng thái mặc định: static.
2. relative: vị trí tương đối.
3. absolute: vị trí tuyệt đối.
4. fixed.
5. sticky.
- relative: khi 1 element khối có thuộc tính position= relative thì nó sẽ lấy vị trí ban đầu làm gốc, khi muốn căn chỉnh khối theo các chiều thì dùng + top (trên).
+ right (phải).
+ left (trái).
+ bottom (dưới).
- absolute: ăn theo vị trí cha chứa nó gần nhất có thuộc tính là position (khác static). Nếu không có thằng cha nào thì sẽ ăn theo kích thước màn hình.
- fixed: cố định element khi lăn chuột.
# Flex 
- Dùng để định dạng layout.
- Khi 1 element có thuộc tính display flex thì sẽ dùng các thuộc tính của flex.
- Cha gọi là flex container, con gọi là flex item.
- Khi cha có thuộc tính display flex thì con nằm trên 1 hàng.
- flex-direction: dùng để điều chỉnh trục của element.
- flex-direction: row thì trục main-axis sẽ nằm ngang, cross-axis sẽ nằm dọc
- flex-direction: column thì main-axis sẽ nằm dọc, cross-axis sẽ nằm ngang
- main-axis ăn theo thuộc tính justify-content.
- cross-axis ăn theo thuộc tính align-item.
- justify-content:
+ center: ra giữa.
+ space-around: khoảng cách từ mép đến element đầu tiên sẽ cách nhau bằng 1/2 khoảng cách từ element đầu đến element 2.
+ space-evenly: khoảng cách từ các element cách đều nhau.
+ space-beetween: hai element đầu và cuối nằm hai mép và khoảng cách các phần tử cách đều nhau.
- order: sắp xếp vị trí của layout của element.
- flex: nếu là 1 số nguyên dương thì sẽ chiếm hết các element còn lại.
- flex-wrap: wrap.

# Mind map: https://whimsical.com/fl-DkAx54LY2ouoYDJmZtsVbG