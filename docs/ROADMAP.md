# Development Roadmap

The roadmap is organized around demonstrations that produce usable integration evidence. Dates will be added after the available hardware and software baseline is inventoried.

## Phase 0 — Define the contract

- [ ] Select the minimum common observation fields
- [ ] Define mission, platform, sensor, and operator identifiers
- [ ] Choose initial geospatial formats and coordinate conventions
- [ ] Define event severity and communications priorities
- [ ] Document platform safe states and authority boundaries
- [ ] Select the initial licensing approach

**Exit condition:** two simulated platform adapters can publish compatible observations into one mission record.

## Phase 1 — Grimhild field core

- [ ] Deploy offline map service
- [ ] Deploy local mission database
- [ ] Provide a common operating picture
- [ ] Ingest MAVLink position and vehicle health
- [ ] Store media with timestamp and location metadata
- [ ] Add local user authentication and an audit log
- [ ] Demonstrate operation with external internet disconnected

**Exit condition:** Grimhild can plan, monitor, record, and replay a single-vehicle mission entirely offline.

## Phase 2 — First integrated search

- [ ] Fly a UAV mapping/search route
- [ ] Produce a georeferenced map or observation layer
- [ ] Flag an item of interest
- [ ] Retask a USV or UGV for close inspection
- [ ] Correlate observations from both platforms
- [ ] Generate a concise mission report with provenance

**Exit condition:** one operator completes an air-to-surface or air-to-ground search handoff without manually reconciling disconnected files.

## Phase 3 — CALI/NOMAD assistance

- [ ] Index local procedures, maps, and mission history
- [ ] Add coverage-gap detection
- [ ] Add anomaly triage with visible confidence
- [ ] Distinguish measured facts, model inference, and operator conclusions
- [ ] Support natural-language mission queries
- [ ] Benchmark local models on available Grimhild hardware

**Exit condition:** offline assistance reduces operator workload while preserving traceability and human mission authority.

## Phase 4 — Resilient communications

- [ ] Establish the field mesh baseline
- [ ] Add bandwidth-aware message priorities
- [ ] Implement store-and-forward observation transfer
- [ ] Test loss and recovery of individual links
- [ ] Add optional Starlink/cellular backhaul
- [ ] Synchronize Grimhild with House CALI after reconnection

**Exit condition:** the mission continues safely through backhaul loss and later reconciles records without silent conflicts.

## Phase 5 — Disaster-response exercise

- [ ] Create a hurricane/flood scenario
- [ ] Create a building-collapse scenario
- [ ] Include UAV, UGV, USV, ROV, and human-team roles
- [ ] Record deployment time and search coverage
- [ ] Measure false alarms, missed areas, bandwidth use, and operator workload
- [ ] Publish an after-action report and revised requirements

**Exit condition:** a documented field exercise demonstrates useful multi-domain coordination and identifies the next engineering priorities.

## Backlog

- Thermal/visual survivor-cue fusion
- Acoustic victim-location nodes
- LiDAR and photogrammetry change detection
- Sonar target classification and revisit planning
- ROV tether and launch/recovery tracking
- Remote ID and airspace-awareness integration
- Multi-team evidence controls
- Simulation and hardware-in-the-loop testing
- Standards mapping for public-safety interoperability
- A tastefully restrained “Thunderbird 3” status panel
