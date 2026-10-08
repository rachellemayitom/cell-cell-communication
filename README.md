# Cell-to-Cell Communication: CCL4–CCR5 Signaling

## 1. Biological Question

How can a monocyte communicate with a macrophage through the CCL4–CCR5 signaling pathway during inflammatory signaling?

## 2. Chosen Sender Cell and Biological Context

The selected sender cell is the **monocyte**, with **inflammation** as the biological context. Monocytes are immune cells that participate in inflammatory responses and can produce signaling molecules that communicate with other immune cells.

## 3. Candidate Ligand and Evidence for Sender-Cell Expression

The selected signaling molecule is **CCL4 (C-C motif chemokine ligand 4)**.

The Human Protein Atlas (HPA) identifies CCL4 as a **secreted** protein and shows cell-type-enhanced expression in **monocytes**, supporting its association with the selected sender cell. HPA also provides evidence at the protein level and predicts CCL4 to be secreted.

## 4. Receptor and Receiver Cell

The selected receptor is **CCR5 (C-C motif chemokine receptor 5)**.

OmniPath shows a signaling interaction from **CCL4 to CCR5**, with stimulation and multiple supporting references. The Human Protein Atlas identifies CCR5 as a membrane protein and shows enrichment in immune cell types including **macrophages**.

Therefore, the proposed receiver cell is the **macrophage**.

## 5. OmniPath Findings

OmniPath identifies CCL4 as a **secreted ligand** involved in intercellular communication. The CCL4–CCR5 interaction is listed as a stimulatory interaction with multiple supporting references.

## 6. STRING Network Interpretation

The STRING network centered on CCL4 and CCR5 includes signaling-associated proteins such as **GNAI1, GNB1, and GNG2**. These proteins are components of heterotrimeric G-protein signaling associated with G-protein-coupled receptors such as CCR5. The network supports a connection between receptor signaling and downstream cellular responses, although STRING associations represent functional associations and do not necessarily indicate direct physical interactions.

## 7. IntAct Validation

The CCL4–CCR5 pair did not provide a useful curated IntAct record for the proposed interaction. An additional interaction involving **GNB1 and GNAI1** was examined. IntAct reported a positive physical association detected using **3D electron microscopy (3d-em)** in *Homo sapiens*, with publication PMID **35501348**.

This evidence supports a physical association between GNB1 and GNAI1, but it does not by itself prove the complete CCL4–CCR5 signaling pathway.

## 8. Final Model

The proposed cell-to-cell communication model is:

**Monocyte → CCL4 → CCR5 → Macrophage → G-protein signaling → Chemotaxis / inflammatory response**

![Final CCL4-CCR5 Cell-to-Cell Communication Model](figures/05_final_model.png)

**Figure 1.** Proposed cell-to-cell communication model showing CCL4 signaling from a monocyte to a macrophage through the CCR5 receptor and downstream intracellular signaling components.

### Interpretation

The proposed cell-to-cell communication model connects a monocyte sender cell to a macrophage receiver through the secreted chemokine CCL4. Human Protein Atlas evidence supports CCL4 as a secreted protein and shows cell-type-enhanced expression in monocytes, providing evidence for its association with the sender cell. OmniPath further supports the signaling model by annotating CCL4 as a secreted ligand and identifying a stimulatory CCL4–CCR5 interaction with multiple references. HPA evidence also supports CCR5 as a membrane receptor associated with macrophages, making the macrophage a biologically reasonable receiver cell. The STRING network identifies CCL4, CCR5, GNAI1, GNB1, and GNG2 as functionally associated proteins, providing a possible connection between receptor activation and intracellular signaling. However, STRING associations do not necessarily represent direct physical interactions or prove pathway direction. IntAct provided experimental evidence for a physical association between GNB1 and GNAI1 using 3D electron microscopy. Overall, the ligand, receptor, and protein-network components are supported by database evidence, while the specific monocyte-to-macrophage communication and resulting chemotactic response remain a biologically supported inference.

## 9. References and Database Links

- Human Protein Atlas: https://www.proteinatlas.org/
- OmniPath: https://omnipathdb.org/
- STRING: https://string-db.org/
- IntAct: https://www.ebi.ac.uk/intact/
- UniProt: https://www.uniprot.org/
