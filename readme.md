# Payment processor
## Modules 
### 1. flow
- receives data via REST end point and publish to kafka 
### 2. Proof
- listen to kafka and receives message published by flow
- encrypt the message and publish to kafka
### 3. Source
- listen to kafka and read the encrypted message, decrypts and shows as console log

## Demo 
![](payment-processor.gif)

- Detailed instruction can be found under each module