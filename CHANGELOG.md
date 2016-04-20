### 0.2.2
* Eliminate heartbeat from message.

### 0.2.1
* Convert whole message to unicode.

### 0.2.0
* Add timeout to get_messages.

### 0.1.0
* Add ssl support.

### 0.0.10
* Re-adapt message delimitation logic to line packets and following STOMP spec.

### 0.0.9
* Revert get_messages logic to upstream phase.

### 0.0.8
* Fix message stream termination logic.

### 0.0.7
* Remove timeout on on_message

### 0.0.6
* Handle tcp send error properly

### 0.0.5
* Increase receiver buffer to a more standard initial capacity (65536)

### 0.0.4
* Add some more error handling, and remove others. Fix styling.

### 0.0.3
* Handle some timeout and empty header/body cases properly.

### 0.0.2
* Add TCP and STOMP error handling with proper gen server protocol.

### 0.0.1
* Initial version
