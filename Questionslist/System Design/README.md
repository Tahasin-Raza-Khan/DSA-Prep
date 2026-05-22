## Amazon (sde 2 23 may 2026)
Round 3 — System Design HLD + Leadership Principle
One high-level design problem followed by one LP question.
Design: Google Docs (Collaborative Document Editing)
Key areas discussed:
•	Real-time collaboration
o	Operational Transformation (OT) vs CRDTs for conflict resolution
o	WebSocket connections for low-latency sync
•	Storage and versioning
o	Delta-based storage for document history
o	Snapshot + diff strategy for efficient retrieval
•	Scalability — sharding by document ID, regional replication
•	Presence indicators (who's editing what, cursor positions)
•	Permissions and access control model
________________________________________
 Round 4 — System Design LLD + Leadership Principles
One low-level design problem followed by two LP questions.
Design: Uber (Ride-Hailing System)
Key areas discussed:
•	Class design — Rider, Driver, Trip, Payment, Location entities
•	Trip state machine: requested → accepted → in_progress → completed / cancelled
•	Driver matching algorithm — geospatial indexing (quadtree / geohash)
•	Surge pricing logic and fare calculation service
•	Payment service integration — idempotency, retries, failure handling
•	API design — REST endpoints for booking, tracking, and cancellation




## 

