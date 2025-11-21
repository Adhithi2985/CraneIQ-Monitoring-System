CraneIQ Monitoring System is an intelligent IoT-based monitoring application built to track and analyze crane operations in real-time. 
The system uses MQTT communication for live sensor updates, a Flutter mobile application for visualization, and an integrated Grok LLM-powered chatbot for operator support and troubleshooting.

**Features**

Real-time sensor monitoring through MQTT
Live crane status visualization in the Flutter app
Integration with Mosquitto MQTT broker
Grok AI chatbot for answering operator queries
Overload and critical alert notifications
Historical log storage (optional backend)
Modern UI built using Flutter + Dart

**Tech Stack**
📱 Frontend (Mobile App)
Flutter
Dart

MQTT Client (mqtt_client package)
 Communication Layer
Mosquitto MQTT Broker
QoS-based message delivery
Topic-based sensor data streaming

🤖 AI Chatbot
Grok API Key
Integrated inside the app for answering:
Crane troubleshooting
Load/limit issues
System queries
General operator guidance
