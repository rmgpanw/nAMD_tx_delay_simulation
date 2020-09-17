# nAMD_tx_delay_simulation

This repo contains the code used to model neovascular age-related macular degeneration visual outcomes following treatment delay in our paper ['Estimating excess visual loss in people with neovascular age-related macular degeneration during the COVID-19 pandemic'](https://www.medrxiv.org/content/10.1101/2020.06.02.20120642v1)

Notes:
- The example simulation code sets the number of iterations to 100. For our actual results this was set to 1000 but this does take longer to run.
- To reproduce the sensitivity analysis, please set the `delay` argument in the `wet_amd_one_year_outcome_simulator()` function to `delay=FALSE`.
