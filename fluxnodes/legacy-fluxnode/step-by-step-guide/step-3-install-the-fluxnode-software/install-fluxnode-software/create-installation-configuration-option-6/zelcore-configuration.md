# Zelcore Configuration

**⚠️ Important — Read Before Proceeding**\
When entering your FluxNode details, double‑check every value **before pressing Enter**.\
If you paste incorrect information or make a mistake during this configuration process, the easiest fix is to:

1. **Close the terminal window completely**
2. **Reconnect to your server**
3. **Restart the configuration process** from the beginning of this step

Entering wrong details can cause setup failures or require manual file edits, which is not recommended for new users.

***

### Detailed Step-by-Step Configuration

#### 1. Log in as Your New Non-Root User

* If your SSH session timed out, reconnect via **PuTTY** using your **non‑root username** and its password.

<figure><img src="../../../../../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

#### 2. Open the Flux Multitoolbox

```
multitoolbox
```

* Enter your **sudo password** of the **New Non-Root User** if prompted.

<figure><img src="../../../../../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

#### 3. Select Installation Config File Option

* In the Toolbox menu, select **`6: Create Installation Config File`**.
* Enter your **sudo password** again if prompted.

<figure><img src="../../../../../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

#### 4. Choose Manual Setup

* Select **`1 - Manually - Fill Questions List`**.
* Press **Enter** to continue.

<figure><img src="../../../../../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

***

### Required Inputs

#### 1. FluxNode Identity Key

* In **Zelcore Wallet**: Go to **Apps → FluxNodes**.
* Find your **offline FluxNode** entry, click the **arrow** to expand, then click **Edit**.
* Copy the **Flux Identity Key** and paste it into the terminal.
* Press **Enter**.

<figure><img src="../../../../../../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

#### 2. Collateral TX ID

* From the same **Edit FluxNode** popup, copy the **Collateral TX ID**.
* Paste it into the terminal.
* Press **Enter**.

<figure><img src="../../../../../../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

#### 3. Output Index

* From the same **Edit FluxNode** popup, copy the **Output Index**.
* You may close the popup now.
* Paste the value into the terminal.
* Press **Enter**.

<figure><img src="../../../../../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

#### 4. FluxID

* In **Zelcore Wallet**: Go to **Apps → FluxID**.
* Copy the ID displayed below the QR code.
* Paste it into the terminal.
* Press **Enter**.

<figure><img src="../../../../../../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

#### 5. Kadena Address

* Navigate to the **Portfolio** menu in Zelcore.
* Add **KDA** as an asset if it’s not already present.
* Click **Receive**, leaving **Chain ID** as `0`.
* Copy the `k...` address and paste it into the terminal.
* Press **Enter**.

<figure><img src="../../../../../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

***

### Additional Settings

#### 1. Auto-Update

* **Yes / No**
* **Recommended:** No — update manually to avoid downtime.

<figure><img src="../../../../../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

#### 2. Alert Notification

* **Yes / No**
* Select **Discord** and/or **Telegram**:
  * **Discord:** Paste your Webhook URL.
  * **Telegram:** Create a bot with `@BotFather` → `/newbot`, then paste the Bot Token.
* **Tip:** Press `Space` to select/deselect, `Tab` to move between OK/Cancel.

<figure><img src="../../../../../../.gitbook/assets/image (44).png" alt=""><figcaption></figcaption></figure>

#### 3. Flux Bootstrap from Source

* **Yes / No**
* **Recommended:** Yes — faster blockchain sync (\~10–15 min download).

<figure><img src="../../../../../../.gitbook/assets/image (45).png" alt=""><figcaption></figcaption></figure>

#### 4. Keep Bootstrap File Locally

* **Yes / No**
* **Recommended:** No — saves storage space.

<figure><img src="../../../../../../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>

#### 5. Enable UPnP

* **VPS:** No
* **Home Hosted**: Yes

<figure><img src="../../../../../../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

#### 6. Enable Thunder Mode

**Yes** if your server has extra storage (may increase rewards).

<figure><img src="../../../../../../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

***

### Finished Configuration

When the confirmation screen appears, your **FluxNode Installation Configuration File** is ready.

<figure><img src="../../../../../../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

**Next Step:** After creating your installation configuration, proceed to **Install FluxNode (Option 2)** to install and configure all Flux components.
