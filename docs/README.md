# Documentation Directory

This directory contains comprehensive documentation and specifications for the Repository Profile Analyzer project.

## Structure

- `api/` - API documentation and endpoint specifications
- `architecture/` - System architecture and design documents
- `user-guide/` - User guides and tutorials

## Contents

### API Documentation (`/api`)
- REST API endpoint specifications
- Request/response schemas
- Authentication requirements
- Rate limiting information
- Error handling guidelines

### Architecture Documentation (`/architecture`)
- System overview and components
- Database design and schemas
- Technology stack decisions
- Deployment architecture
- Security considerations

### User Guide (`/user-guide`)
- Getting started tutorials
- Feature walkthroughs
- Configuration guides
- Troubleshooting tips
- FAQ section

## Documentation Standards

- All documentation should be written in Markdown format
- Include code examples where applicable
- Use clear headings and proper formatting
- Keep documentation up-to-date with code changes
- Include diagrams and screenshots when helpful

## API Reference

The API documentation covers:

### Repository Analysis Endpoints
- `GET /api/analyze/repository/{owner}/{repo}` - Analyze a specific repository
- `POST /api/analyze/repository/batch` - Batch analyze multiple repositories

### Profile Analysis Endpoints  
- `GET /api/analyze/profile/{username}` - Analyze a user profile
- `GET /api/analyze/profile/{username}/repositories` - Get user's repository analysis

### Report Endpoints
- `GET /api/reports` - List available reports
- `GET /api/reports/{id}` - Get specific report
- `POST /api/reports` - Generate new report

### Export Endpoints
- `GET /api/export/{format}` - Export data in various formats (JSON, CSV, PDF)
- `POST /api/export/custom` - Custom export with filters

## Contributing to Documentation

1. Follow the existing structure and formatting
2. Test all code examples before committing
3. Update the table of contents when adding new sections
4. Use consistent terminology throughout
5. Include version information for API changes

## Tools and Resources

- Documentation is built using standard Markdown
- API documentation follows OpenAPI/Swagger specifications
- Architecture diagrams created using standard diagramming tools
- Screenshots and images stored in appropriate subdirectories
