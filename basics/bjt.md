
| Feature | BJT as an Amplifier | BJT as a Binary Digital Switch |
| :--- | :--- | :--- |
| **Operating Mode** | **Forward-Active Mode** | Alternates between **Cutoff** and **Saturation** |
| **Voltage Rule** | $V_{collector} > V_{base} > V_{emitter}$ | **Cutoff (0):** $V_{base} \le V_{emitter}$ <br> **Saturation (1):** $V_{base} > V_{collector}$ |
| **Base-Emitter Junction** | Forward-Biased (ON) | **Cutoff:** Reverse/Unbiased (OFF) <br> **Saturation:** Forward-Biased (ON) |
| **Base-Collector Junction**| Reverse-Biased (OFF) | **Cutoff:** Reverse-Biased (OFF) <br> **Saturation:** Forward-Biased (ON) |
| **Current Gain ($\beta$)** | **Active & Functional** ($I_C = \beta \cdot I_B$) | **Inactive / Blown Out** (Current limited by external resistors) |
| **Behavior** | Acts as a voltage-controlled current source | Acts as an automated open or closed mechanical switch |
| **Common Use Cases** | Audio pre-amps, radio receivers, microphone circuits | Computer processors (CPUs), logic gates, motor drivers |
