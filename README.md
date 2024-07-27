### Keyword
- Reliability: độ tin cậy
- Model layer OSI && TCP/IP:
![img](./modellayer.png)

# Basic concept
- IPV4: 32 bits = 4 bytes
- IPV6: 128 bits = 16 bytes
- Default Gateway: là một thiết bị mạng, thường là một router hoặc switch, mà máy tính hoặc thiết bị sử dụng để gửi dữ liệu đến các mạng khác ngoài mạng cục bộ của nó. Đây là điểm cuối cùng trong mạng nội bộ trước khi dữ liệu được chuyển ra ngoài.
- spyware: thu nhập thông tin người dùng
- Extranet: mạng ngoài truy cập vào mạng nội bộ của công ty
- Intranet: truy cập trong mạng nội bộ
- ISP: là nhà cung cấp dịch vụ Internet. Đây là một công ty hoặc tổ chức cung cấp các dịch vụ truy cập, sử dụng hoặc tham gia vào Internet.
- WISP (Wireless Internet Service Provider) là nhà cung cấp dịch vụ Internet không dây. 
- DHCP: automatic assignment of an IP address to each host
- 3 standards organizations: IANA, IETF, IEE
- flow control: quá trình quản lý tốc độ truyền dữ liệu giữa hai thiết bị để tránh tình trạng mất dữ liệu hoặc tràn dữ liệu.
- access control: quá trình giới hạn quyền truy cập vào tài nguyên mạng để bảo vệ dữ liệu và đảm bảo an toàn.
- encapsulation: quá trình thêm các tiêu đề (header) và đuôi (trailer) vào dữ liệu để chuẩn bị nó cho việc truyền đi trong mạng
- Response timeout: Quản lý thời gian thiết bị chờ khi không nghe thấy phản hồi từ đích.
- end device: is where a message originates from or where it is received. Data originates with an end device, flows through the network, and arrives at an end device.



# CISCO
- Để lưu tệp cấu hình đang chạy vào tệp cấu hình khởi động ```write memory``` or ```copy running-config startup-config``` 
- ```copy startup-config running-config``` sao chép cấu hình khởi động từ NVRAM vào cấu hình đang chạy RAM.
- ```write erase``` or ```erase startup-config``` ==> xóa cấu hình
- Default SVI on a Cisco switch ==> VLAN1
- 





# Question hay hỏi
- the purpose of message encoding --> to convert information to the appropriate form for transmission
- two benefits of using a layered network model:
    * It prevents technology in one layer from affecting other layers
    * It assists in protocol design
- Purpose of protocols in data communications --> providing the rules required for a specific type of communication to occur
- a general term that is used to describe a piece of data at any layer of a networking model --> PDU (protocol data unit)


# Layer
- Which layer of the OSI model defines services to segment and reassemble data for individual communications between end devices --> Transport

# Protocol
- BOOTP, POP -> Application layer
- PPP -> Datalink layer
- flow control: quá trình quản lý tốc độ truyền dữ liệu giữa hai thiết bị để tránh tình trạng mất dữ liệu hoặc tràn dữ liệu.


## Chapter 1 Network Today
New Terms and Commands
 • Peer-to-Peer File Sharing
 • Small Office/Home Office or SOHO
 • Medium to large network
 • Server
 • Client
 • Peer-to-Peer network
 • End device
 • Intermediary device
 • Medium
 • Network Interface Card (NIC)
 • Physical Port
 • Interface
 • Physical topology diagram
 • Logical topology diagram
 • Local Area Network (LAN)
 • Wide Area Network (WAN)
 • Internet
 • Intranet
 • Extranet
 • Internet Service Provider (ISP)
 • Converged networks
 • Network architecture
 • Fault-tolerant network
 • Packet-switched network
 • Circuit-switched network
 • Scalable network
 • Quality of Service (QoS)
 • Network bandwidth
 • Bring Your Own Device (BYOD)
 • Collaboration 
• Cloud computing
 • Private clouds
 • Hybrid clouds
 • Public clouds
 • Custom clouds
 • Data center
 • Smart home technology
 • Powerline networking
 • Wireless Internet Service 
Provider (WISP)
 • Network architecture
  What did I learn in this module?
 • Through the use of networks, we are connected like never before.
 • All computers that are connected to a network and participate directly in network 
communication are classified as hosts.
 • Diagrams of networks often use symbols to represent the different devices and 
connections that make up a network. 
• A diagram provides an easy way to understand how devices connect in a large network.
 • The two types of network infrastructures are Local Area Networks (LANs), and Wide Area 
Networks (WANs).
 • SOHO internet connections include cable, DSL, Cellular, Satellite, and Dial-up telephone. 
• Business internet connections include Dedicated Leased Line, Metro Ethernet, Business 
DSL, and Satellite.
 71
 © 2019, 2021  Cisco and/or its affiliates. All rights reserved.   Cisco Confidential
Module Practice and Quiz
 What did I learn in this module? (Cont.)
 • Network architecture refers to the technologies that support the infrastructure and the 
programmed services and rules, or protocols, that move data across the network.
 • There are four basic characteristics of network architecture: Fault Tolerance, Scalability, 
Quality of Service (QoS), and Security.
 • Recent networking trends that affect organizations and consumers: Bring Your Own Device 
(BYOD), online collaboration, video communications, and cloud computing.
 • There are several common external and internal threats to networks.
 • Larger networks and corporate networks use antivirus, antispyware, and firewall filtering, but 
they also have other security requirements: Dedicated firewall systems, Access control lists 
(ACL), Intrusion prevention systems (IPS), and Virtual private networks (VPN)
 • The Cisco Certified Network Associate (CCNA) certification demonstrates your knowledge of 
foundational technologies
1. Network Type
- cable
    * Đặc điểm: Băng thông cao, luôn kết nối.
    * Mô tả: Cung cấp Internet bởi các nhà cung cấp dịch vụ truyền hình cáp.
- DSL (Digital Subscriber Line)
    * Đặc điểm: Băng thông cao, luôn kết nối.
    * Mô tả: Kết nối Internet chạy qua đường điện thoại.
- Cellular
    * Đặc điểm: Sử dụng mạng di động để kết nối Internet.
    * Mô tả: Cung cấp kết nối Internet thông qua mạng điện thoại di động.
- Satellite( Vệ tinh)
    * Đặc điểm: Lợi ích chính cho các khu vực nông thôn không có nhà cung cấp dịch vụ Internet.
    * Mô tả: Cung cấp kết nối Internet thông qua vệ tinh, hữu ích cho các khu vực mà các loại kết nối khác không khả dụng.
- Dial-up telephone
    * Đặc điểm: Lựa chọn rẻ tiền với băng thông thấp, sử dụng modem.
    * Mô tả: Kết nối Internet qua đường dây điện thoại bằng cách sử dụng modem, tốc độ thấp và yêu cầu quay số để kết nối.
2. Arch
- 4 đặc điểm cần giải quyết để đáp ứng mong đợi của người dùng
    * Fault Tolerance
    * Scalability
    * Quality of Service (QoS)
    * Security

## Chapter 2: Basic Switch and end device
1. 
- Shell: Giao diện người dùng cho phép người dùng yêu cầu các tác vụ cụ thể từ máy tính. Các yêu cầu này có thể được thực hiện thông qua giao diện dòng lệnh (CLI) hoặc giao diện đồ họa người dùng (GUI).
- Kernel:  Giao tiếp giữa phần cứng và phần mềm của máy tính và quản lý cách sử dụng tài nguyên phần cứng để đáp ứng các yêu cầu của phần mềm.
- Hardware: Phần vật lý của máy tính bao gồm các thành phần điện tử cơ bản.
2. 
- Console: Một cổng quản lý vật lý được sử dụng để truy cập vào thiết bị nhằm thực hiện bảo trì, chẳng hạn như thực hiện cấu hình ban đầu.
- Secure Shell (SSH) - 22: thiết lập kết nối CLI từ xa an toàn đến thiết bị thông qua giao diện ảo qua mạng.
- Telnet - 23: Thiết lập kết nối CLI từ xa không an toàn đến thiết bị qua mạng.

## Chapter 4: Physical layer
- IEEE 802.3 (Ethernet) && IEEE 802.11 (Wi-Fi)
- EEE 802.15 (Bluetooth)
- Zigbee (IEEE 802.15.4) && WiMAX (IEEE 802.16) 
1. Encoding(Mã hóa)
- encoding là quá trình chuyển đổi dữ liệu từ dạng số (bit) thành tín hiệu phù hợp để truyền qua phương tiện truyền thông vật lý.
    * Binary Encoding (Mã hóa nhị phân)
    * Line Coding (Mã hóa đường truyền)
2. Signaling (Tín hiệu)
- Signaling là quá trình truyền tải tín hiệu đã được mã hóa qua phương tiện truyền thông vật lý. Lớp Physical Layer đảm nhận việc phát tín hiệu qua các phương tiện truyền thông như cáp đồng, cáp quang, hoặc sóng vô tuyến.
    * Analog Signaling (Tín hiệu tương tự)
    * Digital Signaling (Tín hiệu số)
3. Cable
- UTP: Đây là một loại cáp xoắn không có lớp bảo vệ (shielding), nhưng vẫn có khả năng truyền tải dữ liệu hiệu quả.
- STP: là một loại cáp mạng tương tự như UTP nhưng có thêm lớp bảo vệ để giảm thiểu nhiễu từ bên ngoài.
- Coaxial Cable: là một loại cáp có cấu trúc đồng trục, bao gồm một lõi dây dẫn đồng, một lớp cách điện, một lớp lưới hoặc lá kim loại, và lớp bọc bên ngoài.
- Có 4 loại cap quang:
    * Enterprise Networks
    * Fiber-to-the-Home (FTTH)
    * Long-Haul Networks
    * Submarine Cable Networks


## Chapter 5: DataLink
1. Mục đích
- **Data Link** trong mô hình OSI đóng vai trò quan trọng trong việc chuẩn bị dữ liệu để truyền qua các phương tiện truyền thông cụ thể. Các chức năng chính của lớp này bao gồm:
    * **Đóng Gói Dữ Liệu**: Chia dữ liệu từ lớp Network thành các khung dữ liệu (frames) và thêm thông tin điều khiển (header và trailer) để chuẩn bị cho việc truyền qua môi trường vật lý.
    * **Quản Lý Lỗi**: Phát hiện và sửa lỗi truyền dữ liệu bằng cách sử dụng các phương pháp kiểm tra lỗi như CRC (Cyclic Redundancy Check).
    * **Điều Khiển Luồng**: Quản lý tốc độ truyền dữ liệu giữa các thiết bị để tránh quá tải.
    * **Xác Định Địa Chỉ**: Sử dụng địa chỉ MAC (Media Access Control) để xác định thiết bị đích trong mạng cục bộ.

2. Topologies(Cấu trúc liên kết)
- Physical topology
- Logical topology 

- ![img](./lanTopo.png)

3. DataLink Sublayer
- **LLC Sublayer(IEEE 802.2)**: 
    * Chức năng: Đặt thông tin vào khung dữ liệu (frame) để xác định giao thức lớp mạng (network layer protocol) nào đang được sử dụng cho khung đó.
    * Mục đích: Giúp các giao thức lớp mạng khác nhau có thể hoạt động trên cùng một mạng vật lý bằng cách phân loại và xử lý các khung dữ liệu.
- **MAC(IEEE 802.3, 802.11, hoặc 802.15)**
    * Chức năng: Chịu trách nhiệm về việc đóng gói dữ liệu (data encapsulation) và kiểm soát truy cập phương tiện (media access control), đồng thời cung cấp địa chỉ lớp liên kết dữ liệu (data link layer addressing).
    * Mục đích: Quản lý việc truyền dữ liệu qua phương tiện vật lý và đảm bảo rằng các thiết bị trong mạng có thể giao tiếp hiệu quả với nhau thông qua việc sử dụng địa chỉ MAC và các phương pháp kiểm soát truy cập khác.

## Chapter 8 Network layer: 
- Đặc điểm IP: 
    * Connectionless (phi kết nối)
    * Best Effort
    * Media Independent

- **Routing**: Lớp mạng quyết định đường đi tốt nhất cho gói dữ liệu từ nguồn đến đích qua một hoặc nhiều mạng.
- **Encapsulation**: đảm nhận việc đóng gói segment từ lớp truyền tải (Layer 4) thành gói dữ liệu (IP packet) để gửi qua mạng.
- **De-encapsulation**: Khi dữ liệu di chuyển từ lớp mạng đến lớp ứng dụng, nó phải được giải nén (de-encapsulated) ở mỗi lớp để phục hồi dữ liệu gốc. Đây là một phần quan trọng trong việc xử lý dữ liệu khi nó đến đích. 
- **Addressing end devices**: là quá trình gán địa chỉ IP cho các thiết bị cuối trong mạng để chúng có thể giao tiếp với nhau.

## Chapter 9:
- ARP: xác định địa chỉ MAC của thiết bị khi biết địa chỉ IPv4 của nó
## Chapter 10 && 11: IPV4 && ipv6
1. IPv4
- NAT: dịch ipv4 private --> ipv4 public
- Các địa chỉ ipv4 private: 
    * 10.0.1.1
    * 172.16.5.4
    * 127.0.0.1
    * 192.168.1.0
2. IPv6
- Tổng quan: 
    * Dual Stack: Chạy cả IPv4 và IPv6 trên cùng một thiết bị.
    * Tunneling: Đóng gói gói tin IPv6 vào gói tin IPv4 để truyền qua mạng IPv4.
    * Translation: Sử dụng NAT64 để cho phép giao tiếp giữa thiết bị IPv6 và IPv4.
- Các địa chỉ ipv6:
    * IPv6 global unicast addresses (GUAs) - 2000->3fff: Toàn cầu
    * Unique Local Address (ULA) - fc00:: Địa chỉ riêng tư trong một mạng nội bộ (tương tự như địa chỉ IP private trong IPv4)
    * Link Local Address(LLA) - fe80::/10
    * Multicast - ff0x::
- **SLAAC** là một cơ chế cho phép các thiết bị tự động cấu hình địa chỉ IPv6 của chúng mà không cần sự can thiệp từ máy chủ DHCP
- **Stateless DHCPv6** là một phương pháp bổ sung cho SLAAC, cung cấp thông tin cấu hình bổ sung cho các thiết bị mà SLAAC không cung cấp, chẳng hạn như địa chỉ DNS.
