#  CORS Misconfiguration PoC — Neon Whisper

**This repository is a vulnerability publication for security research and defensive education only.**

A proof-of-concept demonstrating how a permissive `Access-Control-Allow-Origin: *` header combined with missing authentication and rate limiting allows an attacker to spam a web form from any external origin, along with the CORS vulnerability, Thrillshare upon a malformed request returns an error code 429 containing all unanswered question IDs in the response headers, so parsing those can let users automatically spam input fields without having to get the question ID's manually, this is outlined in the demo hosted on Github Pages.

---

## Disclaimer

The code and examples in this repository are provided **for educational and authorised security testing purposes only**.  
Unauthorised use of this software against systems you do not own or have explicit permission to test is **illegal** and may violate computer fraud and abuse laws in your jurisdiction.

The author(s) assume **no responsibility or liability** for any misuse, damage, or legal consequences resulting from the use of this code. By using any part of this repository, you agree that you are solely responsible for your actions.

---

## License

All code and examples in this repository are released under the MIT License.
