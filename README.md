# Analysis on U.S. Patents and Patent Applications

This analysis explored the Patent Examination Research Dataset (Public PAIR) and Assignment Dataset provided by the United States Patent and Trademark Office (USPTO). I primarily focused on the time period 2000-2019 and explored the following:

1. Technology centers - examination groups applications are assigned to based on invention
2. United States Patent Classification (USPC) class numbers - applications are assigned a USPC class number based on the type of invention
3. Inventors - where are the inventors from?
4. Entity status - undiscounted, small, or micro
5. Assignees - who has property right to the patent?

This analysis provides an overview of the types of inventions that have been patented and the owners of these patents. Additionally, analysis of the publicly viewable pending applications provided insight into the patents that are coming down the pipeline. The assignment dataset also provides a general idea of which countries and companies have strong U.S. patent portfolios.

## Datasets and Data Preprocessing

The public PAIR dataset contains information on publicly viewable patent applications through April 2020. The patent assignment dataset contains information on assignments that have been recorded at the USPTO since 1970. The Public PAIR dataset was processed to create two separate dataframes: (1) pending patent applications and (2) issued patents for the time period 2000-2019.

[Link to datasets](https://www.uspto.gov/ip-policy/economic-research/research-datasets)

[Link to notebook and plots](https://ibarahona.github.io/DATS6103-Project-3/US_Patent_Analysis.html)
