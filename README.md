# Task 7 :Identify and Remove Suspicious Browser Extensions

## Objective
Learn to spot and remove potentially harmful browser extensions.

---

##  Audit Steps Followed

1. **Opened Browser’s Extension/Add-ons Manager**  
   - Chrome: `chrome://extensions/`  
   - Edge: `edge://extensions/`

2. **Reviewed All Installed Extensions Carefully**  
   Checked names, functionality descriptions, developer info, install counts, and any verification badges.

3. **Checked Permissions and Public Reviews**  
   - Focused on extensions requesting broad access (e.g., “Read and change all your data on websites”).  
   - Read user reviews to spot any reports of odd behavior.

4. **Identified Unused or Potentially Suspicious Extensions**  
   Listed extensions that either seemed unnecessary or were flagged in external reports (like Malwarebytes), even if they appeared safe after checking.

5. **Removed Suspicious or Unnecessary Extensions**  
   Uninstalled any extensions that lacked a clear purpose or raised red flags—even if they were ultimately benign.

6. **Restarted Browser & Monitored Performance**  
   Verified that startup time improved, no unusual pop-ups appeared, and browsing behavior remained normal.

7. **Researched How Malicious Extensions Can Harm Users**  
   - Sleeper agents capture URLs, send them to command & control servers, and may redirect browsers to fake pages :contentReference[oaicite:2]{index=2}.  
   - Even highly-rated extensions can become malicious later via updates :contentReference[oaicite:3]{index=3}.

8. **Documented Steps Taken & Extensions Removed**  
   Created a table of actions with placeholders for screenshots, for clarity and audit trail.

---

##  Sample Documentation Table
| Extension Name                 | Browser | Permissions Requested         | Review Notes                               | Action Taken |
|--------------------------------|---------|--------------------------------|---------------------------------------------|--------------|
| Emoji keyboard online          | Chrome  | Standard input access          | Flagged in Malwarebytes, no malicious signs | Kept         |
| Free Weather Forecast          | Chrome  | Location, weather data         | Flagged in Malwarebytes, no malicious signs | Kept         |
| Unlock Discord                 | Chrome  | Site access to Discord         | Flagged in Malwarebytes, no malicious signs | Kept         |
| Dark Theme                     | Chrome  | Modify site appearance         | Flagged in Malwarebytes, no malicious signs | Kept         |
| Volume Max                     | Chrome  | Audio control                  | Flagged in Malwarebytes, no malicious signs | Kept         |
| Unblock TikTok                  | Chrome  | Site access to TikTok          | Flagged in Malwarebytes, no malicious signs | Kept         |

---

##  Screenshots  
One example screenshot with the permission showing,
<img width="800" height="700" alt="Screenshot 2025-08-14 191605" src="https://github.com/user-attachments/assets/0bfbcc43-12b8-4c0a-b8e2-13a5a13cc728" />

---
## How Malicious Browser Extensions Can Harm Users

Malicious extensions can operate with high privileges inside your browser, often without the user’s knowledge. The main ways they can cause harm include:

1. **Tracking and Profiling**  
   - Monitor every site you visit.  
   - Build a profile of your browsing habits and sell the data to third parties or use it for targeted attacks.

2. **Data Theft**  
   - Steal personal information such as login credentials, email content, payment information, or private messages.  
   - Capture clipboard contents, which might contain sensitive data like passwords or crypto wallet addresses.

3. **Web Page Manipulation**  
   - Inject malicious JavaScript into legitimate sites.  
   - Replace links or ads to redirect traffic to phishing or malware sites.  
   - Alter page content to trick you into taking harmful actions (e.g., fake login prompts).

4. **Remote Control (Sleeper Agents)**  
   - Extensions can be remotely updated with new code by the developer or attacker.  
   - An initially safe extension can turn malicious later without the user noticing.

5. **Redirects and Ad Injection**  
   - Force the browser to load unwanted pages or open pop-ups with scams, adult content, or fake download prompts.

6. **Bypassing Security Protections**  
   - Modify HTTP headers to bypass CORS, CSP, or other browser-level protections.  
   - Act as a proxy to intercept and alter network traffic.

7. **Persistence and Evasion**  
   - Some malicious extensions can disguise themselves as system components or hide their real code in obfuscated scripts, making removal harder.

**Key Takeaway:**  
Even extensions with high ratings and millions of downloads can become malicious if their developers are compromised or decide to monetize user data. Regular reviews and permission checks are essential.

---

##  Key Concepts  
- **Sleeper Extensions**: Initially clean extensions that become malicious after updates :contentReference[oaicite:5]{index=5}.  
- **Supply-Chain Attacks in Extensions**: Attackers hijack trusted extensions to deliver malware at scale :contentReference[oaicite:6]{index=6}.  
- **Permission Abuse**: Broad access permissions can be misused for tracking or remote redirects :contentReference[oaicite:7]{index=7}.

---
