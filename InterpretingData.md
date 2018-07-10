# Interpreting raw data

## Data types
- **Numberic**: Is a whole number or a decimal and can be positive or negative
- **Integer**: Is a whole number
- **Character** / **String**: Is text
- **Boolean**: Is TRUE or FALSE
- **Date** / **Datetime** Is a point in time

## Core concepts
- **Observation** Taking the measure of *something*
- **Measures** Numeric values quantifying *something*
- **Attributes** Properties of *something*
- **Identifier** / **Key** A value or combination of values that uniquely identifies *something*
- **Surrogate key** A placeholder value that can be used (often a number) to represent *something*

## Tables
Tables are what we tend to work with most often day to day. Even when we get data from systems via an API, we usally make it look like a table.

A table consists of: 
- **Rows**: A record or observation about *something*
- **Columns**: Attributes or information relating to *something*

We often describe tables as having certain shapes. Common shapes you'll find are:
- **Wide** / **Pivoted**: Where the same value was measured repeatedly and occurs going accross
- **Long** / **Unpivoted**: Where instances of repat measures have their own rows
- **Normalised** / **Relational**: Only data about the thing is directly included, perhaps with links to information about other things
- **Denormalised** / **Flat**: Contains data related to other things that are linked

## Data quality

### Missing data
If data is missing, we usually need to work out why. Is it due to the information being optional? System error? Is it new? Depending on why data is missing impacts our handling of it.

### Bad data
Data isn't always very clean! There might be lots of test@test.com, default values for birthdays, crazy income outliers and more. We should check for this sort of thing before it impacts our analysis.

## What to do when you first get some new data
1. Check the number of rows and colums
1. Work out what the ID is
1. Identify the shape of the data
1. Check the datatypes are what you'd expect
1. Identify any missing values and whether you need to do something about them
1. See if there are any unusual values in the data

## Exercises
1. What things should be improved in our data?
2. Implement some of the improvements you've identified

## Recommended readings and resources
- :page_facing_up: [Pivoting and unpivoting data](http://radacad.com/pivot-and-unpivot-with-power-bi)
- :page_facing_up: [Getting simple data profiles](https://blog.crossjoin.co.uk/2016/01/12/descriptive-statistics-in-power-bim-with-table-profile/)
