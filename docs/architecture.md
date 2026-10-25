# SmartWaste Architecture

## System overview
SmartWaste is planned as an IoT-enabled municipal waste monitoring system. ESP32-based nodes collect fill-level measurements and send telemetry to a backend. A Flutter mobile application requests container status and analytics from the backend API.

## Components
- **IoT sensor node:** ESP32 and a fill-level sensor.
- **Telemetry transport:** MQTT or HTTP; the team must confirm the final protocol.
- **Backend API:** FastAPI endpoints validate telemetry and serve mobile-app requests.
- **Database:** PostgreSQL stores container metadata, telemetry history, and alerts.
- **Analytics and alert logic:** evaluates configured thresholds and creates summaries or alerts.
- **Mobile application:** Flutter app for container locations, fill levels, alerts, and analytics.

## Data flow
1. The sensor measures a container's fill level.
2. The device sends telemetry using the selected transport.
3. The backend validates the measurement and stores it in PostgreSQL.
4. Analytics logic evaluates thresholds and records alerts where applicable.
5. The mobile app calls HTTPS REST endpoints and receives JSON responses.

## Diagram files
- `diagrams/source/system-context.drawio`
- `diagrams/source/use-case.drawio`
- `diagrams/source/component-diagram.drawio`
- `diagrams/exports/system-context.png`
- `diagrams/exports/use-case.png`
- `diagrams/exports/component-diagram.png`

## Draft decisions to confirm
- MQTT or HTTP for device telemetry.
- Exact sensor and message schema.
- Alert thresholds and user permissions.
- Whether push notifications are in scope for the prototype.
