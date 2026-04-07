(python3.11) D:\Vin\lab4_agent>python agent.py
C:\Users\LEGION\miniconda3\envs\python3.11\Lib\site-packages\transformers\utils\generic.py:441: UserWarning: torch.utils._pytree._register_pytree_node is deprecated. Please use torch.utils._pytree.register_pytree_node instead.
  _torch_pytree._register_pytree_node(
============================================================
TravelBuddy - Trợ lý Du lịch Thông minh
 Gõ 'quit' để thoát
============================================================

Bạn: Xin chào! Tôi đang muốn đi du lịch nhưng chưa biết đi đâu.

TravelBuddy đang suy nghĩ...
Trả lời trực tiếp

TravelBuddy: Chào bạn! Du lịch thật tuyệt vời, phải không? Bạn đang có ý định khám phá mùa nào, hay có sở thích đặc biệt nào như biển, núi, hay văn hóa? Cùng nhau tìm điểm đến hoàn hảo nhé!

Bạn: Tìm giúp tôi chuyến bay từ Hà Nội đi Đà Nẵng

TravelBuddy đang suy nghĩ...
Gọi tool: search_flights({'origin': 'Hà Nội', 'destination': 'Đà Nẵng'})
Trả lời trực tiếp

TravelBuddy: Tên chuyến bay từ Hà Nội đến Đà Nẵng có một số lựa chọn như sau:

1. **Vietnam Airlines (economy)**: 06:00 -> 07:20 | Giá: 1.450.000₫
2. **Vietnam Airlines (business)**: 14:00 -> 15:20 | Giá: 2.800.000₫
3. **VietJet Air (economy)**: 08:30 -> 09:50 | Giá: 890.000₫
4. **Bamboo Airways (economy)**: 11:00 -> 12:20 | Giá: 1.200.000₫

Bạn có ngân sách cho chuyến bay này là bao nhiêu và bạn đã có kế hoạch ở lại bao lâu chưa? Hãy cho mình biết để mình có thể hỗ trợ bạn tìm khách sạn phù hợp nhé!

Bạn: Tôi ở Hà Nội, muốn đi Phú Quốc 2 đêm, budget 5 triệu. Tư vấn giúp!

TravelBuddy đang suy nghĩ...
Gọi tool: search_flights({'origin': 'Hà Nội', 'destination': 'Phú Quốc'})
Gọi tool: search_hotels({'city': 'Phú Quốc'})
Gọi tool: calculate_budget({'total_budget': 5000000, 'expenses': 'vé_máy_bay: 1100000, khách_sạn: 0'})
Trả lời trực tiếp

TravelBuddy: Có một số lựa chọn thú vị cho chuyến đi từ Hà Nội đến Phú Quốc dành cho bạn!

### Chuyến bay:
1. **VietJet Air (economy)**:
   - **Giờ bay**: 10:00 -> 12:15
   - **Giá vé**: 1.350.000₫

2. **VietJet Air (economy)**:
   - **Giờ bay**: 16:00 -> 18:15
   - **Giá vé**: 1.100.000₫

### Khách sạn:
Dựa trên ngân sách và các đánh giá tốt, bạn có thể tham khảo các lựa chọn khách sạn sau:
1. **9Station Hostel (2 sao)**:
   - **Giá**: 500.000₫/đêm
   - **Khu vực**: Dương Đông
   - **Đánh giá**: 4.5/5

2. **Lahana Resort (3 sao)**:
   - **Giá**: 1.200.000₫/đêm
   - **Khu vực**: Dương Đông
   - **Đánh giá**: 4.0/5

### Tổng chi phí ước tính:
- Vé máy bay (VietJet Air): 1.350.000₫
- Khách sạn (9Station Hostel, 2 đêm): 1.000.000₫ (500.000₫ x 2)

#### **Tổng chi phí:** 2.350.000₫

### Ngân sách còn lại:
Với ngân sách 5 triệu, bạn còn lại 2.650.000₫, rất thoải mái cho các hoạt động vui chơi, ăn uống hay tham quan tại Phú Quốc.

### Gợi ý thêm:
Phú Quốc rất nổi tiếng với các địa điểm ăn uống hải sản tươi ngon như chợ đêm Dinh Cậu hay các bãi biển đẹp như Bãi Sao. Thời tiết Phú Quốc vào mùa này thường đẹp, nhưng bạn cũng nên mang theo kem chống nắng và đồ bơi để trải nghiệm trọn vẹn!

Nếu bạn cần thêm thông tin hoặc muốn đặt vé ngay, hãy cho mình biết nhé! 🌴✈️

Bạn: Tôi muốn đặt khách sạn

TravelBuddy đang suy nghĩ...
Trả lời trực tiếp

TravelBuddy: Mình rất vui khi được giúp bạn đặt khách sạn! Để mình có thể tư vấn chính xác nhất, bạn cho mình biết thông tin sau nhé:

1. Thành phố mà bạn muốn đặt khách sạn?
2. Ngân sách cho mỗi đêm là bao nhiêu?
3. Bạn dự định sẽ ở bao nhiêu đêm?

Chờ bạn nhé!

Bạn: Giải giúp tôi bài tập lập trình Python về linked list

TravelBuddy đang suy nghĩ...
Trả lời trực tiếp

TravelBuddy: Rất tiếc, mình là trợ lý chuyên về du lịch TravelBuddy nên không thể giúp bạn giải bài tập này. Nhưng nếu bạn cần lên kế hoạch đi chơi hoặc có câu hỏi nào liên quan đến du lịch, mình luôn sẵn sàng giúp đỡ!

Bạn: quit