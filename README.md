# Quality-Log-Control
This is the Quality log control Program using The API
# Quality Log Control

## Overview
This project implements a logging system to capture logs from various APIs and provides a query interface for searching through these logs efficiently.

## Log Ingestor
The Log Ingestor component captures logs from multiple APIs and writes them to designated log files. It allows configuring logging levels and file paths for each API.

### Features
- API integration to capture logs.
- Configurable logging levels and file paths.
- Error handling for robustness.

### Scalability Optimizations
- Asynchronous logging to mitigate I/O bottlenecks.
- Configurable log rotation to manage log file size.

## Query Interface
The Query Interface component provides a user-friendly interface (CLI) for searching through logs. It supports full-text search and filtering based on log level, log string, timestamp, and metadata source.

### Features
- Full-text search across logs.
- Filters based on log attributes.

### Advanced Features (Bonus)
- Search within specific date ranges.
- Real-time log ingestion and searching capabilities.

## How to Run
1. Clone the repository.
2. Install dependencies (if any).
3. Run the Log Ingestor and Query Interface modules.

## Evaluation Criteria
- Volume: The ability to handle large volumes of logs efficiently.
- Speed: Quick retrieval of search results.
- Scalability: Adaptability to increasing volumes of logs/queries.
- Usability: Intuitive interface for users.
- Advanced Features: Implementation of bonus functionalities.
- Readability: Clean and structured codebase.

