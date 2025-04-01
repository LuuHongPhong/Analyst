# Analyst
Amazone sale analyst

Tập Data: Amazon Products Sales Dataset 2023

Nguồn: https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset/data?select=Amazon-Products.csv

Mục tiêu phân tích: 
+ Tìm kiếm mối tương quan

Tương quan giữa rating và mặt hàng

Tương quan giữa rating và giá cả

+ Phân tích đưa ra các chiến lược kinh doanh phù hợp

# Executive summary
Amazone là một trong những trang thương mại điện tử lớn nhất thế giới. Bộ dữ liệu được thu thập thông qua scraped
dữ liệu từ trang Amazone, cung cấp lượng lớn thông tin về sản phẩm, đánh giá, giá của sản phẩm. Từ bộ dữ liệu chúng
ta có thể khai thác tìm hiểu xu hướng mua hàng của khách hàng

Hiểu được thế mạnh cạch tranh của từng ngành hàng, nhãn hàng và nhà cung cấp từ đó có thể hiểu rõ về
các yếu tố ảnh hưởng đến hành vi mua hàng của khách. Từ đó đưa ra các chiến lược bán hàng phù hợp cho từng ngành hàng

Số lượng đánh giá và tỷ lệ đánh giá có ảnh hưởng đến quyết định mua hàng của khách hàng nhưng không phải ngành hàng
nào 2 chỉ số này cũng ảnh hưởng, có một số ngành hàng giá cả sẽ là yếu tố quyết định. Bài phân tích này sẽ làm sáng
 tỏ các yếu tố ảnh hưởng đến quyết định mua hàng của khách hàng.

Tầm quan trọng của số lượng ratings: Mối tương quan mạnh mẽ giữa số lượng sản phẩm và tổng số ratings cho thấy rằng số lượng sản phẩm lớn hơn có xu hướng thu 
hút nhiều đánh giá hơn. Amazon có lợi thế ở đây do quy mô và độ phổ biến của nền tảng.
Chiết khấu không phải lúc nào cũng đảm bảo thành công: Tỷ lệ chiết khấu cao không phải lúc nào cũng dẫn đến đánh giá cao hơn. Điều này cho thấy rằng chất lượng sản phẩm và giá trị cảm nhận quan trọng hơn là chỉ giảm giá.
Phân khúc giá ảnh hưởng đến kỳ vọng: Khách hàng có những kỳ vọng khác nhau về các sản phẩm ở các phân khúc giá khác nhau. Các sản phẩm giá rẻ có thể thu hút nhiều người mua hơn bất chấp đánh giá thấp, 
trong khi các sản phẩm đắt tiền cần có chất lượng cao để đáp ứng kỳ vọng.
Danh mục "Health & Personal Care" là một điểm sáng: Danh mục này có xếp hạng trung bình cao nhất và tỷ lệ chiết khấu trung bình thấp nhất, cho thấy rằng khách hàng sẵn sàng trả giá cao cho các sản phẩm chất lượng trong lĩnh vực này.
"Quần áo nữ" và "Túi xách & hành lý" có tỷ lệ chiết khấu cao: Các danh mục này có thể là những lĩnh vực cạnh tranh cao, nơi chiết khấu được sử dụng để thu hút người mua. 
Tuy nhiên, điều quan trọng là phải đảm bảo rằng chất lượng sản phẩm không bị ảnh hưởng. Chiến lược giá linh hoạt là chìa khóa: Cần có một chiến lược giá linh hoạt, có tính đến phân khúc giá, chất lượng sản phẩm và kỳ vọng của khách hàng
