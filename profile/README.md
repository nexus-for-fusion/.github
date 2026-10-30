## Configuration and master data migration for Oracle Fusion Cloud, with review, approval and proof

Nexus finds what differs between two Oracle Fusion Cloud environments, lets the right people review and approve exactly those records, writes them into the target through Oracle's own import and REST interfaces, and reads the target back to prove the change landed. No re-keying, no all-or-nothing exports, no blind approvals.

- **Discover** what changed, field by field, in configuration and in master data such as suppliers and lookups.
- **Review** the records as a changeset: keep what should move, set aside what should not, with the reason kept.
- **Approve** on a route that fixes the source and target pair, with the exact records on screen.
- **Deploy** through Oracle's CSV import and REST services, parents first, every record with Oracle's own response.
- **Verify** by reading the target back after the deployment.

## Start here

- [Overview](https://github.com/nexus-for-fusion/docs#readme) · what it does and why
- [Walkthrough](https://github.com/nexus-for-fusion/docs/blob/main/docs/walkthrough-suppliers.md) · three suppliers moved between two environments, with screenshots
- [Getting started](https://github.com/nexus-for-fusion/docs/blob/main/docs/getting-started.md) · a proof of concept in one to two hours with two development pods and a 30-day trial key
- [Contact](mailto:SatishM@techprojects.com) · ask for a trial key or a walkthrough call

## Who it is for

Oracle Fusion Cloud application teams, release managers and finance or procurement system owners who move setup and master data between development, test, UAT and production and want it done once, reviewed, approved and auditable.

---

*Nexus is an independent product and is not affiliated with, endorsed by, or sponsored by Oracle. Oracle and Oracle Fusion Cloud are trademarks of Oracle Corporation and its affiliates.*
