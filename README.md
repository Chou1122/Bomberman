# Bomberman
***
Thuyết trình về game: https://youtu.be/ms7E7oaMcDQ
## Mô tả
Game Bomberman viết bằng ngôn ngữ Java
***
## Thông tin nhóm
- **Nhóm 99**
- **Thành viên:**
  - Phạm Hồng Minh
  - Trịnh Huy Hoàng
## Hướng dẫn chơi
- Sử dụng `các phím điều hướng` hoặc `A`, `W`, `S`, `D` để di chuyển bomber, `SPACE` để đặt bom, `ESC` hoặc `P` để pause, `ENTER` để chọn
- Tiêu diệt tất cả quái và đi vào cổng để qua màn mới
- Bomber mất một mạng khi dính bom hoặc va chạm với quái
- Khi Bomber mất hết mạng trò chơi sẽ kết thúc
## Các chức năng
- Game gồm 8 màn chơi với độ khó tăng dần, mỗi màn sẽ xuất hiện một loại quái mới và sẽ có 1 item
  - Enemy
    - ![](/src/resouces/sprites/balloom_left1.png) `Balloom`: Di chuyển ngẫu nhiên theo các hướng
    - ![](/src/resouces/sprites/oneal_left1.png) `Oneal`: Di chuyển ngẫu nhiên khi không có đường đi đến player, tốc độ ngẫu nhiên
    - ![](/src/resouces/sprites/kondoria_left1.png) `Kondoria`: Di chuyển ngẫu nhiên rất chậm đi xuyên qua các bức tường, đuổi theo player khi đến gần
    - ![](/src/resouces/sprites/pontan1.png) ![](/src/resouces/sprites/pontan2.png) `Pontan`: Giống với Oneal nhưng tốc độ nhanh
    - ![](/src/resouces/sprites/minvo_left1.png) `Minvo`: Di chuyển ngẫu nhiên hoặc đuổi theo player, tốc độ nhanh, đi xuyên tường
    - ![](/src/resouces/sprites/toxic_left1.png) `Toxic`: Phát nổ xung quanh khi chết
    - ![](/src/resouces/sprites/doll_left1.png) `Doll`: Di chuyển lên xuống, đổi hướng khi có vật cản
    - ![](/src/resouces/sprites/brick_left1.png) `Brick`: Giả làm bức tường, đuổi theo player khi đến gần
  - Item
    - ![](/src/resouces/sprites/powerup_bombs.png) `Bomb Item`: Thêm 1 bomb tối đa
    - ![](/src/resouces/sprites/powerup_flames.png) `Flame Item`: Thêm 1 lửa tối đa
    - ![](/src/resouces/sprites/powerup_speed.png) `Speed Item`: Thêm 1 tốc chạy
- Game có thể lưu lại màn chơi khi tắt
- Chúc năng Ranking lưu lại tên của 5 người chơi có điểm cao nhất
- Link Repo quá trình làm game hồi còn học: https://github.com/21020325-trinhhuyhoang/Bomberman


