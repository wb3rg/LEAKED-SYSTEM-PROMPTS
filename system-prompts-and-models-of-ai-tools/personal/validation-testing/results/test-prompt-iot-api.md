# Test Prompt: IoT API Platform

**Task**: Develop a scalable RESTful API to collect, process, and serve data from thousands of IoT sensors deployed across smart city infrastructure. The API must handle high-frequency data ingestion, real-time processing, and provide endpoints for various client applications including mobile apps, web dashboards, and third-party integrations.

## Key Requirements:
- **Framework**: FastAPI with async/await patterns for high performance
- **Database**: MongoDB for flexible sensor data schema
- **Caching**: Redis for real-time data caching and session management
- **Message Queue**: RabbitMQ for handling high-volume sensor data
- **Authentication**: OAuth2 with scopes for different access levels
- **Rate Limiting**: Implement rate limiting to prevent API abuse
- **Monitoring**: Comprehensive logging and metrics collection
- **Documentation**: Auto-generated API documentation with examples
- **Testing**: 90%+ test coverage with unit and integration tests
- **Deployment**: Docker containerization with CI/CD pipeline

## Technical Constraints:
- Handle 100,000+ requests per minute
- Sub-100ms response times for real-time endpoints
- 99.9% uptime requirement
- Data retention for 5 years with archival strategy
- GDPR compliance for personal data handling

## Business Context:
- 2-month development timeline
- Team of 3 backend developers
- Must integrate with existing city infrastructure APIs
- Budget-conscious approach with open-source technologies
- Potential for white-label licensing to other cities

**Please create a comprehensive project plan for this IoT API platform development.**
