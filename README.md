
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mychores

<!-- badges: start -->
<!-- badges: end -->

The goal of the {mychores} repo is to hold any prompts to be used with
the [chores](https://github.com/simonpcouch/chores) package, and
reference to other folks chores too (from the chores gallery).

``` r
my_prompts <- list.files(pattern = "\\.md")
my_prompts

my_prompts_urls <- paste0("")
```

``` r
chores::prompt_new(chore = "quartochunk",
                   interface = "replace",
                   contents = 
  "https://gist.githubusercontent.com/hfrick/1ca8fc2cb2a4409b743e8120c6cc2223/raw/a9703edfbd4e83839af0278c33add1b33e243d02/quartochunk-replace.md"
)
```

------------------------------------------------------------------------
