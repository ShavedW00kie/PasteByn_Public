SECTION 7. REVOCATION.

(a) An individual may revoke a license granted under this part at any time. Revocation must be no more difficult than the method by which the license was granted, and must be honored through any universal opt-out or revocation signal recognized under [Module 8].

(b) Revocation operates prospectively. It does not require return of compensation lawfully paid for processing that occurred before revocation, and it terminates a controller's authority to engage in new processing, sale, or sharing of the individual's data from the moment of revocation forward.

(c) Within 45 days of a valid revocation request, a controller shall: (1) cease processing under the revoked license; (2) notify every downstream holder identified under [Module 5] and direct equivalent cessation; and (3) delete or sanitize the data from active systems and reasonably accessible backups, consistent with then-current NIST Special Publication 800-88 guidance or successor federal standard.

(d) Where personal data has already been used to train a machine- learning or artificial-intelligence model prior to revocation, the controller shall exclude that data from any subsequent training run or model release, and shall remove any output that reproduces the individual's data verbatim or in identifiable form, regardless of the model's underlying architecture.

A controller that trains a model using an architecture capable of isolating and removing specific training data without full retraining (including but not limited to partitioned or shard-based training methods) shall use that capability to fully remove the individual's data upon revocation.

A controller is excused only from removing a revoked individual's residual statistical influence from a model that was already fully trained, using an architecture not capable of isolated removal, before the revocation request — and only where the controller can show that full retraining was not commercially reasonable at the time of the request. This subsection creates no defense based on a controller's choice not to adopt an architecture capable of isolated removal for models trained after this Act's effective date.
