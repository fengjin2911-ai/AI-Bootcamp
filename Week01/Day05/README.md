# Day 05 - Server Resource Manager

## Overview

This project is a simple Server Resource Manager built with Python and Object-Oriented Programming.

The program allows a user to create a server object, monitor its resource usage, update CPU and memory usage, check server health, and control whether the server is running or stopped.

## Topics Practiced

- Python classes
- Object creation
- `__init__()`
- `self`
- Attributes
- Methods
- Object state
- Input validation
- Conditional statements
- While loops

## Server Attributes

Each server object contains:

- Server name
- CPU usage
- Memory usage
- Server status

## Features

- Show server status
- Update CPU and memory usage
- Validate usage between 0 and 100
- Check server health
- Start server
- Stop server
- Prevent resource updates while the server is offline

## Health Conditions

- `Critical` when CPU or memory usage is 90% or higher
- `Warning` when CPU or memory usage is 75% or higher
- `Healthy` when both values are below 75%
- `Server is offline` when the server status is Stopped

## Run the Program

```bash
python3 day_5_server_resource_manager.py
