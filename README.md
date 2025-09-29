transaction:
  id: "TXN-20250929-0002"
  timestamp: "2025-09-29T12:15:00Z"
  type: "credit"   # credit = adding money
  amount:
    currency: "BDT"
    value: 500.00
  status: "completed"   # pending | completed | failed
  source:
    method: "cash_deposit"   # cash_deposit | cheque | transfer | card
    reference: "BRANCH-ATM-112"
  destination_account:
    account_number: "1234567890"
    account_holder: "faisal"
    bank: "Cit bank"
    branch_code: "BOFAUS3N"
  metadata:
    channel: "branch"   # atm | online_banking | mobile_app | branch
    remarks: "Upay-City-bank"
