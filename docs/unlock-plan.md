# Drive-unlock build plan (scratch note)

Workflow: .github/workflows/build-unlocked-apks.yml

Patches android:appCategory away from the parked "game" category so the AA head-unit
allows the apps while driving. Keystore: .keystore/rsa.jks (alias unlocked, pass android).
