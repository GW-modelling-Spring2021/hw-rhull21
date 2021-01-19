### Hull HW 1 - The Challenge

1. Show, based on the flux with depth, that the model is steady state. Repeat this for a homogeneous and for a heterogeneous column.
  * By steady state, we mean that the discharge is unchanging within the model domain over time. By extension, the flux (q) at every point `z` in our 1-D model domain must also be the same. We can see that in both the heterogenous and homogenous models

2. Show that the steady state flux agrees with the direct calculation based on the harmonic mean average K. Write the equation defining the direct calculation of the flux.
  * why harmonic mean? assume unit gradient?

3. Show the steady state head profile for a column with approximately equal-thickness layers that have different K values.
  * okay that could be a bit challenging

4. Use the head profile to explain WHY the equivalent hydraulic conductivity, Keq, is closer to the lower of the two K values.
  * Tough to know without looking more closely at the model

### Hull HW 1 - Key Figures
* the model should already work
* nb - important to have iterative solutions activated in excel
  * https://support.microsoft.com/en-us/office/remove-or-allow-a-circular-reference-8540bd0f-6e97-4483-bcf7-1b49cd50d123#:~:text=If%20this%20confuses%20you%2C%20imagine,cell%20listed%20in%20the%20submenu

* Change around the boundary conditions and K values

### Discussion Points

1. What are boundary conditions? Answer this both conceptually and mathematically.

2. What are model parameters? How do they (and don't they) represent the actual subsurface?

3. What are steady state conditions and how can they be identified from the Excel model results?

4. Can you imagine how the model inputs could be stored in separate files rather than other spreadsheet cells? Describe the flow of information from a file that describes the other files that contain model-specific information about the system.

5. What is an iterative solution? Can you explain it to a hydrologist who is not a modeler? Can you describe (or imagine) how Excel finds the solution?

6. What is a direct solution? What are its (dis)advantages compared to an iterative (numerical) solution?
