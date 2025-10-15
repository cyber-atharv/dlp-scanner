# Changelog

All notable changes to dlp-scanner are documented here.

### [2025-12-19]
- test: verify backward compatibility with legacy message format

### [2025-12-19]
- security: enforce strict bounds checking on dynamic byte slices

### [2025-12-31]
- perf: minimize redundant heap allocations in hot loop

### [2026-01-12]
- style: clean up trailing whitespace and fix alignment

### [2026-01-26]
- security: sanitize input strings to mitigate format string risks

### [2026-01-28]
- fix: handle malformed HTTP header parsing without crashing

### [2026-01-30]
- refactor: use enum types for status codes instead of magic numbers

### [2026-02-09]
- fix: handle nil pointer dereference on unexpected connection close

### [2026-03-14]
- perf: parallelize independent batch verification tasks

### [2026-03-23]
- fix: resolve memory leak in idle connection reaper

### [2026-03-29]
- test: add unit tests for boundary input cases and error branches

### [2026-04-17]
- refactor: extract validation logic into dedicated helper module

### [2026-05-17]
- fix: ensure file descriptors are properly closed on error exits

### [2026-05-23]
- docs: add example configuration commands to quickstart guide

### [2026-06-11]
- chore: streamline build flags and compiler optimization settings

### [2026-07-09]
- fix: prevent duplicate event emission during rapid retry bursts

### [2026-07-11]
- docs: add example configuration commands to quickstart guide

### [2026-07-25]
- fix: ensure file descriptors are properly closed on error exits

### [2026-08-28]
- test: verify backward compatibility with legacy message format

### [2026-09-06]
- fix: patch edge-case buffer truncation in stream reader

