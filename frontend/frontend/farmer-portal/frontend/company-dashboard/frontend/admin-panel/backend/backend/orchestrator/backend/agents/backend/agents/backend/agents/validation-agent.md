# Validation Agent

## Purpose
The Validation Agent verifies the accuracy of carbon credit calculations and prevents fraudulent data.

## Input
- Tree data from Vision Agent
- Carbon calculations from Carbon Agent
- IoT sensor data
- Satellite verification data

## Processing Steps

1. Cross-check tree data with satellite imagery
2. Validate biomass estimates
3. Compare IoT environmental data with expected crop growth
4. Detect anomalies or suspicious data

## Output
- Verified carbon credits
- Fraud detection alerts
- Validation report

## Example Output

{
 "status": "verified",
 "fraud_risk": "low",
 "verified_carbon_credits": 9
}
