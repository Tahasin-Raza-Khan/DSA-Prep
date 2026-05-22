## — System Design HLD + Leadership Principle<br>

One high-level design problem followed by one LP question.<br>

Design: Google Docs (Collaborative Document Editing)<br>
Key areas discussed:

Real-time collaboration
Operational Transformation (OT) vs CRDTs for conflict resolution
WebSocket connections for low-latency sync
Storage and versioning
Delta-based storage for document history
Snapshot + diff strategy for efficient retrieval
Scalability — sharding by document ID, regional replication
Presence indicators (who's editing what, cursor positions)
Permissions and access control model



## 