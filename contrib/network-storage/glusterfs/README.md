# Removed

The `glusterfs` playbook created a single GlusterFS `PersistentVolume` (PV), which is not what most users want.

See the `heketi` playbook instead which allows dynamic provisioning of volumes using `PersistentVolumeClaim`s (PVCs).
