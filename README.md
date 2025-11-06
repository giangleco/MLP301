
# Mô tả các bài Lab

Dưới đây là mô tả ngắn gọn về các bài lab trong thư mục này.

## Lab 11: Phân tích cảm xúc (Sentiment Analysis)

- **Tên file:** `Analyzing_product_sentiment.ipynb`
- **Dữ liệu:** `amazon_baby.csv`
- **Mô tả:** Lab này tập trung vào việc xây dựng một mô hình phân loại cảm xúc (tích cực/tiêu cực) từ các bài đánh giá sản phẩm dành cho trẻ em trên Amazon. Các kỹ thuật xử lý ngôn ngữ tự nhiên (NLP) được sử dụng để làm sạch và chuẩn bị dữ liệu văn bản trước khi huấn luyện mô hình.

## Lab 12: Truy xuất tài liệu (Document Retrieval)

- **Tên file:** `Document_retrieval.ipynb`
- **Dữ liệu:** `people_wiki.csv`
- **Mô tả:** Lab này hướng dẫn cách xây dựng một hệ thống truy xuất tài liệu. Sử dụng bộ dữ liệu các bài viết về người nổi tiếng từ Wikipedia, lab áp dụng kỹ thuật TF-IDF để biểu diễn văn bản và tính toán độ tương tự (cosine similarity) nhằm tìm ra các tài liệu liên quan nhất đến một truy vấn cho trước.

## Lab 13: Hệ thống gợi ý bài hát (Song Recommender)

- **Tên file:** `Song_recommender.ipynb`
- **Dữ liệu:** `song_data.csv`
- **Mô tả:** Trong lab này, chúng ta sẽ xây dựng hai loại hệ thống gợi ý bài hát:
    1.  **Dựa trên độ phổ biến (Popularity-based):** Gợi ý những bài hát được nghe nhiều nhất.
    2.  **Cá nhân hóa (Personalized):** Gợi ý các bài hát dựa trên lịch sử nghe của người dùng và sự tương đồng giữa các bài hát (item-based collaborative filtering).

## Lab 14: Deep Learning với hình ảnh

Lab này được chia thành hai phần, sử dụng các "deep feature" được trích xuất từ một mô hình học sâu đã được huấn luyện trước để thực hiện các tác vụ trên hình ảnh.

### Lab 14.1: Truy xuất hình ảnh (Image Retrieval)

- **Tên file:** `Deep_Features_for_Image_Retrieval.ipynb`
- **Mô tả:** Hướng dẫn cách xây dựng một hệ thống tìm kiếm hình ảnh tương tự. Bằng cách sử dụng deep features, chúng ta có thể tìm ra các hình ảnh gần nhất (tương tự nhất) với một hình ảnh đầu vào dựa trên khoảng cách cosine trong không gian đặc trưng.

### Lab 14.2: Phân loại hình ảnh (Image Classification)

- **Tên file:** `Deep_Features_for_Image_Classification.ipynb`
- **Mô tả:** Lab này chỉ ra cách sử dụng deep features làm đầu vào để huấn luyện một mô hình phân loại (ví dụ: Logistic Regression) đơn giản nhưng hiệu quả. Cách tiếp cận này (học chuyển giao - transfer learning) cho kết quả tốt hơn nhiều so với việc chỉ sử dụng các điểm ảnh thô.
