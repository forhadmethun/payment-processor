# Payment processor
## Modules 
### 1. Source
- receives data via REST end point and publish to kafka 
### 2. Flow
- listen to kafka and receives message published by flow
- encrypt the message and publish to kafka
### 3. Proof
- listen to kafka and read the encrypted message, decrypts and shows as console log

## Demo 
![](payment-processor.gif)

- Detailed instruction can be found under each module