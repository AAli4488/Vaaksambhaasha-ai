VaakSambhaasha — AI-Powered Indian Sign Language Translator
Har Awaaz Sunai De — Every Voice Must Be Heard
What is VaakSambhaasha?
VaakSambhaasha (वाक्संभाषा) is a free, AI-powered mobile application that provides real-time, bidirectional translation between Indian Sign Language (ISL) and spoken/written Hindi and English.
India has 63 lakh (6.3 million) deaf and mute citizens who face daily barriers in hospitals, schools, government offices, workplaces, and emergencies. No viable ISL-specific AI solution exists today. VaakSambhaasha changes that.
The Problem
Every single day, deaf and mute Indians face:
Hospitals — Cannot describe symptoms. Misdiagnosis is common.
Schools — 70%+ dropout rate among deaf children in mainstream schools.
Government Offices — Cannot file FIRs, access Aadhaar, or apply for welfare schemes.
Workplaces — Unemployment 3x higher than national average despite full capability.
Emergencies — Cannot call for help. Lives are lost due to communication failure.
The Solution
Think Google Translate — but for Indian Sign Language.
DEAF PERSON SIGNS → Phone Camera → AI Recognizes → Hindi/English Text + Voice Output
HEARING PERSON SPEAKS → Speech to Text → Maps to ISL → Animated Signs on Screen
5 Core Features
ISL to Voice — Real-time sign recognition, response under 1.5 seconds
Voice to ISL — Speech or text converted to animated ISL on screen
Emergency SOS — 20 life-saving phrases, 100% offline, no internet needed
Learn ISL — Interactive A-Z lessons with real-time AI feedback
Phrase Library — 200+ preloaded phrases by context, works offline
Technical Stack
AI and Machine Learning:
MediaPipe Hands — Real-time hand landmark detection (21 points per hand)
TensorFlow Lite — On-device CNN-LSTM model for gesture classification
Model Size — 45 MB reduced to 12 MB after Int8 quantization
Inference Speed — 85ms reduced to 28ms on Rs. 8,000 Android phone
Accuracy — 89.1% on diverse Indian test dataset
AWS Cloud Services:
AWS Transcribe — Speech to text in Hindi
AWS Polly — Text to speech with Hindi voice
AWS Lambda — Serverless API
AWS S3 — Model and video storage
AWS DynamoDB — User data and analytics
AWS CloudFront — CDN for fast delivery across India
Mobile App:
Framework — Flutter (Android and iOS)
Minimum Android — 8.0 Oreo
Works on — Rs. 6,000+ smartphones
Install size — Under 60 MB
Offline coverage — 90% of features
Roadmap
Phase 1 — February 2025 — Hackathon MVP:
ISL A-Z recognition at 87%+ accuracy
50 phrases bidirectional
Emergency SOS fully offline
Hindi and English support
Phase 2 — May 2025 — Beta Launch:
Google Play Store release
200+ phrase library
Hospital pilot programs
Tamil and Telugu support
Phase 3 — August 2025 — Version 1.0:
25,000+ downloads
5 Indian languages
NGO and Government partnerships
Phase 4 — February 2026 — National Scale:
5 lakh+ active users
WhatsApp plugin
Ayushman Bharat API integration
Government kiosk deployment
Social Impact
63 lakh+ direct beneficiaries
Aligned with Digital India, Accessible India, Ayushman Bharat, NEP 2020
Supports UN SDGs 3, 4, 8, and 10
Team
Team AwaazAI — AI for Bharat Hackathon 2025
Track — Public Impact + Healthcare and Life Sciences
Deadline — February 15, 2025
India has built rockets. India has built UPI. India has built AI.
But 63 lakh Indians still cannot have a basic conversation at a hospital.
VaakSambhaasha changes that.
Har Awaaz Sunai De — Every Voice Must Be Heard
