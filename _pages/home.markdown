---
title: "Welcome to ArchSec"
permalink : /
layout: home
author: Bernhard Berger
author_profile: true
---
<style>
.column {
  float: left;
  width: 33.33%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>


Welcome to the home of *ArchSec*. *ArchSec* is the *Architectural Security Tool
Suite* that automates Microsoft's Threat Modeling and makes architectural risk
analysis more user-friendly. Therefore, it supports three key features:

<div class="row">
  <div class="column">
*ArchSec* employs more formal dataflow diagrams for representing architectural
views of software systems. The core of these extended dataflow diagrams is its
extensible schema, allowing them to define new node and edge types and specify
implied attributes of such types. 
  </div>
  <div class="column">
*ArchSec* uses static analysis to (semi-)automatically extended dataflow
diagrams of existing software systems, making it easier to start architectural
risk analysis for existing systems. Furthermore, the extracted extended dataflow
diagram reflects the actual system, and there is no gap between the planned 
architecture and the implemented one.
  </div>
  <div class="column">
*ArchSec* collects formalised threat descriptions in a knowledge base and
automatically detects these threats in extended dataflow diagrams. The knowledge
base allows non-security experts to use architectural risk analysis. Still, it
offers advantages for security experts since not all security experts know all
aspects of security equally well. 
  </div>
</div>