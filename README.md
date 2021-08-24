# ENE425 Emissions App
Emissions DB collector for ENE425

# ENE425 Emissions App
### This is an app created for the course ENE425 of the Norwegian School of Economics. 

Online App that stores, edit and remove records of emissions per individuals and between groups. 

The development was carried under Flask-Python, wtforms, sqlalchemy an deployed in Heroku. 

Records are dynamically updated in a Heroku PostgreSQL database.

Input

        User values through Graphical User Interface (GUI)
    
Output

        Dynamic App deployed in a Heroku server with emissions records per group and per group member
   
### Emissison's App tasks

![alt_text](notes/module_design_v2.png)

## Example of the methodology section for the methodology group
## Emissions Methodology
### Within this section we are gathering information on emissions calculation method for transport sources:
A basic understanding requires having a classification of transport as urban transport or industrial transport (e.g maritime, air).
A more segregated classification of "vehicles" under EC standards can be found at this [link](https://www.eafo.eu/knowledge-center/european-vehicle-categories), which is connected to the last study of ["Determining the environmental impacts of conventional
and alternatively fuelled vehicles through LCA"](https://ec.europa.eu/clima/sites/clima/files/transport/vehicles/docs/2020_study_main_report_en.pdf) by Ricardo Energy and Environment for the European Comission. Our observations o this study is that the segregation is practical for our purpouses, but the methodology is on a higher scale than what we are intending to do with the app (local direct emission per km rather than Life Cycle Analysis (LCA)).

