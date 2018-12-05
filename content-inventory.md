# 2.2 HPD Open Standard Format Section 2: Content in Descending Order of Quantity

- [Overview](#overview)
- [Material](#material)
    - [General Information on Materials](#material-general)
    - [Material Name](#material-name)
    - [Percent](#material-percent)
    - [HPD URL](#material-url)
    - [Inventory Threshold](#material-threshold)
    - [Residuals/Impurities](#material-residuals)
    - [Material Notes](#material-notes)
- [Substance](#substance)
    - [General Information on Substances](#substance-general)
    - [Substance Name](#substance-name)
    - [Identifier](#substance-identifier)
    - [Percent](#substance-percent)
    - [GreenScreen](#substance-greenscreen)
    - [Recycled content](#substance-content)
    - [Nano](#substance-nano)
    - [Role](#substance-role)
    - [Hazards, Agency(ies) with Warnings](#substance-hazards)
    - [Substance Notes](#substance-notes)

<a name="overview"></a>
## HPD Open Standard Format Section 2 Overview

This section characterizes the materials in a product (Material) and the substances of which each material is composed (Substance). The guidance below is for general situations. Refer to Variations, Special Conditions for Materials and Substances [See 3.5] for further guidance on special circumstances associated with specific materials and substances.

<a name="material"></a>
## 2.2.1 Material

<a name="material-general"></a>
### General Information on Materials

The Content Inventory must include every material that is part of the product as delivered. Each material must have its own line item entry, regardless of the extent of further inventory at the substance level. For example, a coating or finish must be itemized as a distinct material, whether present on a supplied part or added by the manufacturer producing the HPD, whereas supplied materials that do not remain distinct in the finished product are not inventoried separately (e.g., solution dyes for fabrics). Packaging materials that are removed from the product prior to use and materials that are attached to or part of the product for identification purposes only (e.g., tags, stamps, other identifiers) are excluded from inventory requirements. Accessories are not included as part of the Content Inventory and are instead included in HPD Format Section 4 [See 2.4 for further guidance].

Materials are listed in descending order of quantity in the product.

<a name="material-name"></a>
### 2.2.1.1 Material Name

*Title of the Material.* Options include:

* the material’s specific name (brand),
* a generic name (category/family),
* “Undisclosed.”

If “Undisclosed,” the rationale for nondisclosure is explained in the Material Notes [See 2.2.1.6].

<a name="material-percent"></a>
### 2.2.1.2 Percent (%)

*Material's percentage in the final product by weight.* This is a characteristic of the product rather than the material; it is assigned when the material is added to the product inventory. A fixed percentage is preferred, however, a percentage range may be provided (e.g., 3.0 – 14.5%). An average or typical percentage may be included in the Material Notes [See 2.2.1.6] with an explanation of how the average was derived. Ranges should not exceed 20%. If a range does exceed 20%, the reason for the large range must be described in the Material Notes [See 2.2.1.6] for a product to be identified as “Characterized.”

* Ranges, variable amounts over time: If the percentage of the material varies over time due to market availability, pricing or other factors, an explanation must be provided in the Material Notes [See 2.2.1.6].
* Ranges, similar products: If the HPD is being used to describe several products that are generally similar in content but differ in the percentages of some materials, an explanation must be provided in the Material Notes [See 2.2.1.6]. Refer to Variations, Listing Multiple Products in a Single HPD [See 3.1] for further guidance.
* Alternate: If the entry is for a substitute material (such as different species of wood used as a veneer), “Alternate” is indicated. As long as the primary material for which it is an alternate has a disclosed percent or percent range, “Alternate” is sufficient for disclosure of percentage for this material. Refer to Variations, Alternate Materials or Substances [See 3.2] for further guidance on alternate contents.
* Undisclosed: If the percentage is withheld, “Undisclosed” must be entered with an explanation of why this information is withheld in the Material Notes [See 2.2.1.6]. The product cannot be identified as “Characterized” if the percentage of any material in the product is “Undisclosed.”

<a name="material-url"></a>
### 2.2.1.3 HPD URL

*Functional website link to an HPD for the material (if one exists).* If a URL is provided for an HPD of the material, substance level information must still be itemized on the Product’s HPD unless one of the following exceptions apply:

* The material is listed on the Product HPD as an Alternate (see 3.2 Variations, Alternate Materials or Substances).
* The HPD references a Special Condition HPD for this material that the HPD Collaborative has provided for the material type [see 3.5].

For the above exceptions, if a URL is provided, substance and hazard information is not itemized on the Product’s HPD and users are directed to the Material HPD for related details.

<a name="material-threshold"></a>
### 2.2.1.4 Inventory Threshold

*Concentration above which substances present within the material are itemized by the manufacturer (or supplier as applicable).* Options include:

* **100 ppm:** Inventory includes substances at or above 100 ppm (0.01%) concentration in a material.
* **1,000 ppm:** Inventory includes substances at or above 1,000 ppm (0.1%) concentration in a material.
* **Per GHS SDS<sup>11</sup>:** Inventory of substances in a material meets the level of resolution required for Safety Data Sheets as prescribed by the Globally Harmonized System of Classification and Labeling of Chemicals (GHS)<sup>12</sup>: substances that are identified as health hazards are disclosed at 1,000 ppm (0.1%) for reproductive toxicants, carcinogens, and category 1 mutagens, and at 10,000 ppm (1%) for all other hazard categories.
* **Per OSHA MSDS:** The Occupational Safety and Health Administration (OSHA) MSDS threshold is a transitional option for HPD v2.0<sup>13</sup>. Inventory of substances in a material meets the level of resolution required for Material Safety Data Sheets as prescribed by OSHA: substances identified as health hazards per CFR 1910.1200 are disclosed at 1,000 ppm (0.1%) for carcinogens, and at 10,000 ppm (1%) for all other hazard categories.
* **Other:** Inventory of substances in a material is based on a completely different protocol, or has more or less stringent thresholds than any of those described above. When selected, an explanation must be provided in either the Inventory and Screening Notes or the Material Notes.

The identified inventory threshold always applies to intentionally used substances intended to be constituents of a material and intended reaction products. If residuals and impurities are considered [See 2.2.1.5], the inventory threshold also applies to substances that, while not intended constituents of a material, are known - or have the potential - to be present at or above the selected threshold. Refer to Glossary [See 5] for definitions.

Only one threshold may be indicated per material. If inventory data for the substances within a single material are obtained at multiple threshold levels, the least stringent threshold must be indicated, with further explanation in the Material Notes [See 2.2.1.6].

<a name="material-residuals"></a>
### 2.2.1.5 Residuals/Impurities

*Indication of whether residuals and impurities are considered for the material and included in the inventory.* Options are either “Considered” or “Not Considered”.

When Residuals/Impurities are “Considered,” the manufacturer has taken steps - such as those outlined in Emerging Best Practices - to understand what residuals and impurities may be present in the material and disclose that information on the HPD. The term “Considered” is used, rather than “Included,” to address currently unavoidable variability in methodology and rigor due to industry sector differences in knowledge about residuals and impurities in materials used. Guidance related to considering, identifying and quantifying residuals and impurities is documented on the HPD Collaborative website as Emerging Best Practices.

Whether “Considered” or “Not Considered” is indicated, an explanation must be provided. Related information that applies to more than one material may be indicated in HPD Format Section 5: General Notes [See 2.5]. Use the Material Notes for related information if some materials are “Considered” and others are “Not Considered” or if different methodologies are used for different materials.

* If “Not Considered” is indicated, an explanation must be provided as to why the manufacturer has not considered residuals and impurities.
* If “Considered” is indicated,
    * An explanation must be provided in HPD Format Section 5: General Notes [See 2.5] or in the respective Material Notes [See 2.2.1.6] for each material describing the methodology employed to identify residuals and impurities.
    * Any identified residual or impurity that is known or has the potential to be present in the material or above the Content Inventory Threshold must be listed in HPD Format Section 2: Content in Descending Order of Quantity as an individual line item entry. If the manufacturer can demonstrate (via testing or estimation, based on the current version of Emerging Best Practices on the HPD website ) that an identified residual is not present at or above the indicated threshold, the residual does not need to be listed as a line item in the inventory but an explanation of the rationale must be provided in the Material Notes [See 2.2.1.6]. While it is acceptable to indicate that residuals and impurities have been “Considered” when no identified residuals are listed as line items, a thorough methodological explanation in the Material Notes [See 2.2.1.6] must clearly justify this determination.

Note: When content inventory is documented as per OSHA MSDS or GHS SDS, it is possible that residuals and impurities are listed without distinction or may not be included. If additional reactions occur during subsequent manufacturing processes, a MSDS or SDS may not capture all contents in the final material, but the information may still be useful to help indicate potential residuals.

<a name="material-notes"></a>
### 2.2.1.6 Material Notes

*Explanation of the material’s characteristics.*

The required entries are:

* explanation or rationale for nondisclosure if Material Name [See 2.2.1.1] is
“Undisclosed;”
* explanation for ranges, alternates and undisclosed material percentage as required in 2.2.1.2 Percent (%);
* explanation when "Other" is indicated for Inventory Threshold [See 2.2.1.4], unless provided in the Inventory and Screening Notes;
* explanation when inventory data for substances within a single material are obtained at multiple threshold levels;
* explanations for residuals and impurities as required in 2.2.1.5 Residuals/Impurities, unless provided in the General Notes;
* explanation of variations among different products listed in a single HPD [See 3.1], if not addressed in Substance Notes [See 2.2.2.9] or General Notes [See 2.5].

Optional entries include:

* identification of primary materials that may be replaced by alternate materials [See 3.2],
* if the product varies in composition because there are multiple alternate suppliers for a single material or substance [See 3.3]. Ranges for substances’ percent weight may be provided with an explanation of how the supply chain has influenced disclosure methods,
* references to reports or other published literature about exposure, risk or other qualities specific to the material in the product that may be relevant to understanding the context for its use.

<hr>

<a name="substance"></a>
## 2.2.2 Substance

<a name="substance-general"></a>
### General Information on Substances

Each substance in a material is included with its own line item entry. Substances should be listed in descending order of quantity within the material.

<a name="substance-name"></a>
### 2.2.2.1 Substance Name

*Title of the substance.* Options include the substance’s specific name, generic name, “Undisclosed” or “Unknown.”

* If the manufacturer chooses to identify the substance to a lesser degree of specificity, a generic name or chemical class may be indicated in its place.
* If the manufacturer chooses not to disclose the name of the substance in any fashion, “Undisclosed” must be indicated, with explanation of the rationale for nondisclosure in the Substance Notes [See 2.2.2.9], and the product cannot be indicated as “Identified” [See 2.2.2.2] unless specifically allowed by the instructions in Variations, Special Conditions for Materials and Substances [See 3.5].
* If the manufacturer does not know the substance name, “Unknown” must be indicated. This is possible when the material supplier has passed on content characteristics to the product manufacturer for inclusion in the HPD, but has redacted certain details. Efforts undertaken to identify the substance must be explained in the Substance Notes [See 2.2.2.9], and the product cannot be indicated as “Identified” [See 2.2.2.2] unless specifically allowed by the instructions in Variations, Special Conditions for Materials and Substances [See 3.5].

<a name="substance-identifier"></a>
### 2.2.2.2 Identifier

*Chemical Abstract Service Registration Number (CAS RN or CAS number) or other substance identification<sup>14</sup>.* Refer to Glossary [See 5] for definition. Refer to Variations, Special Conditions for Materials and Substances [See 3.5] for further guidance on identifiers other than CAS numbers.

* “Undisclosed” indicates that the manufacturer knows the identifier and chooses not to disclose. The rationale for non-disclosure must be explained in the Substance Notes [See 2.2.2.9] and the product cannot be indicated as “Identified” [See 2.2.2.2] unless specifically allowed by the instructions in Variations, Special Conditions for Materials and Substances [See 3.5].
* “Unknown” indicates that the manufacturer does not know the chemical identity. An explanation of why it is unknown and manufacturer efforts to identify it must be included in the Substance Notes [See 2.2.2.9], and the product cannot be indicated as “Identified” [See 2.2.2.2] unless specifically allowed by the instructions in Variations, Special Conditions for Materials and Substances [See 3.5].
* If more than one identifier has been assigned to this substance, other relevant identifiers may be listed in the Substance Notes [See 2.2.2.9].
* “Not registered” indicates no CAS number or other identifier has been registered for this substance.

<a name="substance-percent"></a>
### 2.2.2.3 Percent (%)

*Substance's percentage in the material by weight.* For the following instances, the same guidance applies as for “Percent” (%) [See 2.2.1.2] in the Material section above, with explanation entered in the Substance Notes [See 2.2.2.9] instead of the Material Notes [See 2.2.1.6]:

* ranges, variable amounts over time;
* ranges, similar products;
* alternate substances;
* undisclosed.

If “Undisclosed” is selected for any substance in the product, the product may not be indicated as “Characterized” [See 2.1.2.3].

<a name="substance-greenscreen"></a>
### 2.2.2.4 GreenScreen (GS)

*Benchmark or List Translator scores.* Options from highest to lowest concern are: BM-1, LT- 1, LT-P1, LT-UNK, UNK, BM-U, BM-2, BM-3, BM-4. Refer to References [See 2.6.2.2] for definition and an explanation of each score.

Substances that are present on one or more screening or authoritative hazard list are assigned a List Translator score (“LT-1” or “LT-P1”or “LT-UNK”). Substances not present on any list are assigned an “UNK” score. A full GreenScreen assessment is not required to generate a List Translator score. If the substance has received a full GreenScreen assessment published in the Pharos Chemical and Material Library, the Benchmark score is indicated instead of the List Translator score, with explanation in the Substance Notes [See 2.2.2.9], of the source of the full GreenScreen assessment. Any certified full GreenScreen assessment that is completed by a Licensed GreenScreen Profiler and licensed for public use may be submitted for inclusion in the Pharos Chemical and Material Library at no cost. Refer to Variations, Special Conditions for Materials and Substances [See 3.5] for further guidance about Form Specific Hazards.

A GreenScreen assessment certified by a Licensed GreenScreen Profiler for which the manufacturer holds license to make public claims, but which is not published in the Pharos Chemical and Material Library, may be listed in the Substance Notes [2.2.2.9]. Include the GreenScreen Benchmark, the name of the Licensed GreenScreen Profiler certifying the assessment, and the date of the assessment. For example: “This substance was assigned GreenScreen Benchmark 3 by Licensed GreenScreen Profiler xxxx on March 3, 2015.”

<a name="substance-content"></a>
### 2.2.2.5 RC: Recycled content

*Indication of whether the substance was diverted from a waste stream for use in the material.*

* For substances with recycled content, “PostC” indicates postconsumer recycled content, and “PreC” indicates preconsumer (post-industrial) recycled content. Refer to Glossary [See 5] for definitions.
* “Both” indicates the substance includes both postconsumer and preconsumer (post- industrial) recycled content.
* “None” indicates the substance does not include pre- or postconsumer recycled content.
* “Unk” indicates the inclusion of recycled content is unknown.

For each substance with recycled content, the Substance Notes [See 2.2.2.9] must indicate the type of product(s) from which the recycled content is obtained. (Example: for postconsumer recycled high-density polyethylene, the Substance Notes would document sourcing as from recycled milk bottles, grocery bags, or other products.) Refer to Variations, Special Conditions for Materials and Substances [See 3.5] for further guidance about substances that include recycled content of mixed composition.

<a name="substance-nano"></a>
### 2.2.2.6 Nano

*Indication of whether the substance is a nanomaterial.* Refer to Glossary [See 5] for definition.

* “YES” indicates the substance is a nanomaterial.
* “NO” indicates it is not a nanomaterial.
* “UNK” indicates that it is unknown whether the substance is a nanomaterial or not.

<a name="substance-role"></a>
### 2.2.2.7 Role

*Brief phrase that captures the substance’s purpose or function for inclusion in the material.*

Examples include: "binder," "anti-microbial," "flame retardant," "wear layer," "catalyst," "preservative," etc. Further explanation of a particular substance can be included in the Substance Notes [See 2.2.2.9]. The role for each substance must be identified in order for the product to be indicated as “Characterized” [See 2.1.2.3].

<a name="substance-hazards"></a>
### 2.2.2.8 Hazards, Agency(ies) with Warnings

Hazard types, agencies, and warnings associated with a substance as identified by the Health Product Declaration Priority Hazard Lists. Each substance must be screened against the Priority Hazard Lists to determine if the substance is listed. The required Priority Hazard Lists are identified in Appendix D - HPD Priority List Sources. Some lists address multiple hazard types. Refer to Appendix E - HPD Priority List Warnings for the list of the Hazard Warnings required to be scanned when screening a substance.

If the substance is listed, indicate the associated Hazard Type under Hazards, and the Agency List Abbreviation and Hazard Warning separated by a colon (“:”) under Agencies with Warnings as per the standardized forms in Appendix E - HPD Priority List Warnings. There must be a separate line item entry for each Hazard Type for which a substance is listed. If there is more than one Agency and Warning related to a single Hazard Type, add “also in” followed by each of the relevant Agency List Abbreviations.

* Hazard type, agency, and warning information may be manually compiled or obtained through an automated compilation tool. Use of a comprehensive automated compilation tool is recommended to ensure these associations are made accurately and efficiently. The compilation method used to identify hazard type, agency, and warnings must include all relevant information from each of the HPD Priority Hazard Lists. If it does not, the manufacturer must insert information from missing lists. It is the manufacturer’s responsibility to confirm that the compilation method selected is current and comprehensive and that information in the tool is updated at least annually.
* If the substance is not present by name or CAS number on any of the Priority Hazard Lists, then a search by synonyms (name or additional CAS numbers) must be conducted. If still not found, “None found” is indicated for Hazards and “No warnings found on HPD Priority Hazard Lists” is indicated for Agency(ies) with Warnings.
* If a single List has shown that there are multiple hazard types for a substance, but has not specified which particular hazard types apply, “Multiple” is indicated for the Hazards.
* Hazards, agencies, and warnings, if any, must be provided for all known and itemized substances, regardless of whether the substance’s name and CAS number have been disclosed. Confidential Business Information status is not an acceptable reason to avoid disclosure of hazards, agencies, and warnings.
* If the substance identity is proprietary to a supplier and neither the identity nor the hazard, agency, and warning information have been disclosed to the manufacturer, “Unknown” is indicated for Hazard, and “Not disclosed by supplier” is indicated for Agency(ies) with Warnings. An explanation must be provided in the Substance Notes [See 2.2.2.9] regarding efforts to obtain this information from the supplier.
* Refer to Variations, Special Conditions for Materials and Substances [See 3.5] for further guidance about how hazard types, agencies, and warnings are documented in certain specific instances.

<a name="substance-notes"></a>
### 2.2.2.9 Substance Notes

*Explanation of the substance’s characteristics.*

Required entries are:

* explanation if Substance Name [See 2.2.2.1] and Identifier [See 2.2.2.2] are
“Undisclosed” or “Unknown.” The manufacturer must explain the rationale for nondisclosure for “Undisclosed” substances and efforts undertaken to identify “Unknown” substances. The manufacturer is encouraged to indicate if there is a time horizon for the non-disclosure (e.g., a pending patent application filing or other limited time intellectual protection or market advantage issue), and the existence of and time limits associated with a non-disclosure agreement (NDA) in place with the supplier; additional CAS numbers, if the substance can be identified by multiple CAS numbers;
* explanation if GreenScreen assessment is referenced which is not published in Pharos Chemical and Material Library [see 2.2.2.4];
* explanation for ranges, alternates and undisclosed substance percentage as required in 2.2.2.3 Percent (%);
* explanation of source if GreenScreen response is a Benchmark score from a full GreenScreen assessment.) [See 2.2.2.4];
* description of recycled content, if applicable [See 2.2.2.5];
* "Exempt VOC" if the substance is an EPA exempt VOC [See 2.1.4.3];
* explanation of variations among different products listed in a single HPD [See 3.1], if not addressed in Material Notes [See 2.2.1.6] or General Notes [See 2.5].

Optional entries include:

* other relevant identifiers, if more than one identifier has been assigned to this substance [See 2.2.2.2];
* further explanation of role of a substance [See 2.2.2.7];
* identification of primary substances that may be replaced by alternate substances [See 3.2];
* references to reports or other published literature about exposure or risk or other qualities specific to the substance that may be relevant to understanding the context for its use;
* positive listings, which are encouraged, such as if a substance is present on the EPA’s Safer Choice, Safer Chemical Ingredients List<sup>15</sup>.

<hr>

<div class="callout-block callout-info">
    <div class="icon-holder">
        <i class="fas fa-info-circle"></i>
    </div>
    <div class="content">
        <h4 class="callout-title">Footnotes:</h4>
        <p>[ 11 ] &nbsp; OSHA MSDS and GHS SDS are targeted toward occupational safety during manufacturing. As a result MSDS/SDS information does not always represent the actual composition of the final material (e.g., polyurethane foam). When relying on MSDS/SDS information for a material, the Material Notes [2.2.7] are used to explain instances where the contents listed in the HPD represent solely inputs to a reaction product rather than reaction products and residuals. Refer to Special Conditions [See 3.5] for further guidance.</p>
        <p>[ 12 ] &nbsp; https://www.osha.gov/dsg/hazcom/ghs.html</p>
        <p>[ 13 ] &nbsp; Once the GHS SDS officially supersedes the MSDS as OSHA’s Hazard Communication Standard, manufacturers and their suppliers who have reported to the MSDS inventory threshold are strongly encouraged to update the HPD Content Inventory accordingly. Refer to the US Department of Labor’s website for the timeline of Effective Dates. https://www.osha.gov/dsg/hazcom/effectivedates.html Please note that reporting thresholds are different under the new GHS SDS.</p>
        <p>[ 14 ] &nbsp; For example, “MATNUM” and “BIONUM” reference are identifiers assigned to a substance in the absence of another official identifier (e.g., CAS RN). The assigned identifier is cross-referenced with the Healthy Building Network’s Pharos Chemical and Material Library and available online.</p>
        <p>[ 15 ] &nbsp; http://www2.epa.gov/saferchoice/safer-ingredients</p>
    </div>
</div>
