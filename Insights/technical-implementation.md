# Madhmoun Technical Implementation

## Core Services

### 1. Requesting Advertising Permits
* **Purpose**: Obtain digital permit to advertise property on any website
* **Eligible Users**: Real estate developers, brokers, brokerage firms, property management companies, and companies that own properties
* **Access**: Via ADREC platform (www.dari.ae) under Madhmoun category
* **Application Process**:
  - Switch to company account
  - Select role (broker, owner, etc.)
  - Select permit purpose (rent or sale)
  - Select duration (1-3 months)
  - Indicate exclusivity status
  - Add broker details
  - Add properties (via search or certificate number)
  - Review and submit
  - Await approval from other party
  - Complete payment upon approval

### 2. Renewing Permits
* **Eligibility**: Only active permits can be renewed
* **Process**:
  - Select permit to renew
  - Option to remove (but not add) properties
  - Submit for approval by other party
  - Complete payment
* **Duration**: Added to remaining time of existing permit

### 3. Cancelling Permits
* **Eligibility**: Only active permits can be cancelled
* **Process**:
  - Select permit to cancel
  - Submit for approval
  - Both parties must approve (except for shared ownership properties where one landlord's approval is sufficient)
* **Cost**: No charge for cancellation
* **Effects**: Properties become eligible for new permits

## System Integration
* Current integration with Bayut and Property Finder
* Future expansion to additional platforms
* Automatic notifications to stakeholders
* API connections for verification of property data and ownership

## Technical Requirements
* UAE Pass for login (residents)
* Username/password login option for non-residents
* Proper permissions set for employees to access Madhmoun module
* Valid broker licenses and property documentation