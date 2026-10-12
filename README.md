# 🌊 Pump Power Estimator

A smart, lightweight web application designed for field engineers to quickly estimate the suitable pump type and required motor power based on specific duty points (Flow and Head).This tool operates completely offline-ready (client-side HTML/JS) and does not require any proprietary supplier database, relying instead on standard engineering hydraulic formulas and empirical pump performance envelopes.

✨ Features
- Smart Pump Selection: Input your desired Flow and Head, and the logic engine will automatically recommend the most suitable pump type (e.g., End Suction, Split Case, Vertical Multistage) based on standard operating ranges.
- Instant Power Calculation: Calculates the required Hydraulic Power and Shaft Power based on the estimated efficiency of the recommended pump type.
- Standard Motor Sizing: Automatically applies safety factors (10% - 25%) and recommends standard IEC electric motor sizes (kW) available in the market.
- Mobile-Friendly: Clean, responsive UI built with Tailwind CSS, perfectly sized for quick usage on mobile phones directly in the field.

🚀 How to Use
1. Access the App: Open the live GitHub Pages link (or open index.html locally in your browser).
2. Select Application: Choose the fluid condition (Clean Water, Sewage, or Deep Well).
3. Input Duty Point:
   - Enter the Flow Capacity (in $m^3/h$ or L/s).
   - Enter the Total Head (in meters).
4. Calculate: Click the "Cari & Kalkulasi Pompa" button.
5. Review Results: The app will display the recommended pump types, the estimated shaft power, and the minimum standard motor size required.
  
🛠️ Tech Stack
- HTML5V
- anilla JavaScript (No framework required)
- Tailwind CSS (via CDN for styling)
- FontAwesome (via CDN for icons)
