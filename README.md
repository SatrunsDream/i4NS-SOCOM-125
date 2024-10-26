<style>
    body {
        text-align: center;
    }
</style>

# Cold Blooded

# Introduction
Our project is dedicated to solving a critical challenge faced by U.S. Army medics: keeping blood cool for extended periods in the field to preserve its viability for life-saving transfusions. In combat situations, the ability to quickly administer blood can be the difference between life and death. However, current solutions for blood storage are limited by size, portability, and duration of cooling. Small and medium storage units only preserve blood for 24-36 hours, and larger units, while capable of indefinite cooling, are bulky and require an electrical power source, making them impractical for use in the field.

Our goal is to develop a portable, efficient, and durable blood storage solution that can maintain the required temperature for extended periods without relying on external power. This project focuses on creating innovative packaging solutions that are lightweight, "squish-proof," and capable of significantly increasing the shelf life of stored blood. By incorporating cutting-edge materials and preservation technologies, such as cyclodextrin treatments, we aim to extend blood viability beyond current limits, providing medics with the tools they need to save more lives on the battlefield.

This repository will document our research, designs, and developments as we work toward creating a solution that could revolutionize battlefield medicine.

# Background Information

## Blood Storage Requirements
Blood preservation is essential to maintain its viability for transfusions. After being drawn, blood can be safely stored for up to 35 days if kept below 10°C. At higher temperatures, bacteria may proliferate, contaminating the blood and rendering it unusable. When blood is transported, it must remain between 6°C and 10°C for up to 4 hours, but must then be returned to storage below 6°C to extend its usability. Theoretically, this temperature-controlled cycling can repeat without affecting viability, although extended and repeated transport remains challenging.

## Blood Components and Preservation Needs

Blood consists of several components, each playing a unique role:

- **Plasma** – Comprising about 55% of blood, plasma is primarily water (90%), along with electrolytes, proteins, hormones, and waste products. Plasma acts as a transport medium for other blood components.
- **Erythrocytes** – These red blood cells (RBCs) make up 45% of blood, carrying oxygen via hemoglobin and giving blood its color.
- **Leukocytes and Platelets** – Making up around 1% of blood, these white blood cells are crucial for immune responses and blood clotting.

Each component has distinct storage needs, but RBCs, the main element in transfusions, are particularly temperature-sensitive.

## Quality Assessment Biomarkers

To maintain blood quality during storage, various biomarkers are monitored to assess cell integrity, metabolic stability, and potential degradation. Key biomarkers include:

 **Red Blood Cell (RBC) Integrity**
   **Kynurenine**: Used to monitor RBC preservation, assessing cell stability over time.

 **Frozen/Thawed Blood Quality**
   **Gamma-Glutamyl Transferase (GGT)** and **Lactate Dehydrogenase (LDH)**: Indicators of cellular breakdown, especially for blood that has been frozen and thawed.

 **Room Temperature Blood Stability (Up to 48 Hours)**
   **Interleukin-6 (IL-6)** and **C-Reactive Protein (CRP)**: Useful for assessing inflammation and degradation when blood is stored at room temperature for short durations.

These biomarkers, tailored to specific storage and experimental needs, help determine blood viability for transfusions and research applications.

## Blood Type and Antigen Challenges

Blood type compatibility is a major consideration for safe transfusions. The presence of antigens on RBCs determines blood type, with O- blood being a universal donor and AB blood being a universal recipient. However, limited availability of O- blood can make transfusions challenging, especially in remote or field operations.

| Blood Type | Description                |
|------------|----------------------------|
| A+         | Type A with Rh positive    |
| B+         | Type B with Rh positive    |
| AB+        | Type AB with Rh positive   |
| O+         | Type O with Rh positive    |
| A-         | Type A with Rh negative    |
| B-         | Type B with Rh negative    |
| AB-        | Type AB with Rh negative   |
| O-         | Type O with Rh negative    |
