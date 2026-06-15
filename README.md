# Real-Time Sentiment Analysis with PySpark Streaming

A PySpark Streaming pipeline that processes a simulated real-time social stream to surface sentiment, trending topics, influential accounts, and geographic and language patterns. Built as an applied project for the Johns Hopkins Big Data Analytics certificate.

## Overview

This project demonstrates a streaming analytics pipeline: ingesting a continuous flow of short social posts, scoring sentiment, and aggregating signals in near real time. It covers influential users, trending topics, sentiment distribution, geographic breakdowns, and language patterns, with a summary dashboard at the end.

## Data

The pipeline runs on a simulated social stream. The live public Twitter streaming API was retired in 2023, so this project uses a generated corpus designed to mirror realistic distributions (follower counts, country and language patterns, posting times). The synthetic data stands in for a live feed so the streaming pipeline can be demonstrated end to end.

## Approach

1. Spark Streaming session setup
2. Stream ingestion of the simulated post corpus
3. Sentiment scoring
4. Aggregation: influential users, trending topics, geo and language breakdowns, top and most-shared posts
5. Summary dashboard and conclusions

## Tools

PySpark, Spark Streaming, Python, sentiment analysis, data aggregation and visualization.

## Notes

Completed as part of the Johns Hopkins Big Data Analytics certificate. The data is a simulated stream, not live social data, because the public streaming API is no longer available. The pipeline design and analysis are my own work.
