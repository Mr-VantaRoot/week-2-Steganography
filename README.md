Physical Layer (Layer 1):

Handles the physical connection between devices (e.g., Ethernet cables, Wi-Fi signals).
Transmits raw bits over the physical medium.


Data Link Layer (Layer 2):

Manages node-to-node data transfer.
Ensures error-free frames using MAC addresses.
Handles frame synchronization and flow control.


Network Layer (Layer 3):

Routes data packets across networks.
Uses IP addresses to deliver the data to the Telegram server or recipient device.
Performs packet forwarding and addressing.


Transport Layer (Layer 4):

Ensures complete data transfer.
Telegram primarily uses TCP (Transmission Control Protocol), which provides reliable, ordered delivery.
Manages segmentation, acknowledgments, and flow control.


Session Layer (Layer 5):

Manages sessions between the client and server.
Maintains persistent connections during file transfer.
Handles session establishment, maintenance, and termination.


Presentation Layer (Layer 6):

Translates data formats.
Encrypts/decrypts data for security (Telegram uses end-to-end encryption for secret chats, and client-server encryption for cloud chats).
Compresses data to optimize transfer.


Application Layer (Layer 7):

Interacts directly with the user.
Implements Telegram's protocols for file transfer.
Handles user commands, file requests, and responses.
Manages the overall process of uploading and downloading files through the Telegram app.
