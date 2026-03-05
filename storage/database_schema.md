# Database Schema

## Purpose
The database stores farmer data, farm information, carbon calculations, and transaction records.

## Tables

Farmers
- farmer_id
- name
- location
- contact_number
- land_size

Farms
- farm_id
- farmer_id
- location_coordinates
- farm_area

Tree_Data
- tree_id
- farm_id
- tree_count
- tree_height
- estimated_biomass

Carbon_Calculations
- calculation_id
- farm_id
- carbon_stored
- co2_equivalent
- carbon_credits

IoT_Sensor_Data
- sensor_id
- farm_id
- soil_moisture
- soil_ph
- temperature
- humidity
- timestamp

Carbon_Credit_Transactions
- transaction_id
- farmer_id
- company_id
- carbon_credits
- price
- transaction_date
