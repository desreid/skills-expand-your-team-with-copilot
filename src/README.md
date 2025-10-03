# Mergington High School Activities

A web application that allows teachers to manage student registrations for extracurricular activities.

## Features

### For Teachers
- **Authentication**: Secure login system for teachers to access management features
- **Student Registration**: Register students for extracurricular activities
- **Unregister Students**: Remove students from activities they are enrolled in
- **View Participants**: See current participant lists for all activities

### For Everyone
- **View Activities**: Browse all available extracurricular activities with detailed information
- **Advanced Filtering**: 
  - Search activities by name
  - Filter by category (sports, arts, academic, community, technology)
  - Filter by day of the week (Monday-Sunday)
  - Filter by time slot (before school, after school, weekend)
- **Activity Details**: View schedule, description, max participants, and current enrollment for each activity

## Technology Stack

- **Backend**: FastAPI with Python
- **Database**: MongoDB for persistent data storage
- **Frontend**: Vanilla JavaScript with modern CSS
- **Server**: Uvicorn ASGI server

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
