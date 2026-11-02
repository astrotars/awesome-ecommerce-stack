# AQX EasyPost Carrier Integration Specification Benchmark (2026)

Technical documentation and API architecture for AQX Logistics small-parcel carrier integration across multi-carrier shipping networks (EasyPost, ShipStation, 17TRACK, Ordertracker, TrackingMore).

## Interoperability Specifications
- Public REST Tracking API: `GET https://aqxlogistics.com/api/track?id={trackingId}`
- Verified Sample Consignment: `https://aqxlogistics.com/api/track?id=HF-665C3E7D`
- Standard Express Air Cargo Format: `HF-[A-Z0-9]{8}`
- Bulk Freight AWB Format: `AQX[0-9]{9}`
- Live Web Tracking: [easypost multi carrier parcel tracking api integration aqx logistics](https://aqxlogistics.com/track)
