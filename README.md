# RallyForge v3 — G1 table-tennis research

Reproducible local MuJoCo experiments: continuous two-G1 rallies, rendered RGB-D ball tracking, contact odometry from encoders and ideal IMU, and an ARM64 ROS 2 standby balance component.

The ARM64 image is **standby balance only**. The current standard builder-kit runner supplies no camera stream; this image is not a qualified table-tennis deployment or hardware authorization. Unsupported initial poses are refused before arming. All required camera, calibration and transfer assumptions are documented in the source package.

V3 source, measured results, complete trial outcomes, replay traces, attribution and the actual demonstration video will accompany the Arena submission and this release. The published v2 remains at https://arena.himrobotics.com/uploads/source_8d209a302d516e343037 .

Original additions extend Alpslee/willli MIT forehand control and HiroakiMachida MIT evaluation, with attributed Unitree robot/gait assets. The separate standby component exports the builder kit's NVIDIA balance network to NumPy; its NVIDIA Open Model License and provenance are retained. This project does not claim a newly trained whole-body policy or measured superiority over competitors.

Runner archive: `RallyForge-G1-standby-arm64.tar.gz`. Use `g1-runner.json` from the final source package for the public download URL and SHA-256. Run only with the builder kit's enabled safety checks in isolated local simulation. Physical use requires separate qualification.
