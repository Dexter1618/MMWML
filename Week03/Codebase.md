## Dataset Codebase

( _See [README](https://github.com/Dexter1618/MMWML/blob/master/Week03/README.md) for an overview of the dataset and the problem statement_ )

---

Transaction Table

---

- TransactionDT: timedelta from a given reference datetime (not an actual timestamp)
- TransactionAMT: transaction payment amount in USD
- ProductCD: product code, the product for each transaction
- card1 - card6: payment card information, such as card type, card category, issue bank, country, etc.
- addr: address
- dist: distance
- P_ and (R__) emaildomain: purchaser and recipient email domain
- C1-C14: counting, such as how many addresses are found to be associated with the payment card, etc. The actual meaning is masked.
- D1-D15: timedelta, such as days between previous transaction, etc.
- M1-M9: match, such as names on card and address, etc.
- Vxxx: Vesta engineered rich features, including ranking, counting, and other entity relations.

( _Categorical Features_ )

- ProductCD
- card1 - card6
- addr1, addr2
- Pemaildomain Remaildomain
- M1 - M9


---

Identity Table

---

Variables in this table are identity information – network connection information (IP, ISP, Proxy, etc) and digital signature (UA/browser/os/version, etc) associated with transactions. They're collected by Vesta’s fraud protection system and digital security partners. 

(The field names are masked and pairwise dictionary will not be provided for privacy protection and contract agreement)

( _Categorical Features_ )

- DeviceType
- DeviceInfo
- id12 - id38