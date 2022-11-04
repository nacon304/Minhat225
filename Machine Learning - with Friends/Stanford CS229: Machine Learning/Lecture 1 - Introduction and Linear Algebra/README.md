

#  Stanford CS229: Machine Learning | Summer 2019 | Lecture 1 - Introduction and Linear Algebra

  

**Link:** [Introduction and Linear Algebra](https://www.youtube.com/watch?v=KzH1ovd4Ots&list=PLoROMvodv4rNH7qL6-efu_q2_bPuy0adh&index=2&t=5s)

##  Phần 1: Giới thiệu Machine Learning
Cần tư duy rằng: Machine Learning = Khoa học máy tính + Toán xác suất thống kê.

### 1. Khái niệm:
- Học máy là nghiên cứu các *thuật toán* giúp cho máy tính có khả năng tự cải thiện kết quả thông qua *kinh nghiệm*. Trong đó:
	- Kinh nghiệm hãy hiểu là bộ dữ liệu đã có được sau một lần "học"; còn có tên gọi khác là *training data*.
	- Thuật toán sẽ phân tích bộ dữ liệu (training data) và đưa ra một cách thức học mới.

### 2. Mối quan hệ:
- Là tập hợp con của *AI*, hiểu:
	- AI là nghiên cứu chuyên sâu để giúp cho máy có thể đạt được như con người.
	- Điểm khác biệt có thể thấy: AI đôi khi không cần có một bộ dữ liệu cụ thể.  
- Là tập hợp cha của *Deep Learning*, hiểu:
	- Deep Learning dựa trên mạng thần kinh.
	- Thực chất, trước khi Deep Learning chưa được xây dựng thì Machine Learning chỉ gồm những thuật toán tương đối đơn giản. Nên có thể xem Deep Learning là thuật toán có hiệu quả và tính ứng dụng tốt nhất trong Machine Learning.

### 3. Ứng dụng:
- Nhận diện hình ảnh.
- Xe tự lái.
- Apple Siri, Google Assistant.
- Dịch ngôn ngữ.
- Trò chơi (cờ vua - Alphago).



## Phần 2: Phân loại về Machine Learning
### 1. Supervised Learning:
#### a. Khái niệm:
- Dự đoán đầu ra của bộ dữ liệu đã được *gán nhãn* thông qua một *mô hình hàm số*. Trong đó:
	- Gán nhãn nghĩa là đã biết output của dữ liệu.
	- Việc xây dựng hàm số sẽ thông qua bộ dữ liệu đã biết trước đó.

#### b. Bài toán:
- Hồi quy tuyến tính (Linear Regression), bài toán trả ra những con số thực - kết quả của dự báo.
- Phân loại (classification), bài toán trả ra Đúng hoặc Sai - phân chia dữ liệu thành 2 vùng.

### 2. Unsupervised Learning:
#### a. Khái niệm:
- Dự đoán đầu ra của bộ dữ liệu không được *gán nhãn* thông qua việc cố gắng tìm ý nghĩa, cấu trúc của bộ dữ liệu đầu vào để trả ra kết quả. Trong đó:
	- Việc trả ra kết quả có thể dựa vào các quy tắc, xác suất,...

#### b. Bài toán:
- Phân nhóm (clusters), gom nhóm những đối tượng có cùng "tính chất".
- Kết hợp (subspaces), tìm hiểu những đối tượng có thể liên quan đến đối tượng đang xét.

### 3. Semi-Supervised Learning:
Chưa đề cập...

### 4. Reinforcement Learning
#### a. Khái niệm:
- Cần đưa ra *hành động (action)* phải thực hiện để mang lại *kết quả (reward)* tốt nhất trong *tình huống thực tế*. Trong đó:
	- Hành động được chọn trong những hành động có thể thực hiện tại thời điểm đó - được xem là input.
	- Kết quả là số điểm mà nhận được nếu thực hiện hành động đang xét, công việc cần làm là tối ưu số điểm - được xem là phương diện đang xét tới.
	- Tình huống thực tế hiểu là nếu thực hiện hành động đó thì có kết quả thế nào - được xem là output.

#### b. Ví dụ:
- Dưới đây là trò chơi "Đua thuyền", và ta sẽ xem kết quả nếu áp dụng thuật toán với:
	- Ưu tiên thời gian hoàn thành: <br> <iframe width="730" height="411" src="https://www.youtube.com/embed/8ZfPefdt5UU" title="Coast Runners - Game preview / gameplay" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	- Ưu tiên số điểm: <br> <iframe width="730" height="411" src="https://www.youtube.com/embed/tlOIHko8ySg" title="CoastRunners 7" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Phần 3: Deep Learning
Chưa hiểu lắm...

## Phần 4: Learning Theory
Chưa đề cập...

## Khác:
1. [Thuật toán học máy cơ bản trong Machine Learning](https://viblo.asia/p/cac-thuat-toan-trong-hoc-may-machine-learning-GrLZD8w3Zk0)
2. [Khái niệm Deep-Learning](https://nordiccoder.com/blog/deep-learning-la-gi/)
3. [Khái niệm Supervised-Learning](https://nordiccoder.com/blog/supervised-learning-la-gi/)
4. [Khái niệm Unsupervised-Learning](https://nordiccoder.com/blog/unsupervised-learning-la-gi/)
5. [Khái niệm Reinforcement Learning](https://viblo.asia/p/gioi-thieu-ve-reinforcement-learning-rl-djeZ1GEY5Wz)
