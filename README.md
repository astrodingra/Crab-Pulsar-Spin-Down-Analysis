
# **Crab-Pulsar-Spin-Down-Analysis**

**Determining Spin Down Rate of Crab Pulsar Over Years**

#### **Problem: How much has the Crab pulsar slowed down since the launch of AstroSat?**

**Objective:** Finding the rate of spin-down of the Crab pulsar with AstroSat LAXPC and CZTI observations.

**Credit:** [**Jashanpreet Singh Dingra**](https://astrodingra.github.io) | ISRO Data Archive

###### **<span style="color:red">Note:</span> The code in the repository may contain discrepancies, and I am continuously working to enhance the accuracy and precision of the results.**

###### For any queries, please contact me at **astrodingra@gmail.com** or **astrodingra@icloud.com**, or DM me on Instagram [**@astrodingra**](https://www.instagram.com/astrodingra).

---

## **Explanation**

### **Graph 1: Spin Period vs. Pulse Number**

**Plot Description:**
- **X-axis:** Pulse Number (index of each spin period in the sequence).
- **Y-axis:** Spin Period (time between consecutive pulses, in seconds).

**Interpretation:**
- This plot shows how the spin period changes with each successive pulse.
- If the pulsar is spinning down (i.e., its spin rate is decreasing), you might observe a trend where the spin periods gradually increase.
- Any irregularities or significant deviations could indicate noise, observational errors, or interesting astrophysical phenomena such as **glitches** (sudden changes in spin period).

**Note:**
> **Since this is a single dataset, we might not see a significant spin-down rate. For effective results, we need more data, or we can simply predict the future spin-down rate based on this data only and then match it by analyzing a year-long dataset.**

---

### **Graph 2: Spin Period vs. Time**

**Plot Description:**
- **X-axis:** Time (seconds since the start of the observation or another reference point).
- **Y-axis:** Spin Period (time between consecutive pulses, in seconds).

**Interpretation:**
- This plot shows how the spin period changes over the actual observation time.
- A clear increasing trend in the spin periods over time indicates that the pulsar is gradually slowing down.
- This plot can also help identify long-term trends and any short-term variations in the pulsar's spin period.

---

## **Detailed Insights**

### **Spin-Down Rate:**
> **Graph 2 is particularly useful for calculating the spin-down rate, which is the rate at which the pulsar's rotation slows down over time. This can be done by fitting a linear or polynomial model to the data in this plot.**

### **Periodic Variations:**
> **Both graphs can reveal periodic variations in the spin period, which might be related to intrinsic properties of the pulsar or external influences.**

### **Glitches:**
> **Pulsars sometimes exhibit glitches, which are sudden increases in spin frequency (decreases in spin period). These would appear as sharp dips in the spin period in both plots.**
