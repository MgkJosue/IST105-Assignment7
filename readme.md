# OpenRouteService Directions Application

This is a Python script that gets driving directions between two locations using the OpenRouteService API. 

## Description

The application takes two addresses as input, geocodes them to coordinates, and retrieves turn-by-turn driving directions. It displays the route duration, distance, and step-by-step instructions.

## Requirements

- Python 3.6+
- requests library
- OpenRouteService API key

## Installation

```bash
pip install requests
```

## Usage

Run the script:
```bash
python openroute_directions.py
```

Enter locations when prompted:
```
Starting Location: Berlin, Germany
Destination: Hamburg, Germany
```

Type `quit` or `q` to exit.

## Features

- Geocodes addresses to coordinates
- Retrieves driving directions
- Shows trip duration and distance
- Displays turn-by-turn directions
- Error handling for invalid inputs

## API Configuration

You need to get a free API key from OpenRouteService and add it to the script.

## Deployment

The application is deployed on an AWS EC2 instance running Ubuntu 22.04 LTS.

## Repository

GitHub: [Add your repository URL]

EC2 Instance: [Add your public IP/DNS]