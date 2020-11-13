Linking OSF with R
================
Joseph Gaudard
November 13, 2020

## Downloading data from an OSF repository

Use dataDownloader (<https://github.com/Between-the-Fjords/dataDownloader>):

``` r
get_file(node = "node",
         file = "file name on OSF",
         path = "where you want to download the file locally",
         remote_path = "the path in the OSF repository")
```

Cool, but if the OSF repository is still private, it does not work.

## Adding a PAT to your R environment

A PAT (Personal Access Token) will allow R to access your OSF account. If you add it as an environmental variable in R, you will need to do that only once.

***WARNING:*** The PAT gives access to your entire OSF account. It should be treated like a password.

Obtain a PAT (from the `osfr::osf_auth` manual):

1.  Go to <https://osf.io/settings/tokens/>, login, and click "New token";
2.  Define the permissions;
3.  Click "Create" to generate the PAT;
4.  Read the warnings;
5.  Copy the token.

Add the PAT as an environmental variable:

1.  Type `usethis::edit_r_environ()` in your favorite R Console;
2.  Add the line `OSF_PAT=your_token` to the `.Renviron` file;
3.  Save the `.Renviron` file;
4.  Restart R.
