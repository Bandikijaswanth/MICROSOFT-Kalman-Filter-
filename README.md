# MICROSOFT-Kalman-Filter-
AIM

To compute the estimated state using a simplified Kalman Filter update rule.

PROCEDURE
Initialize predicted state and measured state values
Apply the estimation formula: estimate = (prediction + measurement) / 2
Substitute the given values
Compute the estimated state
Display the result
CODE
# Input values
prediction = 20
measurement = 24

# Kalman update (simplified)
estimate = (prediction + measurement) / 2

# Output
print("Estimated State:", estimate)
OUTPUT

Estimated State: 22

RESULT

The estimated state is 22, obtained by combining prediction and measurement to improve accuracy.
