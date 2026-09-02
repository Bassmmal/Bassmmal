<div>

  <!-- Title: Low-Level Memory Pointer Cyan -->
  <svg width="650" height="42" viewBox="0 0 650 42" xmlns="http://www.w3.org/2000/svg">
    <text x="50%" y="28" text-anchor="middle" font-family="Consolas, 'Courier New', monospace" font-size="22" font-weight="bold" fill="#00E5FF" letter-spacing="1">
      ⚡ Security Researcher &amp; Systems Engineer
    </text>
  </svg>

  <br />

  <!-- Subtitle: Terminal Phosphor Green -->
  <svg width="780" height="30" viewBox="0 0 780 30" xmlns="http://www.w3.org/2000/svg">
    <text x="50%" y="20" text-anchor="middle" font-family="Consolas, 'Courier New', monospace" font-size="14" font-weight="600" fill="#39D353">
      [+] Windows Internals • Offensive Tooling • Threat Research • Reverse Engineering
    </text>
  </svg>

  <p align="center">
    <a href="https://linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://x.com/YOUR_HANDLE"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X/Twitter" /></a>
    <a href="mailto:your_email@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>

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
