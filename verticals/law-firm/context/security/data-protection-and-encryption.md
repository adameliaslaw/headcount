## Client files are the data

A practice's sensitive data is not scattered across systems that need finding; it is the client
file, and all of it is sensitive. An estate plan holds Social Security numbers, account numbers,
the family's conflicts, a health care directive and the client's view of each child. The
classification exercise collapses to one class — client-identifying matter content — and the
controls follow from treating everything in the file as that class.

- **Say which threat each control answers.** Provider-managed encryption at rest on a cloud drive
  answers disk theft, not a compromised login or an over-shared folder; those are answered by
  identity controls and by sharing that is scoped to the matter and rechecked when a link is
  opened. A local database that holds a regeneration copy of client intakes is inside the
  machine's boundary and only as protected as the machine; say so in the data boundary rather
  than calling it encrypted.
- **Fictional matters for every test.** Templates, renderers, emulators and demos run on invented
  clients. A real client's data never seeds a test environment, a fixture or a screenshot.
- **The log carries identifiers, not people.** The record of what was drafted, reviewed and
  released names matter ids, versions and actors, never a client, a creditor or an amount.
- **AI features are data exits.** Mail, document, meeting and transcription platforms now carry
  built-in AI features with sharing, retention and training settings that default on; the
  New Jersey Supreme Court's 2026 model policy requires each to be reviewed and turned down
  before firm work touches it. Treat each feature as a new vendor.
- **Keys and secrets live outside the file.** Service credentials for the firm's systems belong
  in a secret manager, rotated on staff departure, and a credential that ever reached a repository
  is rotated, not deleted.
- **Devices are the perimeter in a small firm.** Full-disk encryption on every laptop and phone,
  a remote-wipe capability, and a sign-out that ends each day, so that a device lost on a train
  is a device and not a file.
