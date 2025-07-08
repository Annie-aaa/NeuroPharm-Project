#  NeuroPharm Therapeutics:  Investigation Resolution & Product Variability Analysis for Regulatory Readiness


## 1. Project Background
### Company Context
NeuroPharm Therapeutics is a leading pharmaceutical manufacturer specializing in CNS medications across North America and Europe. The company adheres to rigorous cGMP guidelines to meet regulatory requirements from the FDA and EMA.

### Digital Transition Initiative
In July 2024, NeuroPharm Therapeutics transitioned from a physical documentation system to a new digital documentation system. This strategic shift was intended to improve data integrity, enhance process visibility and ensure readiness for increasingly stringent regulatory audits.

### Current Evaluation in 2027
As of 2027, the company is undertaking a comprehensive evaluation of investigations carried over from the previous physical system and managed within the new digital environment. This evaluation is essential to addressing potential risks to compliance and ensuring the effectiveness of quality systems.

### Project Objectives
This project uses data from the digital system to assess:

- Investigation backlogs and resolution performance.

- Product-specific quality metrics, including particle size and pH levels.

- Investigation performance by resolution category (backlog, delayed, on-time) and severity (critical, moderate, minor).

- Key root causes, such as training gaps, equipment failures, and procedural deviations.

### Analytical Approach
Excel was the primary tool for data analysis and visualization in this project. Power Query was used for data cleaning and aggregation, while Power Pivot was leveraged for data modeling and DAX calculations. The resulting dashboards, built entirely in Excel, provide dynamic exploration of investigation and quality data to identify systemic challenges and improvement opportunities.

### Continuous Improvement Goals
The insights derived from this analysis will support targeted CAPA initiatives, establish a robust baseline for future regulatory audits, and drive continuous improvement of NeuroPharm Therapeutics’ compliance and product quality standards.

## 2. Executive Summary

- In response to regulatory readiness objectives and ongoing compliance demands, NeuroPharm Therapeutics conducted a comprehensive investigation resolution and product variability analysis leveraging digital quality system data from 2023 to 2027. 
- This initiative follows the company’s 2024 digital documentation system transition, aimed at enhancing data integrity, process visibility and audit preparedness.

### <u>Key Objectives and Scope</u>
- <u>This analysis focused on</u>:

    - Resolving investigation backlogs and improving closure performance.

    - Assessing product quality indicators such as particle size and pH variability.

    - Evaluating resolution performance across departments, severity levels, and products.

    - Identifying systemic root causes and areas requiring corrective and preventive action (CAPA).

### <u>Analytical Methodology</u>
- Data from over 2,500 investigation records were processed using Excel-based tools including Power Query and Power Pivot for cleaning, modeling and visualization. 
- Realistic manufacturing challenges were intentionally reflected in the dataset, including inconsistent formats, missing values and duplicate records — simulating real-world regulatory data environments.

### <u>Major Findings</u>
- **Backlog Surge Post-Digital Transition**: 
    - All departments experienced a pronounced spike in net open investigations mid-2024, aligning with the digital system rollout.
    - Although resolution efforts have slightly reduced this backlog, projections suggest a persistent issue into 2025–2027 without significant intervention.

- **Training and Procedural Gaps**: 
    - The most frequent root causes were "Training Gap" and "Procedure Not Followed," consistently across Packaging, Production, QA and other operational units, highlighting urgent needs for targeted retraining and procedural simplification.

- **Resolution Delays**: 
    - Investigations categorized as “Backlog/Error” and “Delayed” are materially extending average resolution times across all severity levels. 
    - The gap between opened and closed cases remains unfavorable in most departments.

- **Product-Level Risk**: 
    - High-volume products like Alprazolam, Fluoxetine and Methylphenidate showed the greatest investigation backlogs and open CAPAs, posing regulatory and operational risks. 
    - Conversely, products such as Duloxetine and Venlafaxine had minimal issues, presenting opportunities to model best practices.

- **Investigator Performance Variability**: 
    - Despite system-wide challenges, individual investigator efficiency (when excluding backlog cases) remains strong. 
    - Investigators like R. Evans demonstrate effective backlog management, offering internal benchmarks.

### <u>Strategic Recommendations</u>
- **Backlog Remediation Task Force**: 
    - Form a dedicated cross-functional team to triage and resolve aging investigations, prioritizing critical severity and high-volume products.

- **System Optimization & Training**: 
    - Audit the digital documentation system for usability issues and retrain users on investigation workflows and CAPA integration.

- **CAPA Management Overhaul**: 
    - Streamline CAPA closure processes and link investigator performance to CAPA follow-through.

- **Targeted Quality Improvements**: 
    - Deploy product-specific quality enhancement plans, with a focus on equipment maintenance, contamination controls and SOP clarity.

- **Real-Time Monitoring & Analytics**: 
    - Establish robust KPIs and dashboards to track open/closed trends, severity aging and training compliance in real time.

### <u>Business and Regulatory Impact</u>
- By addressing the identified backlogs, training deficiencies and systemic process inefficiencies, NeuroPharm Therapeutics positions itself for a stronger compliance posture and enhanced readiness for future FDA/EMA inspections. 
- These actions will drive quality consistency, mitigate regulatory risks and reinforce the company’s commitment to patient safety and operational excellence.


## 3. Dataset Overview
The dataset analyzed in this project contains 2,500 investigation records designed to closely replicate realistic pharmaceutical manufacturing environments. It incorporates key elements encountered in real-world investigation and product quality management processes, including:

- **Investigation metadata**:

    - ```Open Date```

    - ```Closed Date```

    - ```Batch Number```

    - ```Product Name```

    - ```Department```

    - ```Deviation Category```

    - ```Root Cause```

    - ```Impact Severity```

- **Corrective Action and Preventive Action (CAPA) data**:

    - ```CAPA Required```

    - ```CAPA Closed```

    - ```CAPA Number```

- **Investigator information**
    - ```Investigator```

- **Product quality data**:

    - ```Particle Size (μm)```

    - ```pH Level```

<br><br>
To simulate typical challenges in pharmaceutical data environments, the dataset includes realistic inconsistencies such as:

- Mixed date formats

- Inconsistent product naming

- Missing values in key fields

- Duplicate entries

- Variability in product quality parameters

<br>

Data cleaning and aggregation were performed in Excel, leveraging **Power Query** to standardize formats, handle missing values, and remove duplicates. Data modeling was executed in **Power Pivot**, where relationships between data columns were defined to enable robust analysis across investigation severity, product quality, and resolution performance metrics.

<br>
This structured and cleansed dataset underpins the subsequent analyses and visualizations, ensuring accurate insights into NeuroPharm Therapeutics’ investigation and quality performance landscape.

## 4. Insights and Recommendations
### 4.1. Dashboard 1: Investigation Trends & Root Causes

![alt text](<dashboard 1.png>)

---
#### 4.1.1. Insights & Recommendations by Department
---
- <u>**Overall Observation (Applicable Across Departments)**</u>: 
    - The "Net Open Investigations" line chart reveals a critical trend. 
    - Across all departments, there's a steep rise in net open investigations from early 2024, peaking sharply around mid-2024, which directly correlates with the transition to the new digital documentation system. 
    - This indicates a significant initial challenge in migrating or processing existing investigations and/or a learning curve with the new system. 
    - Post-peak, there's a visible but gradual decline, suggesting efforts to clear the backlog are underway, but the projected line into 2025-2027 remains elevated, indicating a persistent, long-term backlog if current trends continue. 
    - The goal should be to bring this net open line closer to zero.

- <u>**Department: Packaging**</u>
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations (Area Chart)**: There's a fluctuating but generally consistent volume of opened investigations from early 2023 through late 2024. No extreme spikes are immediately apparent, suggesting a steady stream of new issues.

            - **Closed Investigations (Area Chart)**: Closed investigations generally track below opened investigations until mid-2024, indicating that new investigations were being opened faster than they were closed. Post-mid-2024, the closing rate appears to improve and sometimes slightly exceed the opening rate, which is positive.
            - **Net Open Investigations (Line Chart)**: The line demonstrates the severe backlog: a rapid increase from early 2024, peaking in mid-2024. After this peak, the line shows a very gradual downward slope, suggesting a slow but positive effort to reduce the backlog. However, the projection indicates this backlog will persist well into 2025 and beyond if current rates continue. The height of the peak (around 250+ days in terms of accumulation) is concerning.

        - <u>```Resolution Categories```</u>: 
            - A significant number of investigations (121) are categorized as "Backlog/Error," directly supporting the observed backlog trend from the volume chart. 
            - This suggests that a portion of the "Net Open Investigations" are likely related to data migration or initial classification issues from the system transition. 
            - "Ongoing" (118) is also high, indicating a large active workload.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (238) and "Procedure Not Followed" (234) are overwhelmingly the primary root causes. 
            - This suggests that operational non-compliance due to lack of knowledge or adherence is a major contributor to new investigations.
        - <u>```Impact Severity```</u>: 
            - Moderate (250) is the most frequent severity.

    - <u>Recommendations</u>:
        - **Aggressive Backlog Reduction Strategy**: 
            - Given the slow decline of "Net Open Investigations," establish a dedicated task force for Packaging's "Backlog/Error" and "Ongoing" investigations. 
            - Implement a "sprint" approach to close these, focusing on efficient triage and resolution for older cases.
        - **Targeted Training for Process & Digital Proficiency**: 
            - Address the high "Training Gap" and "Procedure Not Followed" root causes with immediate, department-specific training. 
            - Crucially, this training must cover both existing GMP procedures and the effective, compliant use of the new digital documentation system to prevent new "Backlog/Error" investigations and ensure accurate data capture.
        - **Procedure Simplification & Validation**: 
            - Review high-frequency "Procedure Not Followed" procedures within Packaging for clarity, potential ambiguities, or excessive complexity. 
            - Simplify and re-validate them with staff to ensure practicality and adherence.
        - **Monitor Opened vs. Closed Rate**: 
            - Closely monitor the daily/weekly ratio of opened vs. closed investigations. 
            - The goal should be to consistently close more investigations than are opened to accelerate backlog reduction.
- <u>**Department: Production**</u>
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: Exhibits a fluctuating pattern, indicating a continuous stream of new issues arising from production activities.

            - **Closed Investigations**: Similar to Packaging, closed investigations lag behind opened ones until mid-2024. Post-transition, there's an improvement, but the gap often remains, preventing a rapid reduction of the net open volume.
            - **Net Open Investigations**: Shows the characteristic sharp peak in mid-2024, similar to other departments, indicative of the system transition impact. The subsequent decline is more gradual than ideal, suggesting that while some progress is being made, the closure rate is not significantly outpacing the opening rate, leading to a persistent backlog that extends far into the projection. The high peak emphasizes the need for aggressive intervention.

        - <u>```Resolution Categories```</u>: 
            - "On-time" (155) is the largest, but "Ongoing" (119) and "Backlog/Error" (108) are substantial, highlighting the active and legacy challenges.

        - <u>```Root Causes```</u>: 
            - "Training Gap" (177) and "Procedure Not Followed" (138) remain prevalent, similar to Packaging, suggesting widespread issues with operational execution. 
            - "Operator Error" (54) is also a factor.
        - <u>```Impact Severity```</u>: 
            - Moderate (262) investigations are the most frequent.

    - <u>Recommendations</u>:
        - **Enhanced Real-time Monitoring & Escalation**: 
            - Implement real-time monitoring of investigation statuses within Production. 
            - Establish clear escalation paths for "Ongoing" investigations that approach critical resolution timelines to prevent further delays and backlog growth.

        - **Focused Training on High-Impact Procedures**: 
            - Identify the specific procedures most frequently associated with "Procedure Not Followed" and "Training Gap" root causes in Production. 
            - Develop targeted, hands-on training for these, possibly including competency assessments.
        - **Production Line Walk-throughs & Gemba Walks**: 
            - Conduct frequent "Gemba walks" on the production floor to observe processes firsthand, identify deviations, and provide immediate coaching, thereby proactively reducing "Operator Error" and "Procedure Not Followed" incidents that lead to new investigations.
        - **Backlog Task Force for Production-Specific Cases**: 
            - Given the persistent backlog, create a dedicated team to specifically address Production-related "Backlog/Error" investigations, prioritizing those that carry higher regulatory or operational risk.

- **Department: QA (Quality Assurance)**

    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - The pattern of opened investigations in QA is generally stable with minor fluctuations.
            - **Closed Investigations**: 
                - The closed investigations largely follow the opened trend, with an improvement in closure rate post-mid-2024, indicating a better ability to handle new investigations.
            - **Net Open Investigations**: 
                - The peak in mid-2024 is pronounced, clearly showing the impact of the system transition. 
                - However, the subsequent decline appears slightly steeper than in Packaging or Production, suggesting QA might be more efficient in clearing its own backlog or that their backlog consists of cases that are easier to close once categorized. 
                - The projection still indicates a persistent volume into 2025.

        - <u>```Resolution Categories```</u>: 
            - QA has the lowest "Delayed" (17) and "Long Delay" (4) investigations, suggesting relative efficiency in managing active cases. 
            - However, "Ongoing" (116) and "Backlog/Error" (114) are still significant.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (229) and "Operator Error" (122) are the highest root causes for QA. 
            - This is particularly concerning as QA is the gatekeeper of quality and compliance. 
            - "Procedure Not Followed" (111) is relatively lower.

        - <u>```Impact Severity```</u>: 
            - Moderate (212) investigations are most frequent.

    - <u>Recommendations</u>:
        - **Urgent QA Staff Training on System & Quality Standards**:
            - Prioritize comprehensive training for QA personnel on the new digital system's full functionality for investigation management and documentation. 
            - Furthermore, given the high "Training Gap" and "Operator Error" within QA itself, revisit core QA competencies, audit methodologies and data integrity principles to ensure their foundational knowledge is robust.
        - **Internal Process Audit for QA's Own Investigations**: 
            - Conduct an internal audit of QA's investigation process to identify specific areas contributing to "Operator Error" within their own team. 
            - This might relate to data entry, review processes, or communication.
        - **Leverage QA's Resolution Strengths**: 
            - Analyze why QA has lower delayed investigations. 
            - Document their internal best practices for investigation closure and knowledge transfer, and consider implementing these methodologies across other departments to improve overall resolution performance.
        - **Focus on Preventative QA Actions**: 
            - Emphasize proactive quality assurance activities (e.g., enhanced in-process checks, pre-audit reviews) to reduce the number of investigations that originate from QA processes, ultimately lowering the opened investigation rate.

- **Department: QC Lab (Quality Control Laboratory)**

    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - Similar to other departments, there's a relatively consistent influx of opened investigations.
            
            - **Closed Investigations**: 
                - While closed investigations track below opened ones until mid-2024, post-transition, the closure rate shows some improvement, but still often trails the opening rate.
            - **Net Open Investigations**: 
                - The familiar sharp peak in mid-2024 is present, indicating the system transition impact. 
                - The subsequent decline is also very gradual, highlighting a persistent backlog issue that will project far into the future without further intervention. 
                - The peak's height signifies a substantial accumulation of unresolved lab-related issues.

        - <u>```Resolution Categories```</u>: 
            - "Backlog/Error" (124) is a major category, consistent with the system transition. "On-time" (145) is also high.

        - <u>```Root Causes```</u>: 
            - "Equipment Malfunction" (180) and "Material Contamination" (165) are uniquely prominent here, differentiating QC Lab from other departments. 
            - "Operator Error" (82) is also significant, while "Training Gap" (65) is comparatively lower.
        - <u>```Impact Severity```</u>: 
            - Moderate (231) is the most frequent severity.
    
    - Recommendations:
        - **Proactive Equipment Management Program**: 
            - Implement a comprehensive preventive maintenance and calibration program for all QC Lab equipment. 
            - This should include regular servicing, predictive analytics where possible, and a robust "out-of-calibration" investigation procedure to proactively address "Equipment Malfunction" root causes.
        - **Enhanced Contamination Control Protocols**: 
            - Conduct a detailed review of all material handling, sample preparation, and testing protocols within the QC Lab to identify and mitigate sources of "Material Contamination." 
            - This could involve stricter aseptic techniques, environmental monitoring, or vendor material quality checks.
        - **Specialized Training for Lab Operations**: 
            - While general "Training Gap" is lower, focus training specifically on precise lab techniques, proper equipment operation and stringent contamination avoidance procedures to reduce "Operator Error" and specific technical errors.
        - **Digital Integration for Lab Data**: 
            - Explore greater integration between lab instruments and the new digital documentation system to automate data capture and reduce manual "Operator Error" in recording results, thereby decreasing the likelihood of new investigations.

- **Department: R&D (Research & Development)**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - R&D shows a fluctuating but relatively consistent volume of opened investigations.
            - **Closed Investigations**: 
                - The rate of closed investigations generally lags behind opened ones, particularly up to mid-2024. 
                - Post-transition, while there's an effort to close investigations, the opening rate seems to frequently outpace the closing rate, contributing to the backlog.
            - **Net Open Investigations**: 
                - R&D exhibits the highest peak in net open investigations among all departments, reaching well over 250 days of accumulation. 
                - This suggests the R&D department was disproportionately affected by the system transition, or inherently generates more complex, longer-duration investigations. 
                - The subsequent decline is also very gradual, indicating significant challenges in clearing this substantial backlog, projecting a long-term issue.
        - <u>```Resolution Categories```</u>: 
            - R&D has the highest number of "Delayed" (26) and "Very Delayed" (3) investigations, indicating severe bottlenecks in their resolution processes. 
            - "Backlog/Error" (137) and "Ongoing" (131) are also very high.
        - <u>```Root Causes```</u>: 
            - "Material Contamination" (263) and "Operator Error" (133) are significantly high for R&D, along with a substantial "Training Gap" (135).
        - <u>```Impact Severity```</u>: 
            - R&D has the lowest "Critical" severity (87) but a higher number of "Moderate" (214) and "Minor" (230) investigations.
        
    - <u>Recommendations</u>:
        - **Dedicated R&D Backlog Reduction Initiative**: 
            - Given the highest peak and slow decline in "Net Open Investigations" and the high "Delayed" categories, R&D requires a dedicated, intensive backlog reduction initiative. 
            - This could involve assigning specific resources, setting aggressive closure targets, and simplifying the resolution workflow for older R&D cases.
        - **Advanced Training for R&D Specific Risks**: 
            - Develop highly specialized training programs for R&D personnel focusing on experimental integrity, meticulous material handling (to combat "Material Contamination"), accurate data recording, and rigorous adherence to research protocols to mitigate "Operator Error" and "Training Gaps."
        - **Streamlined R&D Investigation Workflow**: 
            - Analyze the unique complexities of R&D investigations that contribute to high "Delayed" rates. 
            - Implement streamlined processes, clearer decision points, and enhanced cross-functional collaboration (e.g., with QA, Production liaison) to expedite resolution without compromising scientific rigor.
        - **Pilot Program for Root Cause Elimination in R&D**: 
            - Given the high frequency of "Material Contamination" and "Operator Error," launch a pilot program focused on deeply investigating these root causes within R&D, identifying systemic issues, and implementing targeted corrective and preventive actions (CAPAs) to reduce their recurrence.


#### 4.1.2. Insights & Recommendations by Product
- **Overall Observation (Applicable Across Products)**: 
    - The overarching trend of a sharp increase in "Net Open Investigations" peaking around mid-2024 (aligning with the digital system transition) remains consistent across most products. 
    - This strongly suggests that the system implementation and initial data migration/processing challenges impacted the entire product portfolio. 
    - Post-peak, there's generally a gradual decline, indicating efforts to clear the backlog, but the persistent elevated line in the 2025-2027 projection signifies a continuing challenge in backlog management across multiple products.

- **Product: Alprazolam 0.5mg**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - Shows a fluctuating but relatively consistent volume of opened investigations from early 2023 through late 2024
                - There isn't a clear seasonal pattern, suggesting issues arise steadily.
            - **Closed Investigations**: 
                - For much of 2023 and early 2024, closed investigations lag significantly behind opened ones. 
                - Post-mid-2024, the closure rate improves and occasionally surpasses the opening rate, which is positive.
            - **Net Open Investigations**: 
                - Exhibits the characteristic steep rise in early 2024, peaking sharply around mid-2024, demonstrating a substantial backlog accumulation (peaking around 200+ days). 
                - The subsequent decline is slow and gradual, indicating that while progress is being made to clear the backlog, it is a prolonged effort, and a significant portion of this backlog is projected to persist well into 2025-2027. 
                - This suggests that the existing closure rate is not aggressively addressing the built-up volume.
        - <u>```Resolution Categories```</u>: 
            - This product has the highest numbers in "Delayed" (103) and "Long Delay" (25), with a significant "Slightly Delayed" (386). "Backlog/Error" (604) is exceptionally high. 
            - This indicates severe issues with timely investigation closure for Alprazolam, contributing heavily to the persistent net open volume.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (125), "Procedure Not Followed" (78), and "Operator Error" (75) are the dominant root causes. "Material Contamination" (71) and "Equipment Malfunction" (52) are also notable. 
            - This points to a multifaceted problem involving human error, procedural non-compliance and potentially equipment/material issues specific to Alprazolam production.
        - <u>```Impact Severity```</u>: 
            - Moderate (196) and Minor (102) severities are most prevalent.

    - <u>Recommendations</u>:
        - **Urgent Backlog Task Force for Alprazolam**: 
            - Given the exceptionally high "Delayed" and "Backlog/Error" counts and the very slow decline in net open investigations, an urgent, dedicated task force should be assigned to Alprazolam investigations. 
            - This team should prioritize and rapidly resolve outstanding cases, particularly focusing on those categorized as "Backlog/Error" to reduce the oldest accumulated volume.
        - **Comprehensive Process & Equipment Review for Alprazolam**: 
            - Conduct a thorough review of Alprazolam's manufacturing and quality control processes. Specifically investigate the high incidence of "Material Contamination" and "Equipment Malfunction" to identify root causes and implement targeted CAPAs.
        - **Targeted Training and SOP Reinforcement**: 
            - Develop and deliver highly specific training modules for personnel involved in Alprazolam production and QC, addressing identified "Training Gaps," reinforcing "Procedure Not Followed" areas and minimizing "Operator Error." 
            - Ensure SOPs are clear and actively followed.
        - **Analyze Historical Delays**: 
            - Conduct a deep dive into the 100+ "Delayed" investigations for Alprazolam to understand common blockers, resource constraints or process inefficiencies that are extending resolution timelines.

- **Product: Clonazepam 0.5mg**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - Shows a relatively consistent but lower volume of opened investigations compared to Alprazolam or Fluoxetine.
            - **Closed Investigations**: 
                - The closure rate generally keeps pace with or slightly lags the opening rate in early 2024.
                - Post-mid-2024, closures appear more consistent.
            - **Net Open Investigations**: 
                - Exhibits the characteristic peak around mid-2024, but at a significantly lower magnitude (peaking around 80-90 days, much lower than 200+ for Alprazolam). 
                - The subsequent decline is also present, but the overall backlog is much smaller and appears more manageable, projecting a faster return to baseline if efforts continue. 
                - This suggests Clonazepam was less affected by the system transition or inherently generates fewer complex issues.
        - <u>```Resolution Categories```</u>: 
            - "On-time" (69) is the highest category, followed by "Ongoing" (64) and "Backlog/Error" (42). 
            - "Delayed" (8) and "Very Delayed" (1) are very low, indicating that when investigations for Clonazepam are initiated, they are generally resolved efficiently.

        - <u>```Root Causes```</u>: 
            - "Training Gap" (54), "Operator Error" (50), and "Procedure Not Followed" (32) are the main root causes.
            - "Material Contamination" (28) and "Equipment Malfunction" (21) are present but at lower counts than for high-volume products.
        - <u>```Impact Severity```</u>: 
            - Balanced across Critical (51), Moderate (51) and Minor (53).

    - <u>Recommendations</u>:
        - **Maintain & Replicate Best Practices**: 
            - Clonazepam demonstrates relatively good investigation management. 
            - Document the best practices, training methodologies, or process controls specific to Clonazepam that contribute to its lower backlog and fewer delays.
            - Explore how these can be replicated for other products.
        - **Proactive Root Cause Elimination**: 
            - Even with lower volumes, address the "Training Gap" and "Operator Error" root causes through targeted training and clear SOPs to maintain this positive trend and prevent future spikes.
        - **Monitor for Anomaly**: 
            - While overall good, continue to monitor Clonazepam's investigation trends closely. 
            - Any sudden increase in opened investigations or a spike in net open investigations should be immediately investigated to prevent a new backlog.

- **Product: Duloxetine 30mg**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>: 
            - The chart shows only one investigation opened in June 2024. 
            - The line for "Net Open Investigations" peaks at 1 day and remains flat.
            - **Opened/Closed Investigations**: 
                - Only one investigation was opened and it remains open.
            - **Net Open Investigations**: 
                - Reflects the single open investigation.
        - <u>```Resolution Categories```</u>: 
            - Only one "Ongoing" investigation.
        - <u>```Root Causes```</u>: 
            - Only one "Material Contamination" root cause.
        -   <u>```Impact Severity```</u>: 
            - Only one "Critical" investigation.
    - <u>Recommendations</u>:
        - **Immediate Resolution of Single Investigation**:
            - Investigate and resolve this single, critical "Material Contamination" investigation for Duloxetine 30mg immediately. 
            - Given it's a critical severity and potentially unique, it warrants urgent attention to prevent recurrence.
        - **Verify Data Completeness**: 
            - Given such a low count, it's crucial to confirm that this data is complete and accurate. 
            - Is it possible that Duloxetine investigations are being miscategorized or missed in the new system or is this genuinely a product with exceptionally few quality issues? 
            - Perform a quick data audit to ensure completeness for this specific product.
        - **Proactive Quality Assurance**: 
            - If the low volume is accurate, focus on proactive quality assurance measures for Duloxetine 30mg to maintain its excellent track record and prevent any new investigations.

- **Product: Fluoxetine 20mg**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - Shows a significant and generally consistent volume of opened investigations, similar to Alprazolam, suggesting a steady stream of issues.
            - **Closed Investigations**: 
                - Closures consistently lag behind openings in early 2024. Post-mid-2024, while there's an effort, the closed line often stays below the opened line, indicating difficulty in keeping pace with new investigations.
            - **Net Open Investigations**: 
                - Displays a prominent, high peak (over 200+ days) in mid-2024, demonstrating a substantial backlog.
                - The subsequent decline is very gradual, mirroring the trend seen in Alprazolam. 
                - This indicates that Fluoxetine contributes significantly to the overall company backlog and the current closure rate is insufficient for rapid reduction.
        - <u>```Resolution Categories```</u>: 
            - "Backlog/Error" (116) and "Ongoing" (106) are very high. "Delayed" (19) and "Slightly Delayed" (71) also contribute. 
            - This confirms the challenges in resolving investigations for Fluoxetine, contributing to the persistent backlog.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (148) and "Procedure Not Followed" (87) are the leading root causes, indicating widespread human factor issues. 
            - "Operator Error" (66), "Material Contamination" (80) and "Equipment Malfunction" (68) are also significant contributors.
        - <u>```Impact Severity```</u>: 
            - Moderate (211) and Minor (121) investigations are most frequent.

    - <u>Recommendations</u>:
        - **Fluoxetine-Specific Backlog Focus**: 
    
            - Similar to Alprazolam, Fluoxetine requires a dedicated focus on backlog reduction. 

            - Prioritize "Backlog/Error" and "Ongoing" investigations for this product to bring down the accumulated volume.
        - **Deep Dive into Fluoxetine Root Causes**: 
            - Conduct a comprehensive analysis of the specific "Training Gaps" and "Procedure Not Followed" instances related to Fluoxetine manufacturing. 
            - This might involve process mapping, observation studies or targeted interviews to pinpoint exact deficiencies.
        
        - **Investigate Equipment & Material Issues for Fluoxetine**: 
            - Given the notable "Equipment Malfunction" and "Material Contamination" for Fluoxetine, collaborate with engineering, maintenance and supply chain teams to address these recurring issues. 
            - This could involve equipment upgrades, vendor quality audits or improved material storage/handling.
        - **Performance Monitoring & Feedback**: 
            - Implement specific performance monitoring for Fluoxetine investigation resolution, providing regular feedback to relevant teams on their closure rates and backlog reduction progress.

- **Product: Gabapentin 300mg**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - Shows a relatively consistent but moderate volume of opened investigations.
            - **Closed Investigations**: 
                - The closure rate generally lags behind opened investigations, especially through early 2024. - Post-mid-2024, closures track closer to openings but don't significantly outpace them.
            - **Net Open Investigations**: 
                - Exhibits the mid-2024 peak but at a lower magnitude (around 100-110 days) compared to high-volume products like Alprazolam or Fluoxetine. - The subsequent decline is gradual, indicating a persistent but smaller backlog. 
                - This suggests a more manageable situation, though still requiring attention.
        - <u>```Resolution Categories```</u>: 
            - "Backlog/Error" (58) and "Ongoing" (57) are significant. 
            - "Delayed" (5) and "Very Delayed" (1) are low.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (71) and "Procedure Not Followed" (49) are key root causes. 
            - "Operator Error" (35), "Material Contamination" (39) and "Equipment Malfunction" (37) are also present.
        - <u>```Impact Severity```</u>: 
            - Critical (64) is the highest severity, which is notable despite lower overall volume.
    
    - <u>Recommendations</u>:
        - **Maintain Backlog Control**: 
            - While the backlog is smaller, proactively manage "Backlog/Error" and "Ongoing" investigations for Gabapentin to prevent future accumulation.
        - **Address Critical Severity Root Causes**: 
            - Focus on the root causes contributing to Critical severity investigations for Gabapentin. 
            - Even if fewer in number, their potential impact is high.
        - **Targeted Training for Gabapentin Processes**: 
            - Provide specific training modules for personnel involved in Gabapentin production and quality control, addressing identified "Training Gaps" and reinforcing critical "Procedure Not Followed" areas.
        - **Preventive Maintenance for Gabapentin Equipment**:          
            - Given "Equipment Malfunction" as a root cause, ensure that equipment used for Gabapentin production undergoes robust preventive maintenance to minimize downtime and quality issues.
            
- **Product: Lorazepam 1mg**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - Shows a relatively consistent and lower volume of opened investigations.
            - **Closed Investigations**: 
                - Closures generally track below opened investigations until mid-2024. 
                - Post-transition, the closure rate is more in line with the opening rate, preventing a significant new accumulation.
            - **Net Open Investigations**: 
                - Displays a distinct peak around mid-2024 but at a lower magnitude (around 90-100 days). 
                - The subsequent decline is gradual but consistent, indicating a manageable backlog that is slowly being reduced.
        - <u>```Resolution Categories```</u>: 
            - "On-time" (50) and "Backlog/Error" (57) are the highest. 
            - "Delayed" (10) and "Long Delay" (4) are present but not excessively high.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (50) and "Procedure Not Followed" (38) are prominent. "Operator Error" (31), "Material Contamination" (32) and "Equipment Malfunction" (28) are also present.
        - <u>```Impact Severity```</u>: 
            - Critical (44) and Moderate (95) are the most frequent.
    - <u>Recommendations</u>:
        - **Sustained Backlog Management**: 
            - Continue proactive management of "Backlog/Error" investigations for Lorazepam to ensure the trend of declining net open cases is maintained.

        - **Reinforce Key Procedures**: 
            - Focus on reinforcing critical "Procedure Not Followed" areas specific to Lorazepam to prevent new investigations.
        - **Proactive Issue Resolution**: 
            - Due to the relatively low volume, there's an opportunity to investigate each new Lorazepam investigation thoroughly and quickly, aiming for rapid root cause identification and CAPA implementation to prevent recurrence.

- **Product: Methylphenidate 10mg**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - Shows a fluctuating but high volume of opened investigations, similar to Alprazolam and Fluoxetine, indicating a steady stream of issues.
            - **Closed Investigations**: 
                - Closures consistently lag behind openings through early 2024. Post-mid-2024, while there's an effort, the closed line often stays below the opened line, showing difficulty in keeping pace.
            - **Net Open Investigations**: 
                - Exhibits a very pronounced and high peak (over 200+ days) in mid-2024, on par with Alprazolam and Fluoxetine.
                - The subsequent decline is very gradual, indicating a significant, persistent backlog that will require sustained effort to reduce. 
                - This product is a major contributor to the overall company backlog.
        - <u>```Resolution Categories```</u>: 
            - "Backlog/Error" (91) and "Ongoing" (112) are very high, along with "Delayed" (21) and "Slightly Delayed" (61). 
            - This confirms significant challenges in resolving investigations for Methylphenidate.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (122), "Procedure Not Followed" (79) and "Operator Error" (76) are the leading root causes. 
            - "Equipment Malfunction" (82) is also notably high.
        - <u>```Impact Severity```</u>: 
            - Critical (122) and Moderate (178) are the most frequent.
    - <u>Recommendations</u>:
        - **Methylphenidate-Specific Backlog Task Force**: 
            - Establish a dedicated, aggressive task force to address the significant backlog of Methylphenidate investigations, prioritizing "Backlog/Error" and "Delayed" cases.
        - **In-Depth Analysis of Critical Root Causes**: 
            - Conduct a thorough investigation into the high incidence of "Equipment Malfunction" and "Training Gaps" for Methylphenidate. 
            - This might require collaboration with engineering, equipment vendors and training departments to implement systemic solutions.
        - **Process Optimization for Methylphenidate**: 
            - Review and optimize the manufacturing and quality control processes specifically for Methylphenidate, focusing on areas prone to "Procedure Not Followed" and "Operator Error," potentially through process automation or clearer procedural steps.
        - **Enhanced Monitoring of Opened/Closed Rates**: 
            - Implement rigorous daily/weekly monitoring of opened vs. closed investigation rates for Methylphenidate. 
            - Set clear targets for closing more investigations than are opened to actively reduce the backlog.
- **Product: Sertraline 50mg**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - Shows a consistent and high volume of opened investigations, making it one of the top contributors to new issues.
            - **Closed Investigations**: 
                - Closures consistently lag behind openings through early 2024. 
                - Post-mid-2024, the closed line makes a stronger effort to keep pace or slightly exceed openings, indicating an improving, but not yet dominant, closure rate.
            - **Net Open Investigations**: 
                - Displays a prominent and high peak (over 200+ days) in mid-2024, indicating a substantial backlog. The subsequent decline is gradual, implying that while efforts are being made, the current rate of resolution is not sufficient to rapidly clear the accumulated volume, projecting a persistent backlog.
        - <u>```Resolution Categories```</u>: 
            - "On-time" (128) is highest, but "Ongoing" (100) and "Backlog/Error" (99) are also very high. "Delayed" (17) is also present. 
            - This reflects ongoing challenges in timely resolution and a significant portion related to legacy or system-related issues.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (134), "Operator Error" (83) and "Procedure Not Followed" (77) are the dominant root causes. 
            - "Material Contamination" (78) is also notably high.
        - <u>```Impact Severity```</u>: 
            - Moderate (188) and Minor (127) are the most frequent severities.

    - <u>Recommendations</u>:
        - **Sertraline-Specific Backlog Management**: 
            - Implement a focused plan for Sertraline's backlog, prioritizing "Backlog/Error" and "Ongoing" cases to accelerate their closure.
        - **Address Training & Procedural Deficiencies**: 
            - Develop and deploy targeted training programs and visual aids specifically for Sertraline manufacturing and quality control processes, addressing identified "Training Gaps" and reinforcing "Procedure Not Followed" to reduce new investigations.
        - **Investigate Material Contamination Sources**: 
            - Conduct a thorough investigation into the sources of "Material Contamination" related to Sertraline. 
            - This could involve raw material quality checks, environmental controls in production areas or improved handling protocols.
        - **Cross-Functional Team for Sertraline Issues**: 
            - Consider forming a cross-functional team (e.g., Production, QA, R&D, Supply Chain) dedicated to addressing recurring issues for Sertraline, given the high volume of investigations.

- **Product: Topiramate 25mg**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time``</u>:
            - **Opened Investigations**: 
                - Shows a relatively consistent but moderate volume of opened investigations.
            - **Closed Investigations**: 
                - Closures generally track below opened investigations until mid-2024. 
                - Post-transition, the closure rate is more in line with the opening rate, preventing a significant new accumulation.
            - **Net Open Investigations**: 
                - Displays a distinct peak around mid-2024, but at a lower magnitude (around 100-110 days) compared to high-volume products. 
                - The subsequent decline is gradual but consistent, indicating a manageable backlog that is slowly being reduced.
        - <u>```Resolution Categories```</u>: 
            - "On-time" (54) is highest, with "Backlog/Error" (45) and "Ongoing" (50) also significant. 
            - "Delayed" (12) and "Long Delay" (3) are low.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (65) and "Procedure Not Followed" (39) are the main root causes. 
            - "Operator Error" (37), "Material Contamination" (36) and "Equipment Malfunction" (33) are also present.
        - <u>```Impact Severity```</u>: 
            - Moderate (102) and Minor (56) are the most frequent.
    - <u>Recommendations</u>:
        - **Proactive Backlog Prevention**: 
            - While the backlog is manageable, maintain vigilance to prevent new accumulation for Topiramate. 
            - Focus on efficiently closing new investigations.
        - **Reinforce Specific Training**: 
            - Address the "Training Gap" and "Procedure Not Followed" root causes with targeted training relevant to Topiramate's manufacturing and quality control processes.
        - **Preventive Measures for Equipment & Contamination**: 
            - Implement robust preventive maintenance for equipment used in Topiramate's production and reinforce material handling protocols to minimize "Equipment Malfunction" and "Material Contamination."

- **Product: Venlafaxine 75mg**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>: 
            - The chart shows only one investigation opened in October 2023. 
            - The line for "Net Open Investigations" peaks at 2 days and remains flat.
            - **Opened/Closed Investigations**: 
                - Only one investigation was opened and it remains open.
            - **Net Open Investigations**: 
                - Reflects the single open investigation.
        - <u>```Resolution Categories```</u>: 
            - Only one "On-time" investigation.
        - <u>```Root Causes```</u>: 
            - Only one "Equipment Malfunction" root cause.
        - <u>```Impact Severity```</u>: 
            - Only one "Critical" investigation.

    - <u>Recommendations</u>:
        - **Verify Data Accuracy & Completeness**: 
            - Double-check whether this is the only investigation for Venlafaxine 75mg. 
            - Ensure no investigations are being miscategorized or missed. 
        - **Leverage for Proactive Maintenance**: 
            - If "Equipment Malfunction" is the root cause for this critical event, use this incident to review and enhance preventive maintenance schedules for all equipment involved in Venlafaxine production, even if overall volume is low.

#### 4.1.3. Insights and Recommendations by Investigator
- **Overall Observation (Applicable Across Investigators)**: 
    - The "Investigation Volume Over Time" chart (Opened, Closed, & Net Open) continues to show the company-wide pattern across all investigators: a sharp increase in "Net Open Investigations" peaking around mid-2024 (due to the digital system transition), followed by a gradual decline. 
    - This indicates that while the system transition created a universal backlog challenge, the ability of individual investigators to manage this backlog and new incoming investigations varies. 
    - The persistent elevated line into 2025-2027 projections for many suggests that the current investigation capacity, even across the team, is not fully overcoming the inherited backlog.

- **Investigator: A. Khan**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - A. Khan shows a relatively consistent volume of opened investigations from early 2023. 
                - There are no sudden, extreme spikes in newly opened cases under their purview.
            - **Closed Investigations**: 
                - For much of 2023 and early 2024, closed investigations lag behind opened ones. 
                - Post-mid-2024, there's a visible effort to close investigations, but the rate often falls short of the opening rate, especially after peaks in opened investigations.
            - **Net Open Investigations**: 
                - Exhibits the characteristic steep rise in early 2024, peaking sharply around mid-2024 at a high level (around 160-180 days accumulated). 
                - The subsequent decline is slow and gradual, suggesting a persistent backlog that A. Khan is struggling to significantly reduce and this backlog is projected to continue well into 2025-2027.
        - <u>```Resolution Categories```</u>: 
            - "Slightly Delayed" (91) is the highest category, followed by "Backlog/Error" (90) and "Ongoing" (88). 
            - A significant number of "Delayed" (12) and "Very Delayed" (2) and "Long Delay" (2) investigations are also noted. 
            - This indicates that a substantial portion of A. Khan's workload consists of cases that are taking longer than desired or are part of the inherited system backlog.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (98), "Procedure Not Followed" (75) and "Operator Error" (77) are the predominant root causes.
            - "Material Contamination" (50) and "Equipment Malfunction" (46) are also present. 
            - This suggests a broad range of issues that A. Khan is investigating, often linked to fundamental operational and human factors.
        - <u>```Impact Severity```</u>: 
            - Moderate (158) investigations are the most frequent, followed by Critical (98).
    - <u>Recommendations</u>:
        - **Backlog Reduction Prioritization**: 
            - A. Khan's backlog appears significant and persistent. 
            - A focused effort is needed to prioritize and accelerate the closure of "Backlog/Error," "Ongoing," and "Delayed" investigations. 
            - This could involve offloading simpler cases or providing dedicated support for complex ones.
        - **Training & Procedure Compliance Support**: 
            - Given the high incidence of "Training Gap," "Procedure Not Followed," and "Operator Error" in A. Khan's investigations, provide them with resources to effectively address these recurring issues. 
            - This might include access to specialists for training initiatives or process improvement projects.
        - **Workload Management & Triage**: 
            - Review A. Khan's current workload to ensure it is manageable. 
            - Implement a robust triage system for incoming investigations to quickly identify straightforward cases vs. complex ones, allowing A. Khan to prioritize accordingly.
        - **Root Cause Elimination Focus**: 
            - Encourage A. Khan to dedicate time to identifying systemic solutions for the recurring root causes rather than just resolving individual investigations. 
            - This could involve collaborating with relevant department heads on CAPA implementation.

- **Investigator: D. Garcia**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - D. Garcia shows a consistent volume of opened investigations, similar to A. Khan.
            - **Closed Investigations**: 
                - The closed rate generally keeps pace with opened investigations through early 2024. 
                - Post-mid-2024, while showing effort, the closed line often falls behind the opened line, indicating a struggle to keep up with the influx and backlog.
            - **Net Open Investigations**: 
                - Exhibits the strong peak in mid-2024 (around 170-180 days accumulated), indicating a substantial backlog. 
                - The subsequent decline is very gradual and slow, suggesting that D. Garcia is managing a persistent backlog that is not significantly shrinking. 
                - This projection suggests a long-term issue if current trends continue.
        - <u>```Resolution Categories```</u>: 
            - "Backlog/Error" (88) and "Ongoing" (90) are high, along with "On-time" (93). 
            - A significant number of "Delayed" (17) and "Long Delay" (7) investigations are noted, indicating challenges in timely resolution.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (100) is the leading root cause, followed by "Procedure Not Followed" (67), "Operator Error" (66), "Material Contamination" (56) and "Equipment Malfunction" (56). 
            - This indicates a broad set of issues being investigated, with training deficiencies being primary.
        - <u>```Impact Severity```</u>: 
            - Moderate (173) and Minor (92) investigations are the most frequent.

    - <u>Recommendations</u>:
        - **Aggressive Backlog Clearance Support**: 
            - Provide D. Garcia with targeted support for clearing their backlog, particularly for "Backlog/Error" and "Delayed" investigations. 
            - This could involve temporary assignment of additional resources or specific training on efficient backlog management techniques.
        - **Focus on Training Effectiveness**: 
            - Given the highest "Training Gap" among investigators, ensure D. Garcia has the necessary tools and collaboration channels to work with relevant departments (e.g., HR, departmental trainers) to address training deficiencies identified in their investigations.
        - **Process Improvement for Complex Cases**: 
            - Analyze the characteristics of D. Garcia's "Delayed" and "Long Delay" investigations. 
            - Are there specific types of cases or departments that are consistently slowing down resolution? Identify process bottlenecks and implement improvements.
        - **Regular Workload Review**: 
            - Conduct regular check-ins with D. Garcia to review workload, identify potential blockers and ensure they have the resources needed to effectively manage their investigation pipeline.

- **Investigator: J. Smith**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - J. Smith shows a consistent volume of opened investigations.
            - **Closed Investigations**: 
                - For much of 2023 and early 2024, closed investigations largely mirror opened ones. 
                - Post-mid-2024, the closed rate attempts to keep pace, but often falls slightly short or struggles to significantly exceed the opening rate.
            - **Net Open Investigations**: 
                - Exhibits the characteristic peak in mid-2024 (around 140-150 days accumulated). 
                - The subsequent decline is gradual but somewhat steadier than A. Khan or D. Garcia, suggesting J. Smith might be slightly more effective at chipping away at the backlog, but it still projects a significant amount of open investigations into 2025 and beyond.
        - <u>```Resolution Categories```</u>: 
            - "On-time" (104) is the highest. 
            - "Backlog/Error" (79) and "Ongoing" (86) are significant.
            - "Delayed" (11) and "Long Delay" (2) are present but not as high as some other investigators.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (114) is the highest root cause, followed by "Procedure Not Followed" (66) and "Material Contamination" (60). 
            - "Equipment Malfunction" (59) and "Operator Error" (46) are also notable.
        - <u>```Impact Severity```</u>: 
            - Moderate (161) and Critical (90) are the most frequent severities.

    - <u>Recommendations</u>:
        - **Sustained Backlog Reduction Momentum**: 
            - J. Smith shows better control over their backlog decline compared to some peers. 
            - Maintain this momentum by ensuring continued focus on "Backlog/Error" and "Ongoing" investigations.
        - **Proactive Training Gap Closure**: 
            - Given the high "Training Gap" for J. Smith's investigations, support them in collaborating with departments to implement proactive training interventions based on identified trends.
        - **Investigate Recurring Material & Equipment Issues**: 
            - Focus on the notable "Material Contamination" and "Equipment Malfunction" root causes. 
            - Provide J. Smith with access to relevant SMEs (e.g., Supply Chain, Engineering) to drive systemic corrective actions.
        - **Share Best Practices**: 
            - Identify any unique processes or methodologies J. Smith employs that contribute to their slightly more effective backlog reduction and consider sharing these as best practices across the investigation team.

- **Investigator: L. Zhang**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - L. Zhang shows a consistent, but moderate volume of opened investigations.
            - **Closed Investigations**: 
                - The closed rate generally keeps pace with or slightly lags opened investigations in early 2024. 
                - Post-mid-2024, the closed line makes a strong effort to keep pace with or slightly exceed openings, which is positive.
            - **Net Open Investigations**: 
                - Exhibits the characteristic peak in mid-2024 (around 170-180 days accumulated). 
                - The subsequent decline is gradual but steady, suggesting L. Zhang is making consistent progress on the backlog, but it remains a significant volume that projects into 2025 and beyond.
        - <u>```Resolution Categories```</u>: 
            - "Backlog/Error" (79) and "Ongoing" (79) are the highest, followed by "Slightly Delayed" (56). 
            - "Delayed" (16) and "Very Delayed" (1) are also present.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (100) and "Procedure Not Followed" (65) are dominant. 
            - "Operator Error" (74) and "Material Contamination" (65) are also high. 
            - "Equipment Malfunction" (44) is lower than some peers.
        - <u>```Impact Severity```</u>: 
            - Moderate (157) and Critical (92) are the most frequent severities.

    - <u>Recommendations</u>:
        - **Sustained Backlog Management**: 
            - Continue to support L. Zhang in effectively managing their "Backlog/Error" and "Ongoing" investigations to ensure the current gradual decline of net open cases continues.
        - **Targeted Training and SOP Reinforcement**: 
            - Address the high incidence of "Training Gap," "Procedure Not Followed" and "Operator Error" through targeted training and reinforcement of SOPs in the areas L. Zhang frequently investigates.
        - **Collaboration on Material Contamination**: 
            - Given the high "Material Contamination" root cause, facilitate collaboration between L. Zhang and supply chain/QA to investigate and implement solutions for recurring material issues.
        - **Leverage Digital System**: 
            - Ensure L. Zhang is fully leveraging the new digital system's features for efficient investigation processing, documentation, and reporting to maximize their productivity in clearing the backlog.

- **Investigator: M. Patel**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - M. Patel shows a consistent volume of opened investigations.
            - **Closed Investigations**: 
                - For much of 2023 and early 2024, closed investigations notably lag behind opened ones. 
                - Post-mid-2024, there's an improvement, but the closed line often remains below the opened line, making it difficult to significantly reduce the backlog.
            - **Net Open Investigations**: 
                - Exhibits the highest peak among all investigators in mid-2024 (approaching 200 days accumulated). 
                - This suggests M. Patel likely inherited a very large portion of the legacy backlog or has been assigned more complex, longer-duration investigations. 
                - The subsequent decline is very gradual and slow, indicating that M. Patel is carrying a substantial and persistently high backlog that projects far into the future.
        - <U>```Resolution Categories```</u>: 
            - "Backlog/Error" (93) and "Ongoing" (90) are very high.
            - "Delayed" (18) and "Long Delay" (3) and "Very Delayed" (2) are also significant, indicating difficulties in timely resolution.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (119) and "Procedure Not Followed" (75) are the leading root causes. 
            - "Operator Error" (73) and "Material Contamination" (62) are also high, with "Equipment Malfunction" (57) notable.
        - <u>```Impact Severity```</u>: 
            - Critical (104) and Moderate (178) investigations are most frequent.
    - <u>Recommendations</u>:
        - **Urgent & Aggressive Backlog Intervention for M. Patel**: 
            - M. Patel's backlog is the most critical. 
            - Immediate and aggressive intervention is required. 
            - This could involve re-distributing a portion of their open "Backlog/Error" or "Ongoing" investigations to other investigators or a dedicated backlog team.
        - **Mentorship/Support for Complex Cases**: 
            - Provide M. Patel with senior mentorship or direct support for their most complex or stalled investigations to help expedite resolution and build internal expertise.
        - **Deep Dive into M. Patel's Case Characteristics**: 
            - Analyze the specific characteristics of M. Patel's investigations (e.g., specific products, departments, or root causes) that contribute to such a large and persistent backlog. 
            - Are they primarily critical, long-duration, or highly complex cases?
        - **Process Improvement for M. Patel's Workflow**: 
            - Work with M. Patel to streamline their individual investigation workflow, identify any personal bottlenecks and implement strategies for more efficient case management.

- **Investigator: R. Evans**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - R. Evans shows a high and consistent volume of opened investigations, indicating a steady influx of new cases.
            - **Closed Investigations**: 
                - The closed rate for R. Evans appears to be relatively effective at keeping pace with or slightly exceeding the opened investigations, especially post-mid-2024. 
                - This is a positive indicator.
            - **Net Open Investigations**: 
                - Exhibits the characteristic peak in mid-2024 (around 170-180 days accumulated). 
                - However, the subsequent decline is noticeably steeper and more consistent than most other investigators, suggesting R. Evans is more effective at reducing their personal backlog. 
                - While still projecting open investigations, the trajectory is more favorable.
        - <u>```Resolution Categories```</u>: 
            - "On-time" (121) is the highest. 
            - "Backlog/Error" (88) and "Ongoing" (106) are significant, but "Delayed" (16) and "Long Delay" (5) are lower than some peers, implying better management of active cases.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (121), "Procedure Not Followed" (73) and "Material Contamination" (86) are the leading root causes.
            - "Operator Error" (61) and "Equipment Malfunction" (44) are also present. 
            - R. Evans appears to handle a higher proportion of contamination issues.
        Impact Severity: Moderate (179) and Critical (105) investigations are most frequent.
    - <u>Recommendations</u>:
        - **Leverage R. Evans as a Best Practice Example**: 
            - R. Evans appears to be highly effective at managing their investigation pipeline and reducing backlog. 
            - Document their processes, strategies and techniques for investigation closure and share them as best practices across the investigation team.
        - **Support for Material Contamination Expertise**: 
            - Given the high "Material Contamination" root cause, provide R. Evans with additional resources or specialized training in this area, potentially positioning them as a go-to expert for such investigations.
        - **Continued Resource Allocation**: 
            - Ensure R. Evans continues to have the necessary resources and support to maintain their efficient closure rate and help alleviate the overall company backlog.
        - **Focused CAPA Development**: 
            - Support R. Evans in developing robust CAPA plans for the recurring "Training Gap" and "Material Contamination" issues identified in their investigations to reduce the overall volume of new investigations.

- **Investigator: S. Thomas**
    - <u>Key Insights</u>:
        - <u>```Investigation Volume Over Time```</u>:
            - **Opened Investigations**: 
                - S. Thomas shows a consistent volume of opened investigations.
            - **Closed Investigations**: 
                - The closed rate generally keeps pace with or slightly lags opened investigations through early 2024.
                - Post-mid-2024, there's an effort, but the closed line often struggles to consistently exceed the opened line.
            - **Net Open Investigations**: 
                - Exhibits the characteristic peak in mid-2024 (around 150-160 days accumulated). 
                - The subsequent decline is gradual, suggesting a persistent backlog that is slowly being reduced, projecting a significant amount of open investigations into 2025 and beyond.
        - <u>```Resolution Categories```</u>: 
            - "On-time" (108) is the highest. "Backlog/Error" (87) and "Ongoing" (82) are significant. 
            - "Delayed" (13) and "Long Delay" (5) and "Very Delayed" (1) are also present.
        - <u>```Root Causes```</u>: 
            - "Training Gap" (121) is the highest root cause, followed by "Procedure Not Followed" (62) and "Operator Error" (62).
            - "Equipment Malfunction" (51) and "Material Contamination" (40) are also noted.

        - <u>```Impact Severity```</u>: 
            - Moderate (163) and Critical (93) are the most frequent severities.

    - <u>Recommendations</u>:
        - **Backlog Management Support**: 
            - Provide S. Thomas with targeted support to help accelerate the reduction of their "Backlog/Error" and "Ongoing" investigations. 
            - This could involve temporary assistance or specific guidance on prioritizing older cases.
        - **Address Training & Procedural Compliance**: 
            - Focus on the high incidence of "Training Gap," "Procedure Not Followed" and "Operator Error" identified in S. Thomas's investigations. 
            - This requires close collaboration with relevant departmental managers to implement effective training and procedural adherence programs.
        - **Workload Balancing**: 
            - Assess S. Thomas's overall workload and consider if re-balancing is necessary to enable them to more effectively manage their pipeline and dedicate sufficient time to backlog reduction.
        - **Root Cause Analysis Enhancement**: 
            - Support S. Thomas in strengthening their root cause analysis skills, particularly for complex cases, to ensure that recurring issues are identified and addressed systemically, thereby preventing new investigations from being opened.

---
### 4.2. Dashboard 2: Resolution Performance & Severity
![alt text](<dashboard 2.png>)

#### 4.2.1. Insights and Recommendations by Department
- **Overall Departmental Observations**:
    - <u>Significant Backlog Growth Post-Digital Transition</u>: 
        - Across all departments, the "Moving Average (Incl. Backlog/Error)" for resolution days shows a dramatic and sustained increase starting around mid-2024. 
        - This strongly suggests that the transition to the digital system either introduced a substantial backlog that was carried over, or the new system itself has inherent inefficiencies contributing to prolonged resolution times, especially when including backlog/error cases. 
        - The "Moving Average (Excl. Backlog/Error)" generally remains low and stable, reinforcing that the inclusion of backlog/error cases is the primary driver of the extended resolution times.
    - <u>Resolution Challenges Across All Severities</u>: 
        - All departments exhibit spikes in resolution times for Critical, Moderate and Minor cases when backlog/error is included, indicating that the challenges are not confined to a specific severity level.
    - <u>CAPA Backlog</u>: 
        - A consistent number of open CAPAs across all departments (ranging from 111 to 181) suggests that corrective and preventive actions are also lagging, which could contribute to recurrent investigations.

- **Overall Strategic Recommendations (Applicable to All Departments)**:
    - **Dedicated Backlog Resolution Initiative**: 
        - Establish a cross-functional team with clear targets and resources to aggressively tackle the accumulated backlog of investigations, focusing first on Critical and then Moderate cases.
    - **Digital System Optimization & User Training**: 
        - Conduct a comprehensive audit of the new digital documentation system's implementation. Identify and rectify any system-related bottlenecks, bugs, or user interface issues. 
        - Mandate and provide in-depth, hands-on training for all users on proper documentation, classification, and closure procedures within the new system.
    - **Refine "Backlog/Error" Category**: 
        - Investigate the specific reasons for investigations being categorized as "Backlog/Error." 
        - Is it truly legacy backlog or are new errors in the digital system or processes causing misclassification or re-opening of cases? 
        - This understanding is critical for targeted remediation.
    - **Strengthen CAPA Effectiveness**: 
        - Implement a more rigorous CAPA follow-up and verification process. 
        - Ensure that closed CAPAs are demonstrably effective in preventing recurrence of the initial issue. 
        - Consider linking investigator performance to CAPA closure rates.
    - **Data Quality & Integrity**: 
        - Ensure that data entered into the new digital system is accurate and complete, as poor data quality can lead to misclassified investigations and skewed performance metrics.
    - **Establish Baseline & Monitor Progress**: 
        - Given the regulatory focus, it is imperative to establish a clear baseline of "Excl. Backlog/Error" resolution times for each severity level and department. 
        - Regularly monitor these metrics to demonstrate continuous improvement and compliance readiness.


- **Packaging Department**
    - <u>Insights</u>:
        - **High Total Investigations with Significant Open Cases**:
            - Packaging has 499 total investigations with 118 open, indicating a notable volume of unresolved issues.
        - **Severe Impact of Backlog on Resolution**: 
            - The overall moving average for resolution days sharply escalates from mid-2024, reaching close to 1000 days. 
            - This is almost entirely driven by the "Incl. Backlog/Error" metric, with the "Excl. Backlog/Error" average remaining very low, confirming that the backlog/error investigations are overwhelmingly impacting resolution performance.
        - **Concentrated Spikes in Mid-2025**: 
            - There are distinct, high-duration spikes in Critical, Moderate, and Minor case resolution times (when including backlog/error) occurring around mid-2025, suggesting a period of acute backlog processing or identification.
        - **Moderate CAPA Open Count**: 
            - With 145 open CAPAs, there's a need to address these to prevent future investigations.

    - <u>Recommendations</u>:
        - **Prioritize Backlog Remediation for Packaging**: 
            - Immediately establish a dedicated task force to triage and resolve the outstanding backlog/error investigations, especially those driving the mid-2025 spikes.
        - **Process Review for Digital System Integration**: 
            - Investigate if the digital system's integration with Packaging workflows is introducing bottlenecks or complexity that exacerbates backlog accumulation.
        - **Targeted Training**: 
            - Assess if Packaging personnel require additional training on the new digital system's functionalities, particularly regarding investigation documentation and closure procedures, to reduce "error" related investigations.

- **Production Department**
    - <u>Insights</u>:
        - **Highest Open CAPAs**: 
            - Production has 181 open CAPAs, the highest among all departments, suggesting a significant volume of unaddressed root causes that could be leading to new investigations.
        - **Consistent Backlog Impact**: 
            - Similar to Packaging, Production shows a dramatic rise in the "Moving Average (Incl. Backlog/Error)" from mid-2024, indicating a substantial and persistent backlog effect.
        -**Prominent Spikes Across Severities**: 
            - Critical, Moderate and Minor cases all show severe, high-duration spikes in resolution days (including backlog/error) around mid-2025, similar to Packaging, pointing to systemic backlog issues.
        - **High Critical and Moderate Impact**: 
            - Production reports 158 Critical and 76 Moderate impact severity investigations, indicating a focus on more severe issues.
    - <u>Recommendations</u>:
        - **Aggressive CAPA Closure Strategy**: 
            - Implement a robust plan to close outstanding CAPAs in Production. 
            - Link CAPA closure to investigation reduction targets.
        - **Root Cause Analysis Enhancement**: 
            - Given the high number of critical and moderate investigations, conduct a deeper dive into common root causes within Production to identify systemic failures requiring more comprehensive solutions.
        - **Workflow Optimization Post-Digital Transition**: 
            - Review Production's investigation workflow within the new digital system to identify and eliminate redundancies or inefficiencies that contribute to the backlog.

- **QA Department**
    - <u>Insights</u>:
        - **Relatively Lower Open Investigations**: 
            - QA has 116 open investigations out of 482 total, which is comparatively lower than Packaging and Production in terms of percentage open.
        - **Significant Contribution to Backlog**: 
            - Despite lower open numbers, the "Moving Average (Incl. Backlog/Error)" for QA follows the same sharp upward trend from mid-2024, highlighting QA's involvement in the broader company-wide backlog challenge.
        - **Spikes in Resolution Times Still Present**: 
            - QA also experiences the mid-2025 spikes across all severity levels when backlog/error is included, indicating that even in a quality oversight role, they are impacted by or contributing to the delayed resolution of these cases.
        - **High Number of Minor Impact Cases**: 
            - QA reports a high number of minor impact cases (128), which, while individually less severe, can contribute significantly to the overall volume and backlog if not efficiently managed.

    - <u>Recommendations</u>:
        - **Streamline QA Review Processes**: 
            - Examine QA's review and approval processes within the new digital system for potential bottlenecks that contribute to the "backlog/error" category, especially for minor investigations.
        - **Digital System Proficiency for QA**: 
            - Ensure QA personnel are fully proficient with the digital system's audit trail, reporting, and workflow features to facilitate faster and more accurate investigation closure.
        - **Collaborative Backlog Resolution**: 
            -  QA should actively collaborate with Packaging and Production to facilitate the closure of joint investigations, especially those categorized as backlog/error, given their oversight role.

- **QC Lab Department**
    - <u>Insights</u>:
        - **Similar Backlog Trend**: 
            - The QC Lab also exhibits the identical sharp increase in "Moving Average (Incl. Backlog/Error)" from mid-2024, indicating they are equally affected by the system transition and accumulated backlog.
        - **High Volume of Moderate and Minor Cases**: 
            - QC Lab has a significant number of Moderate (124) and Minor (299) impact severity investigations, suggesting issues related to testing, analysis, or data handling.
        - **Identical Spikes in Resolution Times**: 
            - The prominent spikes in resolution days for Critical, Moderate and Minor cases in mid-2025 are consistent with other departments, pointing to the pervasive nature of the backlog.

    - <u>Recommendations</U>:
        - **Review QC Testing and Documentation Procedures**: 
            - Conduct a thorough review of QC Lab's testing methodologies, equipment calibration and documentation practices within the digital system to identify sources of "backlog/error" investigations.
        - **Automate Data Entry/Reporting**: 
            - Explore opportunities for greater automation in QC data entry and reporting to reduce manual errors and expedite investigation initiation and closure.
        - **Inter-departmental Coordination for Shared Investigations**:
            - Enhance coordination between QC Lab and departments like Production or R&D for investigations that cross departmental boundaries, ensuring clear ownership and efficient resolution.

- **R&D Department**
    - <u>Insights</u>:
        - **Lower Critical Investigations but High Moderate/Minor**: 
            - R&D has the lowest number of Critical investigations (87) but a substantial number of Moderate (214) and Minor (230) cases, indicating potential issues in development, formulation, or early-stage product quality.
        - **Lowest Open CAPAs**: 
            - R&D has the lowest number of open CAPAs (91), which is a positive sign for addressing root causes, though still requires attention.
        - **Consistent Backlog Impact**: 
            - Despite the lower critical count, R&D's resolution performance is also severely impacted by the "Moving Average (Incl. Backlog/Error)" rising sharply from mid-2024, mirroring the trend in other departments.
        - **Mid-2025 Spikes**: 
            - R&D also displays the characteristic high-duration spikes in resolution times across all severities in mid-2025, driven by backlog.
    
    - <u>Recommendations</u>:
        - **Focus on Development Stage Quality Controls**: 
            - Investigate the nature of Moderate and Minor investigations originating from R&D. 
            - Are there opportunities to implement stricter quality controls or FMEAs (Failure Mode and Effects Analysis) during product development to prevent issues from propagating?
        - **Knowledge Transfer and Documentation**: 
            - Ensure robust documentation and knowledge transfer from R&D to Production and QC to minimize quality issues arising from scale-up or manufacturing hand-off.
        - **Early Issue Identification**: 
            - Leverage the digital system to track and identify potential quality issues earlier in the R&D pipeline, reducing the likelihood of them becoming larger investigations post-release.

#### 4.2.2. Insights and Recommendations by Product
- **Overall Product-Level Observations**:
    - **Universal Backlog Impact**: 
        - The "Moving Average (Incl. Backlog/Error)" line shows a sharp, unsustainable rise from mid-2024 onwards for nearly all products, indicating that the company-wide challenge of managing carried-over investigations and/or errors from the new digital system is impacting the resolution of issues across the entire product portfolio.
    - **Minimal Impact Excluding Backlog**: 
        - Conversely, the "Moving Average (Excl. Backlog/Error)" line generally remains low and stable across most products, confirming that the underlying processes for new investigations (once the backlog is removed from consideration) are relatively efficient in terms of resolution time.
    - **Spikes in Mid-2025**: 
        - Many products exhibit significant spikes in resolution times for all severities (Critical, Moderate, Minor) around mid-2025, when "backlog/error" cases are included. 
        - This suggests a period of intensive processing or identification of these problematic investigations.
    - **Variability in Investigation Volume & Severity**: 
        - While the backlog trend is universal, the total number of investigations, open cases and the distribution of impact severity vary significantly by product, highlighting areas for focused quality improvement.

- **Overall Strategic Recommendations (Applicable to All Products)**:
    - **Prioritized Backlog Reduction by Impact**: 
        - Categorize the outstanding backlog investigations by product and then by severity. 
        - Develop a focused plan to clear Critical and High-Volume Moderate backlog investigations first for high-impact products (e.g., Fluoxetine 20mg, Methylphenidate 10mg, Alprazolam 0.5mg, Sertraline 50mg).
    - **Product-Specific Digital System Integration Review**: 
        - While the backlog is systemic, there might be product-specific nuances in how the digital system interacts with different manufacturing or quality control processes. 
        - Conduct targeted reviews for high-volume products.
    - **Cross-Product Best Practice Sharing**: 
        - Facilitate knowledge sharing sessions.
        - Analyze the processes and controls for products with minimal investigations (e.g., Duloxetine 30mg, Venlafaxine 75mg) and identify transferable best practices to reduce investigation volumes for other products.
    - **Proactive Quality Monitoring**: 
        - Implement enhanced, real-time quality monitoring for high-volume and high-severity products. 
        - Utilize statistical process control (SPC) for key parameters to identify deviations before they escalate into formal investigations.
    - **Strengthen Vendor Quality Management**: 
        - Investigate if any common raw materials or components used across high-investigation products are sourced from specific vendors. 
        - Strengthen vendor qualification and ongoing monitoring where necessary.


-  **Alprazolam 0.5mg**
    -   <u>Insights</u>:
        - **High Investigation Volume**: 
            - With 402 total investigations and 106 open, Alprazolam 0.5mg is a high-volume product in terms of quality events.
        - **Balanced Severity Distribution**: 
            - It has a relatively balanced distribution of critical (104), moderate (104), and minor (102) investigations, indicating issues across the spectrum.
        - **Significant Backlog Burden**: 
            - The product is heavily impacted by the company-wide backlog, with resolution times rising dramatically from mid-2024 and pronounced spikes across all severities in mid-2025 when backlog/error is included.
        - **High Open CAPA Count**: 
            - 105 open CAPAs suggest that corrective actions related to Alprazolam 0.5mg are not being closed efficiently.

    - <u>Recommendations</u>:
        - **Deep Dive into Root Causes**: 
            - Conduct a thorough root cause analysis specifically for Alprazolam 0.5mg investigations. 
            - Given the high volume and balanced severity, there might be recurring manufacturing, packaging or raw material issues.
        - **Prioritize CAPA Closure**: 
            - Expedite the closure of the 105 open CAPAs linked to this product to prevent recurrence of issues and reduce future investigation volumes.
        - **Targeted Process Review**: 
            - Review the end-to-end process for Alprazolam 0.5mg (from raw material to distribution) to identify any unique bottlenecks or quality control gaps that contribute to investigations.

- **Clonazepam 0.5mg**
    - <u>Insights</u>:
        - **Lower Total Investigations but High Open Percentage**:
            - Clonazepam 0.5mg has 195 total investigations, but 44 remain open, representing a higher proportion of open cases compared to some other products (approx. 22.5%).
        - **Relatively Balanced Severity**: 
            - Similar to Alprazolam, it shows a mix of Critical (51), Moderate (53) and Minor (91) investigations.
        - **Standard Backlog Pattern**: 
            - The product exhibits the universal backlog trend with resolution times spiking due to backlog/error cases from mid-2024.
        - **Fewer Open CAPAs**: 
            - With 58 open CAPAs, it's relatively better than Alprazolam, but still requires attention.

    - <u>Recommendations</u>:
        - **Focus on Resolution Efficiency**: 
            - Investigate why the percentage of open investigations for Clonazepam 0.5mg is relatively high despite lower total volume. 
            - This might indicate specific challenges in closing these cases.
        - **Review Closure Procedures**: 
            - Ensure that the digital system's closure procedures for Clonazepam investigations are clear and that relevant personnel are trained to avoid "backlog/error" categorizations.

- **Duloxetine 30mg & Venlafaxine 75mg**
    - <u>Insights</u>:
        - **Minimal Investigations**: 
            - Both Duloxetine 30mg and Venlafaxine 75mg show only 1 total investigation each, with 0 or 1 open and 0 open CAPAs. 
            - The resolution times for Venlafaxine are also very low (around 1 day).

    - <u>Recommendations</u>:
        - **Benchmark Best Practices**: 
            - Analyze the manufacturing, quality control and documentation processes for Duloxetine 30mg and Venlafaxine 75mg. 
            - These products represent best practices in terms of low investigation volume and efficient resolution.
        - **Replicate Success**: 
            - Identify key factors contributing to their excellent performance and explore how these practices can be replicated across other products to reduce investigations and improve resolution times.

- Fluoxetine 20mg
    - <u>Insights</u>:
        - **Highest Total Investigations**: 
            - Fluoxetine 20mg stands out with 447 total investigations, making it a primary driver of overall investigation volume.
        - **High Critical and Minor Cases**: 
            - It has a high number of Critical (115) and Minor (211) investigations, indicating issues that are both severe and frequent.
        - **Significant Backlog Contribution**: 
            - This product heavily contributes to the company's overall backlog, showing the typical severe rise in "Incl. Backlog/Error" resolution times from mid-2024.
        - **Highest Open CAPAs**: 
            - With 135 open CAPAs, Fluoxetine 20mg has the most outstanding corrective actions, posing a significant risk for recurrent issues.

    - <u>Recommendations</u>:
        - **Top Priority for Improvement**: 
            - Fluoxetine 20mg should be the highest priority for quality improvement efforts.
        - **Comprehensive Process Audit**: 
            - Conduct a full, in-depth audit of the entire lifecycle for Fluoxetine 20mg – from raw materials and manufacturing to packaging and distribution – to pinpoint the root causes of its high investigation volume and critical issues.
        - **Aggressive CAPA Management**: 
            - Implement an immediate and aggressive plan to address and close the 135 open CAPAs. Link these CAPAs directly to specific process or equipment improvements.

- **Gabapentin 300mg**
    - <u>Insights</u>:
        - **Moderate Investigation Volume**: 
            - Gabapentin 300mg has 230 total investigations with 57 open, placing it in the mid-range for volume.
        - **Significant Moderate Impact**: 
            - A notable 59 Moderate impact severity cases, suggesting issues that are not critical but still require substantial resources.
        - **Standard Backlog Effect**: 
            - Exhibits the consistent trend of rising resolution times due to backlog/error from mid-2024.

    - <u>Recommendations</u>:
        - **Focus on Moderate Issue Prevention**: 
            - Investigate common themes among the 59 Moderate impact investigations. 
            - Are these related to specific equipment, batch processes or operator errors that can be mitigated?
        - **Process Efficiency for Mid-Severity**: 
            - Review processes for managing moderate investigations to ensure they are resolved efficiently and do not unnecessarily contribute to the backlog.

- **Lorazepam 1mg**
    - <u>Insights</u>:
        - **Lower Overall Volume**: 
            - Lorazepam 1mg has 188 total investigations with 37 open, one of the lower volume products.
        - **Proportionately High Minor Cases**: 
            - While total investigations are lower, it has a high number of Minor (108) cases relative to Critical (44) and Moderate (95).
        - **Exhibits Backlog Trend**: 
            - Despite lower volume, it still shows the pervasive impact of backlog/error investigations on its resolution times.

    - <u>Recommendations</u>:
        - **Streamline Minor Investigation Process**: 
            - For Lorazepam 1mg, focus on optimizing the process for resolving minor investigations. 
            - Automation or simplified procedures for these less severe cases could free up resources.
        - **Batch Record Review**: 
            - Given the potential for minor issues, consider a periodic review of batch records for Lorazepam 1mg to proactively identify trends before they escalate into investigations.

- **Methylphenidate 10mg**
    - <u>Insights</u>:
        - **High Investigation Volume**: 
            - Similar to Alprazolam, Methylphenidate 10mg has a high investigation count (402 total, 112 open).
        - **High Critical and Moderate Impact**: 
            - With 122 Critical and 178 Moderate investigations, this product frequently experiences significant issues requiring substantial effort to resolve.
        - **High Open CAPAs**: 
            - 126 open CAPAs indicate a need for robust corrective action.
        - **Pronounced Backlog Impact**: 
            - The resolution performance is heavily burdened by the backlog/error investigations.

    - <u>Recommendations</u>:
        - **Immediate Deep Dive for Critical/Moderate**: 
            - Prioritize a comprehensive investigation into the root causes of Critical and Moderate issues for Methylphenidate 10mg. 
            - These indicate potential failures in core processes.
        - **Intensify CAPA Remediation**: 
            - Accelerate the closure of CAPAs specific to Methylphenidate 10mg to mitigate high-severity risks.
        - **Cross-Functional Team**: 
            - Consider assigning a dedicated cross-functional team to address the recurrent issues associated with this high-impact product.

- **Sertraline 50mg**
    - <u>Insights</u>:
        - **High Investigation Volume**: 
            - Sertraline 50mg is another high-volume product with 424 total investigations and 100 open.
        - **High Moderate and Minor Cases**: 
            - It has a significant number of Moderate (188) and Minor (127) investigations.
        - **Persistent Backlog**: 
            - The product shows the characteristic sharp increase in resolution times due to backlog/error from mid-2024.
        - **Moderate Open CAPAs**: 
            - 113 open CAPAs need to be addressed.

    - <u>Recommendations</u>:
        - **Focus on Moderate Issue Prevention**: 
            - Investigate the commonality among the 188 Moderate investigations for Sertraline 50mg. 
            - This volume suggests recurring non-critical deviations that, while individually manageable, collectively consume significant resources.
        - **Preventative Maintenance & Calibration**: 
            - Explore whether inadequate preventative maintenance or calibration of equipment used for Sertraline 50mg manufacturing contributes to these moderate issues.

- **Topiramate 25mg**
    - <u>Insights</u>:
        - **Moderate Volume**: 
            - Topiramate 25mg has 210 total investigations with 58 open, placing it in the mid-range.
        - **Relatively Balanced Severity**: 
            - Shows a mix of Critical (52), Moderate (102) and Minor (56) cases.
        - **Standard Backlog Impact**: 
            - Demonstrates the same backlog-driven increase in resolution times.

    - <u>Recommendations</u>:
        - **Standardized Problem Solving**: 
            - Utilize standardized problem-solving methodologies (e.g., 5 Whys, Fishbone diagrams) for Topiramate 25mg investigations to ensure thorough root cause identification and effective CAPA implementation.
        - **Review Digital Workflow**: 
            - Assess if the digital workflow for Topiramate 25mg investigations is causing any specific delays or "error" classifications.

#### 4.2.3 Insights and Recommendations by Investigator
- **Overall Investigator Observations**:
    - **Systemic Backlog Impact**: 
        - All investigators are clearly grappling with the same dramatic increase in resolution days, driven by the "Moving Average (Incl. Backlog/Error)" from mid-2024. 
        - This confirms the company-wide nature of the backlog challenge, stemming from the digital transition or accumulated prior issues, rather than individual investigator inefficiency.

    - **Efficient Resolution (Excluding Backlog)**: 
        - For nearly all investigators, the "Moving Average (Excl. Backlog/Error)" remains consistently low, suggesting that when free from the burden of the backlog/error cases, investigators are generally efficient in resolving new investigations within reasonable timelines.
    - **Mid-2025 Spikes**: 
        - The prominent, high-duration spikes in Critical, Moderate and Minor case resolution times (when including backlog/error) around mid-2025 are a common feature across all investigators, indicating a period of significant backlog processing or identification.
    - **Consistent Open CAPA Burden**: 
        - A significant number of open CAPAs is observed for almost all investigators, implying that corrective actions are a bottleneck regardless of the individual investigator, possibly due to process delays or resource constraints.

- **Overall Strategic Recommendations (Applicable to All Investigators)**:
    - **Backlog Task Force & Dedicated Resources**: 
        - The consistent and severe impact of "Incl. Backlog/Error" on all investigators' resolution times screams for a dedicated, cross-functional task force to specifically address the legacy backlog and system-induced errors. 
        - This backlog should be isolated and resolved separately, allowing investigators to focus on new issues.
    - **Digital System User Training & Support**: 
        - Conduct mandatory, advanced training for all investigators on the full capabilities of the new digital documentation system. Focus on areas that cause "error" classifications or delays in investigation closure. 
        - Provide easily accessible technical support for system issues.
    - **CAPA Management Process Optimization**: 
        - Review and streamline the entire CAPA lifecycle – from initiation and root cause identification to implementation, verification, and closure. 
        - Identify bottlenecks (e.g., approval workflows, resource allocation for CAPA execution) that lead to the high number of open CAPAs.
    - **Workload Balancing & Capacity Planning**: 
        - Regularly monitor investigator workloads based on total investigations, open investigations, and CAPA assignments. Implement a system for dynamic workload balancing to prevent certain investigators from becoming overwhelmed.
    - **Performance Metrics Refinement**: 
        - For internal performance measurement, consider separating "new" investigation resolution times from "backlog/error" resolution times to provide a clearer picture of investigator efficiency.
    - **Investigator Collaboration & Best Practices**: 
        - Foster a culture of collaboration among investigators. Encourage regular meetings to discuss challenging investigations, share best practices and collectively identify systemic issues or training needs.
    - **Empowerment for Resolution**: 
        - Ensure investigators have the necessary authority and resources (e.g., access to subject matter experts, equipment, data) to complete investigations and CAPAs without undue external delays.



- **A. Khan**
    - <u>Insights</u>:
        - **Moderate Workload**: 
            - A. Khan has a moderate total investigation count (346) with 88 open, which is in line with the average.
        - **Balanced Severity Profile**: 
            - The impact severity is relatively balanced across Critical (98), Moderate (90) and Minor (150).
        - **Standard Backlog Impact**: 
            - A. Khan's dashboard shows the typical sharp rise in "Incl. Backlog/Error" resolution times from mid-2024.
        - **High Open CAPAs**: 
            - With 94 open CAPAs, A. Khan has a considerable backlog of corrective actions.

    - <u>Recommendations</u>:
        - **Support for Backlog Clearance**: 
            - Provide A. Khan with additional resources or assistance specifically for clearing backlog/error investigations.
        - **CAPA Prioritization Training**: 
            - Offer training on effective CAPA prioritization and management strategies to help reduce the open CAPA count.

- **D. Garcia**
    - <u>Insights</u>:
        - **Consistent Workload**: 
            - D. Garcia's workload (345 total investigations, 90 open) is very similar to A. Khan's.
        - **Slightly Higher Minor Cases**: 
            - A slightly higher proportion of Minor (92) investigations compared to Critical (80) and Moderate (73).
        - **Identical Backlog Trend**: 
            - Displays the same backlog-driven resolution time increase.
        - **High Open CAPAs**: 
            - 100 open CAPAs indicate a significant pending workload.

    - <u>Recommendations</u>:
        - **Workflow Efficiency Review**: 
            - Review D. Garcia's investigation workflow, especially for minor cases, to identify any specific bottlenecks that might contribute to the backlog of open cases.
        - **Access to Support Systems**: 
            - Ensure D. Garcia has seamless access to all necessary resources (e.g., subject matter experts, digital system support) to expedite investigation closure.

- **J. Smith**
    - <u>Insights</u>:
        - **Consistent Workload and Backlog**: 
            - J. Smith mirrors A. Khan and D. Garcia in terms of total investigations (345), open cases (86) and the overall backlog trend.
        - **Higher Moderate Cases**: 
            - J. Smith has a higher number of Moderate (161) investigations compared to Critical (90) and Minor (94), suggesting a focus on or assignment of more complex mid-severity issues.
        - **High Open CAPAs**: 
            - With 104 open CAPAs, J. Smith also faces a substantial CAPA backlog.

    - <u>Recommendations</u>:
        - **Moderate Case Resolution Support**: 
            - Provide J. Smith with advanced training or tools for more efficient resolution of moderate-severity investigations, given the higher volume.
        - **Load Balancing Consideration**: 
            - Assess if J. Smith's workload, particularly regarding moderate cases and CAPAs, needs to be rebalanced with other investigators.

- **L. Zhang**
    - <u>Insights</u>:
        - **Slightly Higher Open Percentage**: 
            - L. Zhang has 348 total investigations with 79 open, representing a slightly lower absolute number of open investigations but still contributing to the overall backlog.
        - **Impact Severity Mix**: 
            - Similar impact severity mix to other investigators.
        - **Clear Backlog Impact**: 
            - The dashboard clearly shows the backlog's severe impact on resolution times from mid-2024.
        - **Moderate Open CAPAs**: 
            - L. Zhang has 101 open CAPAs, indicating a similar challenge with corrective action closure.

    - <u>Recommendations</u>:
        - **Focus on Final Closure**: 
            - Identify if L. Zhang faces any particular hurdles in the final steps of investigation closure that contribute to cases remaining open.
        - **Digital System Proficiency Audit**: 
            - Conduct a brief audit of L. Zhang's usage of the new digital system to identify any areas where further training could improve efficiency in closing cases, particularly those affected by "error" classifications.

- **M. Patel**
    - <u>Insights</u>:
        - **Highest Total and Open Investigations**: 
            - M. Patel stands out with the highest number of total investigations (386) and open investigations (90) among the group, indicating a potentially heavier workload.
        - **High Critical and Moderate Impact**: 
            - M. Patel also has a high number of Critical (104) and Moderate (178) investigations, suggesting responsibility for a higher volume of more complex or impactful issues.
        - **Most Open CAPAs**: 
            - With 118 open CAPAs, M. Patel has the highest number of outstanding corrective actions.
        - **Pronounced Backlog Effect**: 
            - The impact of the "Incl. Backlog/Error" on resolution times is severe and consistent with the overall trend.

    - <u>Recommendations</u>:
        - **Workload Redistribution**: 
            - Seriously consider redistributing some of M. Patel's investigation workload, especially for new incoming critical and moderate cases, to ensure they can effectively manage the existing high volume.
        - **Dedicated Backlog Support**: 
            - Provide M. Patel with dedicated administrative or technical support specifically for clearing the accumulated backlog/error investigations and associated CAPAs.
        - **Advanced Root Cause Training**: 
            - Given the high number of critical and moderate cases, advanced training in root cause analysis and CAPA development might benefit M. Patel.

- **R. Evans**
    - <u>Insights</u>:
        - **High Workload, Similar to M. Patel**: 
            - R. Evans also has a high total investigation count (386) and 106 open cases, making this investigator another with a heavy workload.
        - **High Critical and Moderate Impact**: 
            - With 105 Critical and 179 Moderate investigations, R. Evans, like M. Patel, is handling a large volume of significant issues.
        - **High Open CAPAs**: 
            - R. Evans also has a high number of open CAPAs (113).
        - **Consistent Backlog Trend**: 
            - Shows the same severe backlog impact on resolution times.

    - <u>Recommendations</u>:
        - **Workload Balancing & Support**: 
            - Similar to M. Patel, assess R. Evans' workload and provide additional support, including potential redistribution of new investigations, to help manage the current load and backlog.
        - **CAPA Expediting**: 
            - Focus on expediting the closure of R. Evans' open CAPAs, potentially by providing dedicated follow-up support or streamlining the approval process for CAPA closure.

- **S. Thomas**
    - <u>Insights</u>:
        - **Lowest Total and Open Investigations**: 
            - S. Thomas has the lowest total investigations (344) and open investigations (82) among the group.
        - **Lower Critical/Moderate Cases**: 
            - Also has slightly lower Critical (93) and Moderate (88) impact cases compared to other investigators handling higher volumes.
        - **Lowest Open CAPAs**: 
            - With 105 open CAPAs, while still significant, it's lower than M. Patel and R. Evans.
        - **Still Impacted by Backlog**: 
            - Despite lower volume, S. Thomas's resolution times are still heavily influenced by the company-wide backlog.

    - <u>Recommendations</u>:
        - **Leverage for Backlog Projects**: 
            - Given the comparatively lower new investigation volume, S. Thomas could be a valuable resource to dedicate more time to the overall company backlog clearance initiative.
        - **Knowledge Sharing**: 
            - Encourage S. Thomas to share any efficient investigation resolution practices they employ, particularly if they are finding ways to navigate the system effectively.

---
### 4.3. Dashboard 3: Product Quality Metrics and Variability
![alt text](<dashboard 3.png>)

---
#### 4.3.1. Insights and Recommendations by Department
- **Overall Departmental Observations**:
    - <u>pH Clustering</u>: 
        - All departments show similar clustering of products based on their pH levels. There are distinct groups:
            - <u>Low pH >(~3.5-4.5)</u>: 
                - Appears to include products like Lorazepam 1mg and potentially others.
            - <u>Mid-range pH (~5.0-6.0)</u>: 
                - A denser cluster with products like Alprazolam 0.5mg, Clonazepam 0.5mg, Fluoxetine 20mg, Gabapentin 300mg, Methylphenidate 10mg, Sertraline 50mg and Topiramate 25mg.
            - <u>Higher pH (~6.5-7.5)</u>: 
                - A smaller cluster including products like Duloxetine 30mg and Venlafaxine 75mg.
    - <u>Particle Size Variability</u>: 
        - Across all departments, there's significant variability in particle size for most products, with some having wide interquartile ranges and numerous outliers. 
        - This is a critical area for potential quality issues.
    - <u>Correlation Potential</u>: 
        - The scatter plot (Particle Size vs pH) shows some trends, indicating that certain particle size ranges might be associated with specific pH ranges. 
        - This could hint at formulation, processing or raw material-related variabilities that are worth investigating.
    - <u>Consistent Product Distribution</u>: 
        - The distribution of products and their quality attributes (pH and particle size) remains largely consistent across all departments, implying that the inherent product characteristics and the general manufacturing processes are similar, regardless of which department is focused on. 
        - This also means that any observed variability is likely systematic rather than department-specific.

- **Overall Strategic Recommendations (Applicable to All Departments for Quality Variability)**:
    - **Define Acceptable Variability & Targets**: 
        - Beyond current specifications, establish internal targets and ranges for "acceptable" particle size and pH variability for each product based on performance and historical data. 
        - This proactively defines process control.
    - **Product-Specific Quality Improvement Plans**: 
        - For products exhibiting high variability (e.g., Methylphenidate 10mg, Sertraline 50mg, Fluoxetine 20mg), develop specific, cross-functional quality improvement plans targeting particle size and pH.
    - **Advanced Analytical Techniques**: 
        - Explore the adoption of advanced analytical techniques for in-line or at-line monitoring of particle size and pH during manufacturing to provide real-time feedback and reduce batch-to-batch variability.
    - **Correlation Analysis**: 
        - Perform a more detailed statistical correlation analysis between particle size/pH variability and investigation volumes (and resolution times) across all products. 
        - This will quantify the impact and prioritize interventions.
    - **Cross-Functional Quality Teams**: 
        - Establish cross-functional teams (R&D, Production, QC, QA) dedicated to addressing product quality variability for high-impact products, leveraging expertise from all stages of the product lifecycle.


- **Packaging Department**

    - <u>Insights</u>:
        - **Impact of Packaging on Particle Size/pH**: 
            - While Packaging does not directly produce the product, variations in packaging processes (e.g., compaction, filling, handling) can impact particle size integrity (e.g., attrition, agglomeration) and indirectly, moisture content which affects pH stability.
        - **High Variability Products**: 
            - The box plots show several products with wide particle size distributions (e.g., Methylphenidate 10mg, Sertraline 50mg, Fluoxetine 20mg, Alprazolam 0.5mg) and some with broader pH ranges (e.g., Fluoxetine 20mg, Sertraline 50mg). 
            - These are the same products that had high investigation volumes in the previous dashboard analysis.
        - **Open Investigations/CAPAs**: 
            - Packaging has 118 open investigations and 145 open CAPAs, which could include issues related to product quality attributes if they manifest during or post-packaging.

    - <u>Recommendations</u>:
        - **Investigate Packaging Process Impact**: 
            - Conduct studies to assess the impact of different packaging machine settings, material handling and storage conditions on the particle size and pH stability of sensitive products (e.g., Methylphenidate 10mg, Sertraline 50mg).
        - **Integrate Quality Checks at Packaging**: 
            - Implement more rigorous in-process quality checks (e.g., at-line particle size analysis, pH checks) within the Packaging department for high-variability products.
        - **Correlation with Investigations**: 
            - Analyze if any of the open investigations in Packaging are directly linked to out-of-specification particle size or pH levels observed in finished goods.

- **Production Department***

    - <u>Insights</u>:
        - **Direct Influence on Product Quality**: 
            - Production is where the core manufacturing takes place, directly influencing particle size and pH.
            - The observed variability is a direct reflection of production process control.
        - **Pronounced Variability for Key Products**: 
            - The box plots highlight significant particle size variability for products like Methylphenidate 10mg, Sertraline 50mg, and Fluoxetine 20mg, and a broader pH range for Fluoxetine 20mg and Sertraline 50mg.
            - These products were also identified as having high investigation volumes.
        - **High Critical/Moderate Investigations**: 
            - Production has a high number of Critical (158) and Moderate (262) investigations, implying that quality issues originating in production are often severe.

    - <u>Recommendations</u>:
        - **Process Parameter Optimization**: 
            - Review and optimize critical process parameters (e.g., mixing times, milling speeds, drying conditions, blend uniformity) in Production for products exhibiting high particle size or pH variability.
        - **Statistical Process Control (SPC)**: 
            - Implement robust SPC charts for particle size and pH during production, particularly for high-variability products. 
            - This will allow for real-time monitoring and early detection of trends or shifts.
        - **Equipment Maintenance & Calibration**: 
            - Ensure that all production equipment impacting particle size (e.g., mills, blenders) and pH (e.g., mixing vessels, purification systems) is regularly maintained and calibrated to minimize variability.
        - **Operator Training**: 
            - Enhance operator training on the impact of their actions on critical quality attributes like particle size and pH, and on adhering to precise batch records.

- **QA Department**
    - <u>Insights</u>:
        - **Oversight of Quality Data**: 
            - QA's dashboard shows the same product quality variability, confirming their oversight role in reviewing and managing deviations related to these attributes.
        - **Investigation Volume from Quality Deviations**: 
            - The 116 open investigations and 152 open CAPAs in QA likely stem from, or are related to, the detection of product quality deviations.
        - **Focus on Compliance**: 
            - QA's role means they are concerned with these variabilities in the context of cGMP compliance and audit readiness.

    - <u>Recommendations</u>:
        - **Enhance Specification Monitoring**: 
            - QA should collaborate with QC and Production to establish tighter internal specifications or alert limits for particle size and pH for high-variability products, even if within current release specifications.
        - **Trend Analysis and Risk Assessment**: 
            - Proactively use these quality metrics to conduct trend analysis and risk assessments, identifying products or processes that are consistently operating at the edge of specifications or showing increasing variability.
        - **Support CAPA Effectiveness**: 
            - QA should play a leading role in verifying the effectiveness of CAPAs aimed at reducing product quality variability, ensuring sustained improvement.

- **QC Lab Department**

    - <u>Insights</u>:
        - **Direct Measurement & Reporting**: 
            - QC Lab is directly responsible for measuring and reporting particle size and pH. 
            - The variability seen in the dashboard is a direct result of their analytical data.
        - **High Moderate/Minor Investigations**: 
            - QC Lab has a significant number of Moderate (231) and Minor (299) investigations, which could include out-of-specification (OOS) or out-of-trend (OOT) results for particle size and pH.
        - **Consistent Data Pattern**: 
            - The quality distribution patterns are consistent with other departments, validating the QC Lab's measurements across the product portfolio.

    - <u>Recommendations</u>:
        - **Analytical Method Validation & Control**: 
            - Review the analytical methods used for particle size and pH to ensure they are robust, validated, and consistently applied. 
            - Confirm that method variability is minimal.
        - **Equipment Calibration & Maintenance**: 
            - Implement a stringent calibration and preventative maintenance program for all analytical equipment used for particle size and pH measurements.
        - **OOS/OOT Investigation Training**: 
            - Provide specialized training to QC analysts on conducting thorough OOS and OOT investigations for physical and chemical quality attributes.
        - **Data Integrity & Trend Reporting**: 
            - Ensure seamless data transfer from QC instruments to the digital system and implement automated tools for trend analysis of particle size and pH to quickly identify deviations.

- **R&D Department**

    - <u>Insights</u>:
        - **Formulation & Development Influence**: 
            - R&D is critical in defining the initial particle size and pH targets for new formulations.
            - Variability could stem from sub-optimal formulation or process development.
        - **High Moderate/Minor Investigations**: 
            - R&D has a high number of Moderate (230) and Minor (202) investigations, which could be related to scale-up challenges or initial formulation robustness.
        - **Impact on Manufacturability**: 
            - Variability issues identified in R&D (or not addressed during scale-up) will directly translate to production quality issues.

    - <u>Recommendations</u>:
        - **Design of Experiments (DoE)**: 
            - Utilize DoE principles during R&D to thoroughly understand the impact of critical material attributes and process parameters on particle size and pH, establishing robust design spaces.
        - **Robustness Testing**: 
            - Conduct comprehensive robustness testing during formulation and process development to ensure that products are resilient to minor variations in manufacturing conditions.
        - **Seamless Tech Transfer**: 
            - Enhance the technology transfer process from R&D to Production, ensuring that all critical quality attributes (CQAs) and critical process parameters (CPPs) related to particle size and pH are clearly defined and communicated.
        - **Early Quality Risk Assessment**: 
            - Implement quality risk assessments (e.g., FMEA) early in the R&D phase, specifically focusing on potential variability in particle size and pH and their impact on drug product performance.

#### 4.3.2. Insights and Recommendations by Product

- **Alprazolam 0.5mg**
    - <u>Investigations Overview</u>: 
        - Alprazolam 0.5mg consistently generates a high volume of investigations with 402 total, 106 open, and a balanced impact severity (104 Critical, 102 Moderate, 192 Minor). 
        - There are 229 required CAPAs, with 105 open, indicating a significant corrective action backlog.
        - Resolution times for all severity levels (Critical, Moderate, Minor) show a sharp increase from mid-2024, attributed to "Backlog/Error" investigations.
    - <u>Product Quality Metrics</u>: 
        - This product shows moderate variability in both pH (IQR approx. 4.5 to 5.2) and particle size (IQR approx. 15 to 25 µm). 
        - While the overall distribution is somewhat controlled, there are numerous data points spread across the range and some outliers are visible.
    - <u>Key Insights</u>: 
        - The moderate quality variability, especially the presence of outliers and a broader distribution, likely contributes to the high and varied impact severity of investigations. 
        - The systemic backlog issue from mid-2024 is also severely impacting its resolution times.

    - <u>Recommendations</u>:
        - **Targeted Process Improvement**: 
            - Conduct a thorough review of the manufacturing process for Alprazolam 0.5mg to identify and control critical parameters affecting pH and particle size variability. 
            - Focus on reducing outliers.
        - **Enhanced In-Process Controls**: 
            - Implement tighter in-process controls and specifications for pH and particle size, potentially using Statistical Process Control (SPC) to monitor trends and prevent deviations before they become investigations.
        - **CAPA Prioritization**: 
            - Prioritize the closure of open CAPAs for Alprazolam 0.5mg, especially those linked to critical or moderate investigations, to prevent recurrence.

- **Clonazepam 0.5mg**
    - **Investigations Overview**: 
        - Clonazepam 0.5mg has a moderate investigation volume with 195 total, 44 open and 151 closed. 
        - The impact severity is relatively balanced across Critical (51), Moderate (53) and Minor (91) cases.
        - There are 118 required CAPAs, with 60 open. 
        - Similar to other products, its resolution times are heavily impacted by "Backlog/Error" investigations from mid-2024.
    - **Product Quality Metrics**: 
        - This product shows relatively tighter pH distribution (IQR approx. 5.3 to 6.2). Particle size distribution appears tight (IQR approx. 20 to 30 µm), but with notable outliers.
    - **Key Insights**: 
        - The primary quality concern appears to be occasional particle size outliers, which could be driving some of the investigations, despite overall good control. 
        - The systemic backlog is also a significant factor in resolution times.

    - <u>Recommendations</u>:
        - **Investigate Particle Size Outliers**: 
            - Focus investigations on the specific process steps or equipment that might contribute to particle size outliers for Clonazepam 0.5mg.
        - **Proactive Monitoring**: 
            - Implement real-time monitoring or more frequent in-process checks for particle size to catch potential deviations early.
        - **Backlog Specific Support**: 
            - Provide focused support to clear the backlog of investigations affecting Clonazepam 0.5mg to improve its resolution performance.

- **Duloxetine 30mg**
    - **Investigations Overview**: 
        - Duloxetine 30mg stands out with only 1 total investigation, which is currently open and 0 for all impact severities and CAPA categories. 
        - This suggests excellent process control and product quality, with no significant investigation backlog affecting it. 
        - The weekly moving average chart for resolution days is empty, confirming no historical resolution issues.
    - **Product Quality Metrics**: 
        - This product demonstrates exceptionally tight control over both pH (a single data point at approx. 6.6) and particle size (a single data point at approx. 55 µm), with virtually no variability.
    - **Key Insights**: 
        - Duloxetine 30mg serves as a benchmark for ideal product quality and robust manufacturing processes, resulting in minimal quality deviations and investigation volumes.
    
    - <u>Recommendations</u>:
        - **Benchmark for Best Practices**: 
            - Conduct a detailed study of the manufacturing, analytical and quality control processes for Duloxetine 30mg. 
            - Identify and document the specific best practices that contribute to its consistent quality and low investigation rate.
        - **Knowledge Transfer**: 
            - Share the learnings and best practices from Duloxetine 30mg's production with teams responsible for high-variability products to inform process improvements.

- *Fluoxetine 20mg**
    - **Investigations Overview**: 
        - Fluoxetine 20mg has the highest total investigation count (447 total, 106 open, 341 closed). 
        - It also has a high number of Critical (115) and Moderate (121) investigations, with a significant number of Minor (211) cases. 
        - There are 251 required CAPAs, with 135 open, indicating a substantial backlog of corrective actions.
        - Its resolution times show the dramatic, backlog-driven increase from mid-2024.
    - **Product Quality Metrics**: 
        - This product exhibits significant variability in both pH (wide IQR approx. 5.7 to 7.2) and particle size (wide IQR approx. 70 to 90 µm), with numerous outliers for both. 
        - The scatter plot shows a broad spread of data points.
    - **Key Insights**: 
        - The extreme variability in both pH and particle size is almost certainly the primary driver for the exceptionally high volume and severity of investigations for Fluoxetine 20mg. 
        - This product represents a critical quality control challenge.

    - <u>Recommendations</u>:
        - **Urgent Process Re-evaluation & Optimization**:
            - Initiate an immediate and comprehensive re-evaluation of the entire manufacturing process for Fluoxetine 20mg. 
            - This should include revisiting formulation robustness, raw material specifications and critical process parameters.
        - **Advanced Analytics & SPC**: 
            - Implement advanced Process Analytical Technology (PAT) and rigorous Statistical Process Control (SPC) for real-time monitoring of pH and particle size during production. 
            - Define tighter internal alert limits to prevent deviations.
        - **Dedicated Task Force**: 
            - Establish a dedicated cross-functional task force involving R&D, Production, QC and QA to address the systemic quality issues with Fluoxetine 20mg.
        - **Aggressive CAPA Closure**: 
            - Prioritize and aggressively work to close open CAPAs for this product to prevent recurring issues.

- **Gabapentin 300mg**
    - **Investigations Overview**: 
        - Gabapentin 300mg has a moderate investigation volume (230 total, 57 open, 173 closed). 
        - It shows a balanced impact severity (64 Critical, 59 Moderate, 107 Minor). 
        - There are 138 required CAPAs, with 66 open. 
        - Like other products, its resolution times are heavily influenced by the general "Backlog/Error" trend.
    - **Product Quality Metrics**: 
        - While pH appears relatively well-controlled (IQR approx. 5.2 to 5.7), particle size shows moderate variability (IQR approx. 85 to 105 µm) with a significant number of outliers.
    - **Key Insights**: 
        - Particle size variability, particularly the presence of outliers, is a likely contributor to investigations for Gabapentin 300mg.

    - <u>Recommendations</u>:
        - **Target Particle Size Process Improvement**: 
            - Focus efforts on identifying and correcting the root causes of particle size variability and outliers in the manufacturing process for Gabapentin 300mg (e.g., milling, blending, or drying).
        - **Outlier Investigation Protocol**: 
            - Develop a more stringent protocol for investigating and addressing particle size outliers, ensuring immediate corrective action.

- **Gabapentin 300mg**
    - **Investigations Overview**: 
        - Gabapentin 300mg has a moderate investigation volume (230 total, 57 open, 173 closed). 
        - It shows a balanced impact severity (64 Critical, 59 Moderate, 107 Minor). 
        - There are 138 required CAPAs, with 66 open. 
        - Like other products, its resolution times are heavily influenced by the general "Backlog/Error" trend.
    - **Product Quality Metrics**: 
        - While pH appears relatively well-controlled (IQR approx. 5.2 to 5.7), particle size shows moderate variability (IQR approx. 85 to 105 µm) with a significant number of outliers.
    - **Key Insights**: 
        - Particle size variability, particularly the presence of outliers, is a likely contributor to investigations for Gabapentin 300mg.

    - <u>Recommendations</u>:
        - **Target Particle Size Process Improvement**: 
            - Focus efforts on identifying and correcting the root causes of particle size variability and outliers in the manufacturing process for Gabapentin 300mg (e.g., milling, blending, or drying).
        - **Outlier Investigation Protocol**: 
            - Develop a more stringent protocol for investigating and addressing particle size outliers, ensuring immediate corrective action.

- **Lorazepam 1mg**
    - **Investigations Overview**: 
        - Lorazepam 1mg has a relatively low investigation count (188 total, 37 open, 151 closed). 
        - Impact severity is also lower across the board (44 Critical, 49 Moderate, 95 Minor). 
        - With 108 required CAPAs and 61 open, the CAPA backlog is manageable compared to high-volume products. 
        - The resolution times show the same systemic backlog impact from mid-2024.
    - **Product Quality Metrics**: 
        - This product shows excellent control over both pH (very tight IQR approx. 4.0 to 4.4) and particle size (very tight IQR approx. 18 to 28 µm), with minimal outliers.
    - **Key Insights**: 
        - The consistently tight quality control for both pH and particle size directly correlates with the lower investigation volume and severity for Lorazepam 1mg.
    
    - <u>Recommendations</u>:
        - **Maintain Exemplary Controls**: 
            - Ensure that the current robust manufacturing processes and quality controls for Lorazepam 1mg are rigorously maintained.
        - **Share Best Practices**: 
            - Document and share the successful practices employed in the production of Lorazepam 1mg to serve as a model for improving quality control in other products.

- **Methylphenidate 10mg**
    - **Investigations Overview**: 
        - Methylphenidate 10mg is another high-volume investigation product (402 total, 112 open, 290 closed). 
        - It has a high number of Critical (122) and Moderate (178) investigations, indicating severe quality issues.
        - The CAPA situation is critical with 232 required and 126 open. Its resolution times are significantly prolonged by the systemic backlog from mid-2024.
    - **Product Quality Metrics**: 
        - This product exhibits substantial variability in both pH (wide IQR approx. 6.2 to 7.3) and particle size (wide IQR approx. 65 to 80 µm), with numerous outliers for both. 
        - The scatter plot shows a broad and diffused distribution of data points.
    - **Key Insights**: 
        - The broad and highly variable pH and particle size distributions are directly linked to the high volume and critical/moderate severity of investigations for Methylphenidate 10mg. 
        - This product is a major contributor to overall investigation load.

    - <u>Recommendations</u>:
        - **Aggressive Process Re-engineering**: 
            - This product requires aggressive re-engineering of its manufacturing process to significantly reduce variability in pH and particle size. 
            - This may involve revisiting raw material specifications, formulation parameters and equipment capabilities.
        - **Root Cause Elimination**: 
            - Conduct in-depth root cause analyses specifically for Methylphenidate 10mg's quality deviations, focusing on eliminating sources of variability rather than just containing them.
        - **CAPA Acceleration**: 
            - Accelerate the implementation and closure of CAPAs for Methylphenidate 10mg to prevent recurring critical issues.

- **Sertraline 50mg**
    - **Investigations Overview**: 
        - Sertraline 50mg has a very high investigation volume (424 total, 100 open, 324 closed). 
        - It shows a high number of Moderate (188) and Minor (127) investigations, with a significant number of Critical (109) cases as well. 
        - The CAPA backlog is substantial with 221 required and 113 open. 
        - Resolution times are severely impacted by the systemic backlog from mid-2024.
    - **Product Quality Metrics**: 
        - Sertraline 50mg displays high variability in both pH (wide IQR approx. 6.8 to 7.7) and particle size (wide IQR approx. 85 to 115 µm), with several outliers present.
    - **Key Insights**: 
        - The pronounced variability in both pH and particle size likely contributes to the high investigation volume for Sertraline 50mg, particularly the moderate and minor categories which might stem from out-of-trend or borderline results.

    - <u>Recommendations</u>:
        - **Targeted Process Optimization**: 
            - Implement targeted process optimization efforts to reduce the variability in pH and particle size for Sertraline 50mg. 
            - This could involve tighter control on mixing, drying, and milling operations.
        - **Trend Monitoring & Early Intervention**: 
            - Establish more rigorous trend monitoring for pH and particle size. 
            - Empower QC and Production to initiate pre-emptive actions based on early warnings, even if results are within specification but trending unfavorably.
        - **CAPA Efficiency**: 
            - Improve the efficiency of CAPA implementation and closure for Sertraline 50mg to ensure that identified quality issues are resolved promptly.

- **Topiramate 25mg**
    - **Investigations Overview**: 
        - Topiramate 25mg has a moderate investigation count (210 total, 58 open, 152 closed). 
        - Impact severity is balanced (52 Critical, 56 Moderate, 102 Minor). 
        - The CAPA situation is manageable with 111 required and 69 open. 
        - The systemic backlog heavily impacts its resolution times from mid-2024.
    - **Product Quality Metrics**: 
        - While pH shows moderate variability (IQR approx. 6.0 to 7.0), particle size exhibits significant variability (wide IQR approx. 95 to 125 µm) with numerous outliers and a broad overall range.
    - **Key Insights**: 
        - The high variability in particle size is a key quality concern and likely contributes significantly to the investigations for Topiramate 25mg.
    
    - <u>Recommendations</u>:
        - **Focused Particle Size Control**: 
            - Prioritize efforts to understand and control the factors influencing particle size variability for Topiramate 25mg. 
            - This may require specific equipment adjustments or process changes in milling/granulation.
        - **Process Parameter Review**: 
            - Review manufacturing process parameters related to particle size for Topiramate 25mg to ensure they are optimized for consistency.

- **Venlafaxine 75mg**
    - **Investigations Overview**: 
        - Similar to Duloxetine 30mg, Venlafaxine 75mg shows excellent performance with only 1 total investigation (open) and 0 for impact severity and CAPA categories.
        - There are no apparent resolution time issues due to the lack of investigations.
    - **Product Quality Metrics**: 
        - This product also demonstrates extremely tight control over both pH (a single data point at approx. 7.8) and particle size (a single data point at approx. 50 µm), indicating very low variability.
    - **Key Insights**: 
        - Venlafaxine 75mg serves as another prime example of robust formulation and manufacturing leading to minimal quality issues and investigation volumes.

    - <u>Recommendations</u>:
        - **Model for Success**: 
            - Leverage Venlafaxine 75mg as a model for robust product development and consistent manufacturing.
            - Document and implement its best practices across the product portfolio where applicable.
        - **Proactive Quality Assurance**: 
            - Continue to apply a proactive quality assurance approach to ensure this product maintains its excellent performance.

- **General Strategic Recommendations (Across All Products)**:
    - **Product Prioritization for Quality Improvement**:
        - Categorize products based on their total investigation volume and quality variability (e.g., Fluoxetine 20mg, Methylphenidate 10mg, Sertraline 50mg as high priority; Alprazolam 0.5mg, Topiramate 25mg, Gabapentin 300mg as moderate priority). 
        - Allocate resources for process improvement accordingly.
    - **Systematic Root Cause Analysis for Variability**: 
        - For products with high quality attribute variability, mandate deeper root cause analysis that goes beyond the immediate deviation to uncover underlying systemic issues in formulation, raw materials, equipment or process design.
    - **Invest in Process Analytical Technology (PAT)**: 
        - For high-priority products, explore and implement PAT solutions for real-time, in-line monitoring of critical quality attributes like pH and particle size. 
        - This enables proactive adjustments and reduces batch variability.
    - **Strengthen Supplier Quality Management**: 
        - Investigate if variability in incoming raw materials contributes to pH or particle size issues in the finished products, especially for high-variability products. 
        - Strengthen supplier qualification and incoming material testing.
    - **Robustness Testing and Design Space Definition**: 
        - For new and problematic products, apply Design of Experiments (DoE) and comprehensive robustness testing during development and re-validation to define broader and more resilient operating design spaces.
    - **Backlog Management for Investigations**: 
        - While focusing on product quality, the pervasive "backlog/error" impact on resolution times must be addressed systemically across all products. 
        - This may require a dedicated team or temporary resources to clear the existing backlog.

#### 4.3.3. Insights and Recommendations by Investigator
- **A. Khan**
    - **Investigations Overview**: 
        - A. Khan has handled 346 total investigations, with 88 open and 258 closed. 
        - The impact severity is distributed as 98 Critical, 90 Moderate, and 158 Minor. 
        - There are 195 required CAPAs, with 94 open.
    - **Product Quality Metrics**: 
        - The "Product pH & Particle Size Distribution" charts (box plots and scatter plot) show a wide range of pH and particle size levels across multiple products. 
        - This indicates that A. Khan is involved in investigating a diverse set of products, including those with both tight and highly variable quality profiles. 
        - Products like Fluoxetine 20mg and Methylphenidate 10mg, known for high variability, are visible in the distributions.
    - **Key Insights**: 
        - A. Khan is managing a substantial caseload across various products, including those with significant quality challenges, contributing to the high number of critical and moderate investigations. 
        - The diverse range of products suggests a broad scope of work.
    
    - <u>Recommendations</u>:
        - **Workload Analysis**: 
            - Evaluate A. Khan's investigation workload, especially concerning products with high pH and particle size variability (e.g., Fluoxetine 20mg, Methylphenidate 10mg, Sertraline 50mg) to ensure adequate time and resources for thorough root cause analysis.
        - **Targeted Training**: 
            - Provide A. Khan with advanced training or specialized tools for investigating complex quality deviations related to pH and particle size for high-variability products.

- **D. Garcia**
    - **Investigations Overview**: 
        - D. Garcia has managed 345 total investigations, with 90 open and 255 closed. 
        - The impact severity distribution is 80 Critical, 73 Moderate, and 92 Minor. 
        - There are 194 required CAPAs, with 100 open.
    - **Product Quality Metrics**: 
        - Similar to A. Khan, D. Garcia's dashboard displays a broad spectrum of pH and particle size distributions across multiple products. 
        - This suggests involvement with products exhibiting varying degrees of quality control.
    - **Key Insights**: 
        - D. Garcia handles a significant number of investigations across a variety of products. 
        - The slightly lower proportion of critical and moderate investigations compared to A. Khan might suggest a focus on products with less severe, but still notable, quality deviations.

    - <u>Recommendations</u>:
        - **Efficiency Review**: 
            - Analyze D. Garcia's investigation process for efficiency, particularly for recurring minor or moderate deviations, to ensure quick resolution and prevent escalation.
        - **Knowledge Sharing**: 
            - Encourage D. Garcia to share insights from investigations into products with moderate variability to contribute to proactive quality improvements.

- **J. Smith**
    - **Investigations Overview**: 
        - J. Smith has 345 total investigations, with 86 open and 259 closed. The impact severity is 90 Critical, 94 Moderate and 94 Minor. 
        - There are 200 required CAPAs, with 104 open.
    - **Product Quality Metrics**: 
        - The dashboard shows a wide representation of products and their pH and particle size variability. 
        - This indicates J. Smith investigates a diverse portfolio, including products with substantial quality challenges.
    - **Key Insights**: 
        - J. Smith is managing a heavy workload with a relatively balanced distribution of critical, moderate, and minor investigations. This suggests a broad responsibility across different product lines and quality issues.

    - <u>Recommendations</u>:
        - **Root Cause Focus**: 
            - Emphasize robust root cause analysis training for J. Smith, especially for critical and moderate investigations, to ensure that underlying quality issues are addressed effectively.
        - **Support for CAPA Closure**: 
            - Provide administrative or technical support to help J. Smith expedite the closure of open CAPAs.

- **L. Zhang**
    - **Investigations Overview**: 
        - L. Zhang has 348 total investigations, with 79 open and 269 closed. The impact severity is 92 Critical, 157 Moderate and 99 Minor. 
        - There are 189 required CAPAs, with 101 open.
    - **Product Quality Metrics**: 
        - The dashboard shows that L. Zhang is involved in investigating products across a wide range of pH and particle size distributions, including those with high variability.
    - **Key Insights**: 
        - L. Zhang stands out with a higher proportion of moderate impact investigations compared to other investigators. 
        - This could indicate a focus on deviations that are not critical but still require significant intervention, potentially linked to products with consistent but out-of-trend quality attributes.
    
    - <u>Recommendations</u>:
        - **Proactive Intervention Training**: 
            - Provide L. Zhang with training on proactive quality intervention strategies, focusing on identifying trends in product quality metrics that could lead to moderate investigations before they escalate.
        - **Process Understanding**: 
            - Encourage L. Zhang to deepen understanding of manufacturing processes for products frequently generating moderate investigations to better identify systemic issues.

- **M. Patel**
    - **Investigations Overview**: 
        - M. Patel has the highest total investigations among the group (386 total, 90 open, 296 closed). 
        - The impact severity is significantly high in Critical (104) and Moderate (178) cases, with a lower number of Minor (104) cases. 
        - The CAPA situation is challenging with 215 required and 118 open.
    - **Product Quality Metrics**: 
        - M. Patel's dashboard displays the full range of product pH and particle size distributions, including those with significant variability (e.g., Fluoxetine 20mg, Methylphenidate 10mg, Sertraline 50mg).
    - **Key Insights**: 
        - M. Patel is handling the largest volume of investigations, with a disproportionately high number of critical and moderate cases. 
        - This strongly suggests that M. Patel is primarily responsible for investigating the most complex and severe quality deviations, likely linked to products with high inherent quality variability.
   
    - <u>Recommendations</u>:
        - **Workload Redistribution/Support**: 
            - Seriously consider redistributing some of M. Patel's investigation workload, especially for less severe cases, or provide significant dedicated support to manage the high volume of critical/moderate investigations.
        - **Advanced Problem-Solving**: 
            - Provide M. Patel with access to advanced problem-solving methodologies (e.g., Six Sigma, DMAIC) and specialized external resources to tackle persistent quality issues for high-variability products.
        - **Prioritize Critical CAPAs**: 
            - Focus on rapidly closing CAPAs associated with M. Patel's critical investigations to prevent recurrence of severe issues.

- **R. Evans**
    - **Investigations Overview**: 
        - R. Evans has 386 total investigations, with 106 open and 280 closed. The impact severity is 105 Critical, 179 Moderate, and 102 Minor. 
        - There are 219 required CAPAs, with 113 open.
    - **Product Quality Metrics**: 
        - The dashboard shows a wide array of products with diverse pH and particle size distributions. 
        - This indicates R. Evans is involved in investigating products with various quality profiles, including those with high variability.
    - **Key Insights**: 
        - R. Evans, similar to M. Patel, has a high number of total investigations and a high proportion of critical and moderate cases. 
        - This suggests R. Evans is also heavily involved in addressing severe product quality deviations, likely for products with significant variability.
    
    - <u>Recommendations</u>:
        - **Resource Allocation**: 
            - Ensure R. Evans has sufficient resources (time, access to experts, specialized equipment) to effectively investigate and close critical and moderate deviations.
        - **Cross-Functional Collaboration**: 
            - Facilitate stronger cross-functional collaboration for R. Evans's investigations, particularly with R&D and Production, to drive systemic improvements for products with high variability.
        - **CAPA Monitoring**: 
            - Closely monitor the progress and effectiveness of CAPAs generated from R. Evans's investigations to ensure sustained improvements.

- **S. Thomas**
    - **Investigations Overview**: 
        - S. Thomas has 344 total investigations, with 82 open and 262 closed. The impact severity is 93 Critical, 88 Moderate and 162 Minor. 
        - There are 197 required CAPAs, with 105 open.
    - **Product Quality Metrics**: 
        - The dashboard shows the full range of product pH and particle size distributions, indicating S. Thomas investigates products with varied quality profiles.
    - **Key Insights**: 
        - S. Thomas manages a significant number of investigations, with a relatively higher proportion of minor impact cases compared to some other investigators. 
        - This could indicate a focus on preventing minor deviations from escalating or on products that tend to have less severe quality issues.
    
    - <u>Recommendations</u>:
        - **Proactive Problem Solving**: 
            - Encourage S. Thomas to utilize insights from minor investigations to identify early warning signs for potential larger quality issues.
        - **Efficiency in Minor Case Closure**: 
            - Streamline the investigation and CAPA processes for minor deviations to maximize S. Thomas's efficiency in clearing these cases.

- **General Strategic Recommendations (Investigator Level)**:
    - **Workload Balancing & Specialization**: 
        - Given the differing profiles of investigations (e.g., M. Patel and R. Evans handle more critical/moderate cases, while S. Thomas handles more minor cases), consider if specialization or redistribution of workload based on investigation complexity and product quality profile could improve overall efficiency and effectiveness.
    - **Training & Development**: 
        - Provide targeted training based on the types of quality issues each investigator frequently encounters.
        - For those dealing with high-variability products, focus on advanced root cause analysis, statistical tools and process improvement methodologies.
    - **CAPA Management Support**: 
        - The high number of open CAPAs across most investigators indicates a systemic issue. 
        - Implement a robust CAPA management system, provide dedicated resources for CAPA closure and ensure effective CAPA effectiveness checks.
    - **Knowledge Transfer & Best Practices**: 
        - Facilitate regular forums or platforms for investigators to share learnings, best practices and successful root cause analyses, especially for products with recurring quality issues.
    - **Tools and Technology**: 
        - Ensure investigators have access to the necessary tools and technology (e.g., advanced data analytics software, real-time process data access) to conduct thorough investigations, particularly for complex product quality deviations.
    - **Address Systemic Backlog**: 
        - Acknowledge and actively work to resolve the overarching "Backlog/Error" issue impacting resolution times, as this affects all investigators regardless of their individual performance. 
        - This is crucial for enabling investigators to close cases promptly and effectively.

---
## 5. Assumptions and Caveats
### 5.1. Dataset Representativeness
- The dataset was intentionally generated with realistic data inconsistencies (e.g., mixed date formats, duplicate product entries, and incomplete CAPA records).
- This was done to mimic real-world manufacturing data and to demonstrate advanced data cleaning and transformation capabilities.
- While the data logic (such as deviation categories by department and severity by root cause) mirrors real-world operational practices, the dataset itself is simulated and may not fully replicate all nuances of actual manufacturing data.


### 5.2. Date Handling and Format 
- Date parsing for Open Date assumed mixed formats (```MM/DD/YYYY``` and ```DD/MM/YYYY```), leveraging Power Query’s parsing logic and custom transformations.

- Negative ```Days To Resolution``` values were attributed to date format inconsistencies rather than data entry errors, and corrected by reversing day and month fields in ```Standardized Open Date```.
- The final date logic assumes investigations either remain open (null Closed Date) or follow standard resolution timelines.


### 5.3. Treatment of Null and Partial Data
- <u>For ```CAPA Required```</u>:

    - Nulls with a non-null ```Closed Date``` are assumed to be ***“No”***.
    - Nulls with no ```Closed Date``` are treated as ***“Pending”***.


- <u>For ```CAPA Closed```</u>:

    - Nulls linked to “No” ```CAPA Required``` are marked as ***“No”***.
    - Nulls linked to “Pending” ```CAPA Required``` are marked as ***“Pending”***.
    - Nulls for “Yes” ```CAPA Required``` are treated as ***“Pending”*** (ongoing CAPA).


- **Final product names** were mapped via known **batch-to-product associations** and, where necessary, **approximate matching** using particle size and pH logic, manually validated with QA records for accuracy.


### 5.4. Resolution Category Classification 
- To facilitate a clear understanding of resolution timelines, I introduced a custom classification column named ```Resolution Category```. 
- This column categorizes the ```Final Days to Resolution``` into six distinct groups to highlight the varying degrees of delays and their operational impact. 

- <u>Here’s the logic applied</u>:
    - **Ongoing**: Cases with missing resolution data (**null values**), indicating they are still active.
    - **Backlog/Error**: Cases that have exceeded **730 days**, suggesting data inconsistencies or a backlog of unresolved items.
    - **Very Delayed**: Cases resolved after more than **365 days**, highlighting significant delays.
    - **Long Delay**: Cases with resolution times exceeding **180 days**, suggesting notable delays.
    - **Delayed**: Cases resolved in more than **90 days**, indicating moderate delays.
    - **Slightly Delayed**: Cases resolved within **31-90 days**, reflecting slight delays.
    - **On-time**: All other cases resolved within **30 days or less**, considered timely resolutions.


- This categorization aims to simplify the analysis of resolution efficiency, highlight critical delays, and ensure actionable insights for process improvements. 
- I assumed that these thresholds adequately reflect operational realities and align with typical performance expectations within the organization.

### 5.5. CAPA Number Nulls 
- In the dataset, the ```CAPA Number``` field contains 1,092 null entries
- <u>These nulls represent cases where either</u>:
    - **No CAPA was required** (e.g., minor deviations or issues not warranting corrective or preventive actions), or
    - The **CAPA is still pending** and has not yet been assigned a number.

- I have assumed that these null entries are valid data entries reflecting actual operational scenarios, rather than missing data entries. 
- Given that this practice is standard within the pharmaceutical manufacturing environment, these nulls were retained in the dataset as is.


### 5.6. Outlier Detection Logic
- To ensure accurate outlier detection for **pH and particle size** measurements, I decided to perform the **analysis separately** for each product rather than across the entire dataset. 

- This approach accounts for the fact that different products typically have distinct acceptable ranges, while the same product should fall within **consistent internal ranges**. 
- As a result, this method **reduces the risk of incorrectly flagging** values as outliers due to inter-product variability.
- Additionally, to **assess the skewness** of the particle size distribution for each product, I calculated it using the **mean and median** with a tolerance of 1. 
- This **tolerance was applied** to avoid misclassifying normal variation as skewness. 
- This method helps ensure that skewness assessments and subsequent outlier identifications remain **robust and product-specific**.

### 5.7. General Dataset Integrity
- Each row is assumed to represent a distinct investigation, validated by unique open/close date pairs and detailed contextual fields.

### 5.8. CAPA Number Duplicate Entries
- During data analysis, I identified that the ```CAPA Number``` field contains duplicate entries, even though ideally each investigation should be associated with a **single unique CAPA**. 
- Notably, there is **no Investigation Number** field in the dataset to directly confirm unique investigations. 
- However, I have assumed that **each row represents a unique investigation**, as each row has distinct ```Opened Date`` and ```Closed Date``` entries.
- <u>Despite the duplicate ```CAPA Numbers```, I have decided to retain these entries because</u>:
    - Each row contains **valuable information in other columns** (e.g., issue details, investigation context) that would be lost if duplicates were removed.
    - These duplicate entries may reveal **shared CAPAs** across multiple investigations or reflect **valid process** links.

- To ensure data integrity, I have **flagged** all duplicate ```CAPA Number``` entries **for review** and validation with the relevant stakeholders. 
- This approach balances the need to preserve critical investigation data while recognizing potential data quality issues for further targeted follow-up.



### 5.9. Conflicting Final CAPA Closed Entries 
- During data analysis, I observed that in certain cases, the **same** ```CAPA Number``` appears in different investigations, with **conflicting** ```Final CAPA Closed``` statuses. 

- For example, the same ```CAPA Number``` might be marked as ***“Pending”*** in one investigation, while it is marked as ***“Yes”*** (closed) in another.
- This discrepancy suggests **possible data entry errors or process misalignments** when recording CAPA status across investigations. 
- As I have assumed that **each row represents a unique investigation** (based on unique Opened and Closed Dates), these inconsistencies were noted as potential data quality issues rather than an accurate reflection of CAPA lifecycle status.
- To preserve the integrity of the broader dataset and maintain potentially valuable information in other columns, I have **flagged these conflicting entries for further review** and resolution with the relevant stakeholders.




### 5.10. Caveats and Limitations
- Although all corrections and **mappings** were based on **logical and domain-specific assumptions**, some nuances of real-world data (e.g., edge-case deviations, manual entry errors) might not be fully captured in the generated dataset.

- Final **product name** corrections for **2 records relied on external QA validation** rather than automated logic, representing an exception to systematic data cleaning.
- **Date format corrections** assume consistent patterning (US vs. UK format) across the dataset; deviations from this could lead to residual errors.
- While no outliers were detected, this relies on the validity of **assumed product-specific ranges and distributions**, which may differ in operational data.
- Null treatments for ```CAPA Closed``` and ```CAPA Required``` **assume logical consistency between investigation status and CAPA lifecycle**, which might not fully reflect every real-world scenario.


## 6. Code & Technical Implementation
### Dataset generation (Python)

- The dataset used for the dashboards was generated in **Visual Studio Code** using a **Jupyter Notebook** with **Python**. 

- The **Python script** (linked below) was carefully crafted to ensure that the data simulated real-world scenarios rather than merely producing random values for each column. 
- While generating the data, I paid close attention to ensuring that **logical relationships were preserved** — such as aligning certain deviation categories with specific departments and having severity levels logically connected to the type of issue. 
- Moreover, **I intentionally designed the dataset to be as “dirty” as possible** (e.g., mixed date formats, extra whitespace, missing values, duplicate rows) so that I could fully demonstrate my data cleaning skills in **Power Query** later on. 
- This approach ensured that the downstream **Excel** dashboards were built on **realistic and challenging data**, better showcasing the data transformation and modeling processes.

### Cleaning (Power Query)
- The data cleaning process was performed in Power Query after loading the synthetic dataset (```pharma_dirty_realistic_data_original.xlsx```). 
- Here are the main steps that were conducted in Power Query:
 

    1.  **Initial Cleaning**
    2.  **Null Handling & Column Additions**
    3. **Handling Duplicates**
    4. **Outlier Detection**


 

 #### Initial Cleaning
 ---
 **Open Date**

- The ```Open Date``` column contained two different date formats (MM/DD/YYYY and DD/MM/YYYY). 
- To standardize this column, a custom column called ```Standardized Open Date``` was created using the following M code:
```m
 let
    original = [Open Date],
    parsed = try Date.FromText(original, "en-US") otherwise try Date.FromText(original, "en-GB") otherwise null
in
    parsed
```

- This logic attempted to parse the date using the en-US format first and, if unsuccessful, tried the en-GB format. 
- Rows with neither format returned a null. The original ```Open Date``` column was removed after verifying the new column, and ```Standardized Open Date``` was then converted from text to date type.
<br>

**Batch Number**

- To ensure all batch numbers followed the correct format (Batch_000), a custom column called ```Batch Number Validation``` was created:
```m
let
    value = [Batch Number],
    isCorrectPrefix = Text.StartsWith(value, "Batch_"),
    numericPart = Text.Middle(value, 6, 3),
    isThreeDigits = Text.Length(numericPart) = 3 and Text.Select(numericPart, {"0".."9"}) = numericPart
in
    if isCorrectPrefix and isThreeDigits then "Valid" else "Invalid"
```

- The filter in the ```Batch Number Validation``` column confirmed 100% valid entries. 
- After this verification, the ```Batch Number Validation``` column was removed.

**Product Name**

- Using the filter on the ```Product Name``` column revealed multiple incorrectly formatted or duplicate product names. 
- These incorrect names were replaced with their correct versions using ***Transform → Replace***.
- To ensure that extra spaces were not causing false duplicates, the ***Transform → Format → Trim*** option was applied to the ```Product Name``` column. 
- This final cleaning step resulted in eight unique, correctly formatted product names.

**CAPA Number**

- The ```CAPA Number``` column was first cleaned of any extra spaces using the ***Transform → Trim*** operation.
- A custom column called ```Format CAPA Number``` was then created to validate the formatting of these entries and account for null values:
```m
let
    trimmedValue = [CAPA Number],
    result =
        if trimmedValue = null then "Null"
        else
            let
                cleanValue = Text.Trim(trimmedValue),
                isCorrectPrefix = Text.StartsWith(cleanValue, "CAPA-"),
                numericPart = Text.Middle(cleanValue, 5, 4),
                isFourDigits = Text.Length(numericPart) = 4 and Text.Select(numericPart, {"0".."9"}) = numericPart
            in
                if isCorrectPrefix and isFourDigits then "Valid" else "Invalid"
in
    result
```
- After reviewing the filter in the ```Format CAPA Number``` column, only ***Null*** and ***Valid*** values were present, confirming correct formatting. - The column was then removed to maintain a streamlined table.

#### Null Handling & Column Additions
---
**Checking for Nulls**

- I created a reference query from my ***Cleaned Data*** query.
- Then I added a custom column using the following formula to count the nulls in each column:

```m
let
    // Function to check for nulls or blanks (empty strings or spaces)
    isNullOrBlank = (value) => value = null or Text.Trim(Text.From(value)) = "",

    // Count the nulls/blanks in each column using the 'Source' step
    countOpenDateNulls = List.Count(List.Select(Source[Standardized Open Date], each isNullOrBlank(_))),
    countClosedDateNulls = List.Count(List.Select(Source[Closed Date], each isNullOrBlank(_))),
    countBatchNumberNulls = List.Count(List.Select(Source[Batch Number], each isNullOrBlank(_))),
    countProductNameNulls = List.Count(List.Select(Source[Product Name], each isNullOrBlank(_))),
    countDepartmentNulls = List.Count(List.Select(Source[Department], each isNullOrBlank(_))),
    countDeviationCategoryNulls = List.Count(List.Select(Source[Deviation Category], each isNullOrBlank(_))),
    countRootCauseNulls = List.Count(List.Select(Source[Root Cause], each isNullOrBlank(_))),
    countImpactSeverityNulls = List.Count(List.Select(Source[Impact Severity], each isNullOrBlank(_))),
    countCAPARequiredNulls = List.Count(List.Select(Source[CAPA Required], each isNullOrBlank(_))),
    countCAPAClosedNulls = List.Count(List.Select(Source[CAPA Closed], each isNullOrBlank(_))),
    countCAPANumberNulls = List.Count(List.Select(Source[CAPA Number], each isNullOrBlank(_))),
    countInvestigatorNulls = List.Count(List.Select(Source[Investigator], each isNullOrBlank(_))),
    countParticleSizeNulls = List.Count(List.Select(Source[#"Particle Size (μm)"], each isNullOrBlank(_))),
    countpHLevelNulls = List.Count(List.Select(Source[pH Level], each isNullOrBlank(_)))
in
    // Return a record with counts of nulls/blanks for each column
    [
        StandardizedOpenDateNulls = countOpenDateNulls,
        ClosedDateNulls = countClosedDateNulls,
        BatchNumberNulls = countBatchNumberNulls,
        ProductNameNulls = countProductNameNulls,
        DepartmentNulls = countDepartmentNulls,
        DeviationCategoryNulls = countDeviationCategoryNulls,
        RootCauseNulls = countRootCauseNulls,
        ImpactSeverityNulls = countImpactSeverityNulls,
        CAPARequiredNulls = countCAPARequiredNulls,
        CAPAClosedNulls = countCAPAClosedNulls,
        CAPANumberNulls = countCAPANumberNulls,
        InvestigatorNulls = countInvestigatorNulls,
        ParticleSizeNulls = countParticleSizeNulls,
        pHLevelNulls = countpHLevelNulls
    ]
```
<br>

**Treating Columns with Nulls**

- ```Closed Date```

    - For ```Closed Date```, there were 624 nulls — likely indicating that the investigation is either ongoing or not yet recorded as closed.

- ```Days To Resolution```
    - I added a ```Days To Resolution``` column using a Custom Column formula calculating the difference between ```Closed Date``` and ```Standardized Open Date``` (handling ongoing investigations by treating null ```Closed Date``` as ongoing).
    - I changed the column type to Whole Number.
    - Some ```Days To Resolution``` values were negative, suggesting ```Closed Date``` earlier than ```Open Date``` due to earlier false date conversions (likely day/month swap errors).
- ```Final Standardized Open Date```
    - I added a ```Final Standardized Open Date``` column to swap around day and month for ```Standardized Open Date``` where negative durations were identified:

        ```m
        let
            originalDate = [Standardized Open Date],
            closedDate = [Closed Date],

            // Only attempt to fix if both dates are present
            fixedDate = if originalDate <> null and closedDate <> null then
                let
                    daysToResolution = Duration.Days(closedDate - originalDate),
                    correctedDate = if daysToResolution < 0 then
                        let
                            year = Date.Year(originalDate),
                            month = Date.Day(originalDate),
                            day = Date.Month(originalDate),
                            tryNewDate = try #date(year, month, day)
                        in
                            if tryNewDate[HasError] then originalDate else tryNewDate[Value]
                    else
                        originalDate
                in
                    correctedDate
            else
                originalDate
        in
            fixedDate
        ```
    - I moved ```Final Standardized Open Date``` next to ```Standardized Open Date```, changed its data type to date, and removed the original ```Standardized Open Date``` column.

- ```Final Days To Resolution```

    - I added a ```Final Days To Resolution``` column calculating the difference between ```Closed Date``` and ```Final Standardized Open Date```.
    - I changed it to Whole Number data type, moved it next to the original, and removed the original ```Days To Resolution```.

    - For ```Final Days To Resolution```, there were 624 nulls (aligning with missing ```Closed Date```).
<br>
    - <u>To better interpret resolution times, I added a ```Resolution Category``` column using logic like</u>:
        
        - ***Ongoing***: if null

        - ***Backlog/Error***: > 730 days

        - ***Very Delayed***: > 365 days

        - ***Long Delay***: > 180 days

        - ***Delayed***: > 90 days

        - ***Slightly Delayed***: > 30 days

        - ***On-time***: everything else

- ```Product Name```
    - There were 125 nulls in ```Product Name```.
    - To fill them:

        1. Created a ***Map: Batch To Product*** query referencing ***Cleaned Data***, removed nulls and duplicates from ```Batch Number``` and ```Product Name```.

        2. Merged ***Cleaned Data*** with ***Map: Batch To Product*** on ```Batch Number``` (left join).

        3. Expanded the merged data and filtered rows to identify remaining nulls.

- ```Particle pH Product Name```

    - I used Python in Jupyter Notebook to find likely ```Product Name``` based on ```Particle Size``` and ```pH Level```.
    - Example snippet:

        ```python
        def find_matching_product(particle_size, pH, medication_specs):
        for product, specs in medication_specs.items():
            particle_range_min = specs["particle_mean"] - specs["particle_std"]
            particle_range_max = specs["particle_mean"] + specs["particle_std"]
            pH_min, pH_max = specs["pH_range"]
            if (particle_range_min <= particle_size <= particle_range_max) and (pH_min <= pH <= pH_max):
                return product
        return None
        ```
    - Results filled 6/8 missing ```Product Names```.
    - For the 2 remaining, ***Batch_605*** and ***Batch_376***, I confirmed with QA and updated manually:

        - ***Batch_605***: Venlafaxine 75mg

        - ***Batch_376***: Duloxetine 30mg

    - I updated the ```Particle pH Product Name``` custom column formula in Power Query accordingly:    
    
        ```m
        if Number.Round([#"Particle Size (μm)"], 7) = 25.2856111 and Number.Round([pH Level], 7) = 4.8140441 then "Lorazepam 1mg"
        else if Number.Round([#"Particle Size (μm)"], 7) = 91.0401651 and Number.Round([pH Level], 7) = 6.1539589 then "Sertraline 50mg"
        else if Number.Round([#"Particle Size (μm)"], 7) = 111.3931228 and Number.Round([pH Level], 7) = 6.1825509 then "Topiramate 25mg"
        else if Number.Round([#"Particle Size (μm)"], 8) = 46.17974275 and Number.Round([pH Level], 9) = 7.891396294 then "Venlafaxine 75mg"
        else if Number.Round([#"Particle Size (μm)"], 7) = 96.1939718 and Number.Round([pH Level], 7) = 7.2364361 then "Sertraline 50mg"
        else if Number.Round([#"Particle Size (μm)"], 7) = 55.7764103 and Number.Round([pH Level], 7) = 6.5767670 then "Duloxetine 30mg"
        else if Number.Round([#"Particle Size (μm)"], 7) = 74.5121414 and Number.Round([pH Level], 7) = 6.9478424 then "Fluoxetine 20mg"
        else if Number.Round([#"Particle Size (μm)"], 7) = 89.3173163 and Number.Round([pH Level], 7) = 6.4749571 then "Fluoxetine 20mg"
        else null
        ```
    - I removed other map columns and moved ```Particle pH Product Name``` next to ```Product Name```.

<br>

- ```Final Product Name```
    - I created a ```Final Product Name``` column using conditional logic to integrate the ```Particle pH Product Names``` with the mapped product names.

<br>

- ```CAPA Required```
    - For ```CAPA Required```, there were 161 nulls.
    - I added ```Final CAPA Required``` column with logic:

        ```m
        if [CAPA Required] = null and [Closed Date] <> null then "No"
        else if [CAPA Required] = null then "Pending"
        else [CAPA Required]
        ```

- ```CAPA Closed```
    - For ```CAPA Closed```, there were 1092 nulls.
    - I added ```Final CAPA Closed``` column with logic:

        ```m
        if [Final CAPA Required] = "No" and [CAPA Closed] = null then "No"
        else if [Final CAPA Required] = "Pending" and [CAPA Closed] = null then "Pending"
        else [CAPA Closed]
        ```
    - This ensures that ```CAPA Closed``` aligns with the final status of each investigation.

- ```CAPA Number```
    - For ```CAPA Number```, there are also 1092 nulls. 
    - These nulls exist because there is No ```CAPA Required``` or ```CAPA Required``` is still Pending. 
    - Therefore these nulls are valid and its standard practice to leave them as is.
    - All other columns had 0 nulls. 

#### Handling Duplicates
---
- **Checking for Duplicate Rows**
    - To check for duplicate rows, I referenced the merged query again and renamed it ***Check Duplicate Rows***.
    - I selected all columns in the table and chose ***Keep Duplicates***.
    - There were 10 rows in the output.
    - I then ordered them by ```Standardized Open Date``` to make them easier to read.
    - After confirming that there were indeed duplicate rows, I decided to remove them from the merged table (***Merge: Batch To Product***).
    - I then checked the ***Check Duplicate Rows*** query again and found no duplicates present.

- **Unique Column: CAPA Number Duplicates**
    - I now checked for duplicates on a column basis.
    - The only column where I expect unique values in each row is the ```CAPA Number``` column, since it’s not standard practice to reuse ```CAPA Numbers``` in multiple investigations.
    - To check for duplicates in the ```CAPA Number``` column, I referenced the ***Merge: Batch to Product*** query and called this new query ***Duplicates: CAPA Number***.
    - I selected the ```CAPA Number``` column and chose ***Keep Rows → Keep Duplicates***.
    - This filtered the query to only duplicate ```CAPA Numbers```, and I then removed nulls from the list of duplicates.
    - There were 208 duplicates.
    - I sorted these values in ascending order for easier review by stakeholders.

- **Treating CAPA Number Duplicates**
    - I’m choosing to keep the duplicate ```CAPA Number``` rows because each row contains unique information that may be useful in the analysis—it wouldn’t be accurate to just remove them.
    - I also noticed that in certain cases, the same ```CAPA Number``` in different investigations has conflicting ```Final CAPA Closed``` statuses.
    - For example, one investigation for a CAPA might be pending while another is closed (marked ***Yes*** in ```Final CAPA Closed column```).
    - To flag these cases, I referenced the ***Duplicates: CAPA Number*** query and Grouped this query by ```CAPA Number``` on All Rows.
    - I added a custom column called ```Unique Closure Count``` that counts the unique values in ```Final CAPA Closed``` for each ```CAPA Number``` using this formula:

        ```m
        = List.Count(List.Distinct([Count][Final CAPA Closed]))
        ```

    - If the value is 2, there’s both a ***Yes*** and a ***Pending*** in ```Final CAPA Closed```.
    - If the value is 1, it means the ```Final CAPA Closed``` status is consistent across that ```CAPA Number```.
    - I then filtered only for values of 2 in ```Unique Closure Count``` to highlight the problematic ```CAPA Numbers```.
    - There were 45 rows/45 ```CAPA Numbers``` with this issue, and I sorted the ```CAPA Number``` column in ascending order for better review.

#### Outlier Detection
---

- **Detection Logic: Particle Size and pH Level**
    - There were 2 columns with measurable values for outlier detection: 
        - ```Particle Size (μm)``` and ```pH Level```.

    - I decided to detect outliers for each ```Product Name``` separately, as different products have different pH and particle size ranges. 
    - This makes detection more accurate than lumping all products together.

<br>

- **Outlier Detection: Skewness and IQR Method**

    - I referenced the ***Merge: Batch To Product*** query and performed an ***Advanced Group By*** operation, grouping by ```Final Product Name```.
    - For each group, I calculated means and medians for ```Particle Size``` and ```pH Level```, as well as a row count column.
    - I added two custom columns:

        - ```Skewness: Particle Size```

        - ```Skewness: pH```

    - The skewness check formula (example for Particle Size):
        ```m
        let
            mean = Number.Round([#"Mean: Particle Size"], 1),
            median = Number.Round([#"Median: Particle Size"], 1),
            tolerance = 1,
            skew = 
                if Number.Abs(mean - median) <= tolerance then "Symmetric"
                else if mean > median then "Right-skewed"
                else "Left-skewed"
        in
            skew
        ```
        - Similarly, I applied the same logic to ```pH Level```.

        - Since all products had symmetric skewness for both ```Particle Size``` and ```pH Level```, I decided to use the IQR Method.

<br>

- **IQR Method – Outlier Detection Columns**
    - I added two custom columns:

        - ```Outliers: Particle Size```

        - ```Outliers: pH Level```
    - Example formula for ```Outliers: Particle Size```:
        ```m
        let
            values = List.RemoveNulls([All Rows][#"Particle Size (μm)"]),
            sorted = List.Sort(values),
            q1 = List.Percentile(sorted, 0.25),
            q3 = List.Percentile(sorted, 0.75),
            iqr = q3 - q1,
            lower = q1 - 1.5 * iqr,
            upper = q3 + 1.5 * iqr,
            flag = List.Transform(values, each if _ < lower or _ > upper then "Outlier" else "In Range")
        in
            flag{0}
        ```
    - The same logic was used for ```Outliers: pH Level```, substituting the appropriate column.

- **Outlier Treatment: No Outliers**
    - After expanding all rows and checking the filter in the Outliers columns, all values were ***“In Range”***, meaning there were no outliers.
    - No outlier treatment was necessary.

#### Final Columns After Cleaning
---
After completing the data cleaning process in Power Query, the final columns in the ***Merge: Batch To Product*** query (which is my final cleaned table) were: 
- ```Final Standardized Open Date```, 
- ```Closed Date```, 
- ```Final Days To Resolution```, 
- ```Resolution Category```, 
- ```Batch Number```, 
- ```Final Product Name```, 
- ```Department```, 
- ```Deviation Category```, 
- ```Root Cause```, 
- ```Impact Severity```, 
- ```Final CAPA Required```, 
- ```Final CAPA Closed```, 
- ```CAPA Number```, 
- ```Investigator```, 
- ```Particle Size (μm)```, 
- ```pH Level```

#### Loading Queries
---
- The ***Merge: Batch To Product*** query was the only query loaded into Excel as a table.
- All other queries thus far have been loaded as connection only.
---

### Dashboard Creation and Graph Plotting in Excel
- **Overview**
    - The dashboards were created with a mix of Power Pivot data modeling, dynamic DAX measures, and robust Excel-based calculations (including moving averages and categorical breakdowns). 
    - The visualizations were built with PivotCharts, line charts, scatter plots, and boxplots, all seamlessly integrated and interconnected using slicers to create an interactive and insightful analytical experience.
- **Data Model and DAX Measures in Power Pivot**
    - <u>Key Components</u>:

        - Two main tables: ```Slicer Attempt``` and ```2 Merge Batch To Product```.

        - Three slicer dimension tables: ```Slicer Department```, ```Slicer Product```, and ```Slicer Investigator```.

        - A ```Calendar``` table to handle time-based calculations and ensure accurate cumulative measures.

    - <u>Relationships</u>:

        - One-to-many relationships established between the dimension slicer tables and the main data tables.

        - ```Calendar[Date]``` linked to both ```Slicer Attempt[Date]``` and 2 Merge Batch To Product’s open/closed dates.

- **DAX Measures for Investigation Dashboard (example)**:

    ```DAX
    Opened Investigations :=
    CALCULATE(
        SUM('Slicer Attempt'[Count]),
        'Slicer Attempt'[Status] = "Opened"
    )

    Closed Investigations :=
    CALCULATE(
        SUM('Slicer Attempt'[Count]),
        'Slicer Attempt'[Status] = "Closed"
    )

    Cumulative Opened :=
    CALCULATE(
        [Opened Investigations],
        FILTER(
            ALL('Calendar'),
            'Calendar'[Date] <= MAX('Calendar'[Date])
        )
    )

    Cumulative Closed :=
    CALCULATE(
        [Closed Investigations],
        FILTER(
            ALL('Calendar'),
            'Calendar'[Date] <= MAX('Calendar'[Date])
        )
    )

    Net Open Investigations :=
    [Cumulative Opened] - [Cumulative Closed]

    ```


    - Additional DAX measures were created for calculating KPIs like ```Total Cases```, ```Open Cases```, ```Closed Cases```, ```Impact Severity``` counts and ```CAPA status```, ensuring dynamic and interactive Business Activity Numbers (BANs).

- **Graph Preparation and Plotting in Excel**
    - ***Investigation Volume Over Time***
        - A combo stacked area and line chart was created using PivotCharts.

        - PivotTable sourced from the Data Model (inserted into ```3 Model Net Open Closed``` sheet).

        - <u>Measures plotted</u>:

            - ```Opened Investigations``` and ```Closed Investigations``` as stacked areas.

            - ```Net Open Investigations``` as a line chart.

    - ***Resolution Categories and Root Cause Analysis***
        - Two horizontal bar charts created for categorical counts.

        - <u>PivotTables</u>:

            - **Resolution Category**: ```1 Resolution Category``` sheet.

            - **Root Cause**: ```2 Root Cause``` sheet.

        - Charts linked to the data model to ensure universal slicer functionality.

    - **Moving Average Trend Analysis**
        - For moving average graphs, Excel formulas using AVERAGEIFS within tables (```MA``` table) dynamically calculated 7-day moving averages, e.g.:

            ```excel
            =IFERROR(AVERAGEIFS($C$2:$C$1880, $B$2:$B$1880, ">=" & B2 - 6, $B$2:$B$1880, "<=" & B2), "")
            ```
        - Separate calculations for total cases and impact severity categories (```Critical```, ```Moderate```, ```Minor```).

        - Line charts plotted on ```4 Moving Average Graphs``` sheet and then embedded in the dashboard.

    - **Product Quality Metrics and Variability**
        - <u>Scatter plot of ```Particle Size``` vs. ```pH Level``` per Product</u>:

            -  Data series manually added per product for color-coding.

        - <u>Boxplots</u>:

            - One for ```pH Level``` and another for ```Particle Size```, created using Insert Box & Whisker charts.

            - Charts originated from the ```5 pH vs Particle Scatter``` sheet.

- **Slicers and Dashboard Assembly**
    - <u>Universal Slicers</u>:

        - Created directly from data model tables or the working Excel tables for each dashboard.

        - Slicers linked to PivotTables and PivotCharts via the ***Report Connections*** feature.

    - <u>Dashboard Layout</u>:

        - Graphs and slicers were copied from source sheets and placed in well-defined areas on the respective dashboard sheets.

        - Each dashboard section (BANs, Graph Area, Navigation, and Slicers) was carefully formatted for clarity and aesthetic consistency.

- **Dynamic BANs using Excel Formulas**
    - For sheets not directly using Power Pivot:

        - Excel’s ```SUBTOTAL```, ```OFFSET```, and ```SUMPRODUCT``` functions were leveraged to create dynamic KPIs that responded to slicer selections.

        - <u>Example formula for dynamic counts</u>:
        
            ```excel
            =SUMPRODUCT(SUBTOTAL(103, OFFSET(MA[Final Standardized Open Date],
            ROW(MA[Final Standardized Open Date])-MIN(ROW(MA[Final Standardized Open Date])), 0, 1)))
            ```
        - These formulas ensure real-time updates of KPIs such as ***Investigation*** Counts, ***Impact Severity*** breakdowns, and ***CAPA*** metrics.

<br>

- **Final Touches and Design**
    - Color schemes and font styles were applied consistently to ensure visual coherence.

    - Navigation buttons and icons were inserted to enable seamless user interaction.

    - All graphs and BANs were tested for slicer responsiveness to ensure interactivity across all dashboards.

