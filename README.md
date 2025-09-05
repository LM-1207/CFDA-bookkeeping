# Allocator Bookkeeping Repository for CFDA

## Allocator JSON Link
[CFDA Allocator JSON](https://github.com/filecoin-project/Allocator-Registry/blob/main/Allocators/recR7wcgfv0cbrXgb.json)

## Client Diligence
We apply a comprehensive, multi-layered diligence process to establish client trust and mitigate abuse:

1. **Client Verification & Initial Trust Establishment**
   - All clients must complete KYC (for individuals) or KYB (for businesses) through a trusted third-party provider (e.g., Toggle).
   - Required submissions include:
     - Government-issued ID (for individuals) or company registration documents (for businesses)
     - Project overview, including public website, GitHub repository, and/or white paper
     - Description of dataset type, size, structure, and relevance to Filecoin Plus
     - All private information is used exclusively for identity verification and stored securely.

2. **Sybil Attack Mitigation**
   - Only one active allocation is permitted per verified legal entity.
   - Verification of GitHub and Slack accounts to confirm participation in the ecosystem.
   - Facial recognition and ID document checks through third-party KYC tools.
   - Rate limit enforced: one application per entity every 30 days.
   - IP address and submission metadata monitoring to detect duplicates.

3. **Enterprise or Paying Client Ownership Verification**
   - KYB verification must include business name, incorporation details, and executive team.
   - Required documentation includes:
     - A valid business license
     - Signed and stamped authorization letter from CEO or director
     - A 20% sample of the dataset with CIDs or links
     - Proof of presence within the Filecoin ecosystem (e.g., website, prior deals)

4. **Auditable Diligence Evidence for Governance**
   - All verification records, project materials, and authorization letters are securely stored and available for audit.
   - For any equity holder with ≥20% stake, stakeholder KYC is required and the Ultimate Beneficial Owner (UBO) must be identified.

## Description of Data Diligence
We conduct robust data diligence to ensure program scope alignment, regional compliance, and ownership authenticity:

1. **Project Scope Validation**
   - Clients must clearly describe dataset type (e.g., scientific, public, enterprise), size, structure, and relevance to Filecoin Plus.
   - Submission of a 20% data sample via CIDs or download links is mandatory.

2. **Data Ownership Verification**
   - Proof of ownership or custodianship must be provided (e.g., license, source, or publication).
   - Open datasets require public URLs; proprietary datasets require a signed authorization letter.
   - Enterprise clients must provide a CEO/director-signed and stamped authorization letter.
   - Dataset legitimacy may be cross-checked via public or third-party channels.

3. **Legal & Regional Compliance**
   - Clients in Asia are assessed under applicable regional data laws (e.g., China PIPL, Data Security Law).
   - Clients in other regions must submit a data compliance self-assessment.
   - Additional legal documents or exemption certificates may be required as needed.

4. **Data Sampling & Matching**
   - Clients must submit a 20% dataset sample.
   - After allocation, we use Lotus or Boost to retrieve on-chain data via pieceCIDs.
   - Retrieved content is compared to declared data for file type, format, and content consistency.
   - Sample content that is filler or duplicated results in disqualification.

5. **Verification Tools Used**
   - `datacapstats.io` for allocation tracking.
   - `CID Check Bot` for replica and deal verification.
   - `AC Bot` for allocation-deal matching.
   - Optional tools: SPARK or custom scripts for retrievability and structure verification.

6. **Auditable Proof for Governance**
   - Evidence maintained includes: project overview, ownership proofs, sample data (CIDs or links), Lotus logs, matching records, screenshots, file hashes, and on-chain metadata (pieceCID, dealID, SP ID, file size).
   - Historical compliance tracking ensures transparency and auditability.

## Short description of pathway for clients
CFDA offers a security-first, transparent, and governance-driven pathway for clients seeking DataCap. We emphasize diligent KYC/KYB protocols, rigorous data ownership verification, and adherence to Filecoin Plus objectives. Clients benefit from strong retrievability standards, multi-country storage provider distribution, and thoroughly auditable governance frameworks. Ideal for scientific, public-interest, or enterprise datasets seeking trustworthy long-term storage on Filecoin.

## Contact info
- **GitHub**: [LM-1207](https://github.com/LM-1207)  
- **Slack**: lmmm  
- **Email**: lium@chimsen.com  

- **Bookkeeping Repository**: [CFDA Bookkeeping](https://github.com/LM-1207/CFDA-bookkeeping)

## Detailed Allocator policies, procedures, and requirements.
- **SP Distribution & Data Retrievability**
  - Allocate 5 PiB across at least 5 Storage Providers (SPs), with each SP receiving ≤ 0.5 PiB.
  - Ensure SPs are located in at least 3 different countries.
  - Client allocations range from 50 TiB to 500 TiB.
  - At least 90% of deals must span a minimum of 3 countries.
  - Target average Retrievability (RSR) > 75%; no SP may have RSR < 50% for two consecutive weeks.
  - Weekly audits via SPARK; bi-monthly RSR reports are published in the bookkeeping repository.

- **Replication Health**
  - Require each allocation to have at least 5 verified replicas.
  - Maintain a minimum 95% retrievability rate across all replicas.
  - Use CID Check Bot and AC Bot for weekly monitoring and verification.

- **Client Due Diligence Pass Rate**
  - Aim for a 90% KYC/KYB pass rate.
  - Target 80% of clients to pass verification on their first submission.
  - Enforce strict adherence to allocation size constraints (50–500 TiB).

## Risk mitigation strategies
- Enforce robust KYC/KYB with reputable third-party providers.
- Implement one-allocation-per-entity policy with a 30-day cooldown period.
- Monitor IP addresses and metadata for detection of suspicious patterns.
- Combine automated abuse detection with mandatory manual review for final approval.
- Maintain transparent reporting via public GitHub postings and secure storage of all diligence artifacts.

## Dispute Resolutions
- **Internal disputes** are handled through direct communication and review with the client.
- **External disputes** involving peer allocators or the Fil+ Governance Team will be addressed with comprehensive diligence records and on-chain proofs.
- Disputes may relate to DataCap allocation, data compliance, or execution of storage deals.
- Every decision will be supported by auditable records to preserve fairness and accountability.

## Compliance Audit Check
- We conduct regular audits of client allocations, SP retrievability, and replication integrity.
- Ongoing monitoring is performed using datacapstats.io, CID Check Bot, AC Bot, and SPARK.
- Historical records of client compliance are tracked continuously.
- All diligence documentation is securely stored and shared with the Governance Team upon request.
