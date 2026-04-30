# 🏋️ SE LAB EXAM – Personal Training Booking System

## 👨‍💻 Student Details
**Name:** Pakshal Jain  
**Roll No:** 241070029  

---

# 🧪 Black Box Testing

## 📊 Test Cases

| TC ID | Test Scenario | Input | Expected Output | Type | Result |
|------|--------------|------|----------------|------|--------|
| TC01 | Valid booking | Valid inputs | Booking successful | ECP | Pass |
| TC02 | Invalid member | Member=999 | Error | ECP | Pass |
| TC03 | Invalid trainer | Trainer=999 | Error | ECP | Pass |
| TC04 | Past date | Date < today | Error | ECP | Pass |
| TC05 | Current date | Date = today | Allowed | BVA | Pass |
| TC06 | Beyond limit | Date > 30 | Error | BVA | Pass |
| TC07 | Valid time | Time=10 | Accepted | ECP | Pass |
| TC08 | Time below | Time=5 | Error | BVA | Pass |
| TC09 | Time above | Time=23 | Error | BVA | Pass |
| TC10 | Slot unavailable | Already booked | Error | ECP | Pass |
| TC11 | Slot available | Free slot | Success | ECP | Pass |
| TC12 | Empty input | Missing fields | Error | ECP | Pass |
| TC13 | Invalid format | Time=25 | Error | ECP | Pass |
| TC14 | Limit exceeded | Count ≥3 | Error | ECP | Pass |
| TC15 | Confirmation | Valid input | Success | ECP | Pass |

✅ **Result: 15/15 Passed**

---

## 📋 Black Box Execution Output

```text
===== DETAILED TEST EXECUTION =====
TC01 → PASS
TC02 → PASS
...
TC15 → PASS

TOTAL PASSED: 15/15
