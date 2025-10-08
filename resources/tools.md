# Tools — Natas / OverTheWire (reference)

> Note: Use all these tools **only** on authorized targets (OverTheWire, private labs). Never use them on other systems without permission.

---

## 1. Operating Systems & Distros
- **Kali Linux**
A Linux distro that comes pre-packaged with many pentest tools. Useful as a ready-to-use work environment.
- **Parrot OS**
A lightweight alternative with a focus on privacy and pentesting.
- **Ubuntu / Debian**
Suitable for setting up a minimal environment and installing tools as needed.

---

## 2. Browsers & Extensions
- **Browser (Chrome / Firefox)**
For page inspection, DevTools, and manual testing.
- **Firefox Developer Edition** — more comprehensive dev features.
- **Extensions:**
- *Web Developer* (toolbar utilities)
- *Cookie Editor* (quick cookie editing)
- *ModHeader* (change request headers)
- *Wappalyzer* (identify web technologies)

---

## 3. Intercepting proxies / Web proxies
- **Burp Suite (Community / Pro)**
Intercept, modify, and replay HTTP(S). Very useful for request/response manipulation.
*Free alternatives:* **OWASP ZAP**, **mitmproxy**, **Fiddler**.
- **OWASP ZAP**
Open-source, has a scanner and proxy.
- **mitmproxy**
Terminal-based proxy, great for scripting.

---

## 4. Small HTTP clients and testing
- **curl** — fast requests from the terminal.
- **httpie** — a more user-friendly curl.
- **Postman** — GUI for creating and repeating requests.

---

## 5. Repeater / manual tools
- **Burp Repeater** — repeat requests and try variations.
- **Repeater-like tools:** `curl` + shell script or `httpie`.

---

## 6. Scanners & automation (use with caution)
- **nikto** — simple server/web scanner.
- **wpscan** — WordPress scanner.
- **sqlmap** — automated SQL injection testing (use ethically/controlled).

---

## 7. Fuzzing / brute-force
- **wfuzz**, **ffuf** — fuzzing parameters and directories.
- **hydra**, **medusa** — bruteforce (for authorized labs only).

---

## 8. Encoding/Decoding/Utilities
- **base64**, **xxd**, **hexdump**, **strings** — for data analysis and encoding.
- **openssl** — certificate manipulation, base64, etc.
- **jq** — JSON parsing in the terminal.

---

## 9. CLI Text Tools (Essential)
- **grep**, **sed**, **awk**, **cut**, **tr**, **sort**, **uniq** — text output manipulation.
- **less**, **more**, **cat** — file reading.

---

## 10. Binary/File Analysis (if needed)
- **file**, **strings**, **exiftool** — file and metadata identification.
- **binwalk** — binary file/embedded data analysis.

---

## 11. Network Tools
- **netcat (nc)** — fast TCP/UDP connections.
- **nmap** — port scan & service enumeration (lab-only).
- **tcpdump / tshark** — packet capture & inspection (lower-level).

---

## 12. For web exploitation helpers
- **Burp Extensions** (BApp Store) — additional functionality (decoders, scanners).
- **jsbeautifier / prettier** — tidy up JS/HTML for reading.
- **DOM tools** — inspect DOM & client-side logic.

---

## 13. Scripting / automation languages
- **Python** (3.x) — primary scripting (requests, beautifulsoup, pwntools for pwn).
- **Bash** — simple automation & chaining commands.
- **Ruby / Perl** — some older tools use this.

---

## 14. CLI password/secret scanning (prevention)
- **detect-secrets**, **git-secrets** — help prevent committing credentials to the repo.

---

## 15. Editors/IDEs
- **VSCode** — lightweight, lots of extensions.
- **Vim/Neovim** — fast in the terminal.
- **Sublime/Atom** — alternative editors.
- **Cursor** — has built-in AI.

---

## 16. Useful workflows/example tools for Natas
- Start: **browser DevTools** → observe form/response.
- If needing to intercept: run **Burp** (proxy) → set browser proxy.
- For quick requests: use **curl/httpie**.
- For encoding checks: `base64` / `xxd` / `jq`.
- For text processing: combine `grep`, `sed`, `awk`.