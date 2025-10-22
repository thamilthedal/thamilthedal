### Hi there 👋 I'm Thamil.

I'm a PhD candidate working on the supercritical water flow and heat transfer studies under Prof. Sandip K Saha and Prof. Amit Agrawal at IIT Bombay.
My works involves modelling non-equilibrium in supercritical heat transfer arising due to variation in properties in buoyant-driven channel flows.

I love programming for,
- Postprocessing and Data Visualization
- Automating my workflows
- Works on ANSYS Fluent, Python, C, C++

## Currently Working on
- Building a journal file from ANSYS Fluent case file for easier automation of cases within supercritical CLI
- **_foamMeshToFluent3D_** and optimize it to run faster than in-built OpenFOAM converter
- parametric study in supercritical CLI for batching multiple cases

## Previously Worked on
- **_supercritical_CLI_**: Fully automated CLI based ANSYS Fluent Workflow for simulating supercritical heat transfer through pipe
    - Meshing done in OpenFOAM Blockmesh
    - Conversion to 2D by own-code base (foamToFluent2D)
    - Property journal generated for maximum accurate interpolation based on gradient descent
    - Job handling, monitoring, postprocessing and then report generation based on defined template in LATEX.
    - Conducts a mesh dependency test based on optimized set of parametersand generate a report.
- **_residual_HPC_**: Simultaneously monitor residuals for multiple ANSYS Fluent running in ROCKS HPC.
- **_post_CLI_**: Postprocessing CLI tool based on pyFluent that batch postprocesses all files inside a target folder based on a template settings from JSON
- **_foamToFluent2D_**: Mesh conversion tool for converting all structured 2.5D meshes in OpenFOAM into 2D meshes for ANSYS Fluent (polyMesh to .msh)
