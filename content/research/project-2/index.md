---
title: ""
summary: "A brief summary of the project."
type: research
---
<!-- <h2 style="font-weight: normal">Background</h2>
Over the course of the last two decades, it became progressively clear that physical, i.e.
mechanical forces play a major role in cellular decision making and aid in regulating important
physiological processes like tissue growth and morphogenesis. To actively generate forces, cells
use a highly complex and self-organized contractile structure called the actin cytoskeleton which
allows them to explore the mechanical and geometric properties of their environment through cell-
matrix and cell-cell adhesions. These informations are then fed back to the cell, and evaluated by
means of chemical signals a process which is known as mechanotransduction. Although research
has yielded many new insights in recent years it is still puzzling how cells integrate information
from their environment into their decision-making process. Therefore, it is important to study how
cells generate forces, how the internal molecular machinery regulates them, and how these forces
transmit information in multicellular systems to understand processes such as development,
organogenesis, homeostasis or diseases like cancer. -->

### <h2 style="font-weight: normal">Optogenetic control of cell contarctility and force propagation</h2>
<div style="display: flex; flex-wrap: wrap; gap: 1rem; align-items: center;">

  <!-- Left: Image -->
  <div style="flex: 1.5; min-width: 300px;">
    <img 
      src="/uploads/coupling_mechanism.svg"
      alt="Cell pushing schematic"
      style="width: 100%; height: auto;">
  </div>

  <!-- Right: Column with top movie and bottom row -->
  <div style="
    flex: 1.5; 
    min-width: 300px; 
    display: flex; 
    flex-direction: column; 
    gap: 1rem;
  ">
    <!-- Top: Overview Movie spanning full width -->
    <div>
      <h4>Overview Movie</h4>
      <video controls style="width: 100%; height: auto; display: block;">
        <source src="/uploads/MovieOptoArrow.mp4" type="video/mp4">
      </video>
    </div>
    <!-- Bottom: Row with 2 movies side by side -->
    <div style="display: flex; flex-wrap: wrap; gap: 1rem;">
      <div style="flex: 1; min-width: 100px;">
        <h4>Weak Coupling</h4>
        <video controls style="width: 100%; max-width: 200px; height: auto; display: block;">
          <source src="/uploads/MovieS1_doublet_weak_coupling.mp4" type="video/mp4">
        </video>
      </div>
      <div style="flex: 1; min-width: 100px;">
        <h4>Strong Coupling</h4>
        <video controls style="width: 100%; max-width: 200px; height: auto; display: block;">
          <source src="/uploads/MovieS2_doublet_strong_coupling.mp4" type="video/mp4">
        </video>
      </div>
    </div>
  </div>

</div>






<!-- - Lists
- **Bold text**
- *Italic text*
- Images
- 
{{< math >}}
$$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$
{{< /math >}} -->
<!-- $$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$ -->
