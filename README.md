# Thrust-Vectoring EDF TVC System

A dual-axis thrust vectoring control (TVC) nozzle system designed for the **X-FLY-MODEL 80mm 12-Blade EDF** with **3665 KV2300 Pro motor**.

Engineered for RC jet applications. Designed to be fully 3D printable on a **Bambu Lab A1**.

---

## Project Goal

Design, prototype, and validate a lightweight, serviceable, dual-axis TVC nozzle that can be mounted to an 80mm EDF unit — providing pitch and yaw thrust vectoring for enhanced RC jet maneuverability and stabilization.

---

## Development Phases

This project follows a structured, milestone-gated engineering process. No CAD work begins until Phase 0 is complete and approved.

| Phase | Milestone | Description |
|-------|-----------|-------------|
| **Phase 0** | Architecture Review | Research, trade studies, requirements freeze |
| **Milestone 1** | Core Architecture Complete | Final architecture selected and documented |
| **Milestone 2** | CAD Prototype V1 | First full CAD model complete |
| **Milestone 3** | Mechanical Validation | Kinematic and structural analysis |
| **Milestone 4** | Print Prototype V1 | First physical print |
| **Milestone 5** | Bench Testing | Static thrust, servo, and deflection testing |
| **Milestone 6** | Flight Testing | Live airframe integration and flight validation |
| **Milestone 7** | Production Release V1 | Final design released |

---

## Hardware Targets

| Component | Spec |
|-----------|------|
| EDF Unit | X-FLY-MODEL 80mm 12-Blade |
| Motor | 3665 KV2300 Pro |
| Printer | Bambu Lab A1 |
| TVC Axes | Dual-axis (pitch + yaw) |
| Architecture | TBD — pending Phase 0 trade study |

---

## Repository Structure

```
/docs
  Architecture_Review.md   <- Phase 0 deliverable
  Requirements_Freeze.md   <- Phase 0 deliverable
  Trade_Study.md           <- Phase 0 deliverable
  Risk_Assessment.md       <- Phase 0 deliverable
/cad                       <- CAD files (unlocked after Phase 0 approval)
/prints                    <- Print profiles and settings
/test                      <- Test logs and data
```

---

## Engineering Process

This project enforces a **gate-based design process**:

- No CAD modeling begins until Phase 0 is complete
- Each phase requires documented deliverables before the next begins
- All major design decisions are made before geometry is created

---

## Status

> **Current Phase: Phase 0 — Architecture Review**
> CAD work is locked until this phase is complete and documented.

---

## License

MIT