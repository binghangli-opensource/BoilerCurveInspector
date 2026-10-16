# Third-party notices — Boiler Curve Inspector

Boiler Curve Inspector application code is MIT licensed by Binghang Li. Third-party records and adapted code retain the licenses below; they are not relicensed wholesale as MIT.

## OpenStudio(R) Standards
Repository: https://github.com/NatLabRockies/openstudio-standards
Source commit: 5cf341742b28dc24dad09983f16ef27a1d12b4dd
License: licenses/OpenStudio-Standards.txt (complete, unmodified upstream text).
Imported: DOE Ref Pre-1980 constant-efficiency records; 90.1-2016 thermal-efficiency records and cubic curves; ECMS generic efficiency packages and CT3-17 analysis fit.
The CT3-17 fit is credited upstream to Kamel Haddad. Original manufacturer samples, analysis report, nominal anchor and heat-value basis have not been independently verified; 96.2% is retained as the OpenStudio reference. Generic ECMS packages share a curve.
Boiler Curve Inspector is an independent product adapted using data from OpenStudio(R). No institutional or manufacturer endorsement is claimed. OpenStudio(R) naming and non-endorsement terms apply.

## LBL Modelica Buildings
Repository: https://github.com/lbl-srg/modelica-buildings
Source commit: 11e34d2187abaac63d5b63b269a7e16543403441
License: licenses/Modelica-Buildings.html (complete, unmodified upstream text).
Imported: the Lochinvar Crest family efficiency table and FB-2501/3001/3501/4001/5001/6001 heating capacities.
Copyright holders and contributors are identified in the complete license.
Enhancements paragraph retained: it imposes no obligation to provide fixes, patches or upgrades. It provides an automatic non-exclusive, royalty-free, perpetual license to use, modify, incorporate, distribute and sublicense qualifying Enhancements when made public or supplied directly to LBL without a separate written license agreement. Project-authored Community adaptations are released under the stated MIT terms; upstream materials retain their complete original license. No mandatory contribution or separate submission to LBL is stated in this paragraph.
Adaptations: K to °C conversion; bilinear interpolation; firing fraction to output-PLR conversion; separately labelled approximate EnergyPlus fit.
Additional project estimates: the Crest table seeds explicitly assumed dry-recovery and normalized residual-recovery transformations. Relative transfer indices are not measured UA or manufacturer-certified curves. The original table remains distinct; generated scenarios and constrained export fits are labelled ILLUSTRATIVE.
The six capacities share a family table. This is not six separately measured performance maps. No LBL, DOE, OpenStudio or manufacturer certification/endorsement of Boiler Curve Inspector is claimed.

## EnergyPlus
Repository: https://github.com/NatLabRockies/EnergyPlus
Version: v25.2.0
License: licenses/EnergyPlus.txt (complete, unmodified upstream text).
Imported: datasets/Boilers.idf CondensingBoilerEff, nominal efficiency 0.89, inlet-temperature convention and bounds.
Boiler Curve Inspector is not an EnergyPlus release. EnergyPlus naming and non-endorsement terms apply.

## NECB independent numerical implementation
Necessary numerical coefficients and mathematical relationships are independently implemented and attributed to NECB 2020 Division B 8.4.5.2 and NECB 2025 Division B 8.4.6.2.
Original explanatory text, tables as laid out in the publication, screenshots and PDFs are not bundled.
NRC publications retain their copyright. No NRC open-source license or permission to republish the complete publication is claimed.
Project-authored code, explanations, calculated plots and fitted coefficients are distinguished from the original reference relationships.
Official sources:
https://nrc-publications.canada.ca/eng/view/ft/?id=af36747e-3eee-4024-a1b4-73833555c7fa
https://publications.gc.ca/collections/collection_2026/cnrc-nrc/NR24-24-2025-eng.pdf

## External browser resources
The page loads Plotly.js 2.29.1 (MIT) and Google Fonts through their respective CDNs. The single-file page still requires network access for these external resources.
Plotly.js: https://github.com/plotly/plotly.js/tree/v2.29.1
Font families: Google Sans Flex and Google Sans Code, loaded by the existing page.

## Distribution
Retain these notices and the complete upstream license texts with source and HTML releases.
The complete imported licenses are also embedded in the HTML license panel.
