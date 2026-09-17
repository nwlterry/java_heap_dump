# java_heap_dump

Split archive of Eclipse Memory Analyzer (MAT) 1.16.1 (Linux GTK x86_64, 2025-01-09 build) for analyzing Java heap dumps.

GitHub file size limits required splitting the zip.

## Files

- `MemoryAnalyzer-1.16.1.20250109-linux.gtk.x86_64.zip.zip.001` … `.005`

## Reassemble

On Linux:

```bash
cat MemoryAnalyzer-1.16.1.20250109-linux.gtk.x86_64.zip.zip.00* > MemoryAnalyzer.zip
unzip MemoryAnalyzer.zip
```

On Windows PowerShell:

```powershell
Get-Content MemoryAnalyzer-1.16.1.20250109-linux.gtk.x86_64.zip.zip.00* -Enc Byte -Read 0 | Set-Content MemoryAnalyzer.zip -Enc Byte
```

Prefer `copy /b *.001+*.002+*.003+*.004+*.005 MemoryAnalyzer.zip` in cmd if the PowerShell byte join is slow.
