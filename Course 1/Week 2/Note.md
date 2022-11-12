# Objective
 + Describe when you need to build a custom loss function
 + Implement Huber Loss with a custom loss function
 + Add an adjustable hyper parameter to custom loss using a wrapper function
 + Define a custom loss using an object oriented class
 + Implement contrastive loss function used in a Siamese network

 # Contrastive learning
   + Ý tưởng chính của Contrastive learning là tìm ra các cặp đặc trưng của dữ liệu có tính tương đồng - tương phản nhau trong bộ dataset (Siamese network)
   + Mục tiêu của phương pháp là đối chiếu sự tương phản giữa embedding của các phiên bản biến đổi của cùng một sample để học các đặc trưng bất biến của nó trong khi vẫn phân biệt được embedding của các sample khác.
   + 