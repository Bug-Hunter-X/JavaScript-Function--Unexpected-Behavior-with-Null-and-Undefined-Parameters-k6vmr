# JavaScript Function: Handling Null and Undefined Parameters

This repository demonstrates a potential bug in a JavaScript function and provides a solution.

## Bug Description

The `foo` function is designed to add two numbers. It correctly handles `null` values, returning 0 if either parameter is `null`. However, it fails to explicitly handle cases where one or both parameters are `undefined`, which might lead to unexpected behavior (NaN in addition) or runtime errors.

## Bug Solution

The solution expands the null check to include undefined checks ensuring that the function behaves correctly under all these scenarios, returning 0 or providing error messages when appropriate.