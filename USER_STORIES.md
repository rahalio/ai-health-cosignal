# Cosignal — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Attending physician

- As an attending, I want the drafted note to arrive with the specific claims it asserts traceable to where they came from in the chart, so that reviewing it is faster than writing it but still an act of judgement.
- As an attending, I want my edits captured as edits rather than silently absorbed, so that the record shows what I changed and the system learns from it.
- As an attending, I want drafted orders presented as proposals I sign, never as orders already placed, so that my licence is never exercised without me.
- As an attending, I want a cap on how often drafts interrupt me during rounds, so that the tool cannot degrade the care I am giving the patient in front of me.
- As an attending supervising a resident, I want to see which drafts the resident dispositioned under my supervision, so that supervision is real rather than nominal.

### Registered nurse

- As a nurse, I want the time this system claims to save physicians netted against the work it sends to me, so that a system-level win is not a unit-level loss.
- As a nurse, I want drafted patient messages and symptom triage dispositions to arrive with the patient's own words attached, so that I am not re-interviewing someone the system already interviewed.
- As a nurse, I want to reject a draft as unsafe in one step and see where that rejection went, so that raising a concern is not extra work I do for free.
- As a nurse, I want my recovered minutes reported against my actual scheduled hours, so that the claim is credible to me and to my manager.

### Clinical pharmacist

- As a pharmacist, I want dose and interaction findings routed to me with the patient's renal function, weight, and current regimen in view, so that I can act rather than investigate.
- As a pharmacist, I want a finding type that I override more often than a set threshold suppressed and reviewed, so that my attention is not consumed by a check that is wrong in this population.
- As a pharmacist, I want my interventions attributed to me in the record, so that the value of pharmacy review is visible when staffing is decided.

### Informatics and governance lead

- As an informatics lead, I want each draft type bound to a co-signature rule stating which roles may dispose of it and under what supervision, so that scope of practice is enforced by the system rather than by memory.
- As a governance lead, I want an ageing draft queue past its bound raised as a safety incident, so that a backlog is treated as a hazard and not as a productivity statistic.
- As a governance lead, I want dispositions, unsafe rejections, and linked harm events assembled into the surveillance record for device-classified functions, so that our reporting obligations are met from operational data.

### Coding and billing integrity analyst

- As a billing integrity analyst, I want to see whether a signed note was actually opened and reviewed before attestation, so that we do not bill a level supported by content nobody read.
- As a billing integrity analyst, I want the machine-drafted portion of a note distinguishable from the clinician-authored portion, so that an audit response can be assembled from the record rather than reconstructed.
