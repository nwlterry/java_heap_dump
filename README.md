# java_heap_dump

Split archive of Eclipse Memory Analyzer (MAT) 1.16.1 (Linux GTK x86_64, 2025-01-09) for Java heap dumps.

## Layout

```
packages/MemoryAnalyzer-1.16.1.20250109-linux.gtk.x86_64.zip.zip.001
packages/MemoryAnalyzer-1.16.1.20250109-linux.gtk.x86_64.zip.zip.002
packages/MemoryAnalyzer-1.16.1.20250109-linux.gtk.x86_64.zip.zip.003
packages/MemoryAnalyzer-1.16.1.20250109-linux.gtk.x86_64.zip.zip.004
packages/MemoryAnalyzer-1.16.1.20250109-linux.gtk.x86_64.zip.zip.005
GROUP.md
README.md
```

## Reassemble

```bash
cd packages
cat MemoryAnalyzer-1.16.1.20250109-linux.gtk.x86_64.zip.zip.00* > MemoryAnalyzer.zip
unzip MemoryAnalyzer.zip
```

Windows cmd: `copy /b *.001+*.002+*.003+*.004+*.005 MemoryAnalyzer.zip`

---

See [GROUP.md](GROUP.md) for sibling repositories. Catalog: https://github.com/nwlterry/nwlterry
