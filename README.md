# Twitch-Database-Project

## Description
Your task is to design and implement a database for an application similar to Twitch, a multimedia streaming platform. The database should manage information regarding users, streaming channels, archived videos, content categories, and user interactions (such as comments and likes).

## Project Requirements
1. **Conceptual Design**
   - Create an Entity-Relationship (ER) diagram representing the main entities of the system (e.g., User, Channel, Video, Comment, Like, Category, etc.) and their relationships.
   - Define attributes for each entity and primary/foreign keys.

2. **Logical Design**
   - Convert the ER diagram into a logical database schema (e.g., in relational format).
   - Specify data types for attributes, integrity constraints (e.g., NOT NULL, UNIQUE, FOREIGN KEY), and any business rules.

3. **SQL Implementation**
   - Create SQL tables based on the logical schema.
   - Populate tables with sample data for at least 5 users, 10 channels, 20 videos, and related comments and likes.
   - Write SQL queries for the following operations:
     - Retrieve all videos from a certain user.
     - Find channels with the highest number of subscribers.
     - Display comments on a specific video.
     - Insert a new video into the system.
     - Update the number of likes for a video.
     - Delete a user and all related videos.

4. **Bonus (Optional)**
   - Implement procedures or triggers to automate some operations (e.g., update like count after each added like).
   - Add a table to manage ongoing streaming sessions, with details on real-time video views.

## Deliverables
1. **ER Diagram**: Provide a complete and well-annotated ER diagram.
2. **SQL Schema**: Share the SQL schema with tables, primary and foreign keys, and integrity constraints.
3. **SQL Queries**: Include the required SQL queries for basic operations.
4. **Sample Implementation**: Upload an SQL dump of your database with sample data.
5. **Any Procedures/Triggers**: If you implemented bonus features, explain how they work and provide the SQL code.

## Important Notes
- Use SQL (preferably PostgreSQL or MySQL) for the database implementation.
- Ensure the schema and queries are well-optimized for the required operations.
- The database should support handling large amounts of data (e.g., millions of videos and comments).
- Follow normalization rules to avoid data duplication issues.
- Document your work clearly and concisely, including detailed explanations for design and implementation choices.mat.
