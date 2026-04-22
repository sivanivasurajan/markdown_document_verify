# ASHRAE Decarbonisation Guide

Building Decarbonization Retrofits for Commercial and Multifamily Buildings

Building Decarbonization Retrofits for Commercial and Multifamily Buildings

This publication was prepared under the auspices of ASHRAE’s Center of Excellence for Building Decarbonization (CEBD).

WORKING GROUP

David Heinzerling—Chair Taylor Engineers Daniel Nall Daniel Nall Consultant, LLC Cory Abramowicz Arup Shona O’Dea Skidmore, Owings & Merrill (SOM) James Del Monaco P2S Mike Reimer First Light Energy Solutions David Ellowitz AHA Consulting Engineers Ted Tiffany Building Decarbonization Coalition Jamie Kono Pacific Northwest National Laboratory Brett Webster RMI Eric Yang Vantage Data Centers

NORESCO PRIMARY AUTHORS

W. Michael Goodrum NORESCO Sally Blair NORESCO

NORESCO CONTRIBUTORS

John Arent Roger Hedrick Ian Roth Rahul Athalye Michele Hendrick Elvin Ruya Ozel John Balfe Zalmie (Zee) Hussein Michelle Scordino Scott Emerton Bob Jurovaty Pete Thomson Xia Fang Michael Kennedy Rachel Truttmann Sam Farouz Jeff Logarzo Kyra Weinkle Aaron Hart Afsheen Mashayekhi James Zarske Mark Haskell David Mowery

Literature Review and Research Contribution

Phani Arvind Vadali University of Colorado Moncef Krarti University of Colorado

ASHRAE CENTER OF EXCELLENCE FOR BUILDING DECARBONIZATION

Kent Peterson—Chair P2S Inc. Blake Ellis—Vice Chair Burns & McDonnell Ghina Annan Stantec Rajan Rajendran

Carrie Brown Resource Refocus, LLC Stet Sanborn SmithGroup Luke Leung Skidmore, Owings and Merrill Ginger Scoggins Engineered Designs, Inc. Bing Liu Pacific Northwest National Laboratory Stephanie Reiniche Director of Technology, ASHRAE Clay Nesler The Nesler Group

Building Decarbonization Retrofits for Commercial and Multifamily Buildings

#### Peachtree Corners

ASHRAE is a registered trademark in the U.S. Patent and Trademark Office, owned by the American Society of Heating, Refrigerating and Air-Conditioning Engineers, Inc.

ASHRAE has compiled this publication with care, but ASHRAE has not investigated, and ASHRAE expressly disclaims any duty to investigate, any product, service, process, procedure, design, or the like that may be described herein. The appearance of any technical data or editorial material in this publication does not constitute endorsement, warranty, or guaranty by ASHRAE of any product, service, process, procedure, design, or the like. ASHRAE does not warrant that the information in the publication is free of errors, and ASHRAE does not necessarily agree with any statement or opinion in this publication. The entire risk of the use of any information in this publication is assumed by the user.

Library of Congress Cataloging-in-Publication Data

Names: ASHRAE (Firm), author. Title: Building decarbonization retrofits for commercial and multifamily buildings. Description: [Peachtree Corners, Georgia] : ASHRAE, [2024] | Includes bibliographical references. | Summary: "Provides design engineers solutions and guidance for decarbonizing existing commercial and multi-family buildings. Covers HVAC electrification options and strategies specific to existing building setups; electrification challenges, barriers, and transition considerations; domestic hot water electrification, integration with other systems, heat recovery, thermal energy storage, control systems, equipment replacement cycle considerations, refrigerant considerations, life-cycle costs and financial incentives, cold-climate strategies, and non-HVAC considerations such as load shifting/reduction, on-site renewables, electrical storage, and EV charging"-- Provided by publisher. Identifiers: LCCN 2024007022 | ISBN 9781955516754 (paperback) | ISBN 9781955516761 (PDF) Subjects: LCSH: Sustainable buildings. | Buildings--Retrofitting. | Carbon dioxide mitigation. Classification: LCC TH880 .B877 2024 | DDC 690.028/6--dc23/eng/20240523 LC record available at https://lccn.loc.gov/2024007022

ASHRAE STAFF SPECIAL PUBLICATIONS Cindy Sheffield Michaels, Editor Mary Bolton, Associate Editor December Byrnes, Assistant Editor Michshell Phillips, Senior Editorial Coordinator PUBLISHING SERVICES David Soltis, Group Manager of Electronic Products and Publishing Services Jayne Jackson, Publication Traffic Administrator Director of Publications and Education Mark S. Owen

## Contents

Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . ix Acronyms. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . xi

# 1 INTRODUCTION . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1

## 1.1 Background . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .1

### 1.1.1 Why Decarbonization?. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1 1.1.2 What Does Decarbonizing Existing Buildings Mean? . . . . . . . . . . . . . . . . . . . . . 2 1.1.3 Building Decarbonization Strategies and Benefits. . . . . . . . . . . . . . . . . . . . . . . . 3

## 1.2 Existing Building Decarbonization in Building Codes and Ordinances . . . . . . . . . . . . . . .5

# 2 HOW TO USE THIS GUIDE . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 7

## 2.1 Purpose and Organization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .7 2.2 Case Studies. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .8

# 3 PATH FOR EXISTING BUILDING DECARBONIZATION . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13

## 3.1 Navigating Building Decarbonization. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .13 3.2 Decarbonization Planning . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .13

Decarbonization Retrofit Key Takeaways. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 15

### 3.2.1 Set Decarbonization Goals. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 16 3.2.2 Define Timeline . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 16 3.2.3 Define Scope and Level of Decarbonization Assessment . . . . . . . . . . . . . . . . . 17 3.2.4 Identify and Inform Stakeholders . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 19

## 3.3 Perform Decarbonization Assessment . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .21

### 3.3.1 ASHRAE Energy Audit and Decarbonization Assessment . . . . . . . . . . . . . . . . 21 3.3.2 Decarbonization Evaluation Tools . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 29 3.3.3 Assessing Building Portfolios . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 30

## 3.4 Prioritize/Determine Decarbonization Measures. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .32

### 3.4.1 Reducing Heating and Cooling Loads and Rightsizing Equipment . . . . . . . . . . 33 3.4.2 Maximize Building Systems Efficiency. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 35 3.4.3 Electrify Space Conditioning and Water Heating Systems. . . . . . . . . . . . . . . . . 36

Contents

### 3.4.4 Grid Interactivity . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 39 3.4.5 Distributed Generation and Clean Power Production . . . . . . . . . . . . . . . . . . . . . 39 3.4.6 Energy Storage . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 40 3.4.7 Embodied Carbon. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 41 3.4.8 Select the Best Combination of Measures . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 41 3.4.9 Financial Considerations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 43

## 3.5 Develop a Building Decarbonization Plan . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 46

### 3.5.1 Measure Summary and Implementation Triggers. . . . . . . . . . . . . . . . . . . . . . . . 47 3.5.2 Impacts to Electrical, Utility, or Other Infrastructure. . . . . . . . . . . . . . . . . . . . . 48 3.5.3 Achieving Projected Emissions After Measure Implementation . . . . . . . . . . . . 49 3.5.4 Other Considerations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 50 3.5.5 Portfolio Decarbonization Planning . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 50

## 3.6 Implement the Building Decarbonization Plan . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 54

### 3.6.1 Implementation for Building Portfolios . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 55

## 3.7 Track and Report Performance. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 55

### 3.7.1 Measure Installed Performance . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 56 3.7.2 Measure Ongoing Performance . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 57 3.7.3 Operation and Maintenance Procedures . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 58

# 4 CHALLENGES UNIQUE TO EXISTING BUILDINGS . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 61

## 4.1 Existing Building Considerations. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 61 4.2 Electrical Capacity . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 61 4.3 Structural Capacity. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 62 4.4 Building Age and Envelope/Infrastructure Condition . . . . . . . . . . . . . . . . . . . . . . . . . . . 63 4.5 Space Constraints . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 64 4.6 Local Building Codes and Ordinances. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 65 4.7 Historic Buildings and Regulatory Constraints . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 65 4.8 Occupant Considerations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66 4.9 Equity and Affordability. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 67

### 4.9.1 Disadvantaged Communities . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 68 4.9.2 Policies and Programs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 69

## 4.10 Building Owner Type . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 70

### 4.10.1 Building Owner Occupied . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 70 4.10.2 Leased Buildings . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 72

# 5 DECARBONIZATION STRATEGIES AND TECHNOLOGIES: BUILDING ELECTRICAL, HEATING AND COOLING LOAD REDUCTION. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 73

## 5.1 Electrical Load Reduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 73

### 5.1.1 Building Lighting Systems. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 73 5.1.2 Multifamily Kitchen Appliances and Cooking Systems . . . . . . . . . . . . . . . . . . . 75 5.1.3 Other Systems and Plug Loads. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 76

## 5.2 Heating/Cooling Load Reduction: Building Envelope and Passive Systems . . . . . . . . . 77

### 5.2.1 Building Envelope . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 78 5.2.2 Passive Strategies . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 81 5.2.3 HVAC Optimization . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 83

vi

# 6 DECARBONIZATION STRATEGIES AND TECHNOLOGIES: HVAC SYSTEMS . . . . . . . . . . . . . . . . . 89

## 6.1 HVAC System Retrofits. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .90

### 6.1.1 Gas Furnace Retrofits . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 92 6.1.2 Steam System Retrofits . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 98 6.1.3 Central Boiler Retrofits . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 99 6.1.4 Air-Source Heat Pump Considerations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 109

## 6.2 HVAC Control Sequences . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 111 6.3 Data Analytics and Monitoring Based/Continuous Commissioning (MBCx) . . . . . . . .114

# 7 DECARBONIZATION STRATEGIES AND TECHNOLOGIES: DISTRIBUTED GENERATION AND ENERGY STORAGE . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 115

## 7.1 Renewable Systems . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .115

### 7.1.1 Photovoltaic (PV) Systems . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 115 7.1.2 Other Renewable Systems . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 117

## 7.2 Battery Energy Storage Systems (BESS) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .120 7.3 EV Charging Systems . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .124 7.4 Grid-Interactive Systems . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .127 7.5 Thermal Energy Storage Systems . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .127

### 7.5.1 Sensible Heat Storage (SHS) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 129 7.5.2 Latent Heat Storage (LHS) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 132 7.5.3 Thermochemical Heat Storage. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 133 7.5.4 TES Integration with District Heating and Cooling (DHC) Systems . . . . . . . . 133

# 8 DECARBONIZATION STRATEGIES AND TECHNOLOGIES: DOMESTIC HOT-WATER SYSTEMS . . 135

## 8.1 Evaluating Existing Conditions. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .135

### 8.1.1 System Configuration and Condition. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 135 8.1.2 DHW Load Profile. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 136

## 8.2 Load Reduction and Rightsizing . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .137

### 8.2.1 Low-Flow Fixture Retrofit. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 138 8.2.2 Distribution and Storage Losses . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 139 8.2.3 Passive Heat Recovery (Drain-Line Heat Recovery) . . . . . . . . . . . . . . . . . . . . 139 8.2.4 Rightsizing. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 139 8.2.5 Sizing Methodology for Storage-Based Systems . . . . . . . . . . . . . . . . . . . . . . . 140 8.2.6 Sizing Methodology for Point-of-Use Systems . . . . . . . . . . . . . . . . . . . . . . . . 141 8.2.7 Sizing Considerations for Grid-Demand Response . . . . . . . . . . . . . . . . . . . . . 141

## 8.3 Distributed vs. Central Systems. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .141

### 8.3.1 Distributed DHW Systems. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 142 8.3.2 Central DHW Systems. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 143 8.3.3 Application Considerations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 143

## 8.4 Recirculation Systems . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .144

### 8.4.1 Reducing Recirculation Energy Losses . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 144 8.4.2 Direct-Return Systems. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 145 8.4.3 Recirculation System Considerations for Central Single-Pass HPWHs. . . . . . 145

## 8.5 Heat Pump Water Heaters . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .147

### 8.5.1 Heat Pump Types . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 147

vii

### 8.5.2 Refrigerants . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 148 8.5.3 Heat Pump Heat Sources . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 148

## 8.6 DHW Storage Systems. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 149

### 8.6.1 Cost and GHG Emissions Benefits of Increased DHW Storage . . . . . . . . . . . . 149 8.6.2 DHW Storage Considerations for Retrofits . . . . . . . . . . . . . . . . . . . . . . . . . . . 150 8.6.3 Controls and Automation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 150

## 8.7 Heat Recovery and Renewable Heat Sources . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 150

### 8.7.1 Heat Recovery . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 150 8.7.2 Renewable Heat Sources . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 151

## 8.8 Combined Systems and Hybrid Fuel Systems . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 151

### 8.8.1 Combined Systems. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 151 8.8.2 Hybrid Systems . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 153

Glossary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 155 Case Studies

Case Study 1: University of California, Santa Cruz— Phasing Approach. . . . . . . . . . . . . . . . . . . . . . . . . .159

Case Study 2: 345 Hudson, New York . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .161

Case Study 3: San Diego State University, California. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .167

Case Study 4: University of California, Santa Cruz—Cogeneration Plant . . . . . . . . . . . . . . . . . . . . . . . . .171

Case Study 5: The Heritage, New York. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .173

Case Study 6: Bloedel Conservatory, Canada. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .179

Case Study 7: StopWaste Office, California . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .183

Case Study 8: Montreal City Hall, Canada . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .185

Case Study 9: 47 Seventy Apartments, Utah . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .191

Case Study 10: McMullen County Courthouse, Texas . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .193

Case Study 11: Ken Soble Tower, Canada . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .195

Case Study 12: East Palo Alto Government Center, California. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .199

Case Study 13: Vera Cruz Village, California. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .201

Case Study 14: Skokie Courthouse, Illinois. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .205

Case Study 15: Stella B. Werner Council Office Building, Maryland. . . . . . . . . . . . . . . . . . . . . . . . . . . . . .209

Case Study 16: Virginia Beach City Public Schools, Virginia . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .213

Case Study 17: STAR Transit, Texas. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .217

Case Study 18: North Oak Development, Canada . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .219

Case Study 19: Kitsilano Pool, Canada. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .221

References . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 225

## 

## Acknowledgments

The chair of this working group, David Heinzerling, would like to thank this guide’s primary authors, NORESCO, for their perseverance and ability to successfully incorporate extensive feedback from a wide group of individuals. The working group drafted the original outline for this guide then worked with NORESCO to bring it to completion. We acknowledge support from the working group members' employers: Taylor Engineers, Pacific Northwest National Laboratory, P2S, FirstLight Energy Solutions, Arup, AHA Consulting Engineers, Skidmore, Owings & Merrill, RMI, Building Decarbonization Coalition, and Vantage Data Centers. The working group’s efforts were guided by the CEBD Executive Committee under the leadership of ASHRAE Fellow Kent Peterson and the operational guidance of Blake Ellis, CEBD Operational Subcommittee Chair. ASHRAE staff members Thomas Loxley and Stephanie Reiniche were instrumental in managing the process and keeping everyone organized and on track. In addition to the working group members, authors, and ASHRAE staff who made this guide possible, several individuals played key roles in the guide’s success. Among the working group members, Jamie Kono was a key contributor to the organization and content of Chapter 3, and Mike Reimer was a key contributor to the organization and content of Chapter 8. Significant thanks go to the working group members and TFBD Executive Committee, who dedicated their personal time to thoroughly reviewing the 65% and 90% drafts of the guide and provided feedback, which resulted in a much stronger and more valuable document than would have resulted otherwise. We thank all who provided their experience, insights, and time in the development of this guide, though any errors are the responsibility of the authors. Decarbonization of our existing building stock is one of the most important challenges of our time. We hope that this book provides practical and timely guidance for a wide range of interested parties. The solutions in this space are evolving rapidly, and no guide of this breadth can cover each topic exhaustively; thus, the authors have highlighted many other excellent references on specific topics throughout the book. While specific technological solutions will change over time, the key insights and planning framework presented in this guide will long be relevant. NORESCO would like to thank the following people and organizations for their support and assistance:

- Elena Alschuler, LaSalle Investment Management
- Sophie Cardona, NYSERDA—Empire Building Challenge
- Nora Hart, Lawrence Berkeley National Laboratory

Chapter Analysis Methods for BPS Policy Design

- ASHRAE working group members

Special thanks to these working group members for providing a detailed and thoughtful review and additional contributions to the guide:

- David Heinzerling
- Mike Reimer
- Jamie Kono
- Brett Webster

Special thanks to the various case study authors for the significant contribution each case study makes to the guide. University of California, Santa Cruz—Phasing Approach (Case Study 1) and  Cogeneration Plant (Case Study 4)

- Phil Boutelle, University of California, Santa Cruz
- Brett McQuillan, Affiliated Engineers, Inc. 345 Hudson, New York (Case Study 2)
- Ben Rodney, Hines San Diego State University, California (Case Study 3)
- James Del Monaco, P2S, Inc. The Heritage, New York (Case Study 5)
- Joe Weishaar, L+M Development Partners
- David Ash, L+M Development Partners
- Adam Szlachetka, Steven Winter Associates Bloedel Conservatory, Canada (Case Study 6) and Kitsilano Pool, Canada (Case Study 19)
- Mike Reimer, FirstLight Energy Solutions StopWaste Office, California (Case Study 7) and East Palo Alto Government Center,  California (Case Study 12)
- David Heinzerling, Taylor Engineers Montreal City Hall, Canada (Case Study 8)
- Lianne Cockerton, Martin Roy et Associés 47 Seventy Apartments, Utah (Case Study 9)
- Lillian Gerrity, iCAST McMullen County Courthouse, Texas (Case Study 10); Skokie Courthouse, Illinois (Case Study 14); Stella B. Werner Council Office Building, Maryland (Case Study 15); Virginia Beach City Public Schools, Virginia (Case Study 16); and STAR Transit, Texas (Case Study 17)
- NORESCO Ken Soble Tower, Canada (Case Study 11) and Vera Cruz Village, California (Case Study 13)
- Brett Webster, Rocky Mountain Institute North Oak Development, Canada (Case Study 18)
- Diego Mandelbaum, Creative Energy
- Keith Bate, Creative Energy
- Alex Girdner, Westbank Corp.

x

## Acronyms

ASHP air source heat pump BESS battery energy storage system BPS building performance standards CO2 carbon dioxide CHW chilled water CUI carbon use intensity Cx commissioning DCV demand-controlled ventilation DWHR drain water heat recovery EIFS exterior insulation and finish system EPC energy performance contract EPD Environmental Product Declaration ERV energy recovery ventilation ESPC energy savings performance contract EUI energy usage intensity EUL effective useful life GHG greenhouse gas GWP global warming potential GSHP ground-source heat pump HFC hydrofluorocarbon HPWH heat pump water heater IAQ indoor air quality ITC investment tax credit LCCA life-cycle cost analysis LFG landfill gas LHS latent heat storage LTHW low-temperature hot water MBCx monitoring-based commissioning MTCO2 metric tons of carbon dioxide NPV net present value OPR owner’s project requirements PCM phase-change material PPA power purchase agreement

Acronyms

RCx retrocommissioning ReCx recommissioning ROI return on investment SHGC solar heat gain coefficient SHS sensible heat storage SPB simple payback VAV variable air volume VRF variable refrigerant flow xii

## Introduction

## 1.1 Background

In response to the rising awareness of decarbonization’s vital role in confronting climate change, the ASHRAE Position Document on Building Decarbonization was published stating ASHRAE’s commitment to pursuing efforts related to building decarbonization. Applied to existing buildings, decarbonization is the reduction of carbon emissions through converting existing equipment and systems powered by fossil fuel combustion processes to highly efficient equipment and systems that use low-carbon or carbon-free fuels. It is the intent of this building decarbonization retrofit guide for existing commercial and multifamily buildings to serve as an educational resource on the processes of planning and implementing decarbonization efforts and to provide high-level technical guidance on available decarbonization technologies and strategies.

**[Figure: ASHRAE Position Document on Building Decarbonization]**

Type: diagram

Description: This figure presents a document from the American Society of Heating, Refrigerating and Air-Conditioning Engineers (ASHRAE) that outlines its position on building decarbonization. The document emphasizes the importance of decarbonization in addressing climate change and highlights the need for a holistic approach that includes healthy, safe, and comfortable environments, energy efficiency, environmental impacts, sustainability, operational security, and economics.

Key Elements:

*   **Title**: The title of the document is "ASHRAE Position Document on Building Decarbonization."
*   **Subtitle**: The subtitle reads, "Shaping Tomorrow's Built Environment Today."
*   **Logo**: The ASHRAE logo is displayed in the top-left corner of the document.
*   **Text**: The document contains several paragraphs of text that discuss the importance of decarbonization and the need for a holistic approach.
*   **Bullet Points**: The document includes bullet points that outline the key principles and strategies for decarbonization.
*   **Call to Action**: The document concludes with a call to action, encouraging readers to take steps to reduce their carbon footprint and contribute to a more sustainable future.

Overall, this figure provides a clear and concise overview of ASHRAE's position on building decarbonization and serves as a valuable resource for individuals and organizations looking to reduce their environmental impact.

### 1.1.1 Why Decarbonization?

In 2020, existing buildings were responsible for nearly 40% of energy-related greenhouse gas (GHG) emissions, quantified as carbon dioxide equivalent (CO2-eq), as shown in Figure 1.1. In ASHRAE Position Document on Building Decarbonization, ASHRAE established that the global built environment must halve its 2015 GHG emissions levels by 2030. It lists three main pillars of this plan:

- all new buildings are net-zero GHG emissions in operation,
- widespread energy-efficiency retrofits of existing assets are well underway, and
- embodied carbon of new construction is reduced by at least 40% (ASHRAE 2022h).

With the global building stock expected to double by 2060, strategic efforts must be made within the scope of these pillars to move from energy efficiency to decarbonization (ASHRAE 2022h). Though energy efficiency and decarbonization are related, once carbon emissions levels become the metric, the approach to high-performance building design changes in unexpected ways—namely, it becomes imperative to transition away from fossil-fuelburning appliances in concert with a greening grid. Efficiency is still important, as discussed further in Chapter 3, because peak load and other grid impacts become important as buildings transition to decarbonized systems along with the increasing adoption of electric vehicles (EVs).

**[Figure: Energy-related CO2 emissions in 2020]**

Type: chart

Description: This chart compares the energy-related CO2 emissions in 2020 across different sectors. The key insight is that the residential sector accounts for the largest share of emissions, followed by the industrial sector.

Data Representation:

- Residential (Indirect): 30%
- Residential (Direct): 16%
- Non-Residential (Indirect): 19%
- Non-Residential (Direct): 8%
- Building Construction (Embodied): 27%

Metric: Energy-related CO2 emissions

Chart Type: Pie chart

Units: Percentage

Chart Generation Hint:

- X-axis: Not applicable
- Y-axis: Not applicable

Structured Data (Machine Readable):

{ "chart_type": "pie", "metric": "energy-related CO2 emissions", "units": "percentage", "data": { "Residential (Indirect)": 30, "Residential (Direct)": 16, "Non-Residential (Indirect)": 19, "Non-Residential (Direct)": 8, "Building Construction (Embodied)": 27 }} }

### 1.1.2 What Does Decarbonizing Existing Buildings Mean?

Decarbonizing an existing building is the process of reducing its carbon emissions through the building’s life cycle. Generally, building construction, energy use, methane leakage, and refrigerants are the primary sources of GHG emissions (ASHRAE 2022h). This guide offers mitigation approaches such as building electrification, energy efficiency and demand management, embodied carbon considerations, and more for the various sources of building carbon emissions. Chapter 2 describes what can be found in each chapter and how to use this guide.

ASHRAE Public Policy Information Brief on Building Electrification

Building electrification is often viewed as an essential strategy for building decarbonization, but electrification, in and of itself, does not necessarily guarantee decarbonization. Existing buildings’ ability to electrify cost effectively will accelerate with technological improvements and local and national policy incentives. ASHRAE supports the global need to reduce emissions from buildings, including through beneficial electrification. This public policy information brief (PPIB) outlines the issues and considerations for policy makers regarding building electrification (ASHRAE 2023d).

BUILDING ELECTRIFICATION

THE ISSUE Building electrification is often viewed as an essential strategy for building decarbonization, but electrification, in and of itself, does not necessarily guarantee decarbonization. Building electrification refers to transitioning all or portions of building systems to electricity instead of on-site fossil fuel-based, non-electric energy. Space and water heating, some chilled water generation, snow melt, cooking, laundry, and emergency power backup commonly use on-site fossil fuel-based energy.

Electrification contributes to decarbonization when: (1) the electricity comes from low- or zerocarbon energy sources such as solar, wind, tidal/wave, hydro, and nuclear; or (2) when the efficiency of the new electric equipment results in overall GHG emissions reductions compared to on-site combustion. Therefore, action is needed by both the buildings and the electric grid sectors. Utilities must achieve their grid decarbonization goals by transitioning to low- or zerocarbon generation. Some regional grids have already decarbonized significantly, putting building electrification on a “fast track” toward total building decarbonization.

The growth of building (and transportation) electrification could require a significant increase in electrical grid capacity, emphasizing the need for energy efficiency, energy storage, grid interactive building design, and alignment of consumption with carbon-free generation (i.e., demand flexibility) to minimize the increase in peak demand. Building electrification can present embodied carbon, capital and operating cost, and retrofit challenges; it also provides an opportunity to improve air quality, especially in densely populated areas, by reducing particulate pollution and ground-level ozone from fossil fuel combustion. Many innovative energy efficient buildings with all-electric systems are already being built and occupied. Existing buildings’ ability to electrify cost-effectively will accelerate with technological improvements and local and national policy incentives.

ASHRAE’s ROLE ASHRAE stands at the forefront in supplying standards, guidance, and education for the design, manufacturing, installation, and operation of building systems. These resources can also provide governments with a technical foundation for beneficial building electrification policies. ASHRAE’s relevant consensus-based standards include new proposed standards and those being updated to specifically reflect decarbonization:

 Standard 90.1, Energy Standard for Buildings Except Low-Rise Residential Buildings  Standard 90.2, Energy-Efficient Design of Low-Rise Residential Buildings  Standard 100, Energy Efficiency in Existing Buildings (Note: This Standard is being updated as the Energy and Emissions Building Performance Standard)  Standard 105, Standard Methods for Determining, Expressing and Comparing Building Energy Performance and Greenhouse Gas Emissions  Standard 211, Standard for Commercial Building Energy Audits

ASHRAE Government Affairs Office 1255 23rd Street NW, Suite 825, Washington, DC 20037

Tel: 202.833.1830 | GovAffairs@ashrae.org

&UHDWHG)HEUXDU\202

#### 1.1.2.1 Types of Carbon in Existing Buildings

There are two types of carbon in existing buildings: operational carbon and embodied carbon. Embodied carbon comes from material extraction, manufacturing processes, transport, refrigerant leakage, and waste processing, while operational carbon is generated as the building uses energy and water during its operations.

**[Figure: Building whole-life carbon stages]**

Type: diagram

Description: This diagram illustrates the various stages of a building's life cycle, from raw material supply to end-of-life disposal or recycling. It categorizes these stages into embodied, operational, and circular economy phases, providing a comprehensive view of the environmental impact of buildings throughout their entire lifespan.

Key Elements:

- **Embodied**: This phase includes the raw material supply, manufacturing, transport to site, construction and installation process, use, maintenance, repair, replacement, refurbishment, deconstruction/demolition, transport to waste processing/disposal, waste processing, and disposal of waste.
- **Operational**: This phase encompasses operational energy use and operational water use.
- **Circular Economy**: This phase involves benefits and loads, reuse, recovery, recycling, and potential.

The diagram effectively visualizes the complex interactions between different stages of a building's life cycle, highlighting the importance of considering environmental impacts beyond just the operational phase.

1.1.2.1.1 Embodied Carbon

Significant amounts of a building’s emissions occur as embodied carbon during the construction phase, especially for new construction because foundation materials such as steel and concrete have high embodied carbon. For existing buildings, embodied carbon must be accounted for when considering the “in-use” stage of embodied carbon—including refrigerant leakage, equipment, or building systems replacements (such as windows)—because the deconstruction, waste processing, and materials replacement still occur during renovation. Because this guide targets decarbonization of existing buildings, the strategies presented for embodied carbon reduction will focus on use stages B1–B5, including refrigerant leakage, retrofits, and replacements. Tools for calculating a project’s embodied carbon and assessing low-emissions materials are outlined in Section 3.3.2 in Chapter 3.

1.1.2.1.2 Operational Carbon

Operational carbon reductions are accomplished through upgrades to the building envelope, lighting, and building systems and through electrification of HVAC, water heating, and appliances. These types of upgrades reduce fossil fuel consumption during building operations, thereby reducing emissions. This emissions reduction can be monitored through regular benchmarking for energy use and energy audits to compare the building’s operational carbon over time. Chapter 3 lays out the steps to decarbonizing through renovation and outlines procedures to assess and monitor carbon consumption related to building operations.

### 1.1.3 Building Decarbonization Strategies and Benefits

There are many ways to decarbonize buildings, from passive envelope retrofits to implementing demand response controls. These different decarbonization approaches fit into six strategies that contribute to emissions reduction in various ways. The six strategies are shown in Figure 1.3. Strategies that are appropriate for a given existing building depend on that building’s specific characteristics. Chapter 3 offers a pathway to identify energy-efficiency measures (EEMs) and emission-reduction measures (ERMs) that employ the strategies summarized here. Four primary benefits of implementing decarbonization in existing buildings are reduced operating costs, mitigation of climate change impacts, improved occupant health and well-being, and economic benefits for communities.

**[Figure: Figure on page 17]**

Type: diagram

Description: The diagram illustrates the various ways to reduce peak loads and increase efficiency in building systems. It highlights the importance of replacing equipment, systems, and controls to increase efficiency and reduce peak loads.

Key Elements:

*   Electrifying building systems replaces fossil-fuel-burning equipment with electric.
*   Utilizing heat pump space and water heaters, thermal networks, and electric appliances reduces emissions as electric grids decarbonize.
*   Embodied Carbon
*   Grid Interactivity
*   Renewables & Storage
*   Low GWP Fuels/Refrigerants
*   Energy Efficiency

The diagram provides a comprehensive overview of the strategies that can be employed to reduce peak loads and increase efficiency in building systems. By replacing equipment, systems, and controls, and utilizing heat pump space and water heaters, thermal networks, and electric appliances, buildings can significantly reduce their energy consumption and emissions. Additionally, the diagram highlights the importance of embodied carbon, grid interactivity, renewables and storage, low GWP fuels/refrigerants, and energy efficiency in achieving these goals. Overall, the diagram provides a valuable resource for building owners, managers, and designers looking to reduce their environmental impact and improve the efficiency of their buildings.

- Reduced Operating Costs. Building operating costs may decrease due to more efficient equipment replacing older equipment, rightsizing building systems, on-site renewable generation, and other conservation measures. Depending on pricing structure, utility costs may also be reduced by limiting consumption during peak hours through peak load-reduction strategies such as passive design, controls, energy storage, and demand response.
- Mitigation of Climate Change Impacts. ASHRAE recognizes the need to reduce GHG emissions from existing buildings to mitigate the impacts of climate change including climate-caused disasters and displacements. Extreme heat for prolonged periods, intensifying storms, and unhealthy air quality are some of the impacts we are experiencing; these have outsized consequences for front-line community members.
- Improved Occupant Health and Well-Being. Well-designed decarbonized building systems promote increased indoor air quality (IAQ) through weatherization, proper ventilation, and the elimination of nitrogen dioxide, carbon monoxide, and other chemical emissions generated on-site. Existing building upgrades are also an opportunity to increase occupant comfort through HVAC control strategies, daylighting and glare mitigation, etc.
- Community Economic Benefits. Significant investments are being made to grow a workforce skilled in building decarbonization. Design consultants, contractors, building officials, and facility managers are just a few of the roles that will require new skills and increased numbers to meet the demands of emerging decarbonization policy. The need for an upskilled and increased workforce may result in a greater number of higher-quality jobs. Climate-related disasters and mitigation are also a significant cost to communities. Disaster-related recovery costs often result in the displacement of community members.

## 1.2 Existing Building Decarbonization in Building Codes and Ordinances

Building energy codes have focused primarily on reducing energy consumption for new construction buildings and major renovations and on addressing alterations when equipment or building components are replaced by the building owner. However, a growing number of jurisdictions, such as Denver, New York City, Vancouver, and the State of Washington, have realized that existing building decarbonization must be part of the strategy to meet their emissions reduction goals. As a result, ordinances have become increasingly popular requiring existing building owners to report their consumption through building benchmarking and, in some instances, reduce it through building performance standards (BPS). ASHRAE has created a companion guide on building performance standards to address the policy aspect of achieving existing building decarbonization.

Building Performance Standards: A Technical Resource Guide

This guide is intended to provide a technical basis and resources to policy makers, building owners, facility managers, design professionals, and ASHRAE members when developing and implementing building performance standards (BPS) (ASHRAE 2023g). The guide focuses on larger building types and scope of BPS as developed by leading U.S. cities and states. The guide covers BPS aimed at reducing building operating energy use and resulting emissions and does not cover embodied energy or carbon, which are addressed by the Whole-Life Carbon Guide for Building Systems.

Building Performance Standards A Technical Resource Guide

ASHRAE U.S. Department of Energy

## How to Use This Guide

## 2.1 Purpose and Organization

This guide is organized to take the reader on a path through a decarbonization project, including goal setting, planning, identifying strategies, implementation, metric tracking, financing, and specific considerations for existing buildings. Each chapter contains actionable steps and resources. Case studies of real projects are referenced throughout the guide to illustrate suggested procedures, systems, and technology with real success stories and lessons learned. The guide intends to encompass the best practices for developing and conducting decarbonization retrofits for commercial and multifamily buildings.

### Table: Data Table

|  | Chapter 3 lays out the path for decarbonizing an existin g building. It covers the planning process, including goal settin g and stakeholder engagement, how to conduct a decarboniza- tion assessment, determining appropriate decarbonization measures, drafting an implementation plan, implementing th e plan, and tracking metrics. |
|---|---|
|   FB IE Sc 4 LeN o noN a UA es wv YE Nt riN Rn es gF rg yCI N i_ T c cI N gA SS o Ln soL  ts W Jt er Y ru W aTc tt ܪ ioi Yo nn Y aN R NSL  IRM E C“ PfreugPG ro qta em uEU us prN iaL p eb rer lDA a sy i mnni uTI n gN ” seI g pO tnfG aowo tN is rl n i itS c ahi be is lity  T E ) OgC rW piN d[ tH i-N mS iN nL itI z eC J irnS cA gJ oL W snL mnB ^ eE aJ crN K ttܪ i vE bH iuF tNJ yiI lS T d H iS n^ g  EB NE Adn SsueeN ucV stc phEI - taz piR aeF re oO ivbI nr riT oo tnN nS ng bgM i iozc aaE to tyetlrN si npo gT aon onr A aaa tlL n t ed n o p s l ai g li s  Iamndp rsoavfientgy health | Chapter 4 addresses constraints such as structural capacit y and available space, infrastructure conditions, renovating an occupied building, financing, local building codes and ordi- nances, and buildings with district systems. |

### 2.1.1 Building Types Addressed Within This Guide

This guide addresses commercial and multifamily building types. Commercial buildings come in a range of sizes and variety of uses. For the purposes of this guide, commercial buildings are categorized into three sizes: small, medium, and large. The three categories group buildings that typically have similar considerations and system types. Multifamily buildings are treated as distinct from commercial buildings.

### Table: Data Table

|  |  |  |
|---|---|---|
| Small Commercial < 10,000 ft2 (< 929 m2) | Medium Commercial > 10,000 ft2 and ≤ 50,000 ft2  (> 929 m2 and < 4645m2) | Large Commercial > 50,000 ft2 (> 4645 m2) |

### Table: Data Table

|  |  |
|---|---|
| Multifamily | Hotel/Lodging |

A list of acronyms is included for the reader’s convenience and quick access. A glossary of terms is included in the back for reference.

## 2.2 Case Studies

The appendix includes a variety of case studies to demonstrate decarbonization retrofits. These case studies represent different building types, systems, and approaches to help illustrate the principles presented within this guide.

### Table 2.1    Case Study Specifications

| Case Study Number and Name | Building Type and Location | Highlights | Sections |
|---|---|---|---|
| University of California, Santa Cruz— Phasing Approach | Santa Cruz, CA | • Phasing approach to decarbonization of portfolio of buildings • Address immediate needs with high-efficiency boilers or local heat pumps • Modular, centralized “decarbonization stations” of ASHPs, TES, and electrical infrastructure piped to nearby buildings | 3.2.1 3.2.2 3.4.3 |
| 345 Hudson, New York | New York City, NY | • Comprehensive data strategy by connecting all the current equipment on a common platform • Floor-by-floor replacement of packaged termina l units by WSHP and DOAS phased for tenant turn- over • WSHP loop with minimum 85% heat recovery • ASHP connected to condenser water loop as part of a masterplan to phase out boiler • TES water storage tank and connection to adjacent 555 Greenwich for thermal energy transfer given the varying orientation/occupancy of each building • Exploring WSHP for DHW production | 3.2.3 3.4.8 3.5.1 6.1.3.4 6.1.3.5 6.3 7.5.1 |
| San Diego State University, California | San Diego, CA | • Cogeneration plant evaluated for transition to elec- trification • Evaluated three options for central plant retrofit: two full electric, one hybrid • Full electric options required upgrading electrical service • Hybrid plant selected to achieve partial electrifica- tion within existing electric capacity | 3.3.1.4 6.1.3 |
| University of California, Santa Cruz— Cogeneration Plant | Santa Cruz, CA | • Cogeneration plant evaluated for transition to elec- trification • Reviewed multiple scenarios to supply campus electric needs, reduce campus GHG emissions and realize financial investment in cogeneration plant | 3.4.3.2 |
| The Heritage | New York City, NY | • Reduced heating and cooling loads with EIFS at two buildings. Insulated, prefabricated metal panels with energy-efficient windows at building • Prefabricated panels included electrical infrastruc- ture and punchouts for PTHP upgrades, including capacity for future building electrification • Installation of PTHPs at one building with central ventilation upgrades and centralized controls • Common area dryer electrification at one building • VRF installation in common areas of two buildings • DHW electrification using centralized heat pump water heaters at one building • Submetering apartment electrical use at all three buildings for accurate tenant billing • Tenant engagement and education plan to under- stand purpose and operation of upgrades | 3.5.2 3.7 5.2.1.1 6.1.1.1 8.3.2 |
| Bloedel Conservatory | Vancouver, British Columbia, Canada | • LED lighting retrofit and roof replacement reduce cooling load • Convert CHW loop to low-temp HHW and CHW switchover loop • Replace chiller/boiler plant with two-pipe AWHP sized for 90% of heating load • Active demand reduction to operate AWHP within existing electrical capacity • AWHP sized for increased cooling load to account for future climate change | 4.2 6.1.3.2 |
| StopWaste | Oakland, CA | • Load assessment for increased RTU size and weight • Replaced R-22 VAV RTUs with R-401a VAV Pack- aged heat pump RTUs | 4.3 6.1.1.3 |
| Montreal City Hall | Montreal, Quebec, Canada | • Historic building and site drove many design deci- sions • Goal of no combustion on-site • Cold climate using purchased steam • Radiant heated ceilings with FCUs • DOAS minimized ductwork • ASHPs located indoors improves winter perfor- mance | 4.6 4.7 6.1.3.4 6.1.4 |
| 47 Seventy Apartments | Taylorsville, UT | • Naturally occurring affordable housing retrofit • LED lighting retrofit reduced electric demand • Replaced R22 central air split AC and gas furnaces with split ASHPs with gas furnaces for backup heating • Smart thermostats | 4.9 6.1.1.2 |

### Table 2.1    Case Study Specifications (Continued)

| McMullen County Courthouse | Tilden, TX | • LED lighting and window retrofits reduce cooling load, allowing for downsizing of existing heat pumps • Recommended insulation upgrades will further reduce cooling loads • Heat recovery and DOAS provide efficient retrofit for reduced load • Parking roof PV will provide clean on-site energy for VRF+DOAS | 5.1.1.2 5.2.1.3 |
|---|---|---|---|
| Ken Soble Tower | Hamilton, Ontario, Canada | • Triple-pane window replacements and envelope upgrades with mineral wool EIFS and liquid applied air barrier reduced heating and cooling loads • Replaced central boiler hydronic baseboards with VRF system with VAV boxes to provide cooling and heating • DOAS with ERVs for ventilation • Condensing boiler for DHW due to electric capac- ity limitations | 5.2.1.3 6.1.3 |
| East Palo Alto Government Center | East Palo Alto, CA | • LED lighting retrofit with occupancy controls reduced electric demand • Converted pneumatic to DDC with ASHRAE Guideline 36 sequences for HVAC efficiency improvement • VAV terminal units replaced with 2-row oversized coils and rezoned for lower HHW temp • Chiller/boiler plant replaced with rooftop AWHPs (1 with heat recovery) | 5.2.3.5 6.1.3.2 |
| Vera Cruz Village | Richgrove, CA | • Window replacement, weatherization, and prefabri- cated insulated roof panels for heating and cooling load reductions • Attic air sealing and insulation or conversion to non-ventilated attics (two buildings) • Replaced gas-fired packaged RTUs with ducted heat pumps with ERVs • PTHP (one building) and ducted split heat pump (one building) • Distributed HPWHs (three Sanden with 80 gal tanks, the rest hybrid HPWHs) • Carport PV with virtual net metering to share between owner and tenants | 6.1.1.3 7.1.1 8.3.1 |
| Skokie County Courthouse | Cook County, IL | • LED lighting retrofit with controls reduced electric demand • Window replacements and weatherization reduced heating/cooling loads • Converted pneumatic to DDC with demand-con- trolled ventilation and AHU scheduling for HVAC efficiency improvement • Replaced chiller/boiler plant with 200-ton GSHP with backup condensing boilers • GSHP well field sized for majority of cooling load and all but 484 heating hours per year for project economics | 6.1.3 |
| Stella B. Werner Council Office Building | Montgomery County, MD | • LED lighting retrofit reduced electric demand • Window replacements reduced heating/cooling loads • Mixed HVAC equipment types due to multiple ren- ovations • Replaced HVAC systems (chillers/boilers, RTUs, FCUs, WSHPs) with 300-ton VRF with heat recov- ery and DOAS • VRF refrigerant lines easier to implement with lim- ited ceiling height | 6.1.3 |
| Virginia Beach City Public Schools | City of Virginia Beach | • Phased project across multiple schools • Weatherization measures • For each school, installed central GSHP serving WSHP loop • Replaced packaged RTUs with GSHP RTUs | 6.1.3.5 |
| STAR Transit | Terrell, TX | • Bus fleet conversion to electric buses • Planned installation of PV • Evaluation demonstrating importance of BESS to align PV production with overnight bus fleet charging | 7.3 |
| North Oak Development | Oakfield, Ontario, Canada | • District ambient loop for new development • Ground source loop provides space heating/cooling for buildings • Modular design allows future buildings to be con- nected • DHW loads served by separate boiler | 7.5.4 |
| Kitsilano Pool | Vancouver, British Columbia, Canada | • 40% DHW load reduction from low-flow fixtures • After load reduction, central DHW system retrofit with CO ASHP and two 250-gallon storage tanks 2 | 8.2.1 |

## Path for Existing Building Decarbonization

## 3.1 Navigating Building Decarbonization

Chapter 3 describes the key steps in creating and implementing a decarbonization plan and monitoring, tracking, and reporting performance toward the plan. Key steps include:

- Section 3.2, Decarbonization Planning Establish a framework for decarbonization, which involves obtaining leadership buy-in, setting goals and baselines, establishing timeline and scope, and engaging with stakeholders.

- Section 3.3, Perform Decarbonization Assessment Assessing the building will identify opportunities and constraints that must be considered specific to the existing building.

- Section 3.4, Prioritize/Determine Decarbonization Measures Prioritizing and determining decarbonization measures is typically done as a part of the decarbonization assessment. Several aspects must be considered when determining the right package of measures to meet decarbonization goals. The assessment results will inform measure selection.

- Section 3.5, Develop a Building Decarbonization Plan Once the measures have been identified, an actionable plan should be detailed to create a playbook for the specific building, including considerations such as limiting disruptions to occupants, etc.

- Section 3.6, Implement the Building Decarbonization Plan Implementing the decarbonization plan moves the building down the path toward meeting its decarbonization goals.

- Section 3.7, Track and Report Performance Performance metrics must be tracked to demonstrate progress toward goals and eventual goal achievement, and to update the decarbonization plan as needed.

## 3.2 Decarbonization Planning

The first step to decarbonizing a building is to set the framework for decarbonization. Depending on the magnitude of desired emissions reduction, this can be a multiyear process. This planning process begins even before a building is assessed or decarbonization measures are identified. The steps involved in the planning process include:

**[Figure: Steps to achieving existing building decarbonization]**

Type: diagram

Description: This diagram illustrates the steps involved in achieving decarbonization for existing buildings. It outlines a comprehensive approach, from establishing a framework to implementing a decarbonization plan and tracking performance.

Key Elements:

- Establish Framework -> Set goals and baseline, define timeline, define scope, engage stakeholders
- Perform Assessment -> Decarbonization focus, evaluation tools
- Prioritize Measures -> Evaluate/reduce loads, maximize efficiency, electrify, optimize controls, consider generation and storage, calculate carbon impact, package measures, determine financing
- Draft Decarbonization Plan -> Summarize measures and triggers, project emissions, determine infrastructure impacts
- Implement Decarbonization Plan -> Minimize operational disruptions, monitor systems, communicate with occupants, plan site logistics
- Track and Report Performance -> Measure installed performance, measure ongoing performance, perform O&M procedures

- Set decarbonization goals
- Define timeline
- Define decarbonization scope and level of decarbonization assessment
- Identify and inform stakeholders

Decarbonization Retrofit Key Takeaways

- All GHG Emissions Matter. When developing a decarbonization retrofit project, the goal is to reduce wholelife carbon emissions. This means looking at operational carbon and embodied carbon, including from refrigerants.
- Partial Decarbonization Strategies Work. Not all projects can achieve complete decarbonization, or at least not all at once. Phased approaches with partial decarbonization that account for capital plans and equipment life still provide GHG emissions reductions. A 75% reduction is better than no reduction at all.
- A Shift in Mindset from Energy-Efficiency Projects. Many measures that traditionally had long paybacks for energy-efficiency projects should be evaluated under a new paradigm. When the costs of carbon and potential penalties from building performance standards are factored in, building envelope and heat recovery measures are often economical for decarbonization retrofits.
- Start Collecting Data Now. Building- and system-level data are critical for assessing the peak loads, which is an integral part of a decarbonization retrofit. If you are not collecting data, start collecting and storing it to provide a more accurate representation of the building load profile.
- Determine the Actual Peak Loads. Sizing equipment to match the actual peak heating and cooling loads is a critical part of decarbonization retrofits. Equipment is often oversized for the actual building load, and sizing new equipment, particularly heat pumps, to match the load can further reduce first costs and operating costs as well as the retrofit’s GHG emissions and embodied carbon.
- Perform a Building Stress Test. When replacing fossil fuel boilers with heat pumps, it is important to understand the heating hot-water temperatures necessary to meet the heating loads. Many heat pumps operate at lower temperatures than fossil-fuel-fired boilers, which may require upgrades, such as larger heating coils, to satisfy the loads.
- Alignment with the Capital Plan. Decarbonization retrofit projects often require phasing and should be aligned with facility capital plans. Assessments should highlight the measures that match up to the capital plan, flag items that are in the plan but on a different timeline and call out items that are not part of the capital plan. This also includes clearly identifying any required studies, such as electrical capacity or structural assessments, needed for assessing measures.
- Energy Storage. Electric and thermal energy storage can be key strategies to minimizing GHG emissions while meeting building thermal loads. Storage allows you to leverage clean energy production for use at times when the grid is “dirtier” and to capture excess generation from on-site clean energy production.

### 3.2.1 Set Decarbonization Goals

The critical first step of a decarbonization plan is to establish goals with buy-in from building ownership and stakeholders. Goals may be based on regulatory requirements, corporate goals, tenant requests, or other driving factors. Building performance standards are one such goal-setting mechanism employed by some governments. See Building Performance Standards: A Technical Resource Guide for detailed discussion on these ordinances and how they may affect existing building decarbonization goals. Goals may be chosen by a specific building or portfolio based on ownership or stakeholder interests, such as net zero by 2050, and may also include interim goals, such as 30% emissions reduction by 2030 compared to performance in 2015. Setting decarbonization goals may coincide with a GHG inventory or GHG baseline determination to set specific performance targets or as part of a larger portfolio prioritization effort.

Building Performance Standards: A Technical Resource Guide

This guide is intended to provide a technical basis and resources to policy makers, building owners, facility managers, design professionals, and ASHRAE members when developing and implementing building performance standards (BPS) (ASHRAE 2023g). The guide focuses on larger building types and scope of BPS as developed by leading U.S. cities and states. The guide covers BPS aimed at reducing building operating energy use and resulting emissions and does not cover embodied energy or carbon, which are addressed by the Whole-Life Carbon Guide for Building Systems.

Building Performance Standards A Technical Resource Guide

ASHRAE U.S. Department of Energy

CASE STUDY: University of California, Santa Cruz— Phasing Approach

In pursuit of UC Santa Cruz’s and the broader UC system’s goals, UCSC Chancellor Cindy Larive created a diverse Decarbonization and Electrification Task Force and charged them with researching the feasibility of reducing UCSC’s Scope 1 and 2 carbon emissions, ideally to zero, by 2030 or as soon as possible. See the UCSC Phasing Approach case study in the appendix for details on the decarbonization actions taken by UC Santa Cruz.

### 3.2.2 Define Timeline

The planning process should include establishing a timeline for implementing measures in meeting the building’s decarbonization targets. The timeline may be up to the building owner, or it may be dictated by an incentive program or local ordinance. Even if timelines-to-meet targets are set, there is still flexibility when deciding which decarbonization measures to implement and when. An important aspect of defining a timeline includes establishing a capital improvements budget. Minor decarbonization upgrades might be funded directly from the building’s operation and maintenance budget, but buildings that need significant improvements—or whole-building portfolios or campuses—may require more extensive planning and budgeting. As a result, a multiyear process may be required to determine the decarbonization strategy, outline required investment through contractor bids, and acquire the necessary funds. For facilities that have aging systems approaching the end of their effective useful life (EUL) or requiring persistent maintenance, planning for more efficient and electric replacement options is valuable when establishing a decarbonization timeline. In current practice, equipment is often replaced upon failure and requires immediate replacement. Not having adequate electrical and/or structural infrastructure, or a plan to address such failures, can result in extra downtime that makes certain decarbonization measures less attractive or unfeasible. Sections 4.2 and 4.3 in Chapter 4 include more discussion of electrical and structural infrastructure upgrade considerations that should be part of the decarbonization timeline.

CASE STUDY: University of California, Santa Cruz— Phasing Approach

The University of California Santa Cruz decided on a phased approach to decarbonization for their campus. The plan implemented interim solutions when existing gas boilers were due for replacement. When a building had insufficient electrical capacity to support immediate installation of an air-source heat pump system, a condensing boiler replacement was chosen to lower direct emissions in the interim until sufficient electrical capacity or district heating was available to fully decarbonize the heating system. See the UCSC Phasing Approach case study in the appendix for more detail.

Other timeline considerations include taking advantage of available financial incentives (e.g., utility, municipal, state, federal) and impact on building occupants. Many incentives have a sunset date, intending to motivate customers to implement projects sooner than later.

Timing capital improvement projects to minimize the impact on occupants is a standard practice of existing building upgrades and being prepared to replace lighting or appliances during tenant renovations, for example, can be included in the building’s decarbonization timeline. Any facility that has a decarbonization goal, even if the due date to meet a target is well in the future, will benefit from developing a timeline as part of the planning process. Performing an assessment, determining measures, implementing measures, and collecting data for reporting may take several years, and these later steps in the process will benefit from cataloging timeline considerations during planning.

### 3.2.3 Define Scope and Level of Decarbonization Assessment

Together with defining the project timeline, determining the project scope is an important exercise when starting your decarbonization project. Scope decisions are often driven by the established performance targets and by economic feasibility. Additional factors may also play a role, such as equity considerations, resilience planning, seismic upgrades and preparedness, public relations, or impacts to the timeline. For tenant-occupied buildings, decarbonization measures likely will involve tenant systems requiring updates to design and operation requirements and potentially lease agreements. More on considerations regarding tenant-occupied buildings is included in Section 4.10.

CASE STUDY: 345 Hudson, New York

The case study for 345 Hudson defined scope and goals early. These were:

- Net zero by 2030
- Fossil-fuel-free heating
- 30% to 40% reduction in energy use
- Compliance with NYC Local Law 97

Another key item was minimizing disruptions to tenants. These goals drove the evaluation and selection of measures and implementation of a modular project that allowed phasing to minimize disruption.

**[Figure: Building Systems Involved in Building Decarbonization]**

Type: diagram

Description: This diagram illustrates the various building systems that play a crucial role in building decarbonization. It highlights the different components and technologies involved in reducing carbon emissions from buildings.

Key Elements:

*   Community Wind Turbines -> Generate renewable energy
*   Onsite Renewables & Storage -> Store excess energy for later use
*   Efficient Heat Pump HVAC -> Provide heating, ventilation, and air conditioning while minimizing energy consumption
*   High Performance Envelope -> Insulate the building to reduce heat loss and gain
*   High Performance Windows -> Allow natural light and reduce heat transfer
*   Building Controls -> Monitor and control energy usage in real-time
*   Efficient Electric Water Heater -> Heat water using electricity instead of fossil fuels
*   Efficient Electric Appliances and Lighting -> Use energy-efficient appliances and lighting to reduce energy consumption

This diagram provides a comprehensive overview of the building systems involved in building decarbonization, highlighting the importance of renewable energy, energy efficiency, and smart controls in reducing carbon emissions from buildings.

The project’s scope may become clearer once the decarbonization assessment has been conducted. An early scoping assessment may be helpful to establish focus for the more comprehensive decarbonization assessment where EEM/ERMs are identified. This scoping assessment will include basic GHG emissions and a financial evaluation and may be applied at a building level (for portfolios and campuses) and/or at a system level within individual buildings. Figure 3.2 illustrates building systems often involved in building decarbonization. Other systems, such as refrigeration, thermal energy storage (TES), and ventilation heat recovery, are not illustrated but should be considered when applicable.

Another step in defining the project scope is to determine what level of decarbonization assessment to conduct. Informative Appendix H, “Building Decarbonization Assessment,” in ANSI/ASHRAE/ACCA Standard 211-2018 (RA2023) describes Level 1 and Level 2 decarbonization assessments. Decarbonization goals for the building, existing conditions, and the available budget should be considered to determine the decarbonization assessment level needed.

When identifying measure options, the assessor will consider factors influencing owner priorities, such as:

- Capital costs to decarbonize the building

- Equipment nearing its EUL or that has persistent maintenance problems

- Utility availability and rate structures

- Cost and ease of maintenance for new equipment

- Passive or load-reduction strategies such as envelope improvements

Physical space, electrical capacity, or other limitations may drive decarbonized solutions in specific cases. Additional discussion of existing building limitations is included in Chapter 4. Scope may also be driven by the electric technologies being considered and how they can or cannot be applied based on the existing building’s constraints. Checking its electrical capacity during the assessment may influence the scope or timing of ERMs. Cost-effective efficiency measures can reduce the building’s electrical load and minimize the footprint of its necessary electrical infrastructure. For example, buildings whose lighting systems have not been upgraded recently could be converted to LED lighting or DC lighting as the first step toward decarbonizing because the whole-life carbon of LED lightbulbs is lower than incandescent. Then, prior to evaluating any all-electric heating options, measure the electrical use of the building to get the actual (new) load and compare it to the design electrical capacity. Having this information can help inform the retrofit scope and all associated costs including updates to other building systems and the electrical infrastructure to achieve a decarbonized building. More details on decision making around emissions reduction measures and scope can be found in Section 3.4. 3.2.3.1 Emissions Accounting Scope

Choosing which emissions to include in GHG accounting and goals is important in setting solid goals and achievable outcomes. The most common emissions to include are the energyrelated emissions, although some stakeholders may choose to include additional GHG emissions sources:

- Embodied emissions of building retrofits and maintenance
- Refrigerant leakage
- Operational emissions of landscaping or internal transportation vehicles (e.g., forklifts)
- Building occupant transportation emissions

The World Resource Institute’s Greenhouse Gas Protocol is often referenced when doing GHG emissions accounting, which breaks emissions down into direct emissions (Scope 1), indirect emissions (Scope 2), and all other emissions (Scope 3). The WRI GHG Protocol is not specific to the building industry, however, and ASHRAE has proposed Standards 240P and 242P to address the categorization of building-specific emissions. At the time of publication, this guide recommends categorization based on EN 15978 (CEN 2011), as referenced in Section 1.1.2.1 in Chapter 1, rather than the GHG Protocol.

### 3.2.4 Identify and Inform Stakeholders

The stakeholders in an organization typically include the investors/owners, employees, customers (people paying for the business products/services, using the facility, or paying local taxes), and suppliers, all of whom have a vested interest in the organization’s performance. Table 3.1 provides a broader list of examples of stakeholder categories and responsibilities that are commonly involved in organizational decarbonization planning. For a decarbonization project, investors/ owners and possibly customers will experience its economic impact. While the investors/owners pay for the decarbonization project, they will pass the cost along to the customers. Facilities managers may need special expertise to maintain the new system(s) and should be included in early discussions to ensure that intended savings persist over time. Because there is a financial commitment to decarbonizing the facility, investors are typically the first of the stakeholders to be informed and approve the project, along with any employed facilities support staff. Gathering input from facilities support staff is an important step because they are critical to the project’s long-term success. Ensuring that they understand the project’s goals and the need to change systems or operations will pave the path for efficient building operation after implementation. From there, communicating the environmental benefits of decarbonization to the employees and customers can boost morale by demonstrating a commitment to reducing GHG emissions. Further communication may include assembling and disseminating a case study on the project and/or having a poster in a public corridor of the building showcasing the project scope and GHG emissions savings. 3.2.4.1 Equity Considerations During Stakeholder Engagement

### Table 3.1    Stakeholders for Decarbonization Planning

| Stakeholder Category | Stakeholder Responsibilities |
|---|---|
| Executive Leadership | Provide resources and support to effectively develop and implement the plan (e.g., CEO, CFO, COO). |
| Finance | Identify the financial metrics required to assess the business case and provide guidance on potential financing mechanisms. |
| Property Management, Facilities/ Engineering, and Energy Management | Identify operational needs and maintenance concerns, suggest and evaluate technical solutions, and provide building-level information. |
| Capital Planning, Procurement, and Project Management | Identify workload expectations and opportunities to streamline procurement and project-delivery efforts when implementing activities at scale. |
| ESG/Sustainability | Identify sustainability considerations and expectations, including those beyond operational carbon emissions. Provide input on the risks and opportunities of the GHG Emissions Reduction Plan and review the plan through a lens of ESG regulatory and reporting requirements. |
| Real Estate and Transaction | Provide insight into the organization’s future space needs and incorporate decarbonization requirements into considerations for new construction or acquisitions. |
| Marketing | Identify ways to communicate efforts and GHG emissions reduction planning status within and beyond the organization. |
| Occupants and Community Members (External) | Identify ways to address occupant concerns and improve their overall experience through emissions reduction measures. Consider opportunities to collaborate with the broader community on larger-scale decarbonization efforts. |
| Source: Lawrence Berkeley National Laboratory (DOE 2023c) |  |

Decarbonizing existing buildings may have social and economic impacts, such as changes in property values, adjustments in rental rates and agreements, job creation, and community development. Building owners and managers should consider these factors when planning decarbonization efforts and work with stakeholders to ensure that they are aligned with community goals and needs. Listing the stakeholders that are affected by building operations and renovations is a good place to start this process. Conducting stakeholder outreach to understand the circumstances and priorities of each stakeholder group is an important part of the planning process. When buildings upgrades are required to meet performance targets, such as when there is a local building performance standard ordinance, additional support is often offered to address equity considerations. If the building is in a disadvantaged community or has unique equity circumstances, check with the local jurisdiction for additional resources available and for expectations around stakeholder engagement. Additional discussion and examples on how building renovations might affect equity are included in Section 4.9 in Chapter 4. For example, the University of California Santa Cruz is creating a Just Transition and Equity Subcommittee to conduct analysis around Diversity, Equity, Inclusion, and Justice while planning its campus decarbonization strategies. The subcommittee plans to use inclusive and community-centered approaches to gain feedback from a diverse group of stakeholders and community members. More information can be found in the Decarbonization and Electrification Predesign Report (Affiliated Engineers, Inc. 2023).

## 3.3 Perform Decarbonization Assessment

Before implementing any decarbonization strategies, it is essential to conduct a decarbonization assessment to assess the building’s consumption and emissions patterns and identify areas for improvement. The assessment results in an energy audit report and a decarbonization plan. The plan is then used by facility management to guide future decisions on energy efficiency measures (EEM) and emissions reduction measures (ERM) implementation.

### 3.3.1 ASHRAE Energy Audit and Decarbonization Assessment

Energy audits define the baseline condition of the existing building and its systems and are performed to varying levels based on the need, budget, and timing. ANSI/ASHRAE/ACCA Standard 211 establishes industry practices for conducting and reporting energy audits for commercial buildings (ASHRAE 2023c). A decarbonization assessment includes all the steps of an energy audit and adds additional efficiency and emissions reductions measures, including electrification measures (even partial electrification solutions), fugitive emissions reduction measures, and further renewable energy measures. Depending on established targets and the determined project scope, the decarbonization assessment may also evaluate embodied carbon of the existing building and systems. Table 3.2 compares the primary tasks between a traditional energy audit and a decarbonizationfocused assessment. ASHRAE/ACCA Standard 211 has an appendix (Informative Appendix H) describing the additional aspects related to a decarbonization assessment including the differences between Level 1 and Level 2 decarbonization assessments (ASHRAE 2023c).

#### 3.3.1.1 Pre-Retrofit Energy Use, Water Use, and GHG Emissions Analyses

As the name implies, in a typical energy audit, the primary focus is on energy use. A decarbonization assessment adds a water-use analysis and GHG emissions analysis to its purview. Water use affects GHG emissions calculations; therefore, water utility data should be reviewed and included in pre-retrofit data collection as well. As discussed in Section 8.2 in Chapter 8, efficiency improvements for domestic hot-water systems can reduce operational carbon due to the resulting reduction in water heating. Additionally, water efficiency improvements can reduce impacts from downstream wastewater treatment. The forthcoming ASHRAE/ICC Standard 240P will include a discussion of how water/wastewater contributes to carbon emissions. The GHG emissions analysis includes the following components:

- Annual pre-retrofit GHG emissions
- GHG emissions intensity (lbCO2e/ft2/yr [kgCO2e/m2/yr])
- GHG emissions end-use balance (required for Level 2 assessments)
- Building profiles

Annual pre-retrofit GHG emissions are determined by multiplying the building energy use by the appropriate grid emission factors. GHG emissions calculation methodology is covered in ASHRAE/IES Standard 100, ASHRAE Standard 105, ASHRAE Standard 228, and the proposed ASHRAE/ICC Standard 240P and ASHRAE Standard 242P. Emission factors can be obtained from additional sources, summarized in Table 3.3. Emissions calculated on an annual basis only require annual energy use values. When required, or when hourly electricity use and emission factors are available, the emissions can be calculated on an hourly basis. GHG emissions intensity is calculated by dividing the annual pre-retrofit GHG emissions by the building floor area. GHG emissions end-use balance (required for Level 2 decarbonization assessments) complements the existing energy end-use balance. The estimated emissions for each end use is calculated by multiplying the estimated energy for each end use by the corresponding GHG emission factors used to determine annual pre-retrofit GHG emissions.

Table 3.3 Grid Emission Factor Databases

**[Figure: U.S. EPA eGRID Database]**

Type: diagram

Description: The eGRID database includes annual historical GHG emission factors at the national, subregional, and utility-scale levels.

Key Elements:

- NREL Cambium Database -> The National Renewable Energy Laboratory's Cambium database provides modeled, forward-looking hourly emissions data for electricity generation across multiple grid scenarios.
- UNFCCC Harmonized Grid Emission Factor Data Set -> The United Nations Framework Convention on Climate Change database lists grid emission factors outside of the United States divided by country/territory/island. The International Financial Institutions Technical Working Group on Greenhouse Gas Accounting (IFI TWG) periodically updates this data set.
- Other International Emission Factors -> Electricity Maps is an open-source tool showing carbon intensity (gCO2eq/kWh) of electricity consumed throughout the world (Electricity Maps n.d.). The Gridwatch Web app includes live grid emissions for Ontario, Canada (Gridwatch n.d.). The Canadian government publishes Canadian emission factors by Province/Territory (Government of Canada n.d.).

GHG emissions end-use balance (required for Level 2 decarbonization assessments) complements the existing energy end-use balance. The estimated emissions for each end use is calculated by multiplying the estimated energy for each end use by the corresponding GHG emission factors used to determine annual pre-retrofit GHG emissions. Figure 3.3 provides an example of end-use breakdown by energy use and emissions for comparison. Compared to a typical energy audit (which would prioritize heating, cooling, lights, and fans), the end-use balance assessment by GHG emissions indicates that efficient heating and DHW have the potential to achieve the most GHG reduction. Energy and emission profiles are additional elements of a utility analysis that may be used to better understand building operation, time-of-use electrical rate impacts, hourly emissions interactions, and existing electrical service requirements. These profiles may not be available for a building at the start of the decarbonization planning process, and building owners should consider collecting additional data as soon as possible to better inform future decisions. These data can be collected through utility data, submetering, and building automation system trends. Building Energy-Use Profiles. These are whole-building profiles and can be useful for understanding performance and potential strategies for shifting when married with a grid emission profile. They are also useful for understanding peak energy demand periods. Annual heat maps are a particularly useful representation of this type of profile, as shown in Figure 3.4. This type of heat map indicates time of day, day of year, and illustrates seasonal trends.

**[Figure: Example end-use breakdown by energy (inner circle) and GHG emissions (outer circle)]**

Type: chart

Description: This chart compares the end-use breakdown of energy and GHG emissions in a building. The key insight is that heating accounts for the largest share of both energy and GHG emissions.

Data Representation:

* Heating: 40%
* Cooling: 20%
* Lighting: 15%
* Fans: 10%
* Pumps: 5%
* Plug Loads: 5%
* Elevators: 2%
* Hot Water: 2%
* Heat Rejection: 1%

Metric: Energy and GHG emissions

Chart Type: Donut

Units: Percentage

Chart Generation Hint:

* X-axis: Energy
* Y-axis: GHG emissions

Structured Data (Machine Readable):

{
  "chart_type": "donut",
  "metric": "energy and GHG emissions",
  "units": "percentage",
  "data": {
    "Heating": 40,
    "Cooling": 20,
    "Lighting": 15,
    "Fans": 10,
    "Pumps": 5,
    "Plug Loads": 5,
    "Elevators": 2,
    "Hot Water": 2,
    "Heat Rejection": 1
  }}
}

**[Figure: Example electricity demand annual heat map]**

Type: heat map

Description: This heat map illustrates the yearly profile of electricity demand, with the x-axis representing the day of the year and the y-axis representing the hour of the day. The color scale on the right indicates the level of electricity demand, ranging from -20 kW (blue) to 50 kW (red). The heat map shows that electricity demand is highest during the summer months (June to August) and lowest during the winter months (December to February). The demand also peaks during the morning and evening hours, with a slight dip in the middle of the day.

Key Elements:

*   X-axis: Day of the year
*   Y-axis: Hour of the day
*   Color scale: Electricity demand (kW)

Data Representation:

*   Electricity demand: 0-50 kW
*   Metric: Electricity demand
*   Chart Type: Heat map
*   Units: kW

Chart Generation Hint:

*   X-axis: Day of the year
*   Y-axis: Hour of the day

Structured Data (Machine Readable):

```json
{
  "chart_type": "heat_map",
  "metric": "electricity_demand",
  "units": "kW",
  "data": {
    "day_of_year": [1, 2, ..., 365],
    "hour_of_day": [0, 1, ..., 23],
    "electricity_demand": [0, 1, ..., 50]
  }}
}

**[Figure: Average hourly building demand vs. grid emission factors]**

Type: chart

Description: This line chart compares the average hourly building demand with grid emission factors, specifically focusing on net building demand (with PV), marginal carbon, and high carbon and cost hours. The key insight is that there is a significant variation in these factors throughout the day, with peak hours showing the highest demand and carbon emissions.

Data Representation:

*   Net building demand (with PV): 0-22
*   Marginal carbon: 0-22
*   High carbon and cost hours: 0-22
*   Metric: Hourly demand and emission rates
*   Chart Type: Line chart
*   Units: Hours

Chart Generation Hint:

*   X-axis: Hour
*   Y-axis: Demand and emission rates

Structured Data (Machine Readable):

```json
{
  "chart_type": "line",
  "metric": "hourly demand and emission rates",
  "units": "hours",
  "data": {
    "Net building demand (with PV)": [0, 22],
    "Marginal carbon": [0, 22],
    "High carbon and cost hours": [0, 22]
  }}
}

Building Load Profiles. This profile indicates end-use specific building energy loads (e.g., cooling load, heating load, DHW load, IT load, etc.) and is useful for sizing equipment and understanding opportunities for heat recovery. See Section 3.3.1.2 for additional details on using building load profiles.

Grid Emission Profiles. The emission profile of grid power generation is separate from building energy use. Such data may be obtained from an hourly modeled database, such as the NREL Cambium database, or from historical or projected utility-reported data. This type of profile informs how you might approach designing for lower carbon emissions by minimizing grid-supplied energy during peak grid emissions. Refer to Figure 3.5 for an example where the grid emission profile is marked as “marginal carbon.”

Building Emission Profiles. This type of profile combines the energy profile and the grid emission profile. It can be either building wide or end-use specific. Generally, the data are aggregated into annual values for the annual pre-retrofit GHG emissions or the end-use breakdowns, as described in the following section.

Any of the above profile types can also be combined on a single chart to provide further insights. For example, Figure 3.5 shows an example of the overlay of a nominal office building (with on-site PV) energy-use profile with the grid emission profile (marked as “marginal carbon”).

The combination of energy-use profile and grid emission profile informs the selection of efficiency reduction measures compared to simply seeking energy efficiency measures. Periods when peak energy use coincides with peak grid emissions are the first targets for decarbonization. In the example building for Figure 3.8, the PV system reduces the energy load profile during mid-day hours, when the marginal emissions are lower. Further efficiencies during this mid-day period will have much less impact to the building’s GHG emissions than addressing the peak areas, such as the morning warm-up period. In this example, one approach may be to incorporate thermal energy storage together with other measures for HVAC electrification to capture and store heat generated during the period of low GHG emissions (assisted by the on-site PV) for use during the morning warm-up period.

See ASHRAE’s Grid-Interactive Buildings for Decarbonization: Design and Operation Resource Guide for more details on choosing technologies that can maximize emissions savings through strategic load planning or shifting (ASHRAE 2023h). 3.3.1.2 Heating and Cooling

Grid-Interactive Buildings for Decarbonization: Design and Operation Resource Guide

This guide for building operators, designers, owners, consultants, and other building stakeholders includes techniques and practices to enable buildings to maximize the benefits from the grid while minimizing the carbon impacts of the grid and building (ASHRAE 2023h). This guide builds on ASHRAE’s existing Smart Grid Application Guide by providing specific design and operational parameters for building projects that allow the audience to maximize carbon reduction in their interaction with the grid. This guide has decarbonization as the primary goal and provides guidance on controls as they shift toward more real-time, automated interaction with the grid.

**[Figure: Grid-Interactive Buildings for Decarbonization]**

Type: diagram

Description: The figure presents a comprehensive overview of the design and operation resource guide for grid-interactive buildings, focusing on decarbonization. It features a cityscape with power lines and transmission towers, symbolizing the integration of buildings with the electrical grid to reduce carbon emissions.

Key Elements:

- **Cityscape**: Represents urban areas where grid-interactive buildings are implemented.
- **Power Lines and Transmission Towers**: Illustrate the connection between buildings and the electrical grid, highlighting the flow of energy.
- **Title and Subtitle**: Clearly indicate the focus on grid-interactive buildings for decarbonization, emphasizing the importance of sustainable practices in building design and operation.

This diagram serves as a visual introduction to the resource guide, emphasizing the critical role of grid-interactive buildings in reducing carbon footprint and promoting sustainable urban development.

Load Profile Analysis

Heating and cooling load profile analysis is a key aspect of decarbonization projects and one that is not typically part of a standard energy audit. This type of analysis can identify HVAC or DHW systems that are oversized, presenting an opportunity to downsize, or rightsize, during the retrofit project. Opportunities to rightsize for heating load, in particular, can be critical when electrifying HVAC systems because, for many climates, the heating load will drive the heat pump capacity and sizing. Reducing heat pump capacity and size can be crucial when working within existing building constraints such as electrical capacity, structural capacity, and space. Additional details on rightsizing analysis are provided in Section 3.4.1. Identifying periods of simultaneous heating and cooling, or thermal overlap, is another important aspect of load profile analysis. Where energy efficiency projects have traditionally focused on eliminating periods of thermal overlap, these periods represent prime opportunities for energy recovery within the building. Figure 3.6 illustrates the annual hourly heating and cooling loads for a building in red and blue, respectively, and then periods of simultaneous heating and cooling in yellow. In this figure, the building has weekday thermal overlap all year round, indicating a great potential for energy recovery using systems such as heat recovery chillers to simultaneously cool and heat, or water-source heat pump networks to recover and circulate heat between spaces. Heating and cooling load data are not always readily available for existing buildings. Additional temporary or permanent sub-metering may be required for breaking down energy use into heating and cooling loads. It is important to identify early in the process the information available, confirm that appropriate trend logs are set up, and identify additional metering needs to capture information not currently available. Ideally, a full heating season’s worth of data should be collected for heating systems. For DHW systems, a minimum of one month of data, but preferable three months, should be collected. Simplified analyses can often capture key aspects of the building’s operation without submetering. For example, for buildings with gas heating and electric cooling, the basic gas and electricity use profiles can provide insights into periods of thermal overlap. 3.3.1.3 Identify Emissions Reduction Measures (ERMs)

**[Figure: Building Heating and Cooling Loads with Thermal Overlap]**

Type: diagram

Description: This diagram illustrates the heating and cooling loads of a building over time, highlighting the thermal overlap between the two. The x-axis represents time, while the y-axis represents the load in units of energy.

Key Elements:

* Heating Load -> The red line represents the heating load, which increases as the temperature drops.
* Cooling Load -> The blue line represents the cooling load, which increases as the temperature rises.
* Thermal Overlap -> The yellow area represents the thermal overlap, where both heating and cooling loads are present.

This diagram provides a visual representation of the building's energy needs, allowing for better understanding and optimization of its heating and cooling systems.

PNNL Energy Charting and Metrics (ECAM) Tool

The Energy Charting and Metrics (ECAM) Tool is an add-on for Microsoft Excel® developed by the Pacific Northwest National Laboratory (PNNL) to facilitate the analysis of building and system energy data. ECAM can be used to create various load profiles or scatter charts as well as normalizing data and creating metrics based on consumption or equipment (PNNL n.d.). ECAM can also create schedules and day-type information to time series data and filter data from months, years, days, day-type, day of week, day of month, occupancy, or temperature-binned weather data.

Decarbonization assessments also differ from typical energy audits in terms of recommended capital energy efficiency measures (EEMs) because they also include emissions reduction measures (ERMs). An ERM is an action taken in the operation of equipment in the building or energy supply to the building that reduces the greenhouse gas (GHG) emissions of the building without negative impact within the building. ERMs might include, but are not limited to:

- Improvements to the building’s operational performance and energy use to reduce thermal loads, resulting in the downsizing of the HVAC equipment and reduction in demand and carbon emissions.
- Retrofitting or replacing existing equipment that uses fossil fuels with technologies that can use decarbonized energy, typically electricity.
- Use of on-site renewable energy. While on-site renewable energy resource opportunities are introduced for Level 2 energy audits according to ANSI/ASHRAE/ACCA Standard 211, they should be investigated at all levels, and considerations should also include electric vehicle (EV) charging infrastructure and future parking space ventilation design.

More in-depth discussion on EEMs and ERMs is included in Section 3.4.

#### 3.3.1.4 Evaluate Electrical Infrastructure Upgrades

As part of the decarbonization assessment, electrical system integrity and capacity should be documented. An electrical system may require upgrades to add electric heating loads, or partial electrification may be considered if upgrades are not possible or too costly. Using a battery or other type of energy storage system to store power during low usage and dispatch power during high usage might avoid or limit the need for electrical infrastructure upgrades. To properly evaluate fuel switching and other ERMs, it is necessary to document the electrical system’s existing conditions during the assessment. Additional discussion on electrical system capacity implications can be found in Section 3.5.2 of this guide and in Decarbonizing Building Thermal Systems: A Guide for Heat Pump Systems and Beyond (Houssainy et al. 2024).

Decarbonizing Building Thermal Systems: A Guide for Heat Pump Systems and Beyond

This guide for design engineers and building operators focuses on how heat pumps should be applied and how they should be operated in commercial and multifamily buildings to support decarbonization (Houssainy et al. 2024). It provides guidance to design engineers on various heat-pump-specific design elements, including application and sizing in different climate zones, system configuration and refrigerants, electrical requirements, and control and operation strategies for space and hot-water applications. The guide includes an in-depth discussion about steps for evaluating electrical capacity for the implementation of electrification technologies.

### Table: Data Table

| npa ea l n f oe p r eo a so yt w n ao vh i gn ar ta e oi nL |  |
|---|---|
| Decarbonizing Building Thermal Systems: A How-to Guide for Heat Pump Systems and Beyond | In conjunction with Design and Construction Allies |
|  |  |

i

CASE STUDY: San Diego State University, California

The case study for San Diego State University (SDSU) presents a partial electrification design for a central heating plant serving three campus buildings. The partial electrification allowed SDSU to implement an electrification solution while avoiding costly electrical service upgrades required for full electrification of the central plant. For more details on this case study, see the appendix.

#### 3.3.1.5 Perform Temperature Stress Test

When ERMs include switching central heating sources for heating hot-water loops, such as from natural-gas-fired boilers to heat pumps, another critical evaluation involves assessing the heating hot-water system supply and return temperatures and their compatibility with proposed equipment or systems. The evaluation of these distribution temperatures should include a building/ system stress test, where existing supply temperatures are adjusted to simulate those of a planned ERM to determine whether the system will still satisfy building loads operating with these new temperatures. See Decarbonizing Building Thermal Systems: A Guide for Heat Pump Systems and Beyond for the methodology of a building stress test (Houssainy et al. 2024). 3.3.1.6 Carbon Savings Calculations and Life-Cycle Emissions

Similar to the addition of GHG emissions metrics to the pre-retrofit energy analysis, all EEMs and ERMs should include GHG emissions impacts. Operational GHG emissions reductions and, when possible, incremental embodied emissions associated with the retrofit should be calculated and included in a life-cycle carbon assessment.

Operational carbon savings estimates for EEMs or ERMs should be determined by converting estimated energy savings to carbon savings using the methodology described in Section 3.3.1.1. In addition to operational carbon savings, the embodied carbon impact of the EEMs and ERMs should be considered to minimize their life-cycle emissions. Note that the embodied carbon of the original building construction is not relevant to the decision-making process for EEMs or ERMS; the embodied carbon of the original building construction can be considered zero for purposes of a decarbonization assessment. Only incremental embodied carbon from the new equipment and disposal of old equipment should be considered when calculating the lifecycle emissions of a given EEM or ERM. ASHRAE’s forthcoming Whole-Life Carbon Guide for Building Systems includes additional guidance on life-cycle carbon assessments, calculating embodied emissions, and balancing operational carbon impacts of EEMs and ERMs with embodied carbon impacts. 3.3.1.6.1 Refrigerant Considerations

Whole-Life Carbon Guide for Building Systems

This guide provides design engineers strategies to minimize the whole-life carbon emissions from building mechanical, electrical, and plumbing (MEP) systems (ASHRAE Forthcoming). MEP systems are major contributors to the operational energy consumption and whole-life carbon emissions of buildings. Recent studies have shown that the embodied emissions from MEP systems can be between 15% and 49% of the total building embodied emissions and even higher if photovoltaic (PV) systems are included on the building. To minimize the whole-life carbon emissions of MEP systems, trade-offs between the embodied carbon and the operational carbon emissions—and among MEP, architectural, and structural systems emissions—should be considered. This guide provides ASHRAE members and others with the definitions, concepts, and comprehensive guidance needed to calculate, interpret, and integrate life-cycle data from multiple sources to design MEP systems for low whole-life carbon emissions.

Whole-Life Carbon Guide for Building Systems

GHG emissions associated with refrigerant leakage should be included in the life-cycle emissions calculations for measures. Refrigerants used in HVAC systems have a significant impact on the environment. Some refrigerants, such as hydrofluorocarbons (HFCs), have high global warming potential (GWP) values, meaning that they have a greater potential to contribute to global warming compared to carbon dioxide. In recent years, efforts have been made to phase out the use of high-GWP refrigerants and replace them with lower-GWP alternatives, such as hydrofluoroolefins (HFOs), or natural refrigerants, such as ammonia or carbon dioxide. When considering building decarbonization, it is important to estimate the refrigerant leakage GHG emissions and to select HVAC systems that use low-GWP refrigerants or other options that minimize refrigerant use. For example, when considering a building retrofit for which both air-air heat pumps and a VRF system

EPA Fact Sheet: Transitioning to Low-GWP Alternatives in Residential and Commercial Air Conditioning

This fact sheet provides current information on low global warming potential (GWP) alternative refrigerants to highGWP hydrofluorocarbons (HFCs) for use in residential and commercial air conditioning (AC) equipment, including chillers (EPA 2016). HFCs are powerful greenhouse gases (GHGs) with GWPs hundreds to thousands of times more potent per pound than carbon dioxide (CO2); however, more low-GWP alternatives are becoming available.

TRANSITIONING TO LOW-GWP ALTERNATIVES in Residential and Commercial Air Conditioning and Chillers

Background

This fact sheet provides current information on low global warming potential (GWP)1 alternative refrigerants to high-GWP hydrofluorocarbons (HFCs) for use in residential and commercial air conditioning (AC) equipment, including chillers. HFCs are powerful greenhouse gases (GHGs) with GWPs hundreds to thousands of times more potent per pound than carbon dioxide (CO2); however, more MPX(81 alternatives are becoming available.

HFC refrigerant emissions from AC applications are released to the atmosphere throughout the lifecycle of equipment—i.e., during equipment manufacture, installation, operation, maintenance, and at end-of-life.

Figure 1. Global HFC Emissions in 2020 by Sector

AC

MVAC

28%

13%

Globally, approximately 80% of HFCs are emitted in the refrigeration, AC, and motor vehicle AC (MVAC) sectors, with the remainder accounted for by the foam-blowing, aerosols, fire suppression, and solvents sectors. While developed nations have historically accounted for the majority of global HFC emissions, total HFC emissions in developing nations are projected to quadruple by 2030. This rapidly increasing rate of HFC emissions is largely driven by the increased demand for refrigeration and AC, particularly in the tropical climates of much of the developing world, and the transition away from ozone depleting substances (ODS).

Aerosols, Solvents, Foams, and Fire Ext.

Commercial Ref

26%

21%

Other Ref

12%

Global HFC Emissions: 1,084 MMT CO2 Eq. Global HFC Emissions in AC: 306 MMT CO2 Eq.

Source: Estimates based on U.S. EPA (2013).

AC Equipment

Residential and commercial AC equipment used in households and commercial buildings contain one or more factory-made assemblies that normally include an evaporator or cooling coil(s), compressor(s), and condenser(s). These include small AC systems (self-contained AC and split AC), large AC systems (single split and multi-split, variable refrigerant flow, and ducted and packaged rooftop units), as well as chillers. Descriptions of each of these AC equipment categories are provided below, followed by Table 1, which lists the typical capacity, refrigerant charge, and annual operational leak rate for each equipment type.

# 1 GWP is a measure of a substance’s climate warming impact compared to CO2.

are options, the impact of potential refrigerant leaks and the amount of total refrigerant used in each system should be evaluated as part of the building’s carbon emissions. This can involve retrofitting existing systems, upgrading to more energy-efficient systems, or even redesigning buildings to optimize passive strategies and minimize the use of HVAC systems. There are many resources—including ASHRAE’s Whole-Life Carbon Guide for Building Systems, MEP 2040, the California Air Resources Board, and ANSI/ASHRAE Standard 228—that offer guidance on mitigating refrigerants’ contributions to GHG emissions.

### 3.3.2 Decarbonization Evaluation Tools

Depending on the assessment level, various calculation methods and tools can be utilized. Simple spreadsheet-based calculations are typically used for walk-through survey-level assessments. The BIN method or energy simulation calculations are required for energy survey and analysis or detailed analysis of capital-intensive modification assessments. While there are many tools available, validation needs to be done for energy simulation tool selection in terms of capabilities and credibility. If the assessment is being sponsored by a rebate or incentive program, there may be requirements for the tools used for analysis. Simulation tools such as BEopt™ (residential only), EnergyPlus™, and IESVE are examples of typical tools used to evaluate available measures. Additional tools and resources and their potential uses are described in Table 3.4. ASHRAE’s WholeLife Carbon Guide for Building Systems also references tools available for calculating emissions.

### Table 3.4    Tools Useful for Decarbonization Assessment

| Tool/Resource | Intended Use During Assessment |
|---|---|
| DOE GHG Emissions Reduction Audit Checklist for Owners  (DOE 2023b) | Define scope of audit and deliverables for a building-level GHG emissions reduction audit. |
| DOE Asset Score/Audit Template (DOE n.d.-a) | Create a standard building energy audit report. Could also be used for submission to select jurisdictions to comply with local ordinances. |
| GHG Protocol Emission Inventory Calculation Tools (WRI n.d.) | Develop comprehensive and reliable inventory of GHG emissions. |
| Embodied Carbon Construction Calculator (CLF 2023c) | Benchmark and assess embodied carbon reductions, focused on upfront supply chain emissions of construction materials. |
| Electrification Impact Calculator (ORNL n.d.) | Estimate potential cost and CO emissions savings resulting from changing 2 from fuel-based equipment to electrical equipment. |
| EnergyPlus™ (NREL 2023c) | Model energy and water consumption in buildings and identify EEMs/ ERMs and their potential impacts. |
| URBANopt™ (NREL 2023e) | Investigate energy trade-offs between building locations and geometry, building and district energy storage strategies and locations, aggregated grid services, and district energy system performance characteristics. |
| Energy Charting and Metrics Tool (PNNL n.d.) | Create charts from building energy data to analyze energy use profiles. Filter data from months, years, days, day-type, day of week, day of month, occupancy, temperature binned weather data, and pre/post comparisons. |
| REopt® (NREL 2023d) | Evaluate the optimal mix of renewable energy, conventional generation, and energy storage technologies to meet cost savings, resilience, emissions reductions, and energy performance goals for buildings, campuses, and communities. |
| DER-CAM (LBNL 2023) | Determine the optimal distributed energy resource (DER) investments in the context of either buildings or multi-energy microgrids. |
| Refrigerant Impact Calculator (MEP2040 n.d.) | Calculate potential refrigerant impact for HVAC systems based on selected data sets for refrigerants and leakage rates. |

### 3.3.3 Assessing Building Portfolios

For owners with building portfolios, a few additional factors should be considered when conducting decarbonization assessments. The depth of evaluation depends on factors such as the number of buildings in a portfolio, the diversity of building types, and accessibility of building data. It can be time-consuming and costly to conduct detailed analyses of an existing building’s energy performance at the system level for a large portfolio of buildings. Prior to beginning any assessments, the assessor should work with the building owner to agree upon timing and depth of evaluation to stay within the schedule and budget while also gathering information at a detailed enough level to identify opportunities for improvement and the magnitude of potential impact. 3.3.3.1 Depth of Analysis and Selecting Representative Buildings

Numerous factors contribute to the depth of analysis for building portfolios. While some building portfolios are limited in building type (i.e., an apartment complex), other portfolios may contain a diverse set of buildings (i.e., a college campus). For portfolios with similar building types, one building can be evaluated and used as a representative model for the other buildings in the same category. Complex portfolios that include diverse buildings, such as varied building sizes that were built in different eras and serve unique purposes, may require a group of representative buildings for further study. To select representative buildings, portfolios can be grouped by characteristics. The strategy used to categorize buildings into groups can be programmatic, geographic, based on system type, financial, performance-based, or some combination of these. Table 3.5, from the U.S. Department of Energy’s Framework for Greenhouse Gas Emissions Reduction Planning: Building Portfolios (2023c), lists common building characteristics for grouping building portfolios. Once a portfolio has been categorized into groups of buildings, representative buildings can be selected for further study to help quantify carbon reduction impacts for each category and to project potential impacts across the entire portfolio. In addition to time and budget, considerations such as physical access and the availability of building or system performance data, safety, seasonality, and occupancy play into which representative buildings are good candidates for the assessment. 3.3.3.2 Timing of Assessment

Framework for Greenhouse Gas Emissions Reduction Planning: Building Portfolios

The Department of Energy’s Framework for Greenhouse Gas Emissions Reduction Planning: Building Portfolios provides guidance for reducing Scope 1 and Scope 2 GHG emissions for building portfolios and vehicle fleets (DOE 2023c). The framework includes a five-step process for developing an actionable plan for building owners and organizations, from establishing the building inventory to finalizing implementation scenarios, funding, phasing, etc.

Framework for Greenhouse Gas Emissions Reduction Planning: Building Portfolios

The timing of building assessments may depend on factors such as seasonality, occupancy profiles, building access limitations, availability of system performance data, and funding or incentive program timelines. Depending on the targeted level of assessment, testing and measuring certain building system equipment may only be possible during specific times of the year. Access to buildings or certain areas may be limited due to high security requirements or safety hazards. For projects pursuing external funding through incentive programs, costs associated with building assessments may be covered (or recovered), though reimbursement may only be applicable for certain scopes of work or for a set time period. Therefore, advance planning and communication are important when determining the timing and sequencing for assessment of a building portfolio.

### Table 3.5    Common Building Characteristics Used in Portfolio Categorization

| Characteristic | Guidance for Selection of Characteristic |
|---|---|
| GHG emissions intensity (lb CO e/ft2) 2 | Benchmark GHG intensity (GHGI) between similar building types that are different sizes by normalizing across square footage. This information is used to determine which buildings within the same building type have the highest GHG intensity. |
| Total GHG emissions (tons CO e) 2 | Rank buildings by total GHG emissions. This information is used to identify buildings that are the largest contributors to the portfolio’s emissions. |
| Site energy use intensity (kBtu/ ft2) | This is used to benchmark energy use at the building so buildings of various sizes can be compared. |
| Total energy use (kBtu) | Identify buildings that are the largest contributors to the portfolio’s energy use. |
| Planned renovations/equipment end-of-life | Ensure planned investments are designed to be low to no carbon. |
| Building type | Group similar building types to apply similar strategies. |
| On-site fossil fuel combustion (% energy use or  kBtu/ft2) | Identify buildings where on-site fossil fuel combustion is a significant contributor to the building’s total emissions. |
| HVAC system type | A high-level categorization (e.g., district vs. distributed, hydronic vs. air, fuel type) should be used when there is a range of system types requiring decarbonization strategies. |
| Climate zone | Different technical approaches may apply based on climate zone (e.g., cold climate heat pumps and envelope measures). Select representative buildings in the range of climate zones in which the portfolio is located. |
| Ownership structure | Ownership/management/lease structures may result in differences in utility payment responsibility, so categorizing by ownership structure can be useful. |
| Disadvantaged communities | Determine if buildings are located within disadvantaged communities and consider these buildings for investment. |
| Energy prices | Prioritize buildings with the highest energy prices. |
| Regulatory drivers | Prioritize locations with building performance standards, benchmarking and decarbonization ordinances, strong building codes, and potential financial penalties or taxes. |
| Utility grid carbon intensity | Prioritize overall GHG emissions reduction efforts in regions with high grid carbon intensity and prioritize electrification in regions with lower grid carbon intensity. |
| Utility incentives and funding opportunities | Prioritize locations with utility programs and grants that support electrification and building efficiency improvements. |
| Source: Lawrence Berkeley National Laboratory (DOE 2023c) 2 2 Note: CO e/ft is carbon dioxide equivalent per square foot; kBtu/ft is thousands of British thermal units per squar e 2 foot. |  |

**[Figure: Framework for Building Decarbonization Assessment]**

Type: diagram

Description: This diagram presents a step-by-step framework for assessing and improving the energy efficiency of buildings, with a focus on decarbonization. The framework consists of nine steps, each represented by a numbered box, and is accompanied by a flowchart that illustrates the relationships between the different steps.

Key Elements:

*   **Step 1: Foundational Data** -> Collect and analyze data on the building's energy usage and performance.
*   **Step 2: Building Upgrades** -> Identify opportunities for energy-efficient upgrades and retrofits.
*   **Step 3: Maximize Energy Efficiency** -> Implement energy-saving measures such as lighting and HVAC system upgrades.
*   **Step 4: Electrify Space Conditioning and Water Heating Systems** -> Transition to electric space conditioning and water heating systems.
*   **Step 5: Optimize Building Automation Systems and Grid Interactivity** -> Implement advanced building automation systems and optimize grid interactivity.
*   **Step 6: Assess Distributed Generation and Clean Power Production** -> Evaluate the potential for on-site renewable energy generation.
*   **Step 7: Integrate Grid Interactivity and/or Microgrids** -> Integrate the building with the grid and/or microgrids to optimize energy usage.
*   **Step 8: Utilize Energy Storage** -> Implement energy storage solutions to reduce peak demand and improve energy efficiency.
*   **Step 9: Evaluate Financial Considerations** -> Assess the financial implications of the proposed energy efficiency measures.

This framework provides a comprehensive approach to building decarbonization, from data collection and analysis to implementation and evaluation. By following these steps, building owners and managers can reduce their energy consumption, lower their carbon footprint, and improve the overall sustainability of their buildings.

## 3.4 Prioritize/Determine Decarbonization Measures

The decarbonization assessment will identify EEMs and ERMs that are feasible within the constraints of the existing building and will identify high-priority measures such as replacing equipment that is already toward the end of EUL. Measures identified as feasible by the assessment should be evaluated and grouped for optimization. The best combination of measures should be based on the framework illustrated in Figure 3.7. The following subsections introduce and prioritize different EEMs and ERMs and point to detailed sections later in this guide.

### Table 3.6    Building Systems Discussed in This Guide

| Building System | Chapter/Section |
|---|---|
| Building Lighting Systems | Section 5.1.1 |
| Building Appliances and Plug Loads | Sections 5.1.2–5.1.3 |
| Building Envelope | Section 5.2.1 |
| HVAC Energy Efficiency and Optimization | Section 5.2.3 |
| HVAC Energy Recovery and Ventilation | Sections 5.2.3.3–5.2.3.4 |
| HVAC Systems | Section 6.1 |
| Building HVAC Control Sequences | Section 6.2 |
| Renewable Systems | Section 7.1 |
| Battery Energy Storage Systems | Section 7.2 |
| EV Charging | Section 7.3 |
| Grid-Interactive Systems | Section 7.4 |
| Thermal Energy Storage Systems | Section 7.5 |
| Domestic Hot-Water Systems | Chapter 8 |

### 3.4.1 Reducing Heating and Cooling Loads and Rightsizing Equipment

### Table: Data Table

| Building System | Chapter/Section |
|---|---|
| Building Envelope | Section 5.2.1 |

Reducing Building Loads

Reducing building loads can result in increased resilience and comfort, decreased first costs of replacing heating and cooling equipment, as well as long-term energy and emissions benefits. While envelope upgrades are often overlooked in commercial energy audits due to their longer paybacks, decarbonization assessments should give significant consideration to envelope upgrades.

As decarbonization efforts aim to electrify building systems, minimizing loads becomes even more important, as electric heating equipment typically costs more than equivalent capacity gas heating equipment, and there are also potential electrical and structural upgrade costs that are directly tied to equipment sizing (Chapter 5 further discusses capacity considerations and solutions for electrical and structural systems). Particularly for heating hot-water systems, air-to-water heat pumps are currently many times the cost of equivalent capacity condensing boilers. For these reasons, strategies that reduce loads and the associated peak equipment capacity are made significantly more cost effective in decarbonization retrofits compared to typical energy efficiency retrofits. For more information on load-reduction strategies, see Chapter 5.

Rightsizing

Oversized equipment can result in higher first costs, embodied carbon, energy consumption, operating costs, and potential operational challenges and emissions, while undersized equipment may struggle to meet the building’s load, resulting in reduced comfort levels. Most engineers err on the side of oversizing equipment to avoid the risk of comfort complaints, but on decarbonization retrofit projects, this conservatism comes at a potentially significant cost as well as posing the serious risk of operational challenges, equipment longevity issues, and comfort complaints resulting from the system’s inability to properly turndown to serve low load conditions, leading to frequent compressor cycling. Thermal energy storage is a great solution for these operational challenges with heat pumps, which is detailed in Section 7.5 in Chapter 7.

Load duration curves can be particularly useful for rightsizing equipment and assessing the potential for keeping existing heating sources to handle a portion of the heating needs or providing a hybrid fuel solution. It is often not feasible to fully electrify building heating or domestic hot-water systems due to infrastructure, heat pump technology, or financial constraints, but it is also often the case in decarbonization retrofits that the existing heating system has additional life and could be used to handle some of the annual heating needs.

**[Figure: Framework for building decarbonization assessment]**

Type: diagram

Description: This diagram illustrates a framework for assessing building decarbonization, outlining the steps and considerations involved in evaluating and reducing carbon emissions from buildings.

Key Elements:

- **Assessment Steps**: The diagram outlines a series of steps for conducting a decarbonization assessment, including data collection, analysis, and strategy development.
- **Considerations**: It highlights various factors to consider during the assessment process, such as energy efficiency measures, renewable energy sources, and carbon offsetting options.
- **Decision Points**: The diagram includes decision points where users can evaluate different scenarios and choose the most appropriate path forward.

This framework provides a structured approach to building decarbonization, helping users navigate the complex process of reducing carbon emissions from buildings.

**[Figure: Sample building annual heat load profile. Serving Peak Loads]**

Type: chart

Description: This chart compares the annual thermal consumption of a building with the cumulative annual percent consumption, highlighting the peak loads served by the system.

Data Representation:

- Annual Therms: 4,500
- Metric: Cumulative Annual Percent Consumption
- Chart Type: Line
- Units: Percent

Chart Generation Hint:

- X-axis: Percent of Design Load
- Y-axis: Cumulative Annual Percent Consumption

Structured Data (Machine Readable):

{ "chart_type": "line", "metric": "Cumulative Annual Percent Consumption", "units": "Percent", "data": { "Annual Therms": 4500 }} }

This chart provides valuable insights into the building's thermal consumption patterns, allowing for optimized system design and operation to meet peak demands efficiently.

In Figures 3.8 and 3.9, the orange curve represents the percentage of annual heating energy consumption at a given percentage of design load or less. In this example, 80% of the annual heating energy consumption occurs when the percentage of design load is 25% or less. Figure 3.9 shows a series of four air-to-water heat pump modules that would be required to meet the original design peak load. This load analysis shows that the actual peak is 40% lower than the original design but also that most of the heating consumption happens at much lower loads. Performing this analysis eliminates the cost of at least two modules and highlights the potential for eliminating a third module and handling the peak load with the existing natural gas boiler plant. The increase in operating GHG emissions of using the existing gas boiler plant should be weighed against the embodied carbon and cost of the additional heat pump to cover the remaining 20% of heating energy consumption. Rightsizing can also include evaluating whether using future climate condition models is appropriate for the given decarbonization retrofit.

Using Future Climate Conditions During Load Estimation

The use of weather files based on historical weather patterns may not accurately reflect future climate conditions affecting heating and cooling loads. A collaboration between Argonne, Oak Ridge, and Sandia National Laboratories is investigating the impacts of this issue and producing a data set of future weather files (fTMY) to use in load calculations and the development of building codes and standards (DOE 2023n).

Future and Extreme Weather Data

Argonne, Oak Ridge & Sandia National Laboratories Dr. Ralph T. Muehleisen (Argonne) rmuehleisen@anl.gov WBS 3.5.5.63

Source: IPCC Special Report, 2012 Managing the Risks of Extreme Events and Disasters to Advance Climate Change Adaptation: Cambridge University Press.

### 3.4.2 Maximize Building Systems Efficiency

### Table: Data Table

| Building System | Chapter/Section |
|---|---|
| Building Lighting Systems | Section 5.1.1 |
| Building Appliances and Plug Loads | Sections 5.1.2–5.1.3 |
| HVAC Energy Efficiency and Optimization | Section 5.2.3 |
| HVAC Energy Recovery and Ventilation | Sections 5.2.3.3–5.2.3.4 |
| Building HVAC Control Sequences | Section 6.2 |

Maximizing efficiency continues to be a priority when renovating to decarbonize. Many of the traditional energy efficiency upgrades found in an energy audit can be justified by cost savings alone and are typically worth making before HVAC or DHW system decarbonization. Energy efficiency projects can also reduce the electrical loads from lighting, plug loads, or other equipment, which may help avoid the need for electrical service upgrades when electrifying space heating and water heating equipment. Efficiency alterations can be carried out as individual projects or combined to optimize impact, minimize disruption to occupants, etc. Systems can be prioritized based on their energy consumption and emissions intensity or based on other factors identified during the planning process, such as remaining equipment life or financial incentives. The timeline for decarbonizing the local electrical grid is another consideration. Analysis can show whether there is an advantage to implementing efficiency measures earlier than fuel switching to maximize carbon reduction as electrical generation becomes cleaner.

**[Figure: Decision tree: Determining when to electrify equipment]**

Type: flow diagram

Description: This flow diagram outlines the decision-making process for determining when to electrify equipment. It guides users through a series of questions and considerations to help them decide whether to upgrade their equipment to electric or continue using fossil fuels.

Process Steps:

1. **Follow Capital Plan Upgrade Schedule** -> Determine if the upgrade is part of the capital plan schedule.
2. **Upgrade in the current Capital Plan?** -> Check if the upgrade is already included in the current capital plan.
3. **Will retrofit meet loads (e.g., HHW temps)?** -> Assess if the retrofit will meet the required loads.
4. **Pursue electric, heating and cooling load reduction** -> Consider pursuing electric, heating, and cooling load reduction.
5. **Can the building accommodate new electric equipment?** -> Evaluate if the building can accommodate new electric equipment.
6. **Available electrical capacity** -> Check if there is available electrical capacity.
7. **Available structural capacity** -> Assess if there is available structural capacity.
8. **Available space (indoor, rooftop or outdoor)** -> Determine if there is available space for the upgrade.
9. **Dual fuel or hybrid solution** -> Consider a dual fuel or hybrid solution.
10. **Upgrade Electrical and/or Structural Capacity** -> Upgrade the electrical and/or structural capacity if necessary.
11. **Add to Capital Plan for future retrofit trigger** -> Add the upgrade to the capital plan for future retrofit trigger.

Flow Logic:

* If the upgrade is not part of the capital plan schedule, proceed to step 2.
* If the upgrade is already included in the current capital plan, proceed to step 3.
* If the retrofit will meet the required loads, proceed to step 4.
* If the building can accommodate new electric equipment, proceed to step 5.
* If there is available electrical capacity, proceed to step 6.
* If there is available structural capacity, proceed to step 7.
* If there is available space for the upgrade, proceed to step 8.
* If a dual fuel or hybrid solution is considered, proceed to step 9.
* If the electrical and/or structural capacity needs to be upgraded, proceed to step 10.
* If the upgrade is added to the capital plan for future retrofit trigger, proceed to step 11.

Key Components:

* **Electric** -> Represents the electric option.
* **Fossil Fuel** -> Represents the fossil fuel option.
* **Upgrade Electrical and/or Structural Capacity** -> Represents the upgrade of electrical and/or structural capacity.

Structured Flow (Machine Readable):

{
  "type": "flow_diagram",
  "steps": [
    "Follow Capital Plan Upgrade Schedule",
    "Upgrade in the current Capital Plan?",
    "Will retrofit meet loads (e.g., HHW temps)?",
    "Pursue electric, heating and cooling load reduction",
    "Can the building accommodate new electric equipment?",
    "Available electrical capacity",
    "Available structural capacity",
    "Available space (indoor, rooftop or outdoor)",
    "Dual fuel or hybrid solution",
    "Upgrade Electrical and/or Structural Capacity",
    "Add to Capital Plan for future retrofit trigger"
  ],
  "flow": [
    [
      "Follow Capital Plan Upgrade Schedule",
      "Upgrade in the current Capital Plan?"
    ],
    [
      "Upgrade in the current Capital Plan?",
      "Will retrofit meet loads (e.g., HHW temps)?"
    ],
    [
      "Will retrofit meet loads (e.g., HHW temps)?",
      "Pursue electric, heating and cooling load reduction"
    ],
    [
      "Pursue electric, heating and cooling load reduction",
      "Can the building accommodate new electric equipment?"
    ],
    [
      "Can the building accommodate new electric equipment?",
      "Available electrical capacity"
    ],
    [
      "Available electrical capacity",
      "Available structural capacity"
    ],
    [
      "Available structural capacity",
      "Available space (indoor, rooftop or outdoor)"
    ],
    [
      "Available space...

**[Figure: Decision Tree for Electrifying Equipment]**

Type: flow diagram

Description: This decision tree guides the process of determining when to electrify equipment, considering various factors and conditions to make an informed decision.

Process Steps:

1. **Start Process** -> Initiate the decision-making process for electrifying equipment.
2. **Energy Source** -> Determine the energy source available for electrification.
3. **Decision** -> Evaluate if the energy source is suitable for electrification.
4. **End Process** -> Conclude the decision-making process based on the evaluation.

Flow Logic:

- **Start Process** -> **Energy Source**
- **Energy Source** -> **Decision**
- **Decision** -> **End Process**

Key Components:

- **Energy Source** -> The energy source available for electrification.
- **Decision** -> The evaluation of the energy source's suitability for electrification.

Structured Flow (Machine Readable):

{
  "type": "flow_diagram",
  "steps": ["Start Process", "Energy Source", "Decision", "End Process"],
  "flow": [["Start Process", "Energy Source"], ["Energy Source", "Decision"], ["Decision", "End Process"]],
  "decisions": [{"condition": "Suitable Energy Source", "yes": "Electrify", "no": "Do Not Electrify"}}]
}

### 3.4.3 Electrify Space Conditioning and Water Heating Systems

### Table: Data Table

| Building System | Chapter/Section |
|---|---|
| HVAC Systems | Section 6.1 |
| Building HVAC Control Sequences | Section 6.2 |
| Domestic Hot-Water Systems | Chapter 8 |

There are several key decision points when considering electrification to decarbonize an existing building. Deciding when to electrify equipment should include analysis of the current and future emission factors for the building’s electricity supply (both grid and on-site sources). Buildings whose electricity has a high carbon intensity may require a phased electrification approach depending on the timeline to decarbonize the supply versus equipment life. As discussed in Section 3.4.1, reducing building loads where possible is an important step in electrifying space conditioning and water heating systems. Implementing efficiency upgrades to reduce electrical loads may also be advantageous to avoid major electrical upgrades. If the load trimming is still not sufficient, an electrical infrastructure upgrade may be the only option to electrify all building systems. Savings from implemented efficiency measures may offset some of the upgrade-related costs.

CASE STUDY: University of California, Santa Cruz— Phasing Approach

The University of California Santa Cruz decided to utilize interim solutions when existing gas boilers were due for replacement. When a building had insufficient electrical capacity to support immediate installation of an air-source heat pump system, a condensing boiler was chosen for replacement to lower direct emissions in the interim until sufficient electrical capacity or district heating becomes available to fully decarbonize the heating system. See UCSC Case Study in the appendix for additional details.

If electrical infrastructure is not a constraint, it is recommended to target equipment that is damaged, has capacity or operational issues, or is near or at the end of its EUL for electrification. 5 and 6 provide more detailed discussions of electrification technologies and options for building loads and HVAC systems. Chapter 8 discusses options for water heating systems. For equipment that is operating well and still has years before expected burnout, the timeline to reach emissions reduction goals should be consulted. If emissions goals cannot be met on time without fuel switching, it may be required to replace equipment prior to EUL. If goals can be met with the fossil fuel equipment operating until the end of its EUL, that may be the best option as long as the equipment is monitored for operational and efficiency issues. In this case, evaluate the embodied carbon for replacement as discussed in Section 3.4.7. Leaving the equipment in place while investing in other measures may make the most sense financially and for emissions goals. Alternatively, there may be opportunities to electrify with primary heat pumps and leave fossil fuel equipment in place and extend effective useful life as backup or supplemental capacity while still experiencing drastic emissions reductions during normal operations. Even though first cost is paramount in capital upgrades, decarbonization goals may encourage pursuing electrification strategies even when associated costs may be high and payback periods longer. This may become more common as jurisdictions adopt building performance standards that require building upgrades to meet performance levels or incur financial penalties. When this is the case, an analysis may be required to determine the significance of end-use categories for cooking, domestic hot water, and HVAC loads. Looking at which end use is contributing most to emissions may help the building owner prioritize system replacements to meet goals. There are several modeling tools that can be leveraged for these studies; consult those listed in Section 3.3.2. Should the analysis indicate that systems need to be replaced and there are no ideal technology solutions for the specific existing building conditions, hybrid electrification could be a feasible option.

#### 3.4.3.1 Dual-Fuel Technologies

Dual-fuel heat pump technologies utilize electricity and an additional fuel source, such as a heat pump RTU, which has both an air-source heat pump and an auxiliary gas furnace. The system uses the heat pump or the gas furnace depending on various factors that can be programed into the sequence of operation; e.g., efficiency, emissions, cost, and capacity. In addition to efficiency benefits, life expectancy of these systems can potentially be higher than for traditional heat pumps given their lower compressor run times. Dual-fuel heat pumps may be optimal for climates that experience four seasons and varying temperatures and could also be a good solution to cut emissions when there is existing fossil fuel equipment with remaining EUL. More on heat pump space conditioning can be found in Chapter 6.

#### 3.4.3.2 Stranded Asset Considerations

Building owners must consider the financial impact of stranded assets—a problem unique to existing building renovations—if equipment is replaced before the end of its EUL. Lloyd’s of London defines stranded assets as “assets that have suffered from unanticipated or premature writedowns, devaluation or conversion to liabilities. In recent years, the issue of stranded assets caused by environmental factors, such as climate change and society’s attitudes towards it, has become increasingly high profile” (2017, p. 4). As a result of climate action plans and carbon emissions reduction goals for existing buildings, stranded assets within the built environment may become more common. Buildings and systems are evaluated using typical accounting methods, and a variety of accounting tools exist for these analyses. “To determine whether an asset is ‘stranded,’ accountants conduct impairment tests. An impairment test is a common accounting procedure used to determine potential asset devaluations” (Corporate Finance Institute 2023). Within the context of existing building decarbonization, specifically electrification, stranded assets may take the form of whole buildings or of specific building systems and equipment. In certain situations, adopting phased or hybrid electrification strategies could serve as viable alternatives to prevent assets from becoming obsolete, especially if replacing the equipment entirely would significantly affect the financial standing of the building owner. The evaluation for an optimal combination of measures for decarbonizing a building should take into account possible stranded assets in the form of equipment that produces emissions directly (e.g., steam boiler) or indirectly (e.g., steam distribution system). It is financially preferable to replace equipment that is at its end of EUL; however, published carbon reduction or carbon neutral goals may require replacing fossil fuel systems with electric alternatives before their EUL. For smaller systems, including gas-fired furnaces and small boilers, the financial impact is likely small. However, for owners who have made large investments in either installing and/or maintaining a district steam system or have a combined heat and power plant, the impact of eventually abandoning such systems might be felt immediately. In cases with large systems or equipment that will be replaced, these may still be retained to provide redundancy to all electrical options in extreme weather events or when primary equipment fails. However, with a large steam system, for example, the ramp-up and -down periods can be significant if the system is used as a backup.

CASE STUDY: University of California, Santa Cruz—Cogeneration Plant

A key part of the University of California Santa Cruz decarbonization plan included what to do with their Fackler cogeneration plant, which generates more than half of the campus’s GHG emissions. The cogeneration plant is financed with a long-term loan that has more than 20 years remaining. UCSC evaluated multiple scenarios that explored emissions and financial impacts of either retiring the cogeneration plant early or operating it until full repayment of the loan. See the UCSC cogeneration plant case study in the appendix for more details.

### 3.4.4 Grid Interactivity

**[Figure: Grid-Interactive Buildings for Decarbonization: Design and Operation Resource Guide]**

Type: diagram

Description: This figure presents a comprehensive guide for building operators, designers, owners, consultants, and other stakeholders to enable buildings to maximize the benefits from the grid while minimizing the carbon impacts of the grid and building (ASHRAE 2023d). The guide builds on ASHRAE's existing Smart Grid Application Guide by providing specific design and operational parameters for building projects that allow the audience to maximize carbon reduction in their interaction with the grid.

Key Elements:

- **Cover Image**: A visual representation of a cityscape with a prominent power line tower, symbolizing the integration of buildings with the electrical grid.
- **Title**: Clearly states the purpose of the guide, emphasizing decarbonization through grid interaction.
- **Subtitle**: Provides additional context, highlighting the focus on design and operation resource guidance.
- **ASHRAE Logo**: Indicates the guide is published by the American Society of Heating, Refrigerating, and Air-Conditioning Engineers, lending credibility and authority to the content.

### Table: Data Table

| Building System | Chapter/Section |
|---|---|
| Building HVAC Control Sequences | Section 6.2 |
| Battery Energy Storage Systems | Section 7.2 |
| EV Charging | Section 7.3 |
| Grid-Interactive Systems | Section 7.4 |
| Thermal Energy Storage Systems | Section 7.5 |

### Table: Data Table

| Building System | Chapter/Section |
|---|---|
| Renewable Systems | Section 7.1 |

The proliferation of distributed power generation will continue as jurisdictions adopt building energy codes that require the use of on-site and off-site clean power production. Policy and financial incentives continue to grow, making distributed generation more and more attractive. Resilience efforts are spurring interest in microgrids and other regional solutions for reliable power supply. In some instances, such as for existing campus buildings, microgrid projects may be included in the list of ERMs. Chapter 7 goes into depth on distributed generation systems and technologies. Additionally, many utilities are making efforts to clean up their electricity grids to provide clean power to customers. Understanding the local grid emission factor and the timeline for local clean power should be a consideration when evaluating ERMs and planning the timing of their implementation. As utilities incorporate more variable renewable generation and buildings incorporate more behind-the-meter generation assets, buildings are changing from being perceived as distributed loads to distributed energy resources.

### 3.4.6 Energy Storage

### Table: Data Table

| Building System | Chapter/Section |
|---|---|
| Battery Energy Storage Systems | Section 7.2 |
| Thermal Energy Storage Systems | Section 7.5 |

The use of energy storage technologies such as batteries and thermal storage are important components to building decarbonization as the share of renewable energy in the grid continues to grow. In addition to enabling downsizing of heat pump capacity as discussed in Chapter 7, the increasing importance of these energy storage technologies is due to several reasons. They capture excess clean energy produced during low emissions periods and then use this energy during periods when grid emissions are higher. Second, they provide resilience to changing conditions in the energy market. Third, they can add stability to the rapidly changing grid supply/load balance due to the “duck curve” attributed to changes in PV generation. Buildings that start the decarbonization process today must be able to integrate with future energy storage systems and technologies. Because of this, measures considered for the decarbonization plan should both account for the building’s current setting and position it to be responsive to future circumstances. An example of changing settings is the global energy market. The cost and availability of energy are likely to change over time as the market shifts toward renewables and away from fossil fuels. Changing time-ofuse rates and demand pricing structures play a role in future operating costs. Building owners and managers should consider the potential impacts of these changes on building energy consumption and plan accordingly. Changes in energy markets may affect the financial feasibility of decarbonization strategies.

Tools and Guidance for Estimating Utility Rates

Energy savings performance contracts (ESPCs) have long been a key projectfinancing mechanism for building energy retrofits. These contracts may extend for decades and must establish utility rates to forecast future project savings as part of measure evaluations. The National Institute of Standards and Technology (NIST) provides an energy escalation rate calculator for estimating future energy rates.

- NIST Energy Escalation Rate Calculator The Federal ESPC program offers guidance on establishing future utility rates, including with the use of the NIST calculator.
- Guidance on Utility Rate Estimations and Weather Normalization in Performance Contracts
- Recommended vs. Actual Escalation Rates for ESPCs: Is the Guidance Good?

Resilience in the Face of Climate Events

Buildings that are decarbonized today must be resilient to current and future climate change impacts. This may involve upgrading building systems and installing energy storage to withstand extreme weather events such as floods, hurricanes, high winds, heat waves, or other climate-related hazards. Buildings in particular play a key role in resilience initiatives and policy. Keeping buildings habitable through extreme heat or freeze events and through heavy precipitation and extreme wind or smoke can limit displacement and provide community shelter when required. In addition to providing shelter, commercial building operation directly affects local economies by enabling businesses to stay open or reopen quickly after climate events. Many decarbonization retrofits, such as weatherization improvements, structural enhancements, window replacements, and HVAC system upgrades, provide opportunities to improve an existing building’s resilience.

U.S. Climate Resilience Toolkit

The U.S. Climate Resilience Toolkit includes a five-step framework to document climate hazards and produce solutions to reduce climate-related risks (U.S. Climate Resilience Toolkit n.d.). More than 50 case studies are offered showing how resilience is being addressed throughout the U.S. and territories. The compilation of digital tools ranging from templates to interactive analyses can help individuals and communities understand and manage their climate-related risks and opportunities.

### 3.4.7 Embodied Carbon

CIBSE TM65 for North America

The Chartered Institution of Building Services Engineers (CIBSE) developed and published Embodied Carbon in Building Services: A Calculation Methodology (TM65) in 2021. TM65 outlines the need for assessing the embodied carbon of mechanical, electrical, and plumbing (MEP) systems and offers guidance on how to estimate the embodied carbon of MEP products when environmental product declarations (EPDs) are not available. TM65 provides valuable information for the MEP community and beyond; however, many of the method’s assumptions are specific to the United Kingdom. This addendum addresses North America (CIBSE 2024).

Embodied carbon in building services: a calculation methodology for North America

R

U

T

C

S

N

T

I

O

O

C

N

I

N

T

U

C

S

U

E

D

O

E

F

R

I

P

L

F

O

D

N

E

TM65NA: 2024

- Package 1: Lighting upgrades, HVAC upgrades, GSHP
- Package 2: Envelope improvements, lighting upgrades, HVAC upgrades, ASHP

Though such changes are hard to predict, it is important to consider the potential for changes in the energy market and to ensure that building systems and equipment are adaptable and can operate efficiently with a variety of energy sources. Including on-site energy storage is one way to manage risk against changing markets. Chapter 7 includes more details on energy storage solutions.

Whole-Life Carbon Guide for Building Systems encompasses both the embodied and operational carbon emissions associated with a building (ASHRAE Forthcoming). The process of maintaining and refurbishing existing buildings, in and of itself, constitutes an emissions reduction measure when accounting for embodied carbon. Embodied carbon can be much higher for new construction than for existing building refurbishment because some of the highest embodied emissions are associated with the building’s structural elements, including foundation and framing. Steel typically has high embodied carbon, so replacing HVAC and water heating equipment and distribution systems does have an impact. However, upgrading to more efficient equipment that uses clean electricity will result in lower operational carbon. Therefore, it is useful to consider both embodied and operational carbon impacts when determining whether to replace equipment prior to the end of its EUL. Sections 1.1.2, 3.3.1, and 3.2.3 in this guide offer guidance and tools for limiting embodied carbon during renovation; ASHRAE’s forthcoming Whole-Life Carbon Guide for Building Systems also offers guidance. 3.4.8 Select the Best Combination of Measures

After gathering data on possible decarbonization measures and laying out their relevant considerations individually during the decarbonization assessment, the project team can evaluate multiple scenarios consisting of different combinations of measures to help select the best combination. The criteria for determining the best combination of measures for a decarbonization project will vary. During the scenario evaluation, the project team should evaluate the expected emissions reduction, system life evaluations (repair/replace/refurbish), cost of carbon, future changes in energy markets, occupant considerations, implementation time and cost (including available funding and payback period), and how each scenario fits into the facility’s short- and long-term goals. Table 3.7, adapted from the California State University Decarbonization Framework (CSU 2023b), outlines criteria for evaluating measures based on broad criteria groups. The various measures considered for the project should be grouped and compared for the highest priority criteria. For example, Figure 3.11 illustrates two packages of ERMs compared for their GHG emissions reductions. As noted in the figure, these packages include:

### Table 3.7    Example Decarbonization Strategy Evaluation Criteria (Adapted with Permission from CSU’s Decarbonization Framework [CSU 2023c])

| Criteria Group | Criteria | Overview |
|---|---|---|
| Environmental | Operational Carbon—Energy Use | Energy use of systems and end uses from both on-site and purchased energy sources. For leased buildings, this represents both common area and tenant energy use emissions depending upon lease structure. |
|  | Operational Carbon—Water Use | Water use of systems, particularly those that affect energy use for DHW systems. |
|  | Embodied Carbon | Embodied carbon of materials, including products, building construction, system maintenance and repair, and system decommissioning and disposal. |
| Capital Expenditures (CAPEX) | Direct Measure Costs | First costs for design, procurement, and installation of measures |
|  | Indirect Measure Costs | Costs required to make a building ready for measure implementation, including: Structural repair or reinforcement Electrical capacity upgrades Environmental assessments for specific measures (such as ground-source loops) Remediation of hazards |
|  | Planned CAPEX | Whether measures represent expenditures already included in the organization’s Capital Plan, such as: Equipment replacements for end of life Tenant turnover upgrades |
|  | Unplanned CAPEX | Whether measures represent expenditures not included in the organization’s Capital Plan |
| Operational Expenditures (OPEX) | Utility costs | Utility costs to operate measures after implementation |
|  | Maintenance Costs | Costs to maintain equipment installed for measures |
|  | Government Policy Compliance | Potential financial penalties associated with non-compliance for building energy performance (e.g., BPS penalties) |
|  | Carbon Pricing | Internal cost of carbon for an organization (this may include cost of compliance with government policies) |
| Occupants | Comfort | Potential impact on thermal comfort within space |
|  | Disruption | Level of disruption/displacement to occupants required to implement measure |
| Infrastructure | Phasing | Phasing potential and impact to operations during construction and ongoing operation and GHG emissions |
|  | Electrical Infrastructure | Potential impact on electrical infrastructure and need for electrical capacity upgrades |
|  | Structural Infrastructure | Potential impact on building structure and need for structural repair or reinforcement |
|  | Space and Location Requirements | Spatial impacts and code considerations of equipment installation (such as on-roof visibility or noise levels) |
| Maintainability | Complexity | Complexity of technology and controls and required training for facilities staff |
|  | Compatibility | Compatibility of proposed measures with other building systems and processes |
|  | Technology Readiness | Availability & maturity of technology and number of manufacturers |
| Resilience | Redundancy and Backup | Levels of redundancy offered by technology |
|  | Resilience | Ability of technology to offer resilience to building |
|  | Climate Adaptation | Ability to adapt to climate change and future weather conditions |

**[Figure: Cumulative Emissions Reduction Measures]**

Type: chart

Description: This chart compares the cumulative emissions reduction measures for two packages of measures, Option 1 and Option 2, across nine different ERMs (Energy-Related Measures). The key insight is that both packages achieve 50% reductions in GHG emissions from baseline, with Package 2 including envelope improvements that will also disrupt the occupants within their spaces compared to Package 1.

Data Representation:

*   Package of Measures Option 1: Lighting and HVAC Upgrades, Geothermal Heat Pump Heating
*   Package of Measures Option 2: Envelope Improvements, Lighting and HVAC Upgrades, Air Source Heat Pump Heating
*   Metric: Cumulative Emissions Reduction Measures
*   Chart Type: Bar chart
*   Units: Percentage (%)

Chart Generation Hint:

*   X-axis: ERMs (Energy-Related Measures)
*   Y-axis: Cumulative Emissions Reduction Measures (%)

Structured Data (Machine Readable):

```json
{
  "chart_type": "bar",
  "metric": "cumulative_emissions_reduction_measures",
  "units": "percentage",
  "data": {
    "Package of Measures Option 1": [100, 90, 80, 70, 60, 50, 40, 30, 20],
    "Package of Measures Option 2": [100, 95, 90, 85, 80, 75, 70, 65, 60]
  }}
}

**[Figure: Example comparison of ERM packages]**

Type: chart

Description: This chart compares the cumulative emissions reduction measures for two different packages of measures, Option 1 and Option 2. The chart shows that both options result in a significant reduction in emissions, with Option 1 achieving a 50% reduction and Option 2 achieving a 50% reduction.

Data Representation:

*   **ERM 1**: 90%
*   **ERM 2**: 80%
*   **ERM 3**: 70%
*   **ERM 4**: 60%
*   **ERM 5**: 50%
*   **ERM 6**: 40%
*   **ERM 7**: 30%
*   **ERM 8**: 20%
*   **ERM 9**: 10%

Metric: Emissions reduction

Chart Type: Bar chart

Units: Percentage

Chart Generation Hint:

*   X-axis: ERM number
*   Y-axis: Emissions reduction percentage

Structured Data (Machine Readable):

```json
{
  "chart_type": "bar",
  "metric": "emissions reduction",
  "units": "percentage",
  "data": {
    "ERM 1": 90,
    "ERM 2": 80,
    "ERM 3": 70,
    "ERM 4": 60,
    "ERM 5": 50,
    "ERM 6": 40,
    "ERM 7": 30,
    "ERM 8": 20,
    "ERM 9": 10
  }}
}
```

This chart provides a clear comparison of the emissions reduction measures for two different packages of measures, allowing for easy identification of the most effective options.

### 3.4.9 Financial Considerations

There are numerous drivers behind the economics of existing building decarbonization measures. The easiest, most common way of justifying a measure is by prioritizing the shortest simple payback (SPB) or best return on investment (ROI), especially if the SPB/ROI falls within the time left on a current lease or, for an owner-occupied building, within the owner’s financial criteria. Bundling measures with a range of SPBs is another way to justify implementing numerous measures, especially those with longer SPBs that can be harder to justify as stand-alone projects. Other variables to consider with the SPB approach include incentives, grants, tax credits, etc., that are

CASE STUDY: 345 Hudson, New York

The case study for 345 Hudson provides a real-world example of determining the best combination of measures for a specific project. The project is located in New York City, where NYC Local Law 97 sets targets for GHG emissions for buildings that must be achieved by certain dates or building owners will face monetary penalties. Local Law 97 was a primary factor in project decisions, beginning with analysis of noncompliance compared to implementing ERMs to comply. After determining to implement a decarbonization project, three alternative packages with different sets of ERMs were evaluated using the NYSERDA Strategic Decarbonization Assessment (SDA) tool. Key drivers/decision points for selection of the measures listed were NPV, GHG emissions reductions, electrification, and conversion to a thermal network.

available to reduce capital costs. If the project qualifies, usually these are estimated and deducted from the first cost, and then the net SPB is calculated. Building owners may also identify a dollar value per ton of carbon based on their organizational goals or operations. As an example, ASHRAE/IES Standard 100-2024’s cost-effectiveness criteria for buildings without performance targets require owners to compute the cost savings using a carbon cost value. Another way of financially prioritizing a list of decarbonization measures is by evaluating them based on the first cost of the measure divided by the estimated carbon emissions savings (lower is better). The most comprehensive method is performing a life-cycle cost analysis (LCCA), which factors in the first cost, discount factor, annual energy costs, and annual maintenance costs over the EUL of the equipment. Calculating the net present values (NPV) of each measure allows one to evaluate the true cost of the measure in present dollars over its entire life. It may make sense to compare measures using both LCCA and whole-life carbon analysis. Some measures that are prioritized based on their decarbonization potential may be more costly to implement, and vice versa. The big picture is to evaluate a package of decarbonization measures that meets the building’s performance targets, aligns with the owner’s financial objectives, and accommodates the timeline priorities established during the planning phase.

#### 3.4.9.1 Funding Sources

Funding sources include owner funding, bank loans, incentives, grants, tax credits, and energy service performance contracts (ESPCs). Even if the owner can self-fund the project, taking advantage of other funding sources can help expand the project’s scope. Examples of funding sources are provided in Table 3.8. Incentives typically are available from utilities and/or municipalities, depending on the energy provider; sometimes there can be incentives from both (e.g., utility incentive plus one offered by the city or county in which the project is being undertaken). Incentives from utilities and/or municipalities typically have a customer and program cap, which further supports researching their availability and, if there is an application process, starting that as soon as possible. Many incentive programs ask for projects to be registered in the planning phase, so researching available incentives early is important. Grants and tax credits usually originate from the state or federal level and involve an application process with requisites tied to the technology being considered. ESPCs, while not a funding source on their own, are a mechanism for funding a project that helps reduce up-front capital for the owner and leverages the energy savings (from the energy efficiency upgrades) to pay off the bank loan over time. With carbon savings becoming a goal of many customers, the ESPC model, traditionally based on energy savings, likely will evolve to carbon savings with a potential guarantee.

### Table 3.8    Funding Source Examples

| Funding Source | Description |
|---|---|
| Government Grants and Subsidies | Financial incentives provided by governments to support decarbonization efforts, such as grants and subsidies for energy-efficient projects and renewable energy installations. |
| Low-Interest Loans and Financing | Financial institutions and green financing entities offering low-interest loans and financing options for decarbonization projects. These loans help cover up-front costs and are repaid over time. |
| Energy Efficiency and Renewable Energy Rebates | Utility- or energy-provider-sponsored rebates and incentives for customers who undertake energy efficiency improvements or invest in renewable energy systems. |
| Power Purchase Agreements (PPAs) | Contracts between a renewable energy facility and a buyer where the buyer purchases electricity from the facility over an extended period, providing funding for the project while offering stable revenue to the buyer. |
| Green Bonds | Financial instruments specifically designed to fund environmentally sustainable projects, including decarbonization measures. Investors purchase green bonds, and the returns finance qualifying projects. |
| Corporate Sustainability Initiatives | Businesses and corporations allocate funds as part of their sustainability efforts to invest in decarbonization projects and support their environmental and social responsibility goals. |
| Public-Private Partnerships (PPPs) | Funding through partnerships between public and private entities, leveraging both public funding and private sector expertise to implement large-scale decarbonization measures. |
| Energy Performance Contracts (EPCs) | Energy service companies (ESCOs) finance and implement energy efficiency measures for a building or facility, with the cost savings used to repay the ESCO over time. |
| Community-Based Funding | Crowdfunding or investment platforms where communities raise funds for smaller-scale decarbonization projects, allowing local residents to invest in and support clean energy initiatives. |
| Tax Credits and Incentives | Financial benefits provided by governments to renewable energy project developers, such as investment tax credits (ITC) and production tax credits (PTC). |

Decarbonization funding sources from banks come in different forms. Because it is privatized funding, there are different requirements to qualify for financing opportunities and loans on a caseby-case basis. Some tools to investigate are listed below:

- Better Buildings Financial Allies. Put together by the U.S. DOE, the Financial Allies are “market-leading financing companies that have committed to funding energy efficiency and renewable energy projects” (DOE 2023f).
- Below Market or Philanthropic Loan Programs. Also from the Better Buildings Initiative at the U.S. DOE, its Loan and Debt Financing page aggregates loan and financing resource options for decarbonization and energy efficiency projects, with specific attention to options for below-market and philanthropic loan programs (DOE 2023g).
- PACE Financing. The U.S. DOE’s Office of State and Community Energy Programs developed a property assessed clean energy (PACE) model specific to commercial properties (C-PACE) that offers options for financing energy efficiency and renewable energy improvements. While developed by the federal government, the program is authorized by state legislation (DOE 2023i).

Energy efficiency and decarbonization incentives are usually in the form of rebates and tax credits. For entities such as non-profit 501c3s, direct payments may be available. These incentives can come from federal, state, and local governments. Therefore, a primary tool for accessing incentives is to assess the resources that are available on the respective federal, state, and local websites. For example, on a federal level, commercial buildings are offered tax deductions up to $1.88/ft2 for implementing qualifying energy and power efficiency measures under tax deduction 179D. This deduction is being updated as part of the Inflation Reduction Act passed in 2022. Additional incentive money is available from the Inflation Reduction Act and is being distributed through the DOE’s various offices through formula grants or funding opportunity announcements. On a state-wide level, the Database of State Incentives for Renewables and Energy Efficiency (DSIRE) gathers state incentives and policies related to renewable and energy efficiency measures and allows searching by building zip code. Additionally, utility providers often have incentives for energy efficiency and renewable energy. The respective websites for applicable Investor-Owned Utilities, Community Choice Aggregators, and Regional Energy Networks house lists of local rebates and incentives that could be applicable to the project. Similarly, the ENERGY STAR Rebate program lists available rebates and special offers for ENERGY STAR certified products by zip code. These products are often used in decarbonization retrofits because they meet stringent energy efficiency specifications set by the U.S. EPA.

## 3.5 Develop a Building Decarbonization Plan

Once the planning framework, assessment, and measure prioritization steps have been conducted, a decarbonization plan should be developed to guide the owner and facility management to reach the building’s decarbonization goals. The plan should use the baseline, goals, scope, timeline, measures, and financing mechanisms from the previous steps to lay out a “playbook” for each building. Where decarbonization efforts include a portfolio of buildings, there should be individual building decarbonization plans and an overall portfolio decarbonization plan. Decarbonization plans should include the following content at a minimum and additional content as relevant to each building’s individual circumstances:

- A summary of EEMs and ERMs with their implementation triggers and timelines
- Alignment with owner capital plans, whether changes to planned projects or wholly new projects
- How EEM and ERM implementation would affect electrical or other infrastructure changes and additional assessments that may be necessary for specific EEMs or ERMs, such as electrical capacity studies
- Projected emissions after EEM and ERM implementation
- GHG emissions (and energy) savings, presented separately for owners and tenants to align with carbon accounting requirements
- Other considerations that might be relevant to owner goals or the specific building

**[Figure: Example of emissions reduction measure timeline and triggers]**

Type: diagram

Description: The figure illustrates a timeline for implementing emissions reduction measures, spanning from 2020 to 2030. It highlights key milestones and triggers for various initiatives aimed at reducing emissions.

Key Elements:

- **Timeline**: A horizontal axis representing the years from 2020 to 2030, divided into sections for each year.
- **Emissions Reduction Measures**: Vertical lines and text boxes indicating specific measures to be implemented at different points in time, such as "Data Strategy - Connect Everything" in 2022 and "Complete Ambient Loop - 100% Electric Building" in 2030.
- **Triggers**: Small red circles on the timeline, marking the initiation of new measures or significant events, like the connection to 555 GW to share energy in 2023.

This diagram provides a clear visual representation of the planned emissions reduction strategy, outlining the timeline for implementing various measures and highlighting key triggers along the way.

### 3.5.1 Measure Summary and Implementation Triggers

Measure implementation phasing—which measures should be implemented together and in what order—is a key part of the decarbonization plan. The decarbonization plan is not a single snapshot in time for the building owner to make immediate upgrades. The decarbonization plan provides a longer-term view for the building owner, identifying measures, or packages of measures, to be implemented along a timeline to achieve current and future goals. Some measures may have discrete times for implementation, while others may depend on precursory events, or triggers. In addition, some measures may require upgrades to other building systems prior to their implementation, and these requirements must be communicated to building owners. Triggers for individual measures may include:

- Failure/required replacement of existing systems
- Tenant turnover within a leased space
- Enactment of government policies/ordinances, such as a building performance standard
- Available rebates or funding sources
- Changes in utility polices enabling new technologies (such as bidirectional EV charging or PV net metering)
- Organizational goals or reporting requirements
- Availability of equipment or specific equipment technologies

The decarbonization plan should lay out the measures to be implemented, together with their triggers, in a streamlined and executable format for the building owner. The measure summary and triggers should also compare the existing capital plan to determine whether a recommendation may just be a change to an already planned expenditure versus a wholly new project that is not currently planned for. This is very helpful for building owners in executing their decarbonization plan because it may be much easier for them to shift funding from one period to another within their capital plan, compared to raising additional funds that are not reflected in their capital plan for the building. Figure 3.12 illustrates an example of a timeline showing measure implementation from the 345 Hudson project case study. The upgrades to the central system were required first to pave the way for future retrofits, and then upgrades to various floors were timed based on tenant turnover and the ability to complete upgrades without disrupting the occupants on those floors.

CASE STUDY: 345 Hudson, New York

# 345 Hudson is implementing a phased approach to decarbonization using tenant turnover as the trigger for a modular retrofit to minimize disruption to occupants. The project includes an ambient loop TES “thermal spine” with each floor’s heating/cooling served by a WSHP. WSHPs and the on-floor heating/ cooling loop will be retrofitted per the tenant schedule.

The measure summary should also include a breakdown of the GHG emissions and energy savings for each measure, each measure package, and as a whole. The GHG emissions and energy savings should be presented separately for owners and tenants to align with carbon accounting requirements that many building owners have. Coordination with the owner for the presentation of this information is a critical aspect of the decarbonization plan. Depending on the building owner’s reporting requirements and lease agreements, they may need GHG emissions and energy savings broken out for individual tenants in addition to the separation between tenants and owners.

### 3.5.2 Impacts to Electrical, Utility, or Other Infrastructure

The decarbonization plan also should identify any additional assessments that may be needed in advance of implementing specific measures and potential upgrades that could be associated with the study results. These may include assessments that are typical in conventional energy efficiency projects, such as assessments and testing for hazards including asbestos and lead. The decarbonization plan should focus on assessments and impacts that may be less familiar to building owners because of the technologies and strategies employed in decarbonization projects. Some of these assessments may include electrical capacity assessments for HVAC electrification, utility interconnect assessments for the installation of microgrids; battery energy storage systems (BESS) and PV systems; roof structural assessments for larger and heavier replacement systems, such as packaged heat pump RTUs; or for when new equipment, such as thermal energy storage tanks, will be installed. The decarbonization plan should do more than simply note that an assessment may be needed for certain measures. The plan should identify information including:

- Type of assessment needed for each measure
- Whether it must take place prior to measure design and/or installation
- Time required to obtain results
- Potential results of that assessment, such as facility upgrades
- Estimated time required to complete upgrades
- Alternative options or contingencies if upgrades cannot be completed

An illustrative example may be electrical upgrades associated with a heat pump measure:

A recommended heat pump measure identifies that an electrical capacity assessment was not completed during the decarbonization assessment and will be necessary prior to measure implementation. The plan explicitly states that if the existing electrical capacity is not sufficient to operate the heat pumps at their rated output, the existing electrical service will need to be upgraded with the local electric utility. The cost for service upgrades may range from $5,000 to $10,000 for panel upgrades or from $10,000 to $30,000 if further service upgrades are required. Electrical service upgrades will require multiple site visits and municipal inspections, and time to completion may range from a few weeks to several months. These costs and timeline should be factored in as lead times for implementing the measure and estimating timing of GHG emissions reductions. If the electrical capacity assessment reveals upgrades that are cost (or schedule) prohibitive, an alternative may be to assess whether high-efficiency window inserts can sufficiently lower heating loads to avoid an electrical service upgrade.

CASE STUDY: The Heritage, New York

The Heritage buildings in New York City determined electrical needs and planned ahead when upgrading their building envelope. Prefabricated modular panels were part of the envelope upgrade and included insulation and improved windows, along with the electrical infrastructure for PTHP retrofits to accommodate upgrades to the existing electrical system. See the appendix for more details of the Heritage case study.

The decarbonization plan should indicate the order of implementation for assessments and associated upgrades and whether they prohibit the installation of measures. Some measures may be designed, and installation begun, while completing assessments so they are ready for operation once the right infrastructure is in place. An example of this may be:

A recommended bidirectional EV charging system measure includes identifying whether the local utility’s interconnection agreement permits EVs to provide power back to the grid. The decarbonization assessment already has performed an electrical capacity study, and the building has sufficient capacity to operate an EV charging system. The decarbonization plan identifies this needed review of the local utility interconnection agreement and explicitly states that, depending on the results, the bidirectional EV charging capability may not be usable without a new agreement. The plan identifies the stakeholders for negotiating a new interconnection agreement and expected timeline to achieving one. However, while the EV charging system can be designed and installed for bidirectional charging, it can be used simply for EV charging during the period while a new utility interconnection agreement is negotiated.

### 3.5.3 Achieving Projected Emissions After Measure Implementation

The decarbonization plan should move beyond simply identifying assumptions made during the analysis to determine the projected GHG emissions for recommended measures. Where applicable, these assumptions should be translated into actions the building owner must take to achieve the projected GHG emissions reductions from the project. These include:

- Installation of supporting upgrades or systems to the recommended measure
- Timing of measure implementation
- Occupant behaviors
- Operating procedures/methods
- Maintenance procedures (activities, timing, frequency)
- Which metrics to be checked by facility staff and when

The audience for this portion of the decarbonization plan includes the facility manager and facility staff. The information should be presented in clear and concise language that can be effectively followed to achieve, and maintain, the performance of the installed measures. Training of facility staff will be important to success; therefore, the plan must include both orientation and ongoing training.

### 3.5.4 Other Considerations

Other considerations that are important to the building owner or based on specific property circumstances should also be addressed in the decarbonization plan. Examples include capabilities of facility managers, behavior of building occupants, and waste management procedures. Additional considerations specific to existing building renovations are discussed in Chapter 4. Maintenance Capabilities. Maintenance capabilities refer to the ability of the building's maintenance staff or third-party contractors to perform routine maintenance, repairs, and upgrades on the building’s infrastructure components. An assessment of the maintenance capabilities should include a review of the maintenance staff’s qualifications, tools, and equipment as well as the availability of spare parts and replacement components. This evaluation can help identify any gaps in the building’s maintenance capabilities and may highlight opportunities for training or outsourcing maintenance tasks. If gaps are identified, solutions should be included in the decarbonization plan to provide the building’s maintenance staff with the resources they need. The plan also should outline a routine for system operations review to reinforce changes, share results, and facilitate discussions on progress. Building Occupant Behavior. Building occupants play a critical role in the success of decarbonization efforts. It is important to consider ways to encourage sustainable behaviors and to provide education and resources to building occupants to support decarbonization efforts. Occupant behaviors that are required in order to meet targets should be clearly spelled out in the plan. Staff involved in communicating with occupants, such as leasing agents or building managers, should be made aware of the requirements and procedures to empower them to act. Waste Management. As the economy strives to become more circular, the life cycle of building materials and products must be considered, especially if embodied carbon is part of the building’s decarbonization scope. For example, selecting sustainable and recyclable materials in building construction and renovation as well as having waste management procedures in place influence the building’s carbon footprint. Actionable procedures for reusing, recycling, or otherwise recovering equipment and materials during construction should be included in the plan.

Architecture 2030’s Carbon Avoided: Retrofit Estimator (CARE) Tool

Reusing, recycling, and recovering equipment and other building materials can significantly reduce the carbon impact of building renovations. These concepts should be considered and included in the building’s decarbonization plan. Architecture 2030’s CARE Tool can be used to compare variables of embodied and operating carbon over different timelines for reuse versus replacement.

### 3.5.5 Portfolio Decarbonization Planning

When decarbonizing building portfolios, the sequencing of buildings must be considered in addition to the sequencing of measures. For example, depending on the level of retrofit, it may be beneficial to renovate one building at a time (in the case of a deep energy retrofit), or it may be better to implement a measure, such as a lighting system upgrade, in multiple buildings at once. Multiple factors, such as building location, cost to mobilize contractors, and owner goals and timeline will play into desired sequencing and require pre-planning.

#### 3.5.5.1 Building Prioritization Techniques

Prioritization may be driven by the goals and targets set by the stakeholders, available funding, sources of funding, planned renovations, or some combination of these. When multiple buildings are involved, several scenarios should be developed to evaluate phasing options against these prioritization criteria. Scenarios are developed by applying the EEMs/ERMs identified using the representative buildings, as described in Section 3.3.3, to the entire portfolio. According to U.S. DOE’s Framework for Greenhouse Gas Emissions Reduction Planning: Building Portfolios,

**[Figure: Framework for Greenhouse Gas Emissions Reduction Planning: Building Portfolios]**

Type: diagram

Description: The figure presents a framework for greenhouse gas emissions reduction planning in building portfolios. It includes a guide on developing and evaluating implementation scenarios for building portfolios, as well as reviews on how to apply ERM packages to multiple buildings and create short-, medium-, and long-term implementation plans to inform building manager decision-making.

Key Elements:

*   **Title**: Framework for Greenhouse Gas Emissions Reduction Planning: Building Portfolios
*   **Subtitle**: Building Portfolios
*   **Image**: A photo of a city skyline with tall buildings and a blue sky with clouds.
*   **Logo**: Better Climate Challenge, U.S. Department of Energy
*   **Text**: The Department of Energy's Framework for Greenhouse Gas Emissions Reduction Planning: Building Portfolios guide includes additional guidance on developing and evaluating implementation scenarios for building portfolios (DOE 2023c). The framework reviews how to apply ERM packages to multiple buildings and create short-, medium-, and long-term implementation plans to inform building manager decision-making.

The results of the building-level assessments should be extrapolated during this phase to estimate impacts across the portfolio. While specific plans and designs may not be created for each individual building during this milestone, the strategies identified during the representative audits can set the general approach to be applied within building categories. The expected savings (energy consumption, GHG emissions, and operating costs) from the building level measure packages can be used to project savings at buildings within the same category (DOE 2023c, p.29).

Energy and emissions reduction estimates for each representative building can be applied to the other similar buildings within the same category as the representative building to estimate portfolio-wide results. Stakeholders should then come together to evaluate the results of the various scenarios against the prioritization criteria. Figure 3.13 illustrates how the scenario results may be compared to the criteria of emissions reduction targets. 3.5.5.2 Individual Plans for Each Building Within the Portfolio

**[Figure: Building Efficiency Targeting Tool for Energy Retrofits (BETTER)]**

Type: diagram

Description: The Building Efficiency Targeting Tool for Energy Retrofits (BETTER) is a software toolkit developed by the U.S. Department of Energy to help building operators quickly and easily identify the most cost-saving energy efficiency measures in buildings and portfolios using readily available building and energy data.

Key Elements:

- **Logo**: The logo features a stylized building with a map pin, symbolizing the tool's focus on building efficiency and location-based data.
- **Tagline**: The tagline "Building Efficiency Targeting Tool for Energy Retrofits" clearly communicates the tool's purpose and scope.
- **Department of Energy**: The inclusion of the U.S. Department of Energy logo indicates the tool's origin and credibility.

This diagram effectively conveys the main idea of the BETTER tool and its benefits for building operators, making it a useful visual aid for understanding the tool's purpose and functionality.

After having evaluated multiple scenarios for building and project phasing, the owner must determine which individual buildings within the selected groups should be prioritized and create individual decarbonization plans. Factors such as previously planned renovations or maintenance activities, equipment-life time frames, financial performance and payback of EEMs/ERMs, and other factors that may differ building by building will need to be defined.

**[Figure: Comparison of portfolio renovation scenarios against emissions reduction targets]**

Type: chart

Description: This line chart compares four different scenarios for reducing greenhouse gas emissions from buildings in the United States. The chart shows the projected emissions levels for each scenario from 2020 to 2040, with the goal of achieving a 50% reduction in emissions by 2030 and an 80% reduction by 2040.

Data Representation:

* Scenario 1: Deep Efficiency, Deep Electrification
* Scenario 2: Deep Efficiency, Moderate Electrification
* Scenario 3: Moderate Efficiency, Deep Electrification
* Scenario 4: Moderate Efficiency, Moderate Electrification

Metric: Greenhouse gas emissions (thousand MTCO2e)

Chart Type: Line chart

Units: Thousand MTCO2e

Chart Generation Hint:

* X-axis: Year (2020-2040)
* Y-axis: Greenhouse gas emissions (thousand MTCO2e)

Structured Data (Machine Readable):

{
  "chart_type": "line",
  "metric": "greenhouse gas emissions",
  "units": "thousand MTCO2e",
  "data": {
    "Scenario 1": [140, 120, 100, 80, 60, 40, 20],
    "Scenario 2": [130, 110, 90, 70, 50, 30, 10],
    "Scenario 3": [120, 100, 80, 60, 40, 20, 0],
    "Scenario 4": [110, 90, 70, 50, 30, 10, 0]
  }}
}

This chart provides a visual representation of the different scenarios for reducing greenhouse gas emissions from buildings in the United States. It shows that all four scenarios are projected to meet the 50% reduction target by 2030, but only Scenario 1 is projected to meet the 80% reduction target by 2040. The chart also highlights the importance of deep efficiency and electrification in achieving significant emissions reductions.

Creating a customized decision matrix, also known as a prioritization matrix or weighted scoring model, can be a powerful decision-making tool to visualize and compare different options based on the factors identified as important to the owner. These matrices also can be used to communicate decision-making criteria for each individual building to building managers or project teams as a supplement to the broader implementation plan that is applicable to all buildings within the portfolio. Figure 3.14 includes an example matrix showing the benefits, impacts, and implementation schedule for each EEM/ERM for an individual building.

#### 3.5.5.3 Campus and District System Considerations

Building portfolios using campus or district systems must consider the system schedule, isolation capabilities, and distribution network integrity when planning decarbonization projects. Campus and district system considerations include:

- When upgrading or installing distribution piping, plan for future decarbonization—for example, by installing LTHW loops that can be served by heat pumps as opposed to installing/repairing/extending steam distribution.

- Design new systems with LTHW coils and high CHW temperature differential coils to improve pumping efficiency.

- Include local grid emissions when deciding whether to install or continue to operate combined heat and power (CHP) systems. Running a CHP may provide lower carbon emissions than electrified heating (until the supply grid is a green source).

- Consider that centralized heating and cooling plants provide opportunities for advanced control and heat recovery (e.g., heat recovery chillers) that may be more difficult to implement for distributed plants. Heat recovery can be distributed to individual buildings, which may reduce piping and pumping costs.

**[Figure: Benefits]**

Type: table

Data:

| Building System | System Component | GHG Savings | Comfort | Health/IAQ | Energy Cost Savings |
| --- | --- | --- | --- | --- | --- |
| envelope | Roof Insulation | low | low | $$ | $$ |
| envelope | Windows/Doors | high | medium | $$ | $$ |
| envelope | Air Sealing & Weatherization | high | medium | $$ | $$ |
| envelope | Exterior Wall Insulation | high | medium | $$ | $$ |
| HVAC | Heating System Upgrades | medium | medium | $$ | $$ |
| HVAC | Electrify Heating | high | high | $$ | $$ |
| HVAC | Pipe Insulation | medium | low | $$ | $$ |
| HVAC | Ventilation Upgrades | medium | high | $/$ | $$ |
| domestic hot water | Electrify Hot Water Heating | low | high | $$ | $$ |
| domestic hot water | Plumbing Fixture Upgrades | low | low | $$ | $$ |
| lighting | Common Area & Exterior Upgrades | low | medium | $$ | $$ |
| lighting | In-Unit Upgrades | low | medium | $$ | $$ |
| plug loads | Appliance Upgrades | low | low | $$ | $$ |
| plug loads | Electrify Cooking | medium | high | $$ | $$ |
| renewables | Electrify Laundry | low | medium | $$ | $$ |
| renewables | Solar PV | low | low | $$ | $$ |

Notes: This table presents the benefits of various building systems and their components in terms of GHG savings, comfort, health/IAQ, and energy cost savings. The table provides a comprehensive overview of the advantages of different building systems and their components, allowing for informed decision-making in building design and operation.

**[Figure: Example benefits & impacts matrix for prioritization and implementation planning]**

Type: table

Data:

| COSTS | LIFESPAN (YRS) | MAINTENANCE | TENANT DISRUPTION | when to implement | MID-CYCLE | FUTURE REFI |
| --- | --- | --- | --- | --- | --- | --- |
| $$$$ | 20 | medium | low | as needed | | |
| $$$$ | 20 | medium | high | as needed | | |
| $$$$ | 15 | medium | low | | | |
| $$$$ | 20 | low | medium | if feasible | | |
| $$$$ | 10–20 | medium | low | per HPD guidelines | | |
| $$$$ | 15 | medium | high | per HPD guidelines | | |
| $$$$ | 15 | low | low | | | |
| $$$$ | 15 | medium/high (ERV) | high | per HPD guidelines | | |
| $$$$ | 10 | medium | low | per HPD guidelines | | |
| $$$$ | 10 | low | low | | | |
| $$$$ | 15–20 | low | low | | | |
| $$$$ | 15–20 | low | medium | | | |
| $$$$ | 15 | low | medium | as needed | | |
| $$$$ | 10 | low | high | per HPD guidelines | | |
| $$$$ | 10 | medium | low | as needed | | |
| $$$$ | 20–25 | low | low | per HPD SWF | | |

Notes: This table represents a benefits and impacts matrix for prioritization and implementation planning. It provides a comprehensive overview of the costs, lifespan, maintenance requirements, tenant disruption, and implementation timing for various energy-efficient measures. The table also includes columns for mid-cycle and future refinancing, allowing users to plan for long-term financial implications. By analyzing this matrix, stakeholders can make informed decisions about which measures to prioritize based on their specific needs and goals.

## 3.6 Implement the Building Decarbonization Plan

Compared to new construction, existing buildings require additional planning and consideration in implementing decarbonization measures, particularly when they house occupants. Before starting any retrofit projects, it is essential to develop a detailed plan that outlines the scope of work, timeline, and potential impacts on building operations. The plan should also include a contingency plan in case of unexpected issues or delays. General sequencing and timelines for each measure may be included in the decarbonization plan, but occupancy conditions may change if the decarbonization timeline spans years, so a detailed schedule should be developed at the start of any measure implementation project to minimize disruption. The schedule must detail proper sequencing of implementation tasks and any critical operating conditions. The following strategies should be considered when drafting the detailed project schedule to keep the building functioning with minimal disruption:

- Implement Phased Retrofits. Phased retrofits can help minimize disruptions to building operations by dividing the retrofit process into smaller, more manageable stages. Phased retrofits also account for seasonal loads within a building; time retrofits while systems are not in use. This approach allows building systems to be upgraded in a sequence that minimizes disruption to occupants and avoids interfering with critical building operations.
- Provide Temporary Systems. Temporary systems, such as heating and cooling units, can be installed to maintain comfort levels in the building during retrofit work. These systems can be powered by clean energy sources, such as electric power, batteries, or renewable energy, so they do not increase carbon emissions compared to the systems being replaced.
- Monitor Building Systems. During the retrofit process, it is important to closely monitor building systems to ensure they are functioning properly. For example, where a heat pump system replaced a gas-fired boiler with higher supply temperatures, monitoring system performance early at the new operating temperatures is important to identify any potential problems. Building automation systems and energy management systems can help monitor and control building systems remotely, minimizing the need for manual adjustments.
- Communicate with Building Occupants During Construction. Communication is key to ensuring building occupants are aware of the retrofit process and any potential disruptions. Provide regular updates on the progress of the project and inform occupants of any changes to building operations or access. Occupants should be made aware of any changes to building evacuation or fire/life-safety procedures, and proper signage should be posted in the building.
- Plan for Site Logistics. Logistics such as parking permits, security access, temporary shutdowns, partial area closures, sound ordinances or construction noise levels, construction site safety, accessibility accommodations, etc., all can cause issues if not properly coordinated and planned into the construction schedule. Logistics planning should follow these basic steps:
- Survey building owners/tenants to identify critical operations and planned operating schedules.
- Coordinate with each owner/tenant for construction schedules that minimize disruption.
- Develop a plan with each owner/tenant for mitigating hazards and operational impacts (area safety closures, dust/noise barriers, etc.).
- Communicate the schedule well in advance with frequent reminders leading up to the work.
- Develop procedures for keeping the construction site clean, orderly, and secure.
- Notify owners and occupants when work is complete and they can resume normal operations.

### 3.6.1 Implementation for Building Portfolios

Planning the implementation sequence and schedule is more complex on a portfolio level and requires additional consideration compared to planning for individual buildings. The implementation sequence can affect both the cost of the project and the reductions in energy use and carbon emissions. Construction teams can select multiple subcontractors to implement decarbonization measures based on pricing, estimated manpower and schedule, and areas of specialty. Subcontractor teams’ mobilization and demobilization on measures is an important factor and needs to be planned for and adjusted on an ongoing basis. For single-system retrofits such as lighting upgrades, implementation is typically prioritized by measures first and buildings second; this ensures efficient use of subcontractor time. When it comes to deep retrofits, each building takes priority, as each building can take months to complete.

## 3.7 Track and Report Performance

Performance measurements should be designed to satisfy GHG emissions reporting requirements and allow flexibility for meeting future requirements. The metrics used to evaluate decarbonization retrofit projects will look similar to conventional energy efficiency projects, especially for given systems. Supply and return temperatures, operating status, and other parameters are important in monitoring the performance of individual systems. However, the primary goal for decarbonization retrofits is reduction of GHG emissions for the building or portfolio. Project monitoring for achieving GHG emissions reductions takes a different lens, which includes: GHG Emissions (Not Just Energy Cost). Whole building, and system level, energy use should be collected and compiled with marginal emission rates (where available) or grid emission factors to determine the GHG emissions for the building and compared against the targets. Where hybrid systems and solutions are used, the emissions from on-site boilers or other fossil fuel combustion systems are aggregated with emissions from purchased electricity to develop the full emission profile. The GHG emission profile of the building’s post-implementation operation should be used to capture the total GHG emissions in a given reporting period, such as meeting local BPS targets. The emission profile also should be viewed as a picture of when the emissions occur to identify any times when peak emissions may be higher than expected. System Performance (Not Just Equipment Performance). Many decarbonization solutions rely on different equipment and technologies working on a system level to shift loads and energy use periods. For example, a central plant system with heat recovery chillers and air to water heat pumps that are coupled with a TES tank and on-site PV production relies both on the proper operation (temperatures, energy output, etc.) of the individual components and on the operation as a system. The system must properly leverage clean PV production to charge the TES for use during periods of higher grid emissions to achieve the decarbonization goal. This requires a system-level monitoring approach layered with the grid emissions. Submetering for GHG Reporting. Planning ahead with the installation of utility submeters to separate building owner and tenant emissions data can prepare for reporting beyond whole building utility data. All reporting requirements must be considered, which may include owner or company requirements, investor-related ESG requirements, and government climate policy requirements, such as building performance standards. For example, a multi-tenant commercial building may be subject to local BPS that require reporting building annual GHG emissions and have future ESG reporting that requires documenting building owner and tenant emissions separately. Overall emissions reductions can be tracked using the Energy Star Portfolio Manager with imported utility consumption data. More detailed performance tracking and reporting could be conducted in accordance with the measurement and verification (M&V) plan, which should be included as an appendix to the decarbonization plan. The M&V plan should clearly document what parameters should be monitored for each EEM and ERM, how, and at what frequency. The M&V plan should also specify to whom performance reports should be provided and at what frequency—someone will need to own monitoring the progress toward goals.

CASE STUDY: The Heritage, New York

While submetering was not required for ESG reporting or similar, the case study for the Heritage provides an example of planning ahead and incorporating submetering within a decarbonization project. The Heritage provides heating for residents, and their decarbonization project replaced PTAC units with PTHPs. Electric submeters were installed as part of the project to separate heating use from plug load use to ensure that residents would not be charged for heating provided by the ownership. See the appendix for more details on the Heritage project.

### 3.7.1 Measure Installed Performance

Immediately following, or even during, the commissioning period is the ideal time for conducting performance tests and measurements of the installed decarbonization measures. Testing and measuring performance at this phase allows the project team to understand how the implemented measures compare to the expected performance and helps identify areas that may need troubleshooting. By carrying out the measure-specific post-implementation testing as close to the commissioning period as possible, long periods of poor performance and the associated increase in GHG emissions can be avoided. Post-installation tests and measurements should be performed in accordance with the M&V plan and meet specifications such as accuracy and precision. Any deviations from the test conditions or methods that were specified in the testing plan should be clearly documented to account for those changes when analyzing the test results and comparing them to the expected performance. Ultimately, installed system performance should result in the reduction or elimination of fossil fuels and should limit or reduce electric demand during periods of high GHG emissions. System performance should be based on marginal grid emissions where available, and where not available should use the best published grid emissions database or map (see Section 3.3.1.1) to develop the emission profile for comparison to the design. For straightforward retrofits with individual equipment replacements (e.g., PTAC to PTHP or split DX with furnace to split HP), verify that space conditions for both heating and cooling are met and that individual equipment performance aligns with designed performance. For more complex retrofits (e.g., electrified central plant, TES, BESS and/or microgrid), compare performance for complete systems and not just individual equipment. For example, where central heat pumps and/or heat recovery chillers are paired with TES, evaluate the performance of each individual heat pump/heat recovery chiller for correct temperatures and COP while also analyzing system level operation for correct “flow” of heat compared to end loads, and compare the system energy load profile to grid emission factors to understand the emission profile. Where energy recovery measures are employed, monitor parameters for heat exchange (including temperatures and flow), the conditions from the energy source and sink (e.g., space needing cooling and space needing heating), and the output (temperatures and/or flow) from HVAC systems to ensure reduced heating/cooling, which accounts for recovered energy. Test VRF systems for refrigerant leaks to minimize GHG emissions from refrigerant leaks by quick identification and repair.

With decarbonization retrofits, there are some logistical performance items to verify beyond the energy use and GHG emissions performance. Verify that new electrical equipment operates effectively without electrical capacity issues (overloading/tripping circuits). Verify that any electrical system controls, such as circuit-sharing devices or load shifting/shedding from grid-interactive software, provide correct responses under design conditions and do not result in electrical capacity issues or increased grid use during higher GHG emissions periods. Verify sufficient heating hotwater temperatures where fossil fuel heating (e.g., boilers) was replaced with heat pumps to ensure that needed supply temperatures are met. Verify that equipment operation does not disturb occupants (e.g., noise levels).

### 3.7.2 Measure Ongoing Performance

Key to ensuring the expected performance results of decarbonization measures is tracking and reporting on the observed performance during the post-implementation period. The process of tracking and reporting on performance allows a building operator to identify areas for improvement and aid in troubleshooting a system’s operation.

Ongoing performance for EEMs and ERMs should focus on meeting space needs and operating where building grid electricity use best aligns with periods of low GHG emission factors and on-site generation eliminates or reduces GHG emissions as much as possible. Plans for measured performance should make use of BAS for system-level performance and should include utility interval data for building meters and submeters. Intervals of at least one hour are recommended to compare building energy use with grid emission factors. ASHRAE Guideline 14 provides more detail for measuring EEM performance and calculating savings.

Some items to consider for decarbonization retrofit performance:

- Monitoring and maintaining data connections and reliability are critical for more complex retrofits and grid-interactive systems. This includes communications between field sensors and BAS and between BAS and external systems for grid interactivity.

- Monitor refrigerant leaks for VRF systems to minimize GHG emissions due to their potential impact. Refrigerant monitoring systems can provide early identification of leaks to minimize impacts and track refrigerant recharge quantities. These systems provide data to act on if quantities are higher than expected.

- Where dual-fuel equipment or hybrid systems are installed, monitor modes of operation compared to environmental conditions to ensure that fossil fuel use is minimized.

Measuring equipment and system level performance ensures that whole-building GHG emissions performance may be achieved. In most cases, the ongoing performance for decarbonization projects will be represented as whole-building (or buildings) GHG emissions. Depending on the nature of targets or goals set for the project, performance may be compared as annual GHG emissions or may be compared as annual GHG emissions reductions. ASHRAE/ICC Standard 240P establishes how to measure and verify the GHG and carbon emissions of a building or group of buildings over the entire life cycle.

Ongoing performance tracking can allow building operators and stakeholders to identify areas that have fallen short of expected performance. With the help of qualified contractors, stakeholders can use tracking information to determine ways to correct performance shortfalls. It is especially important to be aware of equipment warranties and to conduct performance reviews prior to their expirations to avoid added equipment or maintenance costs that could be included under the warranty.

If measures are not performing as designed, identify the magnitude and frequency of poor performance within the collected data. Review data for changes to building occupancy/operating profiles that influence system operation, such as shifts in morning warm-up. Also review for changes in equipment sequencing/operation within given systems, such as supplemental boilers operating when a heat pump should be per designed control sequences. Actions taken to remedy the system will depend on the type of poor performance found. Overridden set points for equipment are easily addressed by facility staff after understanding the reason for the override. Where systems or equipment performance issues are not obvious to facility staff, it may be necessary to perform targeted decarbonization assessments of systems or buildings. This can include installing additional metering to better pinpoint sources of either increased or shifted consumption that has resulted in higher GHG emissions.

ASHRAE Guideline 14, Measurement of Energy, Demand, and Water Savings

ASHRAE Guideline 14 provides guidance for reliably measuring the energy, demand, and water savings achieved in conservation projects (ASHRAE 2023e). The guideline presents a standardized set of energy, demand, and water savings calculation procedures and guidance on minimum acceptable levels of performance for determining savings and using measurements in commercial transactions. ASHRAE Guideline 14 is intended for transactions between energy service companies (ESCOs) and their customers and between ESCOs and utilities, where the utilities have elected to purchase energy savings.

ASHRAE Guideline 14-2023 (Supersedes ASHRAE Guideline 14-2014)

Measurement of Energy, Demand, and Water Savings

Approved by ASHRAE on August 1, 2023.

© 2023 ASHRAE ISSN 1049-894X

Guideline 14 includes access to RP-1050 and RP-1093 Final Reports and the ASHRAE Inverse Modeling Toolkit and Diversity Factor Toolkit (requires Microsoft Excel).

### 3.7.3 Operation and Maintenance Procedures

Similar to energy efficiency projects, proper operation and routine maintenance are crucial for decarbonization retrofits. Develop a maintenance plan that includes the level of GHG emissions impact for different equipment and systems. The plan should employ both system-level and equipment-level maintenance plans. Equipmentlevel maintenance plans will include regular preventative maintenance as recommended by the manufacturer. The system-level maintenance plans focus on cooling/heating source, distribution network, and delivery terminals because of the interactive nature of decarbonization solutions. Systemlevel maintenance plans should incorporate monitoring and evaluating system data to inform maintenance for these interdependent systems because of system-wide effects from singleequipment failure. For VRF systems in particular, maintenance procedures should include

Apartment and Office Building Association of Metropolitan Washington Educational Foundation’s Operations and Maintenance Best Practices for Energy Management Guide

This guide outlines the critical role operations and maintenance play in increasing energy efficiency and adding value for property owners and their portfolios (AOBA 2023). Readers will learn key strategies for building an internal culture that promotes efficiency; addressing reactive, proactive, and predictive maintenance; and examining the whole building as well as key building components for energy efficiency opportunities. The guide is meant to be used as the basis for creating manuals tailored to individual facilities or companies.

**[Figure: Operations & Maintenance Best Practices for Energy Management]**

Type: diagram

Description: The figure depicts two individuals in high-visibility jackets and hard hats, engaged in maintenance work on an electrical panel. The scene is set against a backdrop of a building's exterior, with a clear blue sky visible in the distance.

Key Elements:

- Electrical Panel -> The central focus of the maintenance activity, indicating the importance of regular upkeep for energy management.
- High-Visibility Jackets and Hard Hats -> Safety gear worn by the maintenance personnel, highlighting the emphasis on safety protocols in operational practices.
- Building Exterior -> The setting for the maintenance work, suggesting that the practices are applicable to various types of buildings or facilities.

This diagram illustrates the practical application of operations and maintenance best practices in the context of energy management, emphasizing both safety and efficiency.

regular checks of system refrigerant charge to identify and quickly address refrigerant leaks and limit GHG emissions impacts from leaks. Where systems depend upon grid-interactive controls to dispatch equipment for optimal GHG emissions, operation and maintenance procedures must include monitoring and maintaining field sensors, controllers, and data connections for accurate and reliable information. The benefits of quality operations and maintenance plans include increased efficiency and performance of systems over the long term, reduced waste and GHG emissions, and longer equipment life, which reduces the carbon footprint of embodied carbon from buying replacement equipment or components that could last much longer if properly maintained.

## 4.1 Existing Building Considerations

This chapter provides a discussion of key considerations for decarbonization retrofits within existing buildings. Existing buildings can have a host of challenges different from new construction projects that can easily disrupt or impede a retrofit project. Given the number of challenges that may exist when decarbonizing existing buildings, the decarbonization assessment discussed in Section 3.3 should be used to detail existing conditions and potential challenges to properly evaluate and design retrofit measures. Occupants and facilities stakeholders can be a resource: their knowledge of existing conditions and operations can offer valuable insight into what might need to change as part of a renovation to increase occupant satisfaction and wellness. This chapter includes the following considerations, although this is not an exhaustive list:

- insufficient electrical or structural capacity for new equipment, systems, or envelope upgrades
- building age and envelope conditions that may be hard to renovate but that could significantly affect the performance of decarbonization scenarios
- space constraints that complicate existing system or equipment removal and/or limit new system options
- building systems and conditions that are not compliant with local building codes and must be upgraded as part of a retrofit project
- historic building considerations and restrictions due to local ordinances
- occupants or process operations that require disruption during implementation
- equity and affordability considerations that may limit stakeholder participation or result in unintended community impacts
- owner-occupied vs. leased buildings’ financial constraints due to tenant lease structures and phasing challenges with multi-tenant buildings

## 4.2 Electrical Capacity

Converting from fossil fuel building systems and appliances to electric systems or installing EV charging stations can increase a building’s electrical load. An electrical demand analysis of meter readings on the current system’s operation must be done to evaluate the building’s current and anticipated electrical demands. The analysis should include an investigation of circuit sharing, load diversity, and smart devices/panels that can share or schedule loads without increasing the electrical service size. The analysis also should evaluate whether the existing electrical service may allow for partial electrification without major upgrades. In some cases, this approach may make the most sense for the building owner. In cases where electrical service upgrades are necessary, the upgrade may be small (adding sub-panels and electrical conduits) but can also include upgrading utility transformers and switchgear. Utility electrical service upgrades are often costly and time consuming (several months), requiring coordination with utility providers, compliance with current code requirements, and disruptions to building operations. A discussion of including electrical service upgrades in the decarbonization plan is included in Section 3.5.2 in Chapter 3. There are several solutions to consider when addressing electrical capacity issues in existing buildings. In addition to those listed below, Chapter 5 provides additional guidance on technologies and strategies to manage and minimize electrical loads, including:

- load reduction and thermal storage to minimize electrical demand
- load-management switching devices that allow loads to share circuits and prioritize operations based on demand
- smart building systems with advanced control and automation capabilities to optimize equipment operation, curtail load, and shift energy consumption
- integrating distributed energy resources such as solar PV systems and energy storage to offset grid electricity consumption and provide flexibility
- energy storage systems, such as batteries, to help manage peak grid demand by storing and discharging energy when needed
- prioritizing decarbonization measures such as hybrid electrification with less demanding electrical needs and planning a multiyear roadmap of utility service electrical capacity upgrades to gradually reach full decarbonization

CASE STUDY: Bloedel Conservatory, Canada

See the case study for Bloedel Conservatory in Vancouver, BC, where a central plant serving nine AHUs was replaced with an AWHP. Due to existing constraints, an active demand management strategy is implemented to operate the AWHP within the electrical capacity. Future electrical upgrades are planned.

## 4.3 Structural Capacity

New equipment may be much heavier than the existing equipment it replaces or may need to be located in new spaces not originally designed for housing equipment, e.g., locating ASHP skids and largevolume buffer tanks on roofs not originally designed to hold equipment or adding roof-mounted solar PV arrays. This is more critical in seismic zones, where the increase in weight may trigger an upgrade in the lateral system. Therefore, decarbonization strategies need to address the challenges and limitations associated with structural capacity, starting with a load assessment. Structural Load Assessment. Conducting a structural assessment is an

**[Figure: Accelerating Electrification of California's Multifamily Buildings]**

Type: diagram

Description: The figure presents a report titled "Accelerating Electrification of California's Multifamily Buildings" with a cover page featuring a photo of a building and text. The report includes step-by-step instructions for evaluating electrical loads and capacity using the National Electrical Code's (NEC) electrical load calculation method or load-monitoring studies.

Key Elements:

*   Cover page -> Displays the title and a photo of a building
*   Text -> Provides information about the report's content and purpose

This figure is a descriptive diagram that serves as the cover page for a report on accelerating electrification in California's multifamily buildings. It provides an overview of the report's content and purpose, highlighting the importance of evaluating electrical loads and capacity using the NEC's electrical load calculation method or load-monitoring studies.

### Table: Data Table

|  | Accelerating Electrification of California’s Multifamily Buildings POLICY CONSIDERATIONS AND TECHNICAL GUIDELINES |  |
|---|---|---|
|  | STOPWASTE ASSOCIATION FOR ENERGY AFFORDABILITY (AEA) May 2021 |  |

CASE STUDY: StopWaste Office, California

The case study for StopWaste in Oakland, CA, represents a packaged RTU heat pump retrofit where a structural load assessment was performed to determine whether upgrades were needed for increased size and weight of RTUs. See the appendix for more details on the StopWaste Office.

important part of evaluating retrofit measures with equipment replacement and/or new proposed piping routes, etc., to determine its capacity for supporting additional loads. This assessment helps identify any structural weaknesses, such as inadequate foundations, load-bearing walls, or floor systems, which may require reinforcement or retrofitting. A field investigation will be needed with or without existing structural drawings to assess whether additional structural reinforcement is required in areas where new equipment will be located. Structural load assessment also includes wind load analysis for replacement rooftop equipment such as chillers, rooftop units, solar PV, or additional HVAC equipment. A taller and heavier rooftop unit that sits above an existing roof curb and is exposed to wind can create forces the roof structure was not designed to withstand. Structural Reinforcement and Retrofitting. Structural reinforcement may be necessary to enhance the capacity of existing buildings to support the installation of decarbonization technologies. This may involve strengthening load-bearing elements, such as beams or columns, or introducing additional structural elements, such as bracing or shear walls, to improve stability and load resistance. Seismic upgrades and compliance with updates to seismic codes should be considered. Existing buildings often have limited space for integrating these upgrades. See Section 4.5 for space constraint strategies. Building Envelope Upgrades. Enhancing the building envelope through insulation, window upgrades, and air sealing is a key strategy for reducing energy consumption. However, these measures can impose additional loads on the structure. Proper analysis and consideration of the structural implications are necessary to ensure that the building can withstand the added weight and potential changes in loading patterns.

## 4.4 Building Age and Envelope/Infrastructure Condition

The age and condition of the building and its envelope may affect the performance of planned decarbonization strategies. The building envelope—including foundation, roof and wall assembly, windows, and doors—is significantly affected by age. Gaps, cracks, and holes in the building envelope result in unintended air leakage. Single-pane windows, double-pane windows with failed seals, thermal bridging, and lack of wall and roof insulation, etc., all can result in a compromised building envelope, increasing building energy use and occupant discomfort. Upgrades to the existing building envelope, such as weatherization, upgrading windows, adding insulation, etc., should be evaluated to determine reductions to building heating and cooling loads. These upgrades should then be incorporated in conjunction with HVAC equipment upgrades to potentially reduce the size of new HVAC systems and associated costs for HVAC system decarbonization upgrades. Replacing or moving HVAC equipment also might cause differences in the building’s vibration transmission characteristics—something to evaluate as part of the decarbonization strategy. From a design perspective, considerations related to the ratio of building core versus shell and the orientation of the building are important. For example, building envelope improvement measures tend to have a bigger impact on smaller buildings than on larger buildings. When considering building massing, buildings with the long axis oriented east–west make envelope upgrades, daylighting, and natural ventilation measures more impactful. Some considerations for upgrading the existing building envelope include the following, which are discussed further in Section 5.2.1 in Chapter 5: Insulation. One of the primary challenges is ensuring proper insulation throughout the building envelope. Existing buildings may have insufficient or outdated insulation, making it necessary to add or upgrade insulation materials. Air Sealing. Effective air sealing is crucial to prevent air leakage through cracks, gaps, and openings in the building envelope. Air leaks can result in significant energy loss and reduce the effectiveness of HVAC systems. Window Upgrades. Windows are a significant source of heat gain and heat loss in a building. Upgrading windows to more energy-efficient options, such as double-glazed or low-emissivity (low-e) windows, can improve thermal performance. Roof Upgrades. The roof is another critical component of the building envelope that can affect energy efficiency. Upgrading the roof can result in peak heating load reduction. Older roofs may lack proper insulation or have deteriorated over time, leading to heat gain or loss. Moisture Management. Upgrading the building envelope should include moisture management to prevent issues such as mold growth, decay, and deterioration. The challenge is to balance energy efficiency with adequate ventilation and moisture control.

## 4.5 Space Constraints

Existing buildings may have limited roof/floor area, ceiling height, or structural limitations that restrict the installation of new equipment or systems. These physical constraints can pose challenges when implementing decarbonization strategies, including:

- New equipment installed during a decarbonization retrofit may have a larger footprint than the existing equipment because of its better efficiency and greater heat transfer area.
- Space limitations may pose challenges for installing additional electrical panels, upgrading plumbing systems, or installing more complex equipment (e.g., cascaded air-to-water and water-source heat pumps).
- Air-source heat pumps also may have increased ventilation requirements, including additional room volume beyond the size of the equipment itself. Replacing gas boilers, which are relatively small and typically located indoors, with air-to-water heat pumps that are larger and typically located outdoors is a common issue.
- Existing mechanical rooms may have been built around large equipment, leaving minimal space for service clearance.
- Installing refrigerant-based electric solutions in existing boiler rooms can require a refrigeration machine room.

In all these cases, removing the existing equipment and delivering and installing the new equipment can pose significant space constraint challenges and require careful planning during design and the pre-construction period. Some strategies, challenges, and solutions related to space constraints include the following: Efficient Space Planning. Optimize the use of available space through thoughtful planning and design. When feasible, use flexible layouts, shared spaces, and multifunctional areas to maximize limited square footage. Collaborate with architects and designers to develop creative design solutions that maximize available space. This may involve reconfiguring layouts, optimizing underutilized spaces, or incorporating storage solutions. Use building information modeling (BIM) technology to simulate and visualize different design scenarios before implementation. This can help identify potential clashes or conflicts with space constraints and optimize design decisions accordingly.

Compact and Space-Saving Equipment. To address space limitations, select modular and compact replacement equipment that is designed to occupy less space without compromising performance. Look for innovative technologies specifically designed for space-constrained environments, such as compact and integrated systems that combine multiple functions into a single unit, reducing the overall footprint. This also ensures that the equipment can fit through narrow access passages in existing buildings, such as hallways, staircases, or single doors. Large equipment may need to be delivered in modular pieces and assembled on-site in the mechanical rooms, though more labor intensive. Off-site construction methods or prefabricated modular systems can be more easily installed in limited spaces. This allows for faster and more efficient installation while minimizing disruption to building occupants. Existing buildings also may have unused or partially used spaces that might accommodate equipment or allow expansion of existing mechanical rooms. In such cases, this will require working with building owners and operators during design to reconfigure or repurpose rooms for mechanical equipment in advance of implementation. Mechanical Room Location. From an implementation perspective, considerations of mechanical room location and access are important. For example, mechanical rooms located on upper floors of high-rise buildings may require additional planning and logistics for mechanical equipment installation. Some installations may require crane lifts or even helicopter lifts, which represent substantial cost and schedule impacts. Even seemingly simple retrofits may require additional planning and coordination based on building or space configurations. For example, LED lighting retrofits in a high-ceilinged building or space may require the use of man lifts and additional planning and safety coordination to implement successfully.

## 4.6 Local Building Codes and Ordinances

Decarbonization retrofit activities may trigger the need to comply with multiple codes and standards not previously applicable to an existing building, including building codes, mechanical codes, plumbing codes, electrical codes, fire and life safety codes, ventilation standards, and accessibility code requirements. “Reach” or “stretch” codes, “green” codes, and building electrification policies are being adopted locally around the nation and should be consulted for related requirements for energy or emissions reduction, EV infrastructure, clean power generation, wildfire mitigation, and other topics that could influence the decarbonization strategy. Design engineers also should be mindful, that in some cases, adjustments required to comply with current building codes and standards can result in increased energy use compared to that of the existing systems. These impacts should be included in an analysis of the change in energy use and carbon emissions for the project and may drive a pursuit of alternative technologies or unique decarbonization strategies. The Montreal City Hall project provides an example where ASHPs were located within a mechanical room due to roof space limitations and local municipal codes for rooftop equipment.

California IOU Reach Codes Subprogram

In an effort to meet climate action plans, local authorities having jurisdiction (AHJs) are adopting energy codes and stretch codes that are more stringent than the national model codes. Administered by investor-owned utilities (IOU) California’s Reach Codes Subprogram has created a website resource that tracks which AHJs in California have locally adopted reach codes and briefly summarizes the reach code topics (CPUC n.d.).

## 4.7 Historic Buildings and Regulatory Constraints

Decarbonizing historic buildings can present challenges due to their architectural significance and unique characteristics. Implementing decarbonization strategies in these buildings requires careful planning and thoughtful approaches to preserve their historic value and, in some cases, meet preservation requirements while reducing carbon emissions.

CASE STUDY: Montreal City Hall, Canada

The Montreal City Hall project provides an example where ASHPs were located within a mechanical room due to roof space limitations and local municipal codes for rooftop equipment. Locating the ASHPs indoors also proved beneficial for heat pump performance in heating season because of the cold climate.

**[Figure: ASHRAE Guideline 34, Energy Guideline for Historic Buildings]**

Type: diagram

Description: The figure presents a screenshot of the ASHRAE Guideline 34, Energy Guideline for Historic Buildings. The guideline provides sound advice on the practices, processes, and workflows that should be followed when performing energy efficiency and energy conservation improvement projects and programs involving historic buildings, while minimizing disturbance to the historic character, characteristics, and materials (significance, value, and qualities) of the building (ASHRAE 2019c).

Key Elements:

- **ASHRAE Logo**: The logo is displayed in the top-left corner of the image, indicating that the guideline is published by the American Society of Heating, Refrigerating, and Air-Conditioning Engineers (ASHRAE).
- **Guideline Title**: The title of the guideline is prominently displayed at the top of the image, clearly indicating the purpose and scope of the document.
- **Image of a Building**: A small image of a building is shown in the bottom-left corner of the image, likely representing a historic building that the guideline is intended to help preserve.
- **Text**: The majority of the image is filled with text, which provides an overview of the guideline's contents and purpose. The text is written in a clear and concise manner, making it easy to understand for readers who are familiar with the topic.

## 4.8 Occupant Considerations

Existing building retrofit projects must consider how the decarbonization measures—both the measures themselves and the implementation (i.e., construction)—will affect building occupants. Working with an occupied or partially occupied building during construction requires planning and occupant coordination ahead of time. For example, building tenants may need to occupy the building during construction, requiring construction to be staged in phases during hours tenants do not occupy the spaces. Staging and other considerations relevant to occupied building renovations are discussed in Section 3.6 in Chapter 3.

A Field Guide to Retrofits in Occupied Buildings

The Centre for Urban Growth and Renewal developed a guide designed to assist apartment owners, the construction industry, and apartment residents navigating retrofit construction projects in Canada. The guide presents strategies and methods for conducting a retrofit efficiently and effectively while tenants are in the building (CUG+R 2020).

**[Figure: Building with Trees]** Type: diagram Description: The image depicts a tall building with multiple balconies and windows, accompanied by trees in the foreground. Key Elements: - Building -> The central structure with numerous balconies and windows. - Trees -> The foliage in the foreground, partially obscuring the view of the building.

### Table 4.1    Architecture 2030 Intervention Points for Building Energy Upgrades

| Intervention Point | Where Intervention Point is Most Applicable | Key Stakeholders |
|---|---|---|
| Building Point of Lease/ Rental | • Large stock of apartments or leased properties • Large transient populations (e.g., stu- dents, seasonal workers) • High value/competitive rental market | — |
| Building Point of Sale | • Highly active or valuable real estate market • Frequent building turnover rates (3%+ annually) | — |
| Building Renovation | • Large institutional or long-term building owners (e.g., universities, hospitals, government) • Historically significant building stock • Limited rates of new construction | Building owners, tenants, historical commissions, contractors and trades, utilities |
| Building Maintenance and Major System Replacement | • Aging building stock • Prevalence of legacy building sys- tems (e.g., fuel oil heating, incandes- cent lighting) | Building owners, landlords, building managers, systems installers and contractors |
| Building Resilience Upgrades | • Geographic risk of fire, flood, or seismic events • Predominance of weather extremes (hot/cold) • Existing policies or programs for resilience/life safety retrofits for older structures | Homeowners, building managers, health and safety regulators |
| Table Source: Architecture 2030 (2023) |  |  |

The independent climate emergency response organization Architecture 2030 has identified points in the lifespan of a building, dubbed intervention points, that represent potential renovation times that minimize costs, impacts to occupants, etc. The intervention points largely align with necessary capital improvements and renovations. Architecture 2030 highlights the circumstances where intervention points are most applicable and the key stakeholders for coordination.

## 4.9 Equity and Affordability

Equity and affordability are common concerns for both commercial and multifamily buildings. The up-front costs of decarbonization can be a barrier, especially for smaller businesses and lowincome households. To address this, financial incentives, grants, tax credits, and utility rebates can make decarbonization more affordable and encourage wider adoption. Engaging with local communities and stakeholders to understand their specific needs and concerns can help tailor decarbonization strategies that are both effective and affordable. Providing training opportunities for the local workforce, such as workshops with industry experts, is key to a successful technological and economic shift to decarbonization, especially in communities of concern.

In commercial buildings, equity can be addressed by ensuring that decarbonization strategies are accessible to businesses of all sizes. Small businesses may face financial constraints and lack the resources to invest in costly upgrades. Therefore, it is essential to find incentives, grants, or equitable access to financing options, such as on-bill financing, that support small businesses in implementing energy-efficient technologies. Additionally, outreach and education programs can help raise awareness about the benefits of decarbonization and provide guidance on available resources. In multifamily buildings, equity and affordability considerations are closely tied to the well-being of occupants. Decarbonization strategies should aim to improve indoor air quality, thermal comfort, and overall living conditions while reducing carbon emissions. Low-income households often face higher energy burdens, so it is important to implement cost-effective solutions that reduce utility bills and promote energy efficiency. Incentives and programs for affordable housing can support the adoption of energy-efficient appliances, insulation, and renewable energy systems. Collaborating with community organizations, housing authorities, and local energy efficiency programs can help ensure that decarbonization efforts prioritize the needs of low-income residents.

Community Benefits Plans

Community benefits plans (CBPs) document priorities set by local community organizations and leaders where renovation projects occur, including how the renovation might affect the community. CBPs address priorities such as workforce development, job creation, housing availability and affordability, etc. Within the CBP, building owners respond to the documented priorities and how the retrofits will consider them. Rocky Mountain Institute provides guidance on their webpage around developing CBPs, including their purpose and sample content (Draklellis and Richardson 2023).

CASE STUDY: 47 Seventy Apartments, Utah

# 47 Seventy Apartments in the Salt Lake City area are naturally occurring affordable housing. The project included LED and HVAC retrofits. Over half of the project cost was offset by local energy efficiency program rebates and the remainder covered by the property owner. The property owner will realize an increase in value of their property based on the project upgrades and more comfortable and healthy apartments.

### 4.9.1 Disadvantaged Communities

Decarbonization initiatives within disadvantaged communities face several barriers that can hinder progress toward sustainable outcomes. In addition to the up-front cost associated with implementing decarbonization measures, some communities may be at risk for building upgrades resulting in higher rent, displacing businesses and residents from their communities. Working with local equity officers, housing authorities, communitybased organizations, etc., can help building owners understand and respond to community impacts. Additional incentives may be available to limit capital costs to keep rents stable. In some instances, tenant protections are required to avoid increased rent, eviction, or displacement during and after the renovation.

DOE Climate and Economic Justice Screening Tool

Nationwide, the Climate and Economic Justice Screening Tool (CEJST) identifies approximately 27,251 census tracts as disadvantaged. Generally, a census tract will be marked as disadvantaged if it meets the threshold for: 1) environmental, climate, or other burdens and 2) an associated socioeconomic burden. In addition, a census tract that is completely surrounded by disadvantaged communities and is at or above the 50th percentile for low income is also considered disadvantaged. The interactive tool is searchable to indicate disadvantaged communities throughout the United States (DOE 2023o).

**[Figure: Search locations]**

Type: diagram

Description: The figure is a map of the western United States and Canada, with a search bar at the top. The map appears to be a screenshot from a website or application, with various locations marked on it.

Key Elements:

* Search bar -> allows users to enter keywords or locations to search for
* Map -> displays the western United States and Canada, with various locations marked on it
* Zoom controls -> allow users to zoom in and out of the map
* Location markers -> indicate specific locations on the map

This figure is likely used to help users find specific locations or search for information related to those locations.

### Table 4.2    DOE Climate and Economic Justice Screening Tool Indicators

| Climate Change >=90th percentile for at least one of these: • Expected agricultural loss rate • Expected building loss rate • Expected population loss rate • Projected flood risk • Projected wildlife risk AND >= 65th percentile for low income | Legacy Pollution • Have at least one abandoned mine, or • Formerly used defense sites >=90th percentile for at least one of these: • Proximity to hazardous waste facilities • Proximity to superfund sites • Priorities list • Proximity to risk management plan facilities AND >= 65th percentile for low income |
|---|---|
| Energy >=90th percentile for at least one of these: • energy cost • PM in the air 2.5 AND >= 65th percentile for low income | Transportation >=90th percentile for at least one of these: • Diesel particulate matter exposure • Transportation barrier • Traffic proximity and volume AND >= 65th percentile for low income |
| Health >=90th percentile for at least one of these: • Asthma • Diabetes • Heart disease • Low life expectancy AND >= 65th percentile for low income | Water and Wastewater >=90th percentile for at least one of these: • Underground storage tanks and releases • Wastewater discharge AND >= 65th percentile for low income |
| Housing • Experienced historic underinvestment (red- lined) OR >=90th percentile for at least one of these: • Housing cost • Lack of green space • Lack of indoor plumbing • Lead AND >= 65th percentile for low income | Workforce Development >=90th percentile for at least one of these: • Linguistic isolation • Low median income • Poverty • Unemployment AND < 10% people older than 25 have a high school diploma |
| Table Source: DOE (2023o) |  |

Another barrier is the limited outreach and educational resources available to disadvantaged communities. Residents may have limited access to information about the benefits of sustainable technologies and the incentives and opportunities that exist. This lack of awareness and understanding can hinder engagement and stakeholder participation in decarbonization initiatives. Connecting with stakeholders through communitybased organizations, community leaders, and community social programs may help building owners and project teams gain trust and the engagement needed for a successful renovation. The Department of Energy has created indicators to evaluate communities and determine if they qualify as disadvan-

White House Justice40 Initiative

Created under the Biden-Harris Administration, Justice40 establishes the goal that 40% of the overall benefits of certain federal investments flow to disadvantaged communities (DACs). The Justice40 Initiative applies to over 145 Department of Energy (DOE) programs and much of the $62 billion investment in DOE under the Bipartisan Infrastructure Law. To ensure an equitable transition to clean energy, and to avoid further harm to communities with environmental justice concerns, the DOE is laser focused on ensuring that every project that receives funding through a DOE Justice40 covered program adheres to the principles of environmental justice (DOE 2023o).

**[Figure: Justice40 Initiative Environmental Justice Fact Sheet]**

Type: diagram

Description: The Justice40 Initiative provides a once-in-a-generation opportunity to transform communities that, for too long, have faced disproportionate exposure to environmental hazards and harms, been excluded from access to Federal funding, and have been locked out of the decisions that shape their communities.

Key Elements:

- **THE JUSTICE40 INITIATIVE**: Created under the Biden-Harris Administration, Justice40 establishes the goal that 40% of the overall benefits of certain Federal investments flow to disadvantaged communities (DACs). The Justice40 Initiative applies to over 145 Department of Energy (DOE) programs and to much of the $62 billion investment in DOE under the Bipartisan Infrastructure Law.
- **TRANSFORMING COMMUNITIES USING PRINCIPLES OF ENVIRONMENTAL JUSTICE**: The transition of the energy system to one that relies on clean energy will require the development of new energy projects where people, live, play, and work. Underlying structural inequalities and structural racism historically have resulted in development projects that disproportionately and inequitably harm low-income communities and communities of color.
- **WHAT IS ENVIRONMENTAL JUSTICE?**: Environmental justice is the fair treatment and meaningful involvement of all people regardless of race, color, national origin, or income with respect to the development, implementation and enforcement of environmental laws, regulations, and policies. Fair treatment means no group of people should bear a disproportionate share of the negative environmental consequences resulting from industrial, governmental and commercial operations or policies. Meaningful involvement means (1) people have an opportunity to participate in decisions about activities that may affect their environment and (or health, (2) the public's contribution can influence the regulatory agency's decision; (3) community concerns will be considered in the decision making process; and (4) decision makers will seek out and facilitate the involvement of those potentially affected.

taged. The indicators are grouped into eight categories of burden, including climate change, energy, health, housing, legacy pollution, transportation, water and wastewater, and workforce development. Meeting the indicator requirements in any of the eight categories will qualify the community as disadvantaged.

### 4.9.2 Policies and Programs

Policies and programs at the local, state, and federal levels can be an aid for facilitating decarbonization within disadvantaged communities. These initiatives provide support, funding, and incentives to promote sustainable practices and address the unique challenges faced by these communities. One example is the Low-Income Weatherization Assistance Program (LIWAP), a federally funded initiative that assists low-income households in improving energy efficiency through weatherization upgrades. LIWAP grants enable the implementation of measures including insulation, air sealing, and HVAC system improvements, which help to reduce energy costs and alleviate burdens on vulnerable populations. Community solar programs are another effective policy approach that allows residents, including those in low-income communities, to benefit from solar energy. These programs enable individuals to subscribe to a shared solar project and receive credits on their electricity bills, eliminating the need for individual solar installations and promoting equitable access to renewable energy. Additionally, grants provided by the Environmental Protection Agency (EPA) support environmental justice initiatives in communities disproportionately affected by pollution. These grants fund projects that aim to reduce environmental impacts and improve public health while fostering community engagement and capacity building. Many utility companies and state agencies offer energy efficiency assistance programs, which provide free or subsidized energy audits, upgrades, and education to low-income households. These programs empower residents to reduce energy consumption, lower utility bills, and improve comfort, all while addressing equity and affordability concerns.

## 4.10 Building Owner Type

Depending on the ownership/occupancy structure of a building, the economic beneficiaries of decarbonization projects will differ. A common hurdle for implementing decarbonization measures in leased buildings is a “split incentive” problem. A split incentive occurs when a building owner pays the up-front costs of energy efficiency measures, yet the tenant(s)—not the building owner—benefit from the upgrades. Table 4.3 presents various ownership/occupancy structures detailing whether the owner or tenant is responsible for paying expenses and capital costs and indicating whether the lease structure may result in a split incentive.

### Table 4.3    Commercial Lease Types and Split Incentives

| Lease Type | Who Pays Expenses | Who Pays Capital Costs | Split Incentive? |
|---|---|---|---|
| Gross Lease | Owner | Owner | No |
| Triple-Net Lease | Tenant | Tenant | No |
| Multi-Tenant Office Net Lease | Tenant | Owner | Yes |
| Modified Gross Lease | Owner and Tenant | Owner | Yes |
| Table Source: Urban Green, PlaNYC and NRDC’s Energy Aligned Clause (NYC Government 2023). |  |  |  |

**[Figure: Urban Land Institute's business case for electrifying]**

Type: diagram

Description: The diagram illustrates the business case for electrifying buildings, highlighting the financial, impending regulations, technical, and environmental benefits of doing so. It presents a comprehensive overview of the advantages of electrification, including cost savings, compliance with regulations, improved energy efficiency, and reduced environmental impact.

Key Elements:

* Financial Benefits: 
	+ Saving construction costs
	+ Optimizing retrofit timing
	+ Lowering operational energy costs
* Impending Regulations: 
	+ Complying with "gas ban" policies
	+ Preparing for future sustainability requirements
* Technical Benefits: 
	+ Driving energy efficiency
	+ Optimizing smart building grid-interconnectivity
* Environmental Benefits: 
	+ Achieving corporate decarbonization and net-zero goals
	+ Supporting tenant sustainability goals
	+ Improving health and safety

### 4.10.1 Building Owner Occupied

Building-owner-occupied buildings can be more attractive for decarbonization retrofits because the owner benefits directly from building improvements. In addition, how they operate and maintain the building has a direct impact on the utility bills, operating and maintenance costs, and energy consumption/emissions generation. The following benefits should be considered when selecting EEMs/ERMs in owner-occupied buildings:

Cost Savings. Decarbonizing and improving the energy efficiency of the building can result in significant cost savings. Lower utility bills can directly affect the owner’s bottom line, reducing operating expenses and increasing profitability. Additionally, energy-efficient systems and equipment often have lower maintenance and replacement costs, leading to long-term financial benefits.

Energy Use Intensity (EUI) Reduction. The building owner’s operating and maintenance practices directly influence the building’s energy use intensity (EUI). By adopting energy-conscious behaviors and implementing energy-efficient measures, owners can significantly reduce their building’s EUI, which measures the energy consumption per square foot. Lower EUI values indicate a more efficient and sustainable building, positively influencing its environmental footprint. Lower consumption can also prepare buildings to meet future regulations and local ordinances.

Enhanced Comfort and Productivity. A decarbonized building can provide a more comfortable and healthier indoor environment for occupants. Improved insulation, efficient HVAC systems, and advanced controls can regulate temperature, humidity, and air quality, promoting occupant comfort and well-being. Increased comfort can enhance productivity, employee satisfaction, and overall building performance. Building Value and Marketability. Decarbonization retrofits can enhance the market value and marketability of owner-occupied buildings. Energy-efficient and sustainable features are increasingly sought after by tenants, buyers, and investors. Buildings with lower operating costs, reduced environmental impact, and improved indoor environmental quality can command higher rents, attract quality tenants, and have a competitive advantage in the market. To fully capitalize on the benefits of decarbonization, building owners should consider their role in operating and maintaining the building. Implementing energy-management practices—such as regular equipment maintenance, optimizing control settings, and engaging occupants in energy-saving initiatives—has a direct impact on utility bills, operating and maintenance costs, and overall energy usage. By actively managing and maintaining the building’s energy systems, owners can optimize performance, ensure longterm sustainability, and achieve the maximum return on their decarbonization investments.

### 4.10.2 Leased Buildings

Green Lease Leaders’ Reference Guides for Landlords and Tenants

Green Lease Leaders

REFERENCE GUIDE FOR LANDLORDS

Green Lease Leaders

Developed by:

REFERENCE GUIDE FOR TENANTS

Developed by:

Urban Land Institute’s Electrify: The Movement to All-Electric Real Estate

Electrify: The Movement to All-Electric Real Estate, by the Urban Land Institute’s (ULI) Greenprint Center for Building Performance, shows how the commercial real estate industry can shift toward a decarbonized future by moving to all-electric buildings and highlights the importance of why real estate firms need to be aware of the movement (Pierce et al. 2021). Electrification across new and existing buildings is improving real estate’s bottom line, future-proofing portfolios, attracting high-quality tenants, lowering building emissions, and improving the health and safety of building occupants.

As shown in Table 4.3, which outlines different lease types on the market, utilities are commonly paid directly or indirectly by tenants while the owners/ landlords pay for capital improvements. The resulting split incentive can hinder building owners from implementing building upgrades, including decarbonization measures, which in turn can negatively affect tenants, burdening them with higher utility costs and, in some cases, less healthy environments; this is particularly a problem in low-income communities. In leased buildings, stakeholder engagement and outreach should be used to understand potential benefits of decarbonization upgrades for tenants. Improved indoor air quality, comfort, the ability to market their occupancy in a decarbonized building, etc., should all be documented and considered during EEM/ERM selection.

The landlord and tenant reference guides provide guidance for landlords and tenants on how to comply with and implement green leasing standards to achieve recognition as a Green Lease Leader (IMT 2022a and 2022b). Even if not pursuing the Green Lease Leader recognition, building owners may find the guides useful if looking to implement green leasing practices across their portfolios. Topics such as including costrecovery clauses and energy-management best practices are offered in addition to sample lease clauses, case studies, and recorded trainings.

The first steps in the framework for decarbonization projects are identifying opportunities to reduce building electrical loads and heating and cooling loads. Existing buildings typically have limited electrical capacity, and electrical load reductions may help avoid costly electrical upgrades otherwise needed to make HVAC and DHW electrification options achievable. Building heating and cooling load reductions through envelope upgrades and HVAC heat recovery strategies can help reduce the required capacity of electrified HVAC equipment to fit within existing building spaces or reduce space and weight on roofs.

## 5.1 Electrical Load Reduction

Strategies and technologies that optimize energy usage and minimize electrical loads in buildings for lighting and plug loads have traditionally been core components of energy efficiency projects. While these strategies still provide attractive energy savings, they are also key strategies for reducing building electrical loads to make additional electrical capacity available for HVAC electrification equipment in existing buildings that do not have excess capacity.

### 5.1.1 Building Lighting Systems

Building lighting systems have a big impact on the electrical load of a building and influence the heating and cooling loads. Retrofitting with energy-efficient lighting fixtures and advanced controls can reduce the electrical load and provide reductions in GHG emissions through reduced energy consumption. The lighting system types covered in this section include interior lighting, exterior lighting, lighting controls, and daylighting. High-efficiency lighting, such as LED lamps and fixtures, can reduce energy consumption and carbon emissions, especially those with high efficacy ratings and U.S. EPA ENERGY STAR® certifications. Lighting controls can be achieved via dimmers, timers, or sensors that automatically turn lights on/ off or reduce levels based on need. The most common sensor technologies are occupancy, motion, daylight, and photosensor. While occupancy, motion, and daylight sensors are commonly used for interior

LED Troffer Retrofit Lighting and Controls: Best Practices

This DOE application guide provides a detailed discussion of options for retrofitting troffer lighting with LED and TLED systems. It also lists pros and cons for different retrofit approaches and key considerations for different types (DOE 2022a).

# Chapter 5: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

lighting controls, photosensors can be used for exterior lighting controls. When it comes to daylight controls, it should be noted that low-e windows, which play a critical role in reducing cooling load by lowering solar gain, can also be tuned to control visible daylight transmittance. 5.1.1.1 Interior and Exterior Lighting

A building’s interior lighting can consume a significant amount of energy and create considerable heat within the conditioned space. Maintaining an appropriate lighting level depending on occupant needs is critical to ensuring a low carbon footprint while maintaining occupant comfort. Choosing lighting fixtures and bulbs that carry the ENERGY STAR label ensures that retrofits meet strict energy-efficiency standards that reduce energy consumption. LED Lighting. Transitioning from incandescent or fluorescent lighting to energy-efficient LED lighting offers a significant reduction in the electrical load. For interior lighting, due to emitting very little heat to the space, LED fixtures reduce the cooling load considerably. However, this results in increases in the heating load that must be accounted for when sizing heat pumps for HVAC electrification retrofits. Task Lighting. Providing localized lighting sources in areas where specific tasks are performed, such as desks, workstations, or reading areas, allows for lower ambient lighting levels and can reduce the overall electrical load of the lighting system. Bi-Level Switching. Dividing the lighting fixtures into two or more circuits allows for independent control of light levels, which provides the option to operate only a portion of the fixtures when maximum lighting levels are not necessary. Skylights and Solar Tubes. Providing daylighting through skylights and solar tubes, when paired with daylight controls, reduces the need for electric lighting during daytime hours. Encouraging and influencing the adoption of sustainable occupant behaviors and operational procedures, such as conserving power by turning off lights, will have an even greater impact on decarbonization. 5.1.1.2 Lighting Controls Lighting control upgrades reduce building electrical demand when occupancy/task variations and daylight availability are considered. Lighting control requires utilizing dimmers, timers, and automatic controls via occupancy, motion sensors, photosensors, and daylighting sensors. Advanced lighting controls provide significant additional electrical savings beyond savings from LED retrofits. The General Services Administration (GSA), in a study conducted by Pacific Northwest National Laboratory (PNNL), found that after conversion to LED, light level tuning and occupancy sensing reduced lighting energy by an additional 43% (GSA 2018).

Lighting Retrofit and Relighting: A Guide to Green Lighting Solutions

This guide to retrofitting lighting for improved efficiency and performance covers technologies for interior and exterior lighting retrofits and controls. The guide also provides details on conducting lighting audits and lighting retrofit financial analyses (Benya and Leban 2011).

FGIA Skylight Selection and Daylighting Design Guide

This guide provides design criteria and considerations for skylights and top-lit daylighting design (FGIA 2020). It provides features and performance characteristics.

Occupancy Sensors. Turn on/off lights or reduce light levels based on the occupancy status of the space. Timers. Turn lights on/off based on a specific schedule, which can be controlled either manually or electronically through a BAS. Photosensors. Sense ambient light conditions to keep the lights off during daylight hours. Commonly used for exterior lighting. Daylighting Sensors. Adjust artificial lighting levels based on available natural light while maintaining desired illumination levels. Daylighting systems can be programmed to maximize daylighting at times when grid emissions are dirtiest and can scale back to allow more electric lighting when grid emissions are cleaner to reduce electrical load and contribute to overall decarbonization goals.

ANSI/IES LP-3-20+E1 Lighting Practice: Designing and Specifying Daylighting for Buildings

This standard offers guidelines and discussion for the design and performance of daylighting systems (IES 2020c). The guide includes topics related to fenestrations and glazing, lighting systems, and lighting controls for daylighting purposes.

**[Figure: LIGHTING PRACTICE: DESIGNING AND SPECIFYING DAYLIGHTING FOR BUILDINGS]**

Type: diagram

Description: This figure presents a comprehensive guide to designing and specifying daylighting for buildings, emphasizing the importance of natural light in architectural design. It outlines key considerations, such as the impact of daylight on energy efficiency and occupant well-being, and provides strategies for effective daylighting design.

Key Elements:

- **Daylighting Design Principles**: -> Outlines the fundamental principles guiding daylighting design, including maximizing natural light penetration and minimizing glare.
- **Building Orientation and Layout**: -> Discusses how the orientation and layout of a building can significantly affect daylighting, with considerations for window placement and room layout.
- **Lighting Controls and Sensors**: -> Explains the role of lighting controls and sensors in optimizing daylighting, ensuring that artificial lighting is used efficiently in conjunction with natural light.
- **Energy Efficiency and Sustainability**: -> Highlights the energy-saving potential of daylighting and its contribution to sustainable building practices, reducing the need for artificial lighting and associated energy consumption.
- **Occupant Comfort and Productivity**: -> Emphasizes the positive impact of daylighting on occupant comfort and productivity, creating healthier and more conducive work environments.

This diagram serves as a valuable resource for architects, engineers, and designers seeking to integrate effective daylighting strategies into their building designs, promoting both sustainability and occupant well-being.

CASE STUDY: McMullen County Courthouse, Texas

Lighting and window retrofits reduced the McMullen County Courthouse’s cooling load, and an assessment determined the aging heat pump units to be oversized. This case provides an opportunity to rightsize the HVAC system for the new building cooling loads.

Additionally, integrating lighting controls with building automation systems (BAS) allows further demand reduction. This integration enables coordinated control strategies, such as turning off lights in unoccupied areas when the HVAC system enters an energy-saving mode or adjusting lighting levels based on real-time occupancy data.

DOE Grid-Interactive Efficient Buildings Technical Report Series: Lighting and Electronics

**[Figure: Office of ENERGY EFFICIENCY & RENEWABLE ENERGY]**

Type: diagram

Description: The diagram shows a bar chart with two bars, one light gray and one dark gray. The light gray bar is longer than the dark gray bar.

Key Elements:

* Light gray bar -> represents the amount of energy efficiency
* Dark gray bar -> represents the amount of renewable energy

This diagram suggests that energy efficiency is a more significant contributor to reducing energy consumption than renewable energy.

This technical report is part of a larger series produced by the DOE exploring different building systems’ capabilities for grid interactivity. This report focuses on building lighting systems and other consumer electronics, including the current state and evaluation of technologies for grid interactivity (Nubbe and Yamada 2019).

### 5.1.2 Multifamily Kitchen Appliances and Cooking Systems

ENERGY STAR–rated appliances are recommended when replacing existing appliances. ENERGY STAR–certified kitchen appliances, such as refrigerators, dishwashers, and microwaves, are designed to use less energy while maintaining good performance. Decarbonizing cooking kitchen appliances and cooking systems is an important aspect of retrofitting existing multifamily buildings. While it will not reduce electrical load, switching from gas stoves to electric induction cooktops, which use magnetic fields to directly heat the cookware, can provide significant GHG emissions reductions across a multifamily property. Similarly,

# Chapter 5: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

replacing gas ovens with electric convection ovens further reduces GHG emissions from cooking in multifamily properties.

### 5.1.3 Other Systems and Plug Loads

Other systems for energy efficiency are detailed in Table 5.1:

### Table 5.1    Other Electric Load-Reduction Strategies

| System | Description | Considerations | Resources |
|---|---|---|---|
| Laundry and Clothes-Drying Systems | Heat pump dryers and ENERGY STAR–certified washers provide energy-efficiency improvements for laundry systems. Heat pump clothes dryers operate similarly to ASHPs, extracting heat from the surrounding air to dry clothes. | • Higher up-front cost • Longer drying cycles • Generally larger due to additional components for heat pump technology • Increased electrical load if switching from natural gas dryer • No vent required for dryer, condensation-based drying | • ENERGY STAR: Heat Pump Dryer (EPA n.d.-a) |
| Pools, Spas, and Hot Tubs | Solar pool heaters are a clean energy solution that can also reduce electrical load. They captur e energy from the sun to heat circulating pool o r hot tub water. Heat pump pool heaters are another efficien t solution for heating pools and hot tubs. | • Good for maintaining pool temperature • Heat pump pool heater will increase electrical load if switching from natural gas heater | • Energy Saver: Solar Swimming Pool Heaters (DOE 2023m) |
| Ice and Vending Machines | Control strategies to reduce or eliminate operating hours for ice and vending machines when not needed can reduce electrical demand. Load-shedding strategies can be used to manag e vending machine energy demand. Smar t controllers turn machines off during pea k demand periods without affecting the products’ quality or service. Upgrading to energy-efficient ice and vendin g machines that are ENERGY STAR certified als o contributes to reducing electrical demand. | • Simple retrofit options • May represent significant electrical load reduction depending on number of machines/systems |  |
| Computers and Electronics | Load shifting can be applied to computers and electronics by scheduling updates, data backups, and resource-intensive tasks to occur during off- peak hours. Power management software can automatically control and adjust the power settings of computers and peripherals based on occupanc y or usage patterns. Occupancy sensors and timer s can be used to turn off or dim lights and monitors when spaces are unoccupied for a certain period. | • Simple retrofit options • May represent significant electric load reduction depending on number of machines/systems | • Grid-Interactive Efficient Buildings Technical Report Series: Lighting and Electronics (Nubbe and Yamada 2019) |
| Other Plug and Process Loads | Strategies for plug load reduction involve the us e of power-saving modes, sleep settings, and smart power management technologies. Integrating occupancy sensors and advanced controls allow s for automatic power-down or reduced energy consumption when areas are unoccupied. An emerging opportunity with appliances and plug loads lies with grid-interactive controls. Because many plug loads are often sitting idle, they are prime candidates for adjusting to contro l a building’s electric demand in response to th e local grid. | • Stand-alone controllers are typically a simple retrofit • Grid-interactive smart con- trols may have high first cost and are best applied to a variety of building systems to be most effective (not just plug loads) • Available electric load reduction depends upon number of systems | • Assessing and Reducing Plug and Process Loads in Office Buildings (NREL 2020a) • Assessing and Reducing Plug and Process Loads in Retail Buildings (NREL 2020b) • NREL/TP-5500- 74080, Integrat- ing Smart Plug and Process Load Controls into Energy Manage- ment Information System Platforms: A Landscaping Study (Langer and Trenbath 2019) |
| Circuit Sharing Devices | Circuit sharing devices manage the multiple end uses on a given circuit so that the circuit is not overloaded. These devices are installed after th e circuit breaker and switch between loads. | • Effectively expand electri- cal capacity without requir- ing full-panel upgrades • Best to connect loads that do not operate on the same schedule or that can be interrupted without conse- quence • Current products most suit- able for multifamily appli- cations |  |
| Smart Panels | Smart panels provide similar operation at the panel level, shedding loads to manage the panel’s overall electrical load. For example, a panel with HVAC equipment and EV charging may b e programmed to shed EV charging during peak heating or cooling to serve the HVAC loads. | • Performed as an electrical panel upgrade • Higher first cost than con- ventional electrical panel • Expand electrical capacity for end uses that may avoid other electrical service upgrades |  |

## 5.2 Heating/Cooling Load Reduction: Building Envelope and Passive Systems

Building envelope changes such as window, roof, and insulation upgrades may have less attractive paybacks for energy efficiency projects, but the attributed load reductions for these measures can make HVAC electrification options more attractive in decarbonization retrofits. Strategies for reducing building heating and cooling loads contribute to reducing the needed capacity of heat pump and HVAC electrification equipment. These reductions in required heat pump capacity—along with associated size, weight, and electrical load—can be important steps for decarbonization retrofits that have space, weight, and/or electrical capacity constraints for new equipment.

# Chapter 5: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

### 5.2.1 Building Envelope

For buildings whose heating and cooling loads are driven by outdoor conditions, the building envelope is one of the first lines of defense against reducing the size and operation of the HVAC systems. Equally important are reducing ventilation loads, which is covered in Section 5.2.3.4. However, envelope measures typically have longer payback periods due to relatively higher implementation costs and lower energy cost savings. Through the lens of decarbonization, existing buildings with low-performing envelopes should evaluate improving the envelope not just as an energy efficiency component, but as a component to lower heating and cooling loads that contribute to the ability to downsize heat pump equipment as part of a decarbonization retrofit package. Contributing to smaller sized heat pump equipment also reduces electrical load where existing electrical capacity may be a concern. Reducing the size, and weight, of heat pump equipment can be a critical strategy where space and weight constraints are a concern. Common envelope improvement measures for existing buildings include installing exterior wall and roof insulation, adding window shades, minimizing the impact of thermal bridging, weatherization, upgrading windows, adding a reflective roof, and potentially incorporating the addition of PV panel (i.e., shading) upgrades. As building envelopes become more airtight, particulates and contaminants are sealed within the building, resulting in unsatisfactory indoor air quality. Ventilation systems should be matched to occupant loads, and additional ventilation may be necessary to make up for reduced infiltration from air sealing and envelope improvements. Ventilation strategies are discussed further in Section 5.2.3.4. 5.2.1.1 Insulation and Thermal Bridging

BE-Ex Solution Package: Building Envelope

The Building Energy Exchange (Be-Ex), a building decarbonization hub for New York City, has published a short guide to efficient building envelope solutions. The building envelope guide is part of a larger group of six documents being compiled from the Anatomy of an Energy Efficient Building exhibition at the BE-Ex resource center in New York City (BE-Ex 2023c).

Enhancing insulation levels in walls, roofs, and floors helps improve energy efficiency by reducing heat transfer and minimizing the need for heating and cooling. Minimizing or eliminating thermal bridges through techniques like installing thermal breaks or continuous insulation helps maintain a more efficient building envelope. A challenge for existing building retrofits can be adding insulation and addressing thermal bridging with minimal disruption to existing facades (interior and exterior).

Exterior insulation and finish system (EIFS) panels can be a good retrofit option for adding installation and addressing thermal bridging in existing buildings. As the name implies, EIFS are installed from the exterior of the building and avoid removing interior finishes and surfaces. Exterior insulation makes EIFS less disruptive to building occupants and can be more cost effective than altering interior surfaces. The case study for the Heritage below provides an example where two multifamily towers are retrofitted with EIFS panels as part of a larger decarbonization retrofit. The EIFS panels reduce heating and cooling loads for the towers as a key step toward future heat pump upgrades for the units’ electric baseboard heaters and sleeve AC systems. Prefabricated panels are another option for insulating existing buildings. Similar to EIFS, prefabricated panels can be installed on the exterior of the building, reducing the disruption to building occupants. Prefabricated panels also include the benefits of incorporating windows, mechanical equipment cutouts, and electrical systems with an exterior cladding and weatherproof seals.

**[Figure: Typical EIFS detail]**

Type: diagram

Description: The diagram illustrates a typical Exterior Insulation and Finish System (EIFS) detail, showcasing its various components and their arrangement. It provides a visual representation of how these components work together to form a complete EIFS system.

Key Elements:

- Substrate -> The base material to which the EIFS is applied.
- Adhesive -> The substance used to bond the insulation board to the substrate.
- Drainage Plane -> A layer that allows water to drain away from the wall.
- Insulation Board -> Provides thermal insulation to the building.
- Reinforcing Mesh -> Adds strength and durability to the EIFS.
- Base Coat -> The layer applied over the reinforcing mesh.
- Primer -> Prepares the surface for the finish coat.
- Finish Coat -> The outermost layer, providing color and protection.

This diagram is essential for understanding the composition and functionality of an EIFS system, highlighting its importance in building construction for energy efficiency and weather resistance.

CASE STUDY: The Heritage, New York

The case study for the Heritage provides an example of an EIFS and insulated panel retrofit. One of the buildings in the portfolio is retrofitted with prefabricated panels that include insulation and new, more efficient windows. The remaining two towers in the portfolio are retrofitted with EIFS. For this particular retrofit project, the PTAC units are being replaced with PTHP units, and the panelized construction provides new cutouts sized for the PTHP and integrated electrical for supporting the PTHP units, thereby paving the path for future upgrades that may require additional electrical capacity.

#### 5.2.1.2 Air Sealing

Sealing air leaks through gaps or cracks in the building envelope and at fenestration seals is another key strategy for reducing the building’s heat loss or gain and enhances the operation of HVAC systems. A comprehensive building air leakage assessment, such as a blower door test, can help pinpoint areas of air leakage and guide air-sealing efforts. Sealing air leaks can be achieved through various techniques such as caulking, weatherstripping, and using appropriate sealants or gaskets. Air sealing the HVAC ducting also improves the heating and cooling performance for HVAC systems. Sealing leaks in ductwork contained in ceilings and walls ensures that the conditioned air

# Chapter 5: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

is delivered to the space rather than being lost. Aeroseal sealing technology is one solution that can be used for retrofit projects and provides a unique method for sealing ducts and envelopes. Depending on the age of the building and ductwork, sealing leaks may represent a significant reduction in heat loss that can contribute to reducing the required size of heat pumps to condition spaces. At minimum, a visual inspection should be performed to estimate how well (or poorly) the supply air system has been sealed. It is not uncommon for older fans to have significant leakage at their flexible canvas connections. If significant leakage is suspected anywhere in the system, hiring a test-and-balance (TAB) contractor to estimate system duct system (and air control damper) leakage could be money well spent. 5.2.1.3 Window Replacement, Shading, and Films

Upgrading windows to high-performance, energy-efficient models with a low U-factor can significantly improve thermal insulation, reducing heat transfer through glazing and better maintaining consistent indoor temperatures, thereby reducing heating and cooling loads. Double or triple glazing, lowemissivity (low-e) coatings, and gas fills between panes enhance insulation properties while still allowing for natural light transmission. Where full window replacement is challenging or costly, there are several more costeffective options for retrofits:

Resources: Energy-Efficient Windows

Some available resources for understanding and evaluating options for energy-efficient windows include:

Carmody, J., and K. Haglund. 2012. Measure Guideline: Energy-Efficient Window Performance and Selection. Washington, D.C.: U.S. Department of Energy’s Building Technologies Program. https:// www.nrel.gov/docs/fy13osti/55444.pdf. DOE. 2010. Guide to Energy-Efficient Windows. Washington, D.C.: U.S. Department of Energy. https://www.energy.gov/sites/prod/files/ guide_to_energy_efficient_windows.pdf. EWC. 2011. Energy-Efficient Windows for Mid- & High-Rise Residential Buildings. Efficient Windows Collaborative. Greenbelt, MD: Efficient Windows Collaborative. https://efficientwindows.org/wp-content/ uploads/2020/10/MidHighRiseResidential.pdf.

- Adding secondary glazing to the interior or exterior of existing windows improves the window performance and can decrease infiltration.
- Insulated glass unit replacements require replacing only the glazing and not the window frame.
- Low-e films reflect infrared heat back into the building during the heating season and reduce heat gain in the cooling season. When applying low-e films, the solar heat gain coefficient (SHGC) needs to be selected properly based on the climate zone specifics to reduce the cooling or heating loads, respectively.

CASE STUDY: McMullen County Courthouse, Texas

Lighting and window retrofits reduced cooling loads, and an assessment determined that the aging heat pump units are oversized. This provides an opportunity to rightsize the HVAC system for the new building cooling loads.

CASE STUDY: Ken Soble Tower, Canada

The case study for Ken Soble Tower provides an example of a retrofit that includes EIFS along with triplepane window upgrades. These upgrades were made as first steps in a larger retrofit that includes upgrades to space heating and cooling systems.

Shading devices such as awnings, overhangs, fins, and exterior blinds help block direct sunlight and reduce solar heat gain and glare. When strategically designed based on sun position throughout the year for the project site and positioned correctly on windows, these devices can provide shade during peak solar exposure (i.e., when the sun is high in the sky), thus reducing cooling loads. Then during the winter, when the sun is lower in the sky, direct sunlight can provide appreciative solar gains and reduce the heating load (for climates with higher heating degree days). 5.2.1.4 Cool and Green Roofs

For cooling-dominated climates, implementing cool roofs can help to reduce solar absorption through the roof and contributes to cooling load reduction. However, implementing a cool roof will increase the heating load in winter months. In climates with moderate to high heating seasons, the impact of a cool roof on heating load will increase the size of heat pump needed and likely negate any benefit during cooling season. Hourly analyses of heating and cooling loads with a cool roof will offer data to determine whether there are benefits to installing a cool roof or whether the negative impacts to heating are prohibitive. Green roofs, or rooftop gardens, are another option but are likely difficult to implement in a retrofit. The vegetative and soil layer grown on the building roof provides a form of insulation that can help reduce the amount of heat transfer through the roof. In addition, because they include a vegetative layer, green roofs can also provide a form of carbon sequestration within the building structure. When accounting for the carbon life cycle of materials for a green roof system, an extensive green roof can provide a carbon payback between 5.8 and 15.9 years (Kuronuma et al. 2018). While green roof systems reduce heating and cooling loads, they typically require a significant rooftop surface area to provide effective reductions in heating and cooling loads. They will sacrifice space for rooftop mechanical equipment and renewable energy systems, like PV arrays. As a note, there are integrated solar green roof technologies available that demonstrate enhanced cooling, maximized solar output while providing stormwater retention and detention capabilities. Even still, the trade-off between required roof space and benefits from green roofs typically makes them a lower priority compared to other aspects of a decarbonization retrofit. In addition, the vegetation, soil, water, and other green roof system components represent an increased structural load on the roof that may require structural upgrades that are cost prohibitive. ASTM E2397 provides the procedure for determining the loads of a green roof for evaluating whether the existing roof structure can support the installation.

Green Roof Energy Calculator

The Green Roof Energy Calculator developed by researchers at Portland State University, University of Toronto, and Green Roofs for Healthy Cities can help compare the annual energy performance of a building with a green roof against one with either a dark or white roof. It incorporates building location data along with square footage in addition to roof information to estimate the amount of energy savings (Green Roofs for Health Cities n.d.).

### 5.2.2 Passive Strategies

Passive strategies offer a variety of unique approaches to decarbonizing buildings by reducing reliance on mechanical heating and cooling systems. Table 5.2 lists some potential passive strategies that may be incorporated into a decarbonization retrofit. While these and other passive systems can be applied to retrofitting existing commercial and multifamily buildings, the feasibility and effectiveness of each system may vary depending on the specific building characteristics and requirements.

# Chapter 5: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

### Table 5.2    Passive Heating and Cooling Strategies

| System | Description | Considerations | Resources |
|---|---|---|---|
| Passive Solar | There are three main types of passive sola r systems: direct gain, indirect gain, and isolate d gain. Passive solar approaches can includ e solar porches, sunspaces and greenhouses, wall collectors, thermosiphoning wall panels, an d night insulation. | • Difficult to incorporate into existing building without changes to facade • Dependent upon building orienta- tion • Best used in cold climates with high number of clear, sunny days • Long payback | • Whole Building Design Guide: Pas- sive Solar Heating (Fosdick 2016) |
| Phase-Change Materials | Phase-change materials (PCMs) are substances that absorb and release heat during phase transitions, such as from solid to liquid and vice versa. Incorporating PCMs into buildin g elements such as walls or ceilings can help regulate indoor temperatures by absorbing excess heat during the day and releasing it a t night, reducing the need for mechanical cooling or heating. PCMs can be incorporate d into existing buildings during retrofit projects, particularly in walls and ceilings. | • Best suited for dry climates with diurnal temperature swings for heat storage and release • Some require careful installation to avoid rupturing PCM packaging • Storage times and operating tem- peratures vary by manufacturer • May be incorporated into insulation, drywall panels, etc., for retrofit | • U.S. Army Corps of Engineers: Tech- Note 27 Phase- Change Materials (USACE 2016) |
| Earth Tubes | Earth tubes, also known as earth-air hea t exchangers, constitute a passive strategy tha t use underground pipes to pre-conditio n incoming air by utilizing the stabl e temperature of the earth. They are non-electric, passive heating and cooling systems tha t provide precooling in hot climates and preheating in cold climates, reducing th e energy required for mechanical cooling or heating. | • Require excavation for installation, resulting in high first cost • Need careful planning and design adjustments to accommodate the underground pipe network and con- nect it to the existing ventilation system • Best suited for drier climates • Long payback | • Natural Resources Canada: Earth to Air Thermal Exchanger (EATEX): Design Principles and Con- cept Design Tool (NRC 2021) |
| Wind Catchers | Wind catchers are architectural features tha t harness natural wind movement to provide passive cooling and ventilation. They can b e designed to direct airflow into the building, enhancing natural ventilation and reducing th e need for mechanical cooling. | • Require suitable wind patterns for effective ventilation • Design should consider factors such as structural stability, wind direc- tion, and obstruction-free airflow • Best for cooling applications in drier climates | • “Windcatchers and their Applications in Contemporary Archi- tecture” (Sangdeh and Nasrollahi 2022) |
| Natural Ventilation | Natural ventilation reduces HVAC loads b y utilizing natural air movement throug h openings such as operable windows, vents, o r operable skylights to provide fresh air and remove stale air. Natural ventilation ca n reduce reliance on mechanical systems, resulting in energy savings. | • Depends on building design, fenes- trations, climate, and occupant pref- erences, which might be difficult/ impossible to address in retrofits | • Natural Ventilation Review and Plan for Design and Analysis Tools (Emmerich et al. 2001) • Whole Building Design Guide: Natu- ral Ventilation (Walker 2016a) |
| Solar Chimney | A unique application of natural ventilation, solar chimneys use solar heat gain to create a stack effect, reducing the need for mechanica l cooling. | • Most effective in sunny climates with significant temperature variations and are beneficial for buildings with high internal heat gains. • Difficult retrofit because of the depen- dency upon building internal layout to allow sufficient airflow through spaces and out the chimney. | • Solar Chimney Applications in Buildings for Engi- neers and Scientists (Shi and Zhang 2023) |

### 5.2.3 HVAC Optimization

Optimizing HVAC system operation includes various methods to reduce electrical and thermal loads that contribute to available electrical capacity and reduced heating and cooling loads for future electrification of HVAC systems. Optimization strategies include:

- Existing building commissioning (EBCx)
- Increased efficiency of fan and pump motors
- HVAC energy recovery
- Ventilation methods that provide good IAQ and reduce ventilation loads
- Controls retrofits, including optimized sequences of operation

#### 5.2.3.1 Existing Building Commissioning (EBCx)

The existing building commissioning (EBCx) process is used by owners and/or facility decision-makers to match the operation of their facilities and systems to their specific current facility requirements (CFR) and meet applicable jurisdictional requirements. The process establishes facility operation baselines and performance goals and compares existing conditions and operations to post-implementation goals, including decarbonization. EBCx can provide significant improvements in building performance, resulting in improved performance of energy consuming systems and lower GHG emissions. EBCx also consistently provides a quick return on investment. By adjusting/improving current operating control strategies, EBCx is a good early move for decarbonization. ANSI/ASHRAE Standard 230, Commissioning Process for Existing Systems and Assemblies, is an organized, quality-oriented process for planning, assessing, investigating, implementing, verifying, and documenting activities to improve the performance of facilities, systems, and assemblies to meet defined operational requirements and criteria. ASHRAE Standard 230 establishes the minimum requirements for commissioning an existing building while allowing the owner to define the specific scope of work and project budget (ASHRAE 2022b). Supporting technical guidelines for the existing building commissioning process include:

ASHRAE Guideline 1.2, Technical Requirements for the Commissioning Process for Existing HVAC&R Systems and Assemblies

This guideline outlines requirements for the application of the commissioning process (Cx) described in ASHRAE Guideline 0.2 to existing heating, ventilating, air-conditioning, and refrigerating (HVAC&R) systems and assemblies (ASHRAE 2019b).

ASHRAE Guideline 1.2-2019

Technical Requirements for the Commissioning Process for Existing HVAC&R Systems and Assemblies

Approved by ASHRAE on January 7, 2019.

© 2019 ASHRAE ISSN 1049-894X

- ASHRAE Guideline 0.2, Commissioning Process for Existing Systems and Assemblies, details the commissioning process for generic existing systems and assemblies;
- ASHRAE Guideline 1.2, Technical Requirements for the Commissioning Process for Existing HVAC&R Systems and Assemblies, provides specific HVAC&R technical commissioning information;
- ASHRAE Guideline 1.3, Application of the Commissions Process to Building Operation and Maintenance Training, provides information on training of O&M personnel; and
- ASHRAE Guideline 1.4, Preparing Systems Manuals for Facilities, provides advice on development that applies to all building systems.

# Chapter 5: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

These supporting guidelines are closely coordinated with process requirements in both Standard 230 and Guideline 0.2, which can be used together or in any combination to accommodate varying owner requirements. EBCx can, however, be implemented successfully without the supporting technical guidelines. 5.2.3.2 Fan and Pump Motor Efficiency

Motor and drive selection is a key to HVAC fan and pump efficiency. Where commercial fans and blowers rely on oversized single-speed motors that have been designed to meet maximum system demand, retrofitting with more efficient motor and drive systems reduces electrical demand. Direct-drive motors, in which fan wheels are connected directly to the motor shaft, are an efficient replacement to traditional belt-driven fans. Belt-driven fans can have between 10% and 30% efficiency loss, whereas direct-drive fans do not suffer power transmission losses (Albers and Ellis 2023). Replacing less efficient single-speed motor applications with integrated motor and control systems (IMACS) and other power-drive systems (PDS) can reduce electric demand for HVAC motors. Another option is electronically commutated motors (ECM), which combine a brushless motor with on-board electronics that convert AC power to DC for synchronous operation in a compact package. ECMs offer higher efficiency and more precise control over a wide range of speeds than typical AC motors paired with variable-frequency drives. These systems all improve HVAC motor efficiency by better matching motor output to heating and cooling demand. Improved efficiency of AHU fan motors for distributing air reduces the electrical demand of the HVAC system and can contribute to electrical load availability for installing central heat pump equipment serving air-distribution systems. 5.2.3.3 HVAC Airside Energy Recovery

HVAC airside energy recovery refers to the capture and reuse of conditioned ventilation air to reduce space cooling or heating loads. Airside energy recovery is common for various HVAC systems, especially those that require large ventilation loads. Heat can be recovered from exhaust air streams as shown in Figure 5.2, from the heat rejected by the refrigeration cycle, or from waste or process heat. All these systems contribute to electrification, as they reduce heating loads, which can also reduce heating system capacity requirements. In a cooling-dominated climate, heat may be rejected from supply air streams to exhaust air streams, “recovering” cooling for the supply air and reducing the HVAC equipment cooling load. Passive energy-recovery strategies, such as exhaust air energy recovery, are more effective at reducing peak loads than active heat recovery options, such as refrigeration and process heat rejection, which require mechanical system operation and contribute to the building’s electrical demand.

**[Figure: Example of exhaust air heat recovery]**

Type: diagram

Description: The diagram illustrates a heat recovery system for exhaust air, showcasing its components and functionality. It highlights the process of capturing heat from exhaust air and utilizing it to pre-heat supply air, thereby enhancing energy efficiency.

Key Elements:

- **Exhaust Air In**: This component represents the entry point of exhaust air into the system, where it carries heat that would otherwise be lost.
- **Supply Air In**: This element signifies the intake of fresh air that needs to be heated before being supplied to the space.
- **Exhaust Air Out**: This part of the system is responsible for expelling the cooled exhaust air after its heat has been recovered.
- **Supply Air Out**: This component delivers the pre-heated supply air to the space, utilizing the recovered heat from the exhaust air.

This diagram effectively demonstrates how heat recovery systems can optimize energy usage by reusing waste heat from exhaust air to warm incoming supply air.

Energy recovery in WSHP systems is covered in Chapter 6, Section 1.1.3.5, and energy recovery with simultaneous and non-simultaneous heating and cooling using TES is covered in Section 7.5 in Chapter 7. Heat Recovery Ventilators (HRVs)

HRVs recover sensible heat and are characterized by their ability to effectively transfer heat from the exhaust air stream to the supply air stream. Best-practice systems have sensible heat recovery effectiveness levels of 70%–75% or greater and enthalpy recovery effectiveness of over 60% (ASHRAE 2020b). HRVs can use wasted heat from data centers, commercial refrigeration systems, and other constant heat sources within the building to provide an uninterrupted heat source throughout the year. These systems can allow a bypass of the heat recovery device when outdoor air conditions call for free cooling, thereby reducing fan pressure drop losses. Energy-Recovery Ventilators (ERVs)

ERVs recover both sensible and latent heat by transferring heat and moisture between incoming and outgoing air streams to reduce heating and cooling loads. This method is particularly effective in climates with extreme temperatures. ERV systems exchange the energy contained in air that would normally be exhausted out of a building or conditioned space and recover it to preheat or precool the incoming outdoor air. During cooling season, an ERV system precools and dehumidifies the incoming air; during heating season, the system humidifies and preheats the incoming air (Dieckman 2008). ERV systems are HVAC design strategies that help meet ventilation and energy standards, improve indoor air quality, and reduce HVAC loads, all of which contribute to reduced HVAC capacity. ERV systems help to maintain a 40%–50% indoor relative humidity in a variety of conditions (ASHRAE 2020b). Run-Around Coils

Although they are not as common as HRVs or ERVs, run-around coils are another method for energy recovery in HVAC airside systems. Run-around coils allow for energy recovery between air streams that are completely separated from each other. Run-around coil systems can also integrate active heat recovery, such as from refrigeration cycles, for increased heat recovery when outdoor air temperatures are mild. Another design option to improve heat recovery in run-around coil loops is the use of a water-to-water heat pump between the coils, which can increase heat recovery potential through increased ΔT and also potentially latent energy through freezing coils. Heat Recovery in a Retrofit Project

HRVs and ERVs can be installed on existing air handlers during a retrofit, incorporated into replacement units, or installed as stand-alone HRV/ERV units. ERVs are also commonly incorporated into dedicated outdoor air systems (DOAS), whether existing or installed as part of a decarbonization retrofit package such as one employing VRF systems without ventilation. It is also common to replace an old enthalpy wheel with a new one without replacing the entire system.

# Chapter 5: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

Energy-recovery retrofits have many benefits, but they also come with the penalty of cost, increased pressure drop, and increased embodied carbon. These retrofits should be modeled for energy recovery potential and associated energy cost and GHG emissions payback. Modeling of ERV retrofits also should evaluate configurations with and without bypasses to determine whether they should be added to the system. Solar Preheating for Ventilation Distinct from mechanical HVAC airside heat recovery, solar preheating for ventilation air is a passive strategy that captures solar energy to preheat the supply air for building ventilation systems. Solar thermal collectors capture the sun’s heat energy to warm the incoming fresh air before it enters the building’s ventilation system. Solar preheating is a much less common strategy for retrofits and is most applicable in climates that receive significant amounts of direct sunlight during the heating season. 5.2.3.4 Ventilation Methods

BE-Ex Tech Primer: Dedicated Outdoor Air Systems (DOAS) and Energy Recovery Ventilators (ERV)

This tech primer gives an overview for upgrading commercial buildings with a DOAS and ERV system (BE-Ex 2021). These systems can improve ventilation system efficiency and reduce the size of associated heating and cooling equipment. They can be paired with electrified HVAC solutions, such as split systems and VRF systems, that condition spaces independent of ventilation.

tech primer Dedicated Outdoor Air Systems (DOAS) and Energy Recovery Ventilators (ERV) Controlled ventilation for enhanced comfort and savings.

tech overview applicable building types commercial implementation anytime, at midcycle or refinance fast facts

- reduces GHG emissions
- improves air quality
- reduces heating and cooling loads
- reduces maintenance costs
- reduces utility costs

costs & benefits*

GHG Savings

Tenant Experience Improvements

Utility Savings

New York Botanical Garden, Marlon Co. Photography

Capital Costs

Maintenance Requirements

*ratings are based on system end use, see back cover for details.

To get help today: call (212) 656-9202 or visit nyc.gov/Accelerator

Ventilation strategies can be used to reduce HVAC heating and cooling loads while maintaining suitable indoor air quality. Building ventilation is critical to the health of building occupants as it controls humidity; reduces indoor air contaminants, airborne diseases, cleaning and other chemicals, miscellaneous odors, and off-gassing of building materials and furniture; and keeps the building positively pressurized to minimize infiltration. Compliance with ASHRAE Standards 62.1 and 62.2 is crucial to ensuring that ventilation methods meet the necessary requirements for IAQ and energy efficiency while aligning ventilation with occupancy patterns. Beyond the ventilation requirements of Standards 62.1 and 62.2, ASHRAE introduced Standard 241, Control of Infectious Aerosols, to establish requirements for minimizing the risk of disease transmission. This standard introduced the concept of equivalent clean airflow (ECA) to determine the necessary amount of clean air needed to reduce the risk of long-range airborne transmission. ECA is a new and powerful concept in indoor air standards because it provides users flexibility to embrace approaches that are less energy intensive, such as layered strategies to improve IAQ through ventilation, filtration, air cleaning, and occupancy controls. For example, increasing outdoor air above the levels required for normal operation may be a poor solution because of the cost of conditioning more outdoor air or if outdoor air quality is poor where the building is located.

Ventilation strategies to reduce HVAC heating and cooling loads and meet occupant ventilation requirements include: Demand-Controlled Ventilation (DCV)

ASHRAE Standards 62.1, 62.2, and 241

ANSI/ASHRAE Standards 62.1 and 62.2 are the recognized standards for ventilation system design and acceptable indoor air quality (IAQ). Expanded and revised for 2022, both standards specify minimum ventilation rates and other measures to minimize adverse health effects for occupants (ASHRAE 2022c, 2022d).

ANSI/ASHRAE Standard 62.1-2022 (Supersedes ANSI/ASHRAE Standard 62.1-2019) Includes ANSI/ASHRAE addenda listed in Appendix Q Ventilation and Acceptable Indoor Air Quality

Demand-controlled ventilation (DCV) facilitates the adjustment of outdoor airflow when the number of occupants falls below the design occupancy level. This adjustment is made possible through real-time monitoring of occupancy, often utilizing CO2 sensors. It is important to note that, while DCV optimizes ventilation and leads to decreased energy consumption, it does not diminish the design load. DCV proves most beneficial in densely populated areas and in large spaces with sporadic occupancy, such as conference rooms and auditoriums. Performance-Based Ventilation Design

See Appendix Q for approval dates by ASHRAE and the American National Standards Institute.

ANSI/ASHRAE Standard 62.2-2022 (Supersedes ANSI/ASHRAE Standard 62.2-2019) Includes ANSI/ASHRAE addenda listed in Appendix E Ventilation and Acceptable Indoor Air Quality in Residential Buildings

© 2022 ASHRAE ISSN 1041-2336

PDF includes hyperlinks for convenient navigation. Click on a reference to a section, table, figure, or equation to jump to its location. Return to the previous page via the bookmark menu.

See Appendix E for approval dates by ASHRAE and by the American National Standards Institute.

© 2022 ASHRAE ISSN 1041-2336

ASHRAE Standard 241, Control of Infectious Aerosols, establishes minimum requirements aimed at reducing the risk of disease transmission through exposure to infectious aerosols in new buildings, existing buildings, and major renovations. The implementation of this standard brings numerous benefits to occupants and promotes healthier environments (ASHRAE 2023f).

PDF includes hyperlinks for convenient navigation. Click on a reference to a section, table, figure, or equation to jump to its location. Return to the previous page via the bookmark menu.

ASHRAE Standard 241-2023 Control of Infectious Aerosols

Approved by the ASHRAE Standards Committee on June 24, 2023.

© 2023 ASHRAE ISSN 1041-2336B

This standard includes links to online supporting files.

Standard 62.1 includes two methods for calculating minimum outdoor air to maintain acceptable indoor air quality: the Ventilation Rate Procedure (VRP) and the Indoor Air Quality Procedure (IAQP). When decarbonization is the goal, there are many advantages to using the IAQP instead of the VRP. This is because the IAQP allows designers to replace a portion of the outdoor air requirement under the VRP with cleaned, recirculated indoor air without compromising indoor air quality. This approach is usually more energy efficient than a dilution-only strategy using the VRP due to less conditioning of hot and cold outdoor air, which also may be polluted. Additional benefits of using the IAQP include reducing HVAC design loads, which allows for equipment downsizing and associated cost reductions for new HVAC equipment, including heat pumps and associated electrical infrastructure, and for improved building resilience to polluted outdoor air, such as industrial pollution and wildfires. In 2022 and 2023, ASHRAE made a number of updates to the IAQP to make it more prescriptive and therefore easier and less risky to apply. These updates include the publication of Standard 62.1 Calculators, an IAQP calculator that can be downloaded from ASHRAE’s website (ASHRAE 2024). Variable Mechanical Ventilation

Standard 62.2 allows for variable mechanical ventilation rates based on various methods of ensuring that the average ventilation rate over a given period of time meets the standard. This strategy allows the ventilation system to potentially be used as a load that can be shifted. For example, a system could control to reduce the ventilation rate during peak GHG emissions periods and increase ventilation rates at low GHG emissions periods. 5.2.3.5 Controls Retrofit and Optimized Sequences of Operation

Many older buildings have pneumatic controls or older direct digital controls (DDC) with limited capabilities. A decarbonization retrofit is a good time to consider a controls upgrade, including optimized sequences of operation. More details about sequences of operation are provided in Sec-

# Chapter 5: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

tion 1.2 in Chapter 6. Both upgrading the controls and adjusting operation sequences can reduce peak load and building energy use. A California Energy Commission-funded study indicated dramatic heating savings through controls retrofits (CEC 2022).

CASE STUDY: East Palo Alto Government Center, California

The case study for the East Palo Alto Government Center in California performed electrical demand reduction measures, including a pneumatic to DDC retrofit together with ASHRAE Guideline 36 sequences. These measures, along with an LED and lighting controls retrofit, reduced electrical demand to accommodate the installation of AWHPs to replace the chiller/boiler plant.

This chapter discusses approaches and options for partial and full electrification of common HVAC systems in existing buildings and provides several case studies to demonstrate the approach to decarbonizing these systems. Retrofitting fossil-fuel-based HVAC systems with heat pumps poses several challenges, such as higher operating temperatures, conduit and electrical panel capacity limitations, compatibility with the existing system and components, and space and accessibility constraints, among others. Because most building cooling systems, such as direct expansion (DX) air conditioners or chillers, are electric, building heating systems are the primary focus for building electrification. Based on the 2018 Commercial Buildings Energy Consumption Survey (CBECS), the majority of commercial building heating systems are packaged units with either gas furnaces or electric resistance heating coils, which include PTAC units and packaged rooftop units (RTUs). Furnaces and boilers make up another significant portion of heating equipment types. Details from the 2018 CBECS data are outlined below and shown in Figure 6.1.

**[Figure: Total commercial buildings and floor space by heating equipment, 2018 percentage]**

Type: chart

Description: This chart compares the percentage of total commercial buildings and floor space by heating equipment in 2018. The key insight is that packaged heating units are the most common heating equipment, accounting for 40% of total commercial buildings and 50% of total commercial floor space.

Data Representation:

* Packaged heating units: 40%
* Furnaces: 30%
* Individual space heaters: 20%
* Boilers: 10%
* Heat pumps: 5%
* Duct reheat: 5%
* District heat: 5%

Metric: Percentage of total commercial buildings and floor space

Chart Type: Bar chart

Units: Percentage

Chart Generation Hint:

* X-axis: Heating equipment
* Y-axis: Percentage of total commercial buildings and floor space

Structured Data (Machine Readable):

{
  "chart_type": "bar",
  "metric": "percentage",
  "units": "percentage",
  "data": {
    "Packaged heating units": 40,
    "Furnaces": 30,
    "Individual space heaters": 20,
    "Boilers": 10,
    "Heat pumps": 5,
    "Duct reheat": 5,
    "District heat": 5
  }}
}

- Packaged heating units (including PTACs and packaged RTUs) were used in 37% of buildings, or 50% of total floor space.
- Furnaces were used in 27% of buildings, but these buildings only accounted for 18% of total floor space.
- Although boilers were used in only 12% of buildings, these buildings accounted for 30% of total floor space.

Table 6.1 Common HVAC Systems and Decarbonization Retrofit Options

Packaged terminal air conditioner (PTAC) units

Split-system AC with furnace

Common Existing HVAC Systems: Fossil-Fuel-Fired Heating System

## 6.1 HVAC System Retrofits

Medium Commercial

Medium Commercial

Small Commercial

Small Commercial

Hotel/Lodging

Hotel/Lodging

Gas Furnace Retrofits

Multifamily

Multifamily

Building Type

Packaged rooftop unit (RTU) with furnace

Medium Commercial

Small Commercial

Large Commercial

### Table: Data Table

| Building Type | Common Existing HVAC Systems: Fossil-Fuel-Fired Heating System | Common Existing HVAC Systems: Distribution and Terminal Equipment | Retrofit Options | Key Considerations |
|---|---|---|---|---|
| Gas Furnace Retrofits |  |  |  |  |
| Small Commercial Medium Commercial Multifamily Hotel/Lodging | Packaged terminal air conditioner (PTAC) units | N/A | Full Electrification: Packaged terminal heat pump (PTHP) units | • Review manufacturer’s designed performance for cold climates (temperatures <10°F [–12°C]) • Account for unit defrost cycle during heating opera- tion • Confirm available electrical capacity to support heat pump |
| Small Commercial Medium Commercial Multifamily Hotel/Lodging | Split-system AC with furnace | Single-zone or single-duct terminal units | Partial Electrification: • Retain furnace for supplemen- tal heating or • Dual-fuel heat pumps Full Electrification: • Ductless or ducted split heat pump with complete removal of furnace |  |
| Small Commercial Medium Commercial Large Commercial | Packaged rooftop unit (RTU) with furnace | Single zone | Partial Electrification: • In cold climates, may consider dual-fuel heat pump RTU Full Electrification: • Heat pump RTU or • Variable refrigerant flow (VRF) system | • Review manufacturer’s designed performance for cold climates (temperatures <10°F (–12°C)); may consider using the existing furnace or installing dual-fuel heat pumps for these applications • Account for unit defrost cycle during heating opera- tion • Confirm available electrical capacity to support heat pump • Evaluate GHG emissions from estimated refrigerant leaks for system, particularly for VRF systems • For RTUs with zone reheat, evaluate sizing of RTU for heating with heat pump vs. zone reheat to opti- mize: • Efficiency • GHG emissions • Energy cost • RTU size for roof space and weight capacity |
|  |  | • Single-duct termi- nal units with zone reheat • Dual-duct termi- nal units |  |  |
| Central Boiler Retrofits |  |  |  |  |
| Small Commercial Medium Commercial Large Commercial | VAV reheat with packaged RTUs or Air-handling unit (AHU) | Single-duct terminal units with zone reheat | Partial Electrification: • Packaged rooftop heat pumps or centralized heat pumps paired with condensing boiler for peak heating days, or • Heat recovery chiller (optional TES) Full Electrification: • Air-to-water heat pump to replace boiler (optional TES), or • Ground-source heat pump (GSHP), or • VRF system | Partial Electrification: Evaluate sizing of heat pump vs. condensing boiler to optimize: • Efficiency • GHG emissions • Energy cost • RTU size for roof space and weight capacity • Electrical capacity Full Electrification: • Perform heating system temperature stress test to determine minimum HHW operating temperature to meet loads • Confirm available electrical capacity to support heat pump • For air-to-water heat pumps, review manufacturer’s designed performance for cold climates (tempera- tures <10°F [–12°C]) to determine need for supple- mental heating • Account for unit defrost cycle during heating opera- tion • Evaluate GHG emissions from estimated refrigerant leaks for system, particularly for VRF systems • TES used to shift peak load using heat recovery (morning warm-up) can be paired with AWHP and/ or heat recovery chillers • Evaluate HHW reheat or four-pipe systems for heat recovery between zones |
|  |  | Dual-duct distribution | Same as single-duct AHU but may consider retaining AC unit for cold deck and grouping heat pumps to serve hot deck (and cold deck) |  |
| Medium Commercial Large Commercial Multifamily Hotel/Lodging | Two-pipe or four-pipe fan coil units (FCU) with boiler | Local FCU | Partial Electrification: • Heat pumps paired with con- densing boiler or other high- efficiency boiler for peak heat- ing days or • Heat recovery chiller (optional TES) Full Electrification: • Air-to-water heat pump to replace boiler (optional TES), or • GSHP, or • VRF system |  |
| Medium Commercial Large Commercial Multifamily Hotel/Lodging | Water-source heat pumps (WSHPs) with boiler | N/A | Partial Electrification: • Condensing boiler or other high-efficiency boiler for peak heating days Full Electrification: • Air-to-water heat pump (TES) or • GSHP | • Confirm available electrical capacity to support heat pump • TES used to shift peak load using heat recovery (morning warm-up) can be paired with AWHP and/ or heat recovery chillers |

Table 6.1 Common HVAC Systems and Decarbonization Retrofit Options

Common Existing HVAC Systems: Distribution and Terminal Equipment

Two-pipe or four-pipe fan coil units (FCU) with boiler

Common Existing HVAC Systems: Fossil-Fuel-Fired Heating System

VAV reheat with packaged RTUs or Air-handling unit (AHU)

Medium Commercial

Medium Commercial

Small Commercial

Large Commercial

Large Commercial

Central Boiler Retrofits

Multifamily

Building Type

Water-source heat pumps (WSHPs) with boiler

Medium Commercial

Large Commercial

Hotel/Lodging

Hotel/Lodging

Multifamily

### 6.1.1 Gas Furnace Retrofits

There are many types of HVAC equipment that have a gas-fired furnace section. This section covers the most common equipment types with gas furnaces and options for full or partial electrification of those systems. 6.1.1.1 Packaged Terminal Air Conditioner (PTAC) Retrofits

Packaged terminal air conditioner (PTAC) units and packaged terminal heat pump (PTHP) units provide conditioned air directly to a room, typically one that has exposure to the exterior of the building. These are most applicable to multifamily and hotel/lodging, such as shown in Figure 6.2, where they represent a relatively inexpensive HVAC package that provides ease of maintenance and replacement. PTAC units also may be used in some small and medium office buildings. Many PTAC units use electric heating coils to provide heating units, though natural-gasfired PTAC units are available. Whether using electric resistance or gas-fired heating, there is an opportunity to reduce facility GHG emissions through retrofitting PTAC units with PTHP units. Like PTACs, PTHPs offer a relatively inexpensive HVAC package that provides ease of maintenance and replacement, simple individualized comfort control for the occupants, and less intensive installation requirements where no ductwork or piping is needed for installation and operation. While installations are less intensive, a PTHP retrofit is not simply a like-for-like replacement. The design must consider the higher load between cooling and heating and the design temperatures for sizing the PTHP. For climates that are heating dominant, a decision point is whether to include supplemental electric resistance heating to meet the heating load. This decision is influenced by:

**[Figure: Packaged Terminal Unit]**

Type: diagram

Description: The figure shows a packaged terminal unit, which is a type of heating and cooling system commonly used in commercial buildings. The unit is mounted on the wall and has a grille on the front for airflow.

Key Elements:

* Grille -> allows air to enter and exit the unit
* Wall mount -> secures the unit to the wall
* Control panel -> allows users to adjust temperature settings and other functions

This diagram provides a clear visual representation of a packaged terminal unit, highlighting its key components and features.

- Climate and design heating requirements
- Available electrical capacity
- Electric demand utility costs
- Marginal emissions when electric resistance heating would be used
- PTHP system size relative to wall cavity

Where gas-fired PTAC units are in place for a heating-dominant climate, evaluate the new electrical load profile for PTHP heating (and supplemental electric resistance heating, if necessary) and compare to the existing electrical capacity for the building to determine whether there is sufficient capacity to serve the heating load or if electrical infrastructure upgrades may be necessary to meet the electrical demand during heating. Required electrical upgrades should be identified within the building decarbonization plan to allow for proper capital planning by the owner. Electrical system upgrades may be cost prohibitive, or may be schedule prohibitive, and partial electrification options provide an alternative solution.

Full Electrification: Packaged Terminal Heat Pump (PTHP) Units

Where a suitable PTHP is available that satisfies the project’s key performance indicators (KPIs; see Chapter 3, Table 3.7)—such as GHG emissions reductions, occupant comfort, or potential utility cost reductions—it provides a great solution for full electrification of the HVAC system. For cold climates with design heating temperatures below 10°F (–12.2°C), a key KPI will be the heating performance of the PTHP at cold temperatures.

CASE STUDY: The Heritage, New York

An example of a PTAC-to-PTHP retrofit in a multifamily building is included in the case study for the Heritage in NYC. The retrofit required building electrical upgrades, and the building owner decided to invest in the upgrades to support PTHP units and provide the electrical system infrastructure for future upgrades.

#### 6.1.1.2 Split-System AC Retrofits

The split system is a common HVAC system for garden-style multifamily buildings, some hotels, and small to medium commercial buildings. These combine a split-system AC, with the evaporator coil and fan indoors and condenser and compressor outdoors, for cooling along with a natural-gas-fired furnace for heating. Depending upon the application, these systems may be ductless or ducted. Like PTAC units, they provide a common and inexpensive HVAC system that is easy to maintain and allows for the replacement of portions as needed rather than entire units. Figure 6.3 shows images of split-system heat pump installations at the Vera Cruz Village Apartments (see Case Study 13, Vera Cruz Village, California). Split-system heat pumps can offer straightforward replacements for existing split systems, whether ductless or ducted configurations. With the split nature of these systems, and the location of outdoor units, the physical size of a replacement split heat pump is typically not a significant issue. Similar to a PTAC-to-PTHP retrofit (discussed in Section 6.1.1.1), the design must consider the higher of the cooling or heating load and the design temperatures for sizing the split heat pump.

**[Figure: Split-system heat pump installation—Vera Cruz Village Apartments]**

Type: diagram

Description: The figure shows a split-system heat pump installation at Vera Cruz Village Apartments. It includes images of the exterior and interior components of the system, as well as a diagram of the system's layout.

Key Elements:

* Exterior unit -> provides cooling and heating to the building
* Interior unit -> distributes conditioned air throughout the building
* Refrigerant lines -> connect the exterior and interior units
* Thermostat -> controls the temperature of the building

This figure provides a visual representation of a split-system heat pump installation, highlighting its key components and how they work together to provide efficient heating and cooling.

Challenges may arise in colder climates, where ASHP efficiency can be reduced during extreme winter conditions. To address this, supplemental heating systems such as electric resistance or gas furnaces can be integrated to provide additional heat during extreme conditions. A primary decision point for a split system with furnace retrofit is what to do with the existing system furnace. The furnace may be retained for supplemental heat or replaced entirely with a heat pump solution. This decision is influenced by:

- Climate and design heating requirements

- Available electrical capacity

- Age and remaining effective useful life of furnace

- GHG emissions targets

Evaluate the new electrical load profile for the split heat pump heating and compare to the existing electrical capacity for the building to determine whether there is sufficient capacity to completely serve the heating load or if electrical infrastructure upgrades may be necessary to meet the electrical demand during heating. This evaluation applies for designs where the heat pump would serve the full heating load by itself, or where supplemental electric resistance heat may be employed for peak heating periods. Required electrical upgrades should be identified within the building decarbonization plan to allow for proper capital planning by the owner. Electrical system upgrades may be cost or schedule prohibitive, and partial electrification options provide an alternative solution.

Partial Electrification: Retain Furnace for Supplemental Heating

For HVAC electrification retrofits for split-AC systems with furnaces where a suitable split heat pump may not be available to meet the full heating load, or where required electrical system upgrades are prohibitive, one option might be to retain the existing furnace for supplemental heating. For this option to be practical, the existing furnace must be in good operating condition with sufficient years of effective useful life (EUL). The amount of EUL that is acceptable will depend on the building owner and capital plan. In many cases, this will be at least five years’ remaining EUL.

In this scenario, the split heat pump will be staged first to meet a portion of the building heating load, and then the furnace will be fired to provide additional heat for the remaining portion of the heating load. The portion of load met by the heat pump should be determined based on the specific project conditions, such as the electrical capacity and the climate conditions. Generally, the goal is to serve as much of the heating load as possible with the heat pump and limit the periods of supplemental heat from the furnace.

CASE STUDY: 47 Seventy Apartments, Utah

An example of a split-system AC with furnace partial electrification retrofit in a multifamily building is included in the case study for 47 Seventy Apartments in the Salt Lake City area. The team chose a partial electrification solution, installing ASHPs for cooling and heating needs along with gas furnaces for supplemental heating. In this project, the existing gas-fired furnaces had exceeded their EUL and were replaced with new gas-fired furnaces rather than being retained for the project.

Partial Electrification: Dual-Fuel Heat Pumps

Another option when there are limitations on a split heat pump to meet the full heating load can be to install dual-fuel heat pumps. These allow for supplemental heating, typically natural gas fired, that can meet the heating load when the outdoor temperatures fall below the operating range of the heat pump. Figure 6.4 provides an example diagram of a split-system heat pump paired with a natural gas furnace. A dual-fuel heat pump application may be a good solution when supplemental heating is needed but the existing furnace does not have sufficient EUL remaining to be an acceptable solution. Dual-fuel heat pumps also provide an alternative when electrical capacity is limited and the full heating load cannot be met with a heat pump alone. For this scenario, the heat pump can be sized to match the available electrical capacity and then the gas furnace sized to meet the balance of the heating load. The controls for the heat pump should be programmed to operate the auxiliary furnace in response to the current electrical demand relative to the building’s electrical capacity. Finally, in cold climates with design temperatures well below freezing, a dual-fuel heat pump can efficiently meet a portion of the heating load with a gas furnace sized to provide supplemental heat. In cold-climate scenarios, a dual-fuel split-system may not meet Finally, in certain cold-climate scenarios, a dual-fuel split-system may not meet the full heating load due to other factors mentioned above (electrical capacity, roof space and structural capacity, etc.). Cold climates with design temperatures well below freezing may use a dual-fuel heat pump to efficiently meet a portion of the heating load with a gas furnace sized to provide supplemental heat. Full Electrification: Ductless or Ducted Split Heat Pump with Complete Removal of Furnace

**[Figure: Diagram of dual-fuel split-system heat pump]**

Type: diagram

Description: The diagram illustrates the components and flow of a dual-fuel split-system heat pump, highlighting its key elements and their functions.

Key Elements:

- **Heat Pump Indoor Unit (Primary Heating & Cooling Source)** -> This is the central component responsible for heating and cooling.
- **Furnace Exhaust** -> This part handles the exhaust from the furnace.
- **Gas Furnace (Back-up Heat Source)** -> It serves as a backup heat source.
- **Air Filter** -> This component filters the air before it enters the system.
- **Air Handler Blower (Fan)** -> It circulates air through the system.
- **Gas Supply** -> This is the source of gas for the furnace.
- **Refrigerant Lines** -> These lines carry refrigerant between the indoor and outdoor units.

This diagram provides a clear overview of how a dual-fuel split-system heat pump operates, showcasing its dual functionality for both heating and cooling.

Full electrification with a split heat pump can take two forms: a split heat pump with supplemental electric resistance heat and a split heat pump with no supplemental heating. A split heat pump with electric resistance supplemental heating represents a full electrification option but is less efficient than a split heat pump only. Electric resistance supplemental heat is often used during defrost cycles (see Section 6.1.4.1) to melt freezing coils during heating operation. For a design with a heat pump and supplemental electric resistance heat, the system should maximize the number of hours that the more efficient heat pump is used to satisfy the heating load. Because the heat pump is more efficient than electric resistance heat, configuring the system to maximize heat pump heating results in lower GHG emissions and energy costs. Split heat pumps that can be sized to meet the full heating load without need for supplemental heating constitute a straightforward replacement. The split heat pump will be sized based on the peak heating load identified from hourly load analyses and should account for defrost cycle operation as discussed in Section 6.1.4.1.

#### 6.1.1.3 Packaged Rooftop Unit (RTU) Retrofits

As shown in Figure 6.1, packaged HVAC units are the most common type found in commercial buildings. They are a common retrofit and represent a significant opportunity for decarbonization. Of these packaged systems, single-zone RTUs are very common and found on the rooftops of many small and medium commercial buildings. Packaged multiple-zone RTUs that are single duct to terminal units with zone reheat are more commonly found on medium commercial buildings and some large commercial buildings. This section will consider packaged multiple-zone RTUs with variable volume and temperature (VVT) control or electric zone reheat. Section 6.1.3.2 will cover multiple-zone RTUs with hot-water reheat served by a boiler.

Packaged RTU systems, whether single zone or multiple zones, can be replaced with packaged heat pump RTUs. Packaged systems make for seemingly straightforward replacements. However, like other heat pump retrofits, the cooling and heating loads must be evaluated and the larger of the two used for sizing the packaged heat pump RTU. Where heating is the larger load, the retrofit will not be a simple like-for-like replacement of packaged units. Sizing the heat pump to meet the heating load can result in specifying a larger RTU than the existing unit, raising concerns about electrical capacity, roof space, and equipment weight and structural capacity in some applications. This can also lead to humidification issues during cooling but selecting an RTU with variable-speed compressors allows the heat pump to modulate and better meet the cooling and dehumidification loads. The dimensions and weight of specified packaged heat pump RTUs need to be closely evaluated to ensure that the unit meets the existing roof’s structural capacity and will fit in the available space, with sufficient clearance for ease of maintenance and repair.

A variety of strategies can be used to address packaged heat pump RTU size and weight:

- Following the methodology discussed in Section 3.4 and illustrated in Figure 3.7 in Chapter 3, implementing strategies for high performance envelopes and HVAC heat recovery to reduce building heating and cooling loads may allow for reduced sizing of the packaged heat pump RTU that will not exceed roof space constraints or roof structural capacity.

- Install dual-fuel heat pumps to meet the full heating load as discussed under partial electrification options.

- Install a packaged unit (typically semi-custom) with a DX coil and electronic expansion valve (EEV) kit(s) served by separate VRF heat pump condensing unit(s). This solution can increase flexibility for roof weight distribution, although it can increase cost compared to a packaged heat pump RTU.

- Include electric resistance heating or make use of existing electric resistance heating where already in use for zone reheat. Local grid emission factors and electricity costs must be considered when evaluating supplemental electric resistance heat, as this can represent a significant increase in electricity consumption.

Partial Electrification: Dual-Fuel Heat Pump RTUs in Cold Climates

Dual-fuel heat pump RTUs combine an air-source heat pump and an auxiliary gas furnace. The packaged dual-fuel heat pump RTU typically uses the heat pump first to meet the heating load and then operates the gas furnace to provide heat below a specified temperature. Dual-fuel heat pumps provide an option where heating capacity drives peak equipment sizing. It can be a challenge to accommodate a large enough packaged heat pump RTU within the existing roof space and structural capacity for peak heating, but a smaller unit will serve for peak cooling. This option also provides an alternative when electrical capacity is limited.

Full Electrification: Heat Pump RTU

Single Zone

A packaged single-zone heat pump RTU that can be sized to meet the full heating load without triggering the concerns noted earlier in this section makes a straightforward replacement. Even when electrical service, size, and weight are issues, they can often be addressed in ways that still make this type of retrofit financially feasible. Supplemental electric resistance strip heat is often required to address comfort concerns during defrost mode, as discussed in Section 6.1.4.1.

CASE STUDY: Vera Cruz Village, California

Vera Cruz Village, a multifamily apartment village in Richgrove, CA, included a variety of heat pump replacements. The majority of buildings replaced existing packaged RTUs with packaged heat pump RTUs. Retrofits also included split-system heat pump installation and packaged heat pump energy recovery units.

Multiple Zone: Variable Volume and Temperature (VVT)

Packaged heat pump RTUs can be used as a full electrification solution with a heating/cooling change-over type system, also known as a variable volume and temperature (VVT) system. In such systems, the packaged heat pump RTU provides hot or cold air to all zones. Zone dampers control the amount of airflow in order to control room temperature, but there is no zone-level control over supply air temperature. These systems only work for zones that have similar load profiles—i.e., similar exposure and loads. This retrofit approach can be used on existing VVT systems or as a potential solution for larger renovations where zones are being reconfigured or redone. Multiple Zone: Electric Variable Air Volume (VAV) Reheat

Packaged multiple-zone heat pump RTUs with electric reheat can also provide a full electrification option. For a design with a heat pump and supplemental electric resistance heat, the system should maximize the number of hours that the more efficient heat pump is used to satisfy the heating load. Because the heat pump is more efficient than electric resistance heat, configuring the system to maximize heat pump heating results in lower GHG emissions and energy costs.

CASE STUDY: StopWaste Office, California

The case study for StopWaste in Oakland, CA, represents a packaged RTU heat pump retrofit in a small office building. VAV RTUs were replaced with packaged heat pump VAV RTUs.

Multiple Zone: Dual-Fan, Dual-Duct (DFDD) Systems

Dual-fan, dual-duct (DFDD) systems use a cooling air handler and a heating air handler to provide independent cold air and hot air to each zone. This approach eliminates electric resistance or hot-water heating at the zone terminal units, while still providing full zonal temperature control. Packaged heat pump RTUs can be used to create a non-custom DFDD setup, which combines two or more heat pump RTUs and traditional packaged cooling-only RTUs, depending on the load requirements. This retrofit approach is valid for existing DFDD buildings but also for major retrofits where a majority of ductwork and terminal units are being replaced due to age or layout changes.

Full Electrification: Variable Refrigerant Flow (VRF) Systems

Variable refrigerant flow (VRF) systems offer a potential full electrification option for buildings with existing mixed-fuel RTUs. VRF heat pump systems offer flexible zoning capabilities and variable speed compressors that tend to be higher efficiency than similar-sized DX equipment. They include an outdoor unit (or units) serving multiple indoor units, allowing each zone to be heated or cooled individually. These systems are also typically paired with a DOAS to meet ventilation needs for the building, rather than attempting to ventilate with the VRF terminal units. Heat recovery VRF systems allow for heating and cooling different zones at the same time, capturing heat from zones in cooling and moving it to zones in heating, though in practice there are many internal control rules that often limit the realization of full heat recovery. These systems can offer a solution where frequent simultaneous heating and cooling occurs. An hourly analysis of building heating and cooling loads will identify the frequency and duration of simultaneous heating and cooling periods. See Section 3.3.1.2 in Chapter 3 for reference on load analysis. VRF systems use distributed refrigerant lines between the outdoor and indoor units to move heat. These refrigerant lines often require complex field installation and commissioning that may pose challenges, particularly for refrigerant leakage. The refrigerant distribution systems for VRF are frequently fabricated and installed in the field, and the quality of installation can have significant effects on system performance and, most importantly for GHG emissions, on refrigerant leakage rates. For VRF systems with a large amount of field-installed refrigerant piping, ASHRAE Standard 228-2023 provides an annual leakage rate of 10% (ASHRAE 2023b). For large buildings with large VRF systems, the GHG emissions attributed to refrigerant leakage can be significant over the life of the system. These GHG emissions from refrigerant leakage should be accounted for in determining the GHG impacts for the retrofit project when evaluating options. See Section 3.3.1.6.1 in Chapter 3 for a discussion of refrigerant impacts and ASHRAE’s Whole-Life Carbon Guide for Building Systems for details on calculating the lifecycle carbon for buildings and retrofits. Pre-manufactured flexible line sets reduce installation cost and the number of joints, which reduces leakage potential. There may be aesthetic considerations for exposed refrigerant line sets, but they should be considered in all situations for cost and leakage reasons.

**[Figure: Diagram of an example multiple terminal unit VRF system]**

Type: diagram

Description: The diagram illustrates a multiple terminal unit VRF (Variable Refrigerant Flow) system, showcasing its components and their connections. It highlights the system's ability to efficiently manage refrigerant flow across various terminals.

Key Elements:

- **Outdoor Unit** -> Houses the compressor, condenser, and fan.
- **Refrigerant Pipes** -> Connect the outdoor unit to the indoor units, facilitating refrigerant flow.
- **Indoor Units** -> Multiple units are shown, each capable of independent temperature control.
- **Branch Boxes** -> Distribute refrigerant to individual indoor units.
- **Thermostats** -> Control temperature settings for each indoor unit.

This diagram provides a clear overview of how a multiple terminal unit VRF system operates, emphasizing its flexibility and energy efficiency in heating and cooling applications.

### 6.1.2 Steam System Retrofits

Current heat pump technology is designed to supply heating hot water, not steam, though there may be future technology to fill that gap. Electric-resistance steam boilers may be an appropriate solution to replace gas-fired steam boilers depending on the source of electricity and the emission profile, though these are often untenable from electrical service sizing and operational cost perspectives. Some district/city steam providers may provide “low-carbon” or “carbon-free” steam generated with renewable electricity either now or in the future, which may be evaluated as an option. While there may be situations when it makes sense to keep an existing steam distribution system, it is often advisable to convert from steam distribution to hot-water distribution for heating. Steam distribution is inherently less efficient than hot water, and many older steam systems represent a safety concern due to pipe age and corrosion coupled with the potential for dangerous leaks. Two-pipe steam systems may be able to retain the existing distribution piping for hot-water distribution if the piping is in good condition, but special attention should be paid to the increased static pressure from hot-water systems, as steam piping is often not designed for these pressures (particularly in a high-rise application). Pipe thicknesses should be tested, particularly at low points where corrosive condensate tends to collect. For single-pipe steam systems, the distribution piping will require replacement, increasing the cost for retrofit.

### 6.1.3 Central Boiler Retrofits

There are many types of HVAC systems that use a central hot-water system served by a natural gas boiler or steam-to-hot-water heat exchanger. This section covers the primary retrofit options for a central hot-water boiler plant. The subsections cover specific considerations for the different HVAC systems that use central hot water. Partial Electrification: Air-to-Water Heat Pumps Paired with Condensing Boiler or 

Other High-Efficiency Boiler for Peak Heating Days

A hybrid solution for a central heating hot-water system is to pair air-to-water heat pumps (AWHPs) with a high-efficiency boiler, such as a condensing boiler, to meet the heating load. Hybrid systems can meet the heating load when there are challenges to meeting the full heating load with an AWHP or when it otherwise does not make sense to fully electrify immediately (e.g., cost and existing equipment age). There are many potential designs for AWHPs paired with condensing boilers, and the division of heating between the heat pump and high-efficiency boiler will vary based on the specific building and system. Refer to Section 3.4.1 in Chapter 3 for additional discussion regarding rightsizing a combination AWHP and boiler plant. Some scenarios include:

- Electrical System Capacity Limiting Heat Pump Size. The heat pump can be sized for the existing electrical capacity. The high-efficiency boiler will be used to meet the heating load that exceeds the maximum heating capacity of the heat pump.
- Challenge in Heat Pump Sizing with Difference Between Cooling and Heating Loads. Multi-stage or modulating heat pumps can allow for a wider range of operation to meet both cooling and heating loads. These scenarios can still lead to heat pumps being slightly undersized for the heating load, and a high-efficiency boiler can be used to supplement for peak heating days.
- Building Stress Test Indicates Peak Heating Loads Require Higher Supply Temperatures than Heat Pump Provides. When heating hot-water supply temperatures exceed the capacity of available, or cost-effective, heat pump options, a high-efficiency boiler can be used to meet peak heating loads. The hot-water supply temperature can be reset to match the outdoor air temperature, while the heat pump used to meet heating loads is set at or below the maximum hot-water supply temperature. The high-efficiency boiler will be sequenced to meet the heating load at hot-water supply temperatures above the capacity of the heat pump.

Special attention must be paid to the operating temperatures of the AWHPs and boilers. The condensing boiler can supply hot water at a higher temperature than typical AWHPs, but the return water temperature will also be higher. This can result in the HHW loop return temperature exceeding the inlet temperature at which the AWHP will operate. For this reason, if the AWHPs and boilers are operating simultaneously, they need to be operating at a similar hot-water supply temperature set point to ensure appropriate return-water temperatures. This is generally only possible with condensing boilers given the low return-water temperature of a typical AWHP system. Alternatively, the AWHPs and boilers can operate independently. This approach works well when you have an existing boiler plant that is sized for the full capacity and can be controlled to run only during periods above the peak capacity of the AWHP system, during which the AWHP system would be disabled until the load drops to a level the AWHP system can pick back up. This type of transition between boiler and AWHP operation is not always simple and requires transitioning the boiler hot-water supply water temperature down prior to switching back to the AWHP system.

CASE STUDY: San Diego State University, California

The case study for San Diego State University (SDSU) presents a partial electrification design for a central heating plant serving three campus buildings. The partial electrification allowed SDSU to implement an electrification solution while avoiding the costly electrical service upgrades required for full electrification of the central plant.

Partial Electrification: Heat Recovery Chiller (Optional TES)

Heat recovery chillers can help electrify the heating hot-water system and can be a first step toward full electrification. These systems recover waste heat from the cooling process and use it for heating applications, such as space heating or domestic hot water. They transfer heat from the chiller’s condenser through a heat exchanger to the desired heating system. By nature of their design and operation, heat recovery chillers are a good retrofit solution when simultaneous heating and cooling are needed. However, heat recovery chillers typically do not consistently provide sufficient heating to satisfy the heating hot-water load at peak times, when many buildings do not have high cooling requirements. Some exceptions are buildings with high and constant heating loads, such as data centers, where cooling needs enable sufficient heat production from the heat recovery chiller. Heat recovery chillers may provide a full electrification solution when paired with a TES system. The TES can provide a cooling sink for the chiller that allows it to serve as a sufficient heat source for the heating hot-water load. Hourly analysis of building heating and cooling loads is necessary to determine sizing for a heat recovery chiller and TES tank and whether they can be operated effectively to meet building loads and reduce GHG emissions. TES systems are discussed further in Section 7.5 in Chapter 7. Both air-cooled and water-cooled chillers are offered with heat recovery capabilities that produce hot water. Water-cooled chillers incorporate a heat exchanger to recover heat from the condenser water loop. Excess heat that is not recovered is still released through a cooling tower or other heat-rejection device. Air-cooled chillers will include either an in-line, water-cooled heat exchanger prior to the air-cooled condenser or may have parallel circuits that allow for switching between the air-cooled condenser and a water-cooled heat exchanger. Heat recovery chillers typically provide a maximum hot-water supply temperature between 120°F and 140°F (48.9°C and 60°C). Water-cooled heat recovery chillers can provide higher hotwater supply temperatures than AWHPs, depending on the refrigerant that is used. Like the AWHPs discussed above, these are lower operating temperatures than systems designed for fossilfuel-fired boilers. If a building stress test indicates that temperatures above the heat recovery chillers’ maximum supply are needed, supplemental heating will be required. This can be accomplished by adding high-temperature or cascading heat pumps or with a hybrid system that incorporates a high-efficiency boiler for peak heating periods.

Sizing a heat recovery chiller will depend on the heating and cooling loads for the building and the primary goals for the system. Factors such as building size, load profiles, energy-efficiency goals, and available heat sources will determine the most suitable option for a particular retrofit project. See Sections 3.3.1.2 and 3.4.1 in Chapter 3 for details on load profile analysis and rightsizing. The performance of heat recovery chillers decreases as the hot-water supply temperature increases, so the chiller performance should be evaluated against the hourly heating and cooling loads to determine a performance profile. Additionally, heat recovery chillers often can control only one of the leaving water temperatures, either chilled water or hot water, but not both. This aspect of heat recovery chiller control often leads to TES and other strategies to stabilize hot-water and chilled-water temperatures. Partial Electrification: Heat Recovery from Sewer Water

Sewer wastewater can act as a heat source/sink for building heating and cooling needs. While there are different methods for using wastewater heat recovery, typical systems collect wastewater in a holding tank, run it through a macerator, and filter the wastewater before passing it through a heat exchanger to transfer heat with the building systems. The system acts as a heat source during heating months to supplement other heating sources for the building. During cooling season, the system can also act as a heat sink, allowing the building to reject heat to the holding tank where it is tempered before being discharged to the sewer. Sewer heat recovery similarly can be used as a source for domestic hot-water (DHW) heating as described in Section 8.7 in Chapter 8. Full Electrification: Air-to-Water Heat Pump to Replace Boiler (Optional TES)

Full electrification of the heating hot-water system can be achieved using AWHPs. As discussed above, heat pump systems typically operate at lower temperatures than systems designed for fossil-fuel-fired boilers. As discussed in Section 3.3.1.5 in Chapter 3, a building temperature stress test should be done to evaluate the minimum hot-water temperature required to meet the building heating load. Hot water and steam radiators found in older buildings often present a challenge due to the hot-water supply temperatures typically used with operation. Design options exist to meet higher hot-water temperatures with heat pumps, if necessary, as described below. Cascading Heat Pump System

One central system design option that can provide higher hot-water supply temperatures is a cascading heat pump system. This design strategy uses AWHPs to bring the supply water up to a modest temperature of 90°F to 100°F (32.2°C to 37.8°C) before entering a WSHP to boost the hot-water supply temperature up to a range of 160°F to 180°F (71.1°C to 82.2°C). A buffer tank should be installed between the AWHP and WSHP to help stabilize and smooth operation of the heat pumps.

**[Figure: Diagram of cascading hydronic heat pump system]**

Type: diagram

Description: The diagram illustrates a cascading hydronic heat pump system, which is a type of heating and cooling system that uses water as the medium for heat transfer. The system consists of three main components: an airside unit, a waterside unit, and a buffer tank.

Key Elements:

*   Airside unit -> This component is responsible for exchanging heat between the outdoor air and the refrigerant.
*   Waterside unit -> This component is responsible for exchanging heat between the refrigerant and the water in the buffer tank.
*   Buffer tank -> This component stores hot water that is used to heat the building.

The diagram shows how these components work together to provide heating and cooling to a building. The airside unit extracts heat from the outdoor air and transfers it to the refrigerant, which is then pumped to the waterside unit. The waterside unit extracts heat from the refrigerant and transfers it to the water in the buffer tank. The hot water in the buffer tank is then used to heat the building.

Overall, the diagram provides a clear and concise overview of how a cascading hydronic heat pump system works, and it can be useful for engineers, architects, and building owners who want to understand the basics of this type of heating and cooling system.

High-Temperature Heat Pumps

High-temperature heat pumps provide another option for central heating hot water. These heat pumps may use multiple refrigerant stages to produce water near 180°F (82.2°C) but are often costlier than more conventional heat pump designs. High-temperature heat pumps have been used in Europe, particularly in Scandinavia, and there are several manufacturers with products available. Manufacturers in North America are beginning to develop more high-temperature heat pump offerings, though often they are relatively expensive solutions designed for domestic hot-water applications.

Full Electrification: Ground-Source Heat Pump to Replace Boiler

Ground-source heat pumps (GSHPs) can be open-loop or closed-loop systems. They offer a reliable and sustainable energy source for HVAC decarbonization in existing buildings but have higher initial installation costs compared to other heat pump options. GSHPs use the relatively constant temperature of the ground to extract or reject heat, acting as a heat sink or heat source much like a TES system. An important factor in GSHP design is the balance of the annual heating and cooling loads served by the system. If the annual heating and cooling loads are not well balanced, the ground source will slowly deteriorate and become warmer, or cooler, over time depending on the dominant load.

CASE STUDY: Skokie Courthouse, Illinois

See the case study for Skokie Courthouse for a central plant retrofit with a GSHP serving AHU systems. A GSHP was selected to replace the existing central plant for GHG emissions reduction, economic performance, and reliability. The cost for drilling the geothermal well field made it impractical to serve 100% of the building’s heating and cooling loads. A hybrid system design was used with the GSHP sized to meet the majority of the heating and cooling loads aided by supplemental condensing boilers and centrifugal chillers.

Open-Loop Systems

Also known as groundwater systems, open-loop systems pump water directly from a well or water body, use it to transfer heat to or from the building, and then discharge it back into the ground well or water body. Open-loop systems require access to an adequate groundwater source.

Closed-Loop Systems

These systems circulate a heat transfer fluid, typically a mixture of water and glycol, through a closed loop of underground pipes. The fluid absorbs heat from the ground in winter and transfers it to the building for heating. In summer, the system extracts heat from the building and releases it into the ground. Closed-loop systems involve burying a network of high-density polyethylene (HDPE) pipes in vertical or horizontal configurations in the ground or, in some cases, submerging them in a nearby water body. Vertical loops require drilling boreholes, while horizontal loops are installed in trenches. These systems require sufficient land area for trench or borehole installation, which typically makes them most suitable for campus applications and can make them difficult and impractical for many individual building retrofit applications, particularly in dense urban areas. However, there are technologies using diagonal boreholes that have been used in countries including Sweden, which are being tested in places such as New York City for retrofitting a GSHP in an existing high-rise building.

Geothermal systems can be deployed in a wide range of climates, but they are particularly advantageous in areas with moderate to extreme temperature variations where AWHPs have lower performance. They are highly efficient in both heating and cooling modes and can provide consistent performance year-round. While geothermal systems can be beneficial in both commercial and multifamily buildings, there are some differences to consider. Commercial buildings may have higher heating and cooling loads, complex zoning requirements, and specific code compliance considerations. Multifamily buildings may need to address tenant comfort, individual control options, and coordination with shared systems. Customizing the geothermal system design and installation process to suit the building type is essential for optimal performance and efficiency. GSHPs also may be combined with AWHPs, heat recovery chillers, or conventional chillers to meet heating and cooling loads. For example, combining a GSHP with a conventional chiller served by a cooling tower or other air-source heat sink can address scenarios where building cooling loads are considerably larger than heating loads. The GSHP can be sized to meet the building heating load and the chiller sized to meet the cooling load that exceeds the GSHP’s capacity. Full Electrification: Variable Refrigerant Flow (VRF) System

Geothermal Heating and Cooling: Design of Ground-Source Heat Pump Systems

Geothermal Heating and Cooling is recognized as the primary reference for nonresidential GSHP installations (Kavanaugh and Rafferty 2014). This essential guide for HVAC design engineers, design-build contractors, GSHP subcontractors, and energy/construction managers also provides building owners and architects with insights into characteristics of quality engineering firms and the information that should be provided by design firms competing for GSHP projects.

RP-1674

Geothermal Heating and Cooling Design of Ground-Source Heat Pump Systems

Steve Kavanaugh Kevin Rafferty

A Complete Guide to Design of Ground-Coupled,

Groundwater, and Surface-Water Systems for

Commercial and Institutional Buildings

Variable refrigerant flow (VRF) systems are a full-electrification option for central boiler retrofits. See Section 6.1.1.3 for prior discussion of VRF systems, including refrigerant considerations.

CASE STUDY: Stella B. Werner Council Office Building, Maryland

See the case study for the Stella B. Werner Council Office Building in Montgomery County, Maryland, where a central plant serving a variety of FCUs, AHUs, and packaged RTUs was replaced with a watercooled VRF system. The system provided a single-system solution that fit within existing ceiling heights while allowing modular design and installation by floor.

CASE STUDY: Ken Soble Tower, Canada

See the case study for the Ken Soble Tower in Hamilton, Ontario, where a VRF system with DOAS replaced hydronic baseboard heaters with a central boiler. No cooling was in place for the tower prior to the retrofit.

#### 6.1.3.1 Optional Thermal Energy Storage (TES)

For any central heating hot-water system retrofit that maintains a hydronic approach, thermal energy storage (TES) systems are a valuable addition. They provide flexibility in meeting a building’s heating and cooling demands, allowing for load balancing and improved energy efficiency. The integration of TES can effectively reduce the heat pump capacity required for the heating hotwater system. When paired with on-site renewable energy production, such as solar PV, heat pumps and TES systems can be designed to produce chilled or hot water using clean energy and store these for use during periods when grid emission factors are high. Renewable energy production is discussed in Section 7.1, and TES systems and strategies are discussed in Section 7.5 in Chapter 7.

#### 6.1.3.2 VAV Reheat with Packaged RTUs or Air Handlers

As discussed in Section 6.1.1.3, packaged RTU systems can be replaced with packaged heat pump RTUs, using hourly cooling and heating load analysis to determine the appropriate sizing for the heat pump. These are not simply like-for-like replacements, and heat pump RTU size and weight, along with duct sizing, are important design parameters.

Packaged RTU systems with central boilers will have the bulk of heating energy consumption at the zone level hot-water coils. The heating at the central RTU is typically just preheating, which is generally needed only for cold outdoor air temperatures when heat pump performance is lower. As a result, installing packaged heat pump RTUs may provide only minimal benefit, and greater focus should be given to the central boiler and heating hot-water system. A more extensive discussion of central boilers in heating hot-water systems is provided in Section 6.1.3.

AWHPs typically use a lower hot-water supply temperature than the boiler systems they are replacing, which affects the associated heating capacity of the terminal unit heating coils. The revised performance and coil capacity should be modeled using the original terminal unit manufacturer’s catalog data or performance software. Many existing terminal units, especially those used with condensing boilers, will already have this. Boxes with just one row of coils can be retrofitted with a two-row or three-row coil and/or with a larger coil and added duct transitions, if necessary, as determined by the building stress test and coil performance selection software analysis. Many VAV box and coil manufacturers offer multiple coil options, including high-capacity coils, different circuiting options, and oversized casings, where the inlet size is the same but the coil and casing are the size of the next box size up. A decarbonization retrofit should evaluate whether existing coils and piping distribution can handle the increased flow rates typical of a central plant heat pump design: the temperature difference at design conditions across the heating coil can be as low as 10°F (5.6°C). Figure 6.7 shows the DT and hot-water return temperature (HWRT) as a function of the hot-water supply temperature (HWST) for one-row, two-row, and three-row hotwater coils at a given capacity (same entering and leaving air temperatures at the same airflow rate). Figure 6.8 shows the hot-water flow requirements for the same coils and conditions. The figures show that one-row coils struggle to provide enough capacity (for these given conditions) below ~145°F (~62.8°C) water as they max out on flow and minimum DT. As additional rows are added, lower hot-water supply temperatures are viable, often with reasonable DTs and flow rates.

A study of VAV boxes and hot-water heating coil performance is provided in “The Decarbonization of Existing Heating Hot Water Systems” (Ricart et al. 2023).

As an alternative, high-temperature heat pumps, or cascading heat pump systems, described in Section 6.1.3, provide an electrification design option that can provide higher hot-water supply temperatures near 180°F (82.2°C). These systems have a higher first cost than a typical AWHP but may avoid the need to retrofit coils within the existing system.

**[Figure: HHW temperatures and DT for one-, two-, and three-row coils for a given capacity]**

Type: chart

Description: This chart compares the HHW temperatures and DT for one-, two-, and three-row coils for a given capacity. The key insight is that the HHW temperature increases as the number of rows increases, while the DT decreases.

Data Representation:

*   One-row coil: 115°F - 135°F
*   Two-row coil: 145°F - 165°F
*   Three-row coil: 175°F - 195°F

Metric: HHW temperature

Chart Type: Line chart

Units: °F

Chart Generation Hint:

*   X-axis: Capacity (tons)
*   Y-axis: HHW temperature (°F)

Structured Data (Machine Readable):

```json
{
  "chart_type": "line",
  "metric": "HHW temperature",
  "units": "°F",
  "data": {
    "one-row coil": [115, 135],
    "two-row coil": [145, 165],
    "three-row coil": [175, 195]
  }}
}
```

This chart provides a clear comparison of the HHW temperatures and DT for different coil configurations, allowing for easy identification of the optimal configuration for a given capacity.

**[Figure: HHW flow for one-, two-, and three-row coils for a given capacity]**

Type: flow diagram

Description: This figure illustrates the flow of heat for one-, two-, and three-row coils in a heating system, highlighting the differences in heat transfer efficiency between these configurations.

Process Steps:

1. **One-row coil flow** -> Heat is transferred from the hot water to the air through a single row of coils.
2. **Two-row coil flow** -> Heat is transferred from the hot water to the air through two rows of coils, increasing the surface area for heat transfer.
3. **Three-row coil flow** -> Heat is transferred from the hot water to the air through three rows of coils, further increasing the surface area for heat transfer.

Flow Logic:

* The flow of heat is represented by arrows, indicating the direction of heat transfer from the hot water to the air.
* The thickness of the arrows represents the amount of heat transferred, with thicker arrows indicating more heat transfer.

Key Components:

* **Coils**: The coils are the primary component of the heating system, responsible for transferring heat from the hot water to the air.
* **Hot water**: The hot water is the source of heat for the system, flowing through the coils to transfer heat to the air.
* **Air**: The air is the medium being heated, flowing over the coils to absorb heat from the hot water.

Structured Flow (Machine Readable):

{
  "type": "flow_diagram",
  "steps": ["One-row coil flow", "Two-row coil flow", "Three-row coil flow"],
  "flow": [["One-row coil flow", "Two-row coil flow"], ["Two-row coil flow", "Three-row coil flow"]],
  "decisions": [{"condition": "Heat transfer efficiency", "yes": "Increase surface area", "no": "Maintain current configuration"}}]
}

CASE STUDY: Bloedel Conservatory, Canada

See the case study for Bloedel Conservatory in Vancouver, BC, where a central plant serving nine AHUs was replaced with a two-pipe AWHP. The system was converted to a low temperature hot-water loop/ chilled-water loop with switchover and the AWHP sized to meet up to 90% of the heating load for the building.

CASE STUDY: East Palo Alto Government Center, California

The case study for the East Palo Alto Government Center in California includes a retrofit of a central plant serving AHUs with VAV reheat. The VAV terminal units were replaced with new VAV units containing oversized two-row coils to meet the heating load with the lower temperature hot-water from the AWHP. One of the AWHPs was designed with heat recovery to allow for simultaneous heating and cooling.

#### 6.1.3.3 Hydronic Fan Coil Unit Retrofits

Fan coil units (FCU) generally consist of a filter, small fan, and either a two-pipe coil (single coil) or four-pipe coil (separate heating and cooling coils). Two-pipe systems may be heating or cooling only or include changeover controls at the fan coil level (a newer design approach) or at a level higher up the system chain, e.g., at the central plant or at the pipe riser level. Fan coils are often paired with a dedicated outdoor air system to provide ventilation. FCU systems are often found in multifamily and hotel/lodging buildings and can also be found in medium to large commercial buildings. As prior sections have discussed, when switching central heating sources for heating hot-water loops, a critical evaluation of the heating hot-water system supply and return temperatures and their compatibility with proposed equipment or systems is required. For four-pipe FCUs, installing 6-way valves may allow operation with reduced heating hot-water system temperatures without the need for replacing terminal units. For retrofits that have existing four-pipe FCUs, analyze hourly heating and cooling data to identify opportunities for heat recovery between zones. Heat recovery chillers can be used to provide simultaneous heating and cooling for these retrofits. TES systems, discussed in Section 7.5 in Chapter 7, can increase the capability and flexibility for heat recovery with four-pipe systems through peak shaving and shifting strategies. Two-pipe FCUs on hydronic systems can present electrification retrofit challenges because they operate all in heating or cooling modes, making energy recovery within the system difficult. Retrofitting with WSHPs in place of FCUs offers a hydronic solution that can operate very efficiently. The existing piping should be evaluated for condition and sizing to determine that it is suitable for use with a WSHP loop. If substantial alteration of the existing two-pipe system is necessary, that is likely cost prohibitive for the retrofit. However, in buildings where the existing two-pipe system has reached, or passed, its end of EUL and piping replacements are already considered in the building capital plan, that provides an opportunity to evaluate re-piping for a WSHP loop that allows for energy recovery. VRF systems are another solution, discussed in Section 6.1.1.3.

#### 6.1.3.4 Radiant Conversions

Radiant systems that provide cooling through a chilled beam or panel can also be a retrofit option to replace existing FCUs, and hot-water radiators can replace steam radiator systems. Radiant systems do not require as high a hot-water supply temperature as forced-air terminal units, and the lower hot-water supply temperature pairs very well with heat pump systems. Where gut renovations are being made to a building, retrofitting with radiant floor or ceiling systems may be an option, but in most cases, in-floor or in-ceiling systems are likely not cost-effective. For example, in Case Study 8, Montreal City Hall, Canada, in-floor radiant systems were considered but, due to the building’s historic status, were not a feasible retrofit option. Where radiant systems are pursued, ASHRAE’s Active and Passive Beam Application Design Guide provides a resource for system design (Woollett and Rimmer 2014). Radiant systems will require supplying ventilation air to spaces, typically using a dedicated outdoor air system (DOAS). The DOAS will be sized to meet the ventilation loads for the spaces. ASHRAE Design Guide for Dedicated Outdoor Air Systems, Second Edition, is a useful reference for retrofits that will include a DOAS to meet ventilation (ASHRAE 2022f).

CASE STUDY: 345 Hudson, New York

The 345 Hudson case study highlights a retrofit project that provides an example of conversion from steam radiators and terminal cooling units to a radiant system of hot-water radiators and chilled beams connected with TES. WSHPs serve radiant loops at each floor and tie into a condenser water loop with TES to move heat around the building. The modular retrofit approach allows for conversion of systems by floor based on tenant turnover schedules.

#### 6.1.3.5 Water-Source Heat Pump Retrofits

For existing buildings that are served by an existing WSHP loop that includes a central boiler to maintain loop temperature during heating and cooling tower during cooling, these systems represent a great opportunity for full electrification. WSHP loops are a very efficient system for heating and cooling medium and large commercial buildings as well as multifamily and hotel/lodging buildings. The heat pumps in each zone exchange heat between the space and the water loop. When different zones are heating and cooling at the same time, the loop effectively allows heat extracted from one zone to be supplied to another. Unlike the VRF systems discussed in this guide, WSHP systems use water as the medium for transporting energy throughout the building, which does not represent a GHG emissions concern like the refrigerants circulated for VRF. This approach of moving energy around the building is like the Nordic Model described in Case Study 2, 345 Hudson, New York, which includes WSHPs at each floor serving radiant systems that are all connected to a condenser water TES network for the building. WSHP loops operate at relatively low temperatures, typically between 50°F and 100°F (10°C and 37.8°C), and the low heating temperature can make for very efficient heat pump operation as a replacement for the central boiler. WSHP loops are usually served by a cooling tower to handle excess heat rejection requirements. The loads on the central boiler may be low because of the trading of heating and cooling between zones; the boiler is only required to make up the difference in heat between the water temperature and the minimum loop temperature, not the full heating load. For buildings with large floor plates, in particular, the load on the boiler may be very low because the majority of the square footage will be cooling only (e.g., large interior zones). Given the moderate temperatures in WSHP hydronic loops, AWHPs are a good option for boiler retrofits in WSHP loops. The moderate supply water temperatures result in high heat pump capacity and efficiency. AWHPs also offer an opportunity to serve both the heating and cooling requirements for the WSHP loop. If including cost for an AWHP to replace the boiler, using it as a cooling source eliminates the water-use and maintenance requirements of a cooling tower. Use of an AWHP does represent an increase in energy use, and cooling towers may still be necessary to meet the load in cooling-dominated climates. However, where an AWHP can serve both the heating and cooling needs of the WSHP loop, eliminating the cooling tower provides additional operating cost savings to account for when evaluating the retrofit. If the existing building does not currently have a WSHP loop, one can potentially be added through the conversion of an existing hydronic heating system, such as a two-pipe FCU system. As noted in Section 6.1.3.3, the existing piping must be evaluated for use with the WSHP loop. Depending on the age of the central boiler equipment serving the existing system (either existing WSHP loop or converted hydronic loop), it may continue to be used until the end of its EUL as the heating source for the WSHP loop. In such cases, the system design and operating temperature should be evaluated for lowest operating cost and GHG emissions. For example, the system can be designed to operate at a lower loop temperature during heating mode, such as 50°F (10°C), which will require more heat input from the WSHPs at lower operating efficiencies. The alternative would be to operate the central boiler to raise the loop temperature, say to 60°F (15.6°C), where the WSHPs can operate more efficiently. The system can be designed to operate most effectively considering:

- Cost of electricity and fuel for the boiler
- COP of the WSHPs at 50°F (10°C)
- COP of the WSHPs at 60°F (15.6°C)
- Efficiency of the central boiler
- Available heat recovery from other zones in the WSHP loop
- Expected hours of loop operation at minimum temperatures

Thermal Energy Storage (TES)

Thermal energy storage (TES) systems can be integrated with WSHP loops to reduce the need for added heating or cooling to the loop or to stage the periods of loop heating or cooling to coincide with low GHG emissions periods. Case Study 2, 345 Hudson, New York, provides an example of a TES and WSHP network that maintains a loop temperature for high-temperature cooling and lowtemperature heating. TES systems and strategies are discussed in Section 7.5 in Chapter 7.

Ground-Source Loops

Ground-source loops serve as a heat source/sink for the WSHP loop, reducing or eliminating the need for a boiler and cooling tower. Though expensive, GSHP loops can be a high-efficiency decarbonization option for retrofit projects that have sufficient land space and central boilers and cooling towers at the end of EUL.

CASE STUDY: Virginia Beach City Public Schools, Virginia

The case study for Virginia Beach City Public Schools (VBCPS) outlines such projects with ground-source loops serving a WSHP network. The retrofits for several VBCPS schools included existing two-pipe WSHP systems with components at, or near, their end of EUL. Through multiple phases of work, ground-source loops were installed and connected to the existing WSHP networks at several schools. GSHPs were feasible for VBCPS because these schools had available land, such as sports fields, adjacent to the buildings that provided easy access for installation of the ground-source loops.

### 6.1.4 Air-Source Heat Pump Considerations

#### 6.1.4.1 Air-Source Heat Pump Defrost Cycle

The defrost cycle is another important design consideration for air-source heat pumps. Defrost is necessary to maintain heat pump operation/performance at low outdoor air temperatures, typically below ~45°F (~7.2°C), depending on the outdoor humidity level and the temperature of the outdoor coil. The frequency and rate of frost buildup depend on the outdoor air temperature and humidity because water vapor in the air freezes to the coils. Frost buildup reduces the heat transfer at the outdoor coils, lowers the heat pump capacity and efficiency, and eventually can cause the unit to fail altogether. Defrost demand typically peaks at outdoor temperatures of 30°F to 40°F (– 1.1°C to 4.4°C), when moisture content in the air is higher than at colder temperatures. There is a variety of methods for defrost, and two common methods are reversing the heat pump cycle or using electric resistance heaters. Additional details of defrost cycles, including other methods (e.g., hot gas bypass defrost), are presented in Decarbonizing Building Thermal Systems: A Guide for Heat Pump Systems and Beyond (Houssainy et al. 2024). The type of airsource heat pump (RTU, AWHP, split, etc.) also affects how defrost may operate and what options are available. Reverse cycle defrost temporarily operates the heat pump in cooling mode, using heat from inside the building to melt ice from the outdoor coils. The duration and frequency of defrost cycles depend on multiple factors specific to the building, heat pump, and heat pump controls. The defrost cycles are commonly between 2 and 10 minutes and should not initiate more than every 30 minutes. These defrost cycles should be factored into heat pump sizing for heating loads, because the building will have temporary periods of reduced heating capacity. Most manufacturers will provide a defrost derate factor that can be applied to peak load calculations. Larger equipment will have multiple refrigeration circuits that allow alternating circuits to be in defrost mode, which limits the reduction in capacity. Supplemental electric resistance strip heat is often required to address comfort concerns during defrost mode (when the heat pump is running in reverse) and also may be required in colder climates when heat pump capacity drops below design. While supplemental electric resistance heating is often an inexpensive add-on for HVAC equipment, it can trigger electrical service upgrades and should be rightsized for the application. Electric resistance heating can also be used directly at the outdoor coils to prevent the formation of frost. Similar to the use of electric resistance heating for comfort during reverse cycle defrost, the addition of electric resistance heating for defrost should be evaluated for potential electrical capacity constraints that could trigger electrical service upgrades.

#### 6.1.4.2 Cold Climate Considerations

ASHP performance depends on outdoor air temperature, and the performance and heating capacity of ASHPs are primary considerations in cold climates with design temperatures well below freezing. High-performing cold-climate airsource heat pumps are available, and the Northeast Energy Efficiency Partnerships (NEEP) has published the Cold Climate Air Source Heat Pump Specification, as well as the Cold Climate Air Source Heat Pump List, a nationally recognized product selection tool to help identify products best suited to electrify heating in cold climates. The list currently includes central heat pumps, PTHPs, SPVHPs, and VRF products, with the ability to filter by ENERGY STAR certification, ducting configuration, over 200 brands, AHRI reference number, model information, heating capacity, and zip code. A filter for federal tax credit eligibility will be available soon. As of July 2023, the list contains nearly 8500 cold climate products. Other solutions for heat pumps in cold climates include:

Cold Climate Air-Source Heat Pump Specification V4.0

The specification was designed to identify air-source heat pumps that are best suited to heat efficiently in cold climates (IECC climate zone 4 and higher). It is intended for engineers, contractors, and other practitioners who need assurance that the equipment they select will serve the load efficiently throughout the ambient temperature range and to differentiate cold climate performance (NEEP 2023a).

**[Figure: Indoor ASHPs at Montreal City Hall]**

Type: diagram

Description: The image shows two large, white, rectangular units with vents on the front and top, installed in a room with a concrete floor and exposed pipes on the ceiling. The units are likely air-source heat pumps (ASHPs) used for heating and cooling.

Key Elements:

*   Two large, white, rectangular units -> likely air-source heat pumps (ASHPs)
*   Vents on the front and top of the units -> for airflow and heat exchange
*   Concrete floor -> provides a stable base for the units
*   Exposed pipes on the ceiling -> likely part of the building's HVAC system

This diagram provides a visual representation of the indoor ASHPs installed at Montreal City Hall, highlighting their design and installation.

- Supplemental Electric Resistance Heating. Adding supplemental electric heat for cold climates, while straightforward, should be evaluated carefully. Existing electrical capacity is a common concern for decarbonization retrofit projects as discussed in Section 3.5.2 in Chapter 3. See Section 3.3.1.1 in Chapter 3 for GHG evaluation based on timing of peak heating loads and grid emission factors. •Dual-Fuel Heat Pump Systems. Dual-fuel systems, like those in Sections 6.1.1.1–6.1.1.3, offer a solution that does not further aggravate electrical capacity concerns. However, the use of dual-fuel heat pumps will increase site GHG emissions when the natural-gas-fired heating operates. •Locate ASHPs Indoors. Locating ASHPs indoors provides warmer air during cold temperatures that allows the heat pumps to operate more efficiently than if located outdoors. •WSHPs with Ground-Source Loops. WSHPs, presented in Section 6.1.3.5, provide an alternative heat pump technology for use in cold climates. When paired with ground source

CASE STUDY: Montreal City Hall, Canada

The case study for Montreal City Hall provides an example of using heat pumps in cold climates. Locating the ASHP within an indoor mechanical space supplied with exhaust air proved a very good solution. Not only did this improve the efficiency of the ASHPs when outdoor temperatures are very cold, it also provided a solution to municipal regulations for rooftop equipment.

loops, particularly with vertical boreholes for stable ground temperature, a WSHP system is a very efficient and reliable solution that will operate well in very cold temperatures.

- WSHPs with TES. Another WSHP option that has lower first cost than a GSHP is to couple the system with a condenser water TES. This still requires space for siting the TES tank but avoids the required space and cost for drilling a GSHP well field.

Beyond these solutions, the U.S. DOE’s cold climate heat pump initiative is pushing ASHP technology further and recently showed results with 100% heating capacity at 5°F (–15°C) at double the efficiency and 70% to 80% heating at –5°F and –10°F (–20.6°C and –23.3°C) (DOE 2022a). The DOE initiative specifies a COP between 2.1 and 2.4 for 100% heating capacity at 5°F (–15°C).

## 6.2 HVAC Control Sequences

Building automation systems (BAS) and other building control systems are essentially the brains of a building’s HVAC system and a key focus for building optimization. Advanced control sequences for HVAC energy efficiency can play an important role in decarbonization retrofits after electrification of the HVAC system. ASHRAE Guideline 36 provides standardized control sequences designed to minimize system energy use and should be used when developing HVAC sequences of operation. There are some BAS control strategies for HVAC systems that may need to be evaluated differently in the decarbonization context. Some strategies pair well with heat pump systems and other HVAC electrification solutions. For example, hot-water loop supply temperature resets can be very effective with heat pumps that operate at lower supply temperatures. Other strategies may be less effective or could possibly increase GHG emissions. For example, while unoccupied temperature reset may be energy efficient, that strategy may result in higher GHG emissions than maintaining temperatures in certain circumstances. HVAC Space Temperature Set Point Optimization and/or Reset Schedules

**[Figure: ASHRAE Guideline 36, High-Performance Sequences of Operation for HVAC Systems]**

Type: diagram

Description: The figure presents a comprehensive overview of the ASHRAE Guideline 36, which outlines high-performance sequences of operation for HVAC systems. The guideline includes uniform advanced sequences of operation for HVAC systems, rather than custom control sequences created for each system or building (ASHRAE 2021a). The standardized controls sequences in the guideline have been optimized to minimize energy use and maximize comfort and indoor air quality.

Key Elements:

- **ASHRAE Logo**: The logo represents the American Society of Heating, Refrigerating, and Air-Conditioning Engineers, the organization responsible for developing the guideline.
- **Guideline Title**: The title clearly indicates that the document is a guideline for high-performance sequences of operation for HVAC systems.
- **Subtitle**: The subtitle provides additional context, specifying that the guideline includes uniform advanced sequences of operation for HVAC systems.
- **Text**: The text explains the purpose and benefits of the guideline, including its focus on minimizing energy use and maximizing comfort and indoor air quality.

HVAC systems with unoccupied temperature reset schedules have a long history of successful implementation within energy efficiency projects. However, in the context of decarbonization, these strategies should be further examined, particularly when considering HVAC and storage systems that allow for heat recovery. Evaluate the performance of an unoccupied temperature reset strategy based on an hourly analysis of building energy use overlaid with on-site and grid emission factors. The analysis should be performed for each project/building because the overall GHG emissions will depend on factors such as:

- HVAC system components and design
- HVAC equipment efficiencies
- Building thermal characteristics
- Building heating and cooling load profiles
- Environmental conditions

Two potential scenarios are outlined below where an unoccupied temperature reset cannot be assumed to reduce GHG emissions. Morning Warm-Up

Conventional wisdom and standard industry practice dictate employing setbacks in zone temperature set points when buildings are unoccupied at night to minimize energy losses through the building envelope. The HVAC systems then operate in warm-up mode to recover zone temperatures as quickly as possible (called an optimum start) to comfortable levels prior to the start of occupancy. These strategies aim to minimize building envelope losses in cold weather by reducing the amount of time that buildings are maintained at comfortable temperatures and to reduce building energy consumption by minimizing the system operating hours. Optimum start strategies use learning algorithms and real-time measurements to defer starting HVAC systems to minimize runtime. Common airside control strategies then attempt to recover temperatures as fast as possible. The control sequences described in ASHRAE Guideline 36 include a range of strategies to minimize recovery time (ASHRAE 2021a). Warming up a building as fast as possible, however, may not be the most energy-efficient or cost-effective strategy, particularly for decarbonization retrofits. Building heating loads generally peak during the warm-up period. If warm-up loads can be consistently reduced, designers can be more aggressive in equipment sizing, particularly in retrofits of existing buildings where measured loads may be available. Conventional practice for sizing heating equipment assumes unrealistically conservative conditions, sometimes with additional safety factors, and with designers subsequently selecting the “next-size-up” boiler equipment. By conventional wisdom, there is little incentive for designers to rightsize boilers as the incremental first cost for larger equipment is minimal, whereas the consequence of having insufficient capacity during morning warm-up is readily obvious to building occupants and operators. However, rightsizing heat pump equipment is key to cost effectiveness and operational performance. Rightsizing heat pumps and boilers can appreciably improve annual efficiency and equipment longevity, reducing cycling at loads below the minimum turndown limits. See Section 3.4.1 in Chapter 3 for more discussion of rightsizing. Modified morning warm-up control strategies can reduce peak heating coil loads, reducing equipment cost and potentially the need for costly coil and piping replacements if lower hot-water supply temperatures are proven to work. In the most extreme case, disabling night setback altogether and maintaining a constant heating set point eliminates the warm-up/recovery load. For additional information, see Re-Optimizing Optimal Start and Morning Warm-Up (Cheng et al. 2024). On-Site Clean Energy and BESS

A building with on-site PV and a BESS to store clean energy and supply the HVAC system may have been restricted in size as a result of limited roof space for PV and/or location of the BESS. If the system could not be sized to meet the maximum HVAC electrical load, additional power from the grid would be needed in a morning warm-up or cooldown (depending on climate)

period. The GHG emissions attributed to using grid power during warm-up/cooldown should be evaluated against the GHG emissions from leveraging the BESS to operate the HVAC system to maintain temperatures and eliminate or reduce the recovery capacity required. Airside Economizers

Airside economizers are another hallmark of energy efficiency projects. However, economizer operation may not be optimal for GHG emissions, particularly when considering HVAC and storage systems that allow for heat recovery. Again, an hourly analysis of building energy use overlaid with on-site and grid emission factors will be needed to determine when, or if, airside economizers should be used with a project and how they should be optimally controlled. For example, a heat recovery chiller is most efficiently used when there are sufficient cooling and heating loads, either simultaneous or within the time window of an associated TES strategy. During periods or seasons when cooling and heating loads are not balanced, it may be advantageous to reduce or eliminate economizing to provide additional cooling for the heat recovery chiller to operate during periods when grid emissions are low (or on-site clean energy is available). This is especially true when a TES allows for storage of heating energy recovered from the chiller. During periods with large diurnal swings, operating the heat recovery chiller with a higher cooling load might be necessary to produce sufficient hot-water storage to satisfy the next day’s morning warm-up. Control of the airside economizer should be optimized based on GHG emissions and operational costs. Heating Hot-Water Supply Temperature Reset

Heating hot-water supply temperature reset strategies are crucial for AWHP performance. Reducing the heating hot-water supply temperature to reduce the lift the heat pump must meet improves heat pump performance. Supply Air Temperature Reset

Supply air temperature reset strategies provide another opportunity to improve the performance of HVAC systems, both electrified and not. In multiple-zone VAV reheat systems, resetting the cooling supply air temperature reduces cooling plant energy and reheat heating load. Supply air temperature reset also works in concert with hot-water supply temperature reset, where the hot-water supply temperature is more likely to be reset if the reheat loads are lower. More moderate air and water reset temperatures result in more efficient equipment operation when following Guideline 36 sequences. There is a trade-off between supply air/water temperature and fan/pump energy, which is best optimized using Guideline 36 (2021a).

### Table: Data Table

| the cooling sup- e reduces coolin g d reheat heating | Advanced Building Automation Systems: Best Practices Guide, Version 1.0 This guide is intended to serve as a resource for best practices in the imple- Advanced mentation and operation of buildin g Building Automation Systems automation systems (BAS) (Taylor Engi- Best Practices Guide neers 2022). The document highlight s Version 1.0 \| June 13, 2022 key elements of ASHRAE Guideline 36 (ASHRAE 2021a) and addresses other Authored By H Brw ea nk t o En ug b C anh ke sn g - E- uT ba ay nlo kr s E En ng gin ine ee er rs i ng Research key BAS topics, such as some of the Rupam Singla - TRC knowledge barriers to achieving high- performance BAS. |
|---|---|
| temperature rese t ert with hot-water e reset, where th e temperature is reset if the reheat More moderate air mperatures resul t equipment opera- ing Guideline 3 6 is a trade-of f ir/water tempera- | Advanced Building Automation Systems Best Practices Guide Version 1.0 \| June 13, 2022 Authored By Hwakong Cheng - Taylor Engineers Brent Eubanks - Eubanks Engineering Research Rupam Singla - TRC |
| energy, which is |  |

Grid-Interactive Response

Finally, grid-interactive controls paired with the BAS can dispatch equipment and adjust temperatures to optimize the GHG emissions for a building attributed to source energy. Custom equipment dispatch plans can be created to detail when lower-carbon energy sources can be utilized before the use of higher-carbon energy sources. These concepts are covered in detail in Grid-Interactive Buildings for Decarbonization: Design and Operation Resource Guide (ASHRAE 2023h). This guide reviews pricing signals, carbon signals, and emission factors as well as policy mechanisms that drive the design and operation of such smart building systems.

## 6.3 Data Analytics and Monitoring Based/Continuous Commissioning (MBCx)

Maintaining the performance of installed retrofits is a critical aspect of achieving GHG emissions reductions for organizational targets. Maintaining performance can be especially important when faced with potential financial penalties from building performance standards for not meeting required emissions targets. Data analytics and monitoring-based commissioning (MBCx), which can be part of a measure and verification (M&V) plan (highlighted in Section 3.7 in Chapter 3), are powerful tools and approaches for sustaining decarbonization retrofit performance. Data Analytics

Building energy and operations data provide an invaluable source for identifying operational improvements and energy savings potential in buildings. In order to be impactful, data must be stored, structured, and analyzed in ways that provide insights and lead to actions for improvement. An example of this is seen in Case Study 2, 345 Hudson, New York. A key part of the strategy from the beginning of the project has been “connect everything.” The team employed a comprehensive data strategy by connecting all current equipment on a common platform for data collection, monitoring and verifying at every step of the project. This is a first step in a data-driven approach like MBCx to drive sustained performance. MBCx

MBCx is a process that maintains and continuously improves building performance over time. An ongoing commissioning process is put in place with focus on monitoring and analyzing large amounts of HVAC, interval meter, and utility data on a continuous basis to achieve such improvement. For a decarbonization project, marginal emissions should be analyzed together with the other data to determine the GHG emissions performance of the building. Energy management information system (EMIS) tools are used in the MBCx process to organize, present, visualize, and automatically analyze the data. These analyses enable building owners to quickly identify operating anomalies and performance deficiencies and then make corrections to operate their buildings more efficiently.

**[Figure: Lawrence Berkeley National Laboratory: Monitoring-Based Commissioning Plan Template]**

Type: diagram

Description: The figure presents a template for a Monitoring-Based Commissioning (MBCx) plan, which is a process used to ensure that building systems are installed, tested, and functioning as intended. The template outlines the steps involved in the MBCx process, including planning, implementation, and verification.

Key Elements:

*   **Title**: The title of the figure is "Lawrence Berkeley National Laboratory: Monitoring-Based Commissioning Plan Template".
*   **Subtitle**: The subtitle is "Monitoring-Based Commissioning (MBCx) Plan Template".
*   **Logo**: The logo of the Lawrence Berkeley National Laboratory is displayed in the top-left corner of the figure.
*   **Text**: The text in the figure describes the purpose and scope of the MBCx plan template.
*   **Table**: A table is provided to outline the steps involved in the MBCx process.

The figure provides a clear and concise overview of the MBCx plan template, making it easy for users to understand and implement the process.

As outlined in Chapter 3, Figure 3.7, distributed generation and energy storage systems are best incorporated into a decarbonization retrofit once steps are taken to reduce buildings loads and to improve efficiency and/or electrify HVAC and DHW heating equipment. Clean and renewable distributed generation systems constitute a key component for building decarbonization. These systems help reduce carbon emissions but do not provide continuous generation, and their peak generation often does not align with peak building energy use. Combining clean renewable generation systems with energy storage systems, such as batteries, can provide an effective solution for minimizing GHG emissions. Battery energy storage systems (BESS) are a means to store excess electricity generated by clean generation systems and use it for building operation when clean resources are limited or unavailable. Achieving grid-optimal operation requires careful coordination of generation and storage systems with building loads. When designing for energy generation and storage, it is important to include thermal energy as a resource. HVAC systems can take advantage of periods of high clean energy generation or low electricity cost to produce excess thermal energy, in effect converting renewable electricity into thermal energy. Thermal energy storage (TES) systems can supplement HVAC systems to meet heating and cooling loads, increasing capacity for peak loads and replacing capacity at other times, thereby allowing for smaller heat pump sizing and lowering first costs of building electrification. Distributed generation and energy storage systems add complexity to existing building systems, and their advanced control requires training for facility staff to ensure successful operation and maintenance. Retrofit projects do not end with completion of the construction but must provide training to building owners, operators, and occupants on the safe operation, maintenance, and benefits of these systems. Projects also must develop a maintenance plan for routine inspections, testing, and preventive maintenance of the system components. Robust data collection and monitoring are a final component for early identification of potential problems to maintain system performance.

## 7.1 Renewable Systems 7.1.1 Photovoltaic (PV) Systems

Photovoltaic (PV) systems can be incorporated into existing building retrofits to achieve net zero energy and are a versatile on-site clean energy generation source. Adding PV for clean energy generation can offset higher emissions grid source energy depending on location and grid factors (see Chapter 3, Section 3.3.1.1). Where net metering of PV energy production is allowed, pairing PV systems with building electrification strategies can also help offset the difference in utility cost between natural gas

# Chapter 7: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

and electricity and improve the economics of decarbonization projects. This guide considers PV systems as the primary clean and renewable energy source for decarbonization retrofits. One consideration for solar PV systems, particularly in multifamily settings, is the distribution of the generated energy from the system. It is not practical to connect the PV system directly to each tenant meter, which presents challenges for how to distribute or allocate generated power to tenants. It is also not practical to install multiple individual systems to service each tenant/meter. Virtual net metering (VNM) is a solution that allows multifamily buildings to deliver PV energy back to the grid via a single net meter at the property and then allocate the solar credits to the tenants and common area. A VNM agreement must be established with the utility and will require designing for installation of a net metering setup per local utility requirements.

CASE STUDY: Vera Cruz Village, California

The Vera Cruz Village case study includes a rooftop solar PV system with VNM for a multifamily apartment village.

System Sizing

The primary goal of PV systems for decarbonization retrofits is to provide a local clean energy source in place of higher GHG emissions energy sources. Sizing PV systems to costeffectively maximize GHG emissions reduction should be a primary goal, and time-varying carbon emission factors should be considered during the sizing exercise. Roof-mounted PV systems likely will compete for space with HVAC and other rooftop equipment. Determining the optimal PV system size must include sizing and locating this equipment and not just the total rooftop area and building energy needs. Alternatives to rooftop installations, such as ground-mounted systems over parking areas, may provide solutions when evaluating trade-offs between roof-mounted PV systems and other rooftop equipment. Local Policies

On-Site Commercial Solar PV Decision Guide

The guide helps commercial building owners navigate the decisions regarding installing solar photovoltaics (PV) on commercial buildings (DOE 2014). It is intended for anyone investigating the addition of PV to a single or multiple commercial buildings, including building energy managers, facility managers, and property managers in a variety of sectors, including retail, food service, healthcare, higher education, and the public sector.

 On-Site Commercial Solar PV Decision Guide

# 25 SEPTEMBER 2014 

Learn more at energy.gov/betterbuildings

When undertaking decarbonization retrofit programs to comply with local policies, such as BPS, it is important to understand how PV, and other renewable generation, systems are accounted for in the policy. These local policies become one of the KPIs for determining the best combination of measures as discussed in Section 3.4.8. For example, in New York City, Local Law 97 allows deductions for certain clean distributed energy generation such as on-site PV systems. This local policy makes PV systems an attractive ERM to include within a decarbonization retrofit.

Conversely, in the State of Colorado, BPS for on-site renewable electric energy may be accounted for only when following two of three available compliance pathways. Buildings following the eligible compliance pathways must receive approval from the state’s energy office and demonstrate first that they have implemented all cost-effective EEMs based on an ASHRAE Level 2 audit (ASHRAE 2023c). This policy clearly places greater emphasis on other ERMs prior to including PV systems within a decarbonization retrofit. Additionally, state or utility net energy metering policies will affect PV system economics and should be considered. Community-Scale PV Systems

Where rooftop PV space is limited and the alternative solutions suggested above are not feasible, community-scale renewable energy projects provide another solution. Community-scale PV systems use the available space on or near one building to serve buildings with more limited space and thereby increase total PV capacity. These systems can take advantage of larger and more diverse loads to provide cost-effective renewable energy to multiple consumers and reduce reliance on utility power. “To be ‘community-scale’ energy, the generation must be managed or the generation project must at least be instigated by a community: an organized group of residents and/or business owners must be involved in some of the stages of land use planning, acquisition, and installation of renewable equipment, maintenance, and operation of this equipment, and the sale of energy—either electricity or heat—from it” (Wiseman and Bronin 2013). VNM agreements may also be a solution for community solar projects in lieu of directly connecting individual meters to the community-scale system.

### Table: Data Table

| he alternative solution s above are not feasible, scale renewable energ y ovide another solution. -scale PV systems use e space on or near one serve buildings wit h ed space and thereb y tal PV capacity. Thes e take advantage of larger diverse loads to provid e e renewable energy t o nsumers and reduce reli- ity power. “To be ‘com- e’ energy, the generation naged or the generatio n t at least be instigated by y: an organized group o f nd/or business owner s volved in some of th e | A Guide to Community Shared Solar: Utility, Private, and Nonprofit Project Development This guide is an updated version o f the original Guide to Communit y Shared Solar, published November 2010, which was developed for th e A Guide to National Renewable Energy Labora- Community Shared Solar: tory by Northwest Sustainabl e Utility, Private, and Nonprofti Project Development Energy for Economic Development , Keyes and Fox, Stoel Rives, and th e Bonneville Environmental Founda- tion. The guide is a resource to plan , develop, and implement community- shared solar projects. The guide explores the range of incentives and policies for community solar proj- ects while providing examples of operational community-shared solar projects (Coughlin et al. 2010). |
|---|---|

### Table: Data Table

| A Guide to Community Sha Utility, Private, and Nonpro | red Solar: fti Project Development |
|---|---|

### 7.1.2 Other Renewable Systems

Other renewable generation systems may be considered for decarbonization retrofits. These systems are considered secondary to PV applications for decarbonization retrofits and are not likely to have widespread application. These are reviewed in Table 7.1, which includes resources for more details on the technologies and their applications

.

# Chapter 7: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

Renewable Source Description Considerations Resources

Wind Wind turbine generator systems offer opportunities to harness wind energy and contribute clean energy generation. These systems include:

- Building-integrated wind turbines mounted to the building facade or roof
- Freestanding wind turbine generators at the building site

Table 7.1 Other Renewable Generation Sources

Hydrogen Fuel Cells Hydrogen fuel cells convert chemical energy from hydrogen-based fuels to clean electrical energy without combustion. Most fuel cells also produce thermal energy in the form of hot water or steam that can then be recovered and reused.

### Table: Data Table

| Renewable Source | Description | Considerations | Resources |
|---|---|---|---|
| Wind | Wind turbine generator systems offer opportunities to harness wind energy and contribute clean energy generation. These systems include: • Building-integrated wind turbines mounted to the building facade or roof • Freestanding wind turbine generators at the building site | • Require sufficient wind resource for consistent year-round generation • Similar to PV systems, the wind-generation profile likely will not completely align with building energy use • Inclusion of BESS or TES allows for capturing excess wind generation for use during low wind resource periods • Typically higher installation cost and mainte- nance costs compared to PV systems • Placement to minimize turbulence and allow for unobstructed wind flow • Most effective when paired with energy stor- age systems • Accounting of on-site renewable energy for local policies • Building-integrated systems: • Wind loads (static and dynamic) may require structural reinforcement or modifi- cation • Noise and vibration for occupants • Freestanding systems: • Available land area, may be best for large commercial, multifamily, or campuses with ample land • May require setback from occupied space as safety precaution | Technical Report NREL/TP-5000- 65622, Deployment of Wind Turbines in the Built Environment: Risks, Lessons, and Recommended Practices (Fields et al. 2016) |
| Hydrogen Fuel Cells | Hydrogen fuel cells convert chemical energy from hydrogen-based fuels to clean electrical energy without combustion. Most fuel cells also produce thermal energy in the form of hot water or steam that can then be recovered and reused. | • Electricity and heat generation • Quiet operation • Easily scalable • High installation, operating, and maintenance costs compared to PV systems • Requires reliable transportation and storage of hydrogen-enriched fuel | Whole Building Design Guide: Fuel Cells and Renewable Hydrogen (FEMP 2016) |
| Biomass | Biomass is renewable organic material that comes from plants and animals and is a cleaner alternative to fossil fuels. Biomass feed stocks can be used as an energy source directly, such as burning wood, or can be chemically or biologically converted into renewable liquid and gaseous fuels, such as biodiesel or renewable natural gas. | • Burning biomass fuels produces site GHG emissions (some sources consider biomass fuels net zero GHG emissions due to capture of CO when growing plants for biomass fuels) 2 • Requires a sustainable source for biomass fuel production • Fossil fuel systems may be converted to burn biomass fuels | U.S. Energy Information Administration: Biomass Explained (EIA 2023) |
| Municipal Solid Waste Gas | The breakdown of organic waste materials at landfills produces a combination of methane and carbon dioxide known as landfill gas (LFG). | • Burning LFG produces site GHG emissions (“CO emissions from MSW landfills are not 2 considered to contribute to global climate change because the carbon was contained in recently living biomass” [EPA 2024]) • Removes methane, which is a potent GHG • Requires capture, treatment, and delivery of LFG from local MSW landfills • Fossil fuel systems may be converted to burn LFG | U.S. EPA Landfill Methane Outreach Program |
| Municipal Wastewater Gas | The conversion of organic waste to biogas at wastewater treatment plants produces methane that can be captured and converted into renewable natural gas. | • Burning renewable natural gas produces site GHG emissions • Similar to LFG, the process removes methane, which is a potent GHG • Requires capture, treatment, and delivery of renewable natural gas from local wastewater treatment facilities • Fossil fuel systems may be converted to burn renewable natural gas | Argonne National Laboratory: Opportunities for Recovering Resources from Municipal Wastewater (Ha et al. 2022) |

# Chapter 7: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

## 7.2 Battery Energy Storage Systems (BESS)

Battery energy storage systems (BESS) are included as a solution alongside distributed clean generation systems to provide load shifting flexibility and reduce GHG emissions. This integration enables improved use of renewable energy sources and allows them to replace grid energy sources, reduce GHG emissions, and potentially lower energy costs.

BESS are commonly paired with distributed generation systems, such as solar photovoltaic (PV) arrays or wind turbines. The batteries store excess electricity generated by the distributed generation system during periods of low demand or high renewable energy production. This stored energy can then be discharged when demand is high or when renewable energy generation is low, enabling load shifting to optimize energy consumption, reduce grid reliance during peak times, and maximize the use of clean renewable energy sources. Incorporating BESS with distributed clean energy production allows for storing energy when generation exceeds building loads and using stored energy when building loads exceed production. More importantly, the combination of distributed clean energy and storage can be aligned to offset higher-emissions grid source energy and take advantage of cleaner grid generation.

BESS may also be charged directly from the grid, which is a common configuration for systems designed for peak demand reduction to lower or avoid peak demand charges. Grid-charged BESS should be evaluated for the grid emissions during charging and discharging periods to understand their impact on the building grid emission profile. Due to the round-trip efficiency of 80–85% between charging and discharging cycles, a grid-charged BESS may not reduce the GHG emissions for the building(s) it serves.

Shifting from grid source energy to cleaner generation through renewable resources such as solar and wind will influence grid emission factors throughout the day. The classic example of this is the “duck curve” shown in Figure 7.1, demonstrating the impact of increased PV generation for the grid. Stand-alone BESS (not paired with on-site generation systems) provide a means to recover the overproduction of clean energy during the midday period and use it to power building HVAC systems during the afternoon/evening peak and morning warm-up periods. Figure 7.2 demonstrates this concept, showing CAISO’s battery trend for March 15, 2023. The battery charging periods correspond to the overproduction in Figure 7.1, and the discharge periods correspond to the discharge periods in Figure 7.2.

Additionally, BESS can provide other valuable services, including demand charge management, frequency regulation, voltage support, and backup power during grid outages. These functionalities enhance the building’s resilience and contribute to a more sustainable and reliable energy infrastructure, as follows:

- Demand Charge Reduction. BESS can be charged during off-peak periods and discharged during peak demand events to mitigate demand charges, reducing total electricity costs. With optimized controls, the BESS can effectively shave peak loads with a relatively small energy capacity. For stand-alone BESS, it is important to evaluate grid emission factors during charging and discharging periods to ensure that demand charge savings are co-optimized with emissions savings because grid-charged systems may not reduce GHG emissions. Pairing BESS with clean energy production may be a better option to provide both peak shaving and GHG emissions reduction.

- Load Shifting. For buildings with on-site renewable generation such as solar photovoltaics, BESS can be charged directly by the renewable system and discharged to offset grid electricity usage during other periods. This load shifting reduces overall dependence on utility power and associated carbon emissions. Similarly, for buildings without on-site renewable

**[Figure: The "Duck Curve"]**

Type: chart

Description: This line chart illustrates the net load on the California Independent System Operator (CAISO) grid over a 24-hour period, from midnight to 11 PM, on March 31. The chart compares the actual net load in 2012 and 2013 with projected net loads from 2014 to 2020. The key insight is that the net load follows a distinctive "duck curve" shape, characterized by a sharp decline in the middle of the day due to increased solar power generation.

Data Representation:

*   2012 (actual): 22,000 MW
*   2013 (actual): 21,500 MW
*   2014: 20,500 MW
*   2015: 19,500 MW
*   2016: 18,500 MW
*   2017: 17,500 MW
*   2018: 16,500 MW
*   2019: 15,500 MW
*   2020: 14,500 MW

Metric: Net load (MW)

Chart Type: Line chart

Units: Megawatts (MW)

Chart Generation Hint:

*   X-axis: Time of day (hours)
*   Y-axis: Net load (MW)

Structured Data (Machine Readable):

```json
{
  "chart_type": "line",
  "metric": "net_load",
  "units": "MW",
  "data": {
    "2012": 22000,
    "2013": 21500,
    "2014": 20500,
    "2015": 19500,
    "2016": 18500,
    "2017": 17500,
    "2018": 16500,
    "2019": 15500,
    "2020": 14500
  }}
}

**[Figure: California Battery Storage Trend: March 15, 2023]**

Type: chart

Description: This line chart illustrates the trend of battery storage in California on March 15, 2023. The chart compares the amount of energy discharged from batteries (in blue) with the amount of energy charged into batteries (in light blue) over a 24-hour period.

Data Representation:

*   Discharging: 1250 MW
*   Charging: 2500 MW
*   Metric: Energy (MW)
*   Chart Type: Line Chart
*   Units: Megawatts (MW)

Chart Generation Hint:

*   X-axis: Time (hours)
*   Y-axis: Energy (MW)

Structured Data (Machine Readable):

```json
{
  "chart_type": "line_chart",
  "metric": "energy",
  "units": "megawatts",
  "data": {
    "discharging": 1250,
    "charging": 2500
  }}
}
```

This chart provides a visual representation of the battery storage trend in California on March 15, 2023, highlighting the fluctuations in energy discharge and charge throughout the day.

# Chapter 7: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

**[Figure: Estimated costs of commercial stand-alone BESS using NREL bottom-up model from 2023 Annual Technology Baseline for commercial battery storage]**

Type: chart

Description: The chart compares the estimated costs of commercial stand-alone Battery Energy Storage Systems (BESS) using the NREL bottom-up model from the 2023 Annual Technology Baseline for commercial battery storage. The key insight is that the cost of BESS varies significantly depending on the duration of the system, with longer-duration systems being more expensive.

Data Representation:

*   1-hour Duration, 300-kWh: $1,645
*   2-hour Duration, 600-kWh: $2,035
*   4-hour Duration, 1200-kWh: $2,687
*   6-hour Duration, 1800-kWh: $2,888
*   8-hour Duration, 2400-kWh: $3,295

Metric: Cost

Chart Type: Bar

Units: Dollars per kilowatt-hour ($/kWh)

Chart Generation Hint:

*   X-axis: Duration (hours)
*   Y-axis: Cost ($/kWh)

Structured Data (Machine Readable):

```json
{
  "chart_type": "bar",
  "metric": "cost",
  "units": "$/kWh",
  "data": {
    "1-hour Duration, 300-kWh": 1645,
    "2-hour Duration, 600-kWh": 2035,
    "4-hour Duration, 1200-kWh": 2687,
    "6-hour Duration, 1800-kWh": 2888,
    "8-hour Duration, 2400-kWh": 3295
  }}
}
```

This chart provides a clear visual representation of the estimated costs of commercial stand-alone BESS, allowing users to quickly compare the costs of different system durations. The structured data format makes it easy to import and analyze the data in various software tools.

generation, BESS can be charged during low-carbon/low-cost periods and discharged during high-carbon/high-cost periods.

- Backup Power. BESS can provide emergency backup power for critical systems in the event of utility outage. If tied to renewable generation, the system can continue operating in island mode with zero emissions. The BESS must have sufficient capacity to power essential building functions until the outage is resolved or additional generation is deployed. This may require a certain percentage of battery capacity to be held in reserve for emergency power, thereby limiting its ability to be used for other value streams.
- Grid Services. For utility interactive buildings, BESS can participate in demand response programs by dispatching power to the grid during peak events. The building can thereby earn revenue to support its sustainability and decarbonization efforts. BESS control systems must be properly designed to manage these grid interactions.

As the cost of battery technologies continues to decline and their efficiency and capacity increase, BESS are becoming more accessible and cost-effective. The National Renewable Energy Laboratory (NREL) 2023 Annual Technology Baseline for commercial battery storage represents cost and performance for battery storage across a range of durations. As shown, the cost per kilowatt-hour significantly decreases as storage duration increases, so it is important to determine the necessary duration to develop an accurate system cost (NREL 2023a).

When implementing BESS, it is crucial to consider factors such as system sizing, design integration, controls, monitoring, and compliance with safety standards. Local policies may also influence the design and implementation of BESS on-site. System Sizing and Design

On-Site Energy Storage Decision Guide

The guide helps commercial building owners and managers investigate the addition of energy storage to a single or multiple commercial buildings. This could include building energy managers, facility managers, and property managers in a variety of sectors. A variety of incentives, metering capabilities, and financing options exist for installing energy storage at a facility, all of which can influence the financial feasibility of a storage project. However, energy storage is not suitable for all business types or all regions due to variations in weather profiles, load profiles, electric rates, and local regulations.

On-Site Energy Storage Decision Guide

BESS sizing is based on numerous factors, including the building’s energy requirements, load profiles, building emission profile, critical loads, and level of desired resilience. When integrating BESS with on-site clean energy such as PV, the system sizing focuses on the following factors:

APRIL 2017

- Peak load met with BESS
- Depth of discharge for batteries
- Duration of power supply from BESS

In this scenario, the BESS is designed to cycle daily rather than supplying multiple days of backup power. The peak load will be either during the morning warm-up period or the afternoon peak, when grid emissions are high. The depth of discharge will depend on the battery technology selected and whether the morning warm-up or afternoon peak requires the longer duration of power. Analyze the building’s hourly energy demand data over the course of the year during these periods to determine the appropriate size and capacity of the BESS. Evaluate different battery technologies—such as lithium-ion, lead acid, and flow batteries—considering such factors as energy density, cycle life, efficiency, and cost. Choose a battery technology based on factors including energy capacity, power rating, efficiency, and cycle life to align with the building’s specific needs and budget. Design the battery energy storage system and integrate it with the building’s electrical infrastructure. Ensure compatibility with existing equipment, such as inverters, switchgear, and control systems. Battery System Location

**[Figure: Handbook on Battery Energy Storage Systems]**

Type: diagram

Description: This handbook outlines the various battery energy storage technologies, their application, and the caveats to consider in their development. It discusses the economic as well as financial aspects of battery energy storage system projects and provides examples from around the world (ADB 2018).

Key Elements:

- Cover Page -> The cover page features a collage of images related to battery energy storage systems, including batteries, solar panels, and wind turbines.
- Title -> The title of the handbook is prominently displayed on the cover page, indicating that it is a comprehensive guide to battery energy storage systems.
- Author -> The author of the handbook is not explicitly mentioned on the cover page, but it is likely that it was written by experts in the field of energy storage.

The location of the BESS within a building, or on the property, is an important aspect of the design. BESS tend to have a relatively small footprint, making them easy to accommodate within a

# Chapter 7: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

building. However, noise from BESS can be a particular concern for building occupants and, in some cases, local noise ordinances. Evaluate the sound emission profile for the BESS and compare to ambient noise levels for the building. Depending on the BESS sound profile relative to ambient levels, sound mitigation measures may need to be incorporated into the installation to minimize disturbance for occupants. Temperature is also a factor to consider with BESS siting. Battery performance and storage capacity are increased as temperature increases. However, the battery lifespan degrades with increased temperatures. Conversely, battery performance and storage capacity decrease with colder temperatures, but battery lifespan improves. Temperature ranges for optimum performance depend on the battery type used and should be factored into selection and siting. One solution to BESS facing extreme temperatures in certain climates can be to locate the system within the building. BESS located within the building also will require mechanical ventilation to handle the heat load from the batteries. During heating season, this may represent an opportunity for heat recovery from the BESS room, but during cooling season it can represent a significant cooling load for the building. Local fire codes are an additional driver of battery system location, especially for installations inside the building. Controls and Monitoring

A key component of BESS operation includes advanced control and monitoring systems that optimize battery operation based on real-time energy demand, grid emission factors (marginal factors if available), on-site clean energy production, other site conditions, and tariff structures. For systems that also will be connected to the grid, establish proper grid interconnection to enable bidirectional energy flow between the battery system and the utility grid. See ASHRAE’s GridInteractive Buildings for Decarbonization: Design and Operation Resource Guide for more details on BESS controls for grid interactivity to reduce GHG emissions (ASHRAE 2023d). The advanced controls will provide charging and discharging strategies to maximize the value of the battery system. BESS controls may be integrated with BAS to enable seamless communication and coordination with other building systems. When integrating BESS and multiple other systems—such as on-site PV generation, TES, and HVAC equipment—microgrid controllers can manage individual equipment and building systems as a whole to achieve optimal operation for reducing GHG emissions.

IEEE STD 2030.2.1, Guide for Design, Operation, and Maintenance of Battery Energy Storage Systems, both Stationary and Mobile, and Applications Integrated with Electric Power Systems

This guide provides alternative approaches and practices for design, operation, maintenance, integration, and interoperability, including distributed resources interconnection of stationary or mobile BESS with the electric power system(s) at customer facilities, electricity distribution facilities, or bulk transmission electricity facilities (IEEE 2019).

### Table: Data Table

| IEEE Guide for Design, Operation, STANDARDS and Maintenance of Battery Energy Storage Systems, both Stationary and Mobile, and Applications Integrated with Electric Power Systems IEEE Standards Coordinating Committee 21 DIF EueEevEle CSloteap llne sd,d aP brhdy o st t h oCe vo oolrtdaiincsa,t Dinigs pCeormsemd iGtteenee 2r1at oionn , and Energy Storage IEEE Std 2030.2.1™-2019 |  |  |  |
|---|---|---|---|

## 7.3 EV Charging Systems

The decarbonization of commercial and multifamily residential buildings will include energy and operational conservation measures for electric vehicles (EVs) and charging stations or electric vehicle supply equipment (EVSE). Methodologies for incorporating EVSE into building electrical systems play a major role in building decarbonization efforts. Past studies have indicated different points of analysis for this process: interfacing with existing loads, analyzing existing facility electrical infrastructure, implementation costs and operational savings, and operational changes.

**[Figure: EV Charging Scenarios]**

Type: diagram

Description: The diagram illustrates three different scenarios for charging electric vehicles (EVs), highlighting the benefits of using renewable energy sources and the potential for energy storage and grid regulation.

Key Elements:

*   **Scenario 1: Plug-in Your Bidirectional Vehicle to Recharge the Battery for During a Hazard**
    *   A car is plugged into a charging station, with a battery icon indicating the flow of energy.
    *   Purpose: To show how EVs can be used as a source of energy during power outages or emergencies.
*   **Scenario 2: Charging a Bidirectional Vehicle When Renewable Production Exceeds the Building Demand is an Opportunity Store Electricity in the Vehicle to Drive or Use as a Battery**
    *   A wind turbine and solar panel are shown generating electricity, which is then stored in an EV battery.
    *   Purpose: To demonstrate how renewable energy can be harnessed and stored in EVs for later use.
*   **Scenario 3: V2B Saves Money by Reducing Power Consumption in the Building. Energy Can Be Drawn from the EV When the Battery Is Full**
    *   A building is shown with a V2B (Vehicle-to-Building) system, where energy is drawn from an EV battery to power the building.
    *   Purpose: To illustrate how V2B technology can reduce energy consumption and save money by using stored energy from EVs.

Overall, the diagram highlights the versatility and potential of EVs as a source of energy, not just for transportation but also for powering buildings and providing backup power during emergencies.

Electric vehicles play a role in decarbonization through reducing vehicle emissions. For many building decarbonization retrofits, the focus for electric vehicles is bidirectional charging. As the name implies, bidirectional EV charging allows EVs to be charged via the building electrical system and to discharge their stored energy back to the building (or grid) as needed. In this way, a fleet of EVs may operate similar to BESS. Leveraging bidirectional EV charging as a form of mobile battery storage is most applicable for campuses, portfolios, or large buildings with a fleet of EVs that have sufficient aggregate capacity and are regularly available for use as a form of BESS. Electric vehicle-to-grid (V2G) technologies can be incorporated into microgrids to share energy loads from bidirectional charging and discharging of electric vehicle batteries among the grid, on-site generation, and electric vehicles.

Before installing an EV infrastructure, one must analyze the physical space availability, requirements, and existing building electric loads to determine the potential impacts of EV infrastructure installation. ANSI/ASHRAE/ICC/USGBC/IES Standard 189.1 offers guidance for electrical infrastructure for both EV parking and charging. Initially, perform an analysis on what the charging need is at the project location using the expected total demand per day, according to the type of vehicle, total number of vehicles, and the demand profile. Calculate the updated load impact of the additional equipment and determine whether the existing infrastructure can handle

# Chapter 7: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

the new equipment or if additional work needs to be done to upgrade the infrastructure or with the respective utility to increase capacity. Three main types of charging systems are available on the market today (CSE 2019):

- Level 1. Uses a 120V regular wall-connected outlet to charge the EV. It has the slowest charging rate, and a typical full charge can take upwards of eight hours, so this charger is a good option for use in residential buildings or as a backup charger.
- Level 2. This is the most common type of charging speed and requires a 208/240V outlet. Almost 80% of all charging stations have Level 2 chargers. An hour of charging can provide anywhere from 10 to 54 miles (16 to 87 km) of range.
- Level 3 (DC Fast Chargers). DC fast chargers convert the AC voltage from the grid into DC voltage, typically within a wide range. They require a minimum 480V AC circuit and a dedicated electrical panel within the building.

CASE STUDY: STAR Transit, Texas

The STAR Transit case study includes a bus transportation service in Texas in the process of electrifying its bus fleet. Available funding is being applied to the installation of a PV system. The case study demonstrates the benefit and importance of adding battery storage to best harness the PV generation for fleet charging.

## 7.4 Grid-Interactive Systems

Grid-interactive systems can range from a single distributed energy resource (DER) connected at a local load to complicated systems with multiple DERs serving a large campus. The basic requirement of grid-interactive systems is to incorporate grid signals into the control of building loads, generation, or storage systems, while maintaining building services and occupant comfort. Grid signals include time-varying carbon emission factors, demand response calls, and dynamic utility rates. Incorporating data from these signals into the design phase of retrofit projects will help identify control strategies that can reduce emissions and costs and ensure that equipment and system selections are able to achieve the communication and connectivity required for gridinteractivity. Co-optimizing control strategies to minimize cost and carbon is recommended, as these signals are often, but not always, correlated. Grid-interactive systems can have a wide array of stakeholders, ranging from building owners, building tenants, facility managers, and third-party DER owners or operators to utility providers. Coordination across these stakeholders is critical to ensure that grid-interactive operation is safe, reliable, and comfortable, while reducing emissions and costs. See ASHRAE’s GridInteractive Buildings for Decarbonization: Design and Operation Resource Guide (ASHRAE 2023h) for details on grid-interactive design for different building systems, ranging from standalone devices to integrated systems with central controllers.

Distributed Generation and Energy Storage Sizing Tools

Several software tools and methods exist for optimizing the sizing and other trade-offs between various distributed generation and energy storage systems. These tools consider utility tariffs, relative costs, and coordinated dispatch across these resources to optimize system selections, sizes, and configurations. Paid tools are available to support these design decisions. Free tools developed by DOE National Laboratories include:

- Renewable Energy Integration and Optimization Tool (REopt®). Developed and used by NREL to optimize energy systems for buildings, campuses, communities, microgrids, etc. Find the tool at https://reopt.nrel.gov/ (NREL 2023d).
- Distributed Energy Resources Customer Adoption Model (DER-CAM). Developed and used by Lawrence Berkeley National Laboratory as a powerful and comprehensive decision support tool that primarily serves the purpose of finding optimal distributed energy resource (DER) investments in the context of either buildings or multi-energy microgrids. Find the model at https://gridintegration.lbl.gov/der-cam (LBNL 2023).

## 7.5 Thermal Energy Storage Systems

Thermal energy storage (TES) systems can store excess thermal energy generated by HVAC equipment and distributed renewable sources, such as solar thermal systems or waste heat recovery systems. This stored energy can be used later for space heating/cooling or water heating, allowing for load shifting and reducing the need for other heating or cooling equipment during peak demand periods. TES provide flexibility in meeting the heating and cooling demands of buildings, allowing for energy recovery and supplemental thermal capacity for HVAC systems. Many traditional energy efficiency projects pursued the elimination of simultaneous heating and cooling, or thermal overlap, as periods of wasted energy. However, this mindset changes when applying TES to decarbonization retrofit projects. The heat recovery potential for TES, combined with heat recovery chillers and the profile of grid emission factors, may make periods of thermal overlap desirable. During different seasons or times of day, when heating and cooling loads are not balanced, increasing cooling loads with adjustments to HVAC control strategies (see Section 6.2 in Chapter 6) during periods of low GHG emissions can also increase the heat generated for recovery with the TES to meet future heating loads.

# Chapter 7: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

By storing excess thermal energy during periods of cleaner grid operation or when on-site renewable energy sources are abundant, TES systems can reduce the emissions from heating or cooling equipment during higher GHG emissions times. The ability to shift the time of energy use and, therefore, the corresponding grid emission factors for the energy use for heating and cooling is one of the key decarbonization benefits of TES systems. The ASHRAE Journal article “Electrification, Heat Pumps and Thermal Energy Storage” (MacCracken 2020) provides an excellent reference. The selection of appropriate storage media and materials, as well as the control strategies for charging and discharging, are important factors for sizing TES storage tanks and maximizing the effectiveness and efficiency of TES systems. Proper modeling, equipment selection, and controls design are critical early steps. The most effective TES integrations require holistic analysis of hourly building loads, HVAC equipment capacities, building emission profiles, costs, and long-term flexibility. TES storage tank size must be balanced relative to quantity and space requirements of HVAC and electrical equipment on rooftops or in mechanical rooms. The complexity of controls operation for TES systems also must be addressed with building operation and maintenance staff. TES system effectiveness relies on responding to environmental and/or grid conditions, and interventions or equipment disruptions can result in significant impacts to GHG emissions and energy costs. By following these strategies and steps, design teams can proactively address challenges and successfully integrate TES systems into existing commercial and multifamily building retrofits, leading to improved energy efficiency, reduced GHG emissions, and enhanced sustainability.

Thermal Energy Storage: Systems and Applications, Third Edition

Thermal Energy Storage: Systems and Applications provides engineers with upto-date information on methods, models, and approaches in TES systems and their applications in thermal management and elsewhere. The third edition contains detailed coverage of integrated systems with energy storage options, environmental impact and sustainability, design, analysis, assessment criteria, advanced tools in exergy and extended exergy, and more. New and expanded chapters address topics such as renewable energy systems in which thermal energy storage is essential; sensible and latent TES systems; and numerical modeling, simulation, and analysis of TES systems (Dinçer and Rosen 2021).

**[Figure: Thermal Energy Storage Systems and Applications]**

Type: diagram

Description: The figure presents a comprehensive overview of thermal energy storage systems and their applications, showcasing various components and technologies involved in this field.

Key Elements:

- **Thermal Energy Storage Systems**: These are designed to store thermal energy for later use, often in the form of heat or cold.
- **Applications**: The diagram highlights various applications of thermal energy storage, including heating, cooling, and power generation.
- **Components**: It illustrates key components such as tanks, pipes, and heat exchangers that are integral to these systems.
- **Technologies**: The figure also depicts different technologies used in thermal energy storage, including sensible heat storage and latent heat storage.

### 7.5.1 Sensible Heat Storage (SHS)

Sensible heat storage (SHS) involves storing thermal energy in a solid or liquid medium, such as water or rocks. Energy transfer is more efficient in liquids than solids, though the former often can experience greater losses. Examples of solid storage substances include crushed rocks and firebricks, while examples of liquid storage substances include water, oil, and molten salt. Water storage systems are more common. Heating Hot-Water Storage

Heating hot-water storage can play a significant role in existing building decarbonization. Heating hot-water system loads are often less than cooling loads, and these systems typically have a larger temperature differential. As a result, TES hot-water storage tanks can be much smaller compared to chilled-water storage tanks. This can make hot-water storage easier to accommodate within existing buildings and a very good option to combine with HVAC systems. Hot-water TES systems typically operate in ranges between 130°F and 160°F (54.4°C and 71.1°C) and can be paired with a variety of heating sources, whether existing boilers, heat pump systems, or heat recovery chillers. These all represent opportunities for different strategies of heat recovery with TES. Peak Shaving

**[Figure: Thermal Storage]**

Type: diagram

Description: The diagram illustrates the thermal storage capacity of a system, with a focus on hot water generation in megawatt-hours (MWh). The x-axis represents the month, day, and hour, while the y-axis shows the hot water generation in MWh. The diagram features a red cylinder representing the thermal storage tank, accompanied by a bar graph displaying the hot water generation over time.

Key Elements:

*   Red cylinder: represents the thermal storage tank
*   Bar graph: displays the hot water generation over time, with different colors indicating various components of the system (using stored heat, charging heat storage, and heat pump heating)

The diagram provides a visual representation of the thermal storage capacity and its relationship to hot water generation, allowing for easy comparison and analysis of the system's performance over time.

Hot-water TES can be used to shave or level the heating load met by heat pumps or even existing boilers. The heating system operates with a relatively constant heat output that is less than the peak building heating load and greater than the minimum heating load. The TES system recovers excess heat produced during periods of lower heating load and discharges it during the peak heating load period (see Figure 7.5). TES effectively increases the capacity of the heating system. This can be a key strategy for existing building decarbonization retrofits. Including a hot-water TES system allows heat pump equipment to be sized to meet a reduced heating load. Reducing heat pump size can be important when space constraints on rooftops or in mechanical rooms restrict equipment sizes. For rooftop equipment where structural loads are a concern, reducing heat pump size and weight can avoid the need for structural upgrades to the building roof. Simultaneous Heating and Cooling

Hot-water TES can be used with heat recovery chillers to capture heat during cooling. This strategy is particularly effective in buildings with significant temperature variations throughout the day or seasonal variations in heating and cooling needs. For example, during shoulder seasons or in climates with large diurnal swings, there will be morning heating and afternoon cooling. Hotwater TES captures heat generated by the heat recovery chiller during afternoon cooling periods for use during morning heating. Depending on the size of the heating and cooling loads, the TES may fully meet the heating load or may add capacity to and optimize the use of HVAC systems and reduce the GHG emissions for meeting a building’s heating and cooling needs. Hot-water TES tank sizing in these scenarios is based on an hourly heating load analysis. The tank size must balance available space for the tank, a potential reduction in heat pump size or number of heat pumps, and the difference in both capital expense and operating expense for the TES compared to meeting the load with a heat pump or other HVAC equipment. Figure 7.6 provides an example of a small hot-water TES tank included in a mechanical room design with ASHP and electrical equipment.

# Chapter 7: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

**[Figure: Example HVAC system layout with TES tank]**

Type: diagram

Description: The diagram illustrates a detailed layout of an HVAC (Heating, Ventilation, and Air Conditioning) system that incorporates a Thermal Energy Storage (TES) tank. The system is designed to optimize energy efficiency and provide a reliable cooling solution.

Key Elements:

*   **TES-HW**: The TES-HW component represents the Thermal Energy Storage tank, which plays a crucial role in storing thermal energy for later use. This component is essential for reducing peak energy demand and improving overall system efficiency.
*   **Screen Wall**: The screen wall is a critical component that separates the TES tank from the rest of the system. It helps to maintain a consistent temperature and humidity level within the tank, ensuring optimal performance.
*   **Electrical Service/Transformers**: The electrical service and transformers are responsible for providing power to the HVAC system. They play a vital role in ensuring that the system operates efficiently and effectively.
*   **ASHP**: The Air Source Heat Pump (ASHP) is a key component of the HVAC system. It provides both heating and cooling capabilities, making it an efficient and versatile solution for temperature control.
*   **DER**: The Distributed Energy Resource (DER) represents a decentralized energy source that can be integrated into the HVAC system. This component can help to reduce reliance on traditional energy sources and promote sustainability.

Overall, the diagram provides a comprehensive overview of the HVAC system's layout and components. It highlights the importance of the TES tank, screen wall, electrical service, ASHP, and DER in achieving optimal performance and energy efficiency.

Chilled-Water Storage

Chilled-water storage systems can be used for peak shaving or peak shifting with heat pumps and chillers by storing water at the required chilled-water set point (generally between 40°F and 45°F [4.4°C and 7.2°C]). Because chilled water requires less lift from the chiller, a chilled-water storage tank can be more efficient than an ice storage system but is commonly much larger (typically about eight times larger). Similar to hot-water storage, chilledwater storage systems can be used for peak shifting and peak shaving of cooling loads. These strategies should be evaluated based on grid emission factors and for pairing with on-site clean energy production combined with electrical energy storage, such as BESS.

ASHRAE Design Guide for Cool Thermal Storage, Second Edition

The guide provides design engineers with the latest information in designing, modeling, costing, and commissioning cool thermal energy storage systems. With a particular focus on ice and chilled water systems, this guide is a comprehensive, first-level reference that discusses thermal energy storage fundamentals, compares thermal energy storage technologies, and describes an applications-focused procedure for designing cool thermal energy storage systems (Glazer 2019).

RP-1719

ASHRAE Design Guide Cool Thermal Storage for

Jason Glazer, PE, BEMP

Second Edition

**[Figure: Direction of heat flow for condenser water TES]**

Type: diagram

Description: This diagram illustrates the direction of heat flow in a condenser water thermal energy storage (TES) system. The image shows the flow of heat from the condenser water to the TES tank, and then back to the condenser water.

Key Elements:

*   Condenser water -> Heat source
*   TES tank -> Heat storage
*   Heat exchanger -> Heat transfer

This diagram provides a clear visual representation of the heat flow in a condenser water TES system, highlighting the key components involved in the process.

To ensure appropriate flow distribution, storage tanks should be designed to maximize the system’s performance through thermal stratification, and internal baffles may be used. ASHRAE’s Design Guide for Cool Thermal Storage is a resource for chilled-water TES design (Glazer 2019).

Condenser Water Storage

Hot-water and chilled-water TES systems store water at the temperatures needed for heating and cooling end uses. These systems can require substantial insulation and must be charged using chilled water or hot water directly produced by HVAC equipment. Condenser water TES systems instead store water at temperatures closer to 80°F (26.7°C). The condenser water TES does not serve heating and cooling loads directly; instead, it serves as a heat sink for chillers and heat pumps and a heat sink/source for water-cooled heat recovery chillers as seen in Figure 7.7. These systems have good applications in buildings with diurnal temperature swings when heating and cooling are needed. During cooling periods, both chillers and heat recovery chillers reject heat into the tank (and cooling tower) as needed. During heating periods, the heat recovery chiller supplies heat to the building and rejects chilled water to the TES tank. These systems can be a very effective solution in many existing building retrofits. The ASHRAE Journal article “Solving the Large Building All-Electric Heating Problem” provides an excellent reference (Gill 2021).

CASE STUDY: 345 Hudson, New York

The 345 Hudson case study demonstrates a condenser water TES system that serves WSHPs at each floor of the building. The thermal network provides high-temperature cooling water for radiant chilled beams and low-temperature heating water for perimeter radiators. An ASHP provides heating to the thermal network.

Building-Mass Thermal Storage

Where an existing building has a large thermal mass, such as concrete walls or masonry, building-mass thermal storage may be explored to take advantage of the existing building structure. Building thermal storage is the usage of building mass (i.e., the structure and furnishings) as thermal storage materials. This strategy is only applicable to certain existing buildings and would not

# Chapter 7: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

be a retrofit strategy. Hourly analysis of building heating and cooling loads will be required to understand whether the building thermal mass can store sufficient energy to appreciably serve cooling or heating loads.

During summertime, the HVAC equipment can be used to overcool or precool the building during nighttime when it is typically unoccupied. This helps save cooling costs during the daytime when the building is occupied. Depending on the weather, precooling can also be done by increasing the ventilation rate when the temperature at night is much lower than the indoor temperature, in a process called night flush ventilation. Conversely, in cold climates, high-thermal-mass materials can absorb solar energy during the day, which can then help reduce heating costs as the outdoor temperature begins to fall during the evening. An important factor to consider when using building mass as a thermal storage material is the effect on human comfort. Precooling a building or storing additional heat in the building mass may be undesirable from a comfort perspective due to the slow nature of heat transfer.

Thermally Activated Building Systems

Thermally activated building systems (TABS) are a combination of hydronic heating/cooling and thermal mass. Hydronic pipework is embedded within materials with high thermal mass and used to charge the material with heat or cold to regulate indoor air temperature. The heavy thermal mass required for many TABS makes them impractical for retrofit projects unless a complete renovation is being performed.

### 7.5.2 Latent Heat Storage (LHS)

Latent heat storage (LHS) systems use phase-change materials to store and release thermal energy during melting or solidification. Change in phase typically occurs at a constant temperature and is usually associated with a significantly greater energy transfer than sensible heat transfer. Latent heat storage materials are typically solids or liquids. As the material’s phase changes from a solid to a liquid, its density decreases.

### Table 7.2    LHS Thermal Storage Media

| Thermal Storage Medium | Typical Temperature Range | Density | Specific Heat | Relative Cost | Key Characteristics |
|---|---|---|---|---|---|
| Ice | 32°F (0°C) | 57.2 lb/ft3 (916.3 kg/m3) | 0.5 Btu/lb°F (2.09 kJ/kg°C) | Moderate | • Compact. • Phase change pro- vides high capacity. • Requires careful con- trols. |
| Molten Salts | ~1200°F (~648.9°C) | 71–83 lb/ft3 (1137–1330 kg/ m3) | 0.5–1.0 Btu/lb°F (2.09–4.19 kJ/ kg°C) | High | • Very high-temperature operation. • Corrosion concerns. |
| Phase- Change Materials | Variable | 25–100 lb/ft3 (400–1602 kg/ m3) | 10–150 Btu/lb (23.3–348.9 kJ/ kg) | High | • High latent heat capac- ity in small volumes. • Limited temperature range. |

Ice Storage

The most common LHS material is ice. Ice is a relatively cheap and compact material that changes phase at 32°F (0°C), which makes it easy to use in buildings. Different configurations of ice storage systems exist, the most popular of which can be found in the ASHRAE Handbook— HVAC Systems and Equipment. These include ice-on-coil internal melt, ice-on-coil external melt, encapsulated ice storage, and ice harvesters (ASHRAE 2020b). Ice TES systems require smaller tank sizes than chilled-water TES tanks, which can make them an attractive option for cooling TES when space is limited. While the tank sizes are smaller, ice storage systems typically operate with a glycol loop and heat exchanger to serve building loads. These add complexity for system design and maintenance. The maintenance cost and ease of adoption for building operations and maintenance staff are factors when evaluating ice storage TES versus chilled-water TES as a decarbonization strategy.

### 7.5.3 Thermochemical Heat Storage

Thermochemical heat storage uses chemical reactions to store and release heat energy. It can be beneficial in scenarios where there is a need for long-duration heat storage because it depends on chemical reactions rather than retaining thermal energy in a medium such as water. However, thermochemical storage systems are a much less common technology and require careful design, installation, and operation that may make other TES systems more suitable for existing building retrofits.

### 7.5.4 TES Integration with District Heating and Cooling (DHC) Systems

TES systems also find good applications in district heating and cooling systems, where chilled-water TES or hot-water TES tanks can be adjoined to central plants serving multiple buildings. The application of chilled-water and hot-water TES for district heating and cooling plants is similar to individual building systems. The TES systems are of greater scale but still serve to provide peak shaving and heat recovery capabilities to district plants. The district scale for these integrated systems presents opportunities for other solutions for TES, due in part to the expanded opportunity for heat recovery. When multiple buildings are connected, heat recovery may take place within individual buildings and between the buildings and the district loop. Ambient Loop Systems

Ambient loop systems operate with loop temperatures around 70°F (21.1°C), much like the condenser water TES system discussed in Section 7.5.1. These systems interconnect multiple buildings and act as a heat sink or source for each building, depending on its heating or cooling needs. Ambient loop systems leverage WSHPs and heat recovery chillers within individual buildings that are connected to the loop. Ambient loop systems are most effective when serving multiple building types with different heating and cooling load profiles to maximize the opportunity for heat recovery. Campus applications are likely a prime candidate for ambient loop systems due to their wide variety of building types. A significant opportunity for district heat recovery exists with data centers. Data centers generate heat year-round and can serve as a significant source for an ambient loop when the majority of connected buildings require heating. Municipal wastewater treatment plants also present a year-round heat source that may provide heat for an ambient loop. Ambient loop systems can also have multiple heat sources, including heat recovery from connected buildings or heat input from district heating plants, solar thermal systems, or ground-source loops. Where ground-source loops are likely to be prohibitive in land area and cost for many individual building applications, they can be more cost-effective when supplying heating and cooling to multiple buildings. For district systems serving multiple building types with different heating

# Chapter 7: Decarbonization Strategies and Technologies: Distributed Generation and Energy Storage

**[Figure: Diagram of ambient loop system]**

Type: diagram

Description: The diagram illustrates the components and flow of an ambient loop system, which is a type of heating and cooling system that utilizes the natural temperature of the earth to provide thermal energy. The system consists of a network of underground pipes that circulate a fluid through the earth, where it absorbs or releases heat depending on the season.

Key Elements:

* **Ground Source Heat Pump**: This is the central component of the system, responsible for transferring heat between the earth and the building.
* **Underground Pipes**: These pipes are buried in the earth and circulate the fluid that absorbs or releases heat.
* **Building**: This represents the structure that is being heated or cooled by the ambient loop system.
* **Earth**: This is the natural source of thermal energy that the system utilizes.

The diagram shows how the system works by illustrating the flow of heat between the earth, the ground source heat pump, and the building. It also highlights the benefits of using an ambient loop system, such as reduced energy consumption and lower greenhouse gas emissions. Overall, the diagram provides a clear and concise visual representation of the components and operation of an ambient loop system.

and cooling load profiles, there can be an increased flexibility to balance heating and cooling loads, which is important when using ground-source loops. At district scales, longer term ground source TES may also be economical. Underground aquifer storage offers a seasonal TES system that can store heating or cooling energy for two to three months.

CASE STUDY: North Oak Development, Canada

The North Oak Development in Oakville, Ontario, includes multiple buildings connected to a groundsource ambient loop system. The system allows for energy recovery from each building to the loop and between buildings.

Domestic hot-water (DHW) heating is responsible for 32% of the total energy consumption in multifamily buildings (Houssainy et al. 2022) and can be a significant source of energy consumption in commercial buildings as well. Electrification of DHW systems is another key step in building decarbonization retrofits. Similar to HVAC electrification, retrofitting DHW systems with electric heat sources includes several challenges, including water supply temperatures, electrical capacity, cold air exhaust, and space and ventilation requirements. DHW retrofits should first take advantage of opportunities to reduce heating loads through decreased DHW use and energy recovery before pursuing electrification options. DHW retrofits also may include decisions regarding system configurations, such as centralized or decentralized systems. The process for decarbonizing existing DHW systems parallels the decarbonization process previously identified in Section 3.4 in Chapter 3, particularly with respect to evaluating the existing system, reducing loads as much as feasible, and rightsizing replacement systems. The content presented in this chapter provides additional contexts specific to DHW systems.

## 8.1 Evaluating Existing Conditions

It is important to understand the existing DHW configuration and conditions to identify constraints and opportunities for electrifying DHW systems. Unlike new systems, DHW systems in existing buildings often have unique configurations that limit retrofit options. Conversely, the retrofit of DHW heating often provides an opportunity to correct existing operational challenges. A water audit, modified to focus on DHW systems, is a great first step to better understand the existing DHW systems. This section includes considerations that should be addressed as part of the initial system assessment.

### 8.1.1 System Configuration and Condition

Completing a survey of the existing DHW system is a first step to better understanding the system and potential constraints and opportunities that will drive the design process. The configuration of the existing DHW system will drive design considerations for the retrofit. The first step is determining which fuel source the existing system uses. Possible DHW fuel sources include:

- Natural gas
- Electricity
- Steam
- District energy

The next key step is determining whether the existing configuration has centralized DHW generation or distributed DHW generation. Centralized versus distributed systems will influence the piping configuration, space to accommodate new DHW heating sources, and possibly location of electrical infrastructure. As discussed in Section 4.1 in Chapter 4, these can represent constraints for retrofit design and equipment capacity. During the evaluation, confirm space availability and access routes for moving equipment. Often, nearby storage space can be utilized, with approval of the owner and operations staff. In multifamily and multi-story commercial buildings, recirculating systems are common, making it important to understand the configuration of temperature maintenance and operating pressures for the existing system. Most commonly available equipment is only rated for 150 psig (1034 kPa), which may limit equipment placement options for high-rise applications. Common considerations for these systems:

- How are recirculation systems controlled for temperature maintenance?
- Do current temperature set points comply with code and hygiene requirements?
- Does the existing recirculation system properly consider different pressure zones within the building?

Some more basic information to gather relates to the condition of the existing DHW-generating equipment. Confirm the age of the equipment and determine whether capital plans include replacing DHW equipment within the project window. If equipment is planned for replacement, assess whether the equipment and systems are in sufficient condition to remain in operation through project phasing when planned for replacement. Existing systems also may serve as backup or peaking systems, so determining whether they are in suitable condition to remain in operation is important for retrofit design. Similarly, confirm the materials and the condition of existing distribution systems. This includes presence of known or suspected leaks, insulation of piping to minimize heat loss, and any planned upgrades or replacements. Understanding the age and condition of equipment can identify opportunities to leverage existing budgets as part of decarbonization projects. For example, for low-water-use buildings such as office towers, it may be more advantageous to convert a central system to distributed systems rather than spend capital on replacing existing risers. A final step in surveying the existing system is documenting the fixture types, usage types, and fixture flow rates. In multifamily and office buildings, these are often typical domestic fixtures such as faucets and showers, and laundry facilities for multifamily. In other commercial buildings, process loads may represent significant hot-water end uses and data should be collected to determine the operating load profiles. Understanding usage types and existing flow rates is useful for determining potential low-flow retrofit potential to reduce DHW system loads.

### 8.1.2 DHW Load Profile

Metering is the best source of data for developing DHW load profiles. It is critical that data collection be performed after DHW load-reduction measures, such as low-flow fixture retrofits, are implemented to accurately reflect the new peak DHW load. Sub-metering of DHW with a temporary or permanent flow meter is recommended to gather this information. Ideally, three months of metered data should be obtained (but no less than one month). Care should be taken in determining the most suitable location for water meter placement. Often, the best location is at the domestic cold-water makeup to DHW systems, upstream of recirculation systems to avoid false readings from the DHW recirculation system. Metering on distributed DHW systems can be difficult where many smaller systems are installed. If metering is not feasible for these systems, it may be useful to meter a few representative systems and use corresponding domestic cold-water metering along with modeling fixture use to estimate DHW use profiles.

Metering results can be compared against DHW energy use obtained from the DHW component of energy bills, typically the weather-independent component of normalized gas consumption when HVAC reheat systems are not operational (typically July or August).

## 8.2 Load Reduction and Rightsizing

A shortcoming of traditional DHW sizing methodologies is that they are based on outdated assumptions on fixture flow rates and usage patterns, which commonly results in oversizing in new construction projects. Conversely, existing building retrofits provide an opportunity to rightsize replacement systems based on actual peak demands and daily load profiles. Efforts are being made by ASHRAE and other agencies, including the International Association of Plumbing and Mechanical Officials (IAPMO) and the American Society of Plumbing Engineers (ASPE), to develop sizing methodology and typical usage data that better reflect actual use patterns in different building types. This methodology is reflected in the Uniform Plumbing Code (UPC) Appendix M—Peak Water Demand Calculator. Existing buildings have the benefit of actual usage history; this can be leveraged to rightsize replacement systems to better meet the system usage patterns without unnecessary oversizing. Oversizing electrified DHW systems, particularly HPWHs, results not only in performance issues, such as short cycling and reduced equipment life, but also needlessly increases project costs. Because of these factors, trend data collection of DHW use profiles per Section 8.1.2 is critical to inform sizing decisions. The DHW peak and recovery periods are key factors in determining the design of a HPWH system. Data collection for DHW sizing and design should take place after implementing DHW high-efficiency fixtures and heat recovery measures. As part of rightsizing, loadreduction strategies should always be considered as part of a DHW electrification project. Load-reduction strategies are typically lowcost and high-impact interventions that can reduce DHW electrification costs, often avoiding unnecessary electrical service upgrades. DHW thermal loads comprise three main areas of thermal energy use (or loss):

IAPMO Water Demand Calculator and Peak Water Demand Study

The IAPMO and ASPE performed a study in response to the increased use of lowflow plumbing fixtures and reduced water demand in buildings. The study reviewed data for single and multifamily buildings and developed a methodology for determining peak water demand in these buildings. This methodology serves as the basis for the Water Demand Calculator. Find the calculator at IAMPO (2023). Find the study at Buchberger et al. (2017).

**[Figure: Water Demand Calculator (WDC v2.0)]**

Type: table

Data:

| Fixture Groups | Fixture | Enter Total Number of Fixtures | Probability of Use (%) | Enter Fixture Flow Rate (GPM) | Maximum Recommended Fixture Flow Rate (GPM) |
| --- | --- | --- | --- | --- | --- |
| Bathroom Fixtures | Bathtub (no Shower) | 0 | 0.71 | 5.5 | 5.5 |
|  | Bidet | 0 | 0.65 | 2.0 | 2.0 |
|  | Combination Bath/Shower | 16 | 2.8 | 5.5 | 5.5 |
|  | Faucet, Lavatory | 32 | 1.61 | 1.5 | 1.5 |
|  | Shower, per head (no Bathtub) | 16 | 1.98 | 2.0 | 2.0 |
| Kitchen Fixtures | Water Closet, 1.28 GPF Gravity Tank | 32 | 0.85 | 3.0 | 3.0 |
|  | Dishwasher | 8 | 0.41 | 1.3 | 1.3 |
|  | Faucet, Kitchen Sink | 8 | 1.61 | 2.2 | 2.2 |
| Laundry Room Fixtures | Clothes Washer | 8 | 2.80 | 3.5 | 3.5 |
|  | Faucet, Laundry | 4 | 1.61 | 2.0 | 2.0 |
| Bar/Prep Fixtures | Faucet, Bar Sink | 0 | 1.61 | 1.5 | 1.5 |
| Other Fixtures | Fixture 1 | 4 | 1.50 | 5.5 | 6.0 |
|  | Fixture 2 | 0 | 0.00 | 0.0 | 6.0 |
|  | Fixture 3 | 0 | 0.00 | 0.0 | 6.0 |

Notes: This table represents the water demand calculator for a multi-family building, providing the total number of apartments in the building and the total apartments in this calculation. The table includes various fixture groups, such as bathroom fixtures, kitchen fixtures, laundry room fixtures, bar/prep fixtures, and other fixtures, along with their respective enter total number of fixtures, probability of use, enter fixture flow rate, and maximum recommended fixture flow rate.

- Hot-water use at fixtures (useful energy)
- Recirculation heat losses due to distribution systems and piping heat loss (parasitic loss)
- Standby losses due to heat loss associated with storing hot water (parasitic loss)

Understanding the relative proportions of total DHW energy consumption among these three categories is useful for deciding where to focus load-reduction strategies, determining if a system distribution configuration should be modified, and sizing replacement system components such as swing tanks.

**[Figure: Achieving Zero Energy: Advanced Energy Design Guide for Multifamily Buildings]**

Type: diagram

Description: The figure presents a cover page for a guide on achieving zero energy in multifamily buildings, featuring a photograph of a modern building with a courtyard and a pond. The title is prominently displayed at the top, with a green sunburst logo to the right.

Key Elements:

* Title: "Achieving Zero Energy: Advanced Energy Design Guide for Multifamily Buildings"
* Logo: A green sunburst logo with the words "Zero Energy" in white text
* Photograph: A modern building with a courtyard and a pond, showcasing a sustainable design
* Text: The title and logo are accompanied by a brief description of the guide's purpose and content.

- Estimating Hot-Water Use for Thermal Energy. Thermal energy requirements associated with hotwater use can be estimated readily with DHW usage profiles.
- Estimating Recirculation Losses. BAS data can be useful in estimating thermal energy losses associated with recirculation systems. With trended temperature data, losses can be estimated from known recirculation flow rates and pump control strategy/ schedule. For systems with BAS information, losses can be estimated based on pipe length and insulation characteristics.
- Estimating Standby Losses. Standby losses for well-insulated DHW storage tend to be low but can be estimated either through on-site testing using tank temperature trending or through calculations based on the tank dimensions and insulation values.

### 8.2.1 Low-Flow Fixture Retrofit

DHW retrofits in existing buildings should start with reducing the load through efficiency and technological improvements before considering heat pump water heaters (HPWH) or electric resistance DHW systems. Retrofit domestic fixtures with high-efficiency (low-flow) nozzles, aerators, and showerheads. User education and buy-in is very important to the success of a low-flow fixture conversion, particularly in facilities with large shower loads, such as recreation centers. It may be necessary to implement a pilot project first to determine the scale of flow rate reduction that occupants are willing to tolerate. Educating users about the reasons behind flow rate reductions often assists with buy-in for the project. Low-flow fixture retrofits should be completed prior to electrification of the DHW system. This ensures that occupants are used to the flow reductions and any unacceptable operations are remedied before proceeding with DHW electrification. This also allows time to meter actual DHW use to generate load profiles to inform sizing of new DHW generation systems.

CASE STUDY: Kitsilano Pool, Canada

The Kitsilano Pool reduced its DHW load by 40% by implementing low-flow showerheads prior to completing a central DHW retrofit. The central DHW system was retrofitted with a CO2 ASHP and 250-gallon tanks to meet the full DHW load.

How water wait times must be considered as part of low-flow fixture retrofits. In some cases, piping reconfigurations may be required to avoid excessive wait times at fixtures. Again, completing the low-flow conversion first is useful in identifying areas of concern that can be modified as part of the electrification project. For high-rise systems with multiple pressure zones, reliable pressure control also must be considered with flow-rate reductions. Significant flow reductions can cause issues with (now) oversized pressure-regulating valves (PRVs), causing noticeable changes in pressure and wire drawing in the valves.

### 8.2.2 Distribution and Storage Losses

Distribution losses, including losses from DHW heating equipment and recirculation system losses, can account for up to two-thirds of heating needs for multiuse residential buildings. Uninsulated domestic hot-water piping, particularly with recirculation systems, can be a major source of load. Based on a visual inspection of insulation deficiencies, provide piping and storage tank insulation in accordance with ASHRAE/IES Standard 90.1 or local energy codes. Additionally, recirculation systems often run continuously, increasing distribution losses. Consider implementing control strategies to reduce distribution losses (see Section 8.4.1). Strategies for minimizing distribution heat loss in DHW systems are presented in Domestic Hot Water Distribution Heat Loss (Green and Heller 2022).

### 8.2.3 Passive Heat Recovery (Drain-Line Heat Recovery)

Passive forms of DHW heat recovery can contribute to reducing DHW loads. Drain-water heat recovery (DWHR) passively recovers heat from wastewater sources such as shower drains or laundry water. DWHR systems capture heat from the outgoing hot drain water and transfer it to the incoming cold water, preheating it before it enters the DHW water heaters and/or the entering cold water line to the shower/fixture. Both horizontal and vertical DWHR options are available. Implementation of this type of heat recovery is highly dependent on the system configuration and is typically more cost-effective when implemented in areas of high DHW use.It is important to consider the DHW heating source when pairing it with DWHR. For example, singlepass HPWH systems require a cold inlet water temperature to operate efficiently. Preheating incoming cold water in this scenario is not desirable. In contrast, multi-pass HPWHs may be able to take advantage of this type of heat recovery to reduce the number of cycles required to achieve the DHW set point.

**[Figure: Drain-water heat recovery diagram]**

Type: diagram

Description: The diagram illustrates a drain-water heat recovery system, which utilizes the heat from wastewater to preheat cold water before it enters a water heater. This process aims to reduce energy consumption by leveraging the thermal energy present in the wastewater.

Key Elements:

- Faucet -> Source of wastewater
- Heat Exchanger -> Transfers heat from wastewater to cold water
- Cold water in -> Cold water entering the system
- Drain water -> Wastewater leaving the system
- Hot water tank -> Stores preheated water for use

This diagram effectively conveys how a drain-water heat recovery system operates, highlighting its components and their roles in conserving energy.

### 8.2.4 Rightsizing

Rightsizing for DHW systems for existing buildings includes understanding the existing DHW usage profiles, accounting for load-reduction implementation, and understanding anticipated future use changes of areas within the building. The sizing methodology use for electrified DHW systems is dependent on the system type and generally can be classified into one of three categories:

- Storage-Based Systems. Central HPWHs or electric resistance DHW tanks
- Distributed Systems. Distributed (and often packaged) HPWHs and electric DHW tanks
- Point-of-Use and Instantaneous Systems. Under-counter and at-fixture point-of-use electric heaters

**[Figure: DHW system storage/capacity curve for sample building]**

Type: chart

Description: The chart compares the primary heating capacity (kBTU/hr) with the primary tank volume (gallons) at storage temperature. The key insight is that as the primary tank volume increases, the primary heating capacity decreases.

Data Representation:

* Primary Heating Capacity (kBTU/hr): 400-200
* Primary Tank Volume (Gallons): 600-2200
* Metric: Primary Heating Capacity
* Chart Type: Line
* Units: kBTU/hr and gallons

Chart Generation Hint:

* X-axis: Primary Tank Volume (Gallons)
* Y-axis: Primary Heating Capacity (kBTU/hr)

Structured Data (Machine Readable):

{
  "chart_type": "line",
  "metric": "Primary Heating Capacity",
  "units": "kBTU/hr and gallons",
  "data": {
    "600": 400,
    "1000": 350,
    "1200": 300,
    "1400": 250,
    "1600": 200,
    "1800": 150,
    "2000": 100,
    "2200": 50
  }}
}

These three system categories can be represented visually on a system storage/capacity curve—a plot of useful DHW storage vs. DHW-generating capacity—as shown in Figure 8.2. Any combination of useful storage and capacity that falls above the system curve is adequately sized to meet the system demand. The left side of the curve represents instantaneous and point-of-use systems that are sized to meet the system’s instantaneous DHW flow requirements. The left side of the curve represents lowheating, capacity-high storage systems that leverage high volumes of storage and periods of low DHW use to recover and store DHW for periods of peak use. Understanding the trade-off between heating capacity and storage volume is important when accommodating electrified DHW systems in existing buildings. Often, providing high storage can alleviate the need for electrical service upgrades. High system volume also accommodates load shedding and demand reduction strategies with minimal impact on DHW delivery to fixtures. These concepts are explored further in Section 8.6.

### 8.2.5 Sizing Methodology for Storage-Based Systems

Storage-based systems utilize a combination of stored DHW and heating capacity to meet DHW demands. Consequently, there is a system trade-off between storage volume and heating capacity that should be considered. Larger storage volumes require space and add weight but allow for small heatgenerating equipment, reducing electrical peak load and equipment footprint and costs. When grid interactivity is considered, even larger volumes are often viable to allow further flexibility in heating operation to align with periods of reduced grid emissions or demand charges. These sizing considerations are true regardless of the heating source but become particularly important for central HPWHs due to their increased cost per unit capacity compared to alternative forms of heating. Storage is typically less expensive than heat pumps. Sizing systems using larger storage can save first costs on implementation and improve heat pump longevity by reducing short cycling. The appropriate balance between storage volume and heating capacity is specific to each project and is a function of:

- DHW use profile (peaks, variability, specific end uses)
- Electrical capacity limitations
- Grid emission profile
- Available space for DHW equipment

Sizing storage-based systems is best accomplished utilizing design daily load profiles and the cumulative volume vs. time interval method outlined in the 2023 ASHRAE Handbook—HVAC Applications (Chapter 51) or software such as Ecosizer. Ecosizer is an online tool available to the public, created specifically for sizing central HPWH systems. The tool has default load profiles tailored for multi-unit residential buildings, with the flexibility to adjust the DHW load profiles to match project-specific conditions. Additionally, several HPWH manufacturers provide their own tools for sizing, tailored to their specific products. It is important that consultants be familiar with the sizing processes used by these tools before using them. The 2023 edition of the ASHRAE Handbook—HVAC Applications provides load shapes for a variety of occupancy types, which can be adjusted (normalized) in relation to the actual peak demand (see Chapter 51). Nonetheless, the most reliable data for sizing comes from specific demand profiles for the site, which are obtained through metering of actual domestic hot-water use profiles.

Ecosizer Tool

Ecosizer is a useful free tool that is available to size central water heating systems for commercial and multifamily buildings that rely on HPWHs. It allows the user to input climate data, DHW demand data, and HPWH operating temperatures to help determine an appropriate size for the HPWH (Ecosizer n.d.).

### 8.2.6 Sizing Methodology for Point-of-Use Systems

Point-of-use systems have little to no volume to assist with meeting DHW loads. The heating capacity must be sized to meet the anticipated peak DHW load at the associated fixtures. Heating capacity should be based on the expected peak flow rate and the temperature differential between the desired usage temperature at the fixture and the incoming cold water temperature.

### 8.2.7 Sizing Considerations for Grid-Demand Response

For emissions reduction and/or demand cost reduction, grid-demand response should be considered when deciding on and sizing DHW systems. Storage-based systems provide flexibility to accommodate demand response with minimal impact on the end user. Conversely, instantaneous and point-of-use systems have limited flexibility when users need hot water. In the context of overall building grid-demand response, DHW loads are often low-hanging fruit and the simplest load to shed due to the fairly predictable and non-weather-dependent load they represent within a building. See Grid-Interactive Buildings For Decarbonization: Design and Operation Resource Guide for details on grid-interactive design for DHW systems.

## 8.3 Distributed vs. Central Systems

DHW systems may be centralized, with a single DHW system serving the entire building, or may be distributed, with individual hot-water heaters serving each tenant or floor. The configuration of the existing system can be a driving factor in the design of retrofit systems. There are a number of factors to consider when deciding to modify the existing distribution system configuration. Table 8.1 compares distributed and central systems and analyzes which system type better accommodates considerations for different system factors.

### Table 8.1    Accommodating Design Considerations: Distributed vs. Central Systems

| Factor | Distributed System | Central System |
|---|---|---|
| High DHW consumption | Low | High |
| Low DHW consumption | High | Low |
| Variable DHW consumption | High | Low |
| Configuration of existing DHW system | Neutral | Neutral |
| Age and condition of existing DHW distribution infrastructure | High | Low |
| Space availability for DHW equipment | Low | High |
| Retrofit phasing | High | Low |
| System losses | High | Low |
| Occupant sensitivity to noise levels | Low | High |
| Access to ventilation for HPWHs | Low | High |
| Desired metering configuration (owner vs. tenant) | High | Low |
| Ability to leverage DHW storage for demand/emissions management | Low | High |

### 8.3.1 Distributed DHW Systems

Distributed DHW systems involve multiple smaller water heaters, each serving individual dwelling units or commercial spaces. These heaters are typically located closer to the points of use, such as within or near each dwelling unit or space. These are often found in garden-style multifamily buildings and some commercial spaces with fluctuating hot water needs among tenants. Some distributed systems also include point-of-use water heaters, which can serve specific loads within a building that otherwise has relatively low DHW demand, such us commercial office restroom sinks and breakrooms. In an electrified building, these are usually electric resistance point-of-use water heaters with high peak electrical loads. Point-of-use water heaters can also be set up as instantaneous heat exchangers using the building heating hot-water system (or steam) as the heat source. Further discussion of this approach is provided in Section 8.8. Distributed DHW systems reduce the amount of circulation piping with water heaters located at each unit, which in turn reduces the circulation heat losses from the DHW system. This can represent a significant amount of heat loss, so distributed systems effectively reduce the DHW heat load by eliminating losses. Distributed systems also allow for individual metering of tenants’ DHW use. These systems can also be implemented in a phased approach, retrofitting a set number of units at a time or based on triggers in the decarbonization plan, such as tenant turnover. Distributed HPWH systems also bring the issues of noise levels and cold exhaust air closer to tenant spaces. The space and ventilation requirements for HPWHs may also be more challenging to accommodate in the in-unit spaces available for the HPWH unit. Adding noise insulation to an already constrained space is challenging and will compete with needs for adequate space and ventilation of the HPWH. If a distributed DHW system includes a phased retrofit, where different units have different DHW heating systems, it also presents more complex maintenance for the overall system.

### 8.3.2 Central DHW Systems

Central DHW systems involve a single, larger water heating system that serves multiple dwelling units or commercial spaces within a building. Central DHW systems are suitable for larger facilities with a high demand for hot water, such as hotels, hospitals, and laboratories. For build ings that have a central source for domestic hot water with a circulation loop, pumping energy is often perpetually consumed (i.e., independent of occupancy patterns), and the associated heat losses through the circulation loop are a constant within the system. Insulating DHW circulation piping will help reduce heat losses, but these losses must still be accounted for in the design of the centralized DHW system. In addition to insulation, the control strategies covered in Section 8.4.1 should be considered for all central DHW systems. Central systems consolidate equipment and can make maintenance easier by reducing the quantity of equipment to maintain. At the same time, some HPWH central systems incorporate multiple tanks, etc., introducing new equipment and configurations that may be unfamiliar to maintenance staff. Central systems require a larger footprint for the heat pump and storage tanks. These systems also may incorporate additional tanks to buffer water temperatures, as discussed in Section 8.4.3, which can add complexity and increase the footprint. Central systems are not practical to implement as phased retrofits because adding units requires connecting them into the larger loop.

CASE STUDY: Vera Cruz Village, California

The case study for Vera Cruz Village in California presents a retrofit of a distributed DHW system with individual HPWHs at each apartment unit.

CASE STUDY: The Heritage, New York

The case study for the Heritage in New York presents a retrofit of a centralized DHW system from gas boilers to AWHPs, reducing the DHW energy consumption for the 1660 Madison Building.

### 8.3.3 Application Considerations

DHW electrification retrofits often provide an opportunity to enhance the current distribution configuration or pivot and completely change the DHW distribution system to better serve the needs of the building. The decision to modify the existing distribution system includes a large number of factors, identified at the beginning of this section. The following are some specific considerations that may drive the decision-making process. Analyzing the actual DHW load profile can be useful in determining whether making a change to the distribution systems is warranted. Systems with low peak or frequency of use tend to favor distributed systems to reduce standby and distribution losses. On the other hand, systems that experience high peaks tend to benefit from storage-based systems because DHW storage can lower HPWH capacity. Understanding the condition of the existing DHW piping systems can identify opportunities to make cost-effective changes to the current configuration. For example, capital maintenance budgets set aside for DHW and recirculation riser replacement in an office tower may be better spent by converting a central system to a distributed system, eliminating the need for expensive riser replacement and effectively eliminating distribution losses. When considering a change to the distribution scheme, the existing electrical capacity must be understood very early in the process to avoid later issues in design. For example, the decision to convert from a central system to point-of-use water heaters may trigger widespread panel or feeder upgrades that can make an otherwise cost-effective retrofit option impractical. Unique end uses, such as process loads that require high-use and/or high-temperature DHW, are often best served by a dedicated storage-based DHW system.

## 8.4 Recirculation Systems

Recirculation systems are commonly used in commercial and multifamily buildings to reduce wait times for domestic hot water, and the 2021 International Plumbing Code requires some form of hot-water temperature maintenance for distribution systems with developed piping lengths of more than 50 ft (15.2 m) (ICC 2021). Recirculation systems are designed to maintain hot water at the tap, ensuring quick and convenient access to hot water without waiting for it to reach the desired temperature, reducing water usage. However, these systems often account for a large proportion of DHW energy use due to thermal losses.

### 8.4.1 Reducing Recirculation Energy Losses

Uncontrolled DHW recirculation system energy losses can account for up to half of DHW energy requirements in commercial and multifamily buildings (Dentz et al. 2016), particularly for low-demand, low-use central systems. As such, it is important to implement measures to reduce losses associated with recirculation wherever possible. Interventions to minimize losses typically involve adding piping insulation and making control modifications to the recirculation pump operation. Often, existing buildings run recirculation systems constantly, which substantially increases energy losses. Prior studies from NREL (Dentz et al. 2016) and the California Statewide Codes and Standards Enhancement (CASE) program (Goyal et al. 2022) offer multiple DHW recirculation control strategies to reduce recirculation energy. When deciding to implement control changes to recirculation, it is important to consider the application and ensure that modifications do not result in increased risk of exposure to legionella. This is of particular concern for health-care and extended-care applications that serve occupants with weakened or compromised immune systems. A summary of recirculation control strategies is provided below:

- Scheduled Control. This form of control utilizes the BAS or stand-alone time clocks to disable recirculation pump operation during periods when the building is unoccupied. This form of control is a mandatory requirement in ASHRAE/IES Standard 90.1.
- Temperature Control. This method of pump control utilizes a temperature sensor in the recirculation line. The pump is staged on and off to maintain the recirculation temperature at a set point.
- Demand Control Operation. A flow meter or switch in the domestic cold water makeup piping is used to determine when there is a demand for hot water. Upon detection of flow, the recirculation pump is enabled. This method of flow control is commonly implemented in combination with temperature control.
- Temperature Modulation Control. This form of control can be used with or without other pump-control strategies. Rather than directly controlling the recirculation pump, this control strategy resets the temperature set point based on occupancy patterns. The temperature set point is reset down during expected periods of low use. Prior to anticipated periods of high use, the temperature set point is reset up. This saves energy by reducing the mean temperature difference between the piping and the ambient air. Concerns for legionella growth must be considered as part of implementing any temperature reset strategy.
- Machine-Learning-Based System. Although they are not yet ubiquitous, it is expected that learning-based algorithms will become common in the future, incorporating and improving on the control strategies mentioned above.

### 8.4.2 Direct-Return Systems

Gas-fired and electric resistance DHW systems are almost always designed with the recirculation DHW piped to the primary DHW storage where it is reheated. This piping configuration is simple and uses the DHW stored in the tank, and associated heating source, to offset heating losses in the distribution system. While this configuration works well for gas-fired and electric resistance DHW systems, it creates issues for single-pass heat pumps (see Section 8.5), which require a low inlet water temperature to maintain capacity and efficiency. Multi-pass HPWHs do not have the same requirement for low inlet water temperature and generally can be plumbed like conventional DHW systems with direct return of the recirculation system. However, care must be taken to avoid short cycling of heat pumps during low load conditions.

### 8.4.3 Recirculation System Considerations for Central Single-Pass HPWHs

Two piping and storage tank combinations are commonly employed with single-pass HPWHs to ensure the heat pump uses the lowest entering water temperature, required to maximize capacity and efficiency. Both methods involve utilizing a secondary storage tank, downstream or in parallel with the primary storage volume, to separate DHW recirculation from the primary storage volume.

#### 8.4.3.1 Recirculation with Swing Tanks

A swing tank is plumbed in series with the primary storage volume and is equipped with a dedicated heating source, typically a small multi-pass heat pump or electric resistance heater. The DHW return is piped to this tank rather than the primary storage volume. The temperature set point on the swing tank is typically set lower than that of the primary storage and slightly higher than the distribution temperature set point downstream of the master mixing valve. Refer to Figure 8.3 for an illustration of this system configuration. During periods of DHW demand, hot water from the primary storage volume enters the swing tank and mixes with the lower-temperature hot water there before delivery to end uses. A benefit of this arrangement is that the heat generated by the primary heating source (HPWH) is used to satisfy both the DHW needs and offset recirculation losses by mixing hot water from the primary tank.

**[Figure: Schematic of HPWH recirculation loop with swing tank]**

Type: diagram

Description: The diagram illustrates the components and flow of a heat pump water heater (HPWH) recirculation loop with a swing tank. It shows how hot water is circulated from the building to the HPWH, where it is heated, and then returned to the building.

Key Elements:

- Stratified Storage Tank(s) -> Stores hot water for recirculation.
- Recirculating Tank -> Holds water for recirculation and mixing with cold water.
- Mixing Valve -> Blends hot and cold water to achieve the desired temperature.
- Recirculating Pump -> Circulates water through the system.
- Cold Water Makeup -> Adds cold water to the system as needed.
- Hot Water to Building -> Delivers heated water to the building.

This diagram provides a clear visual representation of the HPWH recirculation loop's operation, highlighting the key components involved in heating and distributing hot water efficiently.

**[Figure: Schematic of HPWH recirculation loop with parallel recirculation tank]**

Type: diagram

Description: The figure illustrates a schematic of a heat pump water heater (HPWH) recirculation loop with a parallel recirculation tank. It shows the flow of hot water from the HPWH to the recirculating tank and then to the mixing valve, which combines it with cold water makeup. The mixed water is then pumped back to the building.

Key Elements:

*   HPWH -> Heat pump water heater
*   Recirculating Tank -> Stores hot water for recirculation
*   Mixing Valve -> Combines hot water with cold water makeup
*   Recirculating Pump -> Pumps mixed water back to the building
*   Cold Water Makeup -> Adds cold water to the recirculation loop

This diagram provides a clear visual representation of the HPWH recirculation loop and its components, helping to understand how the system works and how it can be optimized for energy efficiency.

During periods of low DHW demand, the temperature in the swing tank drops due to distribution losses. The dedicated heater operates to maintain the swing tank at temperature while preserving the stratification in the primary storage volume to ensure efficient operation of the HPWH.

CASE STUDY: Kitsilano Pool, Canada

The Kitsilano Pool’s central DHW system was retrofitted with a CO2 ASHP and two 250-gallon tanks to meet the full DHW load. A third 250-gallon tank operates as a swing tank to maintain storage tank temperature stratification.

#### 8.4.3.2 Recirculation with Parallel Recirculation Tanks

Another configuration for addressing HPWH inlet temperature is a parallel recirculation tank design (see Figure 8.4). In this configuration, the recirculation tank is plumbed in parallel with the primary storage volume. Recirculation heat losses are offset within the parallel tank using a dedicated multi-pass HPWH for temperature maintenance. This design requires a higher total heat pump capacity than the swing tank configuration but can be effective for buildings with high distribution losses and when there are low and relatively intermittent hot-water loads. The multi-pass HPWH handles the temperature maintenance for the recirculation loop, while the primary HPWH operates to charge the primary tank.

#### 8.4.3.3 Choosing Swing Tank vs. Parallel Tank Configuration

In general, the choice of which system configuration is best suited for a specific application is based on the chosen heating source for the recirculation loads and the magnitude of the recirculation load. Because parallel tanks more commonly utilize multi-pass heat pumps to offset recirculation losses, parallel tank configurations are recommended for applications with high recirculation losses and relatively low DHW demand. Conversely, swing tank configurations are typically less expensive due to reduced heat pump capacity. In addition, existing gas-fired hot-water tanks or electric resistance tanks can be reused as swing tanks. In this configuration, an existing gas-fired system can serve as backup should the heat pump fail, because all DHW flows through the swing tank upstream of the distribution system.

## 8.5 Heat Pump Water Heaters

Heat pump water heaters (HPWH) include any heat pump that is used to produce DHW. These are the basis for most DHW electrification projects. They can be specially designed HPWHs dedicated to DHW, or they can be general-purpose air-towater or water-to-water heat pumps with an added double-walled heat exchanger to ensure code-required double-wall separation with potable water. DHW and heating hot water (HHW) can be served from the same heat pump, though there are many factors to consider when using this approach, which is further detailed in Section 8.8. As discussed in that section, the need for higher-temperature hot water in DHW applications (often 140°F [60°C] for Legionella control) compared to HHW applications often drives a separation of these systems and the existence of a separate DHW HPWH product market. This section will introduce the different types of HPWHs and associated typical applications, but other available guides should be consulted for a detailed view of heat pump types and their associated refrigerant options.

**[Figure: Central Heat Pump Water Heater Design Guide: Solutions and Tools for Designing Central Heat Pump Water Heater Systems in Multifamily and Other Commercial Buildings]**

Type: diagram

Description: The figure presents a comprehensive guide for designing central heat pump water heater systems in multifamily and commercial buildings. It provides solutions and tools for engineers to design efficient and effective systems.

Key Elements:

*   **Cover Page**: The cover page features a photo of a central heat pump water heater system installed on a rooftop, with a sunset background.
*   **Title**: The title of the guide is prominently displayed at the top of the page, indicating that it is a design guide for central heat pump water heater systems.
*   **Subtitle**: The subtitle provides additional information about the guide, stating that it offers solutions and tools for designing central heat pump water heater systems in multifamily and other commercial buildings.

This figure serves as an introduction to the guide, providing a visual representation of the topic and setting the stage for the detailed information that follows.

### 8.5.1 Heat Pump Types

There are two primary types of HPWHs:

- Single-Pass. As the name implies, single-pass HPWHs heat the DHW from the inlet temperature to the supply temperature in a single pass through the heat pump. The heat pump receives cold incoming water and heats it to the set-point temperature, typically raising the water temperature between 70°F and 100°F (38.9°C and 55.6°C). The hot-water supply to the tank can directly supply the end use fixtures. Because they are designed for a large lift, single-pass HPWH systems rely on colder inlet temperatures for the heat pump and temperature stratification within the storage system.
- Multi-Pass. A multi-pass primary system heats incoming water incrementally, raising the temperature of the water with each pass. Multi-pass water heaters typically raise the water temperature approximately 10°F (5.6°C) with each cycle, operating as many cycles as needed to achieve the set-point temperature. Multi-pass systems also rely on temperature stratification but do not require the large differential that single-pass systems do. Multi-pass systems can also operate more efficiently than single-pass HPWH with higher incoming water temperatures.

Both types can be used with central water heating systems, with or without recirculation loops, which are discussed in Section 8.4. Single-pass systems generally have a higher operating efficiency than multi-pass systems, but care must be taken during times of low load so that very warm return water does not disturb stratification in the storage tank. Integrated storage HPWHs are typically multi-pass types and can be used in either a distributed system or a small central system. These have the heat pump heating and storage tank in a selfcontained unit. Many 120V designs of integrated HPWH are now available, making installation easier. While the installation of a 120V integrated HPWH may appear a simple replacement to a conventional tankless residential water heater, the electrical capacity (especially if the existing water heater was gas fired) must still be evaluated to confirm it is sufficient.

### 8.5.2 Refrigerants

Refrigerants and their ability to reach a given maximum hot-water supply temperature under specific ambient air or source water conditions play a key role in heat pump technology. Refrigerants can be broadly categorized by operating pressure:

- Medium Pressure. R-134a and its corresponding low-GWP replacements R-513A, R515B, R-516A, R-1234yf, and R-1234ze can typically generate up to 160°F (71.1°C) hot water, though for air-source applications they are generally limited to ambient temperatures around freezing. These refrigerants can be used in either single-pass or multi-pass HPWHs.
- High Pressure. R-410a and its corresponding low-GWP replacements R-32, R-454B, R452B, and R-466A can typically generate up to 140°F (60°C) hot water with vapor compression (130°F [54.4°C] without) and operate at ambient temperatures well below freezing. These refrigerants are typically used in multi-pass HPWHs.
- Very High Pressure. R-744 (CO2) can typically generate up to 190°F (87.8°C) hot water at very low ambient temperatures (–25°F [–31.7°C]). R-744 is typically used in single-pass HPWHs. Due to the high operating pressure, the equipment can come at a cost premium, depending on the size of the system. Small systems, or modular systems made up of multiple small units, tend to be the most cost-effective approach.

### 8.5.3 Heat Pump Heat Sources

Heat pump water heaters are either air-to-water heat pumps or water-to-water heat pumps. For WWHPs, the heat source can be the ground or other large physical body (e.g., ocean), sewer water or other type of heat recovery (e.g., the heat rejection of a chilled-water loop or condenser water loop), or an AWHP in series.

- Air. Air as a source of heat is relatively straightforward when it is outdoor air, which is effectively an infinite source. The considerations of outdoor air temperature and heat pump operation are no different than in any other air-source heat pump application, and those considerations are not repeated here. Air-based heat recovery can improve efficiency and is discussed in Section 8.7.
- Ground. A ground-source heat pump application for DHW is typically combined with a heat pump for space cooling/heating. As in any ground-coupled application, the heating and cooling loads need to be relatively balanced over the course of the year (depending on climate) so as not to overcool or overheat the ground and destroy the heat source. As a result, a heating-only application like DHW would not work in a purely ground-coupled application unless there were enough groundwater flow to effectively act as the heat source.
- Sewer-Water or Other Water-Based Heat Recovery. See Section 8.7.

- AWHP in Series with WWHP. In many water-source HPWH applications, there is not a consistent renewable source of heat serving the source side. In those applications, you would need to supplement with an air-to-water heat pump, effectively using the air as the heat source. In most climates, this type of series/cascaded refrigeration loop setup will be less efficient than a stand-alone AWHP unless there were another source of heat in the loop, such as recovered heat from a cooling process. An example application would be a condenser water loop system, where space heating and cooling are served by WSHPs and the DHW is served by a WWHP on the same loop. When the WSHPs are primarily in cooling mode, the DHW has a free source of heat. When the WSHPS are primarily in heating mode, a separate AWHP needs to inject heat into the condenser water loop to satisfy both the space heating and DHW needs.

The type of heat source most appropriate for the retrofit will depend on which sources are available per the existing conditions assessment described in Section 8.1 and the broader existing building considerations covered in Chapter 4.

## 8.6 DHW Storage Systems 8.6.1 Cost and GHG Emissions Benefits of Increased DHW Storage

While the conversion of gas water heaters to electricity-based HPWHs forms an integral part of the decarbonization strategy for DHW systems, a key component to improving the effectiveness of HPWHs is the hot-water storage tank. DHW storage systems can be viewed as a form of TES system (discussed in Chapter 7), which helps store hot water during periods of low demand for use during periods of high demand. Similar to TES systems, described in Section 7.5 in Chapter 7, DHW storage facilitates peak load reduction and shifting of DHW production to minimize GHG emissions. Increasing DHW storage volumes provides two simultaneous benefits:

- Reduces First Costs. HPWHs are very expensive compared with traditional DHW heating systems. Increasing storage volumes allows for reduced capacity of installed HPWHs (see Section 8.2), which reduces capital costs, potentially at the expense of increased space requirements.
- Enables Grid-Interactive Control. Increased storage volumes reduce emissions in a couple ways. First, the installed heat pump capacity can be reduced, reducing peak electrical demand and corresponding emissions when the heat pump operates during periods of high grid emissions. Second, increased storage can facilitate the ability to operate the HPWHs at lower grid emissions periods, generating DHW water during off-peak hours for later use.

### 8.6.2 DHW Storage Considerations for Retrofits

Total DHW storage must take into consideration both the useful storage volume (the result of sizing calculations) and the storage volume required to prevent HPWH short cycling. The total volume also must include an allowance for unusable volumes of water located below the coldwater inlet to the storage tank(s). Identifying adequate space and access routes for increased DHW storage volumes within existing buildings can be challenging and often necessitates the installation of tank arrays versus a smaller number of large tanks. Multiple tanks provide more flexibility with tank layout but at the expense of overall higher footprint requirements and increased standby losses. However, for smaller systems, tank arrays may provide a first cost advantage if tank sizes are maintained below 120 gallons (454 L) and ASME ratings are not required.

Piping configurations for tank arrays are dependent on the type of heating technology. For electric resistance and multi-pass heat pumps, piping tanks in parallel is a common approach. This arrangement facilitates the use of standard tanks with factory-standard pipe connection sizes, and such piping configurations are commonly understood among installers. In addition, isolating a failed tank is straightforward and does not affect the rest of the system. For single-pass HPWH applications requiring a high degree of tank stratification, consider piping tanks in series to promote stratification. In this application, care must be taken to ensure that pipe connection sizes are large enough to accommodate full system flow and run at a low enough velocity to avoid disrupting tank stratification. This often requires the use of semi-custom or custom tanks. The piping configuration should also consider tank failure, with additional isolation valves and tank bypass piping to facilitate removal of a failed tank without the need to shut down the entire system.

### 8.6.3 Controls and Automation

DHW controls can be designed to operate a central DHW system on demand based on historical load profiles, temperature- and occupancy-activated controls, and timers to circulate water only when needed to eliminate unnecessary pumping. This strategy reduces energy consumption during periods of low demand. DHW storage tanks also allow for the use of heat pumps during times of low GHG emissions to charge tanks for distribution during periods of high GHG emissions. These periods may depend on grid marginal emissions or on-site clean energy generation periods. Control strategies for load shaving and shifting using hot-water tanks can have three levels of complexity:

- Simple On/Off. Operation schedule controlled by a simple timer which will block heat pump operation during times of high grid emissions. However, the drawback with this is that if the water demand is high then the storage tank may not be able to satisfy the needs fully. A common way to mitigate this problem is to increase set point temperature but that can contribute to increased losses.
- Load-up/Shed. This strategy is slightly more sophisticated than simple on/off in that the low GHG emissions hours are used to preheat the water, reducing the energy required during on-peak hours.
- Grid Optimization. This grid-interactive control automatically adjusts HPWH operation based on grid marginal emission factors and the predicted DHW demand based on historical system load data.

## 8.7 Heat Recovery and Renewable Heat Sources

Exploring heat recovery and renewable heat sources for DHW can contribute to reducing DHW load on heat pumps and associated electrical demand/consumption requirements.

### 8.7.1 Heat Recovery

The applicability of heat recovery options depends on the HPWH system configuration. For example, single-pass HPWH systems rely on a cold inlet water temperature to operate efficiently. Incorporating heat recovery with single-pass heat pumps generally should be achieved in a parallel configuration rather than as a preheat arrangement. In contrast, multi-pass HPWHs can often take advantage of preheat-configured heat recovery to reduce the number of cycles required to achieve the DHW set point. Potential active heat recovery applications for DHW systems include:

- Heat Recovery from Cooling Systems. Heat produced as part of building cooling can be reclaimed to heat DHW systems rather than being rejected to the atmosphere. Heat can be cap tured from condenser systems to preheat DHW, or a dedicated WWHP can be utilized to heat DHW by directly cooling the chilled-water loop or condenser water loop.
- Heat Recovery from Sewer Water. Sewer water can be a great source of heat, particularly for buildings with large DHW loads or campus-level systems. Unlike other heat recovery strategies that store reclaimed heat as DHW, sewer heat recovery systems use a holding tank to capture water, which can be pumped through a heat exchanger for the HPWH. Some HPWH designs allow for sewer water from the holding tank to be pumped directly through the HPWH. Other systems include a macerator system and intermediate heat exchanger, piped for backflushing, to protect the HPWH.
- Heat Recovery from Air. To the extent that air-source HPWHs can be placed near heat-producing equipment, heat recovery from the indoor air is possible via transfer air. One simple example of this is to place an integrated HPWH in a janitor’s closet next to an IDF closet and duct the air to the IDF closet. On a larger scale, air-source HPWHs can be located in underground garages, which have code minimum exhaust ventilation requirements. This also takes advantage of the tempering effect of the garage being ground-coupled and includes some small heat loads (cars, chargers, lights, etc.).
- Heat Recovery from Other Processes. Some commercial and industrial buildings produce excess heat as a byproduct of their processes, often at temperatures suitable for direct DHW heating. Common examples of such processes are those that utilize co-generation equipment, such as jacket water and/or lube oil coolers. Other examples include process cooling applications, such as glycol systems utilized for breweries. In this application, the heat of fermentation can be recovered to heat DHW.

### 8.7.2 Renewable Heat Sources

Solar thermal collectors are a common renewable energy system used to heat DHW directly. Solar collectors do have the ability to heat DHW to usable temperatures without additional heating; however, due to the variability in solar availability, solar thermal systems are typically integrated as preheating components for DHW systems. Sizing considerations must include potential solar array temperature stagnation during periods of high solar gain. Often, a supplementary heat rejection source, such as a dry cooler, is required to protect the solar system from overheating during periods of high solar gain and low use. While solar thermal hot-water heating systems provide a large amount of thermal energy per square foot of collector area, they represent a trade-off with PV systems, which may be a better fit for reducing building GHG emissions overall, whether by powering the HPWH or other HVAC equipment for the building.

## 8.8 Combined Systems and Hybrid Fuel Systems 8.8.1 Combined Systems

A combined system, often called a combi system, refers to a configuration where both space heating and DHW heating are met by a single energy source. Combined systems can provide a number of benefits as part of the electrification process:

- First-Cost Efficiency. Combining space heating and DHW heat generation into a single system often has first cost benefits because heat pump equipment provides dual duty to meet both loads. This can reduce first costs associated with heat pumps and associated hotwater storage. For example, hot-water buffer tanks can serve both to prevent heat pump short cycling during low loads and to act as a source of thermal energy storage to meet DHW loads.

**[Figure: Diagram of Combined Space and DHW Heating System]**

Type: diagram

Description: The diagram illustrates a combined space and domestic hot water (DHW) heating system. It shows the flow of hot water from the boiler to the radiators and the DHW cylinder, as well as the return flow of cooled water back to the boiler.

Key Elements:

* Boiler -> heats water for space heating and DHW
* Radiators -> heat spaces
* DHW cylinder -> stores hot water for domestic use
* Pumps -> circulate water through the system
* Valves -> control the flow of water
* Sensors -> monitor temperature and pressure

This diagram provides a clear overview of the components and flow of a combined space and DHW heating system, allowing for easy understanding and analysis of the system's operation.

**[Figure: Combined Space and DHW Heating System Diagram]**

Type: diagram

Description: The diagram illustrates a combined space and domestic hot water (DHW) heating system. It shows the flow of heat from the storage water heater to the hydronic air handler, which then supplies hot air to the space and DHW loads.

Key Elements:

* Storage Water Heater -> Provides heat to the system
* Hydronic Air Handler -> Distributes heat to the space and DHW loads
* DHW Mixing Valve -> Mixes hot water from the storage water heater with cold water to produce DHW
* Hot Space Heating Air -> Supplies hot air to the space
* Return Air -> Returns cooled air to the hydronic air handler
* Cold In from Mains -> Supplies cold water to the DHW mixing valve
* DHW Loads -> Represents the demand for DHW
* Supply to AH -> Supplies hot water to the hydronic air handler
* Return from AH -> Returns cooled water to the storage water heater

(a) (b)

- Space Savings. Combined systems often require less space compared with two separate systems, which can make these systems an attractive choice in existing buildings with limited available space.
- Integrated Heat Recovery. Heat recovery can be readily integrated with combined systems, with summer cooling loads being used to heat DHW essentially free of cost.

Traditional fossil-fuel-based combined systems typically take a centralized approach to DHW heat generation and storage, with indirect DHW tanks being located near the boilers and DHW being distributed throughout the building with a dedicated distribution system. While this approach is common with modern heat-pump-based combined systems, a distributed approach to DHW is also possible with combined systems. Unlike distributed DHW systems discussed in Section 8.3, a combined-system approach maintains the ability to leverage large volumes of hot-water storage to facilitate load shifting while providing the benefits of a distributed DHW system. A distributed approach eliminates central DHW distribution and recirculation by utilizing the heating hot-water system for energy distribution. Hot water to DHW heat exchangers are located in each suite, floor, or fixture group to generate DHW on demand. This approach can be an economical solution for buildings with low use and distributed DHW needs. A few benefits of this approach over a stand-alone DHW distributed system are that electrical modifications are largely limited to the mechanical plant rather than being distributed throughout the building and that the system can still leverage thermal energy storage back at the plant for load shifting. The primary challenge when meeting both DHW and heating hot water needs with a single heat pump is the difference in operating temperatures between the systems. As discussed in Chapter 6, a key aspect to efficient HVAC electrification is operating with the lowest heating hot-water temperatures possible to increase heat pump efficiency. By implementing low-temperature terminal unit conversions, or an aggressive demand-based temperature reset, heating hot-water temperatures often may be lower than that required for DHW heating. DHW heating requires stable operating temperatures year-round, which severely limits options to reset hot-water temperatures. The performance of a combined space heating and DHW system must be evaluated against a decoupled system to understand trade-offs between energy efficiency, first costs, and GHG emissions reduction. It is often beneficial to provide a dedicated high-lift heat pump to meet the needs of DHW loads when the heating hot-water temperature set point is below useful temperatures for DHW heating. This can be accomplished in a number of configurations. In scenarios with a consistent year-round cooling load, a heat recovery chiller can be integrated into the system to reclaim heat from the cooling loads to service DHW needs. Alternatively, a dedicated high-lift AWHP or WWHP can be dedicated to DHW loads while also contributing to space heating needs when DHW is satisfied. Refer to Section 6.1.3 in Chapter 6 for considerations when sizing heat recovery chillers.

### 8.8.2 Hybrid Systems

As discussed elsewhere in the guide, particularly in Chapter 6, hybrid systems can be useful as part of a phased decarbonization approach. Hybrid systems combine fossil fuel equipment and electrified equipment within systems, which is different than dual-fuel equipment (described in Chapter 6), which combines fossil fuel and electric sources in the same piece of equipment. Existing fossil fuel systems can be retained for redundancy or peaking capacity. This is often a viable approach when financial constraints do not allow for required redundancy via additional heat pumps or when electrical service upgrades are being deferred to a later stage in a phased decarbonization approach, such as in the UC Santa Cruz case study. The risk with this approach is that the fossil fuel system ends up operating as the default stage for DHW, negating energy and carbon reduction savings. This is common when control systems are not carefully commissioned with approach deadbands and delays and when the operating strategy is not clearly communicated with operations staff.

## Glossary

alternating current. Electric current in an electrical circuit that periodically reverses polarity. boiler. A closed, pressure vessel that uses fuel or electricity for heating water or other fluids to supply steam or hot water for heating, humidification, or other applications. building automation system (BAS). An energy management system, usually with additional capabilities, relating to the overall operation of the building in which it is installed, such as equipment monitoring, protection of equipment against power failure, and building security. building energy model. Model based on first-principles engineering methods that provides information on the energy-using systems in a building (heating, ventilation, and air conditioning; lighting; occupancy; plug loads; building envelope). The model, along with weather data, serves as the input data for a specific computer building energy simulation program. When run, the computer simulation program will estimate the energy use and demand in the described building for a time interval specified in the building energy model. Depending on the kind of simulation program and how it is set up to run, various kinds of output may be produced. building envelope. (1) Outer elements of a building, including walls, windows, doors, roofs, and floors, including those in contact with earth. (2) The exterior plus the semi-exterior portions of a building. For the purposes of determining building envelope requirements, the classifications are defined as follows: building envelope, exterior: the elements of a building that separate conditioned spaces from the exterior; building envelope, semi-exterior: the elements of a building that separate conditioned space from unconditioned space or that enclose semi-heated spaces through which thermal energy may be transferred to or from the exterior, to or from unconditioned spaces, or to or from conditioned spaces. carbon dioxide (CO2). A naturally occurring gas and a by-product of burning fossil fuels (such as oil, gas, and coal), burning biomass, land-use changes (LUC), and certain industrial processes (e.g., cement production). It is the principal anthropogenic greenhouse gas (GHG) that affects the Earth’s radiative balance. It is the reference gas against which other GHGs are measured and therefore has a global warming potential (GWP) of 1. chiller. (1) direct-expansion chillers are complete refrigerating systems consisting of a compressor, condenser, and evaporator with all operating and safety controls. Compressor types include the following: reciprocating, centrifugal, or screw design. (2) Refrigerating machine used to transfer heat between fluids. Chillers are either direct expansion with a compressor or absorption type.

Glossary chilled-water, hot-water, and steam distribution systems. The systems used to distribute water and steam for cooling or heating spaces and processes. These systems may provide direct cooling or heating of spaces or may serve HVAC systems that provide cooling or heating. commissioning process. A quality-focused process for enhancing the delivery of a project. The process focuses upon verifying and documenting that the facility and all of its systems and assemblies are planned, designed, installed, tested, operated, and maintained to meet the Owner’s Project Requirements. cool thermal storage. See thermal energy storage. cooling load. (1) Amount of cooling per unit time required by the conditioned space or product. (2) Heat that a cooling system must remove from a controlled system over time. critical loads. Individual loads deemed to be critical to the operation of the facility or process. daylighting. Using natural, outdoor light to illuminate the interior spaces of a building evenly by means of proper window placements and orientations, skylights, clerestories, and other methods. decarbonization. The process of removing or reducing greenhouse gases. direct current (DC). Electric current in an electrical circuit that does not reverse polarity. Note: direct current is said to flow from positive to negative, but electrons travel from negative to positive. distributed energy resource. A small, modular, energy generation or storage device located within the electrical distribution system at or near the end user. Distributed energy resources may be connected to the local electrical power grid (e.g., for voltage support) or isolated from the grid in standalone applications, such as part of a microgrid. domestic hot-water systems. The systems used to heat and distribute hot water for domestic uses within a building. While these may include end-use devices, this guide will focus on the heating and distribution aspects of domestic hot-water systems. electric vehicle supply equipment (EVSE). The conductors—including the ungrounded, grounded, and equipment-grounding conductors—and the electric vehicle connectors, attachment plugs, and all other fittings, devices, power outlets, or apparatus installed specifically for the purpose of delivering energy from the premises wiring to the electric vehicle (NFPA 2023a). embodied carbon emissions. the total greenhouse gas emissions arising from the manufacturing, transportation, installation, maintenance, and disposal of an asset (i.e., building). energy efficiency. Refers to programs that are aimed at reducing the energy used by whole buildings and specific end-use devices and systems, typically without affecting the services provided. These programs reduce overall electricity consumption (reported in megawatt-hours [MWh]), often without explicit consideration for the timing of program-induced savings. Such savings are generally achieved by substituting technologically more advanced equipment to produce the same level of end-use services (e.g., lighting, heating, motor drive) with less electricity. Examples include high-efficiency appliances; efficient lighting programs; high-efficiency heating, ventilating, and air conditioning (HVAC) systems or control modifications; efficient building design; advanced electric motor drives; and heat recovery systems (EIA 2023). energy storage system. (1) System that has to be operated during on-peak as well as off-peak periods. (2) System wherein the load demand is met by a combination of stored thermal energy and an energy conversion device. energy usage intensity (EUI). An expression of the annual energy used or calculated to be used by a building or building space per unit of gross floor area. Expressed in MBtu/ft2·yr (Watt-h/m2·yr). existing building commissioning. Includes both recommissioning and retrocommissioning. HVAC system. The equipment, distribution systems, and terminals that provide, either collectively or individually, the processes of heating, ventilating, and air conditioning to a building or portion of a building.

interconnection. Two or more electric systems having a common transmission line that permits a flow of energy between them. The physical connection of electric power transmission facilities allows for the sale or exchange of energy (EIA 2023). inverter. A device that converts direct current electricity to alternating current either for standalone systems or to supply power to an electricity grid (DOE 2023). islanding. The condition in which a portion of the grid becomes temporarily isolated from the main grid but remains energized by its own distributed generation resource(s). Islanding may occur accidentally or deliberately. Traditionally, islanding has been seen by utility providers as an undesirable condition due to concerns about safety, equipment protection, and system control. Utility providers’ concerns about unintentional islanding have been a major impediment to the widespread adoption of distributed generation. For the most part, these concerns have been addressed through anti-islanding features in grid-interactive inverters and the provisions included in standards such as UL 1741 and IEEE 1547 (Greacen et al. 2013). load. (1) Amount of heat per unit time imposed on a system by the required rate of heat addition or removal. (2) Energy-absorbing device. (3) Material, force, torque, energy, or power applied to or removed from a system or element. load profile. Summary of thermal or other energy loads in a system over a period of time. For example, a common load profile on a peak design day for thermal storage designs would show hourly system load requirements for 24 hours. mechanical ventilation. (1) the active process of supplying or removing air to or from an indoor space by powered equipment such as motor-driven fans and blowers but not by devices such as wind-driven turbine ventilators and mechanically operated windows. (2) Ventilation provided by mechanically powered equipment, such as motor-driven fans and blowers, but not by devices such as wind-driven turbine ventilators and mechanically operated windows. microgrid. A group of interconnected loads and distributed energy resources within clearly defined electrical boundaries that acts as a single controllable entity with respect to the grid (Ton and Smith 2012). natural ventilation. Movement of air into and out of a space primarily through intentionally provided openings (such as windows and doors), through non-powered ventilators, or by infiltration. net metering. Connecting a customer’s alternative power-generating system to a public utility’s power grid to offset the cost of power drawn by the customer from the grid1. operational carbon emissions. the total greenhouse gas emissions associated with the operation of an asset (i.e., building) during the use stage of the asset. peak load. The maximum amount of power delivered (load) for a given time period. phase-change material (PCM). Substance that undergoes changes of state while absorbing or rejecting thermal energy at constant temperature. plug load. A device that is powered by means of an electrical plug and matching socket or receptacle. This excludes devices that are accounted for as part of major building end uses, such as HVAC, lighting systems, and water heating. process load. The load on a building resulting from the consumption or release of process energy. recommissioning (see existing building commissioning). an application of the commissioning process requirements to a project that has been delivered using the commissioning process. This may be scheduled developed as part of an ongoing commissioning process, or it may be triggered by use change, operations problems, or other needs. renewable energy systems. Distributed generation systems that convert renewable resources into energy. Examples include solar photovoltaics, solar thermal water and air heaters, wind turbine generators, hydraulic turbines, biomass boilers, and geothermal heat exchangers.

1. Dictionary.com, 2023, s.v. “Net meter.”

Glossary resilience. The ability to prepare for and adapt to changing conditions and withstand and recover rapidly from disruptions. Resilience includes the ability to withstand and recover from deliberate attacks, accidents, or naturally occurring threats or incidents (Sandia 2015). retrocommissioning (see existing building commissioning). the commissioning process applied to an existing facility that was not previously commissioned. The same process for retrocommissioning needs to be followed from predesign through occupancy and operations to optimize the benefits of implementing the commissioning process philosophy and practice. retrofit. modification of existing equipment, systems, or buildings to incorporate improved performance, updated operation, improved energy performance, or all three. Derived from retroactive refit. stranded assets. Assets that have suffered from unanticipated or premature write-downs, devaluation, or conversion to liabilities. thermal bridge. Low thermal resistance path connecting two surfaces. thermal energy storage (TES). (1) Thermal energy storage may refer to a number of technologies that stores energy in a thermal reservoir for later reuse. They can be employed to balance energy demand between day time and night time. The thermal reservoir may be maintained at a temperature above (hotter) or below (colder) than that of the ambient environment. The principal application today is the production of ice, chilled water, or eutectic solution at night, which is then used to cool environments during the day. (2) thermal energy storage technologies store heat, usually from active solar collectors in an insulated repository for later use in space heating, domestic or process hot water, or to generate electricity. Most practical active solar heating systems have storage for a few hours to a day's worth of heat collected. There are also a small but growing number of seasonal thermal stores used to store summer heat for space heating during winter. thermal mass. Walls and floors that absorb heat during the day and release it at night in winter (or cool down at night in summer) as outdoor temperatures rise or drop. variable-frequency drive (VFD). VFDs, the most common type of adjustable speed drive, are solid-state electronic motor controllers that efficiently meet varying process requirements by adjusting the frequency and voltage of power supplied to an alternating current (AC) motor to enable it to operate over a wide speed range. External sensors monitor flow, liquid levels, or pressure and then transmit a signal to a controller that adjusts the frequency and speed of the motor to match process requirements (DOE 2012). ventilation. (1) The process of supplying air to or removing air from a space for the purpose of controlling air contaminant levels, humidity, or temperature within the space. (2) The process of supplying or removing air by natural or mechanical means to or from any space. Such air may or may not have been conditioned. voltage. Electric potential or potential difference, expressed in volts.

## Case Studies

University of California, Santa Cruz—

Phasing Approach

This case study is adapted from the University of California, Santa Cruz 2023 Decarbonization and Electrification Predesign Report, provided courtesy of the University of California, Santa Cruz, and Affiliated Engineers, Inc. Decarbonizing a large area with multiple buildings, such as an entire college campus, often requires upgrades to be completed over the course of several phases. The University of California, Santa Cruz (UCSC), commissioned the Decarbonization and Electrification Predesign Report (Affiliated Engineers, Inc. 2023), which outlines the sequencing of projects needed to reduce emissions by 95% on campus. The plan includes installing centralized decarbonization stations: collections of ASHPs, TES, and supporting electrical infrastructure piped to nearby buildings to serve their heating and cooling needs. These decarbonization stations will be designed with space to add ASHPs as additional campus buildings are connected to them over time, breaking down the work into 12 phases between 2024 and 2040. This approach allows UCSC to phase the electrification of its campus buildings by constructing decarbonization stations and modularly connecting buildings over time. One of the major upgrades required to achieve its full electrification goals is additional electrical distribution to the campus. While increasing the electrical supply to UCSC is a major need, some regions of campus can be electrified now using the available power supply. There are multiple colleges on campus with buildings that have aging infrastructures and more immediate replacement needs that would be appropriate candidates for upgrades in the near term, before a decarbonization station is scheduled to be constructed nearby. This requires UCSC to develop a screening and prioritization approach to decarbonization upgrades in campus buildings. The figure shows the decision tree developed to help guide how equipment gets replaced in the near term to align with the long-term decarbonization plan. The order of these phases accounts for needs in existing buildings, utility infrastructure, and constraints presented by campus geography.

Case Study 1 University of California, Santa Cruz—Phasing Approach

**[Figure: Flowchart for Decarbonization Station]**

Type: flow diagram

Description: This flowchart outlines the decision-making process for determining whether a building should be electrified and connected to a Decarbonization Station. The chart considers various factors, including the building's size, scope, and timeline, as well as the availability of existing heating systems and the potential for replacing them with electric alternatives.

Process Steps:

1. **Does a Decarbonization Station exist?** -> If yes, proceed to step 2; if no, consider replacing the boiler.
2. **Is the heating demand >500 MBh?** -> If yes, proceed to step 3; if no, consider replacing the boiler.
3. **Is there medium voltage electrical capacity?** -> If yes, proceed to step 4; if no, consider replacing the boiler.
4. **Will the building be electrified in >7 years?** -> If yes, proceed to step 5; if no, consider replacing the boiler.
5. **Replace with a small air source heat pump** -> If feasible, proceed to step 6; if not, consider replacing the boiler.
6. **Replace a condensing boiler** -> If feasible, proceed to step 7; if not, consider replacing the boiler.
7. **Replace a conventional boiler** -> If feasible, proceed to step 8; if not, consider replacing the boiler.
8. **Funding to electrify?** -> If yes, proceed to step 9; if no, consider replacing the boiler.
9. **Demolish ASHP/boiler** -> If feasible, proceed to step 10; if not, consider replacing the boiler.
10. **Connect into the Decarbonization Station** -> If feasible, proceed to step 11; if not, consider replacing the boiler.
11. **Start a Decarbonization Station** -> If feasible, proceed to step 12; if not, consider replacing the boiler.
12. **Replace with a stand-alone electric system** -> If feasible, proceed to step 13; if not, consider replacing the boiler.
13. **Existing Heating** -> If feasible, proceed to step 14; if not, consider replacing the boiler.
14. **Under 3 floors and 25,000 sf?** -> If yes, proceed to step 15; if no, consider replacing the boiler.
15. **Only replacing the boiler?** -> If yes, proceed to step 16; if no, consider replacing the boiler.
16. **Direct-fired gas system** -> If feasible, proceed to step 17; if not, consider replacing the boiler.
17. **Electric heating** -> If feasible, proceed to step 18; if not, consider replacing the boiler.
18. **Gas boilers** -> If feasible, proceed to step 19; if not, consider replacing the boiler.
19. **How is the project heated today?** -> If feasible, proceed to step 20; if not, consider replacing the boiler.
20. **Yes** -> Proceed to step 21; if not, consider replacing the boiler.
21. **No** -> Consider replacing the boiler.

Flow Logic:

* If the building has an existing heating system, proceed to step 2.
* If the building does not have an existing heating system, consider replacing the boiler.
* If the building's heating demand is greater than 500 MBh, proceed to step 3.
* If the building's heating demand is less than or equal to 500 MBh, consider replacing the boiler.
* If the building has medium voltage electrical capacity, proceed to step 4.
* If the building does not have medium voltage electrical capacity, consider replacing the boiler.
* If the building will be electrified in more than 7 years, proceed to step 5.
* If the building will not be electrified in more than 7 years, consider replacing the boiler.
* If the building can be replaced with a small air source heat pump, proceed to step 6.
* If the building cannot be replaced with a small air source heat pump, consider replacing the boiler.
* If the building can be replaced with a condensing boiler, proceed to step 7.
* If the building cannot be replaced with a condensing boiler, consider replacing the boiler.
* If the building can be replaced with a conventional boiler, proceed to step 8.
* If the building cannot be replaced with a conventional boiler, consider replacing the boiler.
* If the building has funding to electrify, proceed to step 9.
* If the building does not have funding to electrify, consider replacing the boiler.
* If the building can be demolished and replaced with an ASHP/boiler, proceed to step 10.
* If the building cannot be demolished and replaced with an ASHP/boiler, consider replacing the boiler.
* If the building can be connected into the Decarbonization Station, proceed to step 11.
* If the building cannot be connected into the Decarbonization Station, consider replacing the boiler.
* If the building can start a Decarbonization Station, proceed to step 12.
* If the building cannot start a Decarbonization Station, consider replacing the boiler.
* If the building can be replaced with a stand-alone electric system, proceed to step 13.
* If the building cannot be replaced with a stand-alone electric system, consider replacing the boiler.
* If the building has existing heating, proceed to step 14.
* If the building does not have existing heating, consider replacing the boiler.
* If the building is under 3 floors and 25,000 sf, proceed to step 15.
* If the building is not under 3 floors and 25,000 sf, consider replacing the boiler.
* If the building is only replacing the boiler, proceed to step 16.
* If the building is not only replacing the boiler, consider replacing the boiler.
* If the building has a direct-fired gas system, proceed to step 17.
* If the building does not have a direct-fired gas system, consider replacing the boiler.
* If the building has electric heating, proceed to step 18.
* If the building does not have electric heating, consider replacing the boiler.
* If the building has gas boilers, proceed to step 19.
* If the building does not have gas boilers, consider replacing the boiler.
* If the building is heated today, proceed to step 20.
* If the building is not heated today, consider replacing the boiler.

Key Components:

* Decarbonization Station
* Existing Heating
* Direct-fired gas system
* Electric heating
* Gas boilers
* Small air source heat pump
* Condensing boiler
* Conventional boiler
* ASHP/boiler
* Stand-alone electric system

Structured Flow (Machine Read

Figure CS1.1 Example decision tree for replacements of fossil fuel heating systems. (Image credit: Affiliated Engineers Inc. [2023])

These projects can be prioritized appropriately as funds and schedules allow. The order of these phases accounts for needs in existing buildings, utility infrastructure, and constraints presented by campus geography. See the Decarbonization and Electrification Predesign Report (Affiliated Engineers, Inc. 2023) for a full analysis of all options.

# 345 Hudson, New York

This case study is provided courtesy of Hines with adaptations from the Building Energy Exchange Partner Profile in their High Rise/Low Carbon series, sponsored by NYSERDA and highlighting NYSERDA's Empire Building Challenge. Hudson Square Properties (HSP)—comprising Hines, Trinity Church Wall Street, and Norges Bank— owns 12 buildings in New York City, including 345 Hudson. The 345 Hudson building is the most carbon-intensive building in the HSP portfolio that occupies the city block between King and Charlton streets. HSP is taking advantage of tenant turnover at 345 Hudson to upgrade the building and decarbonize building systems with the following goals:

- Net zero by 2030
- Fossil-fuel-free heating
- 30% to 40% reduction in energy use
- Compliance with NYC Local Law 97 HSP is constructing a new commercial building, 555 Greenwich, that adjoins the existing 345 Hudson. A key part of the design for 345 Hudson and 555 Greenwich will be a shared thermal network that will allow for thermal energy recovery not only between floors of a building but between the two buildings. Implementation of the ambient loop thermal network is underway at 345 Hudson, including:
- a comprehensive data strategy connecting all the current equipment on a common platform for data collection, monitoring, and verification at every step
- floor-by-floor replacement of packaged terminal units by WSHP and DOAS for heating/cooling needs and fresh air supply with minimum 85% heat recovery
- ASHP connected to condenser water loop as part of a master plan to phase out boiler heat by providing heat via a heat pump
- TES water storage tank and connection to adjacent 555 Greenwich for thermal energy transfer to leverage the varying orientation/occupancy of each building Key members of the team tackling the decarbonization retrofit for 345 Hudson Square are:
- OWNER: Hudson Square Properties (Hines, Trinity Church Wall Street, Norges Bank)
- SYSTEM DESIGN ENGINEER: URBS
- DESIGN ENGINEER OF RECORD: Jaros Baum and Bolles
- GENERAL CONTRACTOR: Consigli Construction
- MANUFACTURERS
- Water Source Heat Pumps: Energy Machines
- Direct Outdoor Air Handling Unit: Climate Machines
- Air Source Heat Pumps: AERMEC
- Fluid Coolers: GUNTNER

Case Study 2 345 Hudson, New York

### Table: Data Table

| Size | 856,000 ft2 | Year Built | 1931 | Budget |  |
|---|---|---|---|---|---|
| Location | 345 Hudson St. | City | New York City | NYSERDA Funding | $5 million |
|  |  | Implementation Phase | 2022–2032 | Hudson Square Properties Private Investment | $40 million |
| Existing Building Properties |  |  |  |  |  |
| • Steel frame with limestone cladding • Electric water-cooled packaged terminal cooling units • Central natural gas boiler serving two-pipe steam radiators |  |  |  |  |  |
| Key Retrofit Measures |  |  |  |  |  |
| • A comprehensive data strategy connecting all the current equipment on a common platform. This becomes the backbone for data collection, monitoring, and verification at every step. • Floor-by-floor replacement of packaged terminal units by DOAS for fresh air supply with minimum 85% heat recovery. This keeps the heat within the building and minimize energy input for heating and cooling of ventilation. • Floor-by-floor replacement (floors 2, 3, 7, 8, 9) of packaged terminal units by WSHP to meet heating and cooling needs. This provides heating, cooling, and DHW to each floor; allows for the removal of steam radiators; and maximizes simultaneous energy production. • ASHP connected to CW loop. This uses one hydronic transport system for both heating and cooling and represents a step toward phasing out the boiler by providing heat via a heat pump. • TES water storage tank. This utilizes simple water tanks for energy storage to avoid wasted energy. • 555 Greenwich Connection. This connects the adjacent building for waste energy transfer and takes advantage of the varying orientation/occupancy of each building. • Floor-by-floor replacement (floors 10, 11, 13, 16, 17) of packaged terminal units by WSHP to meet heating and cooling needs. This provides a floor-level means to provide heating, cooling, and DHW to a floor; remove steam radiators; and maximize simultaneous energy production. • Floor-by-floor replacement (floors 4, 5, 6, 12, 14, 15) of packaged terminal units by WSHP to meet heating and cooling needs. This provides a floor-level means to provide heating, cooling, and DHW to a floor; remove steam radiators; and maximize simultaneous energy production. |  |  |  |  |  |

Project Design Approach

The HSP team is a participant in the NYSERDA Empire Building Challenge (EBC) and used a Strategic Decarbonization Assessment (SDA) tool created by NYSERDA to compare the alternatives for decarbonization upgrade measures for 345 Hudson. The tool relied on user input of building information and assumptions, including but not limited to physical characteristics, regulatory targets, energy use, and existing equipment and infrastructure. Key drivers/decision points for selection of the measures listed were NPV, GHG emissions reductions, electrification, and conversion to a thermal network. Two baseline business-as-usual (BAU) scenarios were evaluated:

- non-compliance and payment of reactive fines for NYC Local Law 97
- offset-based compliance with emissions mandates

Then three alternatives with different sets of measures were evaluated, including an alternative incorporating all the measures considered for 345 Hudson. The approach to the retrofit options was devised by dividing the energy system of the building into three distinct “system boundaries,” based on how an investment is generally deployed and how it is operated and maintained. Three alternatives for tenants to choose between a good, better, and best option were provided.

Alternative 1: “Best”—Unlocking the Full Potential

- WSHP loop serving space-conditioning end uses
- Active high-temperature chilled beams + radiant slab
- Active beams that work with high-temperature cooling
- Self-regulating radiant slab at a set temperature, using the thermal mass and inertia to provide heating and cooling with minimal energy input

Alternative 2: “Better”—Activating the Thermal Mass

- Radiant slab + variable airflow ventilation
- Self-regulating radiant slab at a set temperature, using the thermal mass and inertia to provide heating and cooling with minimal energy input
- VAV supplied via DOAS with high heat recovery efficiency to balance the loads and act as a booster to the radiant slab

Alternative 3: “Good”—High Efficiency

- Option: Active beams that work with high-temperature cooling
- Active high-temperature chilled beams + perimeter radiators to work with relatively low temperatures
- Option: DOAS boxes served by high temperature chilled water
- Option: Air handlers with VAV boxes

The alternatives and operation measures were defined, and the implementation of each was modeled based on a defined schedule. These can be seen in the analysis snapshots below showing the NPV of each scenario (Figure CS2.1) and the GHG emissions reduction of each scenario compared to NYC Local Law 97 building GHG performance targets. The retrofit solution is much in advance of the LL97 targets set for both 2030 and 2050, with the building set to achieve 2030 targets in 2025 and 2050 targets in 2030. After the complete retrofit, the GHG emissions of the building will reduce in line with the greening of the grid in New York State.

The final option selected was a combination of the alternatives proposed, chosen to adapt to the current New York City mechanical design practices. The design now includes heat pumps on each floor supported by an air-source heat pump on the roof. The energy delivery to the tenant spaces remains flexible for each tenant to choose. This was chosen considering the flexibility to the tenant in the current leasing market conditions.

Thermal Network

A key feature of the 345 Hudson project is the thermal network that will recover heat within the building(s) and circulate to other parts of the building requiring heat. The design strategy, led by Urbs | Urban Systems, a Stockholm, Sweden–based consulting engineer, follows an approach labeled the Nordic Model. This approach takes a whole-building systems perspective

Case Study 2 345 Hudson, New York

**[Figure: Relative NPV of Alternatives]**

Type: chart

Description: This chart compares the relative Net Present Value (NPV) of different alternatives for a selected analysis period. The key insight is that Alternative 2 has the highest NPV, followed by Alternative 1, while Alternative 3 has the lowest NPV.

Data Representation:

*   Alternative 1: $14 million
*   Alternative 2: $15 million
*   Alternative 3: $10 million
*   Metric: Relative NPV
*   Chart Type: Bar chart
*   Units: Millions of dollars

Chart Generation Hint:

*   X-axis: Alternatives
*   Y-axis: Relative NPV (in millions of dollars)

Structured Data (Machine Readable):

```json
{
  "chart_type": "bar",
  "metric": "relative NPV",
  "units": "millions of dollars",
  "data": {
    "Alternative 1": 14,
    "Alternative 2": 15,
    "Alternative 3": 10
  }}
}

Figure CS2.1 NYSERDA Strategic Decarbonization Assessment tool results—net present value comparison of project alternatives

**[Figure: Carbon Emissions Per Year (Before Offsets)]**

Type: chart

Description: This line chart compares the carbon emissions per year for three different scenarios: Alternative 1, Alternative 2, and Alternative 3. The key insight is that all three scenarios show a decrease in carbon emissions over time, with Alternative 1 having the highest emissions and Alternative 3 having the lowest.

Data Representation:

*   Alternative 1: 5000 tons of CO2eq/year
*   Alternative 2: 4000 tons of CO2eq/year
*   Alternative 3: 3000 tons of CO2eq/year
*   Metric: Tons of CO2eq/year
*   Chart Type: Line chart
*   Units: Tons of CO2eq/year

Chart Generation Hint:

*   X-axis: Year
*   Y-axis: Tons of CO2eq/year

Structured Data (Machine Readable):

```json
{
  "chart_type": "line",
  "metric": "tons of CO2eq/year",
  "units": "tons of CO2eq/year",
  "data": {
    "Alternative 1": 5000,
    "Alternative 2": 4000,
    "Alternative 3": 3000
  }}
}

Figure CS2.2 NYSERDA Strategic Decarbonization Assessment tool results— carbon emissions comparison of project alternatives rather than tackling individual equipment and views heat as a resource within the building and not just an input.

First, the design separates ventilation from heating and cooling using a DOAS for fresh air supply to building spaces in order to meet indoor air quality standards. To reduce heating loads, the DOAS employs a heat recovery system that captures a minimum of 85% of heat to temper incoming outdoor air.

The thermal network for heating and cooling then makes use of existing fire protection rooftop water tanks for thermal storage as a repurposed condenser water loop. The network includes a thermal spine that runs vertically throughout the building, with hydronic loops connected to WSHP on each floor. The hydronic loop provides water at a temperature ranging between 57°F and 66°F to the WSHP, which then provides high-temperature chilled water or low-temperature hot water for conditioning individual floors via chilled beams and hydronic radiators. The system replaces the existing packaged terminal cooling units and steam radiators.

Future Upgrades to Hot Water Systems

While the focus of the project design has been on space heating and cooling, the HSP team is exploring potential options for WSHP to supply domestic hot-water needs. Ideally, these would be connected to the thermal network, but that has not yet been addressed.

Project Phasing Plan

To complete such a large project, the HSP team developed a phased approach. The phasing was divided into two parts: on-floor work and core and rooftop infrastructure work. The major base building infrastructure must be retrofitted and phased in such a way that the building can stay online with minimal phased shutdowns, adding to the logistical challenges of the retrofit. The major infrastructure across both phases is planned for completion by 2025. Fortunately for 345 Hudson, incoming electrical service capacity is not required to be increased. However, there will be an increase in electrical use for the building even though the overall energy required to operate the building will go down. The team is working with their local utility regarding this load differential.

**[Figure: Roadmap to 100% Electric Building]**

Type: diagram

Description: The diagram presents a roadmap for achieving a 100% electric building, outlining key milestones and strategies from 2020 to 2030. It highlights the importance of data strategy, replacing primary AHU with high energy recovery, deep retrofit floors, moving to ambient loop, enabling data and AI solutions, connecting thermal storage, and completing the ambient loop.

Key Elements:

*   Data Strategy -> Connect Everything
*   Replace Primary AHU with High Energy Recovery
*   Deep Retrofit Floors - 2,3,7, 8, & 9
*   Move To Ambient Loop (Add ASHP And Dry Coolers)
*   Enable Data And AI Solutions
*   Connect Thermal Storage - Water Tanks
*   Connect To 555 GW To Share Energy
*   Deep Retrofit Floors - 10, 11, 13, 16, & 17
*   Deep Retrofit Floors - 4, 5, 6, 12, 14, & 15
*   Complete Ambient Loop - 100% Electric Building

Figure CS2.3 Timeline for project phasing plan

Case Study 2 345 Hudson, New York

The core and rooftop infrastructure work was planned at the beginning of the retrofit, in consideration of the existing systems and the overall impact it has on the building’s energy consumption. Various modifications to the building structure are required to support the new rooftop equipment, and those were planned into the schedule. The on-floor work was planned with vacant floors and was phased in accordance with the tenant turnover cycle, as seen in the timeline above. Given that the lease durations are typically ten years, all tenants will change at least once between 2022 and 2032, making the entire building retrofit possible by 2030 (the latest by the close of 2032). A critical aspect of the phasing plan for the decarbonization retrofit is minimizing disruption to existing tenant spaces and to building services. At 345 Hudson, the team is only completing full floor retrofits on vacant floors and over time to preserve capital and complete spaces as it makes sense. Following this plan, currently occupied floors will be retrofitted upon lease termination or floor redesign. At the time of the project design, 50% of the building was vacant, so the team retrofitted four floors in 2023 and planned to retrofit another four floors in late 2024 if there is a need due to leasing. As seen in the schedule, remaining floors are planned for completion in coming years as leases roll over.

Key Takeaways

# 345 Hudson is in the midst of implementation and is still tackling challenges for completing a state- of-the-art decarbonization retrofit while keeping the building operational for tenants. Lessons learned by the team during the design and to date in the implementation process include the following: • Look for ways to create thermal networks within buildings that can continue to utilize vertical building infrastructure • Go beyond your own borders and explore other markets to find new ideas • Working with new (and international) equipment suppliers and learning the differences between markets can be an immense challenge • This has been mitigated with factory visits to review products and detailed preparation for the commissioning and start-up process • Planning a phased retrofit that takes advantage of lease rollover and floor redesign is an effective way to minimize tenant disruption • Including modular or networked designs makes phasing more feasible for ease of integrating floors as they are retrofitted

San Diego State University, California

This case study is provided courtesy of P2S Inc. with adaptations from the ASHRAE Journal, Vol. 65, no. 2, February 2023—Responsible Approach to Decarbonization in an Existing Building (Del Monaco 2023). San Diego State University (SDSU) aspires to achieve carbon neutral status within the next 15 years, and one key mandate is the elimination of natural gas for hydronic and domestic hot-water heating. For this project, failing steam infrastructure at a particular section of the distribution was the primary motivation for a centralized heating plant to serve a cluster of three buildings. Two of the buildings were constructed circa 1960, and the third building was constructed within the last five years.

### Table: Data Table

| Project Name | San Diego State University | Year Built |  | 1960, 1962, 2010 |
|---|---|---|---|---|
| Location | San Diego, CA | Building Size |  | 126,000 ft2, 93,000 ft2,  110,000 ft2 |
| Project Phase | Assessment | Year Last Systems Upgrade |  | N/A |
| Key EEMs/ERMs |  |  |  |  |
| • Central hybrid plant with heat recovery chiller and gas-fired boilers |  |  |  |  |
| Central Plant |  |  |  |  |
| Existing |  |  | Retrofit |  |
| Cogeneration plant with steam-to-hot-water converters at each building to local heating hot- water (HHW) plants |  |  | Water-cooled heat recovery chiller providing 80% of building heating loads at 110°F Natural-gas-fired condensing boilers operating at 135°F for peak heating loads |  |

Existing Systems

SDSU has a cogeneration plant with steam-to-hot-water converters at each building providing local heating hot-water (HHW). As part of their plan to achieve carbon neutral status, they are considering transitioning away from the cogeneration plant. The existing building distribution and terminal equipment were designed for a 180°F (82°C) HHW supply temperature. SDSU had Btu meters installed on the HHW side of the heat exchangers, allowing analysis of the actual operation of the system rather than having to rely on the existing equipment capacity or develop a detailed load calculation to size the new plant. The table shows that assuming the existing installed equipment to be sized correctly results in a grossly oversized system with higher capital costs. Such a system is also likely to encounter limitations due to the existing building infrastructure. The data analysis also provided an opportunity to understand other potential issues with the current system operation. As an example, Building A showed a peak heating demand of 27 Btu/h·ft2 (85 W/ m2) prior to the plant upgrades. This value was not in line with expectations and data from similar campus buildings. Evaluation of these data allowed the team to be proactive in its approach and to make improvements to correct issues at the load. For example, the design included the replacement

Case Study 3 San Diego State University, California of three-way valves with two-way valves, eliminating other bypass means and temperature resets. The post-construction data show the peak demand to be 10 Btu/h·ft2 (32 W/m2).

### Table: Data Table

| Table CS3.1 Existing Building Heating Equipment vs. Actual Heating Demand |  |  |  |  |  |
|---|---|---|---|---|---|
| Bldg | Use | Existing Equipment Sizing |  | Analyzed Equipment Sizing |  |
|  |  | Heating Capacity, Mbh | Heating Capacity, Btu/h Per ft2 | Peak Demand, Mbh | Peak Demand, Btu/h per ft2 |
| A | Engineering Classrooms & Labs | 4600 | 49.45 | 2543 | 27* |
| B | Science Classrooms & Labs | 4500 | 44.9 | 2041 | 10.5 |
| C | Geology and Mathematics  Classrooms & Labs | 4,760 | 37.0 | 1,610 | 12.0 |
| * Upon completion of the system upgrades, including replacement of three-way valves and temperature resets, th e 2 measured peak demand was 10 Btu/h·per ft . |  |  |  |  |  |

Analysis of the building reheat coils was performed, and it was determined that 100% of loads could be provided at the one-row heating coils at a reduced HHW supply temperature of 135°F (57°C). The team performed further analysis of the coils at a 110°F (43°C) supply temperature.

Central Plant Retrofit

Three options for a central plant retrofit were evaluated. The approach to the retrofit options was devised by dividing the energy system of the building into three distinct “system boundaries” based on how an investment is generally deployed and how it is operated and maintained. Three options for tenants to choose between a good, better, and best option were provided.

Option 1: All-Electric Heat Pump

An air-source heat pump operating in heating-only mode to provide 100% of the building’s HHW needs. Although this machine has cooling capabilities, it will be run only in heating mode. Two banks of six modules will operate in a two-pipe configuration in heating-only mode and will not be tied into the campus chilled-water system to reject the cooling water.

In this case, the COP at peak heating operation is approximately 2.12 kW/kW (7.5 kW/ton). The COP will increase if the system can operate at a lower HHW supply temperature; however, the one-row coils within the building require a HHW supply temperature of 135°F (57°C), and further reset is not possible without modifying the coils if the site experiences ambient temperatures below 40°F (4.4°C). In this case, supplemental heating would be required due to limits related to the ambient lift capabilities of this machine.

Option 1 is a fully independent heating system but presents significant challenges related to weight, physical size, electrical requirements, and first costs. The existing facility that would house the new heat pump equipment (Building B) has an 800A electrical service, which would require upsizing.

Option 2: All-Electric Heat Recovery Chiller A water-cooled heat pump operating in heating-only mode to provide 100% of the building’s HHW needs. One bank of six modules operating in a four-pipe configuration in heating-only mode that will tie into the campus chilled-water system to reject cooling water. The HHW temperature is set to 135°F (57°C) to ensure existing building coils can meet loads at the lowest possible supply temperature. The equipment COP is approximately 5.0. This option requires pumps on the chilled-water side to ensure that chiller modules maintain the required differential pressure drop across the heat exchanger. Like Option 1, Option 2 would require upsizing the electrical service to Building B. Option 3: Hybrid Plant—Heat Recovery Chiller and Condensing Boilers Option 3 is a hybrid option, which will include a water-cooled heat recovery chiller (HRC) operating in heating-only mode to provide 80% of the building’s annual HHW therms (roughly 25% of peak capacity). This option will consist of a bank of modules operating in a four-pipe configuration in heatingonly mode that will tie into the campus chilled-water system to reject cooling water. For peak loading, supplemental gas-fired boilers will be provided. The HHW supply temperature is set to 110°F (43°C) when the HRC is operating at low-load conditions (and higher ambient temperatures) and to 135°F (57°C) when the gas-fired boilers are operating at peak heating needs. In this case, the HRC equipment COP is approximately 7.0. The HRC requires pumps on the chilled-water side to ensure that the chiller modules maintain the required differential pressure drop across the heat exchanger. Gas-fired boilers are designed as part of the system for condensing temperatures and will operate during peak loads, when the HRC can no longer maintain system loads. Option 3 did not require upsizing the electrical service to Building B and demonstrated a 15year simple payback. Options 1 and 2 did not provide any simple payback. To confirm that Option 3 was viable, a meter read of the facility was performed, which determined the actual load (plus a 25% safety factor) was 343A of the total available 800A. The evaluation considered first costs and

**[Figure: Operational Carbon Emissions Savings - Heating Plant Electrification]**

Type: chart

Description: This chart compares the operational carbon emissions savings of different heating plant electrification options. The key insight is that gas-fired boilers have the highest emissions, while hybrid plant chillers have the lowest.

Data Representation:

* Base Case: Gas-fired Boilers: 608 tons
* Option 1: All-Electric HP: 326 tons
* Option 2: All-Electric HR Chiller: 138 tons
* Option 3: Hybrid Plant Chiller: 236 tons

Metric: Operational carbon emissions savings

Chart Type: Bar chart

Units: Tons

Chart Generation Hint:

* X-axis: Heating plant electrification options
* Y-axis: Operational carbon emissions savings (tons)

Structured Data (Machine Readable):

{
  "chart_type": "bar",
  "metric": "operational carbon emissions savings",
  "units": "tons",
  "data": {
    "Base Case: Gas-fired Boilers": 608,
    "Option 1: All-Electric HP": 326,
    "Option 2: All-Electric HR Chiller": 138,
    "Option 3: Hybrid Plant Chiller": 236
  }}
}

Figure CS3.1 Operational carbon analysis. (Image credit: Del Monaco 2023)

Case Study 3 San Diego State University, California carbon emissions as the main key performance indicators (KPIs). This is an oversimplified approach, and many other considerations should be taken into account when determining the appropriate system type. For simplicity, a more detailed life-cycle cost analysis (LCCA) has not been included here but should be considered for any project. The baseline system for the carbon analysis was a natural-gas-fired plant using condensing boilers with a peak efficiency of 96%, with an assumed average efficiency of 89%. Many factors came into consideration to finally determine that a hybrid plant was the most viable solution to move toward electrification. Options 1 and 2 could be achievable but would require HHW thermal storage to downsize the heat pumps to avoid an upgrade to the electrical infrastructure or would require an upgrade to the electrical service. The hybrid plant offered SDSU the opportunity to introduce electrification technology to the campus while also providing a backup gas-fired system, which SDSU was much more accustomed to maintaining and operating. It also provided resilience to the system, making it not reliant solely on the electrical grid. The hybrid approach is a satisfactory retrofit solution to significantly reduce carbon emissions by operating the HRC for a majority of annual heating therms, while significantly improving the ROI compared to an all-electric plant.

University of California, Santa Cruz—Cogeneration Plant

This case study is adapted from the University of California, Santa Cruz’s 2023 Decarbonization and Electrification Predesign Report, provided courtesy of the University of California, Santa Cruz, and Affiliated Engineers, Inc. The University of California, Santa Cruz (UCSC), is targeting a 95% reduction in fossil fuel emissions and has prepared the Decarbonization and Electrification Predesign Report with four scenarios to achieve this goal by 2030, 2035, 2040, and 2045. This report focuses on emissions directly from university operations and presents an approximate cost of $700 million (in 2023 dollars). UCSC’s on-campus energy generation includes a natural gas cogeneration plant—the Fackler Cogeneration Plant—and just over 2 MW of PV solar. The cogeneration plant accounts for approximately 60% of GHG emissions for the entire campus. In 2015 the cogeneration turbine was replaced and financed with a long-term loan that will not be fully amortized until 2045. This plays a key role in determining which of the decarbonization scenarios UCSC will pursue because the cogeneration plant could be seen as a stranded asset that the university would continue to pay for if it is underutilized prior to 2045. Decommissioning the cogeneration plant also largely depends upon the sequencing of electrification upgrades to air and water heating systems in individual buildings. UCSC is reviewing multiple options to reduce dependence on the Fackler Cogeneration Plant to make a final plan for the plant. The final determination for the cogeneration plant weighs first costs, reduction of GHG emissions, and reliability of energy services from the local utility to support campus electrification, all within the context of UCSC’s Long Range Development Plan. Retiring the cogeneration plant without adding electrical capacity to the campus will strain the local utility’s supply and reduce system reliability. The campus also relies on the existing cogeneration plant’s heat output to serve the science and engineering buildings on the central heating loop, and the plan calls for the heat output from the plant to be replaced with commercial-scale air-source heat pumps. UCSC will need to increase the capacity of the utility electrical service to the campus to account for increased electrical demand associated with decarbonizing both the central plant and other buildings on campus. The increased utility electrical service will compensate for the reduced on-site electrical generation from the cogeneration plant. Additional electrical supply would enable UCSC to reduce the plant’s operating hours and retrofit it to become a backup source of power that is only utilized when there is a local utility power outage. If the cogeneration plant is a backup source of energy, it could be converted to a cleaner alternative energy source, such as green hydrogen (when commercially viable), to further reduce emissions from the plant in this scenario. Find more detail on UCSC’s options for the cogeneration plant and campus electrification in its Decarbonization and Electrification Predesign Report.

The Heritage, New York

This case study is adapted from L+M Development Partners Low Carbon Retrofit Proposal to the Empire Building Challenge for the Heritage, provided courtesy of L+M Development and Steven Winter Associates. L+M Development Partners is committed to achieving carbon neutrality (a 0% emissions level) by 2030. L+M’s definition of a carbon neutral building is one that:

- incorporates significant energy conservation measures, including a high-performance building envelope and energyefficient building systems
- electrifies building systems and loads and employs energy storage systems where feasible
- utilizes smart metering and real-time energy management systems to reduce peak demand
- is staffed by proactive operating teams that work with utilities and other stakeholders to institute protocols that respond to grid conditions
- purchases renewable electricity and carbon offsets as a last resort to account for minimal remaining fossil fuel loads that are difficult or costly to electrify.

**[Figure: Figure on page 186]**

Type: diagram

Description: The image depicts a cityscape with two large buildings, one on the left and one on the right, set against a clear blue sky. The building on the left is taller and has more floors than the one on the right. Both buildings have balconies and windows, and there are trees and cars in front of them.

Key Elements:

- Building on the left -> It is the taller of the two buildings and has more floors.
- Building on the right -> It is shorter than the building on the left and has fewer floors.
- Trees -> They are located in front of both buildings.
- Cars -> They are parked in front of the buildings.
- Streetlights -> They are visible in front of the buildings.
- Crosswalk -> It is visible in front of the buildings.
- Traffic light -> It is visible in front of the buildings.
- Pedestrian -> They are walking across the crosswalk.
- Bus -> It is driving down the street.
- Street sign -> It is visible above the crosswalk.
- Fire hydrant -> It is visible on the sidewalk.
- Trash can -> It is visible on the sidewalk.
- Bench -> It is visible on the sidewalk.
- Bike rack -> It is visible on the sidewalk.
- Construction equipment -> It is visible on the sidewalk.
- Construction workers -> They are working on the sidewalk.
- Scaffolding -> It is visible on the side of the building.
- Ladder -> It is visible leaning against the building.
- Window -> It is visible on the side of the building.
- Door -> It is visible on the side of the building.
- Awning -> It is visible above the door.
- Sign -> It is visible above the awning.
- Flag -> It is visible flying above the building.
- Clouds -> They are visible in the sky.
- Sun -> It is visible shining down on the scene.
- Shadows -> They are visible on the ground and buildings.
- Reflections -> They are visible in the windows and other shiny surfaces.

This image appears to be a photograph of a city street, possibly taken for architectural or urban planning purposes. The presence of construction equipment and workers suggests that the area may be undergoing development or renovation. The image provides a detailed view of the buildings, streets, and surrounding environment, which could be useful for architects, urban planners, or researchers studying urban development.

Figure CS5.1 Exterior view of The Heritage before retrofit.

L+M Development Partners proposes a package of measures at the Heritage designed to eliminate fossil fuel usage, improve resident comfort, and minimize disruption in occupied multifamily properties through the use of innovative retrofit methods, materials, and technology. The Heritage comprises two 35-story high-rise buildings at 1295 and 1309 Fifth Avenue, which overlook the northeastern corner of Central Park, and an 11-story building at 1660 Madison Avenue that consists of four-to-fivebedroom multifamily units in addition to four stories of commercial space. Built in 1975, the buildings have little to no remaining insulation, costly and inefficient baseboard electric resistance heat systems, and central natural-gas-fired domestic hot-water (DHW) plants. With a proposed investment of $18 million, the planned electrification measures aim to reduce the energy use intensity (EUI) by 5% and carbon emissions by a total of 352 tons of CO2-eq/year within the first two years. Over a 20-year period, a reduction in EUI by 19% and 2636 tons of CO2-eq/year is expected.

Case Study 5 The Heritage, New York

**[Figure: 187]**

Type: diagram

Description: The image presents a before-and-after comparison of a building's exterior, showcasing its transformation from a state of disrepair to a renovated condition. The left side of the image depicts the building in its original state, with visible signs of deterioration and neglect. In contrast, the right side of the image displays the same building after undergoing renovation, featuring a newly restored facade and improved overall appearance.

Key Elements:

*   **Before Renovation**: The left side of the image shows the building in its original state, characterized by visible signs of deterioration and neglect.
*   **After Renovation**: The right side of the image displays the same building after undergoing renovation, featuring a newly restored facade and improved overall appearance.

Figure CS5.2 (Left) Upgrades to Facade, (Right) EIFS installation at The Heritage

### Table: Data Table

| Site | The Heritage | Year Built | 1975 | Budget |  |
|---|---|---|---|---|---|
| Location | 1295 and 1309 Fifth Avenue | City | New York | NYSERDA Funding | $5 million |
|  | 1660 Madison Avenue | Implementation Phase | 2021–2024 | L+M Private Investment | $13.7 million |
| Existing Building Properties |  |  |  |  |  |
| • Little to no insulation in walls and roof • Electric resistance baseboard heaters in each room with limited controls; no centralized air-condi- tioning system, only A/C sleeves • Natural-gas-fired domestic hot-water heaters with storage tanks on rooftop to provide hot water • Natural-gas-fired hot-water sources for dryers and washers • 1295 and 1309 Fifth Avenue building lobbies are served by 10-ton horizontal packaged air-cooled split systems |  |  |  |  |  |
| Key Retrofit Measures |  |  |  |  |  |
| • Facade overcladding with exterior insulated facade system (EIFS) at 1295 Fifth Avenue and 1309 Fifth Avenue. Facade upgrades using insulated, prefabricated metal panels with energy-efficient win- dows at 1660 Madison • Installation of Packaged Terminal Heat Pumps (PTHPs) at 1660 Madison Avenue • DHW electrification using heat pump water heaters at 1660 Madison Avenue • Implementation of centralized controls at 1660 Madison Avenue • Common area dryer electrification at 1660 Madison Avenue • Central ventilation upgrades at 1660 Madison Avenue • Variable refrigerant flow (VRF) installation in first floor common areas at 1295 and 1309 Fifth Avenue • Submetering apartment electrical use at all three buildings |  |  |  |  |  |

L+M overclad with exterior insulation finish system (EIFS) for the towers at 1295 and 1309 Fifth Avenue and floors 1–4 of 1660 Madison Ave. The existing masonry for both buildings will be clad with four- and five-inch-thick prefabricated insulation systems. The roof, which is currently uninsulated for the most part, will be augmented with R-30 insulation at 1660 Madison Ave. Existing residential and commercial windows at 1660 Madison are being replaced with double-pane insulated glass units with a U-value of 0.25. 1660 Madison facade upgrades for floors 5–12 use prefabricated panels in conjunction with window replacements and PTHP installation. Coordinating this construction work allows for efficiencies during the window replacement, as some window sizes will be increased, and while punching wall penetrations to accommodate PTHPs. A coordinated mobilization of these major building improvements minimizes the disruption to residents. This measure constitutes enabling work that prepares buildings for future decarbonization by permanently reducing heating and cooling loads. This measure allows for smaller-sized HVAC equipment as part of this work and in future upgrades.

Upgrades to HVAC System

L+M is installing PTHP units in each living room and bedroom of each apartment of 1660 Madison thereby increasing efficiency of the heating system as well as providing optional air conditioning and eliminating the need for window ACs and sleeve units. The selected units are cold climate models; units will not be provided with electric resistance heat back up since the units can operate at outdoor temperatures down to -5ºF. The units will be sized taking into consideration the modified loads due to improved wall insulation, window replacement, and increased airtightness. The lobbies at 1295 and 1309 Fifth Avenue are currently served by 10-ton horizontal packaged aircooled split systems with electric resistance baseboard heaters. A variable refrigerant flow (VRF) system is proposed to condition the lobby and amenity spaces, eliminating the need for different heating and cooling systems. Further, installation of a VRF system will also contribute to increasing the available space as the main components of the system can be moved outside. L+M is investigating an appropriate heat pump replacement for the Fifth Avenue tower baseboard electric heaters and sleeve AC units. The height of the towers results in significant construction challenges as well as considerable cost. As heat pump technology continues to improve and the up-front capital cost declines, L+M anticipates this technology will be feasible prior to 2030.

Upgrades to Hot-Water Systems

The existing gas-fired hot-water boilers with storage tanks will be replaced at 1660 Madison with an air-to-water heat pump that uses CO2 as the refrigerant. Not only does this electrify the system, it also uses a refrigerant with a low global warming potential (GWP) in addition to reaching very high efficiencies. Full DHW electrification is an aggressive, forward-thinking step in eliminating natural gas usage from multifamily buildings. DHW is the buildings’ largest gas use today. The simple swap of replacing gas-fired water heaters with electric resistance type heaters would put a significant strain on the building’s electrical infrastructure and the utility’s infrastructure. Using heat pump

Case Study 5 The Heritage, New York water heaters with CO2 refrigerant, the building will be able to produce hot water up to 300% more efficiently than with electric resistance. This helps to bring the production cost of hot water closer to that of natural gas. The new refrigerant also allows the ability to produce domestic hot water even when the outdoor temperature goes down to -5ºF. The use of a natural refrigerant with a low global warming potential allows the buildings to stay ahead of mandates as other refrigerants are phased out or banned. This will be the first retrofit application of this technology in the L+M portfolio, and successful implementation of this measure will act as a model for other L+M properties.

The team also investigated phase-change materials (PCM) for DHW storage as a method to reduce physical plant size. A preliminary design was prepared for the DHW plant, which resulted in a 90% reduction in the space needed for storage, but interaction with the AWHP plant required additional mechanical components to function. The cost was too high to justify the benefit, but PCM will be considered for a path forward with the Fifth Avenue tower upgrades in the future.

Cooking Electrification

Cooking accounts for a small amount of natural gas usage overall but is one of the end-uses of the fuel. The cost of immediate implementation is prohibitive. Beyond equipment costs, this measure will require upgraded panels in each apartment and re-wiring of the entire building for electrical service. L+M will monitor this opportunity when other mobilization efforts in units can support this upgrade.

Upgrades to Control System

A centralized control system for each PTHP at 1660 Madison will allow for operator controlling over seasonal set point limits as well as thermostat scheduling for the whole building and the individual units. Cloud-based data storage will be used to monitor the performance of the systems in real time and track building energy performance. The 1295 and 1309 Fifth Avenue towers already host a cloudbased, open-source, central control system that monitors and manages the electric resistance baseboard heaters.

Ventilation System Overhaul

The ventilation system at 1660 Madison will undergo a major overhaul starting with cleaning of ducts, sealing ventilation shafts, and replacing fans with efficient energy recovery units where feasible or with ECM direct-drive rooftop fans. An energy recovery ventilator (ERV) will be installed that will recapture waste heat from the existing ventilation systems to preheat corridor supply air.

Submetering

L+M will install submeters for electrical and plug load usage in all apartments at 1660 Madison. Monitoring of data gathered can ensure that residents are not charged for heating usage, which is provided by the ownership. Deduct meters are also installed on the baseboard heaters at the Fifth Avenue towers to allow for subtraction of heating usage from each unit’s load.

Tenant Engagement Plan

L+M will institute a comprehensive tenant engagement and education plan. This plan will empower residents and inform them about the use and purpose of the buildings’ updated features and explain the reasoning behind these improvements to meet carbon and resilience goals. L+M will conduct sessions for residents prior to and following upgrades to explain the approaches and answer questions.

Key Takeaways

Packaging these measures into one upgrade plan is the most effective path forward, accounting for the interactivity of measures and minimizing resident disruption. The combination of these measures offers a holistic approach for deep carbon reductions, rather than reliance on incremental improvements over time.

- Overcladding the buildings reduces loads even before installing higher-efficiency equipment. Utilization of prefabricated panels at 1660 Madison is a unique approach to construction challenges raised by punching sleeves for PTHP equipment; this approach will minimize resident disruption.
- Installing high-performance windows is a key component of the holistic improvement to the building’s envelope and a crucial first step prior to upgrading the building’s HVAC systems.
- Installing PTHP equipment at the 1660 Madison building allows for replacement of the existing baseboard heat with high-efficiency cold climate heat pump equipment. This equipment can be better managed and monitored by central controls year-round.
- PTHPs are easy to replace with newer models with higher efficiencies; efficiency improvements will be phased in during equipment replacement on a rolling basis.
- PTHPs have no field-installed refrigerant piping, minimizing the potential for leakage and the attendant global warming impact.
- The addition of cooling to each room provides residents an important amenity and provides protection for resident health during extreme heat events.
- Cold-climate PTHPs integrated into a new facade offer a viable option for leveraging needed facade work. This inflection point provides the opportunity to replace envelope and mechanical systems simultaneously, incorporating the necessary electrical service and condensate risers into the construction. It also invests in increasing electrical capacity in the building for other future efforts.
- Using heat pump water heaters with CO2 refrigerant eliminates the buildings’ largest natural gas use. The building will be able to produce hot water up to 300% more efficiently than simply using electric resistance DHW heaters.
- Installation of electric dryers in common area laundry rooms is another step toward eliminating on-site fossil fuel usage.
- When submetering in an electrically heated building, it is particularly important to address the split between heating and plug loads.

The combination of apartment-level submeters with deduct meters at the heaters, and eventually the PTHPs, allows for residents to receive owner-provided electric heat while still being responsible for their cooling and plug load usage.

Bloedel Conservatory, Canada

This case study is provided courtesy of FirstLight Energy Solutions. The Conservatory, located in Vancouver’s Queen Elizabeth Park, is a biodiverse conservatory home to more than 500 exotic plants and over 100 exotic birds. The domed structure was built in 1969. A phased approach to building upgrades has reduced GHG emissions by 87% compared to 2011. The latest central plant retrofit has reduced gas consumption by a further 4200 GJ—a 75% reduction compared to pre-retrofit.

**[Figure: Bloedel Conservatory]**

Type: diagram

Description: The Bloedel Conservatory is a geodesic dome located in Queen Elizabeth Park, Vancouver, British Columbia, Canada. It houses over 500 species of plants and flowers from around the world, including tropical plants, trees, and flowers.

Key Elements:

*   Geodesic Dome -> The dome is made up of interlocking triangles that provide structural support and allow for maximum interior space.
*   Tropical Plants -> The conservatory features a variety of tropical plants, including palm trees, ferns, and orchids.
*   Water Feature -> A small pond or fountain is located in the center of the conservatory, adding to the tranquil atmosphere.
*   Walkways -> Visitors can walk along the walkways and explore the different plant species on display.
*   Lighting -> The conservatory is lit up at night, creating a beautiful and peaceful ambiance.

The Bloedel Conservatory is a popular tourist destination and a great place to learn about different plant species and their habitats. It is also a popular spot for photography and relaxation.

Figure CS6.1 Exterior view of Bloedel Conservatory.

### Table: Data Table

| Project Name | Bloedel Conservatory | Year Built |  | 1969 |
|---|---|---|---|---|
| Location | Vancouver, British Columbia (Canada) | Building Size |  | 19,600 ft2 |
| Project Phase | Implemented, 2021 | Year Last Systems Upgrade |  | N/A |
| Key EEMs/ERMs |  |  |  |  |
| • Roof replacement and sealing (2014) • LED lighting retrofit (2018) • Central ASHP plant (2021) • BAS upgrade with ASHRAE Guideline 36 sequences and demand management (ASHRAE 2021a) |  |  |  |  |
| Central Plant |  |  |  |  |
| Existing |  |  | Retrofit |  |
| Heating: two 3,500 MBH condensing boilers (14 years old) Cooling: one 210-ton water-cooled chiller with open cooling tower (18 years old, R22 refrigerant) |  |  | 200-ton AWHP plant Control system upgrades |  |

Existing Systems

The Conservatory’s cooling plant had exceeded its expected service life and needed replacement. The original cooling plant consisted of one 210-ton water-cooled chiller and an open cooling tower. The original heating plant consisted of two gas-fired condensing boilers. Hot water and chilled water served nine existing air-handling units to ventilate and condition the conservatory.

Case Study 6 Bloedel Conservatory, Canada

Load-Reduction Measures

Efficiency upgrades, including replacement of the roof dome in 2014 and the transition to energy-efficient LEDs for lighting, played a pivotal role in reducing energy costs at the Conservatory and effectively reducing facility cooling loads.

Central Plant Retrofit

A 210-ton air-to-water heat pump (AWHP) was selected to replace the aging chiller plant. The existing chilled-water loop was converted to a low-temperature heating and chilled-water switchover loop. This adaption allows the use of a 2-pipe AWHP to meet the heating and cooling needs of the facility while preserving the existing high-temperature hot-water loop to provide supplemental heat for the AHUs as needed. The sizing of the AWHP was aligned with the facility’s current cooling demands and can provide up to 1,500 MBH of heating under design ambient conditions, effectively meeting 85% to 90% of the annual heating load. However, due to constraints in the existing electrical service, an active demand strategy was implemented, limiting the AWHP’s maximum output based on facility demand. A planned future service upgrade will allow the AWHP to operate at its full capacity. Additionally, the retrofit included replacement of AHU control valves, along with enhancements to control sequences and graphics, incorporating control methodologies in line with ASHRAE Guideline 36 (ASHRAE 2021a). Beyond energy and gas savings, this retrofit effectively reduced the facility’s water consumption by eliminating evaporative cooling.

Pre- and Post-Retrofit Performance

Comparison of pre- and post-retrofit gas and electricity consumption is indicated in the graphs in Figures CS6.2 and CS6.3. Gas consumption has been reduced by 75%. The small amount of gas use in the summer months is attributed to the domestic hot-water system. The boilers supplement the AWHP during defrost and peak heating conditions. Comparison of the electrical increase to gas savings indicate a seasonal AWHP COP in the range of 2.7.

Future Proofing and Adaptation

Anticipating the impact of climate change, the heat pump system was designed to accommodate higher cooling loads in the future. Predictions indicate a 30% increase in cooling load by 2050 due to rising temperatures and humidity, prompting the design to include provisions for future additions of thermal energy storage using phase-change materials to boost capacity.

**[Figure: Natural gas consumption]**

Type: chart

Description: This chart compares the baseline and post-retrofit actual natural gas consumption in gigajoules (GJ) from October 1, 2021, to October 1, 2023. The key insight is that the post-retrofit actual consumption is significantly lower than the baseline, indicating a reduction in natural gas usage.

Data Representation:

*   Baseline: 1,400 GJ
*   Post-Retrofit Actual: 600 GJ
*   Metric: Natural gas consumption
*   Chart Type: Bar chart
*   Units: Gigajoules (GJ)

Chart Generation Hint:

*   X-axis: Date (October 1, 2021, to October 1, 2023)
*   Y-axis: Natural gas consumption (GJ)

Structured Data (Machine Readable):

```json
{
  "chart_type": "bar",
  "metric": "natural_gas_consumption",
  "units": "gigajoules",
  "data": {
    "baseline": 1400,
    "post_retrofit_actual": 600
  }}
}

**[Figure: Natural Gas Consumption (GJ)]**

Type: chart

Description: This chart compares the natural gas consumption in gigajoules (GJ) before and after retrofitting, highlighting the reduction in consumption over time.

Data Representation:

* Baseline: 1,400 GJ
* Post-retrofit Actual: 600 GJ
* Post-Retrofit Savings: 800 GJ

Metric: Natural Gas Consumption (GJ)

Chart Type: Bar Chart

Units: Gigajoules (GJ)

Chart Generation Hint:

* X-axis: Time (2021-10-01 to 2023-10-01)
* Y-axis: Natural Gas Consumption (GJ)

Structured Data (Machine Readable):

{
  "chart_type": "bar_chart",
  "metric": "natural_gas_consumption",
  "units": "gigajoules",
  "data": {
    "baseline": 1400,
    "post_retrofit_actual": 600,
    "post_retrofit_savings": 800
  }}
}

**[Figure: Electricity Consumption (kWh)]**

Type: chart

Description: This chart compares the electricity consumption in kWh before and after a retrofit, highlighting the increase and savings. The key insight is that the retrofit has led to a significant reduction in electricity consumption.

Data Representation:

* Baseline: 100,000 kWh
* Post-Retrofit Increase: 50,000 kWh
* Post-Retrofit Savings: 150,000 kWh
* Metric: Electricity Consumption
* Chart Type: Bar
* Units: kWh

Chart Generation Hint:

* X-axis: Time (2021-09-01 to 2023-10-01)
* Y-axis: Electricity Consumption (kWh)

Structured Data (Machine Readable):

{
  "chart_type": "bar",
  "metric": "electricity_consumption",
  "units": "kWh",
  "data": {
    "baseline": 100000,
    "post_retrofit_increase": 50000,
    "post_retrofit_savings": 150000
  }}
}

StopWaste Office, California

This case study is provided courtesy of Taylor Engineers. StopWaste helps Alameda County waste less, recycle properly, and use resources such as energy and water efficiently. They are a public agency governed by the Alameda County Waste Management Authority, the Alameda County Source Reduction and Recycling Board, and the Energy Council. StopWaste’s HVAC system was nearing the end of its effective useful life, and stakeholders were interested in replacing the equipment with an all-electric solution.

**[Figure: 1537 Stopyate]**

Type: diagram

Description: The image depicts a building with a blue facade and white-framed windows, featuring a central entrance with a glass door and a sign above it that reads "Stopyate" and "1537". The building's design is characterized by its symmetrical layout, with a row of windows on either side of the entrance.

Key Elements:

*   Entrance: The central entrance is flanked by two columns and features a glass door with a sign above it.
*   Windows: The building has a row of windows on either side of the entrance, each with a white frame and a decorative pattern above it.
*   Sign: The sign above the entrance reads "Stopyate" and "1537", indicating the building's name and address.
*   Columns: The columns on either side of the entrance are tall and slender, adding to the building's symmetrical design.

Overall, the image presents a clear and detailed view of the building's facade, highlighting its architectural features and design elements.

Figure CS7.1 Exterior view of  StopWaste office.

### Table: Data Table

| Project Name | StopWaste | Year Built |  | Major Renovation in 2006 |
|---|---|---|---|---|
| Location | Oakland, California | Building Size |  | 13,845 ft2 |
| Project Phase | Bidding, January 2024 | Year Last Systems Upgrade |  | 2006 |
| Key EEMs/ERMs |  |  |  |  |
| • Conversion to all-electric HVAC |  |  |  |  |
| Existing |  |  | Retrofit |  |
| 18 years old 3 VAV packaged rooftop units with gas heat 1 cooling-only rooftop unit Gas hot water heater |  |  | 3 VAV packaged heat pump rooftop units 1 cooling-only rooftop unit Heat pump water heater |  |

Existing Systems

The existing heating/cooling rooftop units at StopWaste used R-22 in their refrigeration circuits and an 81% efficient gas furnace for heating. The cooling-only rooftop unit used R-410a. All units included an airside economizer, and three out of four units were variable speed VAV packaged units with digital scroll compressors. Two of the three VAV packaged units served VAV diffusers (Thermafusers). The existing domestic hot-water heater was a condensing gas water heater with integrated storage.

Case Study 7 StopWaste Office, California

HVAC Retrofit

Packaged heat pump VAV rooftop units were selected to replace the existing heating/cooling rooftop units, and the cooling-only unit was replaced with a similar cooling-only rooftop unit. The new units include variable-speed scroll compressors using R-410a. The units have a slightly larger footprint, requiring roof curb adapters, but the increased weights did not trigger structural upgrades. Given the lack of structural drawings, a load assessment had to be performed based on observed conditions and assumed rebar spacing. Existing electrical load data were pulled to establish the allowed maximum combined power draw of the new units. The electrical service did not require upsizing. Electric resistance heating sections were included only in the packaged units serving VAV diffusers in order to maintain neutral supply air temperature when the units are in defrost and prevent the VAV diffusers from switching modes (heating to cooling). Minimizing electric resistance heating allowed the total power requirements to fall under the requirements to keep the existing service size.

Domestic Hot Water

A storage-type heat pump water heater was selected to replace the condensing gas water heater. This replacement was carried as an add-alternate and has not yet been determined to be included in the project.

Montreal City Hall, Canada

This case study is provided courtesy of Martin Roy & Associés with adaptations from the presentation Preserving the Past, Building for the Future: The Montreal City Hall Zero FossilFuel Retrofit at the 2023 Decarbonization Conference for the Built Environment. Montreal City Hall is a historic building on a historic site that undertook a decarbonization retrofit to reduce GHG emissions. The building was inaugurated in 1878 but suffered a devastating fire in 1922 and was rebuilt in 1924. The top two floors of the building were later completely renovated in the 1980s and, therefore, have no historic status. The remainder of the building is historic, and very limited changes are allowed to be made to the building. The retrofit was undertaken by Martin Roy & Associés (MRA) with the following goals:

- LEED O+M Certification •No combustion for regular operations
- Complete replacement of all mechanical systems (working within historic building context)

**[Figure: Montreal City Hall]**

Type: diagram

Description: The image depicts the Montreal City Hall, a historic building in Montreal, Quebec, Canada. The building is a prominent example of Second Empire architecture and features a clock tower and a grand staircase.

Key Elements:

* Clock Tower -> The clock tower is a distinctive feature of the building and is visible from a distance.
* Grand Staircase -> The grand staircase is a prominent feature of the building's interior and is often used for ceremonial purposes.
* Second Empire Architecture -> The building's design is characterized by its use of Second Empire architectural style, which was popular in the 19th century.

This figure provides a visual representation of the Montreal City Hall, highlighting its architectural features and historical significance.

Figure CS8.1 Exterior view of Montreal City Hall.

### Table: Data Table

| Size | 220,000 ft2 | Year Built | 1924 | Budget |
|---|---|---|---|---|
| Location | 275 Notre-Dame St. East | City | Montreal, Quebec, Canada | $160 million |
|  |  | Implementation Phase | 2020–2024 |  |
| Existing Building Properties |  |  |  |  |
| • Historic site: very limited changes allowed to the building • 5 floors, 2 basements, a mechanical penthouse • Top two floors were renovated in the • 1980s, completely torn out—no historic status • Heated with purchased steam (produced with natural gas) • Hot-water radiators 180°F (80°C) • No centralized air conditioning, window AC in many spaces (not appropriate for the historic nature of the building) • Not all spaces are ventilated • No insulation • Old, wooden, single-pane windows |  |  |  |  |
| Key Retrofit Measures |  |  |  |  |
| • Radiant heated ceilings combined with decentralized fan coils: many spaces have historic floors and walls (marble floors and wood paneling on walls) that limit equipment solutions • DOAS: Outdoor air is distributed independently from heating and cooling, minimizing ducting in an extremely complex building and minimizing fan energy for the many hours when neither heating nor cooling is required • ASHP with electric boiler backup: ASHP in an indoor space supplied with exhaust air to improve HP efficiency during very cold winter months |  |  |  |  |

Case Study 8 Montreal City Hall, Canada

Design Challenges

The project design approach considered a variety of options to meet the building’s needs. Decisions for determining the best combination of measures and technologies were driven by the following KPIs:

- GHG emissions reduction (no combustion)
- Respecting historic finishes and appearance
- Ease of maintenance
- LEED certification
- Occupant comfort

The historic value of the building’s interior was the main factor in many decisions during project design. Historic finishes within the building drove the team toward a solution with a decentralized system that minimized ductwork. MRA evaluated a number of decarbonization strategies and technologies for heating and cooling Montreal City Hall, and many were rejected for reasons either directly or indirectly related to the building’s historic status. Some examples of technologies that were not feasible included:

- Geothermal: The building grounds include a large front lawn area that MRA considered for installation of a ground-source loop for GSHP. Installation of a ground-source loop was not restricted, but any excavation within the historic district requires careful verification from archaeologists that no historic artifacts are disturbed. If during excavation anything of historic significance were found, it would have serious impacts on project timelines. As a result of these requirements, installation of a ground-source loop was determined not to be economically feasible and to provide too great a schedule risk to the project.
- Radiant Floors: MRA considered radiant floor loops as an efficient method for heating and cooling the building that would limit the amount of required ductwork. Many areas within the building have existing historic floor coverings (marble), and this significantly limited the ability to retrofit. One small space was deemed feasible for radiant floor loops, but the strategy was determined not to be a feasible solution.
- Windows: Because no insulation could be added due to preservation of historic finishes, the team focused on windows to help improve the building envelope. As part of the pursuit of LEED certification, the team considered replacing the existing windows. However, the windows were also considered a part of the historic finishes for the building and could not be replaced. As an alternative solution, MRA had windows repaired to improve weatherization and reduce air leakage. To meet the historic status requirements, this required using local artisans to carefully repair windows, including hand sanding and refinishing the window frames to maintain their historic appearance.
- Non-Energy Upgrades: There were many systems that needed updating, such as structural elements and seismic systems. Adding a freight elevator for transporting equipment required major structural modifications as well.

- Tenant Considerations: Because of the extent of this major renovation project, occupants were moved to another building for safety during asbestos abatement and major renovations.

Other design considerations were deemed not feasible because of additional factors in the process:

- ASHP Located on the Roof: Municipal regulations required that equipment not be visible from the street, and very strict noise regulations also presented a challenge. When combined with very limited space on the roof, it was not feasible to locate the large ASHP equipment on the roof.

- Heat Production using Existing Purchased Steam System: The team considered retaining the existing steam system as an option that worked within the historic building concept. However, this option was rejected because it did not comply with the goal to eliminate all combustion for regular operations.

HVAC Upgrade

Montreal City Hall was originally heated with purchased steam, produced with natural gas at a maximum 65% efficiency. The building used a steam-to-water heat exchanger to supply hot-water radiators with 180°F (80°C) hot water. The building had no centralized air conditioning, with window AC units in many spaces that were not appropriate for the historic nature of the building. In addition, not all spaces were ventilated. Another factor in the project design was that some systems were at the end of life, but the major issue was that many years of overlapping renovations within the building had rendered the existing systems very complex.

**[Figure: Heat Recovery System]**

Type: diagram

Description: The figure illustrates a heat recovery system, which is designed to capture and reuse waste heat from various sources. The system consists of several key components, including a dry cooler, an insulated mechanical room, a refrigerant-water heat exchanger (HX), a magnetic chiller, an electric boiler, a water-side heat pump (WSHP), a hydraulic separator, and a radiant loop.

Key Elements:

*   Dry Cooler -> used to cool the refrigerant
*   Insulated Mechanical Room -> houses the mechanical equipment
*   Refrigerant-Water HX -> transfers heat from the refrigerant to the water
*   Magnetic Chiller -> cools the water using magnetic refrigeration
*   Electric Boiler -> heats the water using electricity
*   WSHP -> provides heating and cooling to the building
*   Hydraulic Separator -> separates the water into two streams
*   Radiant Loop -> distributes the heated or cooled water to the building

The system operates by circulating a refrigerant through the dry cooler, where it is cooled, and then through the refrigerant-water HX, where it transfers its heat to the water. The cooled water is then pumped through the magnetic chiller, where it is further cooled, and then through the electric boiler, where it is heated. The heated water is then distributed to the building through the radiant loop. The system also includes a hydraulic separator, which separates the water into two streams, one for heating and one for cooling.

Overall, the heat recovery system is designed to efficiently capture and reuse waste heat, reducing the energy consumption of the building and minimizing its environmental impact.

Figure CS8.2 HVAC system schematic.

Case Study 8 Montreal City Hall, Canada

Working to meet the KPIs and within the historic context of the building, MRA developed an approach for an HVAC system that includes radiant ceilings, a DOAS, and ASHPs located in an interior mechanical room. Figure CS8.2 provides a schematic of the HVAC system design.

- Radiant Ceilings Combined with Decentralized Fan Coils: Many spaces have historic floors and walls (marble floors and wood paneling on walls). Radiant ceilings improve comfort and produce low noise for a majority of heating hours. Peaks loads are taken on by fan coils, which also supply cooling capacity. Using hydronic heating and cooling increases efficiency and reduces the size of ducts, which was an essential consideration in a building that does not have space for big ducts.
- DOAS: The outdoor air is distributed completely independently from heating and cooling, minimizing ducting in an extremely complex building. Minimizing fan energy, fan coils do not need to work for the many hours a year when the climate demands neither heating nor cooling. •Electrified Heating: The design includes ASHPs with electric boiler backup. Due to roof space limitations and municipal restrictions, the ASHP is located in an indoor mechanical room that is supplied with exhaust air to improve HP efficiency. Having the units indoors also means that when one unit is in heating mode and another in cooling mode, air can be recirculated within the space to improve efficiency. Locating the ASHPs indoors also proved to be a very good solution for Montreal’s cold climate. Due to locating the ASHPs inside the mechanical room rather than outdoors on the roof, the operating temperatures for the units are significantly warmer and expanded the equipment options beyond those designed for cold climate operation.

**[Figure: HVAC System Components]**

Type: diagram

Description: The figure depicts a section of an HVAC (Heating, Ventilation, and Air Conditioning) system, showcasing its key components. It includes two large air conditioning units positioned side by side, with a ductwork system above them. The ducts are connected to vents on the wall, indicating the system's role in circulating and conditioning air within a building.

Key Elements:

- **Air Conditioning Units**: These are the primary components responsible for cooling the air. They are equipped with filters to clean the air and fans to circulate it throughout the building.
- **Ductwork System**: This network of ducts distributes conditioned air from the air conditioning units to various parts of the building. It ensures that the air reaches all areas efficiently.
- **Vents**: Located on the walls, these vents allow the conditioned air to enter the rooms. They can be adjusted to control airflow and temperature in different areas of the building.

This diagram provides a clear overview of how an HVAC system operates, highlighting its critical components and their functions in maintaining a comfortable indoor environment.

Figure CS8.3 Indoor ASHPs.

Key Takeaways

This final solution achieved the KPIs for the project and ultimately led to a significant reduction in GHG emissions by removing fossil fuel combustion and electrifying HVAC systems. The project’s extremely low GHG emissions are driven by the very low grid emission factor in Quebec, where the main source of electricity is hydropower. This project illustrates how buildings with electrified HVAC systems can achieve extremely low GHG emissions as the electric grid transitions to clean energy production.

- GHG Reduction: removed of all combustion from project operations

**[Figure: GHG emissions comparison for project alternatives]**

Type: chart

Description: This chart compares the GHG emissions of different project alternatives, specifically focusing on the Quebec GHG Emission Factors. The key insight is that the electricity option has significantly lower emissions compared to natural gas.

Data Representation:

- Electricity: 0.00205 kg CO2/yr/kWh
- Natural Gas: 5,578,963 kg CO2/yr/kWh
- Metric: kg CO2/yr/kWh
- Chart Type: Bar
- Units: kg CO2/yr/kWh

Chart Generation Hint:

- X-axis: Project Alternatives
- Y-axis: GHG Emissions (kg CO2/yr/kWh)

Structured Data (Machine Readable):

{
  "chart_type": "bar",
  "metric": "kg CO2/yr/kWh",
  "units": "kg CO2/yr/kWh",
  "data": {
    "Electricity": 0.00205,
    "Natural Gas": 5578963
  }}
}

**[Figure: Tons of CO2/yr]**

Type: chart

Description: The chart compares the tons of CO2 per year for existing buildings, initial projects, and final design. The key insight is that the final design has significantly reduced greenhouse gas emissions compared to the existing building and initial project.

Data Representation:

* Existing Building: 1,000 tons
* Initial Project: 500 tons
* Final Design: 0 tons
* Metric: Tons of CO2 per year
* Chart Type: Bar chart
* Units: Tons

Chart Generation Hint:

* X-axis: Building type (existing, initial project, final design)
* Y-axis: Tons of CO2 per year

Structured Data (Machine Readable):

{
  "chart_type": "bar",
  "metric": "tons of CO2 per year",
  "units": "tons",
  "data": {
    "Existing Building": 1000,
    "Initial Project": 500,
    "Final Design": 0
  }}
}

### Table: Data Table

| Quebec GHG Emission Factors | Electricity | 0.00205 | kg CO /yr/kWh 2 |
|---|---|---|---|
|  | Natural Gas | 5,578,963 | kg CO /yr/kWh 2 |

# 47 Seventy Apartments, Utah

This case study is provided courtesy of ICAST. Property Information

- Garden style apartment complex with 20 buildings •416 units •Salt Lake City metro area •Naturally occurring affordable housing complex that caters to households earning less than 80% of the area median income

**[Figure: Apartment Complex]**

Type: diagram

Description: The image depicts a two-story apartment complex with a parking lot in front. The building features a beige exterior with white trim and a black railing on the second-floor balcony. A black car is parked in the lot, and a tree stands in front of the building.

Key Elements:

*   Apartment building -> The main structure of the complex, featuring a beige exterior with white trim.
*   Balcony -> A second-floor balcony with a black railing, providing outdoor space for residents.
*   Parking lot -> A designated area for parking vehicles, located in front of the building.
*   Tree -> A tree standing in front of the building, adding greenery to the scene.

This diagram provides a visual representation of an apartment complex, highlighting its key features and layout.

Figure CS9.1 Exterior view of 47 Seventy apartments.

### Table: Data Table

| Project Name | 47 Seventy Apartments | Year Built |  | 1975 |
|---|---|---|---|---|
| Location | 4770 Simmental Dr. Taylorsville, UT | Building Size |  | 416 units in 20 buildings |
| Project Phase | Implemented, 2022 | Year Last Systems Upgrade |  | N/A |
| Key EEMs/ERMs |  |  |  |  |
| • LED lighting upgrades • Replace central air split AC with split ASHPs • Gas furnaces for backup heating • Smart thermostats |  |  |  |  |
| HVAC Equipment |  |  |  |  |
| Existing |  |  | Retrofit |  |
| 25 years old Heating: gas-fired, forced air furnace Cooling: ducted split system AC |  |  | Two-ton ASHPs 45,000 Btu gas-fired furnace for supplemental heating |  |

Scope of Work

The project involved upgrading HVAC systems and lighting systems and installing smart thermostats. The 47 Seventy apartments are owned by Marble Partners, LLC, and the property is managed by Apartment Management Consultants, LLC. The owner’s initial goal was to replace their old ducted split-system AC units because they used R22 refrigerants, which have high GWP. However, in collab-

Case Study 9 47 Seventy Apartments, Utah oration with ICAST, they expanded the scope of work to include replacing their gas-fired, forced-air furnaces (which were ~25 years old). The project considered two options for installation:

- Efficient AC + Furnace: This package included more efficient 16 SEER AC units for cooling paired with 95% AFUE 60,000 Btu gas-fired furnaces for heating.
- ASHP + Furnace: This package included two-ton single-zone ASHPs paired with 80% AFUE 45,000 Btu gas-fired furnaces for supplemental heating to the ASHPs.

ICAST installed the hybrid electrification solution, replacing the existing HVAC systems in over 120 units with two-ton single-zone cold climate ASHPs and new gas furnaces for supplemental heating.

Challenges and Barriers

The upfront costs of installing the ASHP + furnace option exceeded those of more efficient AC units and gas furnace combinations, and ASHPs are still an unfamiliar technology for most multifamily affordable housing property owners. ICAST demonstrated to the owner that ASHPs are a high-value investment because, in addition to their decarbonization benefits, they can increase residents’ health, comfort, and safety (they do not give off carbon monoxide). Further, the utility bill savings from the project enable the lower-income residents to redirect their money toward other necessities, such as groceries and healthcare.

Project Costs, Savings, and Impacts

The total project cost was $1.15M. To offset costs, ICAST leveraged $620,698 in rebates from the Rocky Mountain Power Multifamily Energy Efficiency Program. The remaining cost for the project was covered by the property owner, Marble Partners, LLC. The project achieved annual utility bill savings of approximately $156,566 and will save approximately $4M over the lifetime of the upgrades. Beyond providing annual electricity savings of approximately 1,891,281 kWh/yr, the hybrid ASHP and furnace solution will reduce the GHG emissions for the 47 Seventy Apartments by approximately 3M lbs. annually. The project is expected to reduce GHG emissions by approximately 57M lbs. over the lifetime of the upgrades. Marble Partners, LLC, will realize an increase in the value of their property based on the project upgrades, and residents receive more comfortable, healthier apartments.

McMullen County Courthouse, Texas

This case study is part of the Preliminary Energy Assessments (PEA) program through the Texas State Energy Conservation Office (SECO) and is provided courtesy of NORESCO. A preliminary energy audit (PEA) of the McMullen County Courthouse in Tilden, TX, was conducted for the Texas State Energy Conservation Office (SECO) in August 2023. Originally built in 1930, the McMullen County Courthouse has undergone many retrofits over the years and in its current state is a fully electrified building with a gross floor area of about 9000 ft2. As a result of previous lighting and envelope retrofits, the aging heat pump units are oversized and provide an opportunity to rightsize the HVAC system for the new building cooling and heating loads.

**[Figure: Figure on page 206]**

Type: diagram

Description: The image depicts a two-story building with a tan brick exterior and white trim, featuring a central entrance flanked by two trees on either side. The building's facade is adorned with multiple windows, and a small cupola crowns the roof.

Key Elements:

- **Building**: The central structure of the image, characterized by its tan brick exterior and white trim.
- **Entrance**: A prominent feature at the center of the building, marked by a set of steps leading up to a doorway.
- **Trees**: Two trees, one on each side of the entrance, adding a touch of greenery to the scene.
- **Cupola**: A small structure atop the roof, adding architectural interest to the building's design.

This classification template is designed to provide a structured description of the visual elements within the image, focusing on the key components that define its composition and aesthetic.

Figure CS10.1 Exterior view of McMullen County Courthouse.

### Table: Data Table

| Project Name | McMullen County Courthouse | Year Built |  | 1930 |
|---|---|---|---|---|
| Location | Tilden, TX | Building Size |  | ~9000 ft2 |
| Project Phase | Assessment | Year Last Systems Upgrade |  | N/A |
| Key EEMs/ERMs |  |  |  |  |
| • Insulation upgrades • Occupancy-based lighting controls • Replacement of aging heat pumps with rightsized VRF + DOAS unit; demand-controlled ventila- tion • Parking deck rooftop PV |  |  |  |  |
| Existing |  |  | Recommended Retrofit |  |
| • Poor and deformed insulation for roof and floor • Double-pane low-e glazing windows • 8 heat pump units approximately 9 to 13 years old reaching end of life • LED lighting fixtures under manual switch control |  |  | • Addition of roof and attic floor insulation • VRF + DOAS unit • PV system on the installed parking deck • Retrofit existing lighting controls with occu- pancy sensors |  |

Case Study 10 McMullen County Courthouse, Texas

Upgrades to Building Envelope

Although the building has undergone a series of retrofits over the years, it does not have any roof insulation, and the floor insulation in the attic is severely degraded. Further, the door between the attic and the courtroom is left open, resulting in humidity and condensation problems that are addressed by intentional overcooling on hearing days. Adding roof insulation and augmenting the attic floor insulation using spray foam at the underside of the roof sheathing will improve thermal comfort, mitigate condensation issues, and contribute to reducing cooling and heating loads.

Upgrade to Lighting Controls

Although all lighting fixtures are LED based, existing lighting control is through the means of manual switches. Areas of the building that see intermittent traffic, such as corridors and offices, are ideal locations for the installation of passive infrared (PIR) occupancy sensors. The addition of occupancy sensors can reduce lighting operation in courtroom and jury room by 25%, reducing cooling loads.

Upgrades to HVAC System

The courthouse is currently served by eight heat pump units, which are approximately 9 to 13 years old and nearing the end of effective useful life. Due to the age of the building, ceiling height is low, and with the existing ductwork the height is lowered even more. A heat recovery VRF system decoupled with a DOAS for ventilation purposes is recommended to replace the aging heat pumps. The VRF system will not require ductwork except the minimum outdoor air supply by the DOAS unit. Also, removal of the indoor units will provide extra storage space for the building.

A calibrated building energy model indicated that the existing heat pump units are vastly oversized due to the LED lighting and low-e window retrofits performed in recent years (installed total tonnage is 30, while calculated tonnage is 21.3). This suggests that the heat pumps are operating at lower efficiencies at part load conditions. The proposed VRF system is sized based on this reduced load.

Implementation of Solar PV System

The McMullen County Courthouse recently installed a new parking deck with a metal roof that has no obstructions and will provide the idea location for the installation of a new solar PV energy generation panel. With an area of 6404 ft2 and a tilt of 28%, an 88.3kW system can be installed to provide clean energy production on-site and integrated with the grid.

Key Takeaways

Regular retrofits helped keep the 1930 McMullen County Courthouse fairly up to date with the current standards. The audit in August 2023 indicated that proper lighting and thermostat controls can help maximize energy savings from existing systems. Furthermore, implementation of a good energy management policy as well as good and regular maintenance and operation of existing systems can help the building be more sustainable in the long run. This study also highlights how a well-calibrated building energy model, though not very detailed, can still provide great insights into the appropriate sizes of energy systems required for optimum operation.

Ken Soble Tower, Canada

This example is provided courtesy of Rocky Mountain Institute. This high-rise affordable multifamily housing retrofit in Hamilton (greater Toronto area), Canada, was a comprehensive passive house retrofit using a unique mineral wool EIFS approach for envelope improvements. The project revitalized a deteriorating 1967 multifamily building into vibrant and healthy affordable housing for seniors (206.1 kBtu/ft2 before retrofit, 49.1 kBtu/ft2 [modeled] post retrofit).

### Table: Data Table

| Project Name | Ken Soble Tower | Year Built |  | 1967 |
|---|---|---|---|---|
| Location | Hamilton (Toronto), Canada | Building Size |  | 80,000 ft2 (18 stories, 164 units) |
| Project Phase | Constructed 2020 | Year Last Systems Upgrade |  | N/A |
| Key EEMs/ERMs |  |  |  |  |
| • Exterior mineral wool EIFS with liquid applied air barrier (R-38, <0.3ACH50) • Triple-pane windows • VRF system with VAV boxes • DOAS with ERVs for ventilation • Condensing boiler for DHW |  |  |  |  |
| HVAC |  |  |  |  |
| Existing |  |  | Retrofit |  |
| • Hydronic baseboard heat served by central boiler plant • Pressurized corridors, exhaust-only ventila- tion • No cooling • Central recirc gas boiler DHW |  |  | • VRF heating/cooling with VAV boxes • DOAS ducted to each unit with central ERVs and tempered outdoor air • Ceiling fans, shades, low SHGC windows • Condensing gas boiler plant for DHW |  |

Existing Systems

- Individual apartment heating with hydronic baseboards served by a central boiler plant
- Central OA to pressurize corridors and intermittent exhaust in apartments
- No cooling
- Central DHW boiler plant with recirc
- Poorly performing envelope (mold, asbestos, etc.)

Load-Reduction Retrofits

- Fluid-applied air barrier against existing facade
- Field-applied mineral wool EIFS adding R-43 (R-38 effective)
- Triple-pane windows
- Airtightness improved from 5.4 ACH50 to less than 0.3 ACH50
- EnerPHit certified

Case Study 11 Ken Soble Tower, Canada

**[Figure: 500 MACNAB BASE CONDITIONS]**

Type: diagram

Description: The diagram illustrates the base conditions of a building, highlighting various components and their corresponding numbers. It provides a visual representation of the building's structure and features.

Key Elements:

*   Interiors: 
    *   Deteriorated fixture, millworks, and appliances
    *   Deteriorated flooring
    *   Holes in fire separations between units
    *   Asbestos containing materials
    *   Mould remediation required in all interior walls
    *   Pervasive pests
*   Systems:
    *   Deteriorated central ductwork
    *   Deteriorated plumbing
    *   Inadequate ventilation
    *   Deteriorated electrical system
*   Envelope:
    *   Deteriorated balcony slab edge
    *   Deteriorated windows
    *   Masonry repairs required
    *   Deteriorated roof

Figure CS11.1 Schematic view of existing tower conditions. (Image credit: ERA Architects)

**[Figure: 500 MACNAB PASSIVE HOUSE RENEWAL]**

Type: diagram

Description: The diagram illustrates the components of a passive house renewal project, including life safety, comfort, envelope, systems, units, building amenity, and state of repair.

Key Elements:

*   Life Safety:
    *   Sprinklers -> Fire suppression system
    *   New fire alarm system -> Advanced fire detection and alert system
*   Comfort:
    *   Ceiling fans -> Air circulation for temperature regulation
    *   Central low energy cooling -> Energy-efficient cooling system
*   Envelope:
    *   Triple glazed windows -> Insulated windows for energy efficiency
    *   Thermally continuous and airtight envelope with exterior and Interior Insulation -> Energy-efficient building envelope
*   Systems:
    *   Direct ducting for fresh air supply in units with Heat recovery -> Ventilation system with heat recovery
    *   New plumping system -> Upgraded plumbing infrastructure
    *   Modernized electrical system -> Updated electrical infrastructure
*   Units:
    *   New kitchen -> Renovated kitchen space
    *   New flooring -> Upgraded flooring material
    *   Repair of walls for continuous fire separations between units -> Fire-resistant wall repairs
*   Building Amenity:
    *   New community space at base and penthouse -> Additional community areas
    *   New laundry facility -> Upgraded laundry facilities
    *   Modernized landscape -> Updated outdoor landscaping
*   State of Repair:
    *   All state of repair issues addressed to achieve 30 year plus asset renewal -> Comprehensive maintenance and repair plan

Figure CS11.2 Schematic diagram of retrofit measures. (Image credit: ERA Architects)

HVAC Retrofits

- Central VRF heat pump provides heating and cooling via VAV boxes in units
- DOAS with tempered air and central ERVs: one ground floor, one roof, and one in annex building
- Ventilation and exhaust ducts to each unit

Domestic Hot Water

- Condensing gas boilers
- Not fully decarbonized (old utility transformer limited peak loads; replacement did not align with project timeline)

East Palo Alto Government Center, California

This case study is provided courtesy of Taylor Engineers. San Mateo County implemented measures to reduce building greenhouse gas emissions by upgrading the East Palo Alto Government Center (EPA Gov) with an energy-efficient, allelectric heat pump heating system, among other HVAC upgrades. This HVAC retrofit was carefully crafted to align with the county’s sustainability objectives while maintaining a tight project budget.

**[Figure: Solar Panels on a Parking Lot]**

Type: diagram

Description: The image shows a parking lot with solar panels installed on top of the parking spaces. The solar panels are arranged in rows and columns, covering most of the parking lot.

Key Elements:

* Solar panels -> generating electricity from sunlight
* Parking spaces -> providing parking for vehicles
* Trees -> surrounding the parking lot, providing shade and aesthetic appeal

This diagram illustrates the use of solar panels to generate electricity in a parking lot, highlighting the potential for renewable energy sources in urban areas.

Figure CS12.1 Exterior view of East Palo Alto Government Center.

### Table: Data Table

| Project Name | East Palo Alto Government Center | Year Built |  | 1973 |
|---|---|---|---|---|
| Location | East Palo Alto, CA | Building Size |  | 50,000 ft2 |
| Project Phase | Designed in 2021 | Year Last Systems Upgrade |  | 1995 |
| Key EEMs/ERMs |  |  |  |  |
| • Central air-to-water heat recovery heat pump plant • BAS upgrade (pneumatic to DDC) with ASHRAE Guideline 36 sequences of operation • Repairs to penthouse built-up air handling unit • LED lighting with occupancy-based lighting controls |  |  |  |  |
| Central Plant |  |  |  |  |
| Existing |  |  | Retrofit |  |
| • Over 30 years old • 1,800 kBtu/h natural gas boiler • 180-ton water-cooled CHW plant • 80-gallon natural gas domestic water heater |  |  | • 60-ton two-pipe air-to-water heat pump • 60-ton four-pipe air-to-water heat recovery heat pump • 80-gallon hybrid heat pump domestic water heater |  |

Existing Systems

EPA Gov’s HVAC systems were over 30 years old and had exceeded their expected service life. The HVAC system relied on pneumatic controls, offering limited strategies for control and no capacity to track system data.

Case Study 12 East Palo Alto Government Center, California

Space conditioning was accomplished via a central built-up air handling unit and variable air volume (VAV) reheat terminal units.

Load-Reduction Retrofits

Several measures were implemented at EPA Gov to improve efficiency and reduce electrical, heating, and cooling loads. The pneumatic HVAC control system was replaced with a direct digital control (DDC) system down to the zones. The new DDC system includes ASHRAE Guideline 36 best-in-class sequences of operation, including supply air temperature reset, duct static pressure reset, demandcontrolled and occupied standby ventilation, and improved AHU and central plant scheduling. LED lighting conversions were accompanied with occupancy-based lighting controls.

HVAC loads were re-evaluated using industry-standard load calculation software rather than matching the existing system capacities.

Central Plant Retrofit

Rooftop air-to-water heat pumps were selected to replace the chiller and boiler system for GHG emissions reduction, economic performance, and reliability. One of the two heat pumps is designed with heat recovery capability to handle simultaneous heating and cooling loads without significantly increasing construction costs.

The building’s existing electrical infrastructure was able to support the all-electric central plant, primarily due to the load-reduction retrofits described above.

Repairs to the existing built-up air handling unit included replacing economizer dampers, a variable frequency drive, a chilled-water coil, sensors, and controls.

Terminal Unit Retrofits

The existing VAV reheat terminal units were replaced to accommodate lower temperature hot water and re-zoned to improve thermal comfort. The new terminal units contain two-row oversized hotwater coils, which meet heating loads with low-temperature hot water produced by heat pumps without significant replacement of existing piping infrastructure. Terminal units serving spaces with high heating loads were upgraded to parallel fan-powered boxes to reduce reheat and hot-water demand. A series fan-powered terminal unit was provided in the double-height entry lobby to provide space conditioning and destratification.

VAV reheat terminal unit replacements were accomplished in a phased approach to maintain partial occupancy throughout the project.

Domestic Hot-Water Retrofit

The existing gas-fired domestic water heater was also replaced with a hybrid heat pump water heater to eliminate natural gas consumption and help the county meet their sustainability goals.

Vera Cruz Village, California

This multifamily housing project was initiated to rehabilitate existing affordable housing for a low-income population consisting of farmworkers in the town of Richgrove in Central California. It was one of several such affordable housing renovation projects undertaken by the Rocky Mountain Institute (RMI) and partners as part of a grant to study the feasibility of retrofitting existing housing structures utilizing new building technologies while decarbonizing their energy systems and adding solar photovoltaic systems.

**[Figure: Solar Carport]**

Type: diagram

Description: The figure depicts a solar carport, which is a structure that provides shade for vehicles while generating electricity from solar panels. The carport is equipped with solar panels on its roof, which convert sunlight into electrical energy.

Key Elements:

* Solar panels -> Generate electricity from sunlight
* Carport structure -> Provides shade for vehicles
* Electrical connections -> Connect the solar panels to the electrical grid or a battery storage system

This diagram illustrates a sustainable solution for parking and energy generation, highlighting the integration of renewable energy sources into urban infrastructure.

Figure CS13.1 Exterior view of Vera Cruz Village apartments.

### Table: Data Table

| Project Name | Vera Cruz Village | Year Built |  | 1995 |
|---|---|---|---|---|
| Location | Richgrove, CA | Building Size |  | 46,734 ft2 (49 units) |
| Project Phase | Constructed 2022 | Year Last Systems Upgrade |  | N/A |
| Key EEMs/ERMs |  |  |  |  |
| • Window replacement and weatherization • Prefabricated insulated roof panels + conversion to non-ventilated attics (two buildings) • Attic air sealing and insulation (non-roof-panelled buildings, one with attic aerosol sealer applica- tion) • Distributed HPWHs (3 Sanden with 80 gal tanks, the rest hybrid HPWHs) • Carport PV |  |  |  |  |
| HVAC |  |  |  |  |
| Existing |  |  | Retrofit |  |
| • Packaged rooftop units (ducted gas heating and DX cooling) |  |  | • All-in-one Ephoca ducted heat pump + ERV + through-wall PTHPs (one building) • Ducted split heat pumps (one building) • Ducted rooftop packaged heat pumps (remaining buildings) |  |

Existing Systems

Individual apartments were served by rooftop packaged HVAC units consisting of ducted gas-fired heating and DX cooling. Distributed gas tank water heaters were in exterior closets at each apartment. Exhaust only ventilation through bath and kitchen fans.

Case Study 13 Vera Cruz Village, California

Load-Reduction Retrofits

Several measures were implemented at Vera Cruz to improve efficiency and reduce electrical, heating, and cooling loads. The most comprehensive set of load-reduction measures was performed at buildings 615 and 619, where the originally vented attic was sealed and prefabricated insulated metal panels (IMPs) were installed to replace an aging asphalt roof. Existing original windows were replaced with double-pane vinyl windows (U 0.3, SHGC 0.25). An elastomeric paint was used on the stucco walls to improve durability and reduce infiltration. For non-roof-paneled buildings, attics were manually air sealed (but left vented) and insulated with R-38 blown-in cellulose. One building (four units) received aerosol sealing in the attic. All lighting was upgraded to LEDs.

**[Figure: Construction Site with Crane and Workers]**

Type: diagram

Description: The image depicts a construction site where workers are engaged in various activities. A crane is visible, lifting a large bundle of materials towards the roof of a building under construction.

Key Elements:

* Crane -> lifting heavy materials
* Workers -> performing tasks on the roof and ground
* Building -> under construction, with scaffolding and roofing materials visible

This diagram provides a snapshot of a typical construction site, highlighting the use of heavy machinery and the importance of teamwork in completing projects efficiently and safely.

**[Figure: Before & After]**

Type: diagram

Description: The image presents a before-and-after comparison of a house, showcasing its transformation from an older state to a renovated one. The left side of the image displays the house in its original condition, while the right side shows the same house after renovation.

Key Elements:

- **Original House**: The house on the left is depicted with a brown roof and beige walls, featuring a sidewalk leading up to it. It has a chain-link fence in front and is surrounded by grass.
- **Renovated House**: The house on the right has undergone significant changes, including a new gray metal roof and light gray walls. The overall appearance suggests a modernization effort.

This visual representation effectively highlights the differences between the original and renovated states of the house, providing a clear comparison for viewers.

Figure CS13.2 Envelope improvements, including roof and window replacement.

HVAC Retrofits

In building 619, all-in-one ducted heat pump and ERV units were installed in the ceilings. These were supplemented with through-wall slim PTHPs serving the living/kitchen space. Kitchen recirculating range hoods were replaced with exhaust versions as well as bath fans with continuous exhaust. In building 615 (panelized roof retrofit), inverter-driven ducted split heat pumps were installed with continuous exhaust-only ventilation (no ERV).

The rest of the site received heat pump rooftop units to replace the existing rooftop units.

Figure CS13.3 Split system heat pump installation.

**[Figure: Mechanical - Building 619]**

Type: diagram

Description: The image presents a visual representation of mechanical components within Building 619, showcasing various elements such as ductwork, vents, and possibly HVAC systems. The diagram appears to be a collection of photographs taken from different angles and locations within the building, providing a comprehensive view of the mechanical infrastructure.

Key Elements:

* Ductwork -> The ducts are likely used for air distribution throughout the building, possibly as part of a heating, ventilation, and air conditioning (HVAC) system.
* Vents -> These vents could be part of the HVAC system, allowing for airflow into or out of specific areas of the building.
* HVAC System -> Although not explicitly labeled, the presence of ductwork and vents suggests that an HVAC system is installed in the building, which is responsible for maintaining indoor air quality and temperature.

This diagram serves as a visual aid for understanding the layout and components of the mechanical systems within Building 619, which can be useful for maintenance, repairs, or upgrades.

Figure CS13.4 Ducted heat pump/ERV unit installation.

Case Study 13 Vera Cruz Village, California

**[Figure: Domestic Hot Water Upgrades]**

Type: diagram

Description: The figure shows two images of a water heater, one before and one after an upgrade. The image on the left shows a traditional gas water heater, while the image on the right shows a hybrid heat pump water heater with a louver on the door for HP supply air and ducted HP exhaust.

Key Elements:

* Water Heater -> The main component of the image, showing the difference between a traditional gas water heater and a hybrid heat pump water heater.
* Louver -> A feature on the door of the hybrid heat pump water heater that allows for HP supply air.
* Ducted HP Exhaust -> A feature on the hybrid heat pump water heater that allows for efficient exhaust of heat.

This diagram is part of a larger document discussing domestic hot water upgrades, specifically highlighting the benefits of using hybrid heat pump water heaters over traditional gas water heaters.

**[Figure: Water Heater Installation]**

Type: diagram

Description: The image shows a water heater installed in a closet. The water heater is a tall, cylindrical tank with a pipe extending from the top and a valve at the bottom.

Key Elements:

* Water Heater -> The main component of the image, responsible for heating water.
* Pipe -> Extends from the top of the water heater, likely used for venting or connecting to a plumbing system.
* Valve -> Located at the bottom of the water heater, used to control the flow of water into and out of the tank.
* Closet -> The enclosure where the water heater is installed, providing a contained space for the appliance.

This diagram provides a clear visual representation of a water heater installation, highlighting the key components involved in the process.

Skokie Courthouse, Illinois

This case study is provided courtesy of NORESCO and Cook County, IL. Cook County undertook a multiphase project to make progress toward their goals to reduce GHG emissions by 80% by 2050. Upgrades at Skokie Courthouse were part of two project phases that included upgrades to three other courthouses, five highway maintenance facilities, and two high-rise office buildings. These phases combine to reduce GHG emissions for Cook County by 56%, or over 13,400 tons of CO2 equivalent.

### Table: Data Table

| Project Name | Skokie Courthouse | Year Built |  | 1979 |
|---|---|---|---|---|
| Location | Cook County, Illinois | Building Size |  | 345,743 ft2 |
| Project Phase | Implemented 2017 | Year Last Systems Upgrade |  | N/A |
| Key EEMs/ERMs |  |  |  |  |
| • Central GSHP plant • Window replacement and weatherization • BAS upgrade (pneumatic to DDC) with scheduling and demand-controlled ventilation • DHW load reduction • EV Chargers |  |  |  |  |
| Central Plant |  |  |  |  |
| Existing |  |  | Retrofit |  |
| • Over 30 years old • Heating: two 2,000 kW electric boilers • Cooling: two 400-ton electric chillers |  |  | • 200-ton GHSP plant • GS well field: 104 wells, 500 ft deep |  |

Existing Systems

Skokie Courthouse’s boilers and chillers were over 30 years old and had exceeded their expected service life. The existing chillers used the refrigerant R-11, which has a global warming potential (GWP) of 4,000. The courthouse’s HVAC was controlled by a pneumatic system with limited control strategies and no ability to trend system data. Building windows were original, and water testing demonstrated significant leakage. The baseline heating and cooling loads were evaluated using 36 months of 30-minute interval data provided by the electric utility. Figure CS14.1 shows a breakdown of courthouse electricity use by month for 2013.

Load-Reduction Retrofits

Several measures were implemented at Skokie Courthouse to improve efficiency and reduce electrical, heating, and cooling loads. Existing original windows were replaced with thermally broken, low-e windows, and door sweeps, and weatherization reduced infiltration. LED lighting conversions accompanied with occupancy-based lighting controls reduced electric demand.

Case Study 14 Skokie Courthouse, Illinois

**[Figure: Electricity Consumption by Month]**

Type: chart

Description: This line chart illustrates the monthly electricity consumption in kilowatt-hours (kWh) for different categories of usage, including general, lighting, fans, and central plant. The chart provides a visual representation of how electricity usage varies throughout the year.

Data Representation:

* General: 400,000 kWh
* Lighting: 200,000 kWh
* Fans: 100,000 kWh
* Central Plant: 1,000,000 kWh

Metric: Electricity consumption

Chart Type: Line chart

Units: Kilowatt-hours (kWh)

Chart Generation Hint:

* X-axis: Month
* Y-axis: Electricity consumption (kWh)

Structured Data (Machine Readable):

{
  "chart_type": "line",
  "metric": "electricity consumption",
  "units": "kWh",
  "data": {
    "General": 400000,
    "Lighting": 200000,
    "Fans": 100000,
    "Central Plant": 1000000
  }}
}

Figure CS14.1 Electricity consumption.

The pneumatic HVAC control system was replaced with a direct digital control (DDC) system, while retaining some pneumatic actuators and terminal box controls for cost effectiveness. Demand-controlled ventilation and improved AHU scheduling were implemented with the new DDC system.

Central Plant Retrofit

A GSHP was selected to replace the existing electric central plant for GHG emissions reduction, economic performance, and reliability. A geothermal well field sized to offset 100% of the building’s heating and cooling loads was financially impractical. The installed GSHP system includes a 200-ton geothermal well field as a heat sink and a 200-ton heat recovery chiller.

At 200 tons, the GSHP system carries the cooling load of the building for all but approximately 63 hours during a typical year, when peaking/backup chillers are used to supplement. The backup/peaking chillers are two 250-ton high-efficiency centrifugal chillers, which provide N+1 redundancy.

For heating, the GSHP system provides 3,466 kBTUh of heat under design conditions and carries the heating load of the building for all but approximately 484 hours a year, when the peaking/backup boilers are used to supplement. The proposed peaking/backup boilers are two high-efficiency gas-fired condensing boilers sized at 3,000 kBTUh each for N+1 redundancy. These boilers operate at 98% efficiency at low loads and low water temperatures.

Domestic Hot Water

Domestic plumbing fixtures were retrofitted with high-efficiency fixtures, reducing domestic hotwater consumption by approximately 31%. The existing domestic water heaters were two tank-type electric heating units that were original to the building. The team evaluated heating the domestic water via heat recovery from the GSHP system, but the relatively low domestic water load for the courthouse did not justify the additional cost or complexity. As a result, a high-efficiency gas-fired domestic water heater replaced one existing unit. The remaining electric domestic water heater was left in place to serve as an emergency backup. With improvements in heat pump water heater technology, the existing electric unit may be replaced with a heat pump water heater and used as the primary DHW heating source, with the high-efficiency gas-fired unit retained as the emergency backup.

EV Charging

Two 240V, Level 2 EV chargers were installed at Skokie Courthouse. These are not used for two-way charging and result in a small increase in electric use for the courthouse. The EV chargers were installed to demonstrate the county’s climate initiatives and increase public awareness.

Stella B. Werner Council Office Building, Maryland

This case study is provided courtesy of NORESCO and Montgomery County, MD. Montgomery County undertook a project to upgrade the Stella B. Werner Council Office Building (COB), make progress toward their goals to reduce GHG emissions, and apply for LEED certification. The upgrades to the building envelope, lighting, and HVAC combine to reduce GHG emissions for Montgomery County by over 1600 tons of CO2 equivalent.

**[Figure: Council Office Building]**

Type: diagram

Description: The image depicts a multi-story building with a prominent entrance and a satellite dish on the roof. The building's facade features a mix of windows and brickwork, with a sign above the entrance reading "Council Office Building." The surrounding area includes trees and streetlights, set against a blue sky with white clouds.

Key Elements:

- **Building Facade**: The building's exterior is characterized by a combination of windows and brickwork, giving it a modern yet traditional appearance.
- **Entrance Sign**: A sign above the entrance clearly indicates that this is the Council Office Building, suggesting it serves as a hub for local government activities.
- **Satellite Dish**: The presence of a satellite dish on the roof implies that the building is equipped with advanced communication technology, possibly for broadcasting or receiving data.
- **Surrounding Environment**: The inclusion of trees and streetlights in the foreground adds context to the building's location, suggesting it is situated in an urban or suburban area.

Figure CS15.1 Exterior view of Stella B. Werner Council Office Building.

### Table: Data Table

| Project Name | Stella B. Werner Council Office Building | Year Built |  | 1952 (Central Core) 1962 (South Wing) 1970s–1980s (further additions) |
|---|---|---|---|---|
| Location | Montgomery County, Maryland | Building Size |  | 142,480 ft2 |
| Project Phase | Implemented 2021 | Year Last Systems Upgrade |  | Variable |
| Key EEMs/ERMs |  |  |  |  |
| • LED lighting upgrade • Window and door replacement • Water-cooled VRF system with DOAS |  |  |  |  |
| Existing |  |  | Retrofit |  |
| Varying systems by wing • Four-pipe FCUs, WSHPs, AHUs, RTUs • Heating: central natural gas boilers, dedicated natural gas boilers, packaged gas-fired RTUs • Cooling: central electric chillers, packaged DX RTUs, cooling towers (WSHPs) |  |  | • 300-ton water-cooled VRF system • DOAS with energy recovery • DX AHU/RTU for dining/kitchen and audi- torium • Data center conditioning unchanged |  |

Case Study 15 Stella B. Werner Council Office Building, Maryland

Existing Systems

Lighting The interior lighting was primarily made up of T8, and some T12, fluorescent lamps. Switch-mounted occupancy sensors were installed in many areas. Exterior lighting was high-intensity discharge (HID) with high-pressure sodium (HPS) lamps. Envelope Due to multiple additions in the 1960s, '70s, and '80s, different parts of the COB have different architectural designs and different construction materials. A majority of windows were single pane and original to each wing's construction. Many of the operable windows throughout the Core and Core South wings did not close properly and permitted the infiltration of a great deal of unconditioned outdoor air and moisture. HVAC The multiple additions and renovations to the COB over the past 60 years had resulted in a mix of heating and cooling equipment. Multiple HVAC renovation projects were implemented to upgrade systems serving various sections of the building. The result was that the COB has a wide variety of different designs and vintages of HVAC systems, which presented a wide range of issues. A central boiler plant located on the first floor of the Core building served the majority of the COB. The plant consisted of six 299-MBH, direct-vented, natural gas-fired, hot-water boilers. Cooling for much of the building was supplied by a central chiller plant located in the northwestern corner of the parking garage lower level. The plant consisted of three 110-ton water-cooled reciprocating chillers. The central plant water chillers had been in service for approximately 30 years and were near the end of effective useful life. The main chiller plant did not have enough capacity to simultaneously meet building cooling demand and serve as backup for the data center. The central boiler and chiller plants provided heating and cooling for most systems in the building, with some exceptions. Health Wing: Four-pipe FCUs located along the perimeter of the space and four-pipe AHUs on each floor providing tempered ventilation air to the center areas. FCUs and AHUs served by central plants. Auditorium First Floor: Four-pipe AHU served by central plants.

**[Figure: Floor Plan of a Building]**

Type: diagram

Description: The figure is a floor plan of a building, showing the layout of different rooms and areas. The plan is divided into several sections, including the parking garage, auditorium, connector, health wing, council wing, core & core south, and south wing.

Key Elements:

* Parking Garage -> A large area for parking vehicles
* Auditorium -> A room for presentations and performances
* Connector -> A hallway connecting different parts of the building
* Health Wing -> An area for medical facilities
* Council Wing -> An area for administrative offices
* Core & Core South -> Central areas of the building
* South Wing -> A wing of the building located in the south

This diagram provides a clear overview of the building's layout, making it easy to navigate and understand the relationships between different areas.

Figure CS15.2 Diagram of office building layout.

Council Wing Second Floor: Dining area served by a four-pipe AHU located with hot water from a dedicated gas-fired boiler. Kitchen served by a two-pipe makeup air unit (MAU), also served from the same small boiler.

Council Wing Third Floor: Meeting room served by a 15-ton RTU connected to central plants. Hearing room served by a 40-ton AAON packaged rooftop unit (RTU) with gas heat and direct expansion (DX) cooling.

Core And Core South Floors 1-5: WSHPs with condenser loop tempered by the central boiler plant by means of a heat exchanger. The loop was also interconnected to the central cooling towers for heat rejection. Due to the age of the WSHP system, many of the compressors were beginning to fail.

Core South Sixth Floor: Four-pipe VAV RTU served by the central boiler and chiller plants.

Core Top-floor Hearing Room: AHU with DX cooling and electric duct heaters. Two air-cooled condensers on the roof serve the AHU.

The South Wing of the building was heated by a separate hot-water loop, served by a 1260-MBH hotwater boiler. This serves a two-pipe hydronic loop distributed throughout the wing's air-handling units and fan coil units. A separate dedicated hot-water boiler serves the first-floor kitchen and cafeteria of the Council Wing.

South Wing Floors 2, 4, 5: Four-pipe perimeter FCUs with a four-pipe AHU in a penthouse mechanical room for tempered ventilation air to each floor. The AHU is served by the central chiller plant; however, hot water is provided by a dedicated gas-fired boiler located in the penthouse mechanical room.

The sixth floor is served by VAV boxes, similar to the top floor of Core South. The VAV boxes are served by a four-pipe RTU, which in turn is served by the central cooling plant and by the small hot-water boiler in the penthouse.

The third floor of the South Wing houses the County's large data center. This area is primarily served by computer room air-conditioning (CRAC) units and a 120-ton air-cooled chiller located at ground level on the eastern side of the building. The chilled-water supply is also interconnected with the central chiller plant loop for backup and redundancy.

Load-Reduction Retrofits

The window and door replacements, LED lighting upgrades, and DOAS energy recovery measures implemented at the Stella B. Werner Council Office Building improved efficiency and reduced electrical, heating, and cooling loads. Existing original windows were replaced with double-pane insulated windows throughout the Health Wing, Core, Core South, and first floor Council Wing. Exterior doors were replaced with insulated doors in the Health Wing and first floor connector wing. LED lighting conversions accompanied with occupancy-based lighting controls reduced electric demand.

HVAC Options

The County desired a comprehensive, long-term solution for the COB, and a number of different HVAC upgrade options were evaluated for occupant comfort, energy savings potential, ease of operation and

Case Study 15 Stella B. Werner Council Office Building, Maryland maintenance, and flexibility in phasing of installation to minimize occupant disruption during construction.

Option 1-New Central Plants and Variable Air Volume (VAV) Systems

This HVAC upgrade option would involve replacing and expanding the central plant boilers and chillers so that these central plants could serve the entire building. Condensing boilers would provide heating, and water-cooled centrifugal chillers would provide cooling. VAV AHUs and terminal boxes would be installed throughout the building. This option would require electrical system upgrades for the new chiller plant.

Option 2-New Central Plants, Dedicated Outdoor Air Units, and Fan Coil Units

This HVAC upgrade option would again involve replacing and expanding the central boiler and chiller plants with condensing boilers and centrifugal chillers to serve the entire building. Four-pipe FCUs would be installed throughout the building and a DOAS with heat recovery on the roof and/or on each floor to provide ventilation air to the occupied spaces. This option would require electrical system upgrades for the new chiller plant. Option 3-New Variable Refrigerant Flow (VRF) with Dedicated Outdoor Air (DOAS)

This HVAC upgrade option would involve installing an approximately 300-ton VRF system, together with a DOAS system with heat recovery, to serve the entire building. The only exceptions would be the Auditorium and Council Wing, which would receive new packaged HVAC systems, and the South Wing data center, which would remain as-is. A water-cooled VRF system was chosen over an air-cooled VRF system for two primary reasons: lack of available roof space and the need for significant structural reinforcement, which would severely interrupt council operations on the sixth floor. The water-cooled VRF heat pumps are small indoor units installed in small closets near the center of each floor. The system requires a central condenser water loop, which is maintained between 70°F and 86°F. The loop is served by a cooling tower to reject excess heat and a condensing boiler plant to add heat when required. These were installed in the parking garage (cooling tower on the roof and condensing boilers and associated pumps in the existing parking garage mechanical room).

VRF System

A VRF system with dedicated outdoor air units complete with heat recovery was selected. The VRF system provided higher energy savings and comparatively lower installation cost. However, the biggest deciding factor in choosing VRF was the design and installation flexibility to overcome site- and building-specific constraints associated with this retrofit project.

- Because there was no hot-water or chilled-water piping to run, the VRF system helped to overcome the limited ceiling height.
- The ability to phase the installation by floor was critical to the success of the project.
- The modular and adaptable design provided greater flexibility in zoning, which fit well with other proposed interior renovations.
- The ability to efficiently provide simultaneous heating and cooling through the same system improved comfort conditions and energy savings.
- The modular VRF system had the flexibility to provide individual comfort control for each council member without affecting the whole building.

Virginia Beach City Public Schools, Virginia

These case studies are provided courtesy of NORESCO and Virginia Beach City Public Schools. Virginia Beach City Public Schools (VBCPS) has completed multiple phases of projects at various schools as part of a continuing effort to improve building infrastructure while reducing operating costs. WSHP and GSHP upgrades at Providence, Strawbridge, and Centerville Elementary Schools were part of a program with more than 11 project phases across the school district.

### Table: Data Table

| Project Name | Providence Elementary School | Year Built |  | 1981 |
|---|---|---|---|---|
| Location | Virginia Beach, Virginia | Building Size |  | 61,831 ft2 |
| Project Phase | 1 | Year Implemented |  | 2010 |
| Key EEMs/ERMs |  |  |  |  |
| • Weatherization • Demand-controlled ventilation • Central GSHP plant serving WSHP loop • Packaged RTUs replaced with GSHP RTUs |  |  |  |  |
| Existing |  |  | Retrofit |  |
| • Classroom: two-pipe WSHPs • DX RTUs • Heating: 288 kW electric boiler • Cooling: two-cell closed-circuit cooling tower |  |  | • GS well field: 152 wells, 300 ft deep • Heat pump RTUs |  |

Existing Systems

The gym, cafetorium, and library were conditioned by four RTUs with DX cooling and electric resistance heating coils. The office RTU included DX cooling with electric heaters located in the office ductwork to serve the office rooms. At the time of retrofit, Providence Elementary used a two-pipe water-source heat pump (WSHP) system for the classroom heating and cooling air conditioning as well as ventilation air. Each of the classrooms has two water source heat pumps that range in capacity from 0.6 tons to 2.3 tons. The classroom WSHP system included a 288-kW electric boiler and a two-cell, closed-loop evaporative cooling tower whose temperature ranges from 63°F to 103°F.

GSHP Loop

A GSHP loop was installed and connected to the existing WSHP system at Providence Elementary. The GSHP loop comprises in-ground boreholes drilled in the football and soccer field on the eastern side of the building. The well field consists of 152 boreholes, drilled at a 300-ft depth and spaced apart on a 20-ft grid, to satisfy the school's heating and cooling requirements.

Case Study 16 Virginia Beach City Public Schools, Virginia

The existing cooling tower was demolished and removed, but the boiler remained in place for emergency backup. The existing RTUs were replaced with GSHP RTUs. In the office area, four new shut-off VAV boxes containing electric reheat coils were installed to replace the existing four electric duct heaters. Because the GSHP RTUs do not serve any classrooms, a demand-controlled ventilation sequence was implemented to reduce the amount of outdoor air that must be heated or cooled. This project also included replacing the existing PVC condenser water piping from the original WSHP network, which was near end of life. The piping was replaced with new schedule 40 black steel and piped in a reversereturn arrangement to allow for a more balanced flow, reducing the number of balancing valves. The new piping was installed in the ceiling plenum.

### Table: Data Table

| Project Name | Strawbridge Elementary School | Year Built |  | 1991 |
|---|---|---|---|---|
| Location | Virginia Beach, Virginia | Building Size |  | 84,948 ft2 |
| Project Phase | 5 and 6 | Year Implemented |  | 2013 |
| Key EEMs/ERMs |  |  |  |  |
| • Weatherization • Central GSHP plant serving WSHP loop • Replacement WSHPs and FCUs with GSHP console units |  |  |  |  |
| Existing |  |  | Retrofit |  |
| • Classroom two-pipe WSHPs • Classroom FCUs with DX • DX RTUs • Heating: two 1440 MBH natural gas boilers • Cooling: two closed-circuit cooling towers |  |  | • GS well field: 274 wells, 300 ft deep • GSHP console units |  |

Existing Systems

The gymnasium, library, cafeteria, and administrative areas were served by unitary DX RTUs with electric heating. The school previously used a two-pipe WSHP system with console-style WSHPs, ranging from 3.5 to 4 tons of cooling each, in the classrooms that were original to the building. During the 1996-1997 school year, outdoor air was sealed to the classroom WSHPs, and dedicated outdoor air units with DX coils, gas furnaces, and heat pipes were added to provide conditioned outdoor air to the classroom spaces. Once the outdoor air grilles were sealed for these classrooms, the WSHPs became oversized, causing the units to cycle frequently. The classroom WSHP system included two hot-water boilers rated at 1440 MBH output and two closed-circuit fluid coolers.

GSHP Loop

A GSHP well field was installed in the large playground space behind the building at Strawbridge Elementary as part of Phase 5 with VBCPS. The GSHP loop well field consists of 274 boreholes, drilled at a 300-ft depth and spaced apart on a 20-ft grid.

The balance of the GSHP system was installed under Phase 6, including:

- Replacement of fan coil units with GSHP system console units
- Connection of the GSHP console units to the ground-source loop
- Connection of GSHP RTUs (replaced under separate roofing project) to the ground-source loop As at Providence Elementary, the existing cooling towers were demolished and removed, but one of the existing boilers remained in place for emergency backup.

### Table: Data Table

| Project Name | Centerville Elementary School | Year Built |  | 1983 |
|---|---|---|---|---|
| Location | Virginia Beach, Virginia | Building Size |  | 67,082 ft2 |
| Project Phase | 8 and 10 | Year Implemented |  | 2017, 2021 |
| Key EEMs/ERMs |  |  |  |  |
| • Weatherization • Central GSHP plant serving WSHP loop • Replacement WSHPs and FCUs with GSHP console units • Packaged RTUs replaced with GSHP RTUs |  |  |  |  |
| Existing |  |  | Retrofit |  |
| • Classroom two-pipe WSHPs • DX RTUs and outdoor air units • Heating: 510 kwW electric boiler • Cooling: closed circuit cooling tower |  |  | • GS well field: 220 wells, 300 ft deep • Heat pump RTUs and outdoor air units |  |

Centerville Elementary School (Phases 8 and 10)

Centerville Elementary is a 67,082 ft2 facility constructed in 1983.

Existing Systems

Packaged DX RTUs and electric heating served the larger non-classroom spaces.

Like the other schools, Centerville Elementary was built with a two-pipe WSHP system serving the classrooms. Circa 2002, outdoor air was sealed to the classroom WSHPs, and three outdoor air units with DX cooling and electric heating were installed to provide conditioned outdoor air to the classroom spaces. As with Strawbridge Elementary, after the outdoor air sections were sealed, the WSHP units were oversized.

Case Study 16 Virginia Beach City Public Schools, Virginia

GSHP Loop

During Phase 8, a GSHP loop was installed to serve the existing WSHP system. The well field was installed in the open grass area adjacent to the school and included 220 boreholes, each 300 feet deep. The GSHP loop was sized based on the calculated building heating load of 245 tons, which is greater than the calculated cooling load of 200 tons. The well field was designed to serve the whole building, which includes the classroom GSHPs, the RTUs, and the OAUs. During Phase 8, the existing WSHPs were replaced with new GSHPs, but the existing RTUs and outdoor air units remained in place.

Phase 8 also replaced the existing WSHP loop piping within the building with an upsized loop. The water loop included piping stub-outs to the existing locations of the RTUs and outdoor air units for future connections.

Four years later, during Phase 10, the five RTUs and three outdoor air units were replaced, tied into the Phase 8 water loop stub outs, and connected to the GSHP system. Because the GSHP systemincluding associated pumps, condenser water piping, and well fields-originally was designed to accommodate the additional HVAC loads of these RTUs and outdoor air units, no changes to the GSHP were required.

STAR Transit, Texas

This example is part of the Preliminary Energy Assessments (PEA) program through the Texas State Energy Conservation Office (SECO) and is provided courtesy of NORESCO. STAR Transit is a public bus transportation service with a 20,000 ft2 campus at Terrell, TX. The facility consists of a 10,000 ft2 large office space along with an equally large parking garage for the buses. STAR Transit is currently in the process of converting their fleet of 14 buses to electric vehicles (EVs). The projected increase in the electricity load of the building is planned to be offset by the installation of solar PV systems across the facility. STAR Transit had received funding for use in electrification projects that had a deadline of August 2022. A SECO PEA audit estimated that converting 14 buses to EVs will increase the daily electricity consumption by 1078 kWh and the total annual electricity consumption by 388,080 kWh. STAR Transit was interested in offsetting the demand increase from EV buses with a PV installation. However, EV charging was estimated to happen mostly during the evening times in contrast with the daytime generation from a PV system (bus operation is 6:00 a.m. to 6:00 p.m., and charging would be scheduled for 6:00 p.m. to 6:00 a.m.). Due to the project funding timeline, lead times for battery storage systems in the market, and the magnitude of the electrical storage need, grid integration for the PV system was evaluated in the current assessment. Even grid integration requires STAR Transit to change utility providers for a utility that allows PV grid integration. This is possible due to the deregulated electricity market in Texas. Analysis showed that there will be only three hours of overlap between PV generation and bus charging with no energy storage available. The figures show the comparison between PV generation vs. EV charging for representative days for the months of January, April, June, and October. STAR Transit moved forward with PV system installation to avoid expiration of funds, and the next recommended step for their fleet decarbonization is installation of battery storage to fully harness the clean PV energy generation to charge the bus fleet overnight.

**[Figure: Figure on page 230]**

Type: diagram

Description: The image depicts a building with a tan exterior and red awnings, featuring a sign that reads "SUNSET" in red letters. A concrete driveway leads to the entrance, accompanied by a sidewalk and a grassy area with trees on the left side. The background showcases a blue sky with wispy clouds.

Key Elements:

* Building -> The main structure in the image, characterized by its tan exterior and red awnings.
* Sign -> A prominent feature displaying the text "SUNSET" in red letters.
* Driveway -> A concrete path leading to the entrance of the building.
* Sidewalk -> A pedestrian walkway adjacent to the driveway.
* Grass -> A green area with trees situated on the left side of the image.
* Sky -> The background of the image, featuring a blue sky with wispy clouds.

Figure CS17.1 Exterior view of STAR Transit.

Case Study 17 STAR Transit, Texas

**[Figure: Solar generation vs. EV Charging for (a) January, (b) April, (c) July, and (d) October]**

Type: chart

Description: The chart compares solar generation and EV bus charge in kilowatt-hours (kWh) over a 24-hour period for four different months: January, April, July, and October. The key insight is that solar generation peaks during the daytime hours, while EV bus charging occurs primarily during the evening and nighttime hours.

Data Representation:

*   Solar Generation (KWh): 0-250 kWh
*   EV Bus Charge (KWh): 0-100 kWh
*   Metric: Energy consumption
*   Chart Type: Line chart
*   Units: Kilowatt-hours (kWh)

Chart Generation Hint:

*   X-axis: Time of day (12:00 AM - 11:00 PM)
*   Y-axis: Energy consumption (kWh)

Structured Data (Machine Readable):

```json
{
  "chart_type": "line_chart",
  "metric": "energy_consumption",
  "units": "kWh",
  "data": {
    "solar_generation": {
      "january": [0, 50, 100, 150, 200, 250],
      "april": [0, 50, 100, 150, 200, 250],
      "july": [0, 50, 100, 150, 200, 250],
      "october": [0, 50, 100, 150, 200, 250]
    }}},
    "ev_bus_charge": {
      "january": [0, 20, 40, 60, 80, 100],
      "april": [0, 20, 40, 60, 80, 100],
      "july": [0, 20, 40, 60, 80, 100],
      "october": [0, 20, 40, 60, 80, 100]
    }
  }
}
```

This chart provides a visual representation of the relationship between solar generation and EV bus charging over a 24-hour period for four different months. The data shows that solar generation peaks during the daytime hours, while EV bus charging occurs primarily during the evening and nighttime hours. This information can be useful for optimizing energy consumption and reducing reliance on non-renewable energy sources.

**[Figure: Solar Generation vs EV Charging - Jan]**

Type: chart

Description: This chart compares the solar generation and EV bus charge in kilowatt-hours (kWh) over a 24-hour period in January. The key insight is that solar generation peaks during the daytime hours, while EV bus charging occurs primarily during the evening and nighttime hours.

Data Representation:

* Solar Generation (KWh): 0-100 kWh
* EV Bus Charge (KWh): 0-90 kWh
* Metric: Energy consumption
* Chart Type: Line chart
* Units: Kilowatt-hours (kWh)

Chart Generation Hint:

* X-axis: Time of day (1:00 AM - 11:00 PM)
* Y-axis: Energy consumption (kWh)

Structured Data (Machine Readable):

{
  "chart_type": "line",
  "metric": "energy_consumption",
  "units": "kWh",
  "data": {
    "solar_generation": [0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100],
    "ev_bus_charge": [0, 10, 20, 30, 40, 50, 60, 70, 80, 90]
  }}
}

**[Figure: Solar Generation vs EV Charging - April]**

Type: chart

Description: This line chart compares the solar generation in kilowatt-hours (kWh) with the electric vehicle (EV) bus charge in kWh over a 24-hour period in April. The chart shows that solar generation peaks at around 1:00 PM, while EV bus charging peaks at around 5:00 PM.

Data Representation:

* Solar Generation (KWh): 0-250 kWh
* EV Bus Charge (KWh): 0-200 kWh
* Metric: Energy consumption
* Chart Type: Line chart
* Units: Kilowatt-hours (kWh)

Chart Generation Hint:

* X-axis: Time of day (12:00 AM - 11:00 PM)
* Y-axis: Energy consumption (kWh)

Structured Data (Machine Readable):

{
  "chart_type": "line_chart",
  "metric": "energy_consumption",
  "units": "kWh",
  "data": {
    "solar_generation": [0, 50, 100, 150, 200, 250],
    "ev_bus_charge": [0, 50, 100, 150, 200]
  }}
}

**[Figure: Solar Generation vs EV Charging - Oct]**

Type: chart

Description: This line chart compares the solar generation in kilowatt-hours (kWh) with the electric vehicle (EV) bus charge in kWh over a 24-hour period in October. The key insight is that solar generation peaks during the daytime hours, while EV bus charging occurs primarily during the evening and nighttime hours.

Data Representation:

*   Solar Generation (KWh): 0-200
*   EV Bus Charge (KWh): 0-100
*   Metric: Energy consumption
*   Chart Type: Line chart
*   Units: Kilowatt-hours (kWh)

Chart Generation Hint:

*   X-axis: Time of day (12:00 AM to 11:00 PM)
*   Y-axis: Energy consumption (kWh)

Structured Data (Machine Readable):

```json
{
  "chart_type": "line",
  "metric": "energy_consumption",
  "units": "kWh",
  "data": {
    "solar_generation": {
      "12:00 AM": 0,
      "1:00 AM": 0,
      "2:00 AM": 0,
      "3:00 AM": 0,
      "4:00 AM": 0,
      "5:00 AM": 0,
      "6:00 AM": 0,
      "7:00 AM": 0,
      "8:00 AM": 0,
      "9:00 AM": 0,
      "10:00 AM": 0,
      "11:00 AM": 0,
      "12:00 PM": 0,
      "1:00 PM": 0,
      "2:00 PM": 0,
      "3:00 PM": 0,
      "4:00 PM": 0,
      "5:00 PM": 0,
      "6:00 PM": 0,
      "7:00 PM": 0,
      "8:00 PM": 0,
      "9:00 PM": 0,
      "10:00 PM": 0,
      "11:00 PM": 0
    }}},
    "ev_bus_charge": {
      "12:00 AM": 0,
      "1:00 AM": 0,
      "2:00 AM": 0,
      "3:00 AM": 0,
      "4:00 AM": 0,
      "5:00 AM": 0,
      "6:00 AM": 0,
      "7:00 AM": 0,
      "8:00 AM": 0,
      "9:00 AM": 0,
      "10:00 AM": 0,
      "11:00 AM": 0,
      "12:00 PM": 0,
      "1:00 PM": 0,
      "2:00 PM": 0,
      "3:00 PM": 0,
      "4:00 PM": 0,
      "5:00 PM": 0,
      "6:00 PM": 0,
      "7:00 PM": 0,
      "8:00 PM": 0,
      "9:00 PM": 0,
      "10:00 PM": 0,
      "11:00 PM": 0
    }
  }
}

**[Figure: Solar Generation vs EV Charging - Jul]**

Type: chart

Description: This line chart compares the solar generation in kilowatt-hours (kWh) with the electric vehicle (EV) bus charge in kWh over a 24-hour period in July. The chart shows that solar generation peaks at around 1:00 PM, while EV bus charging peaks at around 6:00 PM.

Data Representation:

* Solar Generation (KWh): 0-250 kWh
* EV Bus Charge (KWh): 0-100 kWh
* Metric: Kilowatt-hours (kWh)
* Chart Type: Line chart
* Units: Kilowatt-hours (kWh)

Chart Generation Hint:

* X-axis: Time of day (12:00 AM - 11:00 PM)
* Y-axis: Kilowatt-hours (kWh)

Structured Data (Machine Readable):

{
  "chart_type": "line",
  "metric": "kilowatt-hours",
  "units": "kWh",
  "data": {
    "Solar Generation": {
      "12:00 AM": 0,
      "1:00 AM": 50,
      "2:00 AM": 100,
      "3:00 AM": 150,
      "4:00 AM": 200,
      "5:00 AM": 250,
      "6:00 AM": 200,
      "7:00 AM": 150,
      "8:00 AM": 100,
      "9:00 AM": 50,
      "10:00 AM": 0,
      "11:00 AM": 0,
      "12:00 PM": 0,
      "1:00 PM": 50,
      "2:00 PM": 100,
      "3:00 PM": 150,
      "4:00 PM": 200,
      "5:00 PM": 250,
      "6:00 PM": 200,
      "7:00 PM": 150,
      "8:00 PM": 100,
      "9:00 PM": 50,
      "10:00 PM": 0,
      "11:00 PM": 0
    }}},
    "EV Bus Charge": {
      "12:00 AM": 0,
      "1:00 AM": 0,
      "2:00 AM": 0,
      "3:00 AM": 0,
      "4:00 AM": 0,
      "5:00 AM": 0,
      "6:00 AM": 0,
      "7:00 AM": 0,
      "8:00 AM": 0,
      "9:00 AM": 0,
      "10:00 AM": 0,
      "11:00 AM": 0,
      "12:00 PM": 0,
      "1:00 PM": 0,
      "2:00 PM": 0,
      "3:00 PM": 0,
      "4:00 PM": 0,
      "5:00 PM": 0,
      "6:00 PM": 50,
      "7:00 PM": 100,
      "8:00 PM": 150,
      "9:00 PM": 200,
      "10:00 PM": 250,
      "11:00 PM": 200
    }
  }
}

North Oak Development, Canada

This case study is provided courtesy of Creative Energy. An example of an ambient temperature district energy system broke ground in Oakville, Ontario, Canada on March 28, 2023. Creative Energy developed and is implementing the ambient loop for the Minto Communities North Oak development. While this system serves a new construction development, it provides an example for implementing district ambient loops. The North Oak project interconnects phase-by-phase geothermal fields to provide reliable space heating for five residential buildings developed over three phases. The district system will distribute ambient water at a temperature between 34°F and 90°F for space heating and cooling. The district system also supplies higher-temperature heating water at 145°F for local DHW production from a central natural gas boiler. As seen in the schematic diagram, each building is connected to the district system via two heat exchangers, one for space heating and cooling and one for DHW production. The ambient distribution network will interconnect three geothermal fields, which will be constructed in tandem with the building development schedule. The geothermal field for the first phase will consist of 70 boreholes drilled 600 feet deep. As each phase comes online, another field will be added to the system, increasing the low-carbon thermal energy capacity. The combination of the geothermal fields and ambient distribution will allow buildings to share energy with one another and enable in-suite water-source heat pumps within the buildings to operate reliably and efficiently. The district system supplies all space conditioning needs using the geothermal ambient loop, with the boiler plant reserved for domestic hot-water heating and as a backup for the geothermal field. The district system is expected to decrease carbon emissions related to space heating by up to 95 percent and is expected to avoid almost 1000 tons of GHG emissions annually.

**[Figure: Heat Pump Piping Diagram]**

Type: diagram

Description: The diagram illustrates the heat pump piping system, showcasing the connections between various components. It highlights the flow of heat energy through the system, emphasizing the role of each component in the overall process.

Key Elements:

*   Heat Pump Piping -> Transfers heat energy between components
*   Geo Exchange/Ambient Distribution -> Facilitates heat exchange with the environment
*   Heating Plant -> Generates heat for distribution
*   DHW -> Provides domestic hot water supply
*   Heating Distribution -> Distributes heat throughout the system
*   Flue -> Manages exhaust gases from the heating plant

This diagram provides a comprehensive overview of the heat pump piping system, illustrating how each component contributes to the efficient transfer and distribution of heat energy.

Figure CS18.1 Schematic Diagram of North Oak Ambient District Loop (Image credit: Creative Energy [2022])

Kitsilano Pool, Canada

This case study is provided courtesy of FirstLight Energy Solutions. Kitsilano Pool, one of Vancouver’s seasonal outdoor pools, is a popular swimming destination from late May until September annually. After upgrading its aged domestic hot-water system, it now utilizes a central heat pump with CO2 refrigerant. Selected as the inaugural site for this system, Kitsilano Pool serves as a testing ground before citywide implementation of central HPWHs in other municipal buildings.

**[Figure: Outdoor Pool with City Skyline]**

Type: diagram

Description: The image depicts a large outdoor pool situated in front of a city skyline, with a mountain range visible in the background. The pool is rectangular and features a light blue hue, accompanied by a few pool toys and a ladder at one end. In the foreground, a concrete walkway runs along the length of the pool, while a fence separates the pool area from the city beyond. The cityscape is characterized by numerous tall buildings, trees, and a body of water, with a mountain range rising up in the distance. The sky above is a clear blue.

Key Elements:

- Pool -> The central focus of the image, showcasing its size and amenities.
- City Skyline -> Provides context for the pool's location, highlighting the urban environment.
- Mountain Range -> Adds depth and natural beauty to the scene, contrasting with the man-made structures.
- Concrete Walkway -> Serves as a pathway for users to access the pool and enjoy the surrounding views.
- Fence -> Separates the pool area from the city, ensuring safety and privacy for pool users.

Figure CS19.1 Exterior view of Kitsilano Pool.

### Table: Data Table

| Project Name | Kitsilano Pool | Year Built |  | 1978 |
|---|---|---|---|---|
| Location | Vancouver, British Columbia (Canada) | Building Size |  | — |
| Project Phase | Implemented 2021 | Year Last Systems Upgrade |  | N/A |
| Key EEMs/ERMs |  |  |  |  |
| • Low-flow fixture conversion (2022) • Central Domestic Hot-Water Heat Pumps (2022) |  |  |  |  |
| Domestic Hot Plant |  |  |  |  |
| Existing |  |  | Retrofit |  |
| • Mid-efficiency 725 MBH atmospheric domestic hot- water boiler with two 120-gallon unfired hot-water tanks |  |  | • 210 MBH CO air-source heat 2 pump water heater with 500 gal- lons of DHW storage and an elec- tric resistance swing tank |  |

Existing Domestic Hot-Water System

The existing domestic hot-water system comprised a single 725 MBH mid-efficiency gas boiler supplying two 120-gallon hot-water storage tanks in the pool’s main mechanical room. The system functioned on stand-alone controls, supplying hot water to the pool deck and changing room showers. All showerheads were rated at 2.5 GPM.

Load-Reduction Measure

Case Study 19 Kitsilano Pool, Canada

All showerheads were retrofitted with 1.5 GPM showerheads, reducing the peak DHW demand by approximately 40%. The new DHW plant was integrated with the facility BAS, allowing remote monitoring and control, which can also be utilized for demand-response management.

DHW Plant Retrofit

The City of Vancouver chose this site to implement a central heat pump water heater using CO2 refrigerant as a proof-of-concept test project before implementing them on other municipally owned buildings. In addition to eliminating GHG emissions associated with domestic hot water, a secondary goal was to cool the boiler room in summer using the heat pump for maintenance personnel using the workstation located there.

The system was sized to facilitate 100% of the DHW load, eliminating the need for natural gas for DHW heating. It consists of a single-pass air-source CO2 heat pump, capable of recovering 233 gallons per hour at a COP of 3.8. The heat pump supplies DHW to two 250-gallon primary storage tanks connected in series to promote stratification. To ensure backup functionality, the second primary tank includes a 54-kW electric heater in case of heat pump failure. A third 250-gallon tank, equipped with an 18-kW electric heater, acts as a swing tank, preventing recirculation of DHW from affecting the primary storage tanks’ temperature stratification. Adherence to local building codes required the use of a double-wall heat exchanger with leak detection, preventing the use of the heat pump from directly heating domestic water. Instead, a small hydronic circuit employs a brazed plate double-wall heat exchanger to deliver heat from the heat pump to the domestic hot-water system.

**[Figure: Domestic Hot Water System]**

Type: diagram

Description: The diagram illustrates a domestic hot water system, showcasing its components and their connections. It highlights the various elements involved in providing hot water for domestic use.

Key Elements:

* ASHP-1 -> A heat pump unit responsible for heating water.
* DWP-2 -> A water pump that circulates heated water through the system.
* DHWT-1 -> A hot water tank that stores heated water for later use.
* DHWT-2 -> Another hot water tank that stores additional heated water.
* DHWT-3 -> A third hot water tank that stores more heated water.
* Storage Tank PVI (950L) -> A large storage tank with a capacity of 950 liters.
* Electric Tank PVI (950L) 54 KW -> An electric tank with a capacity of 950 liters and a power rating of 54 kW.
* Mech Rm Fan Status -> A fan status indicator located in the mechanical room.
* Kitsilano Pool -> A pool that utilizes the domestic hot water system.

This diagram provides a comprehensive overview of the domestic hot water system, highlighting its key components and their roles in providing hot water for domestic use.

Figure CS19.2 Schematic diagram of Kitsilano Pool domestic hot-water system (Image Credit: First Light Energy Solutions).

The system is equipped with a large number of temperature sensors to facilitate troubleshooting and characterize system operation. Used as a proof of concept, the city has since implemented similar central HPWH systems in other city-owned buildings. Monitoring of the system operation over the past two summers has indicated that the system has a lot of extra capacity. The next project on-site involves expanding the DHW system to heat pool makeup water and reduce GHG emissions from the natural gas boilers used to heat the pool.

## References

Glossary

Glossary

Glossary ter.energy.gov/sites/default/files/attachments/Decarbonizing%20HVAC%20and%20Water%20Heating%20in%20Commercial%20Buildings%2011.21.pdf. DOE. 2022a. Better Buildings: Fact Sheet—LED Troffer Retrofit Lighting and Controls Best Practices. Washington, D.C.: U.S. Department of Energy. https://betterbuildingssolutioncenter.energy.gov/sites/default/files/attachments/LED-Troffer-Retrofit-Best-Practices.pdf. DOE. 2022b. DOE Announces Breakthrough in Residential Cold Climate Heat Pump Technology. Washington, D.C.: U.S. Department of Energy. https://www.energy.gov/articles/doeannounces-breakthrough-residential-cold-climate-heat-pump-technology. DOE. 2023a. Better Buildings Decarbonization Resource Hub. Washington, D.C.: U.S. Department of Energy. https://betterbuildingssolutioncenter.energy.gov/carbon-hub. DOE. 2023b. Better Buildings: Decarbonizing the Commercial Kitchen. Washington, D.C.: U.S. Department of Energy. https://betterbuildingssolutioncenter.energy.gov/technology-info-suite/ decarbonizing-commercial-kitchen. DOE. 2023c. Better Buildings: Financing Navigator—Connect with Financial Allies. Washington, D.C.: U.S. Department of Energy. https://betterbuildingssolutioncenter.energy.gov/financingnavigator/allies DOE. 2023d. Better Buildings: Financing Navigator—What is Loan or Debt Financing? Washington, D.C.: U.S. Department of Energy. https://betterbuildingssolutioncenter.energy.gov/financing-navigator/option/loan-or-debt-financing. DOE. 2023e. Better Buildings: Framework for Greenhouse Gas Emissions Reduction Planning: Building Portfolios. Washington, D.C.: U.S. Department of Energy. https://betterbuildingssolutioncenter.energy.gov/sites/default/files/attachments/ERP_Framework_Building_Portfolios.pdf. DOE. 2023f. Better Buildings: GHG Emissions Reduction Audit: A Checklist for Owners. Washington, D.C.: U.S. Department of Energy. https://betterbuildingssolutioncenter.energy.gov/ sites/default/files/attachments/Emissions_Reduction_Audit_Checklist.pdf. DOE. 2023g. Better Buildings: Low Carbon Technology Strategies Toolkit. Washington, D.C.: U.S. Department of Energy. https://betterbuildingssolutioncenter.energy.gov/toolkits/low-carbon-technology-strategies-toolkit. DOE. 2023h. Better Buildings: Technology Information Suites. Washington, D.C.: U.S. Department of Energy. https://betterbuildingssolutioncenter.energy.gov/technology-informationsuites. DOE. 2023i. Better Buildings: Upgrading Commercial Laundry Facilities. Washington, D.C.: U.S. Department of Energy. https://betterbuildingssolutioncenter.energy.gov/toolkits/upgradingcommercial-laundry-facilities. DOE. 2023k. Energy Saver: Heat Pump Water Heaters. Washington, D.C.: U.S. Department of Energy. https://www.energy.gov/energysaver/heat-pump-water-heaters. DOE. 2023l. Energy Saver: Insulation. Washington, D.C.: U.S. Department of Energy. https:// www.energy.gov/energysaver/insulation. DOE. 2023m. Energy Saver: Solar Swimming Pool Heaters. Washington, D.C.: U.S. Department of Energy. https://www.energy.gov/energysaver/solar-swimming-pool-heaters. DOE. 2023n. FEMY: Future and Extreme Weather Data. Washington, D.C.: U.S. Department of Energy. https://www.energy.gov/sites/default/files/2023-05/bto-peer-2023-35563-futureweather-anl-muehleisen.pdf. DOE. 2023o. Office of Energy Efficiency and Renewable Energy. Washington, D.C.: U.S. Department of Energy. www.energy.gov/eere/solar/how-does-solar-work. DOE. 2023p. Office of Energy Justice and Equity: Justice40 Initiative—Climate and Economic Justice Screening Tool. Washington, D.C.: U.S. Department of Energy. https:// www.energy.gov/justice/justice40-initiative.

Glossary

Glossary

Glossary

Glossary

### Understanding Commercial and Multifamily Building Decarbonization Retrofits

Decarbonizing existing buildings is a crucial step toward reducing global greenhouse gas emissions and combating climate change. Building Decarbonization Retrofits for Commercial and Multifamily Buildings is an essential resource for professionals and decision-makers in the building industry, offering clear pathways to decarbonizing existing commercial and multifamily properties.

This guide is organized to take the reader on a path through a decarbonization project, including goal setting, planning, identifying strategies, implementation, metric tracking, financing, and specific considerations for existing buildings. The guide details the best practices for developing and conducting decarbonization retrofits for commercial and multifamily buildings.

Key features of this guide include:

- 19 case studies showcasing diverse building types, systems, and decarbonization approaches
- Actionable steps for each phase of a decarbonization project, from goal setting to implementation
- Practical guidance on retrofitting HVAC systems, optimizing building envelopes, and utilizing renewable energy technologies

• Expert recommendations on monitoring and tracking progress to ensure long-term success

By embracing these strategies, building owners and operators can not only reduce carbon emissions but also lower operating costs, improve occupant health, and contribute to a more sustainable future.

ISBN 978-1-955516-75-4 (paperback)

ISBN 978-1-955516-76-1 (PDF)

Product Code: 90486 02/25
