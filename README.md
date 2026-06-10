# Dual-Graph-Neural-Learning-for-Web-API-Service-Composition
The proposed  approach models the service ecosystem using two complementary graph structures: a mashup API  invocation graph that captures real usage interactions, and an API tag association graph that represents  semantic and functional relationships among APIs. 
The rapid expansion of Web APIs has significantly enhanced the flexibility of service oriented applications, but it has also made the task of selecting compatible APIs for service composition increasingly complex.
Traditional service recommendation approaches often rely on sparse invocation data or isolated feature representations, limiting their ability to capture deeper collaborative and functional relationships among services.
To address these challenges, this project proposes an adaptive service recommendation framework based on a dual-graph neural learning paradigm.
A multi-layer graph neural network is employed to propagate information across higher-order connections, enabling the model to uncover latent collaborative patterns that are missed by shallow learning methods.
To prevent performance degradation caused by over-smoothing in deep graph propagation, an interactive attention mechanism is introduced to dynamically weight the contributions of different propagation layers.
Additionally, service feature embeddings are integrated with structural representations to form an end-to-end learning framework.
Experimental evaluation on real world service datasets demonstrates that the proposed model significantly improves recommendation accuracy compared to conventional collaborative filtering and single graph neural network approaches.
The results highlight the effectiveness of dual-graph modeling and adaptive attention in capturing complex service interactions, making the proposed system well suited for intelligent Web API recommendation and service composition scenarios.
