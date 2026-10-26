# Auto Performance Optimizer - signed releases

Update channel for the plugin (`stable.json` = production, `beta.json` = staging).
Every zip in `zips/` carries an Ed25519 signature (`.sig`); the plugin refuses any update whose signature does not verify.
