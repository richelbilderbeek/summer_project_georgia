# summer_project_gina

 Summer project by Gina Tsaridou.
 
 * Timespan: approx 6 weeks full-time in the summer of 2021,
   Monday June 14th - Friday July 23th
 * Supervision:
    * [Willy](https://github.com/FrieseWoudloper) and Richel

## Goals

This summer project has two goals:

 * 1. write `netmhcpanr`
 * 2. write `top2000r`

### 1. write `netmhcpanr`

Write a package `netmhcpanr`, to work with 
[NetMHCpan](https://services.healthtech.dtu.dk/service.php?NetMHCpan-4.1), 
similar to [netmhc2pan](https://github.com/richelbilderbeek/netmhc2pan) 
([YouTube](https://youtu.be/08A_kf4v2UA))
and publish it on CRAN.

 * [ ] Create repo
 * [ ] Copy netmhc2pan code
 * [ ] Make package build, skip all tests
 * [ ] Gradually get all tests to work

Additionally:

 * GitHub Actions must work
 * Code coverage must work (but cannot be 100%)
 * Clean lint

### 2. write `top2000r`

The Top2000 is a yearly-renewed list of the 2000 most popular Dutch songs.
The position of most songs fluctuates over the years.
The customer wants to have a Top2000 list that takes all
years into account.

Write a package `top2000r` to get an averaged Dutch Top2000.
This package does not need to be on CRAN.
It does need to be easy to update every year.

 * [ ] Write down a proposal, share with customer
 * [ ] Implement proposal, share results with customer

Additionally:

 * GitHub Actions must work
 * Code coverage must be 100%
 * Clean lint

## Schedule

### `top2000r`

Week|What
----|-----------------------------------------------
24  |Submit idea to customer
25  |Wait
26  |Implement accepted idea for customer, else resubmit
27  |Wait
28  |Implement accepted idea for customer, else resubmit
29  |Implement accepted idea for customer, else project failed

Week|What
----|-----------------------------------------------
24  |Setup `netmhcpanr`,  similar to [netmhc2pan](https://youtu.be/08A_kf4v2UA)
25  |Improve `netmhcpanr`
29  |Submit to CRAN or rOpenSci

## Links

 * Top2000: [GitHub](https://github.com/rneeft/Top2000) [Wikipedia](https://en.wikipedia.org/wiki/Top_2000)
 * [YouTube: How to create an R package in 8 minutes](https://youtu.be/MoszELQFrvQ)
 * `netmhc2pan`: [GitHub](https://github.com/richelbilderbeek/netmhc2pan) [YouTube](https://youtu.be/08A_kf4v2UA)

