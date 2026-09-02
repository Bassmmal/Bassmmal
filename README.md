<div>

  <h3>Security Researcher & Systems Engineer</h3>
  
  <p>
    <strong>Specialized in Windows Internals • Offensive Tooling • Threat Research • Reverse Engineering</strong>
  </p>

</div>

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
