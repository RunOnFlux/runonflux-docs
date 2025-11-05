# Start via SSP

This step activates your FluxNode from within the SSP Wallet. You’ll link your FluxNode name, set the IP address, and officially start the FluxNode on the Flux blockchain. Once started and confirmed, your node will be live and ready to serve the network.

***

### Step-by-Step Instructions

#### 1. Open the SSP Wallet

* In your **SSP Wallet Extension**, go to the **Nodes** tab.
* Find your **Unassigned FluxNode** entry and click to expand it.
* Wait for **100+ confirmations** on your collateral transaction (\~3.5 hours).
  * You can check this using the **Flux Explorer**: [https://explorer.runonflux.io/](https://explorer.runonflux.io/) — search for the **TXID** of your node to see the confirmation count.

<figure><img src="../../../../.gitbook/assets/Setup FluxNode (1).png" alt=""><figcaption></figcaption></figure>

#### 2. Set Up Your FluxNode

* Click **Setup FluxNode**.
* Enter a **FluxNode name** — any alias to help you identify it.
* For **IP**:
  * Enter `0.0.0.0` for now — SSP will automatically update this once the FluxNode starts.
* Click **Save**.

<figure><img src="../../../../.gitbook/assets/name and IP.png" alt=""><figcaption></figcaption></figure>

#### 3. Start Your FluxNode

* Click **Start**.
* Read the pop-up carefully, review optional steps below, then confirm by clicking **Start**.
* Status changes:
  * **Started** → After \~1 block is mined.
  * **Confirmed** → After 1–10 blocks (2–20 minutes).
* Checking status:
  * In **FluxOS** (click FluxOS button) — look for **“Connected to the network”**.
  * Or stay in Zelcore pop-up — it refreshes every minute.

<figure><img src="../../../../.gitbook/assets/Start 2.png" alt=""><figcaption></figcaption></figure>

***

### (Optional) Confirm Benchmark

* In a browser, open:

```
http://YourServerIP:16196      // Example: http://37.187.79.189:16196/
```

* Go to **Administration → Benchmark → FluxNodes → Get Benchmark**.
* Check results:
  * **CUMULUS / NIMBUS / STRATUS** → Benchmark passed.
  * **RUNNING** → Wait and refresh until complete.
  * **FAILED** or FluxOS not loading → Visit the Flux Discord Support.

<figure><img src="../../../../.gitbook/assets/benchmark good (1).png" alt="" width="563"><figcaption></figcaption></figure>

***

### Congratulations!

Your FluxNode is now installed, benchmarked, and running. Proceed to **Monitoring and Updates & Maintenance** to keep your node healthy and online.

<figure><img src="../../../../.gitbook/assets/Confirmed (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (72).png" alt="" width="563"><figcaption></figcaption></figure>
