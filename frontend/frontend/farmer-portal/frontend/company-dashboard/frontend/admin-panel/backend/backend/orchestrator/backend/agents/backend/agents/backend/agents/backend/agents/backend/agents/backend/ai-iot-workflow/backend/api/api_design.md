# API Design

## Purpose
The API layer connects the frontend applications with the backend AI agents.

## Main APIs

### 1. Upload Farm Images
POST /api/upload-farm-image

Description:
Farmers upload images of their farm for tree detection.

Input:
Farm images

Output:
Image processing status

---

### 2. Carbon Credit Calculation
POST /api/calculate-carbon

Description:
Triggers Vision Agent and Carbon Agent to calculate carbon credits.

Input:
Farm image data
Tree details

Output:
Estimated carbon credits

---

### 3. Carbon Credit Verification
POST /api/verify-carbon

Description:
Validation Agent verifies carbon data using satellite and IoT inputs.

Output:
Verified carbon credits

---

### 4. Carbon Credit Marketplace
GET /api/marketplace

Description:
List available carbon credits for companies to purchase.

Output:
Available credits and prices

---

### 5. Transaction Recording
POST /api/record-transaction

Description:
Blockchain Agent records the carbon credit transaction.

Output:
Blockchain transaction ID
