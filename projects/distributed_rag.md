# Distributed Neural Networks – Decentralized Data Pipeline

**Tech:** Kotlin, Python, Firestore, 4-bit LLMs, Data Parallelism  

Built a distributed data pipeline using data parallelism across mobile devices.  
Each device ran local vector search, processed text embeddings, and executed 4-bit
quantized LLMs for low-latency edge inference, then returned partial answers for
central summarization. Designed the full flow using Slack → Python → Firestore
orchestration, optimised JSON streaming, inter-device communication, and data
aggregation, improving latency and scalability compared to a centralised RAG setup.
