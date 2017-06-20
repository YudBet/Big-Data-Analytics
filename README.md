# Big-Data-Analytics
## HW1: feature selection

### Q1. What features are helpful for Malware Classification task?

-   ent_q_diff_block_0_0
-   ent_q_diff_block_1_15
-   ent_q_diff_block_1_16
-   ent_q_diff_block_1_17
-   ent_q_diff_diffs_10
-   ent_q_diff_diffs_11
-   ent_q_diffs_mean
-   ent_q_diffs_var
-   ent_p_2
-   ent_q_diff_block_2_15
-   ent_q_diff_block_2_16
-   ent_q_diff_block_3_15
-   ent_q_diff_block_3_20

-   Num_Sections
-   Unknown_Sections
-   known_Sections_por
-   section_names_.rdata

-   DisableThreadLibraryCalls
-   FreeEnvironmentStringsA
-   FreeEnvironmentStringsW

-   db0_por
-   db_por
-   db3_all

-   Img*



### Q2. What features are useless for Malware Classification task?

    Any feature which not presented in Q1 are useless for malware classification.

### Q3. How could you draw the conclusion above?

    Simply observe on the boxplots of normalied feature-class plots, which shows the feature sensitivity of each feature.  Although there are many ways to measure sensitivity of feature to class, I have no idea about how to choose the best one.

### Q4. List all packages you used in Python for dealing with the tasks above.

-   numpy
-   pandas
-   matlibplot

### Q5. Make comments for this class.

    No comment.