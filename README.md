# 🔍 Crystal Tester (Proteus Simulation Project)

This is a Proteus simulation project for a **Crystal Oscillator Tester**. The purpose of this circuit is to check whether a quartz crystal (like 8MHz, 12MHz, or 16MHz) is working properly or not. The tester lights up an LED when oscillations are successfully generated by the crystal.

---

## 💡 How It Works

1. The crystal is placed in an oscillator circuit using a transistor-based amplifier.
2. When the crystal oscillates, the signal is processed through diodes and another transistor.
3. If oscillation is detected, the LED lights up – indicating the crystal is functional.
4. If there's no oscillation, the LED remains off – meaning the crystal may be faulty.

This allows quick testing of common crystals used in embedded systems and electronics projects.

---

## ⚙️ Requirements

- Proteus Design Suite (Version 8 or higher is recommended)

---

## ⚙️ Circuit Preview
![WhatsApp Image 2025-03-29 at 4 01 38 PM](https://github.com/user-attachments/assets/c381c5a1-e7cb-421b-a926-e9fabb06eb57)


---

## 🚀 How to Use

1. Open the file `ROOT.DSN` using Proteus.
2. Press the **Run Simulation** button.
3. Observe the LED (D1):
   - ✅ If it glows — crystal is working.
   - ❌ If it doesn't glow — the crystal is likely faulty.
4. Try replacing `X1` with different crystals to test various frequencies.

---

## 📌 Notes

- You can tweak the values of R, C, and the crystal (X1) to test other ranges.
- Works well for most common crystals between **4MHz – 20MHz**.

---

## 📜 License

This project is open-source and free for educational and personal use.  
Feel free to contribute, modify, or share!

---

## 🙌 Acknowledgements

Made using **Proteus** and a passion for learning electronics!
