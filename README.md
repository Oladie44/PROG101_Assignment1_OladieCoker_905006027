Sierra Leone Agricultural Crop & Irrigation Advisor (SL-ACIA)Course: Principles of Programming Logic and Design (PROG101)Institution: Limkokwing University of Creative Technology, Sierra LeoneDepartment: Information and Communication TechnologyAcademic Term: Semester 01 (September 2026 – January 2027)Project OverviewThe Sierra Leone Agricultural Crop & Irrigation Advisor (SL-ACIA) is an automated algorithmic decision-support tool designed to assist smallholder farmers, local agricultural extension officers, and farming cooperatives in Sierra Leone.The software logical design evaluates three critical environmental metrics:Soil pH Level (Acidity/Alkalinity)Soil Nitrogen Level ($mg/kg$)Weekly Expected Rainfall ($mm$)Based on these parameters, the system validates inputs, recommends optimal localized crop varieties (e.g., Rice, Maize, Cassava, or Groundnut), calculates daily water deficits, and generates an automated 7-day irrigation schedule.Key Features & Programming ConstructsComputational Thinking: Problem Decomposition, Pattern Recognition, Abstraction, and Step-by-Step Algorithmic Design.Input Validation: Repetition structure (WHILE loop) to ensure soil pH values fall within realistic agronomic bounds ($3.0 \le \text{pH} \le 10.0$).Nested Decision Logic: Multi-tier IF-THEN-ELSE branching to evaluate soil pH and nitrogen content for crop selection.Irrigation Calculation: Deficit calculation comparing actual rainfall against a standard base crop requirement ($35.0\text{ mm}$).Iterative Scheduling: Fixed repetition structure (FOR loop) to generate a 7-day daily irrigation plan.Modular Design: Clear input, validation, processing, decision, and output separation.Sustainable Development Goals (SDGs) AlignmentSDG 2: Zero Hunger – Optimizes crop placement according to soil chemistry, significantly improving crop yields per hectare in local Sierra Leonean communities.SDG 13: Climate Action – Helps farmers adapt to changing seasonal rainfall patterns by preventing overwatering and underwatering through precise daily irrigation tracking.Open Source & Digital Public Goods (DPGs) JustificationOpen Source Software (OSS): Published under an open license to allow local software developers, student engineers, and agricultural NGOs in Sierra Leone to modify, translate into local languages (e.g., Krio, Mende, Temne), and build upon the core algorithm.Digital Public Good (DPG): Designed to operate with zero licensing cost, enabling public entities like the Ministry of Agriculture and Food Security to integrate the logic into low-bandwidth SMS/USSD platforms for widespread rural accessibility.Directory StructurePROG101_Assignment1_YourName_StudentID/
│
├── README.md                          # Project overview and documentation
├── algorithms/
│   ├── pseudocode.txt                 # Flowgorithm-compatible pseudocode
│   └── flowgorithm_chart.fprg         # Flowgorithm source executable file
├── report/
│   └── PROG101_Final_Report.pdf       # Full academic report document
└── screenshots/
    ├── flowchart_execution.png        # Screenshot of Flowgorithm flowchart
    └── github_commit_history.png      # Screenshot of Git commit history
How to Run the Flowchart in Flowgorithm
Download and install Flowgorithm from flowgorithm.org.
Open Flowgorithm and load algorithms/flowgorithm_chart.fprg (or copy the text from algorithms/pseudocode.txt using the Pseudocode window).
Click the Play ($\triangleright$) button on the top toolbar to execute the flowchart.
Enter test values:Sample Input 1: Name = Sorie Kamara, pH = 5.8, Rainfall = 15.0, Nitrogen = 60.0Expected Result: Recommended Crop = Rice, Irrigation Need = 20.0 Liters/m² over 7 days.
Author & Academic Information
Student Name: [Your Full Name]
Student ID: [Your Student ID]
Lecturer / Examiner: Elijah Fullah
Course Code: PROG101
