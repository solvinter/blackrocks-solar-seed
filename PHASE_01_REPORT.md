# Blackrocks Solar — Phase 1 Report (Seed)

**Location:** Blackrocks, Ghana  
**Date:** January 2026  
**Participants:** Dominic, Brother, Family  
**Project:** Solvinter / Blackrocks Solar (Seed)

---

## 1. Purpose of Phase 1

Phase 1 establishes a **minimum viable energy backup system** to ensure
continuous internet connectivity via Starlink during grid outages.

This phase prioritizes:
- Reliability
- Simplicity
- Local serviceability
- Documentation for future scaling

The system is intentionally small and human-scale.

---

## 2. Scope of Phase 1

**Included**
- Battery backup for Starlink
- Charging from:
  - Main electricity (night)
  - Existing solar panels (day)
  - New solar panel (installed this trip)
- Basic protection, ventilation, and mounting
- Cost tracking and documentation
- Photo documentation of installation

**Excluded (Deferred to Phase 2)**
- Remote monitoring / telemetry
- Edge compute node (Lenovo)
- Automated logging
- Additional battery capacity

---

## 3. System Overview (Phase 1)

### Load
- Starlink (approx. 70 W, continuous)
- Lenovo computer excluded from backup load

### Storage
- 2 × Car batteries (12 V, ~90 Ah each)
- Parallel configuration (12 V system)

### Charging
- Grid-powered smart charger (night)
- Solar charging (day) via MPPT

### Core Components
- Victron MPPT
- Victron Shunt
- Inverter (Luxorparts)
- Existing + new solar panels

---

## 4. Installation Summary

- Batteries mounted with ventilation and physical protection
- Cabling sized for safety and future expansion
- Solar panel installed using tested mounting method
- Inverter configured with low-voltage protection
- Starlink isolated as sole backup load

Photos are stored in:
`/phase_01/photos/`

---

## 5. Energy Expectations (Initial)

Estimated:
- Battery capacity: ~2.1 kWh nominal
- Usable energy (conservative): ~1.2–1.4 kWh
- Expected backup runtime for Starlink: **10–14 hours**

Actual performance to be monitored during stay.

---

## 6. Costs (Phase 1)

> Final numbers tracked separately in `costs.md`

Notable observation:
- Local car batteries significantly more expensive than expected
- Decision made to limit Phase 1 to two batteries

---

## 7. Monitoring During This Trip

- Manual observation of:
  - Battery voltage
  - Charge/discharge behavior
  - Solar contribution
- Family involvement in daily checks
- Notes recorded for future tuning

---

## 8. Lessons Learned (Initial)

(To be filled during and after installation)

---

## 9. Phase 2 — Next Trip (Preview)

Planned upgrades:
- Internet-connected monitoring (Victron)
- Edge compute node enclosure (Lenovo)
- Scalable battery architecture
- Extended AC distribution to annex

Phase 1 is considered **successful** if Starlink remains online during outages.

---

## 10. Status

Phase 1 is:
- [ ] Planned
- [x] Being implemented
- [ ] Completed
- [ ] Reviewed

