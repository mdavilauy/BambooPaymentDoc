---
title: "Variables"
linkTitle: "Variables"
date: 2023-03-22T15:30:03-05:00
type: docs
Description: >
  Find the list of variables and codes available for Payouts integration.
weight: 20
---

## ID Types
The following table shows the availabe document types you need to configure in the parameter `payee.document.type`.

### Argentina
| Abbreviation | Document name | Individuals / Companies | Type | Length |
|:-:|---|---|:-:|:-:|
| CUIT | Unique Tax Identification Code | Companies | Numeric | 11 |
| CUIL | Unique Labor Identification Code | Individuals | Numeric | 11 |
| ID | National Identity Document | Individuals | Numeric | 7-9 |

### Brazil
| Abbreviation | Document name | Individuals / Companies | Type | Length |
|:-:|---|---|:-:|:-:|
| CPF | Individuals Registration | Individuals | Numeric | 11<sup>*</sup> |
| CNPJ | National Registry of Legal Entities | Company | Numeric | 14<sup>*</sup> |

<sup>*</sup> _Validate verifier-digits_

### Chile
| Abbreviation | Document name | Individuals / Companies | Type | Length |
|:-:|---|---|:-:|:-:|
| CI | Identity Card | Individuals | Numeric | 8 or 9 |
| RUN | Unique National Role | Individuals | Numeric | 8 or 9 |
| RUT | Individuals Tax Role | Individuals | Numeric | 8 or 9 |

### Colombia
| Abbreviation | Document name | Individuals / Companies | Type | Length |
|:-:|---|---|:-:|:-:|
| CC | Citizenship ID | Individuals | Numeric | Between 6 and 10 |
| CE | Immigration ID | Individuals | Numeric | Between 6 and 10 |
| NIT | Tax Identification Number | Companies | Numeric | Between 8 and 15 |

### Costa Rica
| Abbreviation | Document name | Individuals / Companies | Type | Length |
|:-:|---|---|:-:|:-:|
| CI | Identity Card | Individuals | Numeric | 9 |

### El Salvador
| Abbreviation | Document name | Individuals / Companies | Type | Length |
|:-:|---|---|:-:|:-:|
| DUI | Unique identity document | Individuals |  | Between 6 and 18 |

### Mexico
| Abbreviation | Document name | Individuals / Companies | Type | Length |
|:-:|---|---|:-:|:-:|
| CURP | Unique Population Registry Key | Individuals | | Between 8 and 18 |
| RFC | Federal Taxpayer Registry | Individuals and Companies | | Between 8 and 18 |
| IFE | Federal Electoral Institute | Individuals | | Between 8 and 18 |
| PASSPORT | International Travel Document | Individuals |  | Between 8 and 18 |
| RESIDENCIA | Document of foreigner residing in the country | Individuals |  | Between 8 and 18 |

### Nicaragua
| Abbreviation | Document name | Individuals / Companies | Type | Length |
|:-:|---|---|:-:|:-:|
| CI | Identity card | Individuals |  | Between 8 and 18 |

### Peru
| Abbreviation | Document name | Individuals / Companies | Type | Length |
|:-:|---|---|:-:|:-:|
| CE | Immigration ID | Individuals | Numeric | 9 |
| ID | National Identity Document | Individuals | Numeric<br><hr>Numeric or Alphanumeric | 8<br><hr>9 |
| PASSPORT | International Travel Document | Individuals | | Between 7 and 18 |
| RUC | Single Taxpayer Registry | Individuals and Companies | | 11 |

### Uruguay
| Abbreviation | Document name | Individuals / Companies | Type | Length |
|:-:|---|---|:-:|:-:|
| CI | Identity Card | Individuals | Numeric | Between 6 and 8 |
| DE | | Single | Numeric | |
| PASSPORT | International Travel Document | Individuals | Alphanumeric | |
| RUT | Single Tax Role | Individuals | Numeric | 12 |ç

## Codes
| Error code | Description |
|---|---|
| `200` | Success |
| `400` | Bad Request |
| `401` | Unauthorized |
| `409` | Conflict |