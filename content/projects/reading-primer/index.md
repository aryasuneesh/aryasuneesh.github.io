---
title: "Reading Primer Project (Fibel)"
date: 2024-05-01
tags: ["digital education", "speech recognition", "Raspberry Pi", "AI in education", "sustainability"]
description: "Digital Reading Acquisition Assistant (DRAA) for children aged 5-10, featuring human-machine peer learning with advanced speech recognition on solar-powered Raspberry Pi devices."
summary: "Developed sophisticated speech recognition system for educational device targeting children's literacy, integrating DeepSpeech and Whisper models on sustainable, Raspberry Pi-driven hardware."
---

## Project Overview

**Project Name:** Reading Primer Project & Fibel Digital  
**Institution:** Berlin University of the Arts & Einstein Center for Digital Future  
**Duration:** May 2024 - July 2024  
**Supervisor:** Prof. Dr. Daniel D. Hromada  

The Personal Primer is a revolutionary digital education artifact designed as a Digital Reading Acquisition Assistant (DRAA) that guides students aged 5-10 in developing fundamental literacy and numeracy skills. The project embraces the innovative concept of 'human-machine peer learning' (HMPL), creating an interactive learning companion that adapts to individual children's learning patterns.

## Technical Architecture

### Hardware Platform
- **Primary Device:** Raspberry Pi 4 with custom educational interface
- **Power System:** Solar energy integration for sustainability and global accessibility
- **Sensors:** I2C sensors for interactive feedback and user engagement
- **Display:** Child-friendly interface optimized for young learners
- **Audio System:** High-quality speakers and microphone array for speech interaction

### Software Stack
- **Operating System:** Raspbian Linux optimized for educational applications
- **Speech Recognition:** DeepSpeech and Whisper models fine-tuned for children's speech
- **Backend:** Python-based application framework with modular architecture
- **Database:** Vector database (Chroma) for efficient content retrieval and personalization
- **Content Management:** Audio-textual content from Panchatantra fables

## Core Technical Contributions

### Advanced Speech Recognition System
The system addresses the challenge of children's highly variable speech patterns through a robust ASR system capable of handling imperfect speech input with high accuracy. Custom training data augmentation and model fine-tuning enable age-appropriate speech recognition, validated through extensive testing with diverse child speech samples. The implementation integrates optimized DeepSpeech for low-resource environments and adapted Whisper for real-time processing on Raspberry Pi, with dynamic model switching based on speech quality and processing requirements while achieving real-time processing with maintained accuracy standards.

### Personalized Narration Module
An adaptive learning system learns and adapts to each child's reading progress and preferences, providing personalized content delivery through dynamic adjustment of difficulty level and pacing based on user performance. Comprehensive analytics track reading development and skill acquisition, with automated identification of learning difficulties and adaptive support. The module integrates audio-textual contents from Panchatantra fables, featuring synchronized text, audio, and visual elements for enhanced comprehension through interactive storytelling that adapts based on user responses while respectfully integrating traditional stories with modern educational technology.

### Hardware Engineering and Prototyping
The Fibel 4 prototype development involved complete device assembly including custom enclosure design, utilizing advanced soldering techniques for reliable connections and both filament and resin 3D printing for custom components and enclosures. Precision laser cutting was employed for device housing and interactive elements. Manufacturing techniques emphasized rapid prototyping through iterative design and testing cycles for optimal user experience, with rigorous testing protocols ensuring durability and child safety while balancing functionality with manufacturing affordability and designing architecture for mass production and global deployment.

## Sustainability and Accessibility

### Environmental Considerations
The system integrates a complete solar energy system for off-grid operation, with optimized software and hardware designed for minimal energy consumption. Environmentally conscious material choices and durable design focus on reducing electronic waste and replacement needs, supporting long-term sustainability goals.

### Global Accessibility
Designed specifically for resource-constrained environments with limited electrical infrastructure, the system features cost-effective manufacturing for widespread adoption. A flexible framework enables easy localization and cultural customization, directly contributing to Sustainable Development Goals for quality education through accessible technology.

## Technical Challenges and Solutions

### Real-time Processing Constraints
Achieving real-time speech recognition on resource-limited Raspberry Pi was solved through optimized model architectures and efficient processing pipelines, resulting in sub-second response times while maintaining recognition accuracy.

### Child-Specific Speech Recognition
The high variability in children's speech patterns and pronunciation was addressed through specialized training datasets and adaptive learning algorithms, creating a robust recognition system capable of handling diverse speech characteristics.

### Personalization at Scale
Individual adaptation without compromising privacy or requiring cloud connectivity was achieved through on-device learning algorithms with local data storage and processing, delivering personalized experiences while maintaining data privacy and offline functionality.

## Research and Development Outcomes

### Technical Innovations
The project delivered a novel hybrid ASR architecture combining DeepSpeech and Whisper for optimal performance, implementing advanced AI capabilities running entirely on edge devices. Child-centered interface design based on educational psychology principles created adaptive UI/UX, while demonstrating advanced AI applications in resource-constrained, sustainable systems.

### Educational Impact
The system achieved measurable improvements in literacy development through interactive learning, with high user engagement and sustained learning motivation. The technology makes quality education accessible in underserved communities while providing a digital platform for preserving and sharing traditional stories.


This project represents a significant contribution to the intersection of AI, education, and sustainability, demonstrating how advanced technology can be made accessible and impactful for global educational challenges.
