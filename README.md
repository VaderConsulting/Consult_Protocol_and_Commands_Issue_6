# Consult_Protocol_and_Commands_Issue_6

Historical working folder for Nissan Consult ECU protocol research. The primary content is the Reference Info set of Consult Protocol and Commands PDFs (Issues 5, 6, and 7) plus a generic Nissan ECU sensor/data register table, kept for catalogue and bench reference. A `ConsultComms` directory is present only as an empty Subversion working-copy stub (original remote was the diagz ConsultComms trunk); no application sources remain there. The tree also includes a tiny Visual Studio 2008 AnkhSVN smoke-test WinForms app (`HelloSVN-VBApp`) that shows a "Hello SVN" message box and is not the subject of this archive.

**Source last updated:** 2009-07-05  
**Language:** documentation (PDF) plus VB.NET test stub  
**Target:** .NET Framework 3.5 (HelloSVN-VBApp only)  
**Output:** reference documents; WinExe test project

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Reference Info` | PDF / image | documentation | Consult Protocol and Commands Issues 5-7 and Nissan ECU register table |
| `ConsultComms` | - | empty SVN stub | Former diagz ConsultComms working copy; no source files retained |
| `HelloSVN-VBApp` | VB.NET | WinForms exe | AnkhSVN / VS 2008 checkout smoke test (`Test/VS08Test`) |

## How to open

- Open the PDFs under `Reference Info/` for the Consult protocol material.
- For the optional test app, open `Test/VS08Test/VS08Test.sln` in Visual Studio.

## Requirements

- PDF reader for the Reference Info documents
- Visual Studio 2008 (optional, for `HelloSVN-VBApp` only)
- .NET Framework 3.5 (optional, for `HelloSVN-VBApp` only)

## Attribution and provenance

- Consult Protocol and Commands documents and the generic Nissan ECU register table are third-party / community diagnostic references retained for study; authorship stays with the original authors.
- `ConsultComms` previously tracked `https://www.zedhead.net:8443/svn/diagz/trunk/ConsultComms` (Subversion); no code remains in this GitHub tree.
- HelloSVN-VBApp assembly metadata lists company Microsoft / Copyright (c) Microsoft 2009.
- Working copy from Dave Robinson's Historical Dev archive. See `THIRD_PARTY_NOTICES.md`.

## License

Original license terms apply to third-party documents and any retained package metadata. This repository does not claim authorship of the Consult PDFs or remote ConsultComms sources. See `THIRD_PARTY_NOTICES.md` and `LICENSE`.
