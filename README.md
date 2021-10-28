## README
This repository contains the Working from Home (WFH) capacity index propsed in "[Germany's Capacity to Work from Home](https://www.cesifo.org/en/publikationen/2020/working-paper/germanys-capacities-work-home "Germany's Capacities to Work from Home")" by Jean-Victor Alipour, Oliver Falck and Simone Schüller.

The index is available at the 2-digit NACE industry level, NUTS-3 (county) level, and the 2-digit occupation level (KldB-2010 and ISCO-2008):

#### Industry-level data [[csv-format](../master/wfh_nace2.csv), [dta-format](../master/wfh_nace2.csv)]
- **nace2**: NACE 2-digit sector identifier
- **wfh_freq**: Share of employees working from home frequently
- **wfh_occ**: Share of employees working from home occasionally
- **wfh_untapped_dem**: Untapped WFH capacity due to lacking demand
- **wfh_untapped_sup**: Untapped WFH capacity due to supply-side contraints
- **wfh_feas**: Share of WFH feasible jobs (WFH capacity)  

#### County-level data [[csv-format](../master/wfh_nuts3.csv), [dta-format](../master/wfh_nuts3.csv)]
- **nuts3**: County identifier (*Allgemeiner Kreisschlüssel*)
- **wfh_freq**: Share of employees (working in county &) working from home frequently
- **wfh_occ**: Share of employees (working in county &) working from home occasionally
- **wfh_tot**: Share of employees (working in county &) ever working from home
- **wfh_untapped_res**: Untapped WFH capacity based on county of work
- **wfh_feas**: Share of WFH feasible jobs (WFH capacity)  
- **wfh_freq_res**: Share of employees (residing in county &) working from home frequently
- **wfh_occ_res**: Share of employees (residing in county &) working from home occasionally
- **wfh_tot_res**: Share of employees (residing in county &) ever working from home
- **wfh_untapped_res**: Untapped WFH capacity based on county of residence
- **wfh_feas_res**: Share of employees (residing in county &) with WFH feasible jobs (WFH capacity based on county of residence)


#### Occupation-level data: KldB-2010 2-digit [[csv-format](../master/wfh_kldb10_2d.csv), [dta-format](../master/wfh_kldb10_2d.csv)]/ ISCO-2008 2-digit [[csv-format](../master/wfh_isco08.csv), [dta-format](../master/wfh_isco08_2d.csv)]
- **kldb10_2d**: 2-digit occupation, Klassifizierung der Berufe 2010
- **isco08_2d**: 2-digit occupation, ISCO 2008
- **wfh_freq**: Share of employees working from home frequently
- **wfh_occ**: Share of employees working from home occasionally
- **wfh_untapped_dem**: Untapped WFH capacity due to lacking demand
- **wfh_untapped_sup**: Untapped WFH capacity due to supply-side contraints
- **wfh_feas**: Share of WFH feasible jobs (WFH capacity)  

All computations are based on data from the BIBB/BAuA Employment Survey 2018 and employment statistics from the Federal Employement Agency (BA), June 2019.

Please cite as: Alipour, J.-V., O. Falck and S. Schüller (2020). Germany's Capacity to Work from Home. CESifo Working Paper No. 8227.

For questions and suggestions, please contact:  
Jean-Victor Alipour  
LMU Munich & ifo Institute  
alipour@ifo.de  
