+----------------------------------------------------------+
|                  MUNICIPAL SANITATION FLEET              |
+----------------------------------------------------------+
|  Truck Cameras (Front / Side)                           |
|  GPS + Timestamp Sync                                    |
|  Optional Edge Compute (Jetson / Intel)                 |
+--------------------------+-------------------------------+
                           |
                           v
+----------------------------------------------------------+
|                 Secure Data Transmission                 |
|  - LTE Encrypted Upload                                  |
|  - Depot Wi-Fi Batch Upload                              |
|  - TLS Encryption                                        |
+--------------------------+-------------------------------+
                           |
                           v
+----------------------------------------------------------+
|                 Cloud Processing Layer                   |
+----------------------------------------------------------+
|  1. Privacy Redaction Engine                             |
|     - Face detection & blur                              |
|     - License plate blur                                 |
|                                                          |
|  2. AI Detection Engine                                  |
|     - Dumpster detection                                 |
|     - Construction debris detection                      |
|     - Roofing tear-off detection                         |
|     - Material stack detection                           |
|                                                          |
|  3. Event Builder                                        |
|     - Frame aggregation                                  |
|     - Confidence scoring                                 |
|     - GPS-to-parcel mapping                              |
+--------------------------+-------------------------------+
                           |
                           v
+----------------------------------------------------------+
|              Municipal Review Dashboard                  |
+----------------------------------------------------------+
|  - Event Queue                                           |
|  - Map + Parcel Overlay                                  |
|  - Clip Playback                                         |
|  - Permit Database Cross-Check (Optional)                |
|  - Decision Controls (Dismiss / Notice / Open Case)     |
+--------------------------+-------------------------------+
                           |
                           v
+----------------------------------------------------------+
|              Code Enforcement Case System                |
+----------------------------------------------------------+
|  - Case Creation                                         |
|  - Officer Assignment                                    |
|  - Audit Logging                                         |
|  - Outcome Tracking                                      |
+----------------------------------------------------------+
