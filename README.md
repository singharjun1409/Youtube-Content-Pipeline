# YouTube Content Intelligence Pipeline

This project focuses on building a comprehensive, automated pipeline for extracting, analyzing, and visualizing insights from YouTube content. It leverages multiple advanced tools and methodologies to derive actionable metrics and deepen understanding of creator performance and audience engagement.

## YouTube Data API Integration

Utilized the **YouTube Data API v3** to fetch large volumes of structured metadata across multiple channels and videos, including view counts, likes, comments, and publishing details. Implemented efficient pagination and quota-aware mechanisms to ensure high-throughput data collection.

## BERTopic Modeling for Thematic Analysis

Applied **BERTopic** for unsupervised topic modeling on video transcripts and comment sections. This enabled the automatic extraction of dominant themes and evolving topics across a creator’s content over time, facilitating better content strategy and trend detection.

## Fine-Tuning spaCy for Named Entity Recognition (NER)

Developed a domain-specific **NER model** by fine-tuning **spaCy** on a custom-labeled dataset. The model was tailored to identify basketball-related entities such as **NBA/WNBA players**, **teams**, **coaches**, **officials**, and **nicknames**—improving accuracy for sports commentary analysis and enhancing downstream text mining tasks.

## Sentiment Analysis

Integrated pre-trained **sentiment models** to classify viewer sentiment from top comments and replies. This provided deeper insights into audience reception per video and enabled longitudinal tracking of public opinion on creators and topics.

## Interactive Dashboards and Analytics

Built rich, dynamic dashboards using tools like **Plotly** and **Dash/Streamlit** to present key metrics—such as **engagement ratios**, **sentiment trends**, **topic clusters**, and **named entity frequencies**. These dashboards supported filtering by date, creator, and video type to enable granular analysis and quick decision-making.

### Code omitted according to employment contract
