---------------------------------------------------Readme----------------------------------------------------------

Label encoding and ordinal encoding are techniques for converting categorical data into numerical form, which is essential for many machine learning models. Here's an explanation of both:

Label Encoding
Label encoding assigns a unique integer to each category in a feature. It does not consider the order or rank of the categories; it simply assigns numbers arbitrarily.

Example:
Feature: Color = ['Red', 'Green', 'Blue', 'Red']

Encoded:

Red → 0
Green → 1
Blue → 2
Result: [0, 1, 2, 0]

Ordinal Encoding
Ordinal encoding is used when the categorical data has a meaningful order or ranking. It assigns integers to categories in a way that reflects their order.

Example:
Feature: Size = ['Small', 'Medium', 'Large']

Encoded:

Small → 0
Medium → 1
Large → 2
Result: [0, 1, 2]

