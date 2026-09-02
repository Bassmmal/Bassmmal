<div align="center">

  <!-- Title: Cyan Monospace Header Badge -->
  <img src="https://img.shields.io/badge/SECURITY_RESEARCHER_&_SYSTEMS_ENGINEER-0d1117?style=for-the-badge&labelColor=0d1117&color=00E5FF&logo=windows-terminal&logoColor=00E5FF" alt="Title" />

  <br /><br />

  <!-- Subtitle: Phosphor Green Monospace Subtitle Badge -->
  <img src="https://img.shields.io/badge/%5B%2B%5D_WINDOWS_INTERNALS_•_OFFENSIVE_TOOLING_•_THREAT_RESEARCH_•_REVERSE_ENGINEERING-0d1117?style=flat-square&labelColor=0d1117&color=39D353" alt="Focus Areas" />

</div>

---

### 🛡️ Runtime Context

```c
typedef struct _RESEARCHER_CONTEXT {
    DWORD dwFocusAreas;             /* WIN_INTERNALS | MALDEV | REVERSE_ENG */
    LPCSTR szPrimaryLanguages[];    /* { "C", "C++", "C#", "Python" }       */
    struct {
        UINT bEvasionResearch  : 1; /* Dynamic API resolution, Hook bypass  */
        UINT bKernelInspection : 1; /* Driver & user-kernel boundary audit  */
        UINT bMemoryForensics  : 1; /* PE analysis, process injection       */
        UINT bReserved         : 29;
    } Capabilities;
    PVOID pTargetEnvironment;       /* Win32 / Native NT Architecture       */
} RESEARCHER_CONTEXT, *PRESEARCHER_CONTEXT;
