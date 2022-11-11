# **A Simple Guide to the Versions of the Inception Network**
   + The Inception network was an important milestone in the development of CNN classifiers
   + Mặt khác, mạng Inception rất phức tạp (được thiết kế kỹ lưỡng)
   + Nó đã sử dụng rất nhiều thủ thuật để đẩy hiệu suất; cả về tốc độ và độ chính xác
   + Sự phát triển liên tục của nó dẫn đến việc tạo ra một số phiên bản của mạng.

## **Inception v1**
    ![Architure IV1]()
   + **Problems:** 
     + Các phần nổi bật trong hình ảnh có thể có sự thay đổi kích thước cực kỳ lớn
     + Ví dụ, một hình ảnh với một con chó có thể là một trong hai hình sau, như được hiển thị bên dưới.
     + Do sự khác biệt lớn về vị trí của thông tin, việc chọn kích thước kernel phù hợp cho hoạt động tích chập trở nên khó khăn
     + A larger kernel is preferred for information that is distributed more globally, and a smaller kernel is preferred for information that is distributed more locally.
     + Very deep networks are prone to **overfitting**
     + Việc xếp chồng các phép toán tích chập lớn một cách ngây thơ là tốn kém về mặt tính toán.
   + **Solutions:**
     + Tại sao không có các bộ lọc với nhiều kích thước hoạt động trên cùng một cấp? Về cơ bản, mạng sẽ trở nên "rộng hơn" một chút thay vì "sâu hơn".
     + Ý tưởng phát triển mạng thần kinh theo chiều rộng chứ không phải chiều sâu 
     + ![Inception V1]()
     + Để làm cho tính toán trên mạng nơ ron sâu rẻ hơn các tác giả giới hạn số lượng kênh đầu vào bằng cách thêm một tích chập 1x1 trước các chập 3x3 và 5x5
   + The total loss used by the inception net during training.
     + total_loss = real_loss + 0.3 * aux_loss_1 + 0.3 * aux_loss_2
   + 

