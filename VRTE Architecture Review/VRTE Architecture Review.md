# VRTE Architecture Review - v1.0

- [ ] Function cluster should have an abbriviated name
- [ ] Function cluster should have description
- [ ] Function cluster should be allocated to atleast one protection domains
- [ ] Every Functional cluster should have following diagrams 
- [ ] naming convention check for FL1 - functional cluster to protection domain
- [ ] naming convention check for FL1 - protection domain
- [ ] naming convention check for FL1 - function interaction
- [ ] naming convention check for FL2 - sub function to protection domain
- [ ] naming convention check of the diagrams and elements
- [ ] Is every FunctionalCluster visible on the FunctionalCluster to Layer class diagram
- [ ] Are all FunctionalClusters allocated to a PDM on the correct “02_PDM_Func” Diagram
- [ ] whether function cluster is realized by atleast one Sw Component Cluster
- [ ] Technical Cluster Package structure verification
- [ ] Technical Cluster Package should contain only Sw Component Cluster Types. There should not be any Function Cluster or Sw Components present
- [ ] SwComponentCluster should offer atleast one interface
- [ ] Interface name should be according the naming convention defined
- [ ] Adaptive AUTOSAR interfaces should be validated against the AUTOSAR release for completeness and correctness
- [ ] Interfaces without any operations defined
- [ ] Interfaces defined but no ports created for the same in Sw Component Cluster
- [ ] The Requester contracted Interface available under the same runtime platform package
- [ ] Mandatory diagrams available in the Technical Cluster package
- [ ] diagrams or elements which contains <rename> are removed
- [ ] Description available for the exported interface
- [ ] Interface without any type defined in the methodology
- [ ] Port can have only one interface attached to it
- [ ] There are no reversed ports
- [ ] SwComponentCluster description is available.<br/>
Check for purpose
- [ ] Interface description is available<br/>
Check for purpose
- [ ] According to the naming conventions defined for TechnicalClusterPkg
- [ ] According to the naming conventions defined for platform specific packages
- [ ] According to the naming conventions defined for SwComponentCluster
- [ ] According to the naming conventions defined for Interfaces
- [ ] According to the naming conventions defined for Ports
- [ ] According to the naming conventions defined for Sub-SwComponentCluster
- [ ] All Interfaces should be modelled under the SwComponentCluster
- [ ] Dependency should be drawn from the Rport to Pport only
- [ ] Any model element that is to be clarified is attached to 'ToBeClarified' stereotype available only from the profile 
- [ ] Any ToBeClarified element is associated with CCM work item
- [ ] All the Interfaces defined by a SwComponentCluster are located under the SwComponentCluster
- [ ] All the Sub SwComponentClusters are located under the SwComponentCluster
- [ ] The actual Interfaces required in the Sub SwComponentCluster should be modelled within Sub SwComponentCluster and the MainSwComponentCluster should have only the ports of its Sub Sw Component Cluster. the main SwComponentCluster itself should not define any Interfaces of its Sub SwComponentCluster
- [ ] Group all the Interfaces which are detailed out into an abstract standard interface if available E.g. <br/>
IF_AAP_COM_ServiceProxy and IF_AAP_COM_ServiceSkeleton could be IF_ARA_COM (label ara::com)<br/>
IF_AAP_EXM_ApplicationClient and IF_AAP_EXM_RecoveryActionClient to IF_ARA_EXM (label ara::exm)<br/>
This is required for showing high leve SwComponentWallpaper<br/>
- [ ] Concepts are available and checked in as controlled file within Rhapsody
- [ ] Architecture decissions if any are documented within the descisions and updated in the VRTE_Decisions.xlsx controlled file in chapter 9