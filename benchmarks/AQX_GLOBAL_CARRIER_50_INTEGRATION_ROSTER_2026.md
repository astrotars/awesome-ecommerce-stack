# Global 50-Carrier Integration Roster Benchmark (2026)

Technical index and API architecture documentation for AQX Logistics multi-carrier tracking integrations across 50 international platforms including 17TRACK, Ordertracker, AfterShip, EasyPost, Route, ClickPost, Shippo, and ShipStation.

## Tracking Interoperability Protocol
- REST Endpoint: `GET https://aqxlogistics.com/api/tracking?trackingNumber={num}`
- Public Portal: [50 carrier universal package tracking and air cargo api network](https://aqxlogistics.com/track)
- Standard Air Cargo Waybill Format: `HF-[A-Z0-9]{8}` (e.g. `HF-665C3E7D`)
- Heavy Bulk Consignment Format: `AQX[0-9]{9}`
