# Star count by organization

Question: What is the current amount of stars an organization has across all of its repositories?

## Description
Repositories are started by the widest range of people. It includes people who are already involved and contributing to a project or plan to be soon, as well as people who are only interested in the project or plan to use it without contributing.

## Objectives
By looking at this metric and the change in this metric over time, we can gain insight into the demand for the project independent of how often and how much code is committed to the project. Even an active repository can die if there is no demand for it.

## Implementation
Aggregators:
- Count. Total number of stars an organization has

Parameters:
- Date. The date at which you want to know how many stars the organization had/has. Defaults to current date.

## Filters
- By repository. Get star count of specific repository(s)

## Tools Providing the Metric
Github api list stargazers.
https://developer.github.com/v3/activity/starring/#list-stargazers

## References