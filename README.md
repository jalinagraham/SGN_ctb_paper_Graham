# code_for_paper
 Jupyter Notebook Python Code for replicating analyses and statistics for publication

#organization notes

#Description of summary data
**injection_groups_all_columns_added.csv
*****total and average SGN and DTN cell counts projecting to DTN, LMN or both for each rat (as well as which injection group each rat belongs to (DTN and LMN hit, adjacent or miss). 

#Analysis code (located in 'Graphs_tables_analyses' folder): Run 'SGN_contra_analysis.ipynb' to replicate graphs and assemble summary data from source data.

#Statistics code (located in 'Statistics' folder): Run 'SGN_ctb_stats.ipynb' to replicate statistical tests (ANOVA and t-tests).


#description of source data
**SGN_contra_counts_with_old.csv
*****Number of single-labeled cells (SGN cells projecting to either LMN 'or' DTN) and double-labeled cells (SGN cells projecting to both LMN 'and' DTN) in the SGN contralateral to the DTN injection

**SGN_ipsi_counts.csv
*****Number of single-labeled cells (SGN cells projecting to either LMN 'or' DTN) and double-labeled cells (SGN cells projecting to both LMN 'and' DTN) in the SGN ipsilateral to the DTN injection

**DTN_contra_counts.csv
*****Number of single-labeled cells (SGN cells projecting to either LMN 'or' DTN) and double-labeled cells (SGN cells projecting to both LMN 'and' DTN) in the SGN contralateral to the DTN injection

**hit_miss_group_paper.csv
*****Which injection site group each brain belongs to (DTN and LMN hits, adjacent or misses)

**lmn_ctb_total_injection_area.csv
*****area (in mm2) of ctb inside or outside of LMN (see paper for details)

**DTN_fluorophore_with_old.csv
*****A list of which fluorophore was injected into DTN (either green or red ctb)