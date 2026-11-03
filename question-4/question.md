# Back-end Challenge – Age Counting

## Problem Description
Perform a GET request to the API endpoint:

`https://coderbyte.com/api/challenges/json/age-counting`

The API returns JSON data containing a `data` key with a string of items in the format `key=STRING, age=INTEGER`.

Your task is to count the number of items whose age is greater than or equal to 50 and print the final count.

## Example Input
```json
{
  "data": "key=IAfpK, age=58, key=WNVdi, age=64, key=jp9zt, age=47"
}
```

## Example Output
```text
2
```

## Explanation
- Age 58 is greater than or equal to 50.
- Age 64 is greater than or equal to 50.
- Age 47 is less than 50.

Therefore, the final count is **2**.

## Concepts Used
PHP, HTTP GET Request, cURL, JSON Decoding, String Parsing, Regular Expressions, Conditional Statements.

**Language:** PHP  
**Difficulty:** Intermediate  
**Category:** Back-end Development