# NPS Microgrid Innovations Research Center
## Website Supplemental Files

The [Naval Postgraduate School Microgrid Innovations Research Center website](https://microgrid.nps.edu/) is dynamically generated with dependencies to data hosted in this repository.

### Instructions

#### publications.bib

To update BibTeX entries:

1. Go to [publications.bib](./publications.bib)
1. Click the **pencil icon** towards the top-right corner to enter editing mode
1. Add new BibTeX entries or update existing ones
    1. Ensure capitalized content is protected by curly braces, so that the capitalization is not modified to title case, e.g.,
        1. `{IEEE}` must be protected so that "Ieee" will not be rendered
        1. `{U}nited {S}tates` must be protected so that “united states” will not be rendered
    1. For NPS thesis and capstone entries (login is required to export .bib files from [Calhoun](https://calhoun.nps.edu/home))
        1. Default: no edits are required for a single-author master’s thesis or a multiple-author master’s capstone
        1. For a multiple-author master’s thesis, the entry type must be changed from `@misc` to `@mastersthesis`
        1. For a single-author master’s capstone, the entry type must be changed from `@misc` to `@masterscapstone`
        1. For a PhD thesis, the entry type must be changed from `@misc` to `@phdthesis`
        1. A custom Master's description can be added by inserting a `type` tag, e.g.
            - `type = {MBA} professional project report`
            - Note: the entry type may remain `@misc`
    1. Non-NPS thesis and capstone entires are supported by setting the entry type
        1. Supported: `@bachorersthesis`, `@bachelorscapstone`, `@mastersthesis`, `@masterscapstone`, `@phdthesis`
1. Click **Commit changes...** in the top right corner
1. Enter a **Commit message** e.g.,
    1. *added new pub Reich, "A generalized method for rightsizing the design of a hybrid microgrid", Energies, 2025*
    1. *added all 2025 Q1 grads advised by Reich*
1. Select **Commit directly to the main branch** (should be seleted by default)
1. Click **Commit Changes**
1. Go to [publications webpage](https://microgrid.nps.edu/publications.html) and refresh the page to verify the updates appear as expected
    - Note: the updates may take up to 5 minutes to appear, due to [GitHub caching controls](https://stackoverflow.com/questions/46551413/github-not-update-raw-after-commit)
