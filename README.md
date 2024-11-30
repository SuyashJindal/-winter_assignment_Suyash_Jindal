# -winter_assignment_Suyash_Jindal
Merchant Investigation System 
### Objective

Create an autoencoder-based anomaly detection system that can identify suspicious merchant behavior patterns.

### Implementation Steps

1. **Data Generation**
    - Create a merchant profile generator
        - Basic fields: ID, name, business type, registration date
        - Additional fields: GST status, transaction volumes
    - Generate transaction data
        - Normal trading patterns (80% of merchants)
        - Specific fraud patterns (20% of merchants):
            - Late night transactions
            - High velocity spikes
            - Customer concentration
2. **Feature Engineering**
    - Calculate merchant features:
        - Transaction velocity metrics
        - Time-based patterns
        - Amount distributions
        - Customer concentration
    - Create feature normalization pipeline
3. **Model Development**
    - Implement autoencoder architecture
    - Train on normal merchant behavior
    - Calculate reconstruction error thresholds
    - Implement anomaly scoring
4. **Fraud Pattern Detection**
    - Implement specific detection rules:
        - High velocity detection
        - Odd-hour pattern detection
        - Customer concentration analysis
    - Calculate pattern-specific scores
      ---------------------------------------------------------
      Used Random & Faker Library for data generation.
      Implement autoencoder for anomaly detection and scoring it.
      Also code detection rules .
