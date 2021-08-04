# Docker CI Zap

Simple tool that removes (or "prunes") intermediate data on Windows that is used by Docker. Originated from this thread: [[Windows] windowsfilter folder impossible to delete · Issue #26873 · moby/moby](https://github.com/moby/moby/issues/26873)

```batch
.\docker-ci-zap.exe -folder "C:\ProgramData\docker"
```
