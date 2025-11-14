# Implementation of Hybrid Blockchain applied for Supply Chain Tracking

## 📄 Article submitted to *Software: Practice and Experience*

The logistics of the supply chain play a crucial role in preserving the quality and safety of perishable products. However, traceability and monitoring throughout the traditional supply chain often face challenges due to a lack of transparency and reliability, leading to losses and risks to public health.

This article proposes an architecture that integrates the Internet of Things (IoT), a hybrid database composed of Hyperledger Fabric and MongoDB, and fog and edge computing to enhance the logistics of these products. IoT enables real-time data collection on environmental conditions, while fog and edge computing process data closer to the source, enabling immediate actions through actuators. The hybrid database ensures traceability by securely and immutably storing information.

A prototype was developed and tested, demonstrating the benefits of the hybrid database approach and improving traceability and efficiency in supply chain management. Although challenges related to scalability were identified, this architecture has the potential to elevate industry standards.

---

## 🔧 Key Features

The proposed architecture consists of six layers: user layer, application layer, data gateway layer, hybrid database layer, fog computing layer, and IoT with edge computing layer.

* **User layer**: includes producers/manufacturers, logistics companies, consumers, and system administrators. They perform specific roles such as assigning electronic codes to products, monitoring storage parameters, and managing the system.

* **Application layer**: provides services such as user, device, and product management, quality regulation, and product traceability.

* **Data gateway layer**: acts as middleware for data processing, storage, and querying. It includes modules such as a storage manager, data integrity checker, and intelligent risk analysis and alerting system.

* **Hybrid database layer**: combines blockchain (Hyperledger Fabric) and traditional databases (MongoDB) to optimize performance and scalability. Data are stored on-chain or off-chain depending on system requirements.

* **Fog computing layer**: includes storage management, device management, connection control, and data validation for IoT devices.

* **IoT and edge computing layer**: covers device monitoring, connection control, alert generation, and actuator capabilities to perform actions based on collected environmental information.

---

## 🧾 Conclusion

In this article, we presented an architecture for managing supply chains of perishable products. This architecture spans several layers, from the user layer to the IoT layer, and we discussed in detail the role of each layer in the system.

The tests performed demonstrated that the hybrid database approach combining MongoDB and Hyperledger Fabric is effective. However, challenges related to scaling at the edge layer were identified, and data insertion and query times could be improved. With proper planning, this solution can significantly enhance the management of perishable products.

For future work, we intend to explore the integration of advanced technologies such as Artificial Intelligence to improve data analysis and validation in real-world scenarios.

--
