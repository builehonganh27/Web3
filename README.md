# 🌐 Nền tảng Giao Dịch Blockchain với Web3 và Tích Hợp AI

## 🚀 Giới thiệu dự án
Dự án này là một nền tảng giao dịch phi tập trung (DApp), sử dụng **công nghệ blockchain** để lưu trữ tài sản và thực hiện giao dịch một cách minh bạch và an toàn.  
Người dùng có thể:  
- Lưu trữ tài sản số (NFT, token).  
- Giao dịch sản phẩm với người dùng khác.  
- Kiểm tra quyền sở hữu và lịch sử giao dịch ngay trên blockchain.
- Được hỗ trợ xác minh tính minh bạch, công khai của các tài khoản và tài sản giao dịch bởi tính năng được tích hợp AI.

Nền tảng kết hợp **Web3** để xây dựng giao diện phi tập trung và **AI** để phân tích dữ liệu giao dịch.  

---

## 📊 Phân tích thị trường
### Xu hướng Web3 hiện nay
- Quy mô thị trường Web3 dự kiến đạt **80 tỷ USD vào năm 2030**.  
- Công nghệ blockchain, DeFi, và NFT đang thúc đẩy sự phát triển mạnh mẽ.
- Phi tập trung (Decentralization): Web3 được xây dựng trên blockchain, cho phép loại bỏ các trung gian và tăng cường quyền kiểm soát cho người dùng cá nhân từ đó cũng làm tăng đáng kể tính riêng tư bảo mật cho cá nhân.

### Lợi thế cạnh tranh
- **Các nền tảng tương tự**: OpenSea, Rarible, Magic Eden.  
- **Điểm khác biệt của dự án**:
  - Tích hợp AI để phân tích giao dịch và định giá tài sản.
  - Giao diện đơn giản, dễ sử dụng, nhưng đảm bảo tính bảo mật cao.  

---

## 🛠️ Kiến trúc kỹ thuật

### 1. **Frontend (Giao diện người dùng)**
- Công nghệ: **Next.js**.  
- Tính năng chính:
  - Kết nối ví crypto như **MetaMask**.  
  - Giao diện thân thiện và tối ưu hóa cho trải nghiệm người dùng.  

### 2. **Backend (Xử lý dữ liệu)**
- Công nghệ: Java Spring Boot.  
- Tính năng chính:
  - API Gateway kết nối blockchain và giao diện người dùng.  
  - Lưu trữ dữ liệu phi tập trung trên **IPFS**.  

### 3. **Blockchain Layer**
- Hỗ trợ các blockchain: **Ethereum**, **Polygon**.  
- **Smart Contract (Hợp đồng thông minh)**:
  - **Mint NFT**: Tạo tài sản số.  
  - **Transfer**: Giao dịch tài sản giữa các người dùng.  
  - **Check Ownership**: Kiểm tra quyền sở hữu thông qua lịch sử giao dịch.  

### 4. **Bảo mật**
- Xác thực thông qua ví crypto (MetaMask).  
- Mã hóa dữ liệu giao dịch, đảm bảo tính riêng tư và toàn vẹn dữ liệu.  
- Kiểm tra tính toàn vẹn dữ liệu với **Merkle Tree**.  

---

## 🔄 Quy trình hoạt động
1. **Kết nối ví crypto**: Người dùng kết nối ví như MetaMask để đăng nhập.  
2. **Quản lý tài sản**:  
   - Mint NFT để lưu trữ tài sản.  
   - Metadata được lưu trên blockchain/IPFS.  
3. **Thực hiện giao dịch**:  
   - Người dùng giao dịch tài sản với nhau, thanh toán bằng token (ETH, MATIC, ...).  
4. **Kiểm tra lịch sử giao dịch**:  
   - Lịch sử giao dịch minh bạch và có thể kiểm tra trực tiếp trên blockchain.  

---

## 🤖 Tích hợp AI
Ngày nay với sự phát triển mạnh mẽ của công nghệ blockchain và web3, các lịch sử giao dịch, mua bán được công khai minh bạch tăng tính an toàn cho người dùng. 
Nhưng với số lượng lịch sử dày đặc như vậy người dùng không thể nào xem hết bằng sức người. 
Từ đó nhóm cho ra ý tưởng sử dụng các mô hình Deeplearning, Machine learning hiện có ngày nay để hổ trợ, đưa ra lời khuyên cho người dùng trước khi thực hiện một giao dịch gì đó.

Mô hình AI dựa vào các lịch sử của một tài khoảng đang muốn thực hiện giao dịch để đánh giá các tiêu chí:
- Tính an toàn của tài khoản.
- Tính an toàn của món hàng.
- Tính tài chính của một giao dịch ( sử lý kế toán )

Với hi vọng sẽ giúp hạn chế được các tai nạn lừa đảo phức tạp và hỗ trợ tính tài chính.

- Với tính an toàn của tài khoản:
  - Các công nghệ sẽ được áp dụng để khai thác các dữ liệu trên các nền tảng dựa trên tài khoản người dùng đã đăng ký.
  - Từ đó sử dụng AI để đánh giá dựa trên các data đó (VD: số lần đã thực hiện giao dịch thành công, có xuất hiện giao dịch bất thường không, các thông tin share trên mạng xã hội có đang quảng cáo cho một đồng coin hoặc món đồ gì không, ... )
- Với tính an toàn của món hàng:
  - Công nghệ lịch sử của block chain sẽ được truy suất dựa trên mã của món hàng đó và kiểm tra dựa trên các hành vi ( lịch sử ) của món hàng đó.
- Với tính tài chính:
  - Hỗ trợ đưa ra lời khuyên tài chính ( ý tưởng vì đây là một lĩnh vực khó, hiện nay đã có rất nhiều mô hình nhưng chưa một mô hình nào cho thấy khả năng vượt trội ). Nhưng ở mức độ lời khuyên gợi ý thì vài mô hình đã cho thấy khả năng phân tích số liệu vượt trội.
  - 
---

## 🛤️ Lộ trình phát triển
### Giai đoạn 1: Cơ bản
- Xây dựng giao diện DApp và tích hợp ví crypto.  
- Phát triển smart contract cơ bản.  

### Giai đoạn 2: Nâng cao
- Tích hợp AI để phân tích giao dịch và định giá tài sản.  
- Cải thiện bảo mật và trải nghiệm người dùng.  

### Giai đoạn 3: Mở rộng
- Hỗ trợ đa blockchain (Ethereum, Binance Smart Chain).  
- Xây dựng DAO để quản lý cộng đồng người dùng.  

---

## 💡 Điểm nổi bật
- **Minh bạch**: Tất cả giao dịch được ghi lại và kiểm tra trên blockchain.  
- **An toàn**: Dữ liệu được lưu trữ phi tập trung và mã hóa bảo mật.  
- **Thông minh**: AI hỗ trợ người dùng với các phân tích và đề xuất chuyên sâu.  

---

## 📜 Bản quyền
Dự án được cấp phép theo [MIT License](LICENSE).  

---

## 🤝 Đội ngũ phát triển
- **Phát triển Web3**: [Lê Hoàng Việt, Trần Minh Khang/Maverick Web3].  
- **Tích hợp AI**: [Nguyễn Tất Đạt, Nguyễn Minh Đạt/Maverick AI].  
- **BA**: [Bùi Lê Hồng Ánh].
