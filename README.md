# Groovy NullPointerException in List Iteration

This repository demonstrates a common NullPointerException in Groovy when iterating over a list that might be null.

## Bug
The `myMethod` function iterates over a list of strings. If a `null` list is passed, a `NullPointerException` occurs because the `each` method cannot operate on `null`.

## Solution
The solution involves adding a null check before iterating over the list, handling the null case appropriately.