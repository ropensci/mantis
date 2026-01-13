# Package index

## Basic usage

- [`mantis_report()`](https://ropensci.github.io/mantis/reference/mantis_report.md)
  : Create an interactive time series report from a data frame
- [`inputspec()`](https://ropensci.github.io/mantis/reference/inputspec.md)
  : Specify relevant columns in the source data frame
- [`example_prescription_numbers`](https://ropensci.github.io/mantis/reference/example_prescription_numbers.md)
  : Example data frame containing numbers of antibiotic prescriptions in
  long format

## Specifying the output format

- [`outputspec_interactive()`](https://ropensci.github.io/mantis/reference/outputspec_interactive.md)
  : Specify output options for an interactive report
- [`outputspec_static_heatmap()`](https://ropensci.github.io/mantis/reference/outputspec_static_heatmap.md)
  : Specify output options for a static report containing heatmaps
- [`outputspec_static_multipanel()`](https://ropensci.github.io/mantis/reference/outputspec_static_multipanel.md)
  : Specify output options for a static report containing a panel of
  plots.

## Specifying alerting rules

- [`alertspec()`](https://ropensci.github.io/mantis/reference/alertspec.md)
  : Specify alerting rules to be run on the data and displayed in the
  report
- [`alert_rules()`](https://ropensci.github.io/mantis/reference/alert_rules.md)
  : Create set of alert rules
- [`alert_missing()`](https://ropensci.github.io/mantis/reference/alert_rule_types.md)
  [`alert_equals()`](https://ropensci.github.io/mantis/reference/alert_rule_types.md)
  [`alert_above()`](https://ropensci.github.io/mantis/reference/alert_rule_types.md)
  [`alert_below()`](https://ropensci.github.io/mantis/reference/alert_rule_types.md)
  [`alert_difference_above_perc()`](https://ropensci.github.io/mantis/reference/alert_rule_types.md)
  [`alert_difference_below_perc()`](https://ropensci.github.io/mantis/reference/alert_rule_types.md)
  [`alert_custom()`](https://ropensci.github.io/mantis/reference/alert_rule_types.md)
  : Built-in alert rules
- [`mantis_alerts()`](https://ropensci.github.io/mantis/reference/mantis_alerts.md)
  : Generate a data frame containing alert results

## Creating a bespoke report

- [`bespoke_rmd_initialise_widgets()`](https://ropensci.github.io/mantis/reference/bespoke_rmd_initialise_widgets.md)
  : Initialise HTML widgets
- [`bespoke_rmd_output()`](https://ropensci.github.io/mantis/reference/bespoke_rmd_output.md)
  : Dynamically generate mantis output for an rmd chunk
- [`bespoke_rmd_alert_results()`](https://ropensci.github.io/mantis/reference/bespoke_rmd_alert_results.md)
  : Dynamically generate a table containing alert results for an rmd
  chunk
