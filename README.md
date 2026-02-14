Here is your README file content written in a clean, powerful narrative format (no bullet points), ready to copy and paste into GitHub:


---

VaakSambhaasha — AI-Powered Indian Sign Language Translator

Har Awaaz Sunai De — Every Voice Must Be Heard

What is VaakSambhaasha?

VaakSambhaasha (वाक्संभाषा) is a free, AI-powered mobile application that enables real-time, bidirectional translation between Indian Sign Language (ISL) and spoken or written Hindi and English.

India is home to more than 63 lakh (6.3 million) deaf and mute citizens who face daily communication barriers in hospitals, schools, government offices, workplaces, and emergency situations. Despite rapid technological progress, there is no widely available, ISL-specific AI communication solution built for Bharat. VaakSambhaasha is designed to change that reality.

This application bridges the communication gap between deaf and hearing communities using on-device artificial intelligence, ensuring accessibility, affordability, and offline reliability.


---

The Problem

Every day, millions of deaf and mute Indians struggle with basic communication needs. In hospitals, patients are unable to describe symptoms accurately, which can lead to misdiagnosis and delayed treatment. In schools, more than 70% of deaf children drop out of mainstream education due to the absence of proper communication support. In government offices, citizens face barriers when filing FIRs, accessing Aadhaar services, or applying for welfare schemes.

In workplaces, unemployment among deaf individuals is nearly three times higher than the national average despite full capability and skills. In emergencies, the inability to communicate can cost lives. The lack of a real-time, accessible communication bridge is not just an inconvenience — it is a systemic barrier to equality.


---

The Solution

VaakSambhaasha functions like Google Translate, but for Indian Sign Language.

When a deaf person signs in front of the phone camera, the AI recognizes the gesture in real time and converts it into Hindi or English text along with natural voice output. When a hearing person speaks, the application converts speech into text and then maps it to animated Indian Sign Language displayed on the screen.

This two-way translation enables seamless, instant communication between deaf and hearing individuals without requiring an interpreter.


---

Core Features

VaakSambhaasha provides real-time ISL to voice translation with response times under 1.5 seconds. It supports voice or text to ISL conversion using animated signs displayed clearly on screen. The Emergency SOS module includes 20 life-saving phrases that work fully offline without internet access. The Learn ISL section offers interactive A-Z lessons with real-time AI feedback to help users practice and improve. A preloaded phrase library of more than 200 context-based phrases ensures offline usability across hospitals, schools, workplaces, and public offices.


---

Technical Architecture

The AI system is built using MediaPipe Hands for real-time detection of 21 hand landmarks per hand. Gesture classification is powered by an optimized TensorFlow Lite CNN-LSTM model running directly on the device. The original 45 MB model has been reduced to 12 MB using Int8 quantization, ensuring compatibility with low-cost smartphones. Inference speed has been optimized from 85 milliseconds to 28 milliseconds even on entry-level Android devices priced around Rs. 8,000. The system achieves 89.1% accuracy on a diverse Indian test dataset.

Cloud services are powered by AWS infrastructure. AWS Transcribe converts Hindi speech to text, AWS Polly generates natural Hindi voice output, AWS Lambda manages serverless APIs, AWS S3 handles model and media storage, AWS DynamoDB manages user data and analytics, and AWS CloudFront ensures fast content delivery across India.

The mobile application is developed using Flutter for cross-platform support on Android and iOS. It supports Android 8.0 Oreo and above, works smoothly on smartphones priced at Rs. 6,000 and above, maintains an install size under 60 MB, and provides offline functionality for 90% of features.


---

Roadmap

The February 2025 Hackathon MVP includes ISL A-Z recognition at 87% or higher accuracy, 50 bidirectional phrases, a fully offline Emergency SOS module, and support for Hindi and English.

The May 2025 Beta Launch aims for Google Play Store release, expansion to a 200+ phrase library, hospital pilot programs, and support for Tamil and Telugu.

The August 2025 Version 1.0 targets 25,000+ downloads, support for five Indian languages, and partnerships with NGOs and government bodies.

The February 2026 National Scale vision includes 5 lakh+ active users, WhatsApp plugin integration, Ayushman Bharat API integration, and deployment in government service kiosks across India.


---

Social Impact

VaakSambhaasha directly benefits more than 63 lakh Indians by restoring dignity, independence, and equal access to essential services. The project aligns with Digital India, Accessible India, Ayushman Bharat, and the National Education Policy 2020. It also supports United Nations Sustainable Development Goals 3 (Good Health and Well-being), 4 (Quality Education), 8 (Decent Work and Economic Growth), and 10 (Reduced Inequalities).


---

Team

VaakSambhaasha is developed by Team AwaazAI as part of AI for Bharat Hackathon 2025 under the Public Impact and Healthcare & Life Sciences track.

Deadline: February 15, 2025


---

India has built rockets. India has built UPI. India has built AI.

But 63 lakh Indians still cannot have a basic conversation in a hospital.

VaakSambhaasha changes that.

Har Awaaz Sunai De — Every Voice Must Be Heard.
