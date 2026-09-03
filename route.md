PURCHASE REQUEST
│
├── GET /procurement/purchase-requests
├── GET /procurement/purchase-requests/{pr}
│
├── PROCUREMENT MODE
│ ├── GET /purchase-requests/{pr}/procurement-mode
│ ├── POST /purchase-requests/{pr}/procurement-mode
│ └── POST /purchase-requests/{pr}/procurement-mode/approve
│
└── NNP
│
├── GET /nnp
├── GET /nnp/create
├── POST /nnp
├── GET /nnp/{nnp}/edit
├── PUT /nnp/{nnp}
├── GET /nnp/{nnp}/review
├── POST /nnp/{nnp}/submit
├── POST /nnp/{nnp}/approve
├── POST /nnp/{nnp}/return
├── GET /nnp/{nnp}/issue
└── POST /nnp/{nnp}/issue
│
▼
QUOTATIONS
│
├── GET /nnp/{nnp}/quotations
├── POST /nnp/{nnp}/quotations
├── GET /quotations/{quotation}
├── PUT /quotations/{quotation}
├── POST /quotations/{quotation}/accept
├── POST /quotations/{quotation}/reject
│
▼
EVALUATION
│
├── GET /nnp/{nnp}/quotations/evaluation
└── POST /nnp/{nnp}/quotations/evaluation
│
▼
ABSTRACT
│
├── GET /nnp/{nnp}/quotations/abstract
└── POST /nnp/{nnp}/quotations/abstract
│
▼
RECOMMENDATION
│
├── GET /nnp/{nnp}/recommendation-for-award
└── POST /nnp/{nnp}/recommendation-for-award
│
▼
AWARD APPROVAL
│
├── GET /nnp/{nnp}/award-approval
├── POST /nnp/{nnp}/award-approval/approve
└── POST /nnp/{nnp}/award-approval/return
│
▼
NOTICE OF AWARD
│
├── GET /nnp/{nnp}/notice-of-award
├── PUT /nnp/{nnp}/notice-of-award
└── POST /nnp/{nnp}/notice-of-award/issue
│
▼
PURCHASE ORDER
│
├── GET /nnp/{nnp}/purchase-order
├── POST /nnp/{nnp}/purchase-order
└── POST /purchase-orders/{po}/issue
│
▼
DELIVERY
│
├── GET /purchase-orders/{po}/deliveries
├── POST /purchase-orders/{po}/deliveries
└── GET /deliveries/{delivery}
│
▼
INSPECTION
│
├── GET /deliveries/{delivery}/inspection
├── POST /deliveries/{delivery}/inspection
└── POST /inspections/{inspection}/complete
│
▼
PAYMENT
│
├── GET /purchase-orders/{po}/payments
├── POST /purchase-orders/{po}/payments
├── POST /payments/{payment}/submit
└── POST /payments/{payment}/process
│
▼
COMPLETED
│
└── GET /purchase-requests/{pr}/completed
