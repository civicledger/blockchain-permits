# Blockchain Permits
Civic Ledger have defined a standard for permits and licences that can be granted via the Ethereum blockchains 

## Terminology
Issuer:  The body in charge of granting entitlments.
Grant:  The process of 
Transfer
Redeem
Revoke
Reclaim

## Permit types
### Basic
```
Name
Type
Issuer
Terms URL (Should be SSL)
Icon URL
Start Time
Duration (How long the voucher is valid for.  0 means does not expire)
Transferable (Boolean)
Version
```

An example of a permit in solidity

```
    struct permit {
        address issuer;
        string type;
        string terms;
        uint256 income;
    }
```

C# DTO for a permit
```
public class Permit
{
  public String Type { get; set; }
}
```

www.civicledger.com
