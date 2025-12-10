
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mychores

<!-- badges: start -->
<!-- badges: end -->

The goal of the {mychores} repo is to hold any prompts to be used with
the [chores](https://github.com/simonpcouch/chores) package, and
reference to other folks chores too (from the chores gallery).

``` r
md_files <- list.files(pattern = "\\.md")
my_prompts <- md_files[md_files != "README.md"]
my_prompts
#> [1] "flipbookify-replace.md" "pipify-suffix.md"
```

I registered my chores as follows, when I write an ‘.md’ file from
scratch.

``` r
chores::prompt_new(chore = "pipify-suffix",
                   interface = "suffix",
                   contents = "pipify-suffix.md")
```

Or I can initiate a new chore you can write use `chores::prompt_new()`

``` r
# chores::prompt_remove(chore = "flipbookify")
chores::prompt_new(chore = "flipbookify",
                   interface = "replace",
                   contents = "flipbookify-replace.md")
```

# Here’s a list of the *web* addresses of the chores in this repo.

``` r
paste0("https://github.com/EvaMaeRey/mychores/blob/main/", my_prompts)
```

# If you want to register any of these chores, you can do so as follows.

# If you want to register the chores of interest as follows:

``` r
chores::prompt_new(chore = "pipify",
                   interface = "suffix",
                   contents = 
  "https://raw.githubusercontent.com/EvaMaeRey/mychores/refs/heads/main/pipify-suffix.md"
)

chores::prompt_new("chore = ")
```

Or since, I could do this:
