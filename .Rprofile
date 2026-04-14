source("renv/activate.R")

if (reticulate::py_available(initialize = FALSE)) {
  # Python already knows where to find the environment, do nothing
} else {
  # Try to find the standard anaconda environment created by reticulate, if it exists
  try(reticulate::use_condaenv("r-reticulate"), silent = TRUE)
}
