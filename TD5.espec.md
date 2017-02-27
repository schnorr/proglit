## TD5: Data Manipulation with dplyr

Using the [first name data
set of INSEE](https://www.insee.fr/fr/statistiques/fichier/2540004/dpt2015_txt.zip), answer some of the following questions (you also have to use
**ggplot2**):

- First name frequency evolves along time?
- What can we say about ``Your name here'' (for each state, FR)?
- Is there some sort of geographical correlation with the data?
- Which state has a larger variety of names along time?
- _your own question_ (be creative)

We have demonstrated the use of the six verbs in [our demonstration of
dplyr](./TD5/TD5.Rmd).

1. Install dplyr and magrittr

   ```
   install.packages("ggplot2");
   install.packages("magrittr");
   ```



3. Unzip the file _dpt2015_txt.zip_ (to get the **dpt2015.txt**)

4. Read in R with this code. Note that you might need to
install the `readr` package with the appropriate command.

   ```
   library(readr);
   df <- read_tsv("dpt2015.txt", locale = locale(encoding = "ISO-8859-1"));
   ```

4. Create your own R markdown (Rmd). Follow the PL guidelines,
explaining your data manipulation and plot.
  - Use all the six verbs: _select()_, _filter()_, _arrange()_, _mutate()_, _group_by()_, _summarize()_
  - Plot data with _ggplot()_


