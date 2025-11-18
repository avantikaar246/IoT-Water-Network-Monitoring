# Limitations of the IoT Water Network Monitoring Project

1. **Data Granularity**
   - Sensors provide readings at different time intervals; slight misalignment may affect analysis.

2. **Missing or Inconsistent Data**
   - Some sensors may have missing timestamps or null values, which can introduce bias even after cleaning.

3. **Vendor Differences**
   - Different vendors use different key names and formats, which may cause integration errors if not mapped carefully.

4. **Anomaly Detection**
   - Simple anomaly indicators may miss complex patterns or rare events.

5. **Scope**
   - The analysis focuses only on pressure and flow metrics; other network health indicators are not considered.
