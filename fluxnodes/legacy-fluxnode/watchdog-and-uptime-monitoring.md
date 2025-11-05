# Watchdog & Uptime Monitoring

Keep your FluxNode running smoothly with automated self‑healing (Watchdog) and external uptime checks (UptimeRobot).

***

### Watchdog

The **Watchdog** service continuously monitors your node’s core processes (`fluxd`, `syncthing`, etc.), automatically restarts or repairs common failures, and sends alert notifications via Discord or Telegram.

*   **Install or Reconfigure:**

    * Run **Multitoolbox Option 4**:

    <pre class="language-bash"><code class="lang-bash"><strong>multitoolbox
    </strong># then select option 4
    </code></pre>
* **Setup Prompts Include:**
  * Enable or disable **auto‑updates** for FluxOS, `fluxd`, and benchmarks
  * Configure **Discord Webhook URL** and **User ID** for pings
  * Configure **Telegram Bot Token** for messages

> 🔧 If you missed Watchdog during initial install, Option 4 will guide you through full setup or reconfiguration.

***

### UptimeRobot External Monitoring

Use **UptimeRobot** to receive SMS or email alerts if your node’s **API** or **UI** becomes unreachable. You can set up to **50 free monitors** per account—use whichever type(s) suit your needs.

**A. API Keyword Monitor**

Monitors your node’s benchmark status via the API endpoint and alerts on the keyword `failed`.

1. **Create UptimeRobot Account** at [uptimerobot.com](https://uptimerobot.com/)
2. On the **Dashboard**, click **+ Add New Monitor**.
3. **Monitor Type:** Keyword
4. **Friendly Name:** e.g., `FluxNode API Health`
5.  **URL (or IP):**

    ```
    perlCopyEdithttp://<yourIP>:<apiPort>/daemon/getbenchmarks
    ```

    * `<apiPort>` ends in `7` (default `16127`)
6. **Keyword:** `failed`
7. **Case‑Insensitive:** ✓
8. **Monitoring Interval & Timeout:** Your discretion (e.g., 5 min/30 sec)
9. **SSL Options:** Uncheck both
10. **Notifications To:** Select your email/SMS contacts

> 🔄 Replace `<yourIP>` and `<apiPort>` with values from your wallet’s FluxNode section.

***

**B. UI HTTP Monitor**

Checks that your FluxNode web UI is accessible and responsive.

1. On UptimeRobot, click **+ Add New Monitor**.
2. **Monitor Type:** HTTP(s)
3. **Friendly Name:** e.g., `FluxNode UI Access`
4.  **URL (or IP):**

    ```
    php-templateCopyEdithttp://<yourIP>:<uiPort>/
    ```

    * `<uiPort>` is one less than your API port (default `16126`)
5. **Monitoring Interval & Timeout:** Your discretion (e.g., 5 min/30 sec)
6. **SSL Options:** Uncheck both
7. **Notifications To:** Select your email/SMS contacts

> 🌐 If your public IP changes, you can use a DDNS hostname in place of `<yourIP>`.
