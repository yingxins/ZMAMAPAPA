# ZMAP: Zebrafish Multi-study Atlas Project
<strong>ZMAP</strong> (<strong><u>Z</u></strong>ebrafish <strong><u>M</u></strong>ulti-study <strong><u>A</u></strong>tlas <strong><u>Z</u></strong>roject) is a single-cell RNA sequencing reference atlas for zebrafish embryogenesis developed by Wagner Lab at University of California, San Francisco, enabling robust cross-study comparison of cell identities.
ZMAP integrates eight published datasets comprising over 790,000 cells spanning 15 developmental time windows from gastrulation through larval stages with a curated hierarchical cell ontology from germ layer to high-resolution clusters. 
Through an interactive web portal, you can explore 2D and 3D UMAP embeddings, query genes, access to the consensus marker resources and project your dataset on it rapidly.

---

## ZMAP Data

### Web Portal

- **2D browser**: [<a href="https://zmap.pages.dev/">View</a>]
  [<a href="#" onclick="copyToClipboard('URL'); return false;">Copy Link</a>]<br> 
- **3D browser**: [<a href="https://zmap-3d.pages.dev/">View</a>]
  [<a href="#" onclick="copyToClipboard('URL'); return false;">Copy Link</a>]<br> 

### Download

All ZMAP reference data are publicly available as AnnData (`.h5ad`) files.


- **Raw counts**
  *(3.5 GB; raw counts)*
  [<a href="https://pub-dbadc2c623224cb58d93cfa3b950fef5.r2.dev/h5ad/ZMAP_250402_raw.h5ad">Download</a>]
  [<a href="#" onclick="copyToClipboard('URL'); return false;">Copy Link</a>]<br>
  

- **Processed (recommended)**
  *(3.5 GB; raw counts + all annotations)*
  [<a href="https://pub-dbadc2c623224cb58d93cfa3b950fef5.r2.dev/h5ad/ZMAP_251209_processed_slim.h5ad">Download</a>]
  [<a href="#" onclick="copyToClipboard('URL'); return false;">Copy Link</a>]<br>

- **Processed (full)**
  *(~25 GB; processed counts + annotations + intermediate embeddings and graphs)*
  [<a href="https://pub-dbadc2c623224cb58d93cfa3b950fef5.r2.dev/h5ad/ZMAP_251209_processed.h5ad">Download</a>]
  [<a href="#" onclick="copyToClipboard('URL'); return false;">Copy Link</a>]<br>
 

- **Symphony reference** 
  [<a href="https://pub-dbadc2c623224cb58d93cfa3b950fef5.r2.dev/h5ad/ZMAP_260103_symphony.h5ad">Download</a>]
  [<a href="#" onclick="copyToClipboard('URL'); return false;">Copy Link</a>]<br>
  
---

## Citation

If you use ZMAP in your research, please cite:

---

<script>
function copyToClipboard(text) {
  navigator.clipboard.writeText(text);
}
</script>

